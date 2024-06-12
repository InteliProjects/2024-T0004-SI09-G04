# Análise Heurística

Para realizar uma análise heurística do projeto, empregaremos as 10 Heurísticas de Usabilidade para Design de Interface de Usuário, conforme definido por Jakob Nielsen. Essas diretrizes, detalhadas e regularmente atualizadas pelo Nielsen Norman Group, servem como uma bússola para o design centrado no usuário, oferecendo insights valiosos sobre a eficácia da interação entre usuário e interface.

As heurísticas de Nielsen abrangem uma ampla gama de aspectos de usabilidade, desde a visibilidade do status do sistema até a prevenção de erros, e são essenciais para criar interfaces intuitivas, eficientes e acessíveis. Ao adotar esses princípios, buscamos não apenas identificar problemas de usabilidade no projeto atual, mas também fornecer recomendações práticas para melhorias. Essa abordagem nos permite aprimorar a experiência do usuário, garantindo que o produto final seja não apenas funcional, mas também agradável de usar.

Para cada heurística, adotamos a seguinte abordagem metodológica:

**1. Identificação:** Examinamos o dashboard para identificar onde e como cada heurística é aplicável.

**2. Avaliação:** Avaliamos a conformidade atual do dashboard com a heurística, identificando áreas de sucesso e oportunidades de melhoria.

**3. Recomendações:** Propomos soluções práticas e viáveis baseadas em princípios de design e usabilidade reconhecidos para aprimorar a interface.

## 1. Visibilidade do status do sistema

*"O design deve sempre manter os usuários informados sobre o que está acontecendo, através de feedback apropriado dentro de um período de tempo razoável."*

Na avaliação da heurística "Visibilidade do Status do Sistema" de Jakob Nielsen aplicada ao nosso dashboard, observamos uma lacuna significativa entre o ideal estabelecido por esta heurística e a realidade do design atual. Essencialmente, a heurística enfatiza a importância de manter os usuários informados sobre as operações em andamento através de feedback claro e em tempo hábil, algo que nosso dashboard, em sua forma atual, não realiza de maneira adequada. Esse desalinhamento é evidente na ausência de indicadores visuais ou de feedback durante momentos críticos, como transições entre telas ou durante a geração de infográficos. Abaixo, demonstra-se que após o login do usuário, ele é automaticamente redirecionado ao ‘Início’ do dashboard, sem algum indício de carregamento ou visibilidade do status do sistema.

![Imagem 1: Telas do dashboard](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled.png)

Imagem 1: Telas do dashboard

Essa deficiência pode ser parcialmente atribuída ao estágio atual do desenvolvimento, onde optamos por "mockar" os dados, levando a respostas instantâneas e omitindo a necessidade de feedback de carregamento. Tal escolha, embora justificável no contexto de desenvolvimento de wireframes e mockups focados na estruturação das principais telas e funcionalidades, não reflete uma experiência de usuário realista, em que tais tempos de espera são comuns e esperados. Além disso, a ausência de feedback pode criar uma falsa percepção de rapidez, não preparando os usuários para possíveis esperas em um ambiente de produção, o que pode resultar em confusão ou frustração.

A falta de feedback visual é classificada como um problema de menor gravidade, dada a natureza não funcional do dashboard em seu estado atual (wireframe) e a previsão de que as transições reais sejam rápidas, especialmente considerando o design "One Page" do aplicativo e a simplicidade dos dados manipulados. No entanto, é imperativo abordar essa questão para não comprometer a experiência do usuário em cenários de uso real.

Como parte da solução, recomendamos a integração de símbolos intuitivos ou mensagens explícitas que sinalizem ao usuário que uma operação está em andamento, particularmente em áreas do sistema onde as ações não resultam em uma resposta imediata. Isso pode incluir a implementação de barras de progresso, ícones de carregamento (como spinners), ou mesmo mensagens de texto que comunicam o status atual da operação (por exemplo, "Carregando dados...").

