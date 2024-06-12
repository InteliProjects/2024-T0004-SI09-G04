# Documentação final

## 1. Entendimento de Negócios

### **1.1 Canvas Proposta de Valor**

O Canvas de Proposta de Valor é uma ferramenta essencial que auxilia a orientar o time de desenvolvimento a articular o valor único que seus produtos ou serviços oferecem ao seu cliente. Seu objetivo é mapear benefícios, aliviar dores e destacar os aspectos do produto que mais ressoam com as necessidades do cliente. Isso é crucial para o alinhamento do produto com as expectativas do mercado, garantindo que a solução seja desejável e relevantes, o que, por sua vez, impulsiona a satisfação do cliente. Abaixo encontra-se o Canvas Prosposta de Valor desenvolvido para o contexto apresentado pela Volkswagen.

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/canvas.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/canvas.png)

**Figura 1:** Canva Proposta de Valor

**Fonte**: Elaboração própria

**Segmento do cliente**

1. Tarefas do cliente
    1. Registros armazenados no Excel de forma manual;
    2. Execução de relatórios em Excel ou PowerPoint e
    3. Comunicação com BPs via emails para diferentes relatórios.
2. Dores
    1. Consolidar dados de múltiplas fontes para eficiência operacional;
    2. Facilitar a comunicação em grandes plantas para unificar a cultura organizacional e
    3. Monitorar saúde mental para melhorar o engajamento e produtividade.
3. Ganhos
    1. Fácil acesso aos dashboards, relatórios e insights;
    2. Tomada de ações reativas mais rápidas e melhoria contínua através das análises e
    3. Agilidade na tomada de decisão e maior precisão das análises.

**Proposta de Valor**

1. Produto e serviço
    1. Dashboard personalizado que correlaciona dados de saúde mental e engajamento dos colaboradores em todas as áreas.
2. Aliviantes de dores
    1. Integração dos dados em uma única plataforma para visualização única;
    2. Centralização da visualização de relatórios para todos os níveis e
    3. Identificação rápida de áreas que necessitam de atenção a partir de gráficos e métricas.
3. Criadores de ganhos
    1. Plataforma unificada com os resultados de todos os relatórios e dados disponíveis (Stiba, GPTW, Zenklub, Plano de saúde;
    2. Diferentes níveis de acesso ao dashboard para atender as hierarquias e privacidades de dados das diferentes diretorias e
    3. Customização dos gráficos e métricas a partir de filtros.

A proposta de valor deste Canvas visa simplificar a gestão de dados e comunicação no ambiente corporativo da Volkswagen, abordando desafios como a consolidação de informações de múltiplas fontes e o monitoramento da saúde mental para melhorar o engajamento e a produtividade. A solução central é um dashboard personalizado que integra dados relevantes em uma única plataforma, facilitando o acesso a insights e a tomada de decisão rápida e informada para a melhoria da saúde mental dos colaboradores e a cultura organizacional. Além disso, a proposta enfatiza a importância da customização e da acessibilidade dos dados, oferecendo diferentes níveis de acesso e a possibilidade de ajustar gráficos e métricas conforme a necessidade, visando atender a uma ampla gama de usuários dentro da empresa.

### **1.2 Matriz de Risco**

A Matriz de Risco é uma ferramenta de gestão que permite os desenvolvedores avaliarem e priorizarem riscos com base na probabilidade de ocorrência e no impacto potencial que esses riscos possam ter. É usada para identificar quais riscos necessitam de atenção imediata ou monitoramento contínuo, ajudando a alocar recursos de maneira eficiente e a implementar estratégias de mitigação adequadas. Essencial para o planejamento estratégico, a matriz de risco é fundamental na tomada de decisões informadas, na preparação para contingências e na minimização de surpresas indesejadas, contribuindo assim para a estabilidade e continuidade do projeto.

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/matriz.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/matriz.png)

**Figura 2:** Matriz de riscos

**Fonte**: Elaboração própria 

|  | Descrição do Risco | Responsável | Ação | Descrição da ação |
| --- | --- | --- | --- | --- |
| 1 | Desafio na definição de indicadores precisos para medir engajamento dos colaboradores. | Sophia Dias | Prevenir | Utilizar frameworks comuns para a área de gestão de pessoas, a fim de orientar a definição dos indicadores. |
| 2 | Limitações técnicas ou de infraestrutura para implementar o dashboard na empresa. | Lucas Britto | Prevenir | Antes de iniciar a implementação do dashboard, é essencial realizar uma avaliação abrangente dos requisitos de escalabilidade. Isso inclui considerar o volume de dados a serem processados, o número de usuários simultâneos e os requisitos de desempenho esperados. |
| 3 | O desalinhamento de storytelling dos dados, podendo prejudicar a compreensão e utilidade das informações apresentadas. | Kathlyn Diwan | Mitigar | No decorrer do projeto do dashboard, deve requisitar às partes interessadas a definição de uma narrativa coesa e objetivos claros para a apresentação dos dados. |
| 4 | O dashboard final não auxiliar na geração de insights para a equipe de RH devida à mal seleção dos dados. | Rafael Moritz | Mitigar | Durante as cerimônias de Review,solicitar ao cliente feedbacks em relação aos dashboards, questionando se de fato os casos de uso satisfazem as necessidades atribuídas. |
| 5 | Baixa qualidade do código em C#, devido à baixa experiência no uso da Programação Orientada à Objeto. | Thaina Lima | Prevenir | Fazer uma verificação semanal de como está o conhecimento do grupo em relação ao C#, garantindo que todos estão em um nível satisfatório em programação. |
| 6 | Incompatibilidade entre diferentes versões de tecnologias utilizadas, resultando em falhas de integração ou comportamento inesperado do sistema como um todo. | João Tourinho | Prevenir | Estabeleça canais eficazes de comunicação e colaboração entre as equipes de desenvolvimento (Devs), gerenciamento (PO e Scrum Master) e qualidade (QAs) para garantir que todos estejam alinhados em relação às versões de tecnologias utilizadas e aos processos de atualização. |
| 7 | Possíveis falhas de segurança, comprometendo a confidencialidade e a integridade dos dados. | Lucas Britto | Mitigar | Fazer uma verificação dos conteúdos para deploy ou enviados para ambientes não locais. |
| 8 | Complexidade na correlação entre os dados para a identificação de insights para melhorias na saúde mental e engajamento dos colaboradores. | Sophia Dias | Mitigar | Realizar análises periódicas para acompanhar a evolução dos dados ao longo do tempo e ajustar estratégias conforme necessário. |
| 9 | Problemas de desempenho no tratamento e armazenamento de dados analíticos. | Thaina Lima | Prevenir | Realizar uma avaliação detalhada dos requisitos de desempenho do sistema, levando em consideração o volume esperado de dados, a complexidade das consultas e as expectativas de tempo de resposta. |

Pontos de oportunidade e suas descrições:

- Oportunidade 10 - A solução final possibilitar a geração de novos insights ainda não imaginados pela empresa, dando um suporte ainda maior à tomada de decisões estratégicas.
- Oportunidade 11 - Possibilidade de uma futura implementação de um modelo de aprendizado de máquina por parte do cliente.
- Oportunidade 12 - Capacidade de escalabilidade para lidar com volumes crescentes de dados e área diferentes da empresa.
- Oportunidade 13 - Desenvolver uma interface bem adaptada para plataformas mobile .

### **1.4. Análise PESTEL**

A análise PESTEL é uma ferramenta utilizada no âmbito do planejamento estratégico empresarial para analisar o ambiente externo no qual uma organização opera. Ela é uma metodologia que surgiu com o intuito de compreender os diferentes fatores que podem influenciar o andamento de uma empresa abrangendo 6 fatores chaves:

1. Políticos: Os fatores políticos se referem ao ambiente político e governamental no qual a organização se encontra. Isso envolve, políticas governamentais, estabilidade política, regulamentações, leis e políticas fiscais.
2. Econômicos: Referem-se aos fatores econômicos que podem afetar a empresa, como taxas de crescimento econômico, taxas de juros, inflação, crescimento do PIB, desemprego, políticas monetárias, entre outros. Esses elementos podem influenciar o poder de compra dos consumidores, consequentemente é importante estar atento à demanda por produtos e serviços e a disponibilidade pelo financiamento de custos operacionais.
3. Sociais: Fatores sociais presentes na análise dizem respeito a fatores sociais, culturais, demográficos e comportamentais que podem impactar a empresa, como mudanças nas tendências de consumo, valores sociais, estilo de vida, demografia da população, entre outros.
4. Tecnológicos: Os fatores tecnológicos dizem respeito às inovações e avanços tecnológicos como utilização e ferramentas de AI, automatização, digitalização entre outras tecnologias emergentes. Logo, esses fatores auxiliam a identificar oportunidades para melhorar a eficiência operacional e manter a empresa competitiva no mercado.
5. Ecológicos: Refere-se a fatores ambientais, ecológicos e sustentáveis que podem afetar a empresa, tais como regulamentações ambientais, impacto e preocupação com sustentabilidade, e pressão dos consumidores por práticas ambientalmente responsáveis. De modo que as empresas estão tendo que se atentar cada vez mais aos fatores de consciência ambiental.
6. Legais: O conhecimento desses riscos avaliam as leis, regulamentações de saúde e segurança, leis trabalhistas, a fim de garantir a conformidade e lidar com questões jurídicas que possam afetar o negócio.

**Político**

No contexto do projeto de desenvolvimento de dashboards e tabelas para analisar o desempenho dos funcionários da Volkswagen, a análise do ambiente político e legislativo adquire uma relevância particular, impactando diretamente a eficácia e o rendimento dos colaboradores. Entender os fatores políticos e legislativos permite à Volkswagen antecipar mudanças e adaptar suas estratégias, assegurando não apenas a conformidade legal, mas também promovendo um ambiente de trabalho que potencialize o desempenho e a satisfação dos funcionários.

As eleições locais, estaduais ou nacionais, e as mudanças nas políticas governamentais ou regionais, podem influenciar significativamente o clima empresarial e econômico no qual a Volkswagen opera. A ascensão de políticos com diferentes visões sobre a política empresarial, por exemplo, pode levar a mudanças nas leis trabalhistas, afetando diretamente as políticas de emprego da empresa. Mudanças legislativas pendentes ou ajustes tributários também têm o potencial de afetar o custo operacional da Volkswagen, o que, por sua vez, pode influenciar a capacidade da empresa de investir em programas de desenvolvimento de funcionários, benefícios e iniciativas de bem-estar.

A regulação empresarial, incluindo relações com sindicatos e a legislação trabalhista, desempenha um papel crucial na definição das condições de trabalho. Alterações nessas regulamentações podem impactar o ambiente de trabalho, influenciando diretamente o engajamento e a produtividade dos colaboradores. Uma tendência para maior regulamentação, por exemplo, pode exigir que a Volkswagen adapte suas práticas de gestão de recursos humanos, enquanto uma tendência para a desregulação pode oferecer mais flexibilidade na gestão do trabalho.

A Volkswagen enfrenta esses desafios monitorando constantemente o ambiente político e legislativo, engajando-se ativamente em diálogos com grupos de interesse e associações comerciais, e estabelecendo parcerias estratégicas. Essas estratégias não apenas asseguram a conformidade legal e mitigam riscos, mas também criam oportunidades para a Volkswagen promover um ambiente de trabalho que valoriza a diversidade, a inclusão e o desenvolvimento sustentável.

Além disso, a empresa investe em programas de capacitação e desenvolvimento contínuo dos colaboradores, adaptando-se às mudanças nas políticas de emprego e às necessidades emergentes. Por exemplo, diante de mudanças nas leis trabalhistas, a Volkswagen pode implementar novos programas de treinamento para garantir que os líderes estejam preparados para gerenciar suas equipes de acordo com as novas regulamentações, promovendo assim um ambiente de trabalho mais justo e inclusivo.

Os dashboards e tabelas desenvolvidos no âmbito deste projeto são ferramentas vitais para monitorar como os fatores políticos e legislativos afetam o desempenho dos funcionários. Eles podem fornecer insights valiosos sobre tendências de engajamento, produtividade e satisfação no trabalho, permitindo que a Volkswagen responda de maneira ágil e informada. Isso inclui ajustes em políticas internas, estratégias de gestão de talentos e iniciativas de bem-estar, garantindo que a empresa não apenas cumpra com as exigências legais, mas também promova um ambiente de trabalho que potencialize o desempenho e o bem-estar dos seus colaboradores.

Assim, o entendimento profundo dos fatores políticos e legislativos, combinado com a implementação estratégica de dashboards e tabelas de desempenho, capacita a Volkswagen a criar um ambiente de trabalho resiliente, adaptativo e propício ao desenvolvimento e sucesso de seus colaboradores, alinhado com os objetivos estratégicos da empresa e as expectativas de um mercado em constante mudança.

**Econômico**

No ambiente operacional da Volkswagen, líder no mercado de transporte no Brasil, os fatores econômicos ocupam um papel crucial, não apenas por sua influência direta nas operações comerciais, mas também pelo impacto significativo que podem ter sobre a saúde mental, o estresse dos funcionários e, por consequência, seus níveis de engajamento. A empresa, detentora de uma significativa fatia de mercado — aproximadamente 16% em 2023, com vendas de cerca de 345.03 mil carros — enfrenta o desafio contínuo de navegar por um cenário econômico marcado por incertezas e volatilidades.

Este cenário econômico incerto pode afetar profundamente a segurança no emprego e as perspectivas de carreira dos funcionários, gerando estresse e potencialmente reduzindo o engajamento e a produtividade. Além disso, fatores como a renda disponível dos consumidores e o acesso restrito ao crédito refletem um ambiente econômico desafiador, que pode aumentar a pressão sobre os colaboradores, impactando negativamente sua saúde mental e engajamento.

A taxa de desemprego e suas variações têm implicações diretas na capacidade da Volkswagen de atrair e reter talentos. Um mercado de trabalho volátil pode intensificar o estresse entre os colaboradores, preocupados com a estabilidade de seus empregos e as dificuldades potenciais em encontrar novas oportunidades. Mudanças nas políticas monetárias, como ajustes na taxa SELIC e flutuações na inflação, afetam o custo de vida e o poder de compra, criando um cenário onde o estresse financeiro se torna um problema crescente para os funcionários, afetando sua saúde mental e seu engajamento com a empresa.

Para mitigar esses impactos e promover um ambiente de trabalho mais saudável e engajador, é imperativo que a Volkswagen implemente estratégias focadas não só em adaptar-se às mudanças econômicas, mas também em apoiar seus funcionários. Estratégias como promover uma comunicação transparente sobre a situação econômica da empresa e oferecer suporte, como programas de assistência financeira, podem ajudar a aliviar a ansiedade dos colaboradores.

Investir no desenvolvimento profissional e em oportunidades de crescimento pode reforçar a segurança no emprego e aumentar o engajamento, mostrando aos funcionários um caminho futuro promissor dentro da empresa. Além disso, a implementação de programas voltados para o bem-estar e saúde mental, que incluam acesso a serviços de psicologia e atividades de team building, é fundamental para construir uma cultura de suporte e engajamento.

Adotar políticas que promovam o equilíbrio entre trabalho e vida pessoal, como trabalho flexível, é uma estratégia eficaz para reduzir o estresse e aumentar o engajamento dos colaboradores. Ao reconhecer e endereçar proativamente os desafios impostos pelo ambiente econômico, a Volkswagen pode não apenas melhorar a experiência e o bem-estar de seus funcionários, mas também fortalecer sua posição como líder de mercado, criando um ciclo virtuoso de produtividade, inovação e comprometimento.

**Sociais**

Os aspectos sociais exercem uma influência significativa na Volkswagen, uma das líderes globais no setor automotivo, afetando diretamente as expectativas e preferências dos consumidores. A empresa está ciente da necessidade de alinhar suas operações com as tendências sociais emergentes, particularmente aquelas relacionadas à mobilidade, sustentabilidade e segurança. A demanda crescente por veículos que sejam ao mesmo tempo eficientes e ecologicamente responsáveis motiva a Volkswagen a investir em tecnologias alternativas, como os veículos elétricos e híbridos, em resposta às expectativas dos consumidores.

