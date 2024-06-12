# Relatório de Testes de Usabilidade e Acessibilidade

# 1. Metodologia  
  Para avaliar a usabilidade e acessibilidade dos dashboards desenvolvidos, empregamos uma metodologia estruturada e focalizada em testes moderados e controlados para a análise de variados fatores, como saúde, clima empresarial e satisfação no trabalho dos funcionários da Volkswagen. Para essas análises, foi selecionado um grupo diversificado de 4 participantes em idade, habilidades visuais e compreensão dos temas apresentados nos dashboards.
  
  Reconhecendo a complexidade da deficiência, que reflete a interação entre as características físicas e cognitivas do indivíduo com seu ambiente, incluímos na nossa amostra participantes com diferentes perfis. Entre eles, um homem com miopia, para avaliar possíveis limitações visuais no uso do dashboard; um indivíduo mais velho, com menor familiaridade com o assunto, um indivíduo mais novo visando entender sua capacidade de ter uma experiência enriquecedora; e um integrante de outro grupo da nossa turma trabalhando em outra solução no mesmo projeto para avaliar a intuição e a facilidade de uso da interface.
  
  Cada participante foi avaliado individualmente, com a orientação de um membro da nossa equipe, através de um conjunto de perguntas pré-definidas voltadas para a exploração dos dashboards, com foco em identificar problemas de usabilidade e acessibilidade. O Guia de Critérios de Acessibilidade para Conteúdo Web (WCAG) foi utilizado como principal referência para avaliação, com os testes centrados nos quatro pilares fundamentais da acessibilidade na web: Perceptível, Operável, Compreensível e Robusto.

* Perceptível: Garantir que todas as informações e componentes da interface sejam perceptíveis a todos os usuários.
* Operável: Assegurar que todos os componentes e navegação sejam operáveis.
* Compreensível: Tornar a informação e a operação da interface compreensíveis.
* Robusto: O conteúdo deve ser suficientemente robusto para ser interpretado por uma ampla gama de tecnologias assistivas.

As observações e resultados dos testes foram sistematicamente documentados em uma planilha do Google Sheets, proporcionando uma organização eficaz e uma análise clara dos dados coletados, incluindo os objetivos de cada teste, perguntas feitas e resultados alcançados.

Link Google Sheets: https://docs.google.com/spreadsheets/d/1ELJfDc3KD4n8Ta11AePpBrPRnUkqEcE7puLaGyx0Nzc/edit#gid=0 



# 2. Resultados 
Os testes nos forneceram uma visão detalhada sobre os aspectos intuitivos e de fácil compreensão dos dashboards, bem como identificaram áreas para aprimoramento. Os achados reforçam a importância de conduzir avaliações regulares para detectar e resolver potenciais problemas que podem não ser evidentes para os desenvolvedores.

# 2.1 - Navegação Consistente - Compreensível [AA]
Concentramos nossa análise na página "Visão Geral", notável por sua riqueza em gráficos, tabelas, KPIs e índices, dada sua capacidade de fornecer um panorama extenso das funcionalidades do dashboard. A uniformidade na navegação recebeu elogios unânimes dos avaliadores, que enfatizaram sua eficiência em promover um padrão coeso de apresentação, interação e disposição de elementos, tais como campos de pesquisa, que se mantêm constantes em diversas interfaces.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/vg1.png)
<br> 
<br>
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/vg2.png)<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/vg3.png)<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/vg4.png)<br> 

O retorno dos usuários foi majoritariamente positivo, sublinhando o êxito em assegurar uma navegação contínua e intuitiva, o que eleva a qualidade da experiência do usuário. Por outro lado, uma sugestão de um dos usuários apontou que, embora a navegação seja fluida, a experiência poderia ser enriquecida por meio de variações na apresentação visual para tornar a interface mais viva e convidativa, sem prejuízo à funcionalidade.

