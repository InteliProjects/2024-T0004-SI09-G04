# Documentação da API

# Visão geral

Esta documentação abrange cinco arquivos de rotas da API, cada um focado em um aspecto específico da plataforma acadêmica e profissional. Os arquivos são:

1. **Gptw:** Focado nos dados de engajamento do programa Great Place to Work (GPTW).
2. **Stiba:** Destinado a manipular informações relacionadas ao relatório Stiba.
3. **GptwStiba:** Integra dados dos dois relatórios, GPTW e Stiba, para análises combinadas.
4. **Saude:** Gerencia informações e dados de saúde dos estudantes ou colaboradores.
5. **SaudeClima:** Combina dados de saúde com análises de clima organizacional.

Cada arquivo de rotas será documentado com os seguintes detalhes:

- **Objetivo e Escopo:** Uma breve introdução sobre o propósito do conjunto de rotas e seus principais objetivos dentro da plataforma.
- **Endpoints e Métodos:** Detalhamento de cada endpoint disponível no arquivo, incluindo o método HTTP (essa API em específico abrange apenas métodos GET), a rota específica, e uma descrição do que o endpoint faz.
- **Parâmetros e Corpos de Requisição:** Descrição dos parâmetros aceitos (se houver), tanto na URL quanto no corpo da requisição, com explicações sobre sua função e formato esperado.
- **Respostas e Códigos de Status:** Explicação das possíveis respostas para cada endpoint, incluindo os códigos de status HTTP e o formato dos dados retornados.
- **Exemplos de Requisições/Respostas:** Exemplos práticos de como fazer uma requisição a um endpoint e o que esperar em resposta, aumentando a clareza e facilitando a compreensão dos usuários da API.
- **Erros e Mensagens:** Descrição dos possíveis erros que podem ocorrer ao acessar os endpoints, incluindo códigos de status de erro e mensagens explicativas.
- **Guia de Testes:** Orientações sobre como testar os endpoints, incluindo ferramentas recomendadas e procedimentos para validar as respostas e o comportamento da API.
- **Ambiente de Testes:** Detalhes sobre o ambiente de testes disponível para experimentação com a API, incluindo como acessá-lo.

**Teste a API com Swagger UI**
A interface Swagger UI está disponível quando o servidor da API está em execução e pode ser acessada localmente em `http://localhost:5058/swagger`. Esta interface fornece uma maneira interativa de explorar os endpoints da API e testá-los em tempo real.

servers:

```jsx
url: [http://localhost:5058/](http://localhost:5058/)
description: Servidor de desenvolvimento local
```

Esta visão geral oferece uma base para a documentação compreensiva de todos os aspectos das rotas da API, assegurando que usuários e desenvolvedores possam entender facilmente e utilizar eficazmente os recursos disponibilizados.

## 2.1. GptwController

A `GptwController` é responsável por gerenciar as requisições relacionadas aos dados de engajamento do programa Great Place to Work (GPTW) dentro da plataforma. Esta documentação aborda os endpoints disponíveis, seus propósitos e os tipos de resposta esperados.

### Endpoints

### **Obter Dados de Engajamento GPTW**

- **Método HTTP:** GET
- **Rota:** `/api/gptw/engagement`
- **Descrição:** Retorna os dados de engajamento coletados pelo GPTW.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "year": 2023,
        "engagementPercent": 35
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### **Obter Médias das Pontuações por Pergunta**

- **Método HTTP:** GET
- **Rota:** `/api/gptw/average-score-question`
- **Descrição:** Fornece as médias das pontuações para cada pergunta feita no contexto do GPTW.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK
    - Exemplo de corpo de resposta:
    
    ```json
    [
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.11.5.2.2 - B-QGS/1",
        "averageScore": 100
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### **Obter Pontuação Média Geral**

- **Método HTTP:** GET
- **Rota:** `/api/gptw/general-average-score`
- **Descrição:** Apresenta a pontuação média geral obtida a partir de todas as respostas do GPTW.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK
    - Exemplo de corpo de resposta:

```json
{
  "averageScoreGeneral": 77.27868920032977
}
```

- **Resposta de erro:** HTTP 500 Erro interno do servidor

### **Obter as Cinco Maiores Pontuações por Pergunta**

- **Método HTTP:** GET
- **Rota:** `/api/gptw/top-five-question`
- **Descrição:** Retorna as cinco maiores pontuações alcançadas em perguntas específicas do GPTW.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.11.5.2.2 - B-QGS/1",
        "score": 100
      },
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.10.1.4.3.3 - B-OAP-3/1",
        "score": 100
      },
      {
        "pergunta": "Gestão Imediata",
        "escala": "VW4017797",
        "score": 100
      },
      {
        "pergunta": "Gestão Imediata",
        "escala": "VW4020577",
        "score": 100
      },
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.12.8.2 - B-RS*2",
        "score": 99.76666666666667
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### **Obter as Cinco Menores Pontuações por Pergunta**

- **Método HTTP:** GET
- **Rota:** `/api/gptw/bottom-five-question`
- **Descrição:** Fornece as cinco menores pontuações obtidas em perguntas específicas do GPTW.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "pergunta": "Médias",
        "escala": "Diferença (*****)",
        "score": 1
      },
      {
        "pergunta": "Médias",
        "escala": "Diferença (****)",
        "score": 4.5423728813559325
      },
      {
        "pergunta": "Em uma escala de 0 a 10, o quanto você indicaria essa empresa para um amigo trabalhar?",
        "escala": "1",
        "score": 16.25
      },
      {
        "pergunta": "Em uma escala de 0 a 10, o quanto você indicaria essa empresa para um amigo trabalhar?",
        "escala": "2",
        "score": 18.466666666666665
      },
      {
        "pergunta": "Em uma escala de 0 a 10, o quanto você indicaria essa empresa para um amigo trabalhar?",
        "escala": "3",
        "score": 32.666666666666664
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

**Tratamento de Erros**

Em caso de falhas internas ao tentar acessar qualquer um dos endpoints listados acima, o servidor retornará `HTTP 500 Internal Server Error`, indicando um erro interno do servidor.

**Logs de Erro**

A `GptwController` registra logs detalhados para facilitar a depuração e o monitoramento de erros, especialmente úteis ao investigar falhas no processamento das requisições.

## 2.2. GptwStibaController

A `GptwVsStibaController` gerencia as requisições relacionadas à análise comparativa entre os programas Great Place to Work (GPTW) e Stiba, fornecendo dados cruciais para a compreensão do engajamento e desempenho organizacional.

### Endpoints

1. **Obter Porcentagem de Respondentes Stiba**
- **Método HTTP:** GET
- **Rota:** `/api/gptwvsstiba/respondent-percentage`
- **Descrição:** Retorna a porcentagem de respondentes do Stiba.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK
    - **Exemplo de corpo de resposta**
    
    ```jsx
    94.81564080149994
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Dados de Engajamento GPTW

