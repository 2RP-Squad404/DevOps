# Pipeline Dataform
Estamos explorando o funcionamento do Cloud Build para desenvolver uma pipeline de automação do Dataform. Essa pipeline tem como objetivo automatizar a validação de scripts SQL migrados do Cloudera para o GCP. O processo seguirá as etapas descritas no diagrama de sequência apresentado abaixo.

![Diagrama](/imagens/DiagramaDeSequencia.png)

O diagrama de sequência apresenta as seguintes etapas:
* Scripts Traduzidos do Cloudera para o Dataform
* Validação de Scripts SQL
* Scripts são enviados para o Github
* Pipeline faz testes e envia os scripts para o Dataform Produção

![Github](/imagens/Github.png)

### Cloud Build
O Cloud Build é uma ferramenta de automação de pipelines de desenvolvimento que permite criar e executar pipelines de automação de desenvolvimento.<br>
O Cloud Build foi configurado para executar a pipeline de automação do Dataform, e realizar testes e envio de scripts para o Dataform Produção.
 
![Gatilho](/imagens/Gatilho1.png)

<br>
Infelizmente, este projeto ainda está em desenvolvimento e apresenta alguns erros que precisam ser corrigidos. O histórico do Cloud Build mostra que ele não está funcionando como esperado. No entanto, estou ativamente trabalhando para identificar e resolver esses problemas. Os detalhes atuais podem ser observados nas imagens abaixo.<br>
<br>

![Cloud Build](/imagens/CloudBuild1.png)

![Cloud Build](/imagens/CloudBuild2.png)