Observamos múltiplas avaliações e comentários positivos que reforçam o bom desempenho em estabelecer e aprimorar uma navegação fluida. Um dos participantes louvou a consistência na organização dos elementos de
navegação por todo o dashboard, mencionando a facilidade em transitar entre as diversas seções. Outro destacou a simplicidade em localizar funcionalidades recorrentes, como busca e menus, graças à sua colocação uniforme, facilitando o aprendizado e uso do dashboard até por usuários iniciantes ou menos habituados. Um terceiro expressou apreço pela estruturação e agrupamento dos gráficos e tabelas, o que facilitou sua interpretação e análise.

No entanto, recebemos também uma crítica construtiva que reconheceu a qualidade da experiência, porém sugeriu melhorias.

Um participante, apesar de valorizar a consistência e facilidade de navegação, observou que a uniformidade pode tornar a experiência um tanto quanto monótona em determinados momentos. Ele apreciou a previsibilidade na disposição dos elementos, como menus e botões de busca, mas sugeriu que variações na apresentação visual poderiam tornar a interface mais dinâmica e engajante, sem afetar a praticidade.

Com essas avaliações em mente, especialmente a do último participante, elaboramos um conjunto de recomendações destinadas a abordar os desafios apontados. Essas sugestões incluem preservar a uniformidade na navegação, introduzindo ao mesmo tempo variações visuais em certas áreas para realçar a experiência do usuário sem comprometer a facilidade de uso. As recomendações se apoiam nos feedbacks recebidos, ressaltando a necessidade de ajustar a interface para que se mantenha tanto consistente quanto estimulante para os usuários.

Por fim, a severidade dos problemas relacionados à navegação consistente é considerada **baixa**. Embora a sugestão de introduzir variações visuais para tornar a interface mais viva tenha sido mencionada, a funcionalidade básica de navegação e a experiência do usuário foram amplamente elogiadas, indicando que as melhorias sugeridas visam aprimorar uma experiência já positiva.

# 2.2 - Rótulo no Nome Acessível - Operável [A] 

Focamos nossa análise na "Página de Relatório de Saúde", particularmente devido à sua apresentação de gráficos acompanhados de legendas visuais. Essas legendas, além de facilitarem o entendimento dos dados sem excessiva dependência de textos descritivos, dispõem de uma interatividade que, ao interagir com o cursor, expõe transcrições detalhadas dos títulos dos gráficos. Esse design cuidadoso é projetado para melhorar tanto a acessibilidade quanto a compreensão visual para a ampla gama de usuários, inclusive aqueles que recorrem a leitores de tela.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/saude1.png)
<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/saude2.png)
<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/saude3.png)
<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/saude4.png)
<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/saude5.png)
<br> 

Os feedbacks dos participantes foram unânimes em reconhecer a contribuição significativa dos rótulos acessíveis na melhoria da navegabilidade e inteligibilidade do dashboard. A precisão e o detalhamento desses elementos interativos enriqueceram consideravelmente a experiência de navegação, tornando-a tanto intuitiva quanto informativa. Entretanto, o processo revelou também oportunidades para aprimorar ainda mais a experiência do usuário. A partir das observações recebidas, delineamos um plano de ação destinado ao contínuo aperfeiçoamento da acessibilidade e usabilidade:

* Aumento na Frequência dos Rótulos: Propomos a inclusão mais abrangente de rótulos acessíveis nos gráficos, assegurando que os usuários tenham uma compreensão imediata dos dados apresentados, mesmo na ausência de interação direta.
* Dinamismo Visual Ampliado: Sugerimos a implementação de variações visuais nos gráficos que, em sinergia com os rótulos acessíveis, empreguem cores distintas ou animações sutis ao passar do mouse. Este enriquecimento visual visa tornar a análise de dados não apenas mais acessível, mas também visualmente estimulante e atraente.

Essas estratégias não apenas têm o objetivo de ampliar a clareza e acessibilidade do conteúdo, mas também de tornar a experiência do usuário mais imersiva e prazerosa. A personalização visual, cuidadosamente alinhada ao feedback dos usuários, é chave para alcançar esse fim. Esse esforço coletivo ressalta a importância de refinamentos contínuos nos termos empregados e na padronização dos rótulos acessíveis, essenciais para manter a usabilidade e acessibilidade da interface para todos os usuários, especialmente para aqueles dependentes de tecnologias assistivas.

Conclue-se, portanto, que os problemas identificados nesta categoria são de severidade **média**. Apesar dos rótulos acessíveis melhorarem significativamente a navegabilidade e compreensão, a necessidade de aumentar a frequência dos rótulos e introduzir dinamismo visual indica que há espaço para melhorias significativas para enriquecer ainda mais a experiência do usuário.

# 2.3 - Pronúncia / Palavras incomuns - Compreensível legível [AAA]

No desenvolvimento do nosso dashboard, encaramos o desafio de tratar com termos técnicos e palavras pouco usuais que exigem um entendimento contextual ou conhecimento prévio específico. Este desafio torna-se evidente especialmente na página "Visão Geral", onde uma profusão de gráficos, tabelas e índices podem introduzir conceitos não familiares aos usuários, como "Stiba" e "GPTW". Reconhecemos que, embora nosso público-alvo possa ter um conhecimento prévio substancial sobre os assuntos abordados, a compreensão de termos específicos ainda poderia representar uma barreira à usabilidade plena.

Durante a avaliação do uso do dashboard, alguns usuários relataram dificuldades em compreender determinados jargões e termos técnicos, mesmo com a assistência de membros da equipe de desenvolvimento. Ficou claro que a falta de familiaridade com esses termos poderia comprometer a experiência do usuário, destacando a necessidade de soluções que facilitassem a compreensão sem interromper o fluxo de trabalho. Dessa forma as seguintes soluções foram propostas pelos usuários: 

Integração de Dicas de Ferramentas e Pop-ups Contextuais: Para superar essa barreira, sugerimos aprimorar a interface com a implementação de dicas de ferramentas e pop-ups contextuais. Essa solução permitiria que os usuários obtivessem definições e explicações breves ao interagir com termos complexos, diretamente no contexto de uso, evitando desvios desnecessários na navegação e mantendo o foco no conteúdo relevante.
Funcionalidade de pronúncia: Adicionalmente, reconhecemos a importância de suportar a compreensão auditiva dos termos apresentados. A adoção de ícones de áudio ao lado de termos técnicos e jargões facilitaria o acesso dos usuários à pronúncia correta desses termos com um simples clique. Tal funcionalidade não somente auxiliaria na compreensão dos termos como também promoveria uma abordagem inclusiva, respeitando as diferentes necessidades de todos os usuários.


A análise do feedback dos usuários sobre a página "Visão Geral" sublinhou a crucial necessidade de tornar termos técnicos e jargões amplamente acessíveis e compreensíveis. As soluções que propomos visam não apenas endereçar os desafios identificados, mas também ampliar a acessibilidade geral do nosso dashboard. Com esses aprimoramentos, aspiramos a transformar nosso dashboard em uma ferramenta não só robusta para análise, mas também plenamente acessível e compreensível para uma gama diversificada de usuários. Este empenho reflete nosso compromisso inabalável com a inclusividade e a acessibilidade, assegurando que o dashboard sirva eficazmente a todos os seus potenciais usuários.

Em suma, A dificuldade em compreender termos técnicos e jargões representa um problema de severidade **média a alta**. Essa questão pode criar barreiras significativas para a usabilidade do dashboard, especialmente para usuários novos ou menos experientes no assunto abordado sobre engajamento e saúde mental dos colaboradores, embora as soluções propostas anteriormente possam mitigar eficazmente esse desafio.

# 2.4 - Contraste e Apresentação Visual - Perceptível Discernível [AAA]

