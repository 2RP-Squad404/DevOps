# Jenkins
O Jenkins é uma poderosa ferramenta de automação open-source projetada para facilitar práticas de Integração Contínua (CI) e Entrega Contínua (CD) no desenvolvimento de software. Ele é amplamente utilizado por equipes de desenvolvimento que buscam automatizar tarefas repetitivas e garantir eficiência e qualidade ao longo do ciclo de vida de suas aplicações.<br>
<br>
Paralelamente ao estudo do Jenkins, também estou explorando o Google Cloud Build, uma ferramenta nativa da Google Cloud Platform para CI/CD. Ela se destaca pela integração total com o GCP e pela simplicidade em configurar pipelines diretamente na nuvem. Comparar as duas ferramentas tem sido uma experiência enriquecedora, pois me permite entender abordagens diferentes para resolver desafios de automação e entrega de software.

### Cloud Build X Jenkins

![Jenkins X Cloud Build](/imagens/CloudBuildXJenkins.png)

Durante os cursos e estudos que venho realizando, tive a oportunidade de aprender como o Jenkins funciona e como ele pode ser uma ferramenta essencial para automação de processos no ciclo de vida de desenvolvimento de software. Esse aprendizado tem sido extremamente enriquecedor, permitindo que eu não apenas entenda os conceitos teóricos, mas também coloque em prática os conhecimentos adquiridos em projetos reais.

### CI/CD
![Jenkins](/imagens/JenkinsPrincipal.png)

Explorando o Jenkins, consegui alcançar alguns resultados interessantes e práticos. Um dos maiores destaques foi a criação de duas pipelines completas, cada uma desempenhando um papel crucial no processo de desenvolvimento:

![Pipelines](/imagens/JenkinsTarefasLeilao.png)

Build e Testes Unitários: Configurei pipelines que automatiza o build do código e realizam testes unitários, garantindo que o código esteja funcional e livre de problemas antes de seguir para a próxima etapa.

![Testes](/imagens/TestesLeilao.png)

CI/CD com Deploy Automatizado: Desenvolvi uma pipeline de Integração e Entrega Contínua (CI/CD) que realiza o deploy automático de uma aplicação. Essa automação reduz o tempo de entrega e diminui os erros manuais durante a implantação.

![Deploy](/imagens/jenkinsLeilaoDeploy.png)

Para tornar o processo mais eficiente e escalável, estou utilizando uma imagem Docker para rodar o Jenkins. Isso traz diversas vantagens, como a portabilidade do ambiente de execução, facilidade de configuração e isolamento das dependências, o que simplifica muito a instalação e a manutenção da ferramenta.

![Docker](/imagens/DockerJenkins.png)