A companhia reforça seu compromisso com a ética nos negócios e com o respeito pelos direitos de colaboradores, clientes e parceiros comerciais. Isso se reflete em suas políticas que promovem a concorrência leal e a proteção de dados pessoais. O foco em segurança ocupacional e saúde dos colaboradores demonstra uma preocupação genuína com o bem-estar social e responsabilidade corporativa, alinhando-se às expectativas da sociedade para um tratamento justo e ético dos trabalhadores. A seleção criteriosa de fornecedores e a prevenção de conflitos de interesse mostram uma preocupação contínua com a responsabilidade social em toda a cadeia de suprimentos.

À medida que a população global continua a crescer e envelhecer, a Volkswagen enfrenta desafios e oportunidades únicas. O perfil etário em mudança afeta diretamente a dinâmica da força de trabalho e as estratégias de mercado da empresa. Essas transformações demográficas demandam uma adaptação constante das políticas de RH e dos critérios de avaliação de desempenho para refletir as competências e necessidades de uma força de trabalho que está em constante evolução.

Mudanças geracionais nas atitudes também têm um impacto significativo. A geração mais jovem, por exemplo, pode priorizar a flexibilidade e o equilíbrio entre vida pessoal e profissional mais do que as gerações anteriores. Isso influencia diretamente a forma como o desempenho é avaliado e incentivado na Volkswagen. A empresa precisa considerar fatores como saúde, educação, e mobilidade social ao desenvolver dashboards e tabelas para análise de desempenho, garantindo que estas ferramentas não apenas meçam eficácia e eficiência, mas também promovam um ambiente de trabalho que respeita e valoriza a diversidade e o bem-estar dos funcionários.

Os padrões de emprego, as tendências do mercado de trabalho e as atitudes em relação ao trabalho, que variam entre diferentes grupos etários e sociais, refletem-se nas expectativas e na satisfação dos funcionários da Volkswagen. A empresa está atenta a essas dinâmicas, adaptando suas ferramentas e processos de avaliação para promover um ambiente de trabalho mais inclusivo e respeitoso. Além disso, as atitudes sociais e os tabus, juntamente com as mudanças socioculturais recentes, podem afetar o clima organizacional e a eficácia dos métodos de avaliação de desempenho. A sensibilidade crescente a questões de diversidade e inclusão deve ser refletida nas políticas e critérios de avaliação de desempenho da empresa.

Finalmente, outros fatores socioculturais, como a evolução dos valores sociais e as expectativas dos consumidores, também impactam diretamente na operação e avaliação de desempenho na Volkswagen. A empresa deve se manter alinhada com essas mudanças, assegurando que suas estratégias de desenvolvimento de produtos e gestão de talentos reflitam os valores e prioridades da sociedade.

Ao incorporar estes insights ao desenvolvimento de dashboards e tabelas para análise de desempenho dos funcionários, a Volkswagen não apenas mede eficácia e eficiência, mas também fortalece sua posição como uma líder responsável no setor automotivo global, promovendo um ambiente de trabalho que respeita e valoriza a diversidade, a inclusão e o bem-estar de seus funcionários.

**Tecnológico**

No cenário tecnológico que se encontra em constante evolução, a Volkswagen enfrenta desafios e oportunidades significativos. A indústria automobilística, em particular, está passando por uma revolução tecnológica, com avanços que transformam a maneira como os veículos são projetados, fabricados e utilizados. A Volkswagen, mantendo seu compromisso com a inovação e a competitividade, investe pesadamente em pesquisa e desenvolvimento para criar veículos que não só atendam, mas também antecipem as demandas dos consumidores por eficiência, segurança e conectividade. A adoção de tecnologias emergentes, como veículos elétricos, inteligência artificial, condução autônoma e conectividade, é um pilar central dessa estratégia.

Esses investimentos são fundamentais não apenas para o desenvolvimento de produtos inovadores, mas também para a melhoria dos processos de produção e a oferta de experiências personalizadas aos clientes. A Volkswagen enfrenta, contudo, desafios relacionados à cibersegurança e à privacidade dos dados, especialmente com o aumento da conectividade dos veículos. Assegurar a segurança dos sistemas eletrônicos e proteger as informações dos clientes são prioridades para manter a confiança do consumidor e atender às rigorosas regulamentações de proteção de dados.

A empresa também se esforça para estar na vanguarda da tecnologia verde, implementando soluções avançadas que minimizam o impacto ambiental. A sustentabilidade é um valor intrínseco às operações da Volkswagen, refletido no investimento em tecnologias que promovem a eficiência energética e reduzem as emissões. A digitalização, incluindo o uso da realidade virtual e a automação de alto nível nas fábricas, permite não apenas uma produção mais eficiente, mas também oferece aos clientes novas maneiras de experimentar e personalizar seus veículos.

A inteligência artificial, em particular, é uma área de foco intenso, com aplicações que vão desde a melhoria da experiência do cliente até a otimização da produção e do design dos veículos. A Volkswagen está atenta às novas tecnologias emergentes e ao potencial impacto que podem ter sobre a indústria automobilística e sua própria operação. O avanço da automação e a adoção de tecnologias de manufatura avançada são exemplos de como a empresa está se preparando para o futuro, mantendo-se alinhada com as expectativas do mercado e as demandas por produtos mais sustentáveis e inovadores.

Além disso, a Volkswagen reconhece a importância de se manter atualizada sobre as tendências tecnológicas e os desenvolvimentos em áreas-chave, como a inteligência artificial e a realidade virtual, que têm o potencial de transformar radicalmente o setor. A colaboração com governos, instituições educacionais e polos tecnológicos pode oferecer acesso a novos conhecimentos e recursos, permitindo à empresa tirar proveito de avanços significativos nessas áreas. A mudança para trabalho remoto, impulsionada por mudanças na infraestrutura tecnológica, é outro fator que influencia a forma como a Volkswagen opera, destacando a necessidade de sistemas de trabalho flexíveis e seguros.

Considerando o projeto de desenvolver dashboards e tabelas para análise de desempenho dos funcionários, a Volkswagen pode explorar como essas tendências tecnológicas afetam não apenas a produção de veículos, mas também o engajamento e o bem-estar dos colaboradores. A implementação de novas tecnologias pode contribuir para um ambiente de trabalho mais eficiente, inovador e adaptável às necessidades dos funcionários, alinhando-se às tendências de digitalização e automação da indústria.

Portanto, a Volkswagen está bem posicionada para navegar no cenário tecnológico em constante mudança, adotando uma abordagem proativa para a inovação e a sustentabilidade. Ao investir em novas tecnologias e práticas sustentáveis, e ao permanecer atenta às oportunidades de colaboração e aprendizado, a Volkswagen pode assegurar sua posição de liderança na indústria automotiva, enfrentando os desafios tecnológicos atuais e futuros com confiança.

**Legais**

A Volkswagen Brasil reafirma seu compromisso inabalável com a conformidade legal e ética em todos os aspectos de suas operações. Este compromisso é evidenciado em sua Política de Privacidade, que garante a confidencialidade e proteção dos dados de seus clientes, delineando os procedimentos de coleta, uso e armazenamento dessas informações. A empresa reforça sua postura responsável ao condenar práticas como trabalho infantil, trabalho forçado e discriminação, não apenas respeitando as leis pertinentes, mas também promovendo uma cultura de respeito, inclusão e diversidade. Assim, a Volkswagen do Brasil assegura oportunidades iguais para todos os seus colaboradores e parceiros, enquanto mantém seus produtos e serviços em conformidade com os mais elevados padrões legais e de segurança.

Em relação às questões legais, a Volkswagen demonstra um compromisso firme em evitar práticas anticompetitivas e o uso indevido de informações privilegiadas, reforçando sua ética empresarial e preocupação com a transparência. Isso se traduz em uma abordagem cuidadosa em relação às leis de concorrência, proteção ao consumidor, propriedade intelectual e segurança do produto. A empresa reconhece a importância de aderir às diretrizes de segurança ocupacional e proteção de dados pessoais, garantindo o cumprimento das leis trabalhistas e de privacidade. Ao fazer isso, a Volkswagen não apenas evita possíveis penalidades legais, mas também preserva sua reputação como uma organização comprometida com a conformidade e a integridade em todas as suas operações.

Além disso, com o avanço das inovações tecnológicas e o acesso às informações dos veículos, surge uma preocupação crescente com a proteção de dados e privacidade. O Grupo Volkswagen agiu de diversas maneiras para manter a confiança dos usuários e consumidores, alinhando-se aos seus valores e ideais e garantindo sua posição de liderança no mercado. Outro fator relevante é a conformidade com as leis de comércio de exportação e importação, dada a volatilidade dos valores, para garantir um forte branding e a confiança dos investidores, adaptando-se às normas de governança corporativa e cumprindo todas as leis e regulamentos pertinentes. O respeito às leis trabalhistas é crucial para evitar problemas legais e preservar a reputação da empresa tanto no mercado brasileiro quanto internacional.

Para mitigar riscos e aproveitar oportunidades, a Volkswagen pode adotar estratégias como investir em treinamento contínuo para colaboradores, garantindo que estejam atualizados com as leis e regulamentos relevantes, reforçar as políticas de segurança cibernética para proteger os dados dos clientes contra ataques cibernéticos e estabelecer parcerias com organizações externas que promovam a ética nos negócios e a responsabilidade social corporativa.

**Ecológico**

O Grupo Volkswagen Brasil mantém um compromisso inabalável com a preservação ambiental e a sustentabilidade em todas as suas operações. Isso se reflete em sua Política Ambiental e de Energia, alinhada aos objetivos globais da empresa. A Volkswagen busca incessantemente reduzir seu impacto ambiental, promover a mobilidade sustentável e garantir a conformidade com todas as leis e regulamentações ambientais. Para isso, implementou um Sistema de Gestão e Compliance Ambiental robusto, visando conscientizar todos os colaboradores sobre os riscos associados às atividades e promover uma cultura de conformidade com as leis ambientais.

A Sustentabilidade está no cerne da Volkswagen do Brasil, que investe em processos produtivos e produtos cada vez mais sustentáveis, além de apoiar iniciativas em benefício de seus funcionários e da comunidade. Através da estratégia ACCELERATE, a Volkswagen busca se posicionar como líder em mobilidade sustentável, acelerando áreas-chave para o futuro, como a redução de emissões de carbono e a integração de software nos veículos. Com o compromisso de alcançar a neutralidade de carbono até 2050, a empresa implementou a estratégia global Way to Zero, incluindo investimentos significativos e parcerias estratégicas, como a colaboração com Raízen e Shell para a redução das emissões de CO2. Além disso, a Volkswagen demonstra seu compromisso com práticas ambientais, sociais e de governança por meio de iniciativas como o acordo de captação de dívida bancária com compromissos ESG, evidenciando seu compromisso com a sustentabilidade em todas as suas operações e relacionamentos.

A parceria e o acordo com a Raízen e Shell contemplam uma série de iniciativas que visam principalmente o uso do etanol e seus resíduos para a redução das emissões de CO2. A Volkswagen do Brasil reforça ainda mais seu compromisso com a sustentabilidade ao incorporar a tecnologia de tecidos à base de PET reciclado também na linha de veículos comerciais leves, revestindo bancos e portas da Nova Saveiro. Esse tecido reciclável atende às exigências de aparência e durabilidade da Volkswagen, proporcionando uma alternativa ambientalmente consciente para seus produtos.

### **1.4 Análise TAM, SAM, SOM**

Tam, Sam, e Som são métricas usadas em análises de mercado para entender o tamanho total do mercado (Total Addressable Market - TAM), o tamanho do mercado disponível (Serviceable Available Market - SAM) e a parcela do mercado que uma empresa pode capturar (Share of Market - SOM), respectivamente. Essas métricas são cruciais para avaliar oportunidades de negócios e desenvolver estratégias de marketing e vendas. Para a atual solução, o mercado macro identificado (TAM) é o de análise de dados, avaliado em 3,45 milhões, de forma média (SAM) é a área de saúde mental dentro das empresas e de forma micro (SOM) é o serviço de people analytics na áreas de RH dentro das empresas.


![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99208815/859137b6-f962-4de2-911a-a8a9af6a2e68)


**Cálculos**

TAM (Total Available Market): Quantidade de empresas que usam análise de dados no Brasil número de empresas no Brasil x porcentagem de empresas no Brasil que usam Data Analytics 5.748.599 x 0,60 = 3.449.159

SAM (Serviceable Available Market): Quantidade de empresas que se preocupam com a saúde mental de seus colaboradores no Brasil número de empresas no Brasil x porcentagem de empresas no Brasil que se preocupam com a saúde mental de seus funcionários 5.748.599 x 0,37 = 2.126.981

SOM (Serviceable Obtainable Market): Quantidade de empresas que utilizam data analytics para realizar a administração de saúde mental de seus colaboradores número de empresas no Brasil x porcentagem de empresas que consideraram People Analytics uma questão de alta prioridade x porcentagem dos investimentos em Big Data que vão para o RH nas empresas x porcentagem das empresas acreditam ter um bom entendimento sobre quais características dos profissionais impulsionam o desempenho em suas organizações 5.748.599 x 0.70 x 0.05 x 0.09 = 18.108

## 2. Entendimento da Experiência do Usuário

### **2.1 Personas**

Personas são perfis semifictícios de usuários típicos criados para representar os diferentes segmentos de usuários de um produto ou serviço. Elas são usadas no desenvolvimento e design de produtos para focar as decisões a partir da perspectiva do usuário e guiar a criação de soluções que atendam às suas necessidades e expectativas. A importância das personas reside na sua capacidade de ajudar as equipes a manterem uma abordagem centrada no usuário, melhorando a usabilidade e a experiência do usuário final, além de facilitar a comunicação e a priorização de recursos dentro das equipes de projeto. As personas desenvolvidas e apresentadas abaixo auxiliaram na criação dos wireframes e diagramas da solução proposta.


![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/518676e4-8c5d-41a2-bc0a-b85e039fc9d7)

**Figura 1**: Personas

**Fonte:** Elaboração Própria:

**1.1 Mário Prosperato**

- **Idade**: 54 anos
- **Cargo**: CEO
- **Objetivos**:
    - Alcançar o topo do ranking GPTW no setor e liderar a transformação cultural.
    - Manter uma visão unificada em meio à diversidade de operações e diretorias.
- **Necessidades**:
    - Visualização consolidada dos dados para estratégia e alinhamento corporativo.
    - Receber relatórios bem direcionados, com várias fontes de dados, para ações estratégicas.

**1.2 Laura Martinez**

- **Idade**: 32 anos
- **Cargo**: Gerente de operações de planta
- **Objetivos**:
    - Melhorar os indicadores de desempenho operacional e satisfação da equipe.
    - Equilibrar a eficiência operacional com a manutenção de um ambiente de trabalho positivo.
- **Necessidades**:
    - Dados analíticos para otimizar processos e desenvolvimento de equipe.
    - Prefere dashboards interativos que permitam uma análise aprofundada de sua unidade, customizável às suas necessidades.

Ambas as personas destacam a importância de ter acesso a dados relevantes e acionáveis para apoiar a tomada de decisões estratégicas e operacionais. Enquanto Mário se concentra na visão global e no alinhamento estratégico, Laura busca eficiência e melhoria contínua no nível operacional.

### **2.2 Wireframes**

Wireframes são esboços simplificados que representam a estrutura básica de uma página da web ou aplicativo, servindo como um plano para a interface de usuário. O objetivo dos wireframes é focar na disposição dos elementos e na funcionalidade sem se distrair com estilos gráficos, cores ou imagens. Eles são fundamentais no processo de design e desenvolvimento, pois permitem que designers, desenvolvedores e stakeholders visualizem e testem a arquitetura da informação, organizem os elementos de forma lógica e melhorem a experiência do usuário antes de investir tempo e recursos no desenvolvimento e no design final. Wireframes facilitam a comunicação de ideias, servem para coletar feedback antecipado e iterar rapidamente sobre o design, garantindo que o produto final seja funcional e alinhado com as expectativas dos usuários.

Na concepção dos dashboards apresentados, buscamos não apenas fornecer informações, mas também facilitar a extração de insights valiosos para os usuários finais. Optamos por uma abordagem diversificada na escolha dos gráficos e métodos de visualização para garantir que os usuários possam explorar os dados de maneira eficaz e intuitiva.

Inicialmente, escolhemos organizar nosso dashboard da seguinte forma:

**2.2.1. Início (login/cadastro)**


![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/438807f2-adb8-414e-94e2-bfb5edce7d00)

![Untitled 2](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/8b90fdc8-4924-4d1b-8997-e8998405c0ef)