- **Método HTTP:** GET
- **Rota:** `/api/gptwvsstiba/engage-data`
- **Descrição:** Retorna a porcentagem de respondentes do GPTW.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com os dados de engajamento.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "year": 2023,
        "engagementPercent": 35
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Notas Gerais do Stiba

- **Método HTTP:** GET
- **Rota:** `/api/gptwvsstiba/stiba-notas`
- **Descrição:** Retorna as notas gerais do Stiba.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com as notas do Stiba.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "nota2023": 87.72948328267474,
      "nota2022": 88.12522796352584,
      "variacaoPercentual": -0.4490708166053246
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Dados Gerais do GPTW

- **Método HTTP:** GET
- **Rota:** `/api/gptwvsstiba/gptw-data`
- **Descrição:** Retorna dados gerais coletados do GPTW.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com os dados do GPTW.
    - **Exemplo do corpo de resposta:**
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Identificar Áreas de Pontuação Crítica

- **Método HTTP:** GET
- **Rota:** `/api/gptwvsstiba/critical-score-areas`
- **Descrição:** Calcula e retorna áreas com pontuações críticas para ação imediata.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com as áreas críticas identificadas.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "areaDescription": "B-OAM-4*2-9 AJUSTE...EM - 1 TURNO",
        "score": 69.9
      },
      {
        "areaDescription": "B-OFE-1 MONTAG...SICAO, LOG & FUP",
        "score": 69.7
      },
      {
        "areaDescription": "B-OPS-4-2 MANUT ...A211-2 1 TURNO",
        "score": 68.9
      },
      {
        "areaDescription": "B-OFD-2-4 TRY OU...OS - OFICINA 1",
        "score": 68.9
      },
      {
        "areaDescription": "B-OFE-1*2-5 TRY OUT 5",
        "score": 68.5
      },
      {
        "areaDescription": "B-TEI INFOTAINMENT & APP STORE",
        "score": 68.5
      },
      {
        "areaDescription": "B-QAM*2-2 Q.A. A...AO E TEAR DOWN",
        "score": 68.1
      },
      {
        "areaDescription": "B-OLI-3-10 EMBARQ...SALA DE NOTAS",
        "score": 67.8
      },
      {
        "areaDescription": "B-OFD*3-1 COMISS...E DISPOSITIVOS",
        "score": 67.6
      },
      {
        "areaDescription": "B-QV*1-1 ABSICH...UBATE - GRUPO 1",
        "score": 67.2
      },
      {
        "areaDescription": "B-OFE-1*1-3 MONTAGEM 3",
        "score": 66.2
      },
      {
        "areaDescription": "B-MLS VENDAS LAM",
        "score": 65.3
      },
      {
        "areaDescription": "B-SCP COMPRA...PECAS DE REPOSICAO",
        "score": 65.3
      },
      {
        "areaDescription": "B-OFE-1*2 TRY OUT",
        "score": 63.7
      },
      {
        "areaDescription": "B-OAP-1*1-6 FABRIC...RBOCK ANC 1T",
        "score": 63.5
      },
      {
        "areaDescription": "B-TAV-2-3-4 DURABI...TE - 3 TURNO",
        "score": 63.3
      },
      {
        "areaDescription": "B-DBO-1 GESTAO DE TECNOLOGIA",
        "score": 62.7
      },
      {
        "areaDescription": "B-OAM-3-1*12 MANUTE...A - 2 TURNO",
        "score": 62.7
      },
      {
        "areaDescription": "B-OCM-4*1-4 MONTAG...C.I E II -1T",
        "score": 60.9
      },
      {
        "areaDescription": "B-OFD-2-1 MONTAG...OS - OFICINA 1",
        "score": 60.4
      },
      {
        "areaDescription": "B-TXR-2-2 OFICINA DE AGREGADOS",
        "score": 58.7
      },
      {
        "areaDescription": "B-OAM-1*3-2 PRODUC...PARIA ANC 1T",
        "score": 56.5
      },
      {
        "areaDescription": "B-OFE-1*2-1 TRY OUT 1",
        "score": 55.2
      },
      {
        "areaDescription": "B-OFE-1*2-4 TRY OUT 4",
        "score": 50.3
      },
      {
        "areaDescription": "B-OFE-1*2-7 TRY OUT 7",
        "score": 46.2
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter as Cinco Maiores Pontuações do Stiba

- **Métodos HTTP:** GET para ambos `/api/gptwvsstiba/top-five-questions`
- **Descrição:** Retorna as cinco maiores pontuações de perguntas, respectivamente.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com as perguntas e suas pontuações.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "question": "Q20",
        "averageScore": 92.62019347037491
      },
      {
        "question": "Q14",
        "averageScore": 92.52128174123335
      },
      {
        "question": "Q23",
        "averageScore": 92.13446191051993
      },
      {
        "question": "Q22",
        "averageScore": 91.79189842805317
      },
      {
        "question": "Q19",
        "averageScore": 91.07871825876667
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter as Cinco Menores Pontuações do Stiba

- **Métodos HTTP:** GET para ambos `/api/gptwvsstiba/bottom-five-questions`
- **Descrição:** Retorna as cinco menores pontuações de perguntas, respectivamente.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com as perguntas e suas pontuações.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "question": "Q1",
        "averageScore": 80.05574365175339
      },
      {
        "question": "Q3",
        "averageScore": 81.40931076178967
      },
      {
        "question": "Q7",
        "averageScore": 81.68367593712213
      },
      {
        "question": "Q4",
        "averageScore": 82.65247883917777
      },
      {
        "question": "Q21",
        "averageScore": 84.20048367593726
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter as Cinco Maiores Pontuações do Gptw

- **Métodos HTTP:** GET para ambos `/api/gptwvsstiba/top-five-question-score`
- **Descrição:** Retorna as cinco maiores pontuações de perguntas, respectivamente.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com as perguntas e suas pontuações.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "pergunta": "Área de Trabalho",
        "escala": "1 - B",
        "score": 0
      },
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.9 - B-M",
        "score": 0
      },
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.9.3 - B-MP",
        "score": 0
      },
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.9.3.3 - B-MPS",
        "score": 0
      },
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.9.3.3.2 - B-MPS-1",
        "score": 0
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter as Cinco Menores Pontuações do Gptw

