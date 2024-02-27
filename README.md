# Continuous Integration (JENKINS)

<br> 

A integração contínua (CI) é uma prática de desenvolvimento de software que visa tornar a integração de código mais eficiente, através de builds e testes automatizados. Os desenvolvedores integram seu código com frequência, geralmente várias vezes ao dia, para garantir que o código seja compatível e funcione corretamente.

A CI é uma prática fundamental do DevOps, que é um conjunto de práticas que visam melhorar a colaboração entre desenvolvedores e operações de TI. A CI ajuda a reduzir o risco de erros e atrasos no desenvolvimento de software, e também pode ajudar a melhorar a qualidade do software.

A CI funciona da seguinte forma:

Os desenvolvedores fazem alterações no código e as enviam para um repositório central.
Um servidor de CI compila o código e executa testes automatizados.
Se os testes forem bem-sucedidos, o código é integrado à base de código principal.
A CI pode ser implementada usando uma variedade de ferramentas e serviços. Algumas ferramentas populares de CI incluem Jenkins, CircleCI e Travis CI.

Os benefícios da CI incluem:

Redução de erros: A CI ajuda a identificar e corrigir erros mais cedo no processo de desenvolvimento, o que pode reduzir o custo de corrigi-los.
Melhoria da qualidade: A CI ajuda a garantir que o código seja compatível e funcione corretamente, o que pode melhorar a qualidade geral do software.
Aumento da produtividade: A CI pode ajudar os desenvolvedores a trabalhar de forma mais eficiente, pois eles não precisam esperar até que o código seja integrado à base de código principal para testá-lo.
A CI é uma prática importante que pode ajudar a melhorar a qualidade e a produtividade do desenvolvimento de software.

<hr>

As ferramentas de automação e construção variam muito pois são especificas da linguagem e plataforma mas também variam na área de uso como desenvolvimento web, mobile ou data science. Além disso, existem ferramentas especificas para uma etapa de build como teste ou deploy. Enfim, a lista abaixo representa apenas alguns exemplos.
Ferramentas de automação e construção, separado por linguagem/plataforma:
•	Java: Ant, Maven, Gradle
•	Front-end: Gulp, Grunt, Webpack
•	.NET: MSBuild
•	Ruby: Rake
•	Kotlin: Gradle
•	Clojure: Leiningen
•	C/C++: CMake/Make
•	PHP: Composer
E alguns frameworks famosos da área de teste:
•	Selenium (automação do navegador)
•	Cucumber (testes de aceitação)
•	Postman e SoapUI (testes de API)
•	JMeter (stress tests)
•	JUnit, xUnit, PHPUnit (automação de testes)
•	entre muitos outros frameworks e bibliotecas
Para o configuration management e provisioning podemos mencionar:
•	Ansible
•	Puppet
•	Chef
•	Salt
•	Terraform (cloud)
O configuration management / provisioning é sobre a instalação e manutenção da maquina.


Abaixo alguns servidores de integração disponíveis no mercado. Alguns servidores são opensource, outros não, alguns são pagos ou podem ser alocados na nuvem e outros só existem para nuvem ou instalação local.
Em geral, não existe uma bala de prata e a melhor ferramenta é aquela que te serve bem:

•	Jenkins (https://jenkins.io/)

•	GoCD (https://www.gocd.org/)

•	Bamboo (https://www.atlassian.com/br/software/bamboo)

•	Travis CI (https://travis-ci.org/)

•	Team City (https://www.jetbrains.com/teamcity/)

•	Circle CI (https://circleci.com/)

•	Gitlab (https://about.gitlab.com/product/continuous-integration/)

•	AWS Code Pipeline https://aws.amazon.com/codepipeline/

•	Azure (https://azure.microsoft.com/pt-br/services/devops/server/

![CI1](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/980c906a-db86-452f-bace-6d66db8291b6)

![CI2](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/4c1676c0-501e-4497-9d6b-1503e98f03a4)

![CI3](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/7908c1c3-c0e4-4250-a018-1024d7450793)

![CI4](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/b81fb8b4-3181-4af3-bbd4-c4cdb99b8ce0)

![CI5](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/6ce7c3cf-d542-434a-b264-4fb05c7de1d3)

![CI6](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/2252cd20-a9b5-4be5-9535-d6d64364b517)

![CI7](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/e767a29e-9c05-4ea5-9696-ed33fbc3e952)

![CI8](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/217adb13-e8ba-4fb5-b75a-9dd5a6882a08)

![CI9](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/4dde8722-88ac-4b9d-9ff2-c98ea1f83c2a)

## Duas regras: Todo time commita pelo menos uma vez no dia, e o 'main' deve sempre estar em estado "deployável".

# Continuous Delivery 

O que a CD faz?

Automação: A CD automatiza tarefas repetitivas, como integração de código, testes e implantação, liberando tempo e energia para sua equipe se concentrar em inovações.
Velocidade: Com a CD, novas funcionalidades e correções de bugs chegam aos seus usuários com muito mais rapidez, impulsionando a agilidade do seu negócio.
Confiabilidade: A automação garante que cada mudança seja testada e validada antes da implantação, reduzindo drasticamente o risco de erros e falhas.
Feedback: A CD permite que você obtenha feedback do usuário mais rapidamente, ajudando a tomar decisões informadas sobre o desenvolvimento do seu software.
Como funciona a CD?

Integração Contínua: O código é integrado e validado frequentemente, garantindo que as alterações sejam compatíveis e funcionem como esperado.
Testes Automatizados: Bateria de testes automatizados garante que o código esteja livre de erros e atenda aos requisitos de qualidade.
Build Automatizado: O código é automaticamente convertido em um artefato pronto para implantação.
Implantação Automatizada: O artefato é implantado em diferentes ambientes, como teste, homologação e produção, com total controle e confiabilidade.
Benefícios da CD:

Agilidade: Lançamentos frequentes e com menor tempo de espera.
Qualidade: Redução significativa de erros e falhas na produção.
Confiabilidade: Maior confiabilidade e estabilidade do software.
Produtividade: Aumento da produtividade da equipe de desenvolvimento.
Satisfação do cliente: Maior satisfação do cliente com entregas frequentes e de alta qualidade.
Começando com a CD:

Planejamento: Defina seus objetivos, processos e ferramentas de CD.
Automação: Implemente ferramentas para automatizar tarefas de integração, testes, build e implantação.
Cultura: Crie uma cultura de colaboração e comunicação entre as equipes de desenvolvimento e operações.
Monitoramento: Monitore o desempenho e a qualidade do software em produção.
Melhoria contínua: Aprimore continuamente seu processo de CD com base em feedback e aprendizados.
Recursos para aprofundar seu conhecimento:

Livro: Entrega Contínua - Jez Humble e David Farley: URL Livro Entrega Contínua
Artigo: O que é entrega contínua? - Atlassian: URL Artigo O que é entrega contínua
Ferramentas de CD: Jenkins, Azure DevOps, CircleCI: URL Ferramentas de CD
A Entrega Contínua é uma ferramenta poderosa que pode revolucionar a forma como você desenvolve e entrega software. Ao automatizar o processo de desenvolvimento, você pode aumentar a velocidade, a qualidade e a confiabilidade do seu software, além de impulsionar a agilidade e a produtividade da sua equipe.

Dica bônus: A CD é apenas uma parte da filosofia DevOps. Para um sucesso ainda maior, combine a CD com práticas de desenvolvimento ágil, infraestrutura como código e monitoramento constante.

![c1](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/36944bd6-0f1b-4a20-9222-772a320a5860)

![c2](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/d80d2277-efe2-4558-b460-0f1ab65fcfa5)

![c3](https://github.com/Rafael-Bessa/CI-CD/assets/104053775/ff3e679d-007f-4d50-8a15-239fc9eea3c0)


