# Programação

# 1. Diagramas

Os diagramas C4, criados por Simon Brown, são uma técnica de notação gráfica projetada para representar a arquitetura de sistemas de software. C4 é uma abreviação para Contexto, Container, Componente e Código - os quatro níveis desse modelo.

Por tanto, justifica-se a utilização dos diagramas, dado que, o modelo C4 é uma ferramenta para visualizar o estado atual de um sistema e planejar o estado desejado.

## 1.1 Diagrama de Casos de Uso

O Diagrama de Caso de Uso é mais uma ferramenta de modelagem UML para a concepção de soluções. Ele representa as interações entre um sistema e seus usuários ou outros sistemas, definindo quais são as diferentes maneiras que os usuários podem interagir com o sistema para atingir seus objetivos. O diagrama mostra atores externos e os casos de uso do sistema, assim como as relações entre eles.

No diagrama desenvolvido nessa Sprint 1, o principal (e único) ator externo é o CEO da Volkswagen Brasil, o sistema abordado é o Dashboard Interativo que estamos desenvolvendo neste módulo. As interações com o sistema consistem em autenticações de usuário, exploração de dados e interatividade e gestão de perfil, respectivamente.

1. **Ator**: O ator principal neste diagrama é o **CEO**.
2. **Casos de Uso**:
    - **Fazer Login**: Este é o processo pelo qual o CEO acessa o sistema. Isso inclui a verificação da senha, que é uma parte necessária do processo de login. Se a verificação da senha falhar, o sistema exibirá um erro de login.
    - **Selecionar Relatórios e Segmentos**: Este caso de uso descreve a capacidade do CEO de selecionar diferentes relatórios e segmentos no sistema.
    - **Visualizar Dados e Infográficos**: Este caso de uso permite que o CEO visualize dados e infográficos no sistema.
    - **Interagir com Infográficos**: Este caso de uso descreve a interação do CEO com os infográficos disponíveis no sistema.
    - **Aplicar filtros e buscas para validação de dados**: Este caso de uso permite que o CEO aplique filtros e realize buscas para validar os dados. Isso inclui a verificação de correspondência no banco de dados, que é uma parte necessária do processo de aplicação de filtros e buscas. Se a verificação de correspondência falhar, o sistema exibirá um erro de busca.
    - **Alterar informações do perfil cadastrado**: Este caso de uso descreve a capacidade do CEO de alterar as informações do perfil cadastrado no sistema.
      
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/480dfc86-a3a2-4d29-a815-28591926629d)<br><br> 
**Figura 1:** Diagrama caso de Uso <br> 
**Fonte**: Elaboração própria

## 1.2 Diagrama de componentes

Um diagrama de componentes é uma representação visual da estrutura e organização dos componentes de um sistema de software. Ele descreve como os diferentes módulos, bibliotecas, serviços e subsistemas se relacionam entre si para formar o sistema completo. 

1. **Componentes**:
    - Os componentes são unidades lógicas e independentes de funcionalidade dentro de um sistema. Cada componente tem uma responsabilidade específica e oferece interfaces bem definidas para interagir com outros componentes.
2. **Relações entre Componentes**:
    - No diagrama de componentes, as relações entre os componentes são representadas por linhas ou setas.
    - As relações mais comuns são:
        - **Dependência**: Um componente depende de outro para funcionar corretamente.
        - **Associação**: Indica que dois componentes estão associados de alguma forma.
        - **Uso**: Um componente usa outro para realizar uma tarefa específica.
        - **Herança/Implementação**: Quando um componente herda funcionalidades de outro (por exemplo, uma classe que implementa uma interface).
3. **Interfaces**:
    - As interfaces definem como os componentes se comunicam entre si. No diagrama, as interfaces são representadas como pontos de conexão entre os componentes.

No sistema desenvolvido, a coleta eficiente de dados é fundamental para garantir a qualidade das análises subsequentes. Nesse sentido, a API .NET Core desempenha um papel central, representada como um componente no diagrama. A API estabelece uma conexão direta com o banco de dados, assegurando uma coleta de dados ágil e confiável. É imperativo que a API seja bem definida e implementada, proporcionando uma base sólida para o processamento dos dados.

Além da coleta, o tratamento e armazenamento dos dados analíticos são etapas críticas no processo. O componente de banco de dados, relacionado a essa fase, deve ser otimizado para consultas analíticas, garantindo eficiência e desempenho. Antes do armazenamento, os dados passam por processos de tratamento para garantir sua integridade e prepará-los para análises posteriores.

Após o tratamento dos dados, entra em cena a análise estatística e a geração de insights. Embora essa etapa não esteja explicitamente representada no diagrama, é uma parte essencial do processo. As análises estatísticas são realizadas para extrair insights valiosos dos dados, contribuindo significativamente para as tomadas de decisão. Os insights gerados são cruciais para fornecer uma compreensão mais profunda dos dados coletados.

A apresentação dos resultados no dashboard, desenvolvido com Angular e TypeScript, é a interface final para os usuários interagirem com os dados. O componente de front-end está diretamente ligado a essa etapa, permitindo uma visualização clara e compreensível dos insights e dados analíticos. O dashboard proporciona uma experiência amigável e interativa para os usuários explorarem os resultados das análises de maneira eficaz.

Por fim, a segurança e autorização na API .NET Core são aspectos críticos a serem considerados. Embora não explicitamente representadas no diagrama, são fundamentais para proteger os dados e garantir o acesso adequado aos usuários. A implementação de autenticação e autorização robustas, possivelmente utilizando Keycloak, é essencial para manter a integridade e segurança do sistema de análise de dados.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/50088287-ccfb-47b1-8d8f-aea73568d375)<br> 
<br> 
**Figura 2:** Diagrama Componentes <br> 
**Fonte:** Elaboração própria <br> 
<br> 

## 1.3 Diagrama de conteiner

O Diagrama de Container é uma ferramenta de modelagem UML que consiste em representar a arquitetura de software em termos de containers, mostrando suas interações e os atores externos envolvidos. Esse aspecto da modelagem destaca também quais tecnologias em específico serão utilizadas em cada container. Com esse tipo de diagrama é possível ter  uma visão de alto nível da infraestrutura do sistema, ajudando a entender como os componentes estão distribuídos e como eles se relacionam para fornecer funcionalidades específicas.

No diagrama desenvolvido nessa Sprint 1, o ator externo é o CEO da Volkswagen Brasil, ficando no topo do diagrama. Existem 4 containers em sequência, compondo o front-end (TypeScript e Angular) que está ligado ao back-end (C# e .NET) que está ligado aos dois bancos de dados (PostgreSQL). Esse conjunto de containers e suas relações representam o sistema que será desenvolvido, além de informar em detalhes as tecnologias aplicadas.

1. **Usuário**: O usuário principal neste diagrama é o **CEO da Volkswagen Brasil**.
2. **Aplicações**:
    - **Aplicação Web**: Esta é uma aplicação web construída com Angular e Typescript. Ela fornece todas as funcionalidades do Dashboard ao usuário através do navegador web.
    - **Aplicação da API**: Esta é uma aplicação API construída com C# e .NET. Ela fornece comunicação segura e eficiente entre sistemas, suportando integração transparente com o frontend.
3. **Bancos de Dados**:
    - **Banco de Dados 1**: Este é um contêiner PostgreSQL que armazena todos os dados brutos fornecidos pelo cliente.
    - **Banco de Dados 2**: Este é outro contêiner PostgreSQL que registra logs a partir das interações com o sistema.
4. **Interações**:
    - O usuário interage com ambas as aplicações.
    - Ambas as aplicações leem e escrevem, nos respectivos bancos de dados.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/40273c40-9f43-4791-a730-8c059dacc4ab)
<br> 
<br> 
**Figura 3:** Diagrama de Container <br> 
**Fonte:** Elaboração própria <br> 
<br> 

## 1.4 Diagrama de classes

Um diagrama de classes é um tipo de diagrama estrutural estático que descreve a estrutura de um sistema mostrando as classes do sistema, seus atributos, métodos e as relações entre os objetos.

As classes são representadas por retângulos que contêm o nome da classe na parte superior, seguido por seus atributos e operações. As linhas que conectam diferentes retângulos indicam as relações entre eles.

### Back-end

O back-end consiste em classes como **`Usuario`**, **`Autenticador`** e **`BancoDeDados`**.

- A classe **`Usuario`** tem atributos como **`nomeUsuario`**, **`codigoConfirmacao`** e métodos como **`obterLista()`** e **`verificarCodigoConfirmacao(codigo: String)`**.
- A classe **`Autenticador`** herda de **`Usuario`** e tem um método **`autenticar(usuario: Usuario, codigo: String)`**.
- A classe **`BancoDeDados`** tem um método **`adicionarScanResultado(scanResultado, Usuario)`**.

### Front-end

O front-end é representado pelas classes **`InterfaceUsuario`**, **`NavBar`**, **`Filtro`**, **`ResultadoDados`**, **`ResultadoGrafico`** e **`MonitoramentoDados`**.

- A classe **`InterfaceUsuario`** tem atributos como **`nomeUsuario`**, **`codigoConfirmacao`** e métodos como **`obterLista()`** e **`verificarCodigoConfirmacao(codigo: String)`**.
- A classe **`NavBar`** tem atributos como **`usuario`**, **`dashboard`** e métodos como **`acessar(dash: Dashboard)`**, **`processar(filtro: Filtro)`** e **`apresentarResultado()`**.
- A classe **`Filtro`** tem atributos como **`campo`**, **`tipo`**, **`operador`** e métodos como **`obterCampos()`**, **`obterTipos()`** e **`obterOperadores()`**.
- As classes **`ResultadoDados`**, **`ResultadoGrafico`** e **`MonitoramentoDados`** representam diferentes componentes da interface do usuário e cada uma delas tem um método **`gerarResultado()`** para gerar os resultados correspondentes.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/67f0de6c-2323-44f8-ba5d-1cf3618f0008)
<br> 
<br> 
**Figura 4:** Diagrama de Classe <br> 
**Fonte:** Elaboração própria <br> 
<br> 

# 2. API de Integração 

O Modelo-Visão-Controlador (MVC) é um padrão de arquitetura de software amplamente utilizado na concepção e desenvolvimento de aplicativos da web. Ele divide uma aplicação em três componentes principais: Model, View e Controller. 

O Modelo é a camada responsável por representar os dados e toda a lógica de negócios da aplicação em questão. Ele é responsável por encapsular a lógica de manipulação dos dados, trazer os cálculos, validações e todas as interações com o banco de dados. 

Já a View, é a camada responsável por apresentar a interface do usuário ao usuário final. Ela exibe todas as informações fornecidas pelo Modelo de uma forma que seja compreensível e interativa para o usuário. Dessa forma, facilitando e garantindo uma comunicação eficiente entre todas as partes para comunicar de forma clara todos os dados e funcionalidades. 

O Controlador é a camada intermediária entre o Modelo e a Visão. Ele atua como um mediador entre as ações do usuário na interface do usuário e a lógica de negócios do Modelo. Quando o usuário interage com a aplicação, por exemplo, enviando um formulário, clicando em um botão, etc., o Controlador recebe essas interações, processa os dados necessários e decide como responder, geralmente atualizando o Modelo e/ou selecionando a Visão apropriada para exibir.

No contexto do nosso projeto, tomamos a decisão consciente de não utilizar views por uma variedade de razões. Em primeiro lugar, a essência da nossa aplicação foi moldada para oferecer endpoints que permitem interações programáticas com outros sistemas ou serviços, em detrimento de uma interface visual direta com o usuário. Considerando que os dados fundamentais do projeto são provenientes de um banco de dados, não consideramos ideal que os usuários tenham acesso direto a essas informações. Essa abordagem nos permitiu adotar uma estratégia centrada em API, simplificando a arquitetura e priorizando a entrega eficaz de dados. Ao estabelecer um sistema de API, viabilizamos uma comunicação fluida entre diferentes sistemas, serviços ou componentes, promovendo a troca de dados e funcionalidades e garantindo a interoperabilidade entre as partes envolvidas.

Além disso, ao evitar a criação de views, conseguimos estabelecer uma clara separação de responsabilidades na aplicação, mantendo a lógica de negócios e os serviços de backend totalmente independentes da camada de apresentação. Essa abordagem proporcionou não apenas uma maior flexibilidade e reutilização do código, mas também facilitou integrações futuras com uma variedade de clientes ou interfaces de usuário. Em resumo, a decisão de não adotar views foi alinhada com os objetivos fundamentais do projeto, assegurando uma arquitetura mais eficiente, modular e orientada para a interoperabilidade.







# 2.1 Estruturação das pastas 


Para a estruturação do nosso Backend estamos trabalhando com 4 principais repositórios: 
- Kombi.Dashboard.Model
- Kombi.Dashboard.Repository
- Kombi.Dashboard.Services
- Kombi.Dashboard.Teste 
- Kombi.Dashboard.WebApi 

Essa estruturação foi criada para facilitar o armazenamento das informações, e garantir uma fluidez das informações e dados. 

O repositório **Kombi.Dashboard.Model**, é responsável por conter as configurações relacionadas à gestão de pacotes NuGet e compilação de projetos C#. Ela é vista como uma parte crucial do backend da aplicação, responsável pela definição de modelos de dados e lógica de negócios. Ela contém dependências do projeto, como as versões dos pacotes NuGet a serem restauradas e as configurações de restauração. Ela define onde os pacotes estão armazenados, os caminhos para os arquivos


A pasta **Kombi.Dashboard.Repository** contém arquivos relacionados à manipulação de dados no contexto do projeto. 

O primeiro arquivo define as classes *CidsModel*, e representa um modelo de dados para lidar com informações relacionadas a CIDs (Classificação Internacional de Doenças). A classe contém propriedades que representam os diferentes atributos como: unidade, diretoria, dias de afastamento, etc. Logo após isso, estamos trabalhando com um arquivo chamado *CidsRepository.cs*, que implementa a interface ICidsRepository e fornece as operações necessárias para interagir com os dados das CIDs.Contendo métodos para recuperar, inserir, atualizar e excluir informações das CIDs de um banco de dados já armazenado. Dessa forma, é vista como uma pasta responsável pela definição de modelos de dados e pela implementação de classes para manipulação de dados relacionados às CIDs. 

<br> 

![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/repclasse.png)

<br> 

**Figura 5:** Cids Repository - classes <br> 
**Fonte:** Elaboração própria <br> 
<br>  

A pasta **Kombi.Dashboard.Services** contém arquivos relacionados aos serviços da aplicação, responsáveis por interagir com os dados e fornecer funcionalidades para outras partes do sistema. 


O arquivo *CidsService.cs* contém a implementação da classe CidsService, que é responsável por fornecer operações relacionadas às CIDs. Por exemplo, ele possui métodos para recuperar todas as CIDs, obter uma CID específica por ID e outros métodos relacionados ao gerenciamento de CIDs.

<br> 

![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/implementacao.png)

<br> 
<br> 

**Figura 6:** Implementação da classe CidsService <br> 
**Fonte:** Elaboração própria <br> 
<br>  

Já o arquivo *ICidsService.cs*, define a interface ICidsService, que estabelece os contratos para os serviços relacionados às CIDs. Ele é responsável por declarar os métodos que os serviços devem implementar, tais como a obtenção de CIDs por ID etc. 

Ou seja, esses arquivos fornecem a base para o desenvolvimento e gerenciamento dos serviços relacionados às CIDs na aplicação. O CidsService é responsável por implementar a lógica de negócios relacionada às CIDs, enquanto a interface ICidsService estabelece os contratos que os serviços devem cumprir. 



A pasta **Kombi.Dashboard.Teste** foi criada com o intuito de armazenar os arquivos relacionados aos testes unitários do projeto.

O arquivo *GlobalUsings.cs*, contém uma declaração global de using que importa o namespace NUnit.Framework. Dessa forma, permite que todos os arquivos no projeto tenham acesso aos tipos e membros definidos neste namespace sem a necessidade de importá-lo explicitamente em cada arquivo.