- **Métodos HTTP:** GET para ambos `/api/gptwvsstiba/bottom-five-questions-score`
- **Descrição:** Retorna as cinco menores pontuações de perguntas, respectivamente.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com as perguntas e suas pontuações.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "pergunta": "Você possui algum tipo de deficiência?",
        "escala": "1.3 - Intelectual",
        "score": 0
      },
      {
        "pergunta": "Estado em que trabalha",
        "escala": "CE-Ceará",
        "score": 0
      },
      {
        "pergunta": "Entre os gêneros abaixo, você se define como:",
        "escala": "Não-binário",
        "score": 0
      },
      {
        "pergunta": "Entre os gêneros abaixo, você se define como:",
        "escala": "Outros (gênero fluido, variável entre os espectros feminino e masculino)",
        "score": 0
      },
      {
        "pergunta": "Estado em que trabalha",
        "escala": "GO-Goiás",
        "score": 0
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Análise de Pareto para Perguntas Stiba

- **Método HTTP:** GET
- **Rota:** `/api/gptwvsstiba/pareto-stiba-questions`
- **Descrição:** Apresenta uma análise de Pareto para identificar perguntas críticas do Stiba.
- **Parâmetros:**
- **Resposta de Sucesso:** HTTP 200 OK com os resultados da análise de Pareto.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "question": "Q20",
        "averageScore": 92.62019347037491,
        "cumulativePercentage": 4.4509999402289955
      },
      {
        "question": "Q14",
        "averageScore": 92.52128174123335,
        "cumulativePercentage": 8.897246531495943
      },
      {
        "question": "Q23",
        "averageScore": 92.13446191051993,
        "cumulativePercentage": 13.324903925538472
      },
      {
        "question": "Q22",
        "averageScore": 91.79189842805317,
        "cumulativePercentage": 17.736098926415387
      },
      {
        "question": "Q19",
        "averageScore": 91.07871825876667,
        "cumulativePercentage": 22.113021002869164
      },
      {
        "question": "Q18",
        "averageScore": 90.58391777509088,
        "cumulativePercentage": 26.46616471263263
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Análise de Pareto para Perguntas Gptw

- **Método HTTP:** GET
- **Rota:** `/api/gptwvsstiba/pareto-questions-score`
- **Descrição:** Apresenta uma análise de Pareto para identificar perguntas críticas do Gptw.
- **Parâmetros:**
- **Resposta de Sucesso:** HTTP 200 OK com os resultados da análise de Pareto.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "question": "Gestão Imediata",
        "scale": "VW4020577",
        "score": 100,
        "cumulativePercentage": 0.10667912678867586
      },
      {
        "question": "Área de Trabalho",
        "scale": "1.10.1.4.3.3 - B-OAP-3/1",
        "score": 100,
        "cumulativePercentage": 0.21335825357735172
      },
      {
        "question": "Gestão Imediata",
        "scale": "VW4017797",
        "score": 100,
        "cumulativePercentage": 0.3200373803660276
      },
      {
        "question": "Área de Trabalho",
        "scale": "1.11.5.2.2 - B-QGS/1",
        "score": 100,
        "cumulativePercentage": 0.42671650715470344
      },
      {
        "question": "Área de Trabalho",
        "scale": "1.12.8.2 - B-RS*2",
        "score": 99.76666666666667,
        "cumulativePercentage": 0.5331467159808724
      },
      {
        "question": "Gestão Imediata",
        "scale": "VW1330403",
        "score": 99.71666666666667,
        "cumulativePercentage": 0.639523585243647
      },
      {
        "question": "Área de Trabalho",
        "scale": "1.10.3.2.1 - B-OEE-1",
        "score": 99.66666666666667,
        "cumulativePercentage": 0.7458471149430272
      },
      {
        "question": "Área de Trabalho",
        "scale": "1.10.7.3.2 - B-OPL*2",
        "score": 99.3,
        "cumulativePercentage": 0.8517794878441823
      },
      {
        "question": "Gestão Imediata",
        "scale": "VW2080761",
        "score": 99.15,
        "cumulativePercentage": 0.9575518420551545
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter as notas de todas as perguntas do Stiba

- **Método HTTP:** GET
- **Rota:** `/api/gptwvsstiba/stiba-questions-score`
- **Descrição:** Apresenta a lista com as médias de notas de todas as perguntas do Stiba
- **Parâmetros:**
- **Resposta de Sucesso:** HTTP 200 OK com as médias das notas.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "question": "Q20",
        "averageScore": 92.62019347037491
      },
      {
        "question": "Q14",
        "averageScore": 92.52128174123335
      },
      {
        "question": "Q23",
        "averageScore": 92.13446191051993
      },
      {
        "question": "Q22",
        "averageScore": 91.79189842805317
      },
      {
        "question": "Q19",
        "averageScore": 91.07871825876667
      },
      {
        "question": "Q18",
        "averageScore": 90.58391777509088
      },
      {
        "question": "Q8",
        "averageScore": 90.4590084643289
      },
      {
        "question": "Q17",
        "averageScore": 87.37871825876658
      },
      {
        "question": "Q10",
        "averageScore": 86.85441354292628
      },
      {
        "question": "Q11",
        "averageScore": 86.48270858524792
      },
      {
        "question": "Q2",
        "averageScore": 86.28814993954053
      },
      {
        "question": "Q6",
        "averageScore": 85.98222490931076
      },
      {
        "question": "Q16",
        "averageScore": 85.7830713422008
      },
      {
        "question": "Q9",
        "averageScore": 85.76021765417181
      },
      {
        "question": "Q24",
        "averageScore": 85.6575060532687
      },
      {
        "question": "Q15",
        "averageScore": 85.37896009673518
      },
      {
        "question": "Q13",
        "averageScore": 85.17920193470381
      },
      {
        "question": "Q5",
        "averageScore": 84.64522370012092
      },
      {
        "question": "Q12",
        "averageScore": 84.30350665054416
      },
      {
        "question": "Q21",
        "averageScore": 84.20048367593726
      },
      {
        "question": "Q4",
        "averageScore": 82.65247883917777
      },
      {
        "question": "Q7",
        "averageScore": 81.68367593712213
      },
      {
        "question": "Q3",
        "averageScore": 81.40931076178967
      },
      {
        "question": "Q1",
        "averageScore": 80.05574365175339
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter as notas de todas as perguntas do Gptw

- **Método HTTP:** GET
- **Rota:** `/api/gptwvsstiba/stiba-questions-score`
- **Descrição:** Apresenta a lista com as médias de notas de todas as perguntas do Stiba
- **Parâmetros:**
- **Resposta de Sucesso:** HTTP 200 OK com as médias das notas.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.11.5.2.2 - B-QGS/1",
        "averageScore": 100
      },
      {
        "pergunta": "Gestão Imediata",
        "escala": "VW4017797",
        "averageScore": 100
      },
      {
        "pergunta": "Gestão Imediata",
        "escala": "VW4020577",
        "averageScore": 100
      },
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.10.1.4.3.3 - B-OAP-3/1",
        "averageScore": 100
      },
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.12.8.2 - B-RS*2",
        "averageScore": 99.76666666666667
      },
      {
        "pergunta": "Gestão Imediata",
        "escala": "VW1330403",
        "averageScore": 99.71666666666667
      },
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.10.3.2.1 - B-OEE-1",
        "averageScore": 99.66666666666667
      },
      {
        "pergunta": "Área de Trabalho",
        "escala": "1.10.7.3.2 - B-OPL*2",
        "averageScore": 99.3
      }
     ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

