# Devops

#### No âmbito da criação, estruturação e suporte ao ambiente Google Cloud Platform (GCP), nossa equipe assume diversas responsabilidades cruciais para garantir a eficiência, segurança e escalabilidade dos serviços. Essas responsabilidades incluem:

- Criação e Estruturação do Ambiente GCP: Definimos a arquitetura do ambiente de nuvem, garantindo que ele atenda às necessidades da organização e possa crescer de forma sustentável.

- Definição da Hierarquia de Projetos: Estabelecemos uma hierarquia clara para os projetos, permitindo uma gestão eficaz dos recursos e uma melhor organização dos dados e serviços.

- Políticas de Permissionamento: Implementamos políticas rigorosas de controle de acesso, assegurando que apenas usuários autorizados possam acessar e modificar recursos, protegendo assim a integridade e a segurança das informações.

- Gerenciamento de Contas de Serviço: Administramos as contas de serviço necessárias para automações e interações entre serviços, garantindo que tenham as permissões adequadas e sejam mantidas de forma segura.

- Implantação de Pipelines CI/CD: Estamos aprendendo e aplicando práticas de integração e entrega contínuas (CI/CD) para automatizar o desenvolvimento e a implantação de aplicações, melhorando a eficiência e reduzindo o tempo de entrega.

- Automação com Terraform: Estamos utilizando o Terraform para gerenciar a infraestrutura como código (IaC), o que nos permite automatizar a criação e a manutenção de recursos na nuvem de maneira consistente e reproduzível.

## Ferramentas Utilizadas

### 1. *Infinity Free*
- *Descrição*: Plataforma usada para criação do domínio da organização. 

### 2. *Console Admin*
- *Descrição*: Ferramenta do Google desenvolvida para administradores gerenciarem suas organizações.

### 3. *Jenkins*
- *Descrição*: O Jenkins é uma ferramenta de automação usada para integração contínua e entrega contínua (CI/CD).

### 4. *Vagrant*
- *Descrição*: O Vagrant é uma ferramenta para criar e gerenciar ambientes virtuais de desenvolvimento de forma rápida e consistente.

### 5. *VirtualBox*
- *Descrição*: O VirtualBox é um software de virtualização que permite executar múltiplos sistemas operacionais simultaneamente em um único computador.

### 6. *Docker*
- *Descrição*: O Docker é uma plataforma de contêineres que permite criar, implantar e executar aplicações em ambientes isolados e portáveis.

### 7. *CloudBuild*
- *Descrição*: O Cloud Build é um serviço do Google Cloud para construir pipelines automatizadas.

### 8. *Terraform*
- *Descrição*: Terraform é uma ferramenta de infraestrutura como código que permite criar, modificar e versionar recursos de nuvem de forma automatizada e declarativa.

#### Atualmente, nossa organização adota uma estrutura de grupos de permissionamento para facilitar e agilizar a concessão de permissões a diferentes squads que compartilham objetivos comuns. Além disso, utilizamos contas de serviço dedicadas para atender às necessidades específicas de cada aplicação, garantindo que cada recurso tenha acesso apropriado e seguro. Abaixo, apresentamos a distribuição detalhada das permissões.

## Permissões atribuídas

### Principal: 756882@pefisa.com.br
Papéis:

- Editor

### Principal: 95663131429-compute@developer.gserviceaccount.com
Papéis:

- Acessador de campo de registro
- Acessador de exibição de registros
- Acessador de links do registro
- Agente de serviço do Monitoring
- Chamador do Cloud Run
- Conta de serviço do Cloud Build
- Destinatário do evento do Eventarc
- Editor de configuração de painel do Monitoring
- Editor de dados BigQuery
- Editor de monitoramento
- Editor do canal de notificação de monitoramento
- Editor do Monitoring AlertPolicy
- Editor dos serviços de Monitoring
- Gravador de alertas SQL
- Gravador de configuração de registros
- Leitor de dados do BigQuery
- Visualizador de registros privados

### Principal: BackOps@finops2rp.rf.gd
Papéis:

- Acessador de campo de registro
- Acessador de exibição de registros
- Acessador de links do registro
- Builder do Cloud Run 
- Chamador do Cloud Functions
- Chamador do Cloud Run
- Consumidor do Service Usage
- Criador de código
- dataform.workflow.role
- Desenvolvedor do Cloud Functions
- Desenvolvedor do Cloud Run
- Editor de configuração de painel do Monitoring
- Editor de dados BigQuery
- Editor de monitoramento
- Editor do canal de notificação de monitoramento
- Editor do Dataform
- Editor do Monitoring AlertPolicy
- Editor dos serviços de Monitoring
- Executor de jobs do Cloud Scheduler
- Gerente de faturamento do projeto
- Gravador de alertas SQL
- Gravador de configuração de registros
- Leitor
- Leitor de dados do BigQuery
- Leitor de recursos do BigQuery
- Leitor do Dataform
- Usuário da conta de serviço
- Visualizador de registros privados

### Principal: CallOfData@finops2rp.rf.gd
Papéis:

- colab
- Criador de objeto do Storage
- Desenvolvedor de origem do Cloud Run
- Desenvolvedor do Cloud Run
- Editor de dados BigQuery
- Editor do Dataform
- Gravador de bucket de registros
- Leitor
- Leitor de objetos do Storage
- Usuário da conta de serviço
- Usuário da Vertex AI
- Usuário de jobs do BigQuery

### Principal: CloudStrike@finops2rp.rf.gd
Papéis:

- Editor de dados BigQuery
- Editor de tags do Data Catalog
- Leitor de dados do BigQuery
- Leitor de metadados do BigQuery
- Leitor de objetos do Storage
- Leitor do Dataform
- Taxonomies
- Usuário de jobs do BigQuery

### Principal: colab-591@integracaohomologado.iam.gserviceaccount.com
Papéis:

- colab
- Agente de serviço de recursos do Cloud
- Criador de objeto do Storage
- Editor de dados BigQuery
- Leitor
- Leitor de dados do BigQuery
- Leitor do Cloud Storage para Firebase
- Usuário de ambiente e de objetos do Storage
- Usuário do BigQuery

### Principal: devops.pefisa@finops2rp.rf.gd
Papéis:

- Administrador da chave da conta de serviço
- Administrador da conta de serviço
- Administrador da organização
- Administrador de IAM do projeto
- Administrador de retenção de tag
- Administrador do Gerenciador de secrets
- Criador de chaves externas da conta
- Proprietário

### Principal: EmptyCloud@finops2rp.rf.gd
Papéis:

- Administrador do Dataform
- Editor de dados BigQuery
- Leitor do recomendador de compromissos de uso da conta de faturamento
- Usuário de jobs do BigQuery

### Principal: Fullstack@finops2rp.rf.gd
Papéis:

- Assessor de secret do Secret Manager
- Cliente do Cloud SQL
- Criador de objeto do Storage
- Desenvolvedor do Cloud Functions
- Editor de dados BigQuery
- Editor pub/sub
- Executor de jobs do Cloud Scheduler
- Gerenciador de versões de secret do Secret Manager
- Leitor
- Leitor de dados do BigQuery
- Leitor de metadados do BigQuery
- Leitor de objetos do Storage
- Usuário da conta de serviço
- Usuário da Vertex AI
- Usuário de jobs do BigQuery

### Principal: giovani.rodrigues@finops2rp.rf.gd
Papéis:

- Leitor do Cloud Build
  
### Principal: HaloWorld@finops2rp.rf.gd
Papéis:

- Administrador do Dataform
- Editor de código
- Editor de dados BigQuery
- Leitor de objetos do Storage
- Usuário de jobs do BigQuery

### Principal: matheus.barbosa@finops2rp.rf.gd
Papéis:

- Proprietário

### Principal: mockdados@integracaohomologado.iam.gserviceaccount.com
Papéis:

- Editor de dados BigQuery
- Gerenciador de versões de secret do Secret Manager
- Leitor de dados do BigQuery
- Leitor de metadados do BigQuery
- Usuário de jobs do BigQuery

### Principal: pfs-risco-tivea@integracaohomologado.iam.gserviceaccount.com
Papéis:

- Administrador do BigQuery
- Administrador do Dataform
- Criador do token da conta de serviço

### Principal: pfs-risco-tivea@integracaohomologado.iam.gserviceaccount.com?uid=108905301942289976870
Papéis:

- Assessor de secret do Secret Manager

### Principal: rafael.ribeiro@finops2rp.rf.gd
Papéis:

- Administrador da organização
- Administrador de IAM do projeto
- Administrador de transparência no acesso
- Gerente de faturamento do projeto
- Proprietário
- Transportador de projetos


## Observações
Os administradores das permissões IAM da organização são a equipe DevOps:
- Gabriel P.
- Matheus B.