![Untitled 3](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/79a60aff-5e1f-417d-a932-4e85a4269ac8)
<br> <br> <br> 
**Figuras 2, 3, e 4**: Telas de início e cadastro

**Fonte:** Elaboração Própria

A tela de login é o ponto de entrada crucial para os usuários, onde as credenciais são inseridas para acesso ao sistema, tais como email, senha e cargos. A inclusão da seleção de cargo na organização durante o login não só permite uma autenticação personalizada, mas também direciona os usuários para conteúdos relevantes, aumentando a eficiência da plataforma. Além disso, a direção para a tela de cadastro, caso o usuário não tenha um login, facilita a entrada de novos usuários no sistema.

**2.3. Organização geral do dashboard**

**2.3.1. Abas**

A implementação de abas na parte superior da interface facilita a navegação intuitiva do usuário, permitindo transições suaves entre diferentes seções de conteúdo. Essa estrutura não só aprimora a usabilidade, mas também contribui para uma análise de dados mais dinâmica, otimizando a eficiência da plataforma. As abas são organizadas de maneira a atender às diversas necessidades dos usuários, o que será explorado detalhadamente em seções subsequentes.

<img width="550" alt="Untitled 4" src="https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/11a97852-b482-4ac6-9b76-91bbb1296075"> <br> <br> 
**Figura 5:** Filtro de abas do dashboard

**Fonte**: Elaboração própria

**2.3.2 Filtros**

A presença de filtros personalizáveis na interface permite que os usuários ajustem a visualização dos dados conforme suas preferências, acessando as informações relevantes com maior liberdade. Esses filtros, ao serem aplicados, adaptam o conteúdo de todo o dashboard. Além disso, certos gráficos dispõem de filtros específicos, adaptando-se às particularidades de cada conjunto de dados.

<img width="136" alt="Untitled 5" src="https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/185bbac8-6047-494c-8521-fa9f14ffcd4b"> <br> <br> 


**Figura 6:** Filtro de abas do dashboard

**Fonte**: Elaboração própria

**2.4 Telas do dashboard**

**2.4.1 Início**

A tela “Iníco” do dashboard exibida oferece uma visão abrangente e bem estruturada dos dados de satisfação dos colaboradores e saúde no trabalho, organizada em seções distintas para facilitar o acesso e a interpretação das informações. Essa tela fornece os indicadores principais para uma primeira visão.
![Untitled 6](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/fdd5b026-57e3-4e8c-920e-f5e146766320)
<br> <br> <br> 

**Figura 7:** Página início

**Fonte**: Elaboração própria

**Seção "Visão Geral"**

- **Resultados Great Place to Work (GPTW)**: Esta área destaca os principais indicadores de satisfação dos colaboradores, como a porcentagem de respondentes e a nota média obtida em diferentes dimensões. O uso de comparações ano a ano permite aos líderes acompanhar a evolução do engajamento e identificar tendências. O Employee Net Promoter Score (eNPS) é uma métrica-chave para medir a lealdade dos funcionários e é destacado visualmente por cores que facilitam a interpretação rápida do status atual.

**Seção "Resultado Stiba"**

- **5 questões com notas mais altas/baixas**: Aqui são listadas as questões que receberam as melhores e piores avaliações, oferecendo uma visão clara dos pontos fortes e fracos percebidos pelos colaboradores. Essa seção é crucial para que os gestores entendam as áreas que requerem atenção e aquelas que devem ser mantidas ou reforçadas.

**Seção "Monitoramento da Área"**

- **Quantidade de atestados por mês**: Representa visualmente a frequência de atestados médicos ao longo do ano, uma métrica essencial para monitorar a saúde dos colaboradores e identificar padrões ou picos que podem indicar problemas sistêmicos.
- **Média de dias abonados por mês**: Semelhante à seção anterior, mas focada no tempo médio que os colaboradores estão ausentes do trabalho, o que pode influenciar a produtividade e indicar questões de bem-estar.
- **5 principais doenças e problemas da área**: Oferece uma análise dos problemas de saúde mais frequentes, fornecendo dados essenciais para o desenvolvimento de programas de saúde e bem-estar focados nas necessidades específicas da força de trabalho.
- **5 principais causas**: Relaciona as causas mais comuns que levam aos atestados, dando insights sobre fatores externos e internos que podem estar afetando a saúde dos colaboradores.
- **5 principais cargos afetados**: Apresenta quais cargos estão mais sujeitos a atestados, possibilitando ações direcionadas de prevenção e apoio para essas funções específicas.

**Recursos Adicionais**

- **Ícones de interatividade**: Os ícones de interrogação sugerem que há ajuda ou informações adicionais disponíveis, enquanto os ícones de filtro indicam que os dados podem ser segmentados ou filtrados para análises mais específicas.
- **Botões "Saiba mais"**: Cada seção possui um botão que convida os usuários a explorar os dados em maior profundidade, promovendo um engajamento ativo com o conteúdo do dashboard.

**2.4.2 GPTW**

Na tela do dashboard "Relatório GPTW", têm-se uma organização focada na exibição de métricas e comparações relevantes para entender a percepção dos colaboradores sobre a empresa, segmentadas em várias seções detalhadas:

![Untitled 7](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/ba487ca1-0a90-4a13-906f-fed02bd0d39a)


**Figura 8:** Relatório GPTW

**Fonte**: Elaboração própria

**Seção "Visão Geral dos Resultados Great Place to Work"**

- **Indicadores-chave**: Apresenta a taxa de resposta dos colaboradores, pontuações médias de dimensões específicas como orgulho e práticas culturais, e comparações com o ano anterior. Essa visão geral é valiosa para rastrear a evolução do clima organizacional e, por isso, posiciona-se no início da visualização da página.
- **Employee Net Promoter Score (eNPS)**: Esta métrica ressalta a disposição dos colaboradores em recomendar a empresa como um bom lugar para trabalhar. A codificação por cores e a representação numérica facilitam a rápida interpretação dos dados.

**Seção "Comparativo entre Áreas"**

- **Nota por área por aspecto no GPTW**: O mapa de calor fornece uma comparação visual entre diferentes áreas da empresa em relação a diversos aspectos do GPTW, como credibilidade e respeito. Esta é uma ferramenta essencial para identificar pontos fortes e áreas de melhoria em toda a organização. O filtro do gráfico em dropdown permite a escolha do que se deseja visualizar, sendo ‘Aspectos’, ‘Dimensões’ ou ‘Práticas culturais’.

**Seção "Frequência de Feedback x Índice de Confiança"**

- **Gráfico de dispersão**: Correlaciona a frequência de feedback recebido pelos colaboradores com o índice de confiança dentro da empresa. Esta análise pode revelar a importância do feedback na construção da confiança organizacional.

**Seção "Frequência de Feedback x Segurança Psicológica"**

- **Gráfico de radar**: Compara a frequência de feedback com a percepção de segurança psicológica em diferentes departamentos. Uma ferramenta vital para entender como a comunicação interna pode influenciar o bem-estar dos colaboradores.

**Seção "Satisfação Geral dos Colaboradores por Diretoria"**

- **Gráficos de barras horizontais**: Apresenta um ranking de satisfação dos colaboradores por diretoria, permitindo aos gestores identificar quais diretorias estão superando ou ficando abaixo das expectativas dos colaboradores em comparação ao total da empresa.

**2.4.3 Stiba**

A página do dashboard "Relatório Stiba" apresenta dados relacionados a uma pesquisa interna de satisfação e engajamento dos colaboradores, estruturada em várias seções para análise detalhada:

![Untitled 8](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/23bf2ed7-660f-4e6c-8156-76e34e13e804) <br> <br> <br> 


**Figura 9:** Relatório Stiba

**Fonte**: Elaboração própria

**Seção "Resultados Gerais"**

Essa visão geral é valiosa para rastrear a evolução do clima organizacional e, por isso, posiciona-se no início da visualização da página.

- **Taxa de Resposta**: Apresenta um alto índice de resposta dos colaboradores à pesquisa, indicando um forte envolvimento com os processos de feedback da empresa.
- **Nota Média das Unidades Organizacionais**: Mostra a pontuação média geral obtida, com uma comparação percentual com o ano anterior, oferecendo uma visão da evolução da satisfação interna.
- **Nota por Unidade Organizacional (Diretorias)**: Lista as pontuações por diretoria, permitindo comparações entre diferentes segmentos da empresa e destacando áreas de alto e baixo desempenho.

**Seção "Análise por Questão do Formulário"**

- **5 questões com notas mais altas/baixas**: Identifica as questões que tiveram as melhores e piores avaliações, fornecendo insights específicos sobre as percepções dos colaboradores. Isso pode direcionar áreas para reconhecimento e melhorias.

**Seção "Variação das Notas por Questão em Período de Tempo"**

- **Gráfico de tendências**: Traça a variação das notas de cada questão ao longo do tempo, crucial para identificar tendências, melhorias ou declínios na percepção dos colaboradores sobre questões específicas. Nesse gráfico é possível, a partir da passagem do mouse por cima dos valores do eixo X, visualizar a pergunta correspondente para uma melhor visualização.

**Seção "Avaliação de Cada Diretoria por Pergunta"**

- **Análise Detalhada**: Oferece uma comparação lado a lado de como cada diretoria respondeu a cada questão, permitindo uma análise granular que pode apontar para necessidades específicas de treinamento ou desenvolvimento em diferentes áreas da empresa. A partir de um filtro em dropdown é possível selecionar a pergunta que deseja visualizar essa comparação.

**2.4.4 Saúde**

A página do dashboard intitulada "Monitoramento de Saúde" é dedicada a fornecer uma visão geral e análises detalhadas da saúde ocupacional dos colaboradores, utilizando várias métricas e categorias de dados:

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/90d7027e-8050-4ae3-8fbc-50e0a9c790f1) <br> <br> 


**Figura 10:** Monitoramento de Saúde

**Fonte**: Elaboração própria

**Visão Geral da Saúde Ocupacional**

- **Quantidade de Atestados por Mês**: Exibe um gráfico de linha que traça a quantidade de atestados médicos ao longo do ano, o que pode ser útil para identificar tendências ou padrões sazonais de ausência por motivos de saúde.
- **Média de Dias Abonados por Mês**: Um gráfico de barras que mostra a média de dias de ausência remunerada, oferecendo um olhar sobre o impacto potencial na produtividade e na gestão do trabalho.

**Análise de Condições de Saúde**

- **5 Principais Doenças e Problemas da Área**: Lista as condições de saúde mais comuns relatadas, permitindo que a empresa direcione recursos e estratégias de prevenção ou intervenção onde são mais necessários.
- **5 Principais Causas**: Foca nas causas mais frequentes para os atestados médicos, como sobrecarga e mudança de função, fornecendo insights sobre os fatores de risco dentro do ambiente de trabalho.
- **5 Principais Cargos Afetados**: Identifica os cargos com maior número de atestados, permitindo ações específicas de melhoria nas condições de trabalho ou programas de saúde direcionados.

**Análise por Demografia** Para entender a relação entre dados de saúde e demografia, criamos dois gráficos específicos. Um deles é um gráfico de barras duplo, que analisa as cinco principais doenças em relação ao gênero. Essa visualização permite uma comparação direta entre diferentes grupos demográficos. O segundo gráfico de barras analisa as principais doenças de acordo com faixas etárias, dividindo os colaboradores em categorias específicas para investigar possíveis tendências relacionadas à idade.

- **5 Principais Doenças e Problemas por Gênero**: Apresenta uma comparação entre gêneros nas condições de saúde mais reportadas, o que pode destacar necessidades específicas de saúde ocupacional relacionadas ao gênero.
- **5 Principais Doenças e Problemas por Faixa Etária**: Oferece uma análise da incidência de condições de saúde por idade, possibilitando a adaptação de programas de saúde e bem-estar para diferentes demografias na força de trabalho.

**Engajamento com Programas de Bem-Estar** Para promover o bem-estar dos colaboradores, desenvolvemos um relatório que relaciona o engajamento com programas de bem-estar. Esse relatório inclui uma representação visual da quantidade de sessões realizadas por colaborador, acompanhada por gráficos que destacam a distribuição dessas sessões ao longo do tempo. Essa abordagem visa incentivar a participação em iniciativas de saúde e bem-estar.

- **3 Sessões**: Destaca o número médio de sessões de bem-estar realizadas por colaborador, o que pode indicar o nível de engajamento dos colaboradores com os recursos de saúde mental disponibilizados pela empresa.
- **Média de Sessões Realizadas no Zenklub por Colaborador por Mês**: Compara o engajamento em sessões de bem-estar entre diferentes plantas da empresa, mostrando quais áreas estão mais ativas nos programas de saúde mental.

Ao projetar esses elementos, incorporamos ícones intuitivos de pesquisa e filtro para aprimorar a experiência do usuário, facilitando a análise e a interpretação dos dados e garantindo uma navegação fluida e eficiente na plataforma.

**2.5 Considerações finais**

Os wireframes foram projetados tendo em vista a acessibilidade e a eficiência para líderes operacionais e executivos que requerem análise profunda e ação estratégica baseada em dados robustos. A escolha por um design modular e a disposição de abas atendem à necessidade de filtragem específica por diretoria e hierarquia, refletindo a complexa estrutura organizacional e as restrições de acesso necessárias. A implementação de funcionalidades como filtros dinâmicos e a possibilidade de comparações interativas entre diferentes conjuntos de dados foram impulsionadas pelo desafio de sintetizar múltiplas fontes de informação num formato que ofereça insights rápidos e precisos.

A antecipação da ação do usuário foi incorporada por meio de um sistema de login inteligente que ajusta o conteúdo do dashboard com base no cargo e na área de atuação, promovendo uma experiência altamente personalizada desde o início. As micro-interações, como animações sutis durante a seleção de filtros e a expansão de dados, foram desenhadas para fornecer feedback imediato às ações dos usuários, aumentando a intuitividade e a eficiência da interface.

O design interativo dos wireframes é o resultado de um processo iterativo informado pelo feedback direto dos usuários finais e stakeholders. As mudanças implementadas incluíram a simplificação da interface para aumentar a velocidade de carregamento, melhorando a clareza das visualizações de dados e refinando o fluxo de trabalho do usuário para minimizar a curva de aprendizado e o tempo necessário para realizar análises profundas.

- **Apresentação Geral**: Foi alcançado um equilíbrio cuidadoso entre a densidade de informações e a clareza visual, onde cada elemento foi colocado com o propósito de manter a interface limpa, priorizando a usabilidade e a compreensão rápida.
- **Legibilidade dos Elementos**: Os elementos foram projetados para serem acessíveis, com consideração especial à acessibilidade e à inclusão, garantindo que os elementos sejam legíveis em uma variedade de dispositivos e sob diferentes condições de visualização.
- **Consistência e Padronização**: A consistência em design transcende a estética; ela foi implementada para reforçar a lógica operacional do dashboard. A padronização dos elementos visuais não é apenas uma escolha estilística, mas uma decisão funcional que promove a eficiência cognitiva, permitindo que os usuários reconheçam padrões de interação e compreendam rapidamente as visualizações de dados.

O design dos wireframes reflete um compromisso com um processo de desenvolvimento centrado no usuário, garantindo que as necessidades, objetivos e desafios dos usuários sejam atendidos de forma eficaz. Ao fornecer uma base sólida para a iteração de design, os wireframes servem como um mapa crucial para o desenvolvimento subsequente, assegurando que as soluções finais sejam alinhadas com as estratégias e operações da empresa, bem como com a cultura e o bem-estar dos colaboradores.

## 2.6 Mockups avançados

### **2.6.1. Guia de estilos**

Nessa seção você encontrará as especificações da nossa paleta de cores, tipografia, iconografia, e outros elementos de design que formam a essência da experiência do usuário em nosso dashboard. Este guia serve como uma bússola para designers, desenvolvedores e qualquer um que contribua para o ecossistema do produto, assegurando que cada elemento seja um reflexo do nosso compromisso com a excelência e a clareza.

### **2.6.2 Paleta de cores**
![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled.png) <br> <br> 

A paleta de cores para o Dashboard foi meticulosamente selecionada para promover uma experiência de usuário clara e eficiente. Cada cor foi escolhida não apenas pela sua estética, mas também pela funcionalidade e psicologia das cores em relação à usabilidade e acessibilidade. As cores foram selecionadas de acordo com o Guia de Estilos da Volkswagen e também a partir da biblioteca Material UI, a ser utilizada na construção do frontend.