Na avaliação dos padrões de contraste e design visual definidos pelo WCAG, particularmente no que se refere ao uso em dashboards como o "Relatório Stiba", percebe-se a crucialidade de manter um design visual intuitivo e acessível. A seleção apropriada de contrastes entre texto e plano de fundo não só simplifica a leitura para todos, inclusive para pessoas com deficiências visuais, mas também contribui para a compreensão eficaz das informações exibidas. A escolha de uma paleta de cores harmônicas, exemplificada pelo uso de cinza escuro sobre branco, foi destacada por sua capacidade de potencializar a legibilidade e promover uma navegação mais fluida pelo dashboard.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/stiba.png)
<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/stiba2.png)
<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/stiba3.png)
<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/stiba4.png)
<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/stiba5.png)
<br> 
![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/stiba6.png)
<br> 

**Feedback dos Usuários e Ações Sugeridas**:

Embora tenhamos recebido avaliações positivas, surgiram pedidos por opções que ofereçam aos usuários a liberdade de personalizar a experiência visual, incluindo a modificação do tamanho da letra e do esquema de cores. Essa demanda sinaliza a necessidade de evoluir o dashboard para não apenas ser acessível, mas também personalizável conforme as preferências de cada um. Como resposta, sugerimos a inclusão de Funcionalidades de Ajuste Personalizado que permitirão alterações no contraste, no tamanho do texto e no esquema de cores diretamente no dashboard, por meio de ferramentas de fácil uso como controles deslizantes. Tal iniciativa busca ampliar a acessibilidade e a personalização, aprimorando a usabilidade para o usuário.

Por fim, propõe-se a realização de testes de usabilidade específicos para essas novas opções de ajuste personalizado, com o objetivo de recolher opiniões e efetuar melhorias conforme necessário. Isso garantirá que as inovações atendam de maneira eficaz às expectativas dos usuários, elevando a qualidade da experiência proporcionada.

Em resumo, os problemas relacionados ao contraste e à apresentação visual são de severidade **baixa a média**. As sugestões para permitir a personalização do tamanho da letra e do esquema de cores visam melhorar uma experiência de usuário já positiva, sugerindo que as questões de contraste não impedem significativamente a funcionalidade ou a compreensão do dashboard, mas a personalização poderia melhorar a acessibilidade e satisfação do usuário.

# Recomendações
A realização deste abrangente processo de testes de usabilidade e acessibilidade nos dashboards desenvolvidos para a Volkswagen ofereceu insights valiosos sobre a interação dos usuários com a tecnologia. Através de uma metodologia estruturada, envolvendo participantes com variados perfis, conseguimos explorar em profundidade as nuances da experiência do usuário, desde a percepção visual à compreensão das interfaces. Os resultados evidenciaram pontos fortes, como a navegação consistente e intuitiva que facilita o acesso e a compreensão dos dashboards, e identificaram oportunidades significativas de melhoria. Em particular, destacaram-se sugestões para enriquecer a experiência do usuário por meio de variações visuais e funcionalidades personalizáveis, reforçando a necessidade de uma abordagem centrada no usuário para o design de dashboards.

As críticas construtivas recebidas e as recomendações propostas refletem um compromisso contínuo com a melhoria, sugerindo que a adaptação e a inovação devem ser elementos centrais no desenvolvimento de tecnologias acessíveis. A incorporação de ajustes personalizados e a ampliação da acessibilidade dos termos técnicos são passos cruciais na direção de um ambiente digital mais inclusivo.

Concluímos, portanto, que a jornada para aprimorar a usabilidade e a acessibilidade é um processo iterativo e colaborativo, que beneficia imensamente do envolvimento direto dos usuários. O diálogo contínuo com os usuários, a avaliação criteriosa de feedbacks e a implementação ágil de melhorias são fundamentais para garantir que os dashboards não apenas cumpram seu propósito analítico, mas também promovam uma interação gratificante e acessível para todos.