Tratamento de Erros

Todos os endpoints são protegidos contra falhas inesperadas, retornando um código `HTTP 500` com uma mensagem de erro genérica indicando "Erro interno do servidor" em caso de exceções não tratadas.

Logs de Erro

Os erros são logados detalhadamente, incluindo a natureza do erro e o ponto exato de falha, facilitando a rápida identificação e resolução de problemas.

## 2.3. SaudeController

A `SaudeController` gerencia dados e informações relacionadas à saúde dos colaboradores, abrangendo desde atestados médicos até sessões de terapia. Esta documentação detalha os endpoints disponíveis, descrevendo suas funções, respostas esperadas e possíveis erros.

### Endpoints

### Obter Atestados do Mês Atual

- **Método HTTP:** GET
- **Rota:** `/api/saude/certificates/currentmonth/{month}`
- **Descrição:** Retorna os atestados médicos emitidos no mês especificado.
- **Parâmetros:**
    - `month`: Mês desejado para a consulta de atestados.
- **Resposta de Sucesso:** HTTP 200 OK com os dados dos atestados.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "month": "Jan",
      "atestados": 25,
      "difference": 0
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Dias Agrupados por Atestado

- **Método HTTP:** GET
- **Rota:** `/api/saude/aggregateddays/{month?}`
- **Descrição:** Agrega os dias cobertos por atestados, opcionalmente filtrados por mês.
- **Parâmetros:**
    - `month`: Mês para filtro dos atestados em valor de string (Jan, Fev, Mar, etc)