### **2.6.3 Iconografia**
![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%201.png) <br> <br> 

A iconografia do Dashboard foi cuidadosamente escolhida para fornecer uma navegação intuitiva e melhorar a compreensão do usuário sobre as funcionalidades disponíveis. Cada ícone é projetado para ser imediatamente reconhecível e funcional, garantindo uma experiência do usuário consistente e eficiente.

- **Logo Volkswagen**: Representa a marca e serve como um ponto de referência inicial para os usuários.
- **Fábrica**: Simboliza a produção e operações industriais, facilitando a identificação rápida de seções relacionadas às plantas da empresa, citadas pelos stakeholders.
- **Busca**: Oferece uma maneira rápida de acessar informações específicas, um elemento essencial para a eficiência do usuário.
- **Confirmar (Check)**: Indica uma ação positiva ou conclusão de uma tarefa, proporcionando feedback claro sobre as interações bem-sucedidas.
- **Calendário**: Permite aos usuários localizar os filtros relacionados às datas.
- **Cancelar (X)**: Oferece aos usuários a opção de desfazer ações, um componente crítico para uma boa experiência do usuário.
- **Trabalho**: Destaca o filtro relacionados à tipos de carga de trabalho, mencionados pelos stakeholders.
- **Voltar (Seta para esquerda)**: Fornece uma navegação fácil para retornar à tela ou seção anterior.
- **Localização**: Identifica o filtro para a localização das plantas, mencionadas pelos stakeholders.
- **Pergunta**: Utilizado para indicar suporte ou fornecer ajuda adicional sobre gráficos específicos.
- **Informações (i)**: Oferece informações mais aprofundadas sobre os tópicos do dashboard.

Este conjunto de ícones foi desenvolvido para ser simples e universal, minimizando a necessidade de aprendizado e melhorando a usabilidade geral do dashboard. A escolha das cores para os ícones segue a paleta definida, mantendo a harmonia visual e a acessibilidade em todo o design.

### **2.6.4 Tipografia**

## **2.7 Dashboard**

Essa seção é um mergulho profundo na anatomia do nosso Dashboard de Saúde Mental vs. Indicadores de Engajamento, descrevendo meticulosamente cada tela e sua funcionalidade. Para cada interface, discutiremos os gráficos, a interatividade e o fluxo do usuário, justificando as escolhas de design que contribuem para a experiência geral do usuário. Ao adentrarmos nas especificidades de cada tela, revelaremos como a estética, a funcionalidade e a lógica de navegação se entrelaçam para criar uma ferramenta robusta e intuitiva que não apenas informa, mas também engaja e capacita os colaboradores da Volkswagen do Brasil.

### **2.7.1 Tela - “Início”**
![Untitled 9]( https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%202.png
) <br> <br> 

A tela "Início" do dashboard oferece uma experiência compreensiva e estruturada, permitindo aos colaboradores da Volkswagen do Brasil uma análise rápida e eficaz dos indicadores de desempenho e saúde organizacional geral. Ela é dividida em várias seções:

**Elementos do Dashboard:**

1. **Resultados Great Place to Work**: Mostra a nota geral das dimensões e práticas culturais com uma comparação ano a ano, destacando áreas de orgulho e pontos a cuidar.
2. **Resultados Sitba**: Apresenta cinco questões com notas mais altas e mais baixas, permitindo um entendimento rápido das áreas de força e melhoria.
3. **Monitoramento da Área**: Esta seção fornece dados sobre a quantidade de atestados por mês e a média de dias abonados, dando um panorama da saúde da equipe.

Cada gráfico contido nessa página será abordados de maneira mais profunda mais abaixo.

### **2.7.2 Tela - “GPTW”**
![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%203.png)

A tela "GPTW" do dashboard oferece uma análise aprofundada dos resultados obtidos na pesquisa Great Place to Work, permitindo um entendimento detalhado sobre o ambiente de trabalho percebido pelos colaboradores. Através de uma interface rica em dados e interativa, os usuários podem explorar métricas vitais e identificar tendências e áreas para desenvolvimento.

**Elementos do Dashboard:**

1. **Porcentagem de Respondentes**: Este indicador compara o total de colaboradores da empresa com o número que respondeu à pesquisa, refletindo o engajamento da equipe no processo de feedback corporativo.
2. **Nota Média das Dimensões**: Este KPI exibe a média das avaliações coletadas para diferentes dimensões organizacionais, acompanhadas de uma análise comparativa que destaca a evolução ou regressão em relação ao período anterior, além de indicar a dimensão com a pontuação mais elevada.
3. **Nota Média das Práticas Culturais**: Similar ao KPI de dimensões, este mostra a média das avaliações para as práticas culturais, com um comparativo temporal e destaque para a prática melhor avaliada.
4. **Employer Net Promoter Score (eNPS)**: Este score classifica a disposição dos colaboradores em recomendar a empresa como um bom lugar para trabalhar, situando a pontuação em uma escala padronizada de lealdade de funcionários.
5. **Comparativo entre Áreas**: Utilizando uma matriz de cores, este gráfico permite aos usuários visualizar e comparar a performance de cada área da empresa em relação a diferentes aspectos do GPTW, identificando pontos fortes e áreas para melhoria.
6. **Correlações de Feedback e Confiança**: Gráficos de dispersão que ilustram a relação entre a frequência de feedback e os índices de confiança e segurança psicológica, respectivamente, destacando a importância do feedback contínuo para o bem-estar organizacional.
7. **Satisfação Geral dos Colaboradores**: Um gráfico de barras horizontal que fornece uma visão geral da satisfação dos colaboradores por departamento, com a capacidade de filtrar por aspectos específicos para análises mais focadas.
8. **5 Questões Mais Altas e Mais Baixas**: Duas listas que destacam as questões com as maiores e menores notas, proporcionando insights sobre as percepções mais positivas e as áreas que requerem atenção imediata.

Cada elemento da tela "GPTW" é cuidadosamente projetado para proporcionar insights estratégicos, fomentar o engajamento dos colaboradores e direcionar ações de melhoria contínua na cultura organizacional.

### **2.7.3 Tela - “Stiba”**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%204.png)
A tela "Stiba" do dashboard oferece uma análise aprofundada dos resultados obtidos na pesquisa interna da empresa, permitindo um entendimento detalhado sobre o ambiente de trabalho percebido pelos colaboradores. Através de uma interface rica em dados e interativa, os usuários podem explorar métricas vitais e identificar tendências e áreas para desenvolvimento.

**Elementos do Dashboard:**

1. **Porcentagem de Respondentes:** Exibe a taxa de participação na pesquisa Stiba em relação ao total de colaboradores. Avalia o engajamento dos colaboradores com iniciativas de feedback interno.
2. **Nota Média da Pesquisa:** Mostra a média geral das avaliações coletadas na pesquisa, fornecendo uma visão geral do sentimento dos colaboradores em relação à empresa.
3. **Nota por Diretoria**: Relaciona as médias de avaliação de cada diretoria, possibilitando comparações setoriais para que o RH possa identificar áreas de destaque e oportunidades de melhoria em diferentes departamentos.
4. **Score dos Valores de Cultura (%)**: Representa o alinhamento dos colaboradores com os valores corporativos ao alinhar cada uma das perguntas com um pilar da cultura organizacional e assim busca medir a aderência e o compromisso com a cultura organizacional.
5. **5 Questões com Notas Mais Altas e Mais Baixas**: Lista as questões que receberam as maiores e menores notas na pesquisa, destacando as forças e áreas que precisam de atenção segundo a percepção dos funcionários.
6. **Avaliação de Cada Diretoria por Pergunta (Anualmente)**: Compara o desempenho ano a ano das diretorias em perguntas específicas, que podem ser selecionadas pelos usuários, permitindo a análise de evolução ou regressão em áreas-chave ao longo do tempo.
7. **Nota por Pergunta**: Detalha as notas atribuídas a cada pergunta da pesquisa, oferecendo um entendimento granular das opiniões dos colaboradores, com o objetivo de compreender profundamente a perspectiva dos colaboradores sobre questões específicas.

### **2.7.4 Tela - “Saúde”**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%205.png)
A tela “Saúde” fornece uma visão abrangente da saúde ocupacional dentro de uma organização, permitindo aos usuários filtrar os dados por ano, tipo de trabalho e localidade da planta a partir dos dados sobre o uso do Zenklub, atestados e uso dos planos de saúde dos colaboradores.

**Elementos do dashboard:**

1. **Quantidade de Atestados por Mês:** o KPI ****mostra o número total de atestados médicos com CIDF em comparação aos atestados totais por mês, possibilitando comparar os dados atuais com o período anterior, destacando a variação percentual.
2. **Quantidade de Atestados por Dias Abonados:** gráfico de linha que apresenta o número de dias abonados por atestados médicos ao longo do ano, demonstrando quais são as maiores tendências dos atestados
3. **Quantidade de Sessões do Zenklub por colaborador:** o KPI ****mostra o número médio de sessões do Zenklub por colaborador, possibilitando comparar os dados atuais com o período anterior, destacando a variação percentual.
4. **Média de Dias Abonados por Mês**: barras verticais que representam a média de dias abonados em cada mês, possibilitando demonstrar a sazonalidade de abono dos colaboradores.
5. **Média de Dias Abonados por Planta**: Barras verticais que mostram a média de dias abonados, divididos por localidade da planta, possibilitando demonstrar a sazonalidade de abono dos colaboradores em cada localidade da empresa.
6. **Principais Causas de Doenças e Problemas:** Duas tabelas que listam as cinco principais causas de doenças e os cinco principais cargos afetados, com a quantidade correspondente, permitindo identificar a correlação de causa com doenças e os cargos.
7. **Quantidade de Atestados CIDF por Diretoria:** Tabela que mostra a quantidade de atestados por diretoria, utilizando o código CIDF, permitindo entender quais são as diretorias mais afetadas pelas doenças de saúde ocupacional.
8. **Média de Sessões Realizadas no Zenklub por Colaborador:** Gráficos de barras mostrando a média mensal de sessões de terapia realizadas por colaborador em cada planta da empresa
9. **Tendência de Saúde Mental por CIDF:** Gráfico de linhas com diversas séries que representam diferentes categorias de saúde mental e como a quantidade de ocorrências desses CIDFs de acordo com o mês.
10. **Quantidade de Atestados por Sessões do Zenklub:** Gráfico de dispersão que correlaciona a quantidade de atestados com o número de sessões de terapia realizadas no Zenklub, permitindo demonstrar tendências de redução ou aumento no número de atestados à medida que decresce/aumentam o número de sessões do app.

### **2.7.5 Tela - “GPTW x Stiba”**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%206.png)
A tela “GPT x Stiba” fornece uma comparação direta entre as percepções do clima empresarial captadas pelas pesquisas GTPW (Great Place to Work) e Stiba, oferecendo insights importantes sobre o ambiente de trabalho e a satisfação dos colaboradores.

**Elementos do Dashboard:**

1. **Nota Geral do Stiba e GPTW - Nota Geral**: Apresenta a nota geral para cada pesquisa, a quantidade de colaboradores que participaram e a variação percentual em comparação com o ano anterior.
2. **5 Questões com Notas Mais Altas e Mais Baixas**: Listas que apresentam as questões com maiores e menores notas para Stiba e GPTW, permitindo identificar pontos fortes e áreas a melhorar.
3. **Variação de Notas das Pesquisas por Diretoria**: Gráfico de linha que mostra a variação das notas por diretoria para cada pesquisa.
4. **Gráficos de Pareto de Questões**: Gráficos de Pareto que destacam as questões mais votadas para Stiba e GPTW, ajudando a priorizar questões críticas.
5. **Nota por Pergunta**: Tabelas que detalham as notas atribuídas a cada pergunta individual nas pesquisas Stiba e GPTW.
6. **Variação das Notas por Plantas:** O gráfico de linhas exibe a variação das notas por diferentes plantas ao longo do tempo, ajudando a visualizar tendências e discrepâncias entre as localidades.
7. **Tabela de Áreas Críticas**: Lista as áreas da empresa com pontuação inferior a 70 (nota base fornecida pelos stakeholders) para as duas pesquisas, organizando as áreas mais críticas em primeiro lugar.

O dashboard é uma ferramenta valiosa para entender a percepção dos colaboradores sobre a empresa, avaliar a eficácia das iniciativas de clima organizacional e identificar áreas para melhorias contínuas.

### **2.7.6 Tela - “Saúde x Clima empresarial”**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%207.png)
A tela “Saúde x Clima empresarial” integra dados de saúde ocupacional e clima empresarial para fornecer uma visão holística do bem-estar dos colaboradores e seu engajamento na empresa. Ele utiliza métricas interativas para correlacionar saúde e satisfação no trabalho.

**Elementos do Dashboard:**

1. **Média de Dias Abonados**: Indica a média de dias abonados e sua variação percentual com o período passado.
2. **Quantidade de Sessões do Zenklub**: Mostra o total de sessões realizadas pela plataforma Zenklub e sua variação percentual com o período passado.
3. **GPTW - Índice de Saúde e Satisfação**: Apresenta um índice que combina a saúde e a satisfação dos colaboradores, fornecendo uma visão geral de bem-estar. A métrica é calculada da seguinte maneira:
    
    > ISE = (1 - (QA Normalizado)) * NG
    > 
    - QA Normalizado é a quantidade de atestados dividida pelo número total de colaboradores ou dias úteis.
    - NG é a nota do GPTW normalizada para uma escala de 0 a 100.
    
    Ao ter um valor mais alto de ISE sugeriria um melhor engajamento e uma menor incidência de atestados, indicando uma saúde organizacional mais robusta, ao tempo que um valor mais baixo indicaria mais atestados e/ou menor satisfação, sinalizando áreas que podem precisar de atenção.
    
4. **Stiba - Índice de Saúde e Satisfação**: Apresenta um índice que combina a saúde e a satisfação dos colaboradores, fornecendo uma visão geral de bem-estar. A métrica é calculada da mesma maneira da anterior, mas com a pesquisa Stiba.
5. **Índice de bem estar e engajamento:** A métrica é calculada assim como o Índice de Saúde e Satisfação, mas utiliza a quantidade de sessões do Zenklub e é calculada para cada pesquisa (Stiba e GPTW).
6. **Saúde Ocupacional x Engajamento**: Gráficos de dispersão que correlacionam as condições de saúde ocupacional, com o filtro para cada tipo de CIDF, com os níveis de engajamento, buscando entender correlações entre os dois dados.
7. **Sessões de Zenklub x GPTW**: Correlaciona o número de sessões de terapia com os índices de clima organizacional do GPTW, permitindo filtrar por cada aspecto do GPTW e buscando entender como esses dados se correlacionam.
8. **Quantidade de Atestados x Notas de Engajamento**: Gráfico de linhas que mostra a relação entre a quantidade de atestados e as notas de engajamento (Stiba e GPTW) por planta.
9. **Quantidade de Sessões do Zenklub x Notas de Engajamento**: Similar ao gráfico anterior, mas foca nas sessões do Zenklub.
10. **Tabela de Áreas Críticas**: Lista as áreas da empresa com pontuação inferior a 70 (nota base fornecida pelos stakeholders), mostrando a proporção de atestados e sessões do Zenklub, além das notas do GPTW e Stiba.

Este dashboard é uma ferramenta estratégica para líderes e gestores de RH, permitindo intervenções focadas e o desenvolvimento de programas de saúde e bem-estar alinhados com o engajamento dos colaboradores.

### **2.7.7 Filtros**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%208.png)
Os filtros são ferramentas interativas no dashboard que permitem aos usuários refinar e segmentar os dados exibidos de acordo com critérios específicos. Eles são fundamentais para personalizar a visualização e realizar análises mais direcionadas.

**Filtros Disponíveis**

1**. Filtro pelo Ano:** Permite que os usuários selecionem o ano para o qual desejam visualizar os dados.

- **Opções Disponíveis**:
    - 2022
    - 2023
- **Impacto**: Atualiza todos os componentes do dashboard para refletir informações apenas do ano selecionado.
1. **Filtro por Tipo de Trabalho:** Habilita a seleção do tipo de contrato de trabalho dos colaboradores.
- **Opções Disponíveis**:
    - Administrativo
    - Mensalista
    - Horista