Paralelamente, a construção da navbar merece elogios por sua clareza na comunicação do status do sistema, com cada seção claramente delineada e a seção ativa destacada, fornecendo uma orientação visual constante ao usuário sobre sua localização atual no sistema. Essa prática exemplifica bem a aplicação da heurística e deve ser mantida e possivelmente expandida para outras áreas do dashboard, garantindo uma experiência de usuário coesa e intuitiva.

![Imagem 2: Navbar](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%201.png)

Imagem 2: Navbar

Ao endereçar essas questões e implementar as recomendações propostas, podemos aprimorar significativamente a usabilidade do nosso dashboard, alinhando-o mais estreitamente com as heurísticas de Nielsen e, por extensão, melhorando a experiência geral do usuário.

## 2: Correspondência entre o sistema e o mundo real

*"O design deve falar a língua dos usuários. Use palavras, frases e conceitos familiares ao usuário, em vez de jargões internos. Siga as convenções do mundo real, fazendo com que as informações apareçam em uma ordem natural e lógica."*

Na análise da heurística "Correspondência entre o sistema e o mundo real" de Jakob Nielsen, nosso dashboard se destaca por sua aderência exemplar a este princípio. A heurística enfatiza a importância de o sistema comunicar-se numa linguagem familiar aos usuários, usando termos, frases e conceitos reconhecíveis, e apresentando informações de maneira lógica e ordenada. Neste aspecto, o dashboard foi meticulosamente projetado com uma linguagem verbal clara e acessível, especificamente adaptada ao público-alvo principal, neste caso do wireframe, o CEO da Volkswagen Brasil. A seleção cuidadosa da terminologia e a contextualização das informações garantem que os usuários não apenas compreendam as funcionalidades disponíveis, mas também se sintam à vontade com a interface desde o início. Abaixo, demonstra-se o uso claro da correlação de cores do mundo real com as informações a serem demonstradas no gráfico.

![Imagem 3: Gráfico de matriz de correlação](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%202.png)

Imagem 3: Gráfico de matriz de correlação

![Imagem 4: Métrica de índice com associação de cores](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%203.png)

Imagem 4: Métrica de índice com associação de cores

![Imagem 4: Métricas com associação de cores de acordo com a evolução](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%204.png)

Imagem 4: Métricas com associação de cores de acordo com a evolução

Além da linguagem verbal, o dashboard brilha igualmente na sua linguagem não verbal. Os símbolos, ícones e o esquema de cores foram escolhidos não apenas por sua estética, mas principalmente por sua capacidade de comunicar funções e estados de forma intuitiva. Cada elemento visual foi projetado para ser autoexplicativo, eliminando qualquer ambiguidade na interpretação das funcionalidades do dashboard. Esta clareza visual reforça a acessibilidade e a usabilidade do sistema, permitindo que os usuários naveguem e interajam com o dashboard de forma eficaz e sem erros. Os exemplos abaixo demonstram como o uso de ícones que remetam ao mundo real auxiliam na navegação e uso do dashboard.

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%205.png)

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%206.png)

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%207.png)

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%208.png)

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%209.png)

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2010.png)

![Imagem 5: Demonstração de ícones em filtros, gráficos e botões do sistema](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2011.png)

Imagem 5: Demonstração de ícones em filtros, gráficos e botões do sistema

Esta congruência entre a linguagem verbal e não verbal e a experiência e expectativas dos usuários é um testemunho do design centrado no usuário empregado no desenvolvimento do dashboard. Através desta abordagem, asseguramos que o dashboard não apenas atenda às necessidades operacionais dos usuários, mas também ressoe com eles em um nível mais intuitivo e familiar, facilitando uma experiência de usuário coesa e satisfatória.

## 3: Controle e liberdade do usuário

*"Os usuários geralmente executam ações por engano. Eles precisam de uma “saída de emergência” claramente marcada para abandonar a ação indesejada sem ter que passar por um processo extenso."*