- **Resposta de Sucesso:** HTTP 200 OK ou 204 No Content se não houver dados.
    - **Exemplo de corpo de resposta:**
        
        ```json
        [
          {
            "month": "Jan",
            "totalAtestados": 25,
            "mediaDias": 2.7320000000000007
          },
          {
            "month": "Jan - Ago - Out - Nov",
            "totalAtestados": 4,
            "mediaDias": 33
          },
          {
            "month": "Jan - Fev",
            "totalAtestados": 16,
            "mediaDias": 11
          },
          {
            "month": "Jan - Fev - Jul - Ago - Out - Dez",
            "totalAtestados": 6,
            "mediaDias": 15
          },
          {
            "month": "Jan - Fev - Mai - Jul",
            "totalAtestados": 4,
            "mediaDias": 19
          },
        ]
        ```
        
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Média de Sessões do Zenklub

- **Método HTTP:** GET
- **Rota:** `/api/saude/zenklub/average`
- **Descrição:** Retorna a média de sessões de terapia no Zenklub.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com a média de sessões.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "averageSessionsPerPerson": 3.8542024013722127,
      "differenceFromLastYear": 0
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Média Mensal de Dias Abonados

- **Método HTTP:** GET
- **Rota:** `/api/saude/monthlyaverages/days`
- **Descrição:** Calcula a média mensal de dias abonados por saúde.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com a média mensal de dias.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "month": "Abr",
        "averageDaysOff": 3.5586206896551724
      },
      {
        "month": "Abr - Ago - Set",
        "averageDaysOff": 11
      },
      {
        "month": "Abr - Ago - Set - Nov",
        "averageDaysOff": 34
      },
      {
        "month": "Abr - Ago - Set - Out",
        "averageDaysOff": 39
      },
      {
        "month": "Abr - Jul",
        "averageDaysOff": 29
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Média de Dias Abonados por Localização

- **Método HTTP:** GET
- **Rota:** `/api/saude/averages/daysbylocation`
- **Descrição:** Retorna a média de dias abonados, organizada por localização.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com as médias por localização.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "month": "Abr",
        "location": "ANC",
        "averageDaysOff": 3.961904761904762
      },
      {
        "month": "Abr - Ago - Set",
        "location": "ANC",
        "averageDaysOff": 11
      },
      {
        "month": "Abr - Ago - Set - Nov",
        "location": "ANC",
        "averageDaysOff": 34
      },
      {
        "month": "Abr - Jun",
        "location": "ANC",
        "averageDaysOff": 1.4
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Principais Doenças

- **Método HTTP:** GET
- **Rota:** `/api/saude/diseases/top`
- **Descrição:** Lista as principais doenças registradas entre os colaboradores.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com a lista de doenças.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "disease": "Ansiedade",
        "quantity": 235
      },
      {
        "disease": null,
        "quantity": 150
      },
      {
        "disease": "Depressão",
        "quantity": 67
      },
      {
        "disease": "Transtornos Gerais",
        "quantity": 57
      },
      {
        "disease": "Dependência de Álcool e Drogas",
        "quantity": 22
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Principais Causas de Doenças

- **Método HTTP:** GET
- **Rota:** `/api/saude/diseasescauses/top`
- **Descrição:** Apresenta as principais causas das doenças registradas.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com as principais causas.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "disease": "Ansiedade",
        "cause": "Não identificado",
        "quantity": 169
      },
      {
        "disease": null,
        "cause": null,
        "quantity": 150
      },
      {
        "disease": "Transtornos Gerais",
        "cause": "Doença Mental Fiosiologica",
        "quantity": 32
      },
      {
        "disease": "Depressão",
        "cause": "Não identificado",
        "quantity": 31
      },
      {
        "disease": "Ansiedade",
        "cause": "Laboral e Profissional",
        "quantity": 28
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Cargos Mais Afetados

- **Método HTTP:** GET
- **Rota:** `/api/saude/roles/affected`
- **Descrição:** Identifica os cargos mais afetados por questões de saúde.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com a lista de cargos afetados.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "role": "AGILE COACH",
        "atestados2021": null,
        "atestados2022": null,
        "atestados2023": null
      },
      {
        "role": "PREPARADOR ENSAIOS SEGURANCA VEICULAR II",
        "atestados2021": null,
        "atestados2022": null,
        "atestados2023": null
      }
     ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Atestados por Diretoria