- **Impacto**: Filtra os dados para mostrar apenas os referentes ao tipo de trabalho escolhido, permitindo análises específicas por categoria de emprego.
1. **Filtro por Planta:** Possibilita a seleção de uma planta específica da empresa.
- **Opções Disponíveis**:
    - Anchieta
    - Curitiba
    - São Carlos
    - Taubaté
- **Impacto**: Limita a visualização dos dados às informações correspondentes à planta selecionada, oferecendo uma análise regionalizada.

Ao selecionar a opção desejada clicando no item correspondente, o dashboard automaticamente atualizará para refletir os dados correspondentes aos filtros aplicados. Para remover um filtro, clique novamente no item selecionado ou na opção de limpar filtro (x).

Os filtros podem ser combinados para uma análise mais precisa. Por exemplo, selecionar o ano de "2023", o tipo de trabalho "Horista" e a planta "Curitiba" fornecerá dados específicos para essa configuração. A aplicação dos filtros não altera os dados brutos, apenas a visualização dos mesmos no dashboard.

### **2.7.8 Login**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%209.png)
A tela de login busca ser simples e intuitiva aos usuários. Essa tela é essencial para definir os dados a serem visualizados pelos usuários, pois como descrito pelos stakeholders, cada nível de cargo poderá ver determinados dados. Para esse mockup, todo o design e os gráficos foram pensados para um colaborador de RH, que possui a visão sobre todas as áreas, mas, quando o usuário for algum BP, por exemplo, ele só poderá visualizar sua própria área no dashboard. Essa restrição é feita no momento do login, a partir do email e cargo do colaborador.

### **2.7.9 Perfil**

O sistema de gestão de usuários permite que administradores do sistema (colaboradores de RH) realizem operações de cadastro, edição e exclusão de usuários, além de visualizarem um diretório de colaboradores existentes.

**→ Tela de Diretório de Usuários**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%2010.png)
Essa tela lista todos os usuários cadastrados no sistema e permite a navegação para ações de edição ou exclusão.

- **Componentes**:
    - Lista de usuários com nome e cargo.
    - Botões de ação para editar ou excluir usuários individuais.

**→ Tela de Cadastro de Usuário**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%2011.png)
Essa tela permite o cadastro de novos usuários no sistema.

- **Componentes**:
    - Formulário com campos para nome completo, e-mail, cargo e senha.
    - Botão "Cadastrar" para submeter o formulário.
    - Botão "Cancelar" para descartar as informações inseridas e voltar ao diretório.

**→ Tela de Edição de Usuário**

![Untitled 9]
Essa tela habilita a edição das informações de um usuário existente.

- **Componentes**:
    - Formulário preenchido com as informações atuais do usuário selecionado.
    - Botão "Salvar" para atualizar as informações no sistema.
    - Botão "Cancelar" para rejeitar as alterações e voltar ao diretório.

**→ Confirmação de Cadastro**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%2013.png) 
Modal que solicita confirmação antes de finalizar o cadastro de um novo usuário.

- **Componentes**:
    - Mensagem de confirmação: "Você confirma o cadastro deste usuário?"
    - Botões "Confirmar" para prosseguir com o cadastro e "Cancelar" para voltar ao formulário.

**→ Sucesso de Cadastro**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%2014.png)
Modal que informa que o usuário foi cadastrado com sucesso.

- **Componentes**:
    - Mensagem de sucesso: "O usuário foi cadastrado com sucesso!"
    - Botão "Voltar ao início" para retornar ao diretório de usuários.

**→ Confirmação de Edição**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%2015.png) 
Modal que solicita confirmação antes de salvar as alterações de um usuário.

- **Componentes**:
    - Mensagem de confirmação: "Você confirma a edição deste usuário?"
    - Botões "Confirmar" para salvar as alterações e "Cancelar" para voltar ao formulário de edição.

**→ Sucesso de Edição**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%2016.png) 
Modal que notifica que as informações do usuário foram atualizadas com sucesso.

- **Componentes**:
    - Mensagem de sucesso: "O usuário foi editado com sucesso!"
    - Botão "Voltar ao início" para retornar ao diretório de usuários.

**→ Confirmação de Exclusão**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%2017.png)
Modal que requer confirmação antes de excluir permanentemente um usuário.

- **Componentes**:
    - Mensagem de confirmação: "Você confirma a exclusão deste usuário?"
    - Botões "Confirmar" para excluir o usuário e "Cancelar" para voltar ao diretório.

**→ Sucesso de Exclusão**

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/docs/Mockups%20avanc%CC%A7ados/Untitled%2018.png) 
Modal que confirma que o usuário foi excluído do sistema.

- **Componentes**:
    - Mensagem de sucesso: "O usuário foi excluído com sucesso!"
    - Botão "Voltar ao início" para retornar ao diretório de usuários.

## 3. Relatório de Testes de Usabilidade e Acessibilidade

### **3.1 Metodologia**

Para avaliar a usabilidade e acessibilidade dos dashboards desenvolvidos, empregamos uma metodologia estruturada e focalizada em testes moderados e controlados para a análise de variados fatores, como saúde, clima empresarial e satisfação no trabalho dos funcionários da Volkswagen. Para essas análises, foi selecionado um grupo diversificado de 4 participantes em idade, habilidades visuais e compreensão dos temas apresentados nos dashboards.

Reconhecendo a complexidade da deficiência, que reflete a interação entre as características físicas e cognitivas do indivíduo com seu ambiente, incluímos na nossa amostra participantes com diferentes perfis. Entre eles, um homem com miopia, para avaliar possíveis limitações visuais no uso do dashboard; um indivíduo mais velho, com menor familiaridade com o assunto, um indivíduo mais novo visando entender sua capacidade de ter uma experiência enriquecedora; e um integrante de outro grupo da nossa turma trabalhando em outra solução no mesmo projeto para avaliar a intuição e a facilidade de uso da interface.

Cada participante foi avaliado individualmente, com a orientação de um membro da nossa equipe, através de um conjunto de perguntas pré-definidas voltadas para a exploração dos dashboards, com foco em identificar problemas de usabilidade e acessibilidade. O Guia de Critérios de Acessibilidade para Conteúdo Web (WCAG) foi utilizado como principal referência para avaliação, com os testes centrados nos quatro pilares fundamentais da acessibilidade na web: Perceptível, Operável, Compreensível e Robusto.

- Perceptível: Garantir que todas as informações e componentes da interface sejam perceptíveis a todos os usuários.
- Operável: Assegurar que todos os componentes e navegação sejam operáveis.
- Compreensível: Tornar a informação e a operação da interface compreensíveis.
- Robusto: O conteúdo deve ser suficientemente robusto para ser interpretado por uma ampla gama de tecnologias assistivas.

As observações e resultados dos testes foram sistematicamente documentados em uma planilha do Google Sheets, proporcionando uma organização eficaz e uma análise clara dos dados coletados, incluindo os objetivos de cada teste, perguntas feitas e resultados alcançados.

Link Google Sheets: [https://docs.google.com/spreadsheets/d/1ELJfDc3KD4n8Ta11AePpBrPRnUkqEcE7puLaGyx0Nzc/edit#gid=0](https://docs.google.com/spreadsheets/d/1ELJfDc3KD4n8Ta11AePpBrPRnUkqEcE7puLaGyx0Nzc/edit#gid=0)

### **3.2 Resultados**

Os testes nos forneceram uma visão detalhada sobre os aspectos intuitivos e de fácil compreensão dos dashboards, bem como identificaram áreas para aprimoramento. Os achados reforçam a importância de conduzir avaliações regulares para detectar e resolver potenciais problemas que podem não ser evidentes para os desenvolvedores.

**3.2.1 - Navegação Consistente - Compreensível [AA]**

Concentramos nossa análise na página "Visão Geral", notável por sua riqueza em gráficos, tabelas, KPIs e índices, dada sua capacidade de fornecer um panorama extenso das funcionalidades do dashboard. A uniformidade na navegação recebeu elogios unânimes dos avaliadores, que enfatizaram sua eficiência em promover um padrão coeso de apresentação, interação e disposição de elementos, tais como campos de pesquisa, que se mantêm constantes em diversas interfaces.

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/vg1.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/vg1.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/vg2.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/vg2.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/vg3.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/vg3.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/vg4.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/vg4.png)

O retorno dos usuários foi majoritariamente positivo, sublinhando o êxito em assegurar uma navegação contínua e intuitiva, o que eleva a qualidade da experiência do usuário. Por outro lado, uma sugestão de um dos usuários apontou que, embora a navegação seja fluida, a experiência poderia ser enriquecida por meio de variações na apresentação visual para tornar a interface mais viva e convidativa, sem prejuízo à funcionalidade.

Observamos múltiplas avaliações e comentários positivos que reforçam o bom desempenho em estabelecer e aprimorar uma navegação fluida. Um dos participantes louvou a consistência na organização dos elementos de navegação por todo o dashboard, mencionando a facilidade em transitar entre as diversas seções. Outro destacou a simplicidade em localizar funcionalidades recorrentes, como busca e menus, graças à sua colocação uniforme, facilitando o aprendizado e uso do dashboard até por usuários iniciantes ou menos habituados. Um terceiro expressou apreço pela estruturação e agrupamento dos gráficos e tabelas, o que facilitou sua interpretação e análise.

No entanto, recebemos também uma crítica construtiva que reconheceu a qualidade da experiência, porém sugeriu melhorias.

Um participante, apesar de valorizar a consistência e facilidade de navegação, observou que a uniformidade pode tornar a experiência um tanto quanto monótona em determinados momentos. Ele apreciou a previsibilidade na disposição dos elementos, como menus e botões de busca, mas sugeriu que variações na apresentação visual poderiam tornar a interface mais dinâmica e engajante, sem afetar a praticidade.

Com essas avaliações em mente, especialmente a do último participante, elaboramos um conjunto de recomendações destinadas a abordar os desafios apontados. Essas sugestões incluem preservar a uniformidade na navegação, introduzindo ao mesmo tempo variações visuais em certas áreas para realçar a experiência do usuário sem comprometer a facilidade de uso. As recomendações se apoiam nos feedbacks recebidos, ressaltando a necessidade de ajustar a interface para que se mantenha tanto consistente quanto estimulante para os usuários.

Por fim, a severidade dos problemas relacionados à navegação consistente é considerada **baixa**. Embora a sugestão de introduzir variações visuais para tornar a interface mais viva tenha sido mencionada, a funcionalidade básica de navegação e a experiência do usuário foram amplamente elogiadas, indicando que as melhorias sugeridas visam aprimorar uma experiência já positiva.

**3.2.2 - Rótulo no Nome Acessível - Operável [A]**

Focamos nossa análise na "Página de Relatório de Saúde", particularmente devido à sua apresentação de gráficos acompanhados de legendas visuais. Essas legendas, além de facilitarem o entendimento dos dados sem excessiva dependência de textos descritivos, dispõem de uma interatividade que, ao interagir com o cursor, expõe transcrições detalhadas dos títulos dos gráficos. Esse design cuidadoso é projetado para melhorar tanto a acessibilidade quanto a compreensão visual para a ampla gama de usuários, inclusive aqueles que recorrem a leitores de tela.

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/saude1.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/saude1.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/saude2.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/saude2.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/saude3.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/saude3.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/saude4.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/saude4.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/saude5.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/saude5.png)

Os feedbacks dos participantes foram unânimes em reconhecer a contribuição significativa dos rótulos acessíveis na melhoria da navegabilidade e inteligibilidade do dashboard. A precisão e o detalhamento desses elementos interativos enriqueceram consideravelmente a experiência de navegação, tornando-a tanto intuitiva quanto informativa. Entretanto, o processo revelou também oportunidades para aprimorar ainda mais a experiência do usuário. A partir das observações recebidas, delineamos um plano de ação destinado ao contínuo aperfeiçoamento da acessibilidade e usabilidade:

- Aumento na Frequência dos Rótulos: Propomos a inclusão mais abrangente de rótulos acessíveis nos gráficos, assegurando que os usuários tenham uma compreensão imediata dos dados apresentados, mesmo na ausência de interação direta.
- Dinamismo Visual Ampliado: Sugerimos a implementação de variações visuais nos gráficos que, em sinergia com os rótulos acessíveis, empreguem cores distintas ou animações sutis ao passar do mouse. Este enriquecimento visual visa tornar a análise de dados não apenas mais acessível, mas também visualmente estimulante e atraente.

Essas estratégias não apenas têm o objetivo de ampliar a clareza e acessibilidade do conteúdo, mas também de tornar a experiência do usuário mais imersiva e prazerosa. A personalização visual, cuidadosamente alinhada ao feedback dos usuários, é chave para alcançar esse fim. Esse esforço coletivo ressalta a importância de refinamentos contínuos nos termos empregados e na padronização dos rótulos acessíveis, essenciais para manter a usabilidade e acessibilidade da interface para todos os usuários, especialmente para aqueles dependentes de tecnologias assistivas.

Conclue-se, portanto, que os problemas identificados nesta categoria são de severidade **média**. Apesar dos rótulos acessíveis melhorarem significativamente a navegabilidade e compreensão, a necessidade de aumentar a frequência dos rótulos e introduzir dinamismo visual indica que há espaço para melhorias significativas para enriquecer ainda mais a experiência do usuário.

**3.2.3 - Pronúncia / Palavras incomuns - Compreensível legível [AAA]**

No desenvolvimento do nosso dashboard, encaramos o desafio de tratar com termos técnicos e palavras pouco usuais que exigem um entendimento contextual ou conhecimento prévio específico. Este desafio torna-se evidente especialmente na página "Visão Geral", onde uma profusão de gráficos, tabelas e índices podem introduzir conceitos não familiares aos usuários, como "Stiba" e "GPTW". Reconhecemos que, embora nosso público-alvo possa ter um conhecimento prévio substancial sobre os assuntos abordados, a compreensão de termos específicos ainda poderia representar uma barreira à usabilidade plena.

Durante a avaliação do uso do dashboard, alguns usuários relataram dificuldades em compreender determinados jargões e termos técnicos, mesmo com a assistência de membros da equipe de desenvolvimento. Ficou claro que a falta de familiaridade com esses termos poderia comprometer a experiência do usuário, destacando a necessidade de soluções que facilitassem a compreensão sem interromper o fluxo de trabalho. Dessa forma as seguintes soluções foram propostas pelos usuários:

Integração de Dicas de Ferramentas e Pop-ups Contextuais: Para superar essa barreira, sugerimos aprimorar a interface com a implementação de dicas de ferramentas e pop-ups contextuais. Essa solução permitiria que os usuários obtivessem definições e explicações breves ao interagir com termos complexos, diretamente no contexto de uso, evitando desvios desnecessários na navegação e mantendo o foco no conteúdo relevante. Funcionalidade de pronúncia: Adicionalmente, reconhecemos a importância de suportar a compreensão auditiva dos termos apresentados. A adoção de ícones de áudio ao lado de termos técnicos e jargões facilitaria o acesso dos usuários à pronúncia correta desses termos com um simples clique. Tal funcionalidade não somente auxiliaria na compreensão dos termos como também promoveria uma abordagem inclusiva, respeitando as diferentes necessidades de todos os usuários.

A análise do feedback dos usuários sobre a página "Visão Geral" sublinhou a crucial necessidade de tornar termos técnicos e jargões amplamente acessíveis e compreensíveis. As soluções que propomos visam não apenas endereçar os desafios identificados, mas também ampliar a acessibilidade geral do nosso dashboard. Com esses aprimoramentos, aspiramos a transformar nosso dashboard em uma ferramenta não só robusta para análise, mas também plenamente acessível e compreensível para uma gama diversificada de usuários. Este empenho reflete nosso compromisso inabalável com a inclusividade e a acessibilidade, assegurando que o dashboard sirva eficazmente a todos os seus potenciais usuários.

Em suma, A dificuldade em compreender termos técnicos e jargões representa um problema de severidade **média a alta**. Essa questão pode criar barreiras significativas para a usabilidade do dashboard, especialmente para usuários novos ou menos experientes no assunto abordado sobre engajamento e saúde mental dos colaboradores, embora as soluções propostas anteriormente possam mitigar eficazmente esse desafio.

**3.2.4 - Contraste e Apresentação Visual - Perceptível Discernível [AAA]**