O arquivo *UnitTest1.cs*, contém a classe Tests, que é uma classe de teste unitário. A classe usa o framework de teste NUnit (NUnit.Framework) para escrever e executar os testes. O método Setup é executado antes de cada método de teste[Test]) e ele é usado para configurar o ambiente de teste. O método TestMethodToTest é um método de teste que verifica se o método MethodToTest da classe CidsService retorna o valor esperado quando chamado com um modelo de CID específico. Ou seja, um método que recebe um modelo de CID como entrada e retorna um número inteiro. Consequentemente, são responsáveis por configurar o ambiente de teste, definir casos de teste e verificar se o código funciona conforme o esperado.
<br> 

![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/Classe.png)

**Figura 7:** Classe de testes <br> 
**Fonte:** Elaboração própria <br> 
<br>  


A pasta **Kombi.Dashboard.WebAPI**, contém os arquivos relacionados à API da página web do projeto. 

O primeiro arquivo é o *Kombi.Dashboard.WebApi.csproj*, que contém dados que especificam como o projeto deve ser construído, suas dependências e outras configurações importantes. Aqui estão algumas das configurações importantes neste arquivo:
- TargetFramework: Define o framework de destino para o projeto (.NET 8.0).
- PackageReference: Lista as referências de pacotes NuGet necessárias para o projeto, como Dapper.SimpleCRUD, NUnit, Npgsql, entre outros.
- ProjectReference: Lista as referências de projeto para os projetos de Repository e Services, que este projeto depende.
- UserSecretsId: Identificador para armazenamento seguro de segredos do usuário.
- DockerDefaultTargetOS: Define o sistema operacional padrão para o Docker (Linux).

Outro arquivo de extrema importância é o *Kombi.Dashboard.WebApi*.http. Ele é o arquivo responsável por testar. Ele fornece exemplos de solicitações HTTP que podem ser usadas para interagir e testar a API da web desenvolvida no projeto. Define o endereço base da API, e demonstra como fazer uma solicitação GET para um dos seus endpoints, especificando o formato de resposta desejado. Isso é útil para verificar se a API está funcionando conforme o esperado e para identificar problemas de comunicação entre o cliente e o servidor. 

<br> 
<br> 

![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/endereco.png)

**Figura 8:** Endereço base e solicitação GET <br> 
**Fonte:** Elaboração própria <br> 
<br>  
<br> 

O arquivo *Program.cs*, contém o código para configurar e iniciar a aplicação web. Utilizando o padrão de inicialização do ASP.NET Core, ele configura os serviços de solicitação HTTP. 

Inicialmente, ele configura o provedor de configuração para carregar as configurações do arquivo appsettings.json, utilizando a classe ConfigurationBuilder para construir uma instância. Em seguida, são registrados os serviços necessários para a aplicação. Isso inclui serviços como controladores, serviços de repositório e serviços de serviço. O método AddScoped é usado para registrar esses serviços no contêiner de injeção de dependência. O Swagger é então configurado para fornecer documentação da API. Visto como uma ferramenta de código aberto, que ajuda os desenvolvedores a projetar, documentar e consumir APIs REST de maneira fácil e eficiente. Ele fornece uma interface interativa baseada na web para explorar a API, utilizando o método AddSwaggerGen para configurar o SwaggerGen. 
<br> 
<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/Swagger.png)<br><br> 

**Figura 9:** Swagger <br> 
**Fonte:** Elaboração própria <br> 
<br>  <br> 

Por fim, o arquivo *Startup.cs* contém a classe Startup, que é responsável por configurar os serviços e o pipeline de solicitação HTTP da aplicação. Ele é responsável por configurar os serviços da aplicação, incluindo  o pipeline de solicitação HTTP, para tratamento de exceções, autorização e endpoints de controle.

Em suma, a documentação apresentada oferece uma visão abrangente do projeto Kombi.Dashboard. Essa documentação  destaca a estrutura modular da aplicação e os componentes-chave que a compõem. Por meio dos arquivos identificados, é possível compreender como os dados são modelados, armazenados e manipulados de forma eficiente garantindo uma boa comunicação entre o usuário com o sistema. 
Essa documentação serve como um recurso valioso com insights detalhados sobre a arquitetura, funcionamento e testes da aplicação destacados. 