- **Método HTTP:** GET
- **Rota:** `/api/saude/directorates/atestados`
- **Descrição:** Fornece atestados médicos categorizados por diretoria.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com os atestados organizados por diretoria.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "directorate": "OPERAÇÕES",
        "atestados": 805
      },
      {
        "directorate": "QA",
        "atestados": 44
      },
      {
        "directorate": "RH",
        "atestados": 39
      },
      {
        "directorate": "DESENVOLVIMENTO PRODUTO",
        "atestados": 38
      },
      {
        "directorate": "COMPRAS",
        "atestados": 12
      },
      {
        "directorate": "FINANÇAS",
        "atestados": 8
      },
      {
        "directorate": "ENGENHARIA DE MANUFATURA",
        "atestados": 6
      },
      {
        "directorate": "V&M",
        "atestados": 4
      },
      {
        "directorate": "PÓS-VENDAS",
        "atestados": 4
      },
      {
        "directorate": "TI",
        "atestados": 3
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Sessões do Zenklub por Colaborador

- **Método HTTP:** GET
- **Rota:** `/api/saude/zenklub/sessionsperemployee`
- **Descrição:** Retorna o número de sessões do Zenklub por colaborador.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com o número de sessões por colaborador.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "month": "1",
        "location": "Anchieta",
        "employeeCount": 92,
        "totalSessions": 297,
        "sessionsPerEmployee": 3.2282608695652173
      },
      {
        "month": "1",
        "location": "Curitiba",
        "employeeCount": 7,
        "totalSessions": 17,
        "sessionsPerEmployee": 2.4285714285714284
      },
      {
        "month": "1",
        "location": "São Carlos",
        "employeeCount": 3,
        "totalSessions": 6,
        "sessionsPerEmployee": 2
      },
      {
        "month": "1",
        "location": "Taubate",
        "employeeCount": 16,
        "totalSessions": 41,
        "sessionsPerEmployee": 2.5625
      },
      {
        "month": "2",
        "location": "Anchieta",
        "employeeCount": 109,
        "totalSessions": 334,
        "sessionsPerEmployee": 3.0642201834862384
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Tendências de CID por Mês

- **Método HTTP:** GET
- **Rota:** `/api/saude/cidstrends`
- **Descrição:** Apresenta as tendências de Classificação Internacional de Doenças (CID) por mês.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com as tendências de CID.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "Abr": {
        "Misto - Pessoal e Profissional": 3,
        "Doença Mental Fiosiologica - Bipolaridade": 1,
        "Laboral e Profissional - Sobrecarga": 2,
        "Laboral e Profissional - Outros": 1,
        "Laboral e Profissional - Excesso de demanda": 1,
        "Não identificado": 10,
        "Dependencia Química - Drogas": 2,
        "Laboral e Profissional  - Liderança": 1,
        "Laboral e Profissional - Layoff": 1,
        "Contexto Familiar e Relacionamento - Outros": 4,
        "Laboral e Profissional - Mudança de Função": 2,
        "Doença Mental Fiosiologica - Outros": 1
      },
      "Abr - Ago - Set": {
        "Não identificado": 1
      },
      "Abr - Ago - Set - Nov": {
        "Laboral e Profissional - Mudança de Função": 1
      },
      "Abr - Ago - Set - Out": {
        "Contexto Familiar e Relacionamento - Outros": 1
      },
      "Abr - Jul": {
        "Contexto Familiar e Relacionamento - Outros": 1
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Atestados por Sessão do Zenklub

- **Método HTTP:** GET
- **Rota:** `/api/saude/sessions/certificates`
- **Descrição:** Calcula e retorna os atestados associados a sessões do Zenklub.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com os atestados por sessão.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "atestados": 1,
        "sessions": 23
      },
      {
        "atestados": 14,
        "sessions": 72
      },
      {
        "atestados": 1,
        "sessions": 24
      },
      {
        "atestados": 1,
        "sessions": 11
      },
      {
        "atestados": 1031,
        "sessions": 0
      },
      {
        "atestados": 1,
        "sessions": 29
      },
      {
        "atestados": 86,
        "sessions": 260
      },
      {
        "atestados": 1,
        "sessions": 30
      },
      {
        "atestados": 1,
        "sessions": 41
      },
      {
        "atestados": 1,
        "sessions": 21
      },
      {
        "atestados": 97,
        "sessions": 222
      },
      {
        "atestados": 2,
        "sessions": 34
      },
      {
        "atestados": 1,
        "sessions": 20
      },
      {
        "atestados": 3,
        "sessions": 9
      },
      {
        "atestados": 4,
        "sessions": 52
      },
      {
        "atestados": 1,
        "sessions": 33
      },
      {
        "atestados": 21,
        "sessions": 98
      },
      {
        "atestados": 111,
        "sessions": 90
      },
      {
        "atestados": 46,
        "sessions": 160
      },
      {
        "atestados": 93,
        "sessions": 156
      },
      {
        "atestados": 3,
        "sessions": 16
      },
      {
        "atestados": 23,
        "sessions": 84
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

## Tratamento de Erros

Os erros são cuidadosamente logados, e qualquer falha interna resulta em um código `HTTP 500`, acompanhado por uma mensagem de erro genérica para evitar a divulgação de informações sensíveis.

## 2.4. ZenklubController

A `ZenklubController` foca na análise e relatórios de bem-estar e engajamento fornecidos através das sessões do Zenklub, bem como em índices de satisfação e engajamento. Esta documentação detalha os endpoints disponíveis, descrevendo suas funções, respostas esperadas e possíveis erros.

## Endpoints

### Obter Dias de Atestado

- **Método HTTP:** GET
- **Rota:** `/api/zenklub/certificatedays/{month?}`
- **Descrição:** Calcula e retorna métricas agregadas de dias de atestado, opcionalmente filtradas por mês.
- **Parâmetros:**
    - `month`: Mês para a consulta, no formato string "Jan".
- **Resposta de Sucesso:** HTTP 200 OK com as métricas agregadas de dias de atestado.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "mediaDias": 5.190476190476191,
      "percentageChange": 0
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Métricas de Sessões

- **Método HTTP:** GET
- **Rota:** `/api/zenklub/sessions/{month}`
- **Descrição:** Retorna métricas das sessões realizadas em um mês específico.
- **Parâmetros:**
    - `month`: Mês para a consulta, como um inteiro “12”.
- **Resposta de Sucesso:** HTTP 200 OK com as métricas das sessões do mês especificado.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "currentSessions": 0,
      "sessions": 730,
      "difference": -4.57516339869281
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Índice de Saúde e Satisfação

- **Método HTTP:** GET
- **Rota:** `/api/zenklub/healthsatisfactionindex`
- **Descrição:** Calcula e retorna o índice de saúde e satisfação com base nas sessões do Zenklub.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com o índice de saúde e satisfação.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "iseIndex": 77
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Índice de Saúde e Satisfação do Stiba

- **Método HTTP:** GET
- **Rota:** `/api/zenklub/healthsatisfactionindexstiba`
- **Descrição:** Retorna o índice de saúde e satisfação derivado das análises do Stiba.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com o índice específico do Stiba.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "iseIndex": 86.50362756952842
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Índice de Engajamento

- **Método HTTP:** GET
- **Rota:** `/api/zenklub/engagementindex`
- **Descrição:** Fornece o índice de engajamento calculado a partir das sessões do Zenklub.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com o índice de engajamento.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "iseIndex": 77
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Índice de Engajamento do Stiba

- **Método HTTP:** GET
- **Rota:** `/api/zenklub/stibaengagementindex`
- **Descrição:** Retorna o índice de engajamento calculado com base nos dados do Stiba.
- **Parâmetros:** Não há
- **Resposta de Sucesso:** HTTP 200 OK com o índice de engajamento do Stiba.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "iseIndex": 86.50362756952842
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

## Tratamento de Erros

Qualquer falha interna durante a execução dos endpoints resultará em um código `HTTP 500`, indicando erro interno do servidor, acompanhado por uma mensagem genérica para evitar a exposição de detalhes sensíveis do sistema.

## 2.5. StibaController

A `StibaController` é responsável pela gestão e análise dos dados coletados através de pesquisas do programa Stiba, incluindo taxas de resposta, pontuações das pesquisas e métricas específicas de comprometimento, responsabilidade, confiabilidade, coragem e entusiasmo. Esta documentação descreve cada endpoint disponível, seus propósitos, respostas esperadas e possíveis erros.

### Endpoints

### Obter Taxa de Resposta

- **Método HTTP:** GET
- **Rota:** `/api/stiba/responserate`
- **Descrição:** Retorna a taxa de resposta geral das pesquisas Stiba.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com a taxa de resposta.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "percentageRespondents": 94.6810287241149,
      "totalCollaborators": 12
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Pontuações da Pesquisa

- **Método HTTP:** GET
- **Rota:** `/api/stiba/surveyscores`
- **Descrição:** Fornece as pontuações obtidas nas pesquisas Stiba.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com as pontuações das pesquisas.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "score2023": 86.50362756952842
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Pontuações da Pesquisa por Diretoria

- **Método HTTP:** GET
- **Rota:** `/api/stiba/surveyscoresdirectory`
- **Descrição:** Retorna um diretório com as pontuações detalhadas das pesquisas Stiba.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com o diretório de pontuações.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "directory": "B-OTM-2*3-3 AUFBAU POLO - 2 TURNO",
        "score2023": 89.5
      },
      {
        "directory": "B-OCM-2*2-6 ARMACA...ACAO CUR -3T",
        "score2023": 94.4
      },
      {
        "directory": "B-OAM-3*3-2V PREPAR...R - 2 TURNO",
        "score2023": 89.3
      },
      {
        "directory": "B-SN NOVOS ... DE PECAS COMPRADAS",
        "score2023": 88.8
      },
      {
        "directory": "B-VPS DESENV... CANAIS & PRODUTOS",
        "score2023": 85.6
      },
      {
        "directory": "B-TAV-4-2-1 OFICIN...O COMPLETO 1",
        "score2023": 97.7
      },
      {
        "directory": "B-SEE COMPRA...&SIST INFOTAINMENT",
        "score2023": 91.7
      },
      {
        "directory": "B-OLI-3*1 TRANSP...ANC/TBT/SANTOS",
        "score2023": 87.3
       }
     ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Pontuação de Comprometimento

- **Método HTTP:** GET
- **Rota:** `/api/stiba/commitmentscore`
- **Descrição:** Apresenta a pontuação de comprometimento calculada a partir das pesquisas Stiba.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com a pontuação de comprometimento.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "scoreCompromisso": 90.4590084643289
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Pontuação de Responsabilidade

- **Método HTTP:** GET
- **Rota:** `/api/stiba/responsabilityscore`
- **Descrição:** Fornece a pontuação de responsabilidade coletada nas pesquisas.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com a pontuação de responsabilidade.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "scoreResponsabilidade": 92.13446191051995
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Pontuação de Confiabilidade

- **Método HTTP:** GET
- **Rota:** `/api/stiba/confiabilityscore`
- **Descrição:** Retorna a pontuação de confiabilidade derivada das respostas das pesquisas.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com a pontuação de confiabilidade.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "scoreConfianca": 92.52128174123338
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Pontuação de Coragem

- **Método HTTP:** GET
- **Rota:** `/api/stiba/couragescore`
- **Descrição:** Apresenta a pontuação de coragem baseada nas respostas das pesquisas Stiba.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com a pontuação de coragem.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "scoreCoragem": 81.68367593712213
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Pontuação de Entusiasmo

- **Método HTTP:** GET
- **Rota:** `/api/stiba/entusiasmscore`
- **Descrição:** Fornece a pontuação de entusiasmo obtida através das pesquisas Stiba.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com a pontuação de entusiasmo.
    - **Exemplo de corpo de resposta:**
    
    ```json
    {
      "scoreEntusiasmo": 0
    }
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Top Cinco Perguntas

- **Método HTTP:** GET
- **Rota:** `/api/stiba/top-five-questions`
- **Descrição:** Retorna as cinco perguntas baseadas nas pontuações mais altas.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com as cinco principais perguntas.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "question": "Q20",
        "averageScore": 92.6201934703749
      },
      {
        "question": "Q14",
        "averageScore": 92.5212817412334
      },
      {
        "question": "Q23",
        "averageScore": 92.1344619105199
      },
      {
        "question": "Q22",
        "averageScore": 91.7918984280532
      },
      {
        "question": "Q19",
        "averageScore": 91.0787182587667
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Cinco Piores Perguntas

- **Método HTTP:** GET
- **Rota:** `/api/stiba/bottom-five-questions`
- **Descrição:** Apresenta as cinco piores perguntas com base nas pontuações mais baixas.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com as cinco piores perguntas.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "question": "Q1",
        "averageScore": 80.05574365175339
      },
      {
        "question": "Q3",
        "averageScore": 81.40931076178967
      },
      {
        "question": "Q7",
        "averageScore": 81.68367593712213
      },
      {
        "question": "Q4",
        "averageScore": 82.65247883917777
      },
      {
        "question": "Q21",
        "averageScore": 84.20048367593726
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

### Obter Todas as Notas por Perguntas por Diretoria

- **Método HTTP:** GET
- **Rota:** `/api/stiba/all-directory-questions`
- **Descrição:** Fornece todas as notas das perguntas da pesquisa Stiba por diretoria.
- **Parâmetros**: Não há
- **Resposta de Sucesso:** HTTP 200 OK com todas as perguntas do diretório.
    - **Exemplo de corpo de resposta:**
    
    ```json
    [
      {
        "descricaoUO": "Volkswagen do Brasil",
        "q1": 80.4,
        "q2": 85.4,
        "q3": 81.1,
        "q4": 81.6,
        "q5": 83.8,
        "q6": 84.9,
        "q7": 80,
        "q8": 89.6,
        "q9": 84.8,
        "q10": 85.6,
        "q11": 85.9,
        "q12": 82.7,
        "q13": 84.7,
        "q14": 91.4,
        "q15": 84.1,
        "q16": 83.7,
        "q17": 85.6,
        "q18": 90.5,
        "q19": 90.9,
        "q20": 92.9,
        "q21": 83,
        "q22": 91.9,
        "q23": 90.6,
        "q24": 84.6
      },
      {
        "descricaoUO": "B EXECUTIVE CHAIRMAN REGIAO SAM",
        "q1": 80.3,
        "q2": 85.4,
        "q3": 81.1,
        "q4": 81.6,
        "q5": 83.8,
        "q6": 84.9,
        "q7": 80,
        "q8": 89.6,
        "q9": 84.8,
        "q10": 85.6,
        "q11": 85.9,
        "q12": 82.7,
        "q13": 84.7,
        "q14": 91.4,
        "q15": 84.1,
        "q16": 83.7,
        "q17": 85.6,
        "q18": 90.5,
        "q19": 90.9,
        "q20": 92.9,
        "q21": 83,
        "q22": 91.9,
        "q23": 90.6,
        "q24": 84.6
      }
    ]
    ```
    
- **Resposta de erro:** HTTP 500 Erro interno do servidor

**Tratamento de Erros**

Qualquer erro interno resultará em um código `HTTP 500`, indicando um erro no servidor, acompanhado por uma mensagem genérica para evitar a exposição de informações sensíveis.