Na avaliação dos padrões de contraste e design visual definidos pelo WCAG, particularmente no que se refere ao uso em dashboards como o "Relatório Stiba", percebe-se a crucialidade de manter um design visual intuitivo e acessível. A seleção apropriada de contrastes entre texto e plano de fundo não só simplifica a leitura para todos, inclusive para pessoas com deficiências visuais, mas também contribui para a compreensão eficaz das informações exibidas. A escolha de uma paleta de cores harmônicas, exemplificada pelo uso de cinza escuro sobre branco, foi destacada por sua capacidade de potencializar a legibilidade e promover uma navegação mais fluida pelo dashboard.

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba2.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba2.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba3.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba3.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba4.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba4.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba5.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba5.png)

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba6.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/stiba6.png)

**Feedback dos Usuários e Ações Sugeridas**:

Embora tenhamos recebido avaliações positivas, surgiram pedidos por opções que ofereçam aos usuários a liberdade de personalizar a experiência visual, incluindo a modificação do tamanho da letra e do esquema de cores. Essa demanda sinaliza a necessidade de evoluir o dashboard para não apenas ser acessível, mas também personalizável conforme as preferências de cada um. Como resposta, sugerimos a inclusão de Funcionalidades de Ajuste Personalizado que permitirão alterações no contraste, no tamanho do texto e no esquema de cores diretamente no dashboard, por meio de ferramentas de fácil uso como controles deslizantes. Tal iniciativa busca ampliar a acessibilidade e a personalização, aprimorando a usabilidade para o usuário.

Por fim, propõe-se a realização de testes de usabilidade específicos para essas novas opções de ajuste personalizado, com o objetivo de recolher opiniões e efetuar melhorias conforme necessário. Isso garantirá que as inovações atendam de maneira eficaz às expectativas dos usuários, elevando a qualidade da experiência proporcionada.

Em resumo, os problemas relacionados ao contraste e à apresentação visual são de severidade **baixa a média**. As sugestões para permitir a personalização do tamanho da letra e do esquema de cores visam melhorar uma experiência de usuário já positiva, sugerindo que as questões de contraste não impedem significativamente a funcionalidade ou a compreensão do dashboard, mas a personalização poderia melhorar a acessibilidade e satisfação do usuário.

**Recomendações**

A realização deste abrangente processo de testes de usabilidade e acessibilidade nos dashboards desenvolvidos para a Volkswagen ofereceu insights valiosos sobre a interação dos usuários com a tecnologia. Através de uma metodologia estruturada, envolvendo participantes com variados perfis, conseguimos explorar em profundidade as nuances da experiência do usuário, desde a percepção visual à compreensão das interfaces. Os resultados evidenciaram pontos fortes, como a navegação consistente e intuitiva que facilita o acesso e a compreensão dos dashboards, e identificaram oportunidades significativas de melhoria. Em particular, destacaram-se sugestões para enriquecer a experiência do usuário por meio de variações visuais e funcionalidades personalizáveis, reforçando a necessidade de uma abordagem centrada no usuário para o design de dashboards.

As críticas construtivas recebidas e as recomendações propostas refletem um compromisso contínuo com a melhoria, sugerindo que a adaptação e a inovação devem ser elementos centrais no desenvolvimento de tecnologias acessíveis. A incorporação de ajustes personalizados e a ampliação da acessibilidade dos termos técnicos são passos cruciais na direção de um ambiente digital mais inclusivo.

Concluímos, portanto, que a jornada para aprimorar a usabilidade e a acessibilidade é um processo iterativo e colaborativo, que beneficia imensamente do envolvimento direto dos usuários. O diálogo contínuo com os usuários, a avaliação criteriosa de feedbacks e a implementação ágil de melhorias são fundamentais para garantir que os dashboards não apenas cumpram seu propósito analítico, mas também promovam uma interação gratificante e acessível para todos.

# 4. Descrição da Arquitetura

### **4.1. Diagramas**

Os diagramas C4, criados por Simon Brown, são uma técnica de notação gráfica projetada para representar a arquitetura de sistemas de software. C4 é uma abreviação para Contexto, Container, Componente e Código - os quatro níveis desse modelo.

Por tanto, justifica-se a utilização dos diagramas, dado que, o modelo C4 é uma ferramenta para visualizar o estado atual de um sistema e planejar o estado desejado.

### **4.1.1 Diagrama de Casos de Uso**

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

**Figura 1:** Diagrama caso de Uso

**Fonte**: Elaboração própria

### **4.1.2 Diagrama de conteiner**

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


**Figura 3:** Diagrama de Container

**Fonte:** Elaboração própria

### **4.1.3 Diagrama de classes**

Um diagrama de classes é um tipo de diagrama estrutural estático que descreve a estrutura de um sistema mostrando as classes do sistema, seus atributos, métodos e as relações entre os objetos.

As classes são representadas por retângulos que contêm o nome da classe na parte superior, seguido por seus atributos e operações. As linhas que conectam diferentes retângulos indicam as relações entre eles.

**Back-end**

O back-end consiste em classes como **`Usuario`**, **`Autenticador`** e **`BancoDeDados`**.

- A classe **`Usuario`** tem atributos como **`nomeUsuario`**, **`codigoConfirmacao`** e métodos como **`obterLista()`** e **`verificarCodigoConfirmacao(codigo: String)`**.
- A classe **`Autenticador`** herda de **`Usuario`** e tem um método **`autenticar(usuario: Usuario, codigo: String)`**.
- A classe **`BancoDeDados`** tem um método **`adicionarScanResultado(scanResultado, Usuario)`**.

**Front-end**

O front-end é representado pelas classes **`InterfaceUsuario`**, **`NavBar`**, **`Filtro`**, **`ResultadoDados`**, **`ResultadoGrafico`** e **`MonitoramentoDados`**.

- A classe **`InterfaceUsuario`** tem atributos como **`nomeUsuario`**, **`codigoConfirmacao`** e métodos como **`obterLista()`** e **`verificarCodigoConfirmacao(codigo: String)`**.
- A classe **`NavBar`** tem atributos como **`usuario`**, **`dashboard`** e métodos como **`acessar(dash: Dashboard)`**, **`processar(filtro: Filtro)`** e **`apresentarResultado()`**.
- A classe **`Filtro`** tem atributos como **`campo`**, **`tipo`**, **`operador`** e métodos como **`obterCampos()`**, **`obterTipos()`** e **`obterOperadores()`**.
- As classes **`ResultadoDados`**, **`ResultadoGrafico`** e **`MonitoramentoDados`** representam diferentes componentes da interface do usuário e cada uma delas tem um método **`gerarResultado()`** para gerar os resultados correspondentes.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G04/assets/99209712/67f0de6c-2323-44f8-ba5d-1cf3618f0008)

**Figura 4:** Diagrama de Classe

**Fonte:** Elaboração própria

### **4.1.4 API de Integração**

O Modelo-Visão-Controlador (MVC) é um padrão de arquitetura de software amplamente utilizado na concepção e desenvolvimento de aplicativos da web. Ele divide uma aplicação em três componentes principais: Model, View e Controller.

O Modelo é a camada responsável por representar os dados e toda a lógica de negócios da aplicação em questão. Ele é responsável por encapsular a lógica de manipulação dos dados, trazer os cálculos, validações e todas as interações com o banco de dados.

Já a View, é a camada responsável por apresentar a interface do usuário ao usuário final. Ela exibe todas as informações fornecidas pelo Modelo de uma forma que seja compreensível e interativa para o usuário. Dessa forma, facilitando e garantindo uma comunicação eficiente entre todas as partes para comunicar de forma clara todos os dados e funcionalidades.

O Controlador é a camada intermediária entre o Modelo e a Visão. Ele atua como um mediador entre as ações do usuário na interface do usuário e a lógica de negócios do Modelo. Quando o usuário interage com a aplicação, por exemplo, enviando um formulário, clicando em um botão, etc., o Controlador recebe essas interações, processa os dados necessários e decide como responder, geralmente atualizando o Modelo e/ou selecionando a Visão apropriada para exibir.

No contexto do nosso projeto, tomamos a decisão consciente de não utilizar views por uma variedade de razões. Em primeiro lugar, a essência da nossa aplicação foi moldada para oferecer endpoints que permitem interações programáticas com outros sistemas ou serviços, em detrimento de uma interface visual direta com o usuário. Considerando que os dados fundamentais do projeto são provenientes de um banco de dados, não consideramos ideal que os usuários tenham acesso direto a essas informações. Essa abordagem nos permitiu adotar uma estratégia centrada em API, simplificando a arquitetura e priorizando a entrega eficaz de dados. Ao estabelecer um sistema de API, viabilizamos uma comunicação fluida entre diferentes sistemas, serviços ou componentes, promovendo a troca de dados e funcionalidades e garantindo a interoperabilidade entre as partes envolvidas.

Além disso, ao evitar a criação de views, conseguimos estabelecer uma clara separação de responsabilidades na aplicação, mantendo a lógica de negócios e os serviços de backend totalmente independentes da camada de apresentação. Essa abordagem proporcionou não apenas uma maior flexibilidade e reutilização do código, mas também facilitou integrações futuras com uma variedade de clientes ou interfaces de usuário. Em resumo, a decisão de não adotar views foi alinhada com os objetivos fundamentais do projeto, assegurando uma arquitetura mais eficiente, modular e orientada para a interoperabilidade.

### **4.1.5 Estruturação das pastas**

Para a estruturação do nosso Backend estamos trabalhando com 4 principais repositórios:

- Kombi.Dashboard.Model
- Kombi.Dashboard.Repository
- Kombi.Dashboard.Services
- Kombi.Dashboard.Teste
- Kombi.Dashboard.WebApi

Essa estruturação foi criada para facilitar o armazenamento das informações, e garantir uma fluidez das informações e dados.

O repositório **Kombi.Dashboard.Model**, é responsável por conter as configurações relacionadas à gestão de pacotes NuGet e compilação de projetos C#. Ela é vista como uma parte crucial do backend da aplicação, responsável pela definição de modelos de dados e lógica de negócios. Ela contém dependências do projeto, como as versões dos pacotes NuGet a serem restauradas e as configurações de restauração. Ela define onde os pacotes estão armazenados, os caminhos para os arquivos

A pasta **Kombi.Dashboard.Repository** contém arquivos relacionados à manipulação de dados no contexto do projeto.

O primeiro arquivo define as classes *CidsModel*, e representa um modelo de dados para lidar com informações relacionadas a CIDs (Classificação Internacional de Doenças). A classe contém propriedades que representam os diferentes atributos como: unidade, diretoria, dias de afastamento, etc. Logo após isso, estamos trabalhando com um arquivo chamado *CidsRepository.cs*, que implementa a interface ICidsRepository e fornece as operações necessárias para interagir com os dados das CIDs.Contendo métodos para recuperar, inserir, atualizar e excluir informações das CIDs de um banco de dados já armazenado. Dessa forma, é vista como uma pasta responsável pela definição de modelos de dados e pela implementação de classes para manipulação de dados relacionados às CIDs.

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/repclasse.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/repclasse.png)

**Figura 5:** Cids Repository - classes

**Fonte:** Elaboração própria

A pasta **Kombi.Dashboard.Services** contém arquivos relacionados aos serviços da aplicação, responsáveis por interagir com os dados e fornecer funcionalidades para outras partes do sistema.

O arquivo *CidsService.cs* contém a implementação da classe CidsService, que é responsável por fornecer operações relacionadas às CIDs. Por exemplo, ele possui métodos para recuperar todas as CIDs, obter uma CID específica por ID e outros métodos relacionados ao gerenciamento de CIDs.

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/implementacao.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/implementacao.png)

**Figura 6:** Implementação da classe CidsService

**Fonte:** Elaboração própria

Já o arquivo *ICidsService.cs*, define a interface ICidsService, que estabelece os contratos para os serviços relacionados às CIDs. Ele é responsável por declarar os métodos que os serviços devem implementar, tais como a obtenção de CIDs por ID etc.

Ou seja, esses arquivos fornecem a base para o desenvolvimento e gerenciamento dos serviços relacionados às CIDs na aplicação. O CidsService é responsável por implementar a lógica de negócios relacionada às CIDs, enquanto a interface ICidsService estabelece os contratos que os serviços devem cumprir.

A pasta **Kombi.Dashboard.Teste** foi criada com o intuito de armazenar os arquivos relacionados aos testes unitários do projeto.

O arquivo *GlobalUsings.cs*, contém uma declaração global de using que importa o namespace NUnit.Framework. Dessa forma, permite que todos os arquivos no projeto tenham acesso aos tipos e membros definidos neste namespace sem a necessidade de importá-lo explicitamente em cada arquivo.

O arquivo *UnitTest1.cs*, contém a classe Tests, que é uma classe de teste unitário. A classe usa o framework de teste NUnit (NUnit.Framework) para escrever e executar os testes. O método Setup é executado antes de cada método de teste[Test]) e ele é usado para configurar o ambiente de teste. O método TestMethodToTest é um método de teste que verifica se o método MethodToTest da classe CidsService retorna o valor esperado quando chamado com um modelo de CID específico. Ou seja, um método que recebe um modelo de CID como entrada e retorna um número inteiro. Consequentemente, são responsáveis por configurar o ambiente de teste, definir casos de teste e verificar se o código funciona conforme o esperado.

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/Classe.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/Classe.png)

**Figura 7:** Classe de testes

**Fonte:** Elaboração própria

A pasta **Kombi.Dashboard.WebAPI**, contém os arquivos relacionados à API da página web do projeto.

O primeiro arquivo é o *Kombi.Dashboard.WebApi.csproj*, que contém dados que especificam como o projeto deve ser construído, suas dependências e outras configurações importantes. Aqui estão algumas das configurações importantes neste arquivo:

- TargetFramework: Define o framework de destino para o projeto (.NET 8.0).
- PackageReference: Lista as referências de pacotes NuGet necessárias para o projeto, como Dapper.SimpleCRUD, NUnit, Npgsql, entre outros.
- ProjectReference: Lista as referências de projeto para os projetos de Repository e Services, que este projeto depende.
- UserSecretsId: Identificador para armazenamento seguro de segredos do usuário.
- DockerDefaultTargetOS: Define o sistema operacional padrão para o Docker (Linux).

Outro arquivo de extrema importância é o *Kombi.Dashboard.WebApi*.http. Ele é o arquivo responsável por testar. Ele fornece exemplos de solicitações HTTP que podem ser usadas para interagir e testar a API da web desenvolvida no projeto. Define o endereço base da API, e demonstra como fazer uma solicitação GET para um dos seus endpoints, especificando o formato de resposta desejado. Isso é útil para verificar se a API está funcionando conforme o esperado e para identificar problemas de comunicação entre o cliente e o servidor.

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/endereco.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/endereco.png)

**Figura 8:** Endereço base e solicitação GET

**Fonte:** Elaboração própria

O arquivo *Program.cs*, contém o código para configurar e iniciar a aplicação web. Utilizando o padrão de inicialização do ASP.NET Core, ele configura os serviços de solicitação HTTP.

Inicialmente, ele configura o provedor de configuração para carregar as configurações do arquivo appsettings.json, utilizando a classe ConfigurationBuilder para construir uma instância. Em seguida, são registrados os serviços necessários para a aplicação. Isso inclui serviços como controladores, serviços de repositório e serviços de serviço. O método AddScoped é usado para registrar esses serviços no contêiner de injeção de dependência. O Swagger é então configurado para fornecer documentação da API. Visto como uma ferramenta de código aberto, que ajuda os desenvolvedores a projetar, documentar e consumir APIs REST de maneira fácil e eficiente. Ele fornece uma interface interativa baseada na web para explorar a API, utilizando o método AddSwaggerGen para configurar o SwaggerGen.