Ao examinar a heurística "Controle e Liberdade do Usuário" em nosso dashboard, notamos que ela é amplamente respeitada, embora exista um aspecto que requer atenção. A navegação principal, facilitada por uma navbar proeminente e bem posicionada, permite que os usuários se movam de forma eficiente e intuitiva entre as diferentes seções do dashboard. Esse design garante que, mesmo em casos de cliques acidentais em abas não desejadas, os usuários possam rapidamente corrigir a ação e navegar para a área desejada sem dificuldades.

![Imagem 6: Navbar do dashboard](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2012.png)

Imagem 6: Navbar do dashboard

Além disso, a funcionalidade de retorno ao início é prontamente acessível nas seções de perfil e edição de perfil, onde um botão destacado "Voltar ao Início" com um ícone direcional proporciona um caminho claro de volta à página inicial. Essa abordagem garante que os usuários mantenham o controle sobre sua navegação, podendo desfazer ações indesejadas de maneira simples e direta.

![Imagem 7: Tela do usuário com botão ‘Voltar ao Início’](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2013.png)

Imagem 7: Tela do usuário com botão ‘Voltar ao Início’

![Imagem 8: Tela de edição do usuário com botão ‘Voltar ao Início’](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2014.png)

Imagem 8: Tela de edição do usuário com botão ‘Voltar ao Início’

![Imagem 9: Tela de cadastro do usuário com botão de ‘Voltar ao Início’](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2015.png)

Imagem 9: Tela de cadastro do usuário com botão de ‘Voltar ao Início’

A gestão dos infográficos também reflete a consideração pela autonomia do usuário, permitindo ajustes rápidos e fáceis sem penalizar o usuário por possíveis erros de interpretação ou cliques involuntários. A flexibilidade nas configurações dos gráficos destaca a capacidade do sistema de se adaptar às necessidades e preferências do usuário, reforçando a usabilidade e a satisfação geral.

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2016.png)

![Imagem 10: Exemplos de gráficos com personalização por parte do usuário](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2017.png)

Imagem 10: Exemplos de gráficos com personalização por parte do usuário

No entanto, identificamos uma lacuna em relação à opção de deslogar do sistema. Atualmente, o dashboard não oferece uma maneira direta para o usuário encerrar sua sessão, uma funcionalidade crítica para manter a segurança e a personalização da experiência do usuário. Especialmente considerando a possibilidade de o projeto se expandir para incluir diferentes tipos de usuários, a inclusão de uma opção de logout torna-se essencial para assegurar que os usuários possam gerenciar o acesso às suas contas de forma segura e conveniente.

Para solucionar esse ponto de atenção, recomendamos a implementação de um mecanismo de logout claramente visível, idealmente posicionado na área de perfil ou na navbar principal. Isso não apenas abordará a preocupação identificada, mas também elevará a conformidade do dashboard com a heurística de controle e liberdade do usuário, assegurando que todos os aspectos da navegação e interação sejam otimizados para proporcionar uma experiência de usuário coesa e empoderadora.

## 4: Consistência e Padrões

*"Os usuários não deveriam se perguntar se palavras, situações ou ações diferentes significam a mesma coisa. Siga as convenções da plataforma e do setor."*

Ao avaliar o mockup do dashboard utilizando a heurística "Consistência e Padrões" de Jakob Nielsen, observa-se um forte compromisso com a aplicação desta regra de usabilidade. Esta heurística ressalta a importância de padrões consistentes no design de interface, que são essenciais para uma navegação intuitiva e uma experiência de usuário previsível.

O design do mockup demonstra uma abordagem deliberada para manter a consistência visual e funcional em todos os seus elementos. Os gráficos, de maneira geral, seguem um esquema consistente de cores e estilos, o que facilita a compreensão dos dados apresentados. Além disso, os menus suspensos seguem um padrão uniforme em localização e operação, proporcionando uma experiência de usuário coesa.

![Imagem 11: Gráfico de linhas da página ‘Stiba’](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2018.png)

Imagem 11: Gráfico de linhas da página ‘Stiba’

![Imagem 12: Gráfico de linhas da página ‘GPTW x Stiba’](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2019.png)

Imagem 12: Gráfico de linhas da página ‘GPTW x Stiba’

![Imagem 13: Gráfico de linhas da página ‘Saúde x Clima empresarial’](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2020.png)

Imagem 13: Gráfico de linhas da página ‘Saúde x Clima empresarial’

![Imagem 14: Menu suspenso](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2021.png)

Imagem 14: Menu suspenso

No entanto, identificou-se uma oportunidade de melhoria em relação à funcionalidade de logout, que está ausente no mockup atual. Considerando a expansão potencial para mais usuários, a inclusão de uma opção de logout é uma consideração de segurança importante e uma prática padrão de design. A ausência desta funcionalidade é vista como uma preocupação de moderada severidade e deve ser abordada para garantir a integridade do sistema.

A solução recomendada é a integração de um mecanismo de logout facilmente acessível e visível, alinhando-se com as práticas de consistência e segurança esperadas em design de interfaces. Isso não só fortalecerá a confiança no uso do dashboard, mas também manterá a consistência ao longo de toda a jornada do usuário.

Este mockup, ao implementar a recomendação sugerida, estará reforçando seu alinhamento com as heurísticas de Nielsen e, consequentemente, melhorando a experiência do usuário em aspectos fundamentais de usabilidade e segurança.

## 5: Prevenção de Erros

*"Boas mensagens de erro são importantes, mas os melhores designs evitam cuidadosamente a ocorrência de problemas. Elimine condições propensas a erros ou verifique-as e apresente aos usuários uma opção de confirmação antes de se comprometerem com a ação."*

Revisando o dashboard fornecido à luz da heurística "Prevenção de Erros" de Jakob Nielsen, nota-se que várias medidas para orientar o usuário de forma eficaz, minimizando as chances de erros. Por exemplo, a clareza nas visualizações de dados e as categorizações distintas nos menus suspensos ajudam a evitar confusões durante a interação com o dashboard. Além disso, os elementos de design, como botões e ícones, são apresentados de forma a indicar claramente suas funcionalidades, contribuindo para uma experiência de usuário sem esforço e intuitiva.

![Imagem 15: Menu suspenso](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2022.png))

Imagem 15: Menu suspenso

Contudo, o dashboard poderia ser aprimorado adicionando prompts de confirmação para ações significativas, especialmente onde a reversão não é direta ou onde as consequências são substanciais. Essa adição não só aumentaria a confiança na interação com o sistema, como também proporcionaria uma camada adicional de segurança, assegurando que as ações dos usuários sejam intencionais e conscientes.

Além disso, a funcionalidade de desfazer é incorporada em áreas críticas para permitir que os usuários corrijam facilmente quaisquer ações acidentais, como em cadastro, exclusão e edição de usuários. Isso é particularmente relevante para operações que alteram dados ou configurações significativas. Implementar tais mecanismos não só atenderá melhor à heurística "Prevenção de Erros", mas também reforçará a usabilidade e a eficácia geral do dashboard.

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2023.png))

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2024.png))

![Imagem 16: Páginas de edição, cadastro e exclusão de usuário](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2025.png))

Imagem 16: Páginas de edição, cadastro e exclusão de usuário

Por fim, também foram implementados feedbacks de sucesso em relação à essas mesmas ações:

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2026.png))

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2027.png))

![Imagem 17: Feedback de sucesso em edição, cadastro e exclusão de usuário](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2028.png))

Imagem 17: Feedback de sucesso em edição, cadastro e exclusão de usuário

Embora não estejam visíveis problemas críticos relacionados a essa heurística no mockup atual, a inclusão das melhorias sugeridas ajudará a garantir que o sistema seja robusto e confiável, mantendo a consistência com as práticas de design centradas no usuário e cumprindo com os padrões estabelecidos para uma interface de qualidade.

## 6: Reconhecimento em vez de lembrança

*"Minimize a carga de memória do usuário tornando visíveis elementos, ações e opções. O usuário não deveria ter que lembrar informações de uma parte da interface para outra. As informações necessárias para usar o design (por exemplo, rótulos de campos ou itens de menu) devem estar visíveis ou facilmente recuperáveis quando necessário."*

Analisando a sexta heurística de Nielsen, "Reconhecimento em vez de lembrança", o dashboard deve ser desenhado de modo a minimizar a necessidade do usuário de memorizar informações ao longo de sua interação. Este princípio é seguido com eficácia no projeto, em que elementos, ações e opções são visíveis e facilmente recuperáveis, facilitando o reconhecimento direto em vez de depender da memória.

As visualizações de dados, com gráficos e tabelas claramente rotulados, permitem aos usuários identificar e compreender as informações rapidamente, sem necessidade de lembrar o significado de diferentes elementos ou símbolos. Além disso, os controles e opções de interação são consistentemente apresentados, permitindo que os usuários localizem as funções necessárias sem esforço, o que é um bom exemplo de como o dashboard permite o reconhecimento fácil de ações disponíveis.

![Imagem 18: Exemplo de tela com gráficos e botões de interações](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2029.png))

Imagem 18: Exemplo de tela com gráficos e botões de interações

![Imagem 19: Exemplo de outra tela com gráficos e botões de interações consistentes à anterior](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2030.png)

Imagem 19: Exemplo de outra tela com gráficos e botões de interações consistentes à anterior

No entanto, sempre há espaço para melhorias. A inclusão de dicas de ferramentas informativas ou legendas explicativas poderia aprimorar ainda mais a capacidade do usuário de reconhecer e entender as funcionalidades sem ter que se recordar de informações previamente vistas em outras partes do dashboard. Adicionar um recurso de ajuda contextual ou um sistema de orientação passo a passo para novos usuários também reforçaria esta heurística, auxiliando no reconhecimento e compreensão das funcionalidades do sistema.

Implementando esses ajustes, o dashboard não apenas fortalecerá a experiência do usuário em termos de reconhecimento, mas também assegurará que o design esteja em completa harmonia com as diretrizes de usabilidade reconhecidas. Estas melhorias têm o potencial de tornar o dashboard mais intuitivo e reduzir a curva de aprendizado, alinhando-se aos critérios estabelecidos para um sistema eficaz e centrado no usuário.

## 7: Flexibilidade e Eficiência de Uso

*"Atalhos – ocultos para usuários novatos – podem acelerar a interação do usuário experiente, para que o design possa atender tanto usuários inexperientes quanto experientes. Permita que os usuários personalizem ações frequentes."*

A heurística número sete de Jakob Nielsen, "Flexibilidade e Eficiência de Uso", aborda a importância de atender tanto usuários inexperientes quanto os mais experientes, oferecendo atalhos que acelerem a interação para o último grupo, sem prejudicar a compreensão do primeiro. No projeto, a interface é projetada com a clareza necessária para novos usuários, mas não há indicações claras de atalhos ou personalizações avançadas que possam beneficiar usuários frequentes.

Para melhor atender a esta heurística, seria recomendável introduzir funcionalidades que permitam personalizar a visualização de dados ou configurar preferências que possam ser salvas e recuperadas em visitas futuras. Por exemplo, permitir que os usuários criem conjuntos de filtros pré-definidos ou tenham a capacidade de modificar e salvar layouts de dashboard poderia ser uma forma eficaz de aumentar a eficiência para usuários regulares.

![Imagem: Filtros de página do dashboard (presente em todas as páginas)](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2031.png)

Imagem: Filtros de página do dashboard (presente em todas as páginas)

![Imagem 20: Filtro de gráfico específico na página ‘GPT](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2032.png)

Imagem 20: Filtro de gráfico específico na página ‘GPT

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2033.png)

![Imagem 21: Filtro de gráfico específico na página ‘Stiba’](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2034.png)

Imagem 21: Filtro de gráfico específico na página ‘Stiba’

![Imagem 22: Filtro de gráficos específicos na página ‘Saúde x Clima empresarial’](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2035.png)

Imagem 22: Filtro de gráficos específicos na página ‘Saúde x Clima empresarial’

A adição dessas capacidades não só melhoraria a experiência dos usuários mais avançados, que poderiam realizar suas tarefas de maneira mais rápida e eficiente, mas também manteria a interface intuitiva para aqueles que ainda estão se familiarizando com o dashboard. Ao incorporar essas mudanças, o dashboard se alinharia mais estreitamente com as melhores práticas de usabilidade e proporcionaria uma experiência mais rica e adaptável a diferentes perfis de usuários.

## 8: Design Estético e Minimalista

*"As interfaces não devem conter informações irrelevantes ou raramente necessárias. Cada unidade extra de informação numa interface compete com as unidades de informação relevantes e diminui a sua visibilidade relativa."*

Essa heurística enfatiza que os designs de interface devem ser simples e não devem conter informações desnecessárias que possam distrair ou sobrecarregar o usuário. No dashboard em análise, o design segue essa heurística ao apresentar uma interface limpa e focada, com visualizações de dados e opções de interação que não parecem sobrecarregadas ou desordenadas.

Os elementos são apresentados de maneira a facilitar o foco nas tarefas, e as informações são expostas de forma que destaca os dados mais importantes, sem excesso de ornamentação ou elementos gráficos que não contribuem para o entendimento. Isso demonstra uma consideração cuidadosa para com a estética e a funcionalidade, mantendo a atenção do usuário onde é mais necessário.

Para aprimorar ainda mais o alinhamento com esta heurística, revisar o dashboard para garantir que todas as informações e opções apresentadas são necessárias e valiosas para a tarefa ao usuários utilizarem a solução em mãos é uma boa alternativa. Se houver elementos que raramente são utilizados ou que não agregam valor imediato, eles podem ser removidos ou escondidos até que sejam necessários. Isso reduziria a carga cognitiva e melhoraria a eficiência geral do usuário.

Além disso, é fundamental manter o equilíbrio entre um design minimalista e a necessidade de fornecer informações suficientes para que os usuários tomem decisões informadas. Portanto, qualquer simplificação do design deve ser cuidadosamente considerada para evitar a remoção de elementos cruciais para a funcionalidade ou compreensão do usuário.

Adotando esses princípios de design estético e minimalista, o dashboard continuará a oferecer uma experiência de usuário que é ao mesmo tempo agradável e livre de desordem visual, o que é essencial para uma ferramenta eficaz de análise de dados.

## 9: Ajude os usuários a reconhecer, diagnosticar e se recuperar de erros

*"As mensagens de erro devem ser expressas em linguagem simples (sem códigos de erro), indicar com precisão o problema e sugerir uma solução de forma construtiva."*

A nona heurística de Nielsen diz respeito à clareza das mensagens de erro, que devem ser expressas em linguagem simples e indicar precisamente o problema, além de sugerir uma solução construtiva. No dashboard apresentado, não é possível identificar diretamente como os erros são tratados ou se as mensagens de erro são fornecidas, pois isso dependeria da interação em tempo real e dos sistemas de back-end em funcionamento.

Para alinhar-se plenamente com esta heurística, é recomendável que o dashboard inclua mensagens de erro claras e instrutivas que orientem os usuários quando algo não ocorrer conforme o esperado. Se uma ação não puder ser completada, o sistema deve informar o usuário sobre o que deu errado e fornecer etapas diretas para corrigir o problema. Por exemplo, se o upload de dados falhar, o sistema poderia explicar o motivo da falha e sugerir verificar o formato dos dados e tentar o upload novamente.

Além disso, seria benéfico para a experiência do usuário incorporar mecanismos de suporte que permitam aos usuários resolver problemas sem a necessidade de assistência externa, aumentando assim a autonomia do usuário e reduzindo a frustração.

A implementação de mensagens de erro informativas e de fácil entendimento, juntamente com diretrizes claras para a resolução de problemas, garantirá que o dashboard não apenas previna erros, mas também ofereça suporte adequado para a recuperação de erros, melhorando a usabilidade geral e a satisfação do usuário.

## 10: Ajuda e Documentação

*"É melhor que o sistema não precise de nenhuma explicação adicional. No entanto, pode ser necessário fornecer documentação para ajudar os usuários a compreender como concluir suas tarefas."*

A décima heurística de Nielsen sugere que, mesmo que seja ideal que um sistema possa ser usado sem documentação, pode ser necessário fornecer ajuda e documentação para auxiliar os usuários a completarem suas tarefas. Analisando o dashboard em questão, há evidências visíveis de ajuda integrada em gráficos e métricas para fornecer auxílio a compreensão acerca daquele gráfico, dos dados apresentados ou cálculos das métricas a partir do ícone ‘?’.

![Imagem 23: Exemplo de gráfico com ícone de ajuda (’?’)](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Ana%CC%81lise%20Heuri%CC%81stica/Untitled%2036.png)

Imagem 23: Exemplo de gráfico com ícone de ajuda (’?’)

Para aderir ainda mais a esta heurística, seria benéfico integrar uma seção de ajuda ou um sistema de tutoriais interativos que possam guiar os usuários pelas características e funcionalidades do dashboard. Isso poderia incluir FAQs, dicas contextuais, ou até mesmo pop-ups de orientação que aparecem na primeira utilização ou quando uma nova funcionalidade é acessada.

Além disso, a documentação poderia ser disponibilizada em um formato facilmente acessível, como um manual do usuário ou uma base de conhecimento online, com instruções passo a passo, exemplos de uso e soluções para problemas comuns. Isso permitiria que os usuários se autoajudassem e melhorassem sua compreensão do dashboard, resultando em uma experiência de usuário mais enriquecedora e independente.

Ao fornecer ajuda e documentação adequadas, o dashboard estaria não só cumprindo esta heurística, mas também reforçando a autonomia do usuário e a facilidade de uso do sistema. Isso é particularmente importante para um dashboard que pode apresentar uma grande quantidade de dados e várias opções de análise, onde o suporte adicional pode ser crucial para usuários de todos os níveis de habilidade.

## Conclusão

Concluindo a análise heurística deste dashboard, observamos que ele demonstra uma consideração profunda pelas práticas de design centrado no usuário, respeitando as heurísticas de usabilidade estabelecidas por Jakob Nielsen. A interface apresenta um design intuitivo e esteticamente agradável, com elementos interativos funcionais e visualizações de dados claras, permitindo aos usuários uma interação eficaz e informativa.

Embora a análise tenha revelado pontos de destaque, como a consistência no design e a facilidade de reconhecimento das funcionalidades, também identificamos áreas para melhoria, incluindo a necessidade de documentação e ajuda integradas, além de mecanismos para a prevenção e recuperação de erros. A inclusão desses elementos elevaria ainda mais a experiência do usuário, aumentando a autonomia e a eficiência ao utilizar o dashboard.

As recomendações fornecidas visam aprimorar a usabilidade e a funcionalidade do sistema, assegurando que ele não só atenda às necessidades operacionais dos usuários, mas também ofereça uma jornada de uso que seja compreensível, segura e agradável. Ao implementar essas melhorias, o dashboard não só estará em conformidade com as heurísticas de Nielsen, mas também se destacará como um exemplo exemplar de design de interface bem-sucedido e centrado no usuário.

Esta documentação serve como um registro detalhado das análises realizadas e como um guia para o desenvolvimento contínuo do dashboard. É uma ferramenta valiosa que reflete uma abordagem analítica e crítica ao design, crucial para o refinamento contínuo do projeto e para a entrega de um produto final que seja não apenas funcional, mas também uma alegria de usar.