![https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/Swagger.png](https://github.com/Inteli-College/2024-T0004-SI09-G04/raw/main/assets/Swagger.png)

**Figura 9:** Swagger

**Fonte:** Elaboração própria

Por fim, o arquivo *Startup.cs* contém a classe Startup, que é responsável por configurar os serviços e o pipeline de solicitação HTTP da aplicação. Ele é responsável por configurar os serviços da aplicação, incluindo o pipeline de solicitação HTTP, para tratamento de exceções, autorização e endpoints de controle.

Em suma, a documentação apresentada oferece uma visão abrangente do projeto Kombi.Dashboard. Essa documentação destaca a estrutura modular da aplicação e os componentes-chave que a compõem. Por meio dos arquivos identificados, é possível compreender como os dados são modelados, armazenados e manipulados de forma eficiente garantindo uma boa comunicação entre o usuário com o sistema. Essa documentação serve como um recurso valioso com insights detalhados sobre a arquitetura, funcionamento e testes da aplicação destacados.

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

Além da coleta, o tratamento e armazenamento dos dados analíticos são etapas críticas no processo. O componente de banco de dados, relacionado a essa fase, deve ser otimizado para consultas analíticas, garantindo eficiência e desempenho. Ainda falando sobre a estrutura de back-end, os dados passam por processos de tratamento para garantir sua integridade e prepará-los para análises posteriores.

Após o tratamento dos dados, entra em cena a análise estatística e a geração de insights. Embora essa etapa não esteja explicitamente representada no diagrama, é uma parte essencial do processo. As análises estatísticas são realizadas para extrair insights valiosos dos dados, contribuindo significativamente para as tomadas de decisão. Os insights gerados são cruciais para fornecer uma compreensão mais profunda dos dados coletados.

A apresentação dos resultados no dashboard, desenvolvido com Angular e TypeScript, é a interface final para os usuários interagirem com os dados. O componente de front-end está diretamente ligado a essa etapa, permitindo uma visualização clara e compreensível dos insights e dados analíticos. O dashboard proporciona uma experiência amigável e interativa para os usuários explorarem os resultados das análises de maneira eficaz.

O registro de logs é uma peça fundamental para monitorar e solucionar problemas em sistemas de software. No contexto do dashboard, utiliza-se o PostgreSQL como banco de dados para armazenamento de logs. Compreende-se como  essencial o acompanhamento de  eventos, erros, atividades e outras informações relevantes geradas a partir das interações dos usuários com o sistema.

O Grafana é uma ferramenta poderosa para visualização de dados, e isso inclui a capacidade de exibir linhas de log de diversas fontes de dados, incluindo o PostgreSQL. Essa funcionalidade é extremamente útil para correlacionar eventos registrados no banco de dados com outras métricas e gráficos, proporcionando uma visão abrangente do estado do sistema.

Ao visualizar logs no Grafana, cada linha de log é apresentada de forma clara e organizada, com a opção de expandir detalhes relevantes. Isso inclui rótulos e campos detectados, facilitando a compreensão do contexto em que cada evento ocorreu. Além disso, o Grafana oferece recursos avançados, como a capacidade de criar links para recursos internos ou externos a partir de partes específicas de uma mensagem de log.

### Configurações e Opções de Exibição:

Para refinar a visualização dos logs, utiliza-se o Grafana a fim de facilitar o acompanhamento e 

O Grafana é capaz de determinar o nível de log com base em rótulos ou expressões contidas no conteúdo de cada mensagem. Isso permite classificar os eventos de acordo com sua importância e gravidade. Em casos onde não é possível determinar o nível de log, ele será visualizado como "desconhecido", garantindo transparência e clareza na apresentação dos dados.

Por fim, a segurança e autorização na API .NET Core são aspectos críticos a serem considerados. Embora não explicitamente representadas no diagrama, são fundamentais para proteger os dados e garantir o acesso adequado aos usuários. A implementação de autenticação e autorização robustas, utilizando Keycloak, é essencial para manter a integridade e segurança do sistema de análise de dados.

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/Diagrama%20de%20componentes.drawio.png) <br> <br> 
# Decisão da Arquitetura

A estrutura da arquitetura foi desenvolvida a fim de suportar os requisitos funcionais e não-funcionais levantados.

A presença de dois bancos de dados pode ser justificada por haver duas necessidades diferentes do projeto. O primeiro banco de dados, conectado diretamente à API, contém as informações necessárias para alimentar as visualizações do dashboard. O segundo banco de dados é utilizado para armazenar logs de atividades do sistema, garantindo uma separação clara entre os dados de produção e os registros de auditoria.

A API (Interface de Programação de Aplicativos) é uma escolha comum para expor funcionalidades e dados do sistema para outros aplicativos ou serviços. Ela permite que o Front-end e outros sistemas se comuniquem com o Back-end de maneira padronizada e segura. 

O Back-end é o coração da aplicação, onde a lógica de negócios e o processamento de dados acontecem. Ele está conectado ao Banco de Dados e gerencia as requisições vindas do Front-end através do Protocolo de Comunicação Web. A separação entre Back-end e Front-end permite que essas partes evoluam independentemente, facilitando a manutenção e a escalabilidade.

O Front-end é responsável pela interface do usuário. Ele se comunica com o Back-end através do Protocolo de Comunicação Web, exibindo dados e permitindo interações com os usuários. A separação entre Front-end e Back-end permite que diferentes equipes trabalhem em paralelo, focando em suas áreas específicas.

A separação dos Registros de Logs em um banco de dados específico e a conexão com o Dashboard de Logs (representado pelo ícone do Grafana) é uma escolha que permite o armazenamento e consulta dos logs de forma eficiente, facilitando a detecção de problemas e a análise de eventos.

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/Untitled%20(3).png) <br> <br> 
![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/Untitled%20(1).png) <br> <br> 


# Fluxo de dados

O fluxo de dados é o caminho pelo qual as informações se movem dentro de um sistema de software. Ele descreve como os dados são processados, transformados e transferidos entre diferentes componentes do sistema. 

O fluxo começa na origem dos dados, durante a interação do usuário interagindo com o Front-end.

O Front-end é a interface com a qual os usuários interagem. Ele recebe entradas do usuário (como cliques, digitação, seleções) e as transforma em solicitações para o Back-end.

A API atua como um intermediário entre o Front-end e o Back-end. Ela recebe as solicitações do Front-end, e suas responsabilidades incluem o encaminhamento a solicitação para o serviço apropriado no Back-end; Verificação se os dados da solicitação são válidos; Garantia que o usuário tenha permissão para executar a ação solicitada.

Já o Back-end é estruturado em diversos serviços que compõem parte do fluxo de dados.

O Service contém a lógica de negócios do sistema. Ele processa as solicitações recebidas da API. Em resumo, suas atividades consistem em validar os dados e executar operações específicas. Além disso, coordena a interação com o Repository.

O Repository é responsável pela persistência dos dados. Ele se comunica diretamente com o banco de dados, buscando, salvando e tratando os dados conforme as informações que devem ser apresentadas no dashboard.

O Model representa a estrutura de dados. Ele define como os dados são organizados e quais propriedades eles possuem.

Por fim, após o processamento dos dados no Back-end, espera-se resposta no Front-end. O Service processa os dados conforme necessário (aplica regras de negócios, formata os resultados), ele retorna uma resposta à API, que envia a resposta de volta ao Front-end.

# Segurança e conformidade

A segurança e a conformidade são pilares fundamentais para qualquer sistema, especialmente em um mundo cada vez mais digital e conectado. Garantir a proteção dos dados e a conformidade com as regulamentações relevantes é essencial para proteger a sua organização, seus clientes e sua reputação.

A fim de abranger o tópico de autenticação da plataforma, o Auth0 é uma plataforma de gerenciamento de identidade e acesso (IAM) que fornece autenticação e autorização para o sistema. Ele permite que os usuários se autentiquem usando uma variedade de métodos, como login com nome de usuário e senha, autenticação social (por exemplo, Google, Facebook) ou autenticação baseada em dispositivo.

Justifica-se a utilização do Auth0 pois o mesmo oferece recursos de segurança avançados, como autenticação multifator (MFA), detecção de anomalias e prevenção de ataques de força bruta. Além do mais, do ponto de vista técnico, a ferramenta é fácil de configurar e usar, tanto para desenvolvedores quanto para os usuários finais, sendo altamente escalável, podendo suportar um grande número de usuários e aplicativos.

![Untitled 9](https://github.com/Inteli-College/2024-T0004-SI09-G04/blob/main/assets/Untitled.png) <br> <br> 

Fonte: Auth0 (2024)

Conseguinte, o Github Actions é um serviço de integração e entrega contínua (CI/CD) que permite automatizar o processo de construção, teste e implantação do código. O CI/CD automatiza o processo de desenvolvimento e implantação, o que reduz o tempo e o esforço necessários para lançar novas versões do aplicativo.

Já o Render é uma plataforma de hospedagem em nuvem que permite implantar aplicativos web e APIs. Dessa maneira, tanto o Front-end quanto o Back-end que estruturam  o dashboard do projeto são hospedados no Render.

Ressalta-se aspectos de conformidade relacionados ao atendimento dos requisitos levantados por regulamentações relevantes como a LGPD (Lei Geral de Proteção de Dados) e ISO/IEC 27001. Tais requisitos garantem a confidencialidade e privacidade dos dados dos usuários.

## **Escalabilidade e Desempenho**

Em um mundo digital em constante evolução, a **escalabilidade** e o **desempenho** assumem um papel fundamental para o sucesso de qualquer sistema de software. A capacidade de um sistema crescer e se adaptar às demandas crescentes, sem comprometer a eficiência e a velocidade de resposta, é crucial para garantir a competitividade e a longevidade de qualquer organização.

**Assim, escalabilidade** se refere à capacidade de um sistema lidar com um aumento no volume de trabalho ou de usuários sem sofrer degradação no desempenho. Isso envolve a capacidade de adicionar recursos de hardware ou software de forma eficiente para atender às demandas crescentes.

**Consoante, desempenho** se refere à velocidade e à eficiência com que um sistema executa suas tarefas. Um sistema de alto desempenho responde rapidamente às solicitações dos usuários e utiliza os recursos de hardware de forma eficiente.

A **Programação Orientada a Objetos (POO)**, com seus princípios de modularidade, reutilização de código e flexibilidade, emerge como uma ferramenta poderosa para alcançar a escalabilidade e o desempenho desejados. Através da implementação de boas práticas de design e arquitetura, como o uso de interfaces, herança e polimorfismo, podemos criar sistemas robustos e adaptáveis, prontos para enfrentar os desafios do futuro.

## **Monitoramento e Manutenção**

O monitoramento e a manutenção de software abrangem um conjunto de atividades interligadas que visam garantir o bom funcionamento e a saúde de um sistema ao longo de seu ciclo de vida.  A coleta e análise de logs, a utilização de ferramentas como o Grafana e SonarQube, e a implementação de princípios como SOLID e DDD contribuem para a identificação e correção de problemas, otimização do desempenho e aprimoramento contínuo do sistema.

Investir em um plano robusto de monitoramento e manutenção oferece diversos benefícios, como reduzindo o risco de falhas e indisponibilidades do sistema, garantindo a sua operação contínua e minimizando o impacto negativo nas operações da organização; Identificando e corrigindo gargalos de desempenho, otimizando o uso de recursos e garantindo uma experiência fluida para os usuários; Evita gastos com correções emergenciais, falhas e indisponibilidades, otimizando o uso de recursos e maximizando o retorno do investimento em software.

Nesse contexto, os princípios **SOLID** e a abordagem **DDD** surgem como ferramentas valiosas para auxiliar no desenvolvimento e na manutenção de software de alta qualidade.

Os princípios SOLID representam um conjunto de cinco boas práticas de design de software que visam promover a criação de código modular, reutilizável e fácil de manter. São eles:

- **S** - Single Responsibility Principle (Princípio da Responsabilidade Única): Cada classe deve ter apenas uma única responsabilidade.
- **O** - Open-Closed Principle (Princípio Aberto-Fechado): Classes e módulos devem ser abertos para extensão, mas fechados para modificação.
- **L** - Liskov Substitution Principle (Princípio da Substituição de Liskov): Classes derivadas devem ser substituíveis por suas classes base sem quebrar o comportamento do sistema.
- **I** - Interface Segregation Principle (Princípio da Segregação de Interfaces): As interfaces devem ser pequenas e específicas, definindo apenas os comportamentos necessários.
- **D** - Dependency Inversion Principle (Princípio da Inversão de Dependência): As dependências entre classes devem ser definidas através de interfaces, e não através de implementações concretas.

Ao seguir os princípios SOLID, os desenvolvedores podem criar código mais modular, coeso e desacoplado, facilitando a compreensão, a manutenção e a extensibilidade do sistema.

O Domain-Driven Design (DDD) é uma abordagem de design de software que divide o sistema em subdomínios, cada um com seu próprio modelo de negócio, regras e responsabilidades. Essa divisão facilita a compreensão do sistema, pois cada subdomínio representa uma área específica de conhecimento.

O DDD também promove a reutilização de código e a extensibilidade do sistema, pois os subdomínios podem ser facilmente desacoplados e modificados sem afetar o restante do sistema.


## 5. Perspectivas à longo prazo

Para impulsionar ainda mais sua efetividade e atender às necessidades dos diferentes públicos de interesse, propomos um plano abrangente de aprimoramento. 

Inicialmente, é fundamental implementar um sistema de permissões que defina quais informações do dashboard podem ser acessadas por cada nível de liderança, garantindo a segurança e a confidencialidade dos dados. Para que essa nova funcionalidade seja implantada é necessário: criar perfis de usuário com diferentes níveis de permissão e definir quais dashboards e relatórios podem ser acessados por cada perfil; Por fim, estabelecer o sistema de login seguro para controlar o acesso ao dashboard.

Em seguida, entende-se como fundamental facilitar a utilização das informações apresentadas no dashboard para auxiliar na tomada de decisão. Por isso, identifica-se como excelente oportunidade a possibilidade de extração de relatórios em PDF com os dados do dashboard, facilitando o compartilhamento e a análise das informações.

Buscando compreender e facilitar cada vez mais o dia a dia dos usuários indica-se a adptação das telas que compõem o dashboard, atendendo, assim,  às diferentes necessidades dos usuários. Entende-se como fundamental as funcionalidades que são utilizadas em contextos de pessoas com deficiência, assim como descrita no relatório de acessibilidade. Além do mais, ressalta-se  a importância dos usuários estarem inseridos na conjuntura das informações que estão sendo apresentadas, para que tais façam sentido e agreguem na tomada de decisão.

## 6. Análise Financeira

# **Introdução**

Neste documento, será apresentada a análise financeira do projeto para o período de um ano, com foco exclusivo nas projeções de custos. Dado que o projeto é de natureza interna e não visa à geração de receita, a análise abordará os diversos componentes típicos dos custos associados ao desenvolvimento de software, como recursos humanos e infraestrutura.

# **Análise**

Os principais custos identificados para o projeto são atribuídos a recursos humanos e infraestrutura. Abaixo, apresentamos as justificativas e relevâncias desses custos para o projeto, além das projeções anuais.

## **RECURSOS HUMANOS (RH)**

Os custos de recursos humanos (Tabela 1) se referem a equipe de desenvolvimento que engloba as seguintes funções:

* 1 Desenvolvedor Back-End;
* 1 Desenvolvedor Front-End;
* 1 Analista de Dados;
* 1 Gestor de Projeto;

### **Justificativa**

A maior parte do orçamento é destinada aos recursos humanos, que incluem desenvolvedores, analista de dados e gestor de projeto. Esta é uma área crítica de investimento devido às seguintes razões:

**Especialização Técnica**: O desenvolvimento de software, especialmente em tecnologias específicas como .NET Core para a API e Angular/TypeScript para o dashboard, requer profissionais com habilidades especializadas.


**Diversidade de Funções**: A equipe não consiste apenas em desenvolvedores, mas também inclui um analista de dados para interpretar e modelar os dados, bem como um gestor de projeto para coordenar as atividades, gerenciar prazos e comunicar-se com os stakeholders.

### **Projeção**

O Glassdoor é uma plataforma que oferece visões abrangentes sobre empregos, incluindo detalhes sobre vagas disponíveis, faixas salariais, avaliações de entrevistas.

Para obter as estimativas salariais mencionadas, foi feita uma consulta à média salarial de cada posição conforme disponibilizado pelo Glassdoor, levando em conta a diversidade de dados fornecidos por profissionais do setor.

| Estimativa dos Custos de Recursos Humanos |  |  |
| --- | --- | --- |
| Cargo | Mensal | Anual |
| 1 Desenvolvedor Back-End | R$ 8.581,00 | R$ 102.972,00 |
| 1 Desenvolvedor Front-End | R$ 6.900,00 | R$ 82.800,00 |
| 1 Analista de Dados | R$ 5.175,00 | R$ 62.100,00 |
| 1 Gestor de Projeto | R$ 9.699,00 | R$ 116.638,00 |
| Total | R$ 30.355,00 | R$ 364.260,00 |

**Tabela 1**. Estimativa dos Custos de Recursos Humanos.

## **INFRAESTRUTURA**

Os custos de infraestrutura (Tabela 2) se referem aos seguintes serviços

Sistema de armazenamento;

Hospedagem do Dashboard;

**Justificativa**

A infraestrutura é essencial para a coleta, armazenamento e processamento de dados, bem como para a hospedagem e operação do dashboard. Investimentos nesta área são cruciais devido:

**Capacidade e Escalabilidade**: A infraestrutura deve ser capaz de suportar o volume de dados gerado e ter a flexibilidade para escalar conforme o crescimento das necessidades do projeto.

**Disponibilidade e Confiabilidade**: Uma infraestrutura robusta garante que o dashboard esteja sempre disponível para os usuários e que os dados estejam seguros.

**Projeção**

Para a infraestrutura do projeto, selecionamos o Render como plataforma de nuvem, que simplifica a implantação e gerenciamento de aplicações, juntamente com o PostgreSQL no plano "Starter" a $7 (R$ 35,06) mensais para armazenamento de dados, devido à sua robustez. A hospedagem será assegurada por duas máquinas no Render, uma a $25 (R$ 125,23) e outra a $7 (R$ 35,06) por mês, adequadas para diferentes necessidades operacionais. Além disso, as 500 horas disponíveis de pipeline do GitHub Actions são cruciais para automatizar o ciclo de desenvolvimento, permitindo a integração e entrega contínuas sem custos extras, o que otimiza o processo de desenvolvimento e mantém a qualidade do código, balanceando eficácia e custo de maneira eficiente.

| Estimativa dos Custos de Infraestrutura |  |  |  |
| --- | --- | --- | --- |
| Serviço | Mensal | Anual |  |
| Armazenamento | R$ 35,06 | 420,72 |  |
| Hospedagem | R$ 160,27 | 1.923,24 |  |
| Total | R$ 195,33 | R$ 2.343,96 |  |
|  |  |  |  |

**Tabela 2**. Estimativa dos Custos de Infraestrutura.

# **Conclusão**

Estes custos são considerados os principais devido à sua magnitude e ao fato de serem indispensáveis para o sucesso do projeto. Recursos humanos representam o maior custo direto, dada a necessidade de uma equipe multidisciplinar de especialistas, totalizando um custo anual de R$ 364.260,00. A infraestrutura é essencial para o armazenamento e processamento de dados, bem como para a operação do dashboard, totalizando um custo anual de R$ 2.343,96.

## 7. Plano de comunicação

**1. Objetivo:**

O objetivo central do plano de comunicação para o projeto do Dashboard de Saúde Mental vs Indicadores de Engajamento na Volkswagen do Brasil é assegurar uma comunicação efetiva e alinhada entre todos os stakeholders. Este plano enfatiza a necessidade de clarificar o papel fundamental do dashboard na estratégia de bem-estar da empresa, demonstrando como a ferramenta será utilizada para aprimorar o ambiente de trabalho e o bem-estar dos colaboradores.

Além disso, busca garantir que cada parte envolvida, desde a equipe de desenvolvimento até os gestores e funcionários que serão usuários finais, tenha uma compreensão precisa e unificada das metas e do escopo do projeto. Este entendimento compartilhado é crucial para o sucesso da iniciativa, incentivando uma colaboração mais eficaz e o engajamento de todos os participantes em direção aos objetivos comuns estabelecidos para o projeto.

**1.1. Relevância do projeto**

A relevância do projeto para a Volkswagen do Brasil pode ser consolidada nos seguintes pontos-chave:

- O projeto direciona esforços para a análise da saúde mental e do engajamento, fundamentais para a satisfação e produtividade dos colaboradores, alinhando-se com as políticas de bem-estar da empresa.
- Facilita o acesso a dados críticos, permitindo identificar padrões e tendências, e oferece insights acionáveis para otimizar as operações e melhorar a tomada de decisões.
- Reforça a liderança da Volkswagen no uso de tecnologias avançadas para promover um ambiente de trabalho saudável, além de contribuir para os objetivos estratégicos da empresa em mobilidade sustentável e digitalização.
- Apoia uma cultura de transparência e inclusão, onde a saúde mental e o engajamento são valorizados, criando um ambiente de trabalho acolhedor e propício ao desenvolvimento contínuo.

**1.2. Objetivos do projeto**

- Criar uma ferramenta que consolide e apresente de forma intuitiva dados sobre saúde mental e engajamento dos colaboradores, facilitando a análise e interpretação das informações.
- Consolidar informações dispersas em várias fontes e sistemas em um único dashboard, superando os desafios atuais de ineficiências operacionais e dificuldades na tomada de decisões.
- Utilizar análises estatísticas para extrair insights relevantes, identificar padrões e tendências nos dados corporativos, e orientar decisões estratégicas.
- Incluir funcionalidades que permitam a avaliação contínua do desempenho da empresa e o monitoramento periódico de indicadores-chave de desempenho (KPIs), auxiliando na identificação de áreas que requerem atenção.

**1.3. Benefícios esperados**

- A partir do acesso facilitado a análises detalhadas e insights relevantes permitirá que os gestores tomem decisões informadas e estratégicas, impulsionando a eficiência operacional cotidiana de análises de dados de saúde e clima empresarial.
- Com dados precisos sobre os colaboradores, o projeto possibilita a identificação de áreas de melhoria nas políticas e práticas de RH, visando a retenção de talentos e o desenvolvimento de uma força de trabalho engajada.
- Ao adotar uma abordagem orientada por dados para questões de saúde mental e engajamento, a Volkswagen reforça seu compromisso com a inovação e sustenta sua posição de liderança no setor automobilístico.
- A implementação do dashboard apoia uma cultura de transparência, inclusão e cuidado com o bem-estar dos colaboradores, alinhando-se aos valores centrais da empresa.

**1.4. Entrega do projeto**

- Desenvolvimento de um dashboard visualmente atraente e de fácil utilização que apresenta análises sobre a saúde mental e o engajamento dos colaboradores, permitindo uma compreensão rápida e aprofundada dos dados, personalizável a partir de filtros.
- Inclusão de recursos que permitem análises estatísticas descritivas, identificação de tendências, monitoramento de indicadores-chave (KPIs), e geração de insights acionáveis para suporte à tomada de decisões.
- Documentação para facilitar a implantação, adoção e utilização eficaz do dashboard pelos gestores e pela equipe de RH, garantindo que todos possam maximizar o valor oferecido pela ferramenta.
- Desenvolvimento de uma API na plataforma .NET Core para alimentar o dashboard com dados atualizados e precisos, assegurando a escalabilidade e performance do sistema.

**2. Stakeholders:**

Os stakeholders do projeto na Volkswagen do Brasil englobam diversos grupos, cada um com um papel vital no desenvolvimento e na implementação bem-sucedida do projeto:

- **Equipe técnica**: Liderada pelo Líder Técnico Marco Túlio Soares de Carvalho, esta equipe é responsável pela análise técnica do dashboard, assegurando que a ferramenta atenda às necessidades específicas da empresa e dos usuários para a posterior implantação.
- **Líderes de Projeto e Executivos**: Incluindo o Líder do Projeto Rodrigo Filus e a Líder Executiva Karine Rachel Wohlke da Silva Purchio, esse grupo define a visão do projeto, alinha-o com os objetivos estratégicos da empresa e provê recursos e suporte de alto nível.
- **Gestores e Equipe de RH**: Esses stakeholders serão os principais usuários do dashboard, utilizando a ferramenta para monitorar a saúde mental e o engajamento dos colaboradores, bem como para informar decisões relacionadas à gestão de recursos humanos.
- **Colaboradores**: Embora não estejam diretamente envolvidos no desenvolvimento do projeto, os colaboradores da Volkswagen do Brasil são um grupo-chave de interesse, pois as informações derivadas do dashboard visam melhorar seu bem-estar e engajamento.
- **Ponto focal backup**: Representados pela Thais Sandoval Baptista de Oliveira e Dayane Rodrigues Silva, este grupo utiliza as informações do dashboard para avaliar e melhorar as condições de trabalho e as práticas de saúde e segurança na organização, além de fornecer feedback interativos durante o desenvolvimento do projeto nas sprints.
- **Professor Orientador Cesar Almiñana**: Como figura acadêmica orientadora, ele oferece supervisão, orientação e expertise teórica para garantir que o projeto esteja fundamentado em sólidos princípios de gestão de saúde e engajamento no ambiente de trabalho.

Esses stakeholders desempenham papéis críticos, desde a concepção e desenvolvimento do projeto até sua implementação e uso cotidiano, garantindo que o "Dashboard de Saúde Mental vs Indicadores de Engajamento" atenda aos objetivos desejados e traga melhorias tangíveis para a Volkswagen do Brasil.

**3. Mensagens Chave:**

- **Para a equipe Técnica**: Concentrar-se na análise técnica para garantir que o dashboard seja desenvolvido de acordo com as necessidades da empresa e dos usuários, visando uma implantação eficaz.
- **Para os líderes de projeto e executivos**: Definir a visão do projeto, alinhá-lo com os objetivos estratégicos da empresa e garantir o fornecimento de recursos e apoio necessários.
- **Para os usuários finais (Gestores e Equipe de RH)**: Utilizar o dashboard para acompanhar a saúde mental e o engajamento dos colaboradores, informando decisões estratégicas de gestão de recursos humanos.
- **Para os colaboradores**: Beneficiar-se das informações fornecidas pelo dashboard para melhorar o bem-estar e engajamento, embora não estejam envolvidos diretamente no desenvolvimento.
- **Para o ponto focal backup**: Empregar dados do dashboard para avaliar e aprimorar as condições de trabalho, práticas de saúde e segurança, além de contribuir com feedback interativo durante as fases de desenvolvimento.
- **Para o professor orientador Cesar Almiñana**: Oferecer supervisão e orientação acadêmica, assegurando que o projeto seja embasado em princípios sólidos de gestão da saúde e engajamento no ambiente de trabalho.

Essas mensagens resumem o foco e a contribuição esperada de cada grupo de stakeholders para o sucesso do projeto na Volkswagen do Brasil.

**4. Canais de Comunicação:**

- Adoção rigorosa das cerimônias do Scrum, incluindo Daily Standups para sincronização diária, Planning Meetings para definição de objetivos de Sprint, Sprint Reviews para demonstração dos incrementos alcançados e Retrospectives para reflexão e melhoria contínua do processo;
- Realização de Sprint Reviews abertas aos stakeholders, incluindo demonstrações interativas dos incrementos e compartilhamento de Status Reports detalhados, visando transparência total e engajamento das partes interessadas;
- Utilização de plataformas de gerenciamento de documentos, como Google Drive ou Notion, para centralizar, compartilhar e atualizar a documentação do projeto, assegurando fácil acesso e colaboração entre os membros da equipe;
- Implementação de ferramentas digitais de comunicação, como Slack para interações rápidas e focadas no trabalho, WhatsApp para comunicações urgentes ou informais e e-mail para comunicações oficiais e distribuição de documentos importantes e
- Estabelecimento de canais e grupos específicos no Slack e WhatsApp para diferentes fluxos de trabalho e discussões temáticas, facilitando a organização e a eficiência das comunicações.

**5. Plano de Implementação:**

**5.1. Sprint 1 (semanas 1 e 2):**

- Reuniões de kick-off com os líderes de projeto e executivos e professor orientador para alinhar as expectativas e leitura/entendimento do TAPI;
- Desenvolvimento dos artefatos de entendimento do usuário (UX): Criação de Persona e Wireframes Avançados de Dashboard;
- Desenvolvimento dos artefatos de entendimento do negócio: Canvas Proposta de Valor e Matriz de Risco e
- Desenvolvimento dos artefatos de programação: Diagrama de Casos de Uso, Diagrama de Classese Diagrama de Componentes.

**5.2. Sprint 2 (semanas 3 e 4):**

- Desenvolvimento dos artefatos de negócio: Análise PESTEL e TAM, SAM, SOM;
- Desenvolvimento dos artefatos de UX: Mockups Avançados para Dashboards e
- Desenvolvimento dos artefatos de programação: API de Integração e Dashboard Versão I.

**5.3. Sprint 3 (semanas 5 e 6):**

- Desenvolvimento dos artefatos de UX: Dashboard final e Análise Heurística detalhada;
- Desenvolvimento da versão 2 da API e
- Finalização do Dashboard com integração ao backend versão 2.

**5.4. Sprint 4 (semanas 7 e 8):**

- Deploy do dashboard e da API para produção;
- Relatório de Testes de funcionamento da API e do dashboard e
- Aplicação de análise de acessibilidade.

**5.5. Sprint 5 (semanas 9 e 10):**

- Realização da análise financeira do projeto;
- Desenvolvimento da documentação final completa com arquitetura e
- Apresentação Final.

**6. Medidas de Sucesso:**

- Avaliação da compreensão dos objetivos e funcionalidades do dashboard entre todos os stakeholders;
- Medição da capacidade de uso do dashboard com base na facilidade de interpretação dos dados apresentados;
- Adesão ao cronograma definido, com foco especial nas datas de entrega chave e marcos do projeto;
- Alinhamento contínuo das entregas do projeto com as expectativas e necessidades da Volkswagen do Brasil e
- Implementação de ações corretivas em resposta a feedbacks negativos para aprimorar a eficácia e usabilidade do dashboard.

**7. Feedback e Ajustes:**

- Organização de sessões de feedback após cada apresentação ao cliente para capturar impressões e sugestões;
- Implementação de um sistema para registrar, classificar e priorizar os feedbacks recebidos, visando uma abordagem sistemática para os incrementos;
- Estabelecimento de canais dedicados em plataformas de comunicação, como Slack, para facilitar a troca contínua de ideias e feedbacks entre a equipe de projeto e o professor orientador;
- Incentivo à comunicação aberta e transparente, promovendo um ambiente colaborativo onde todos se sintam confortáveis para compartilhar suas ideias e preocupações e
- Realização de revisões semanais do plano de comunicação e da estratégia do projeto para incorporar os feedbacks e fazer os ajustes necessários.

# **Referências**
**Glassdoor.** Salários do cargo de Analista De Dados Júnior – Brasil. 2024. [Online]. Disponível em: https://www.glassdoor.com.br/analista-de-dados-junior. Acesso em: 09 abr. 2024.

**AUTH0.** Como a Auth0 utiliza os padrões da indústria de identidade. 2023. [Online]. Disponível em: https://auth0.com/pt/learn/how-auth0-uses-identity-industry-standards. Acesso em: 10 abr. 2024.

**Glassdoor.** Salários do cargo de Desenvolvedor Back-End Pleno – Brasil. 2024. [Online]. Disponível em: https://www.glassdoor.com.br/desenvolvedor-back-end-pleno. Acesso em: 09 abr. 2024.

**Glassdoor.** Salários do cargo de Desenvolvedor Front-end Pleno – Brasil. 2024. [Online]. Disponível em: [https://www.glassdoor.com.br/Salários/desenvolvedor-front-](https://www.glassdoor.com.br/Sal%C3%A1rios/desenvolvedor-front-) end-pleno-sal%C3%A1rio. Acesso em: 09 abr. 2024.

**Glassdoor.** Salários do cargo de Gestor De Projetos – Brasil. 2024. [Online]. Disponível em: https://www.glassdoor.com.br/gestor-de-projetos. Acesso em: 09 abr. 2024.

**Volkswagen do Brasil.** Informações Legais. [Online]. Disponível em: https://www.vw.com.br/pt/volkswagen/informacoes-legais.html. Acesso em: 10 abr. 2024.

**Volkswagen do Brasil.** Política de Privacidade. [Online]. Disponível em: https://www.vw.com.br/pt/volkswagen/informacoes-legais/politica-de-privacidade.html. Acesso em: 10 abr. 2024.

**Volkswagen do Brasil.** Política Ambiental e de Energia. 2023. [Online]. Disponível em: https://www.vw.com.br/pt/volkswagen/Responsabilidade-Corporativa/Sistema-de-Gestao-de-Compliance-Ambiental-e-de-Energia-SGCAE/politica-ambiental-e-de-energia.html. Acesso em: 10 abr. 2024.

**Render.** Preços Previsíveis que Escalam com Você. 2024. [Online]. Disponível em: https://render.com/pricing. Acesso em: 09 abr. 2024.

**Poder360.** Volkswagen pagará mais de R$ 10 milhões em processos trabalhistas. 2023. [Online]. Disponível
