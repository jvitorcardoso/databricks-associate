# 🧠 Preparatório p/ Databricks Associate (com Gabarito e Comentários)

## Questão n° 1
**Qual vantagem abaixo descreve algo que está presente em uma arquitetura Lakehouse, mas não em um data warehouse tradicional?**

- A. Um sistema relacional de gerenciamento de dados.
- B. Um sistema que permite análises em batch e em tempo real de forma integrada.
- C. Um formato proprietário para armazenamento de dados.
- D. A utilização de snapshots para controle de versão de dados.

**✅ Resposta correta:** B
*💬 *Comentário:* A arquitetura Lakehouse suporta análises em batch e em tempo real de forma integrada, o que não é encontrado em data warehouses tradicionais. Este é um dos diferenciais fundamentais da arquitetura Lakehouse.

## Questão n° 2
**Onde estão localizados os nós de driver e de trabalhador de um cluster gerenciado pelo Databricks?**

- A. No plano de dados (data plane).
- B. No Databricks Filesystem.
- C. No plano de controle (control plane).
- D. Na interface web do Databricks.

**✅ Resposta correta:** A
*💬 *Comentário:* No Databricks, os nós de driver e de trabalhador são localizados no plano de dados (data plane), enquanto o plano de controle gerencia metadados e solicitações.

## Questão n° 3
**Um arquiteto de dados precisa modelar dados para cargas de trabalho de aprendizado de máquina baseadas em vídeo e também para ETL altamente auditado. Como a arquitetura Lakehouse atende às necessidades desses dois cenários?**

- A. Combina dados estruturados e não estruturados com conformidade ACID.
- B. Permite auto-escalonamento para clusters de processamento.
- C. Exige pouca modelagem de dados para atender aos requisitos.
- D. Permite governança simples ao combinar computação e armazenamento.

**✅ Resposta correta:** A
*💬 *Comentário:* A arquitetura Lakehouse combina suporte a dados estruturados e não estruturados com conformidade ACID, o que é essencial para aprendizado de máquina e pipelines ETL auditáveis.

## Questão n° 4
**Quando um engenheiro de dados deve preferir usar um Job cluster em vez de um cluster de uso geral?**

- A. Para uma análise pontual que exige colaboração entre equipes.
- B. Para agendar fluxos de trabalho automatizados que devem ser executados periodicamente.
- C. Para criar relatórios ad-hoc com otimização de custos.
- D. Para investigar manualmente um erro em produção.

**✅ Resposta correta:** B
*💬 *Comentário:* Job clusters são criados para fluxos de trabalho automatizados que precisam ser executados periodicamente, otimizando custos e recursos, diferentemente de clusters de uso geral.

## Questão n° 5
**Um engenheiro de dados criou uma tabela Delta em uma pipeline. Analistas de dados agora precisam de permissões SELECT nesta tabela. Qual ferramenta do Databricks pode ser usada para conceder essa permissão?**

- A. Jobs.
- B. Data Explorer.
- C. Dashboards.
- D. Repos.

**✅ Resposta correta:** B
*💬 *Comentário:* O Data Explorer no Databricks permite configurar permissões como SELECT diretamente nas tabelas, facilitando o controle de acesso.

## Questão n° 6
**Dois engenheiros de dados estão colaborando em partes separadas de um único notebook de pipeline de dados. Eles estão trabalhando em branches do Git diferentes para evitar conflitos. Um engenheiro sênior sugere uma alternativa melhor para essa colaboração.**

- Qual funcionalidade do Databricks Notebooks suporta diretamente essa sugestão?
- 
- A. Coautoria em tempo real no mesmo notebook.
- B. Suporte a múltiplos idiomas dentro de um mesmo notebook.
- C. Rastreamento automático de alterações e versionamento.
- D. Criação de visualizações interativas diretamente no notebook.

**✅ Resposta correta:** A
*💬 *Comentário:* A coautoria em tempo real no Databricks Notebooks permite que vários usuários colaborem simultaneamente em um mesmo notebook, reduzindo conflitos.

## Questão n° 7
**Como o recurso Repos no Databricks facilita fluxos de trabalho de CI/CD na plataforma Lakehouse?**

- A. Facilita solicitações de pull, revisões e aprovação antes de mesclar branches.
- B. Armazena o repositório Git usado como fonte única de verdade.
- C. Permite criar e disparar pipelines de automação Git diretamente.
- D. Commite ou envia alterações de código para iniciar processos CI/CD automaticamente.

**✅ Resposta correta:** D
*💬 *Comentário:* O recurso Repos do Databricks permite realizar commits diretamente no código, iniciando processos de CI/CD automaticamente.

## Questão n° 8
**Como o Delta Lake é descrito corretamente em relação à sua função como camada de armazenamento?**

- A. Um formato de armazenamento aberto que oferece confiabilidade, segurança e desempenho.
- B. Um mecanismo de análise open source utilizado para grandes volumes de dados.
- C. Uma plataforma para gerenciar todo o ciclo de vida de aprendizado de máquina.
- D. Um formato proprietário de armazenamento de dados distribuídos.

**✅ Resposta correta:** A
*💬 *Comentário:* O Delta Lake é descrito como um formato de armazenamento aberto que oferece confiabilidade, segurança e desempenho, sendo projetado para atender às necessidades modernas de dados.

## Questão n° 9
**Qual comando SQL permite criar uma tabela Delta com o esquema especificado, garantindo que ela será criada apenas se ainda não existir uma tabela com o mesmo nome?**

- A. CREATE OR REPLACE TABLE
- B. CREATE TABLE IF NOT EXISTS
- C. CREATE TABLE AS SELECT
- D. CREATE OR REPLACE TABLE WITH COLUMNS

**✅ Resposta correta:** B
*💬 *Comentário:* O comando CREATE TABLE IF NOT EXISTS cria uma tabela Delta apenas se ela ainda não existir, garantindo que não ocorra erro se a tabela já estiver presente.

## Questão n° 10
**Qual comando SQL é utilizado para adicionar novas linhas a uma tabela Delta existente?**

- A. INSERT INTO
- B. UPDATE
- C. COPY
- D. MERGE

**✅ Resposta correta:** A
*💬 *Comentário:* O comando INSERT INTO é utilizado para adicionar novas linhas a uma tabela Delta existente sem modificar os dados já presentes.

## Questão n° 11
**Qual das opções descreve corretamente a função de um plano de dados (data plane) no Databricks?**

- A. Gerencia permissões e metadados na plataforma.
- B. Hospeda nós de driver e worker em clusters gerenciados.
- C. Controla o acesso aos recursos por meio de uma interface web.
- D. Armazena logs de auditoria para compliance.

**✅ Resposta correta:** B
*💬 *Comentário:* O plano de dados (data plane) hospeda os nós de driver e worker em clusters gerenciados, enquanto outras opções se referem a funcionalidades diferentes.

## Questão n° 12
**Qual é a diferença principal entre um cluster de uso geral (all-purpose cluster) e um cluster de jobs (job cluster)?**

- A. Clusters de uso geral são utilizados apenas para tarefas de produção.
- B. Clusters de jobs são temporários e focados em executar tarefas automatizadas.
- C. Clusters de uso geral oferecem maior performance em pipelines ETL.
- D. Clusters de jobs permitem a execução de múltiplas tarefas simultâneas.

**✅ Resposta correta:** B
*💬 *Comentário:* Clusters de jobs são temporários e otimizados para execução de tarefas automatizadas, sendo encerrados automaticamente após o término do trabalho.

## Questão n° 13
**Um arquiteto de dados está projetando um modelo que precisa suportar tanto dados não estruturados quanto ACID compliance. Qual tecnologia atende a essas necessidades?**

- A. Apache Hadoop.
- B. Um armazém de dados tradicional.
- C. Delta Lake.
- D. Apache Hive.

**✅ Resposta correta:** C
*💬 *Comentário:* O Delta Lake suporta dados não estruturados e conformidade ACID, tornando-o ideal para cenários que exigem transações confiáveis e análise de dados variados.

## Questão n° 14
**O que acontece ao usar o comando CREATE TABLE AS SELECT no Databricks?**

- A. O esquema da nova tabela é adotado do resultado da consulta SQL.
- B. A tabela será criada apenas se ela ainda não existir no sistema.
- C. Os dados existentes na tabela serão substituídos.
- D. Uma tabela temporária será criada para uso exclusivo na sessão atual.

**✅ Resposta correta:** A
*💬 *Comentário:* O comando CREATE TABLE AS SELECT cria uma nova tabela baseada no resultado de uma consulta, inferindo o esquema diretamente dos dados consultados.

## Questão n° 15
**Qual método de otimização pode melhorar a performance de uma consulta em tabelas Delta Lake cujos dados estão distribuídos aleatoriamente?**

- A. Data skipping.
- B. Z-Ordering.
- C. Bin-packing.
- D. Compactação de arquivos.

**✅ Resposta correta:** B
*💬 *Comentário:* O Z-Ordering organiza fisicamente os dados no disco, o que melhora o desempenho de consultas que filtram frequentemente por valores em colunas específicas.

## Questão n° 16
**Um engenheiro de dados quer criar uma tabela relacional a partir de duas tabelas existentes. A nova tabela deve estar disponível para outros engenheiros e evitar cópias físicas dos dados. Qual opção o engenheiro deve usar?**

- A. Criar uma view.
- B. Criar uma tabela temporária.
- C. Criar uma tabela Delta.
- D. Criar um banco de dados.

**✅ Resposta correta:** A
*💬 *Comentário:* Views são usadas para criar uma representação relacional dos dados existentes, sem a necessidade de replicá-los fisicamente.

## Questão n° 17
**Um engenheiro de dados percebe que ao usar tabelas Parquet em sistemas externos, consultas no Databricks não retornam os novos dados. Como resolver isso?**

- A. Converter as tabelas para o formato Delta.
- B. Atualizar o cluster antes de executar as consultas.
- C. Adicionar metadados para evitar caching.
- D. Configurar refresh automático no Databricks.

**✅ Resposta correta:** A
*💬 *Comentário:* Converter tabelas Parquet para o formato Delta resolve o problema de atualizações não refletidas, pois o Delta Lake gerencia metadados mais eficientemente.

## Questão n° 18
**Qual das opções representa corretamente o uso do Z-Ordering em tabelas Delta Lake?**

- A. É uma técnica para compactar os arquivos físicos.
- B. Ordena fisicamente os dados para melhorar a eficiência das consultas.
- C. Reduz o tamanho dos arquivos para melhorar a performance de escrita.
- D. Garante a exclusividade das chaves primárias em tabelas Delta.

**✅ Resposta correta:** B
*💬 *Comentário:* O Z-Ordering organiza fisicamente os dados no disco para melhorar a eficiência das consultas, especialmente ao filtrar por colunas.

## Questão n° 19
**Um engenheiro de dados quer combinar horizontalmente duas tabelas utilizando uma coluna em comum como chave, retornando apenas as linhas que existem nas duas tabelas. Qual comando SQL é apropriado?**

- A. INNER JOIN
- B. LEFT JOIN
- C. OUTER JOIN
- D. UNION

**✅ Resposta correta:** A
*💬 *Comentário:* O INNER JOIN retorna apenas as linhas que existem em ambas as tabelas, atendendo ao requisito da questão.

## Questão n° 20
**Um engenheiro de dados precisa transformar uma coluna JSON em múltiplas linhas, extraindo valores individuais. Qual função SQL deve ser usada?**

- A. FILTER
- B. EXPLODE
- C. FLATTEN
- D. MAP

**✅ Resposta correta:** B
*💬 *Comentário:* A função SQL EXPLODE transforma elementos de uma coluna JSON em múltiplas linhas, extraindo valores individuais.

## Questão n° 21
**Um engenheiro de dados quer criar uma tabela Delta que só será atualizada com os novos dados inseridos. Qual comando SQL deve ser usado?**

- A. UPDATE
- B. INSERT INTO
- C. COPY INTO
- D. MERGE

**✅ Resposta correta:** B
*💬 *Comentário:* O comando INSERT INTO adiciona apenas novos dados a uma tabela existente, sem modificar os registros já presentes.

## Questão n° 22
**Um engenheiro de dados está criando uma nova tabela Delta e deseja garantir que ela seja sobrescrita se já existir. Qual comando SQL é apropriado?**

- A. CREATE TABLE
- B. CREATE OR REPLACE TABLE
- C. CREATE TABLE IF NOT EXISTS
- D. ALTER TABLE

**✅ Resposta correta:** B
*💬 *Comentário:* O comando CREATE OR REPLACE TABLE cria ou sobrescreve uma tabela Delta, garantindo que novos dados possam substituir os antigos.

## Questão n° 23
**Qual das opções melhor descreve o comportamento de um comando MERGE no Delta Lake?**

- A. Insere dados duplicados em uma tabela existente.
- B. Atualiza ou insere dados dependendo de uma condição específica.
- C. Sobrescreve os dados existentes com base na ordem dos arquivos.
- D. Remove as linhas que não satisfazem as condições da consulta.

**✅ Resposta correta:** B
*💬 *Comentário:* O comando MERGE no Delta Lake atualiza ou insere dados com base em condições específicas, como comparação de chaves.

## Questão n° 24
**O que acontece quando o comando VACUUM é executado em uma tabela Delta?**

- A. Compacta os arquivos físicos da tabela.
- B. Remove versões antigas dos arquivos não referenciados.
- C. Garante conformidade com as transações ACID.
- D. Atualiza os índices da tabela.

**✅ Resposta correta:** B
*💬 *Comentário:* O comando VACUUM remove arquivos antigos e não referenciados de uma tabela Delta, liberando espaço em disco.

## Questão n° 25
**Um engenheiro de dados está usando Auto Loader para processar dados incrementais de arquivos JSON. Qual parâmetro é necessário para habilitar o rastreamento do esquema automaticamente?**

- A. .option("cloudFiles.autoSchema", "true")
- B. .option("cloudFiles.schemaLocation", "/path/to/schema")
- C. .option("jsonSchema.auto", "true")
- D. .option("schemaTracking.enabled", "true")

**✅ Resposta correta:** B
*💬 *Comentário:* O parâmetro .option("cloudFiles.schemaLocation") define um local persistente para rastrear a evolução do esquema, essencial no Auto Loader.

## Questão n° 26
**Qual é a vantagem do Z-Ordering sobre compactação padrão em tabelas Delta Lake?**

- A. Reduz o espaço em disco.
- B. Melhora a performance de consultas que utilizam filtros por coluna.
- C. Otimiza operações de escrita em tabelas grandes.
- D. Garante exclusividade em chaves primárias.

**✅ Resposta correta:** B
*💬 *Comentário:* O Z-Ordering melhora a performance de consultas aplicando filtros, reorganizando dados fisicamente de forma otimizada.

## Questão n° 27
**Qual dos seguintes comandos SQL pode ser usado para remover duplicatas de uma tabela Delta?**

- A. SELECT DISTINCT * FROM table_name
- B. DELETE DUPLICATES FROM table_name
- C. ALTER TABLE table_name REMOVE DUPLICATES
- D. UPDATE table_name DROP DUPLICATES

**✅ Resposta correta:** A
*💬 *Comentário:* O comando SELECT DISTINCT remove duplicatas ao retornar apenas valores únicos de uma tabela.

## Questão n° 28
**Um engenheiro de dados precisa identificar a localização exata de um arquivo armazenado em uma tabela Delta. Qual comando deve ser usado?**

- A. DESCRIBE FORMATTED
- B. SHOW FILES
- C. LIST FILES
- D. DESCRIBE DETAIL

**✅ Resposta correta:** D
*💬 *Comentário:* O comando DESCRIBE DETAIL fornece informações detalhadas sobre a localização e outros metadados dos arquivos em uma tabela Delta.

## Questão n° 29
**Qual é o comportamento padrão do Delta Lake em relação à conformidade ACID?**

- A. Permite apenas transações de leitura e escrita sequenciais.
- B. Garante que todas as transações sejam atômicas, consistentes, isoladas e duráveis.
- C. Requer que as transações sejam aprovadas manualmente.
- D. Fornece controle de versão apenas para dados não estruturados.

**✅ Resposta correta:** B
*💬 *Comentário:* O Delta Lake garante que todas as transações sejam atômicas, consistentes, isoladas e duráveis (ACID compliance).

## Questão n° 30
**Qual recurso do Databricks é usado para definir permissões detalhadas, como acesso a tabelas ou colunas específicas?**

- A. Databricks Repos
- B. Data Explorer
- C. Unity Catalog
- D. Databricks Jobs

**✅ Resposta correta:** C
*💬 *Comentário:* O Unity Catalog é usado para definir permissões detalhadas, incluindo acesso a tabelas e colunas específicas.

## Questão n° 31
**Qual comando pode ser usado para reverter uma tabela Delta para uma versão anterior?**

- A. VACUUM
- B. RESTORE
- C. REVERT
- D. ROLLBACK

**✅ Resposta correta:** B
*💬 *Comentário:* O comando RESTORE permite reverter uma tabela Delta a uma versão anterior, útil para recuperação de dados.

## Questão n° 32
**Ao configurar uma pipeline com Delta Live Tables, qual funcionalidade ajuda a definir dependências entre tabelas?**

- A. Utilizar o comando CREATE LIVE TABLE.
- B. Usar o MERGE INTO.
- C. Criar uma DAG (Directed Acyclic Graph).
- D. Definir chaves primárias nas tabelas Delta.

**✅ Resposta correta:** A
*💬 *Comentário:* O comando CREATE LIVE TABLE no Delta Live Tables ajuda a definir dependências entre tabelas automaticamente.

## Questão n° 33
**Um engenheiro de dados precisa combinar duas tabelas Delta usando uma coluna-chave, mas deseja incluir todas as linhas, independentemente de corresponderem ou não na outra tabela. Qual comando SQL deve ser usado?**

- A. LEFT JOIN
- B. INNER JOIN
- C. FULL OUTER JOIN
- D. UNION

**✅ Resposta correta:** C
*💬 *Comentário:* O FULL OUTER JOIN retorna todas as linhas de ambas as tabelas, mesmo que não correspondam.

## Questão n° 34
**Ao usar Auto Loader para ingestão de dados incrementais, qual vantagem ele oferece em relação à ingestão manual?**

- A. Atualiza automaticamente as permissões do Unity Catalog.
- B. Garante performance otimizada com compactação automática.
- C. Monitora novas alterações nos dados sem necessidade de configuração manual.
- D. Reduz os custos de computação em até 50%.

**✅ Resposta correta:** C
*💬 *Comentário:* O Auto Loader monitora alterações nos dados automaticamente, simplificando a ingestão incremental sem configuração manual.

## Questão n° 35
**Ao criar tabelas no Delta Live Tables, qual é o comportamento esperado ao processar dados que violam as expectativas configuradas?**

- A. Os dados são descartados silenciosamente.
- B. Os dados são adicionados a uma tabela de quarentena.
- C. A execução da pipeline falha imediatamente.
- D. Os dados são armazenados com um indicador de validação.

**✅ Resposta correta:** B
*💬 *Comentário:* Dados que violam expectativas no Delta Live Tables são adicionados a uma tabela de quarentena, permitindo auditoria e ajustes.

## Questão n° 36
**Um engenheiro de dados quer criar uma tabela gerenciada no Databricks. Qual comando é apropriado?**

- A. CREATE TABLE table_name USING DELTA LOCATION '/path/to/data'
- B. CREATE MANAGED TABLE table_name (id STRING, value INT)
- C. CREATE TABLE table_name (id STRING, value INT)
- D. CREATE TABLE table_name LOCATION '/path/to/data'

**✅ Resposta correta:** C
*💬 *Comentário:* O comando CREATE TABLE cria uma tabela gerenciada, permitindo que o Databricks gerencie automaticamente os metadados e o armazenamento.

## Questão n° 37
**Qual comando SQL pode ser usado para criar uma visualização temporária de dados em um Spark DataFrame?**

- A. CREATE TEMP VIEW view_name AS SELECT ...
- B. CREATE VIEW view_name AS SELECT ...
- C. CREATE OR REPLACE TEMP VIEW view_name AS SELECT ...
- D. CREATE OR REPLACE VIEW view_name AS SELECT ...

**✅ Resposta correta:** C
*💬 *Comentário:* O comando CREATE OR REPLACE TEMP VIEW cria ou substitui visualizações temporárias de dados para análises rápidas.

## Questão n° 38
**Ao configurar pipelines de produção no Databricks, qual das opções representa corretamente o uso de múltiplas tarefas em um único job?**

- A. Permite que as tarefas sejam executadas em paralelo sem dependências.
- B. Exige que todas as tarefas sejam executadas sequencialmente.
- C. Suporta tarefas com dependências definidas de forma linear.
- D. Garante que todas as tarefas sejam executadas no mesmo cluster.

**✅ Resposta correta:** C
*💬 *Comentário:* As tarefas em um job podem ter dependências lineares definidas, garantindo a execução na ordem correta.

## Questão n° 39
**Ao usar Delta Live Tables, qual é o modo de execução recomendado para desenvolvimento e testes?**

- A. Production Mode
- B. Development Mode
- C. Testing Mode
- D. Debugging Mode

**✅ Resposta correta:** B
*💬 *Comentário:* O Development Mode no Delta Live Tables é ideal para desenvolvimento e testes, permitindo alterações iterativas.

## Questão n° 40
**Ao configurar uma política de retenção em tabelas Delta, qual comando define o tempo de retenção para versões antigas?**

- A. ALTER TABLE table_name SET RETENTION 7
- B. ALTER TABLE table_name SET TBLPROPERTIES ("delta.logRetentionDuration" = "interval")
- C. VACUUM table_name RETAIN 7 DAYS
- D. SET TABLE RETENTION 7

**✅ Resposta correta:** C
*💬 *Comentário:* O comando VACUUM RETAIN define o tempo de retenção para arquivos antigos em tabelas Delta, removendo dados obsoletos.

## Questão n° 41
**Qual das opções é uma vantagem principal de usar Delta Live Tables para pipelines de dados?**

- A. Oferece um ambiente completamente sem código.
- B. Garante versionamento automático dos dados processados.
- C. Simplifica a definição de dependências entre tabelas.
- D. Fornece escalabilidade ilimitada para grandes volumes de dados.

**✅ Resposta correta:** C
*💬 *Comentário:* O Delta Live Tables simplifica a definição de dependências entre tabelas, reduzindo erros manuais e melhorando a gestão.

## Questão n° 42
**Ao configurar um SQL Endpoint no Databricks, qual configuração pode melhorar a latência de consultas sequenciais?**

- A. Aumentar o tamanho do cluster associado ao endpoint.
- B. Habilitar o recurso Serverless no endpoint.
- C. Configurar o Auto Stop para minimizar custos.
- D. Aumentar o limite de tempo para inatividade do endpoint.

**✅ Resposta correta:** B
*💬 *Comentário:* O recurso Serverless nos SQL Endpoints melhora a latência ao gerenciar automaticamente os recursos de execução.

## Questão n° 43
**Qual funcionalidade do Databricks permite o envio automático de alertas baseados em condições específicas de uma consulta SQL?**

- A. Notificações de pipeline.
- B. Dashboards automatizados.
- C. Regras de alerta em queries SQL.
- D. Configuração de notificações no Unity Catalog.

**✅ Resposta correta:** C
*💬 *Comentário:* As regras de alerta em queries SQL enviam notificações automáticas com base em condições definidas pelo usuário.

## Questão n° 44
**Um engenheiro de dados quer garantir que um job no Databricks será reexecutado automaticamente em caso de falha. Qual configuração é apropriada?**

- A. Ativar o recurso de auto-scaling.
- B. Configurar uma política de retry no job.
- C. Garantir que o job use um cluster exclusivo.
- D. Habilitar a opção de fail-safe manualmente.

**✅ Resposta correta:** B
*💬 *Comentário:* Configurar uma política de retry nos jobs garante a reexecução automática em caso de falha.

## Questão n° 45
**Qual dos comandos é usado para conceder permissões completas sobre uma tabela no Unity Catalog?**

- A. GRANT SELECT ON TABLE table_name TO user@domain.com
- B. GRANT ALL PRIVILEGES ON TABLE table_name TO user@domain.com
- C. GRANT CREATE ON TABLE table_name TO user@domain.com
- D. GRANT SELECT, INSERT ON TABLE table_name TO user@domain.com

**✅ Resposta correta:** B
*💬 *Comentário:* O comando GRANT ALL PRIVILEGES concede todas as permissões para uma tabela no Unity Catalog, atendendo às necessidades de gerenciamento de acessos.

## Questão n° 46
**Qual vantagem abaixo descreve algo que está presente em uma arquitetura Lakehouse, mas não em um data warehouse tradicional?**

- A. Um sistema relacional de gerenciamento de dados.
- B. Um sistema que permite análises em batch e em tempo real de forma integrada.
- C. Um formato proprietário para armazenamento de dados.
- D. A utilização de snapshots para controle de versão de dados.

**✅ Resposta correta:** B
💬 *Comentário:* A arquitetura Lakehouse suporta análises em batch e em tempo real de forma integrada, o que não é encontrado em data warehouses tradicionais. Este é um dos diferenciais fundamentais da arquitetura Lakehouse.

## Questão n° 47
**Onde estão localizados os nós de driver e de trabalhador de um cluster gerenciado pelo Databricks?**

- A. No plano de dados (data plane).
- B. No Databricks Filesystem.
- C. No plano de controle (control plane).
- D. Na interface web do Databricks.

**✅ Resposta correta:** A
💬 *Comentário:* No Databricks, os nós de driver e de trabalhador são localizados no plano de dados (data plane), enquanto o plano de controle gerencia metadados e solicitações.

## Questão n° 48
**Um arquiteto de dados precisa modelar dados para cargas de trabalho de aprendizado de máquina baseadas em vídeo e também para ETL altamente auditado. Como a arquitetura Lakehouse atende às necessidades desses dois cenários?**

- A. Combina dados estruturados e não estruturados com conformidade ACID.
- B. Permite auto-escalonamento para clusters de processamento.
- C. Exige pouca modelagem de dados para atender aos requisitos.
- D. Permite governança simples ao combinar computação e armazenamento.

**✅ Resposta correta:** A
💬 *Comentário:* A arquitetura Lakehouse combina suporte a dados estruturados e não estruturados com conformidade ACID, o que é essencial para aprendizado de máquina e pipelines ETL auditáveis.

## Questão n° 49
**Quando um engenheiro de dados deve preferir usar um Job cluster em vez de um cluster de uso geral?**

- A. Para uma análise pontual que exige colaboração entre equipes.
- B. Para agendar fluxos de trabalho automatizados que devem ser executados periodicamente.
- C. Para criar relatórios ad-hoc com otimização de custos.
- D. Para investigar manualmente um erro em produção.

**✅ Resposta correta:** B
💬 *Comentário:* Job clusters são criados para fluxos de trabalho automatizados que precisam ser executados periodicamente, otimizando custos e recursos, diferentemente de clusters de uso geral.

## Questão n° 50
**Um engenheiro de dados criou uma tabela Delta em uma pipeline. Analistas de dados agora precisam de permissões SELECT nesta tabela. Qual ferramenta do Databricks pode ser usada para conceder essa permissão?**

- A. Jobs.
- B. Data Explorer.
- C. Dashboards.
- D. Repos.

**✅ Resposta correta:** B
💬 *Comentário:* O Data Explorer no Databricks permite configurar permissões como SELECT diretamente nas tabelas, facilitando o controle de acesso.

## Questão n° 51
**Dois engenheiros de dados estão colaborando em partes separadas de um único notebook de pipeline de dados. Eles estão trabalhando em branches do Git diferentes para evitar conflitos. Um engenheiro sênior sugere uma alternativa melhor para essa colaboração.**

- Qual funcionalidade do Databricks Notebooks suporta diretamente essa sugestão?
- 
- A. Coautoria em tempo real no mesmo notebook.
- B. Suporte a múltiplos idiomas dentro de um mesmo notebook.
- C. Rastreamento automático de alterações e versionamento.
- D. Criação de visualizações interativas diretamente no notebook.

**✅ Resposta correta:** A
💬 *Comentário:* A coautoria em tempo real no Databricks Notebooks permite que vários usuários colaborem simultaneamente em um mesmo notebook, reduzindo conflitos.

## Questão n° 52
**Como o recurso Repos no Databricks facilita fluxos de trabalho de CI/CD na plataforma Lakehouse?**

- A. Facilita solicitações de pull, revisões e aprovação antes de mesclar branches.
- B. Armazena o repositório Git usado como fonte única de verdade.
- C. Permite criar e disparar pipelines de automação Git diretamente.
- D. Commite ou envia alterações de código para iniciar processos CI/CD automaticamente.

**✅ Resposta correta:** D
💬 *Comentário:* O recurso Repos do Databricks permite realizar commits diretamente no código, iniciando processos de CI/CD automaticamente.

## Questão n° 53
**Como o Delta Lake é descrito corretamente em relação à sua função como camada de armazenamento?**

- A. Um formato de armazenamento aberto que oferece confiabilidade, segurança e desempenho.
- B. Um mecanismo de análise open source utilizado para grandes volumes de dados.
- C. Uma plataforma para gerenciar todo o ciclo de vida de aprendizado de máquina.
- D. Um formato proprietário de armazenamento de dados distribuídos.

**✅ Resposta correta:** A
💬 *Comentário:* O Delta Lake é descrito como um formato de armazenamento aberto que oferece confiabilidade, segurança e desempenho, sendo projetado para atender às necessidades modernas de dados.

## Questão n° 54
**Qual comando SQL permite criar uma tabela Delta com o esquema especificado, garantindo que ela será criada apenas se ainda não existir uma tabela com o mesmo nome?**

- A. CREATE OR REPLACE TABLE
- B. CREATE TABLE IF NOT EXISTS
- C. CREATE TABLE AS SELECT
- D. CREATE OR REPLACE TABLE WITH COLUMNS

**✅ Resposta correta:** B
💬 *Comentário:* O comando CREATE TABLE IF NOT EXISTS cria uma tabela Delta apenas se ela ainda não existir, garantindo que não ocorra erro se a tabela já estiver presente.

## Questão n° 55
**Qual comando SQL é utilizado para adicionar novas linhas a uma tabela Delta existente?**

- A. INSERT INTO
- B. UPDATE
- C. COPY
- D. MERGE

**✅ Resposta correta:** A
💬 *Comentário:* O comando INSERT INTO é utilizado para adicionar novas linhas a uma tabela Delta existente sem modificar os dados já presentes.

## Questão n° 56
**Qual das opções descreve corretamente a função de um plano de dados (data plane) no Databricks?**

- A. Gerencia permissões e metadados na plataforma.
- B. Hospeda nós de driver e worker em clusters gerenciados.
- C. Controla o acesso aos recursos por meio de uma interface web.
- D. Armazena logs de auditoria para compliance.

**✅ Resposta correta:** B
💬 *Comentário:* O plano de dados (data plane) hospeda os nós de driver e worker em clusters gerenciados, enquanto outras opções se referem a funcionalidades diferentes.

## Questão n° 57
**Qual é a diferença principal entre um cluster de uso geral (all-purpose cluster) e um cluster de jobs (job cluster)?**

- A. Clusters de uso geral são utilizados apenas para tarefas de produção.
- B. Clusters de jobs são temporários e focados em executar tarefas automatizadas.
- C. Clusters de uso geral oferecem maior performance em pipelines ETL.
- D. Clusters de jobs permitem a execução de múltiplas tarefas simultâneas.

**✅ Resposta correta:** B
💬 *Comentário:* Clusters de jobs são temporários e otimizados para execução de tarefas automatizadas, sendo encerrados automaticamente após o término do trabalho.

## Questão n° 58
**Um arquiteto de dados está projetando um modelo que precisa suportar tanto dados não estruturados quanto ACID compliance. Qual tecnologia atende a essas necessidades?**

- A. Apache Hadoop.
- B. Um armazém de dados tradicional.
- C. Delta Lake.
- D. Apache Hive.

**✅ Resposta correta:** C
💬 *Comentário:* O Delta Lake suporta dados não estruturados e conformidade ACID, tornando-o ideal para cenários que exigem transações confiáveis e análise de dados variados.

## Questão n° 59
**O que acontece ao usar o comando CREATE TABLE AS SELECT no Databricks?**

- A. O esquema da nova tabela é adotado do resultado da consulta SQL.
- B. A tabela será criada apenas se ela ainda não existir no sistema.
- C. Os dados existentes na tabela serão substituídos.
- D. Uma tabela temporária será criada para uso exclusivo na sessão atual.

**✅ Resposta correta:** A
💬 *Comentário:* O comando CREATE TABLE AS SELECT cria uma nova tabela baseada no resultado de uma consulta, inferindo o esquema diretamente dos dados consultados.

## Questão n° 60
**Qual método de otimização pode melhorar a performance de uma consulta em tabelas Delta Lake cujos dados estão distribuídos aleatoriamente?**

- A. Data skipping.
- B. Z-Ordering.
- C. Bin-packing.
- D. Compactação de arquivos.

**✅ Resposta correta:** B
💬 *Comentário:* O Z-Ordering organiza fisicamente os dados no disco, o que melhora o desempenho de consultas que filtram frequentemente por valores em colunas específicas.

## Questão n° 61
**Um engenheiro de dados quer criar uma tabela relacional a partir de duas tabelas existentes. A nova tabela deve estar disponível para outros engenheiros e evitar cópias físicas dos dados. Qual opção o engenheiro deve usar?**

- A. Criar uma view.
- B. Criar uma tabela temporária.
- C. Criar uma tabela Delta.
- D. Criar um banco de dados.

**✅ Resposta correta:** A
💬 *Comentário:* Views são usadas para criar uma representação relacional dos dados existentes, sem a necessidade de replicá-los fisicamente.

## Questão n° 62
**Um engenheiro de dados percebe que ao usar tabelas Parquet em sistemas externos, consultas no Databricks não retornam os novos dados. Como resolver isso?**

- A. Converter as tabelas para o formato Delta.
- B. Atualizar o cluster antes de executar as consultas.
- C. Adicionar metadados para evitar caching.
- D. Configurar refresh automático no Databricks.

**✅ Resposta correta:** A
💬 *Comentário:* Converter tabelas Parquet para o formato Delta resolve o problema de atualizações não refletidas, pois o Delta Lake gerencia metadados mais eficientemente.

## Questão n° 63
**Qual das opções representa corretamente o uso do Z-Ordering em tabelas Delta Lake?**

- A. É uma técnica para compactar os arquivos físicos.
- B. Ordena fisicamente os dados para melhorar a eficiência das consultas.
- C. Reduz o tamanho dos arquivos para melhorar a performance de escrita.
- D. Garante a exclusividade das chaves primárias em tabelas Delta.

**✅ Resposta correta:** B
💬 *Comentário:* O Z-Ordering organiza fisicamente os dados no disco para melhorar a eficiência das consultas, especialmente ao filtrar por colunas.

## Questão n° 64
**Um engenheiro de dados quer combinar horizontalmente duas tabelas utilizando uma coluna em comum como chave, retornando apenas as linhas que existem nas duas tabelas. Qual comando SQL é apropriado?**

- A. INNER JOIN
- B. LEFT JOIN
- C. OUTER JOIN
- D. UNION

**✅ Resposta correta:** A
💬 *Comentário:* O INNER JOIN retorna apenas as linhas que existem em ambas as tabelas, atendendo ao requisito da questão.

## Questão n° 65
**Um engenheiro de dados precisa transformar uma coluna JSON em múltiplas linhas, extraindo valores individuais. Qual função SQL deve ser usada?**

- A. FILTER
- B. EXPLODE
- C. FLATTEN
- D. MAP

**✅ Resposta correta:** B
💬 *Comentário:* A função SQL EXPLODE transforma elementos de uma coluna JSON em múltiplas linhas, extraindo valores individuais.

## Questão n° 66
**Um engenheiro de dados quer criar uma tabela Delta que só será atualizada com os novos dados inseridos. Qual comando SQL deve ser usado?**

- A. UPDATE
- B. INSERT INTO
- C. COPY INTO
- D. MERGE

**✅ Resposta correta:** B
💬 *Comentário:* O comando INSERT INTO adiciona apenas novos dados a uma tabela existente, sem modificar os registros já presentes.

## Questão n° 67
**Um engenheiro de dados está criando uma nova tabela Delta e deseja garantir que ela seja sobrescrita se já existir. Qual comando SQL é apropriado?**

- A. CREATE TABLE
- B. CREATE OR REPLACE TABLE
- C. CREATE TABLE IF NOT EXISTS
- D. ALTER TABLE

**✅ Resposta correta:** B
💬 *Comentário:* O comando CREATE OR REPLACE TABLE cria ou sobrescreve uma tabela Delta, garantindo que novos dados possam substituir os antigos.

## Questão n° 68
**Qual das opções melhor descreve o comportamento de um comando MERGE no Delta Lake?**

- A. Insere dados duplicados em uma tabela existente.
- B. Atualiza ou insere dados dependendo de uma condição específica.
- C. Sobrescreve os dados existentes com base na ordem dos arquivos.
- D. Remove as linhas que não satisfazem as condições da consulta.

**✅ Resposta correta:** B
💬 *Comentário:* O comando MERGE no Delta Lake atualiza ou insere dados com base em condições específicas, como comparação de chaves.

## Questão n° 69
**O que acontece quando o comando VACUUM é executado em uma tabela Delta?**

- A. Compacta os arquivos físicos da tabela.
- B. Remove versões antigas dos arquivos não referenciados.
- C. Garante conformidade com as transações ACID.
- D. Atualiza os índices da tabela.

**✅ Resposta correta:** B
💬 *Comentário:* O comando VACUUM remove arquivos antigos e não referenciados de uma tabela Delta, liberando espaço em disco.

## Questão n° 70
**Um engenheiro de dados está usando Auto Loader para processar dados incrementais de arquivos JSON. Qual parâmetro é necessário para habilitar o rastreamento do esquema automaticamente?**

- A. .option("cloudFiles.autoSchema", "true")
- B. .option("cloudFiles.schemaLocation", "/path/to/schema")
- C. .option("jsonSchema.auto", "true")
- D. .option("schemaTracking.enabled", "true")

**✅ Resposta correta:** B
💬 *Comentário:* O parâmetro .option("cloudFiles.schemaLocation") define um local persistente para rastrear a evolução do esquema, essencial no Auto Loader.

## Questão n° 71
**Qual é a vantagem do Z-Ordering sobre compactação padrão em tabelas Delta Lake?**

- A. Reduz o espaço em disco.
- B. Melhora a performance de consultas que utilizam filtros por coluna.
- C. Otimiza operações de escrita em tabelas grandes.
- D. Garante exclusividade em chaves primárias.

**✅ Resposta correta:** B
💬 *Comentário:* O Z-Ordering melhora a performance de consultas aplicando filtros, reorganizando dados fisicamente de forma otimizada.

## Questão n° 72
**Qual dos seguintes comandos SQL pode ser usado para remover duplicatas de uma tabela Delta?**

- A. SELECT DISTINCT * FROM table_name
- B. DELETE DUPLICATES FROM table_name
- C. ALTER TABLE table_name REMOVE DUPLICATES
- D. UPDATE table_name DROP DUPLICATES

**✅ Resposta correta:** A
💬 *Comentário:* O comando SELECT DISTINCT remove duplicatas ao retornar apenas valores únicos de uma tabela.

## Questão n° 73
**Um engenheiro de dados precisa identificar a localização exata de um arquivo armazenado em uma tabela Delta. Qual comando deve ser usado?**

- A. DESCRIBE FORMATTED
- B. SHOW FILES
- C. LIST FILES
- D. DESCRIBE DETAIL

**✅ Resposta correta:** D
💬 *Comentário:* O comando DESCRIBE DETAIL fornece informações detalhadas sobre a localização e outros metadados dos arquivos em uma tabela Delta.

## Questão n° 74
**Qual é o comportamento padrão do Delta Lake em relação à conformidade ACID?**

- A. Permite apenas transações de leitura e escrita sequenciais.
- B. Garante que todas as transações sejam atômicas, consistentes, isoladas e duráveis.
- C. Requer que as transações sejam aprovadas manualmente.
- D. Fornece controle de versão apenas para dados não estruturados.

**✅ Resposta correta:** B
💬 *Comentário:* O Delta Lake garante que todas as transações sejam atômicas, consistentes, isoladas e duráveis (ACID compliance).

## Questão n° 75
**Qual recurso do Databricks é usado para definir permissões detalhadas, como acesso a tabelas ou colunas específicas?**

- A. Databricks Repos
- B. Data Explorer
- C. Unity Catalog
- D. Databricks Jobs

**✅ Resposta correta:** C
💬 *Comentário:* O Unity Catalog é usado para definir permissões detalhadas, incluindo acesso a tabelas e colunas específicas.

## Questão n° 76
**Qual comando pode ser usado para reverter uma tabela Delta para uma versão anterior?**

- A. VACUUM
- B. RESTORE
- C. REVERT
- D. ROLLBACK

**✅ Resposta correta:** B
💬 *Comentário:* O comando RESTORE permite reverter uma tabela Delta a uma versão anterior, útil para recuperação de dados.

## Questão n° 77
**Ao configurar uma pipeline com Delta Live Tables, qual funcionalidade ajuda a definir dependências entre tabelas?**

- A. Utilizar o comando CREATE LIVE TABLE.
- B. Usar o MERGE INTO.
- C. Criar uma DAG (Directed Acyclic Graph).
- D. Definir chaves primárias nas tabelas Delta.

**✅ Resposta correta:** A
💬 *Comentário:* O comando CREATE LIVE TABLE no Delta Live Tables ajuda a definir dependências entre tabelas automaticamente.

## Questão n° 78
**Um engenheiro de dados precisa combinar duas tabelas Delta usando uma coluna-chave, mas deseja incluir todas as linhas, independentemente de corresponderem ou não na outra tabela. Qual comando SQL deve ser usado?**

- A. LEFT JOIN
- B. INNER JOIN
- C. FULL OUTER JOIN
- D. UNION

**✅ Resposta correta:** C
💬 *Comentário:* O FULL OUTER JOIN retorna todas as linhas de ambas as tabelas, mesmo que não correspondam.

## Questão n° 79
**Ao usar Auto Loader para ingestão de dados incrementais, qual vantagem ele oferece em relação à ingestão manual?**

- A. Atualiza automaticamente as permissões do Unity Catalog.
- B. Garante performance otimizada com compactação automática.
- C. Monitora novas alterações nos dados sem necessidade de configuração manual.
- D. Reduz os custos de computação em até 50%.

**✅ Resposta correta:** C
💬 *Comentário:* O Auto Loader monitora alterações nos dados automaticamente, simplificando a ingestão incremental sem configuração manual.

## Questão n° 80
**Ao criar tabelas no Delta Live Tables, qual é o comportamento esperado ao processar dados que violam as expectativas configuradas?**

- A. Os dados são descartados silenciosamente.
- B. Os dados são adicionados a uma tabela de quarentena.
- C. A execução da pipeline falha imediatamente.
- D. Os dados são armazenados com um indicador de validação.

**✅ Resposta correta:** B
💬 *Comentário:* Dados que violam expectativas no Delta Live Tables são adicionados a uma tabela de quarentena, permitindo auditoria e ajustes.

## Questão n° 81
**Um engenheiro de dados quer criar uma tabela gerenciada no Databricks. Qual comando é apropriado?**

- A. CREATE TABLE table_name USING DELTA LOCATION '/path/to/data'
- B. CREATE MANAGED TABLE table_name (id STRING, value INT)
- C. CREATE TABLE table_name (id STRING, value INT)
- D. CREATE TABLE table_name LOCATION '/path/to/data'

**✅ Resposta correta:** C
💬 *Comentário:* O comando CREATE TABLE cria uma tabela gerenciada, permitindo que o Databricks gerencie automaticamente os metadados e o armazenamento.

## Questão n° 82
**Qual comando SQL pode ser usado para criar uma visualização temporária de dados em um Spark DataFrame?**

- A. CREATE TEMP VIEW view_name AS SELECT ...
- B. CREATE VIEW view_name AS SELECT ...
- C. CREATE OR REPLACE TEMP VIEW view_name AS SELECT ...
- D. CREATE OR REPLACE VIEW view_name AS SELECT ...

**✅ Resposta correta:** C
💬 *Comentário:* O comando CREATE OR REPLACE TEMP VIEW cria ou substitui visualizações temporárias de dados para análises rápidas.

## Questão n° 83
**Ao configurar pipelines de produção no Databricks, qual das opções representa corretamente o uso de múltiplas tarefas em um único job?**

- A. Permite que as tarefas sejam executadas em paralelo sem dependências.
- B. Exige que todas as tarefas sejam executadas sequencialmente.
- C. Suporta tarefas com dependências definidas de forma linear.
- D. Garante que todas as tarefas sejam executadas no mesmo cluster.

**✅ Resposta correta:** C
💬 *Comentário:* As tarefas em um job podem ter dependências lineares definidas, garantindo a execução na ordem correta.

## Questão n° 84
**Ao usar Delta Live Tables, qual é o modo de execução recomendado para desenvolvimento e testes?**

- A. Production Mode
- B. Development Mode
- C. Testing Mode
- D. Debugging Mode

**✅ Resposta correta:** B
💬 *Comentário:* O Development Mode no Delta Live Tables é ideal para desenvolvimento e testes, permitindo alterações iterativas.

## Questão n° 85
**Ao configurar uma política de retenção em tabelas Delta, qual comando define o tempo de retenção para versões antigas?**

- A. ALTER TABLE table_name SET RETENTION 7
- B. ALTER TABLE table_name SET TBLPROPERTIES ("delta.logRetentionDuration" = "interval")
- C. VACUUM table_name RETAIN 7 DAYS
- D. SET TABLE RETENTION 7

**✅ Resposta correta:** C
💬 *Comentário:* O comando VACUUM RETAIN define o tempo de retenção para arquivos antigos em tabelas Delta, removendo dados obsoletos.

## Questão n° 86
**Qual das opções é uma vantagem principal de usar Delta Live Tables para pipelines de dados?**

- A. Oferece um ambiente completamente sem código.
- B. Garante versionamento automático dos dados processados.
- C. Simplifica a definição de dependências entre tabelas.
- D. Fornece escalabilidade ilimitada para grandes volumes de dados.

**✅ Resposta correta:** C
💬 *Comentário:* O Delta Live Tables simplifica a definição de dependências entre tabelas, reduzindo erros manuais e melhorando a gestão.

## Questão n° 87
**Ao configurar um SQL Endpoint no Databricks, qual configuração pode melhorar a latência de consultas sequenciais?**

- A. Aumentar o tamanho do cluster associado ao endpoint.
- B. Habilitar o recurso Serverless no endpoint.
- C. Configurar o Auto Stop para minimizar custos.
- D. Aumentar o limite de tempo para inatividade do endpoint.

**✅ Resposta correta:** B
💬 *Comentário:* O recurso Serverless nos SQL Endpoints melhora a latência ao gerenciar automaticamente os recursos de execução.

## Questão n° 88
**Qual funcionalidade do Databricks permite o envio automático de alertas baseados em condições específicas de uma consulta SQL?**

- A. Notificações de pipeline.
- B. Dashboards automatizados.
- C. Regras de alerta em queries SQL.
- D. Configuração de notificações no Unity Catalog.

**✅ Resposta correta:** C
💬 *Comentário:* As regras de alerta em queries SQL enviam notificações automáticas com base em condições definidas pelo usuário.

## Questão n° 89
**Um engenheiro de dados quer garantir que um job no Databricks será reexecutado automaticamente em caso de falha. Qual configuração é apropriada?**

- A. Ativar o recurso de auto-scaling.
- B. Configurar uma política de retry no job.
- C. Garantir que o job use um cluster exclusivo.
- D. Habilitar a opção de fail-safe manualmente.

**✅ Resposta correta:** B
💬 *Comentário:* Configurar uma política de retry nos jobs garante a reexecução automática em caso de falha.

## Questão n° 90
**Qual dos comandos é usado para conceder permissões completas sobre uma tabela no Unity Catalog?**

- A. GRANT SELECT ON TABLE table_name TO user@domain.com
- B. GRANT ALL PRIVILEGES ON TABLE table_name TO user@domain.com
- C. GRANT CREATE ON TABLE table_name TO user@domain.com
- D. GRANT SELECT, INSERT ON TABLE table_name TO user@domain.com

**✅ Resposta correta:** B
💬 *Comentário:* O comando GRANT ALL PRIVILEGES concede todas as permissões para uma tabela no Unity Catalog, atendendo às necessidades de gerenciamento de acessos.

## Questão n° 91
**Qual vantagem abaixo descreve algo que está presente em uma arquitetura Lakehouse, mas não em um data warehouse tradicional?**

- A. Um sistema relacional de gerenciamento de dados.
- B. Um sistema que permite análises em batch e em tempo real de forma integrada.
- C. Um formato proprietário para armazenamento de dados.
- D. A utilização de snapshots para controle de versão de dados.

**✅ Resposta correta:** B
💬 *Comentário:* A arquitetura Lakehouse suporta análises em batch e em tempo real de forma integrada, o que não é encontrado em data warehouses tradicionais. Este é um dos diferenciais fundamentais da arquitetura Lakehouse.

## Questão n° 92
**Onde estão localizados os nós de driver e de trabalhador de um cluster gerenciado pelo Databricks?**

- A. No plano de dados (data plane).
- B. No Databricks Filesystem.
- C. No plano de controle (control plane).
- D. Na interface web do Databricks.

**✅ Resposta correta:** A
💬 *Comentário:* No Databricks, os nós de driver e de trabalhador são localizados no plano de dados (data plane), enquanto o plano de controle gerencia metadados e solicitações.

## Questão n° 93
**Um arquiteto de dados precisa modelar dados para cargas de trabalho de aprendizado de máquina baseadas em vídeo e também para ETL altamente auditado. Como a arquitetura Lakehouse atende às necessidades desses dois cenários?**

- A. Combina dados estruturados e não estruturados com conformidade ACID.
- B. Permite auto-escalonamento para clusters de processamento.
- C. Exige pouca modelagem de dados para atender aos requisitos.
- D. Permite governança simples ao combinar computação e armazenamento.

**✅ Resposta correta:** A
💬 *Comentário:* A arquitetura Lakehouse combina suporte a dados estruturados e não estruturados com conformidade ACID, o que é essencial para aprendizado de máquina e pipelines ETL auditáveis.

## Questão n° 94
**Quando um engenheiro de dados deve preferir usar um Job cluster em vez de um cluster de uso geral?**

- A. Para uma análise pontual que exige colaboração entre equipes.
- B. Para agendar fluxos de trabalho automatizados que devem ser executados periodicamente.
- C. Para criar relatórios ad-hoc com otimização de custos.
- D. Para investigar manualmente um erro em produção.

**✅ Resposta correta:** B
💬 *Comentário:* Job clusters são criados para fluxos de trabalho automatizados que precisam ser executados periodicamente, otimizando custos e recursos, diferentemente de clusters de uso geral.

## Questão n° 95
**Um engenheiro de dados criou uma tabela Delta em uma pipeline. Analistas de dados agora precisam de permissões SELECT nesta tabela. Qual ferramenta do Databricks pode ser usada para conceder essa permissão?**

- A. Jobs.
- B. Data Explorer.
- C. Dashboards.
- D. Repos.

**✅ Resposta correta:** B
💬 *Comentário:* O Data Explorer no Databricks permite configurar permissões como SELECT diretamente nas tabelas, facilitando o controle de acesso.

## Questão n° 96
**Dois engenheiros de dados estão colaborando em partes separadas de um único notebook de pipeline de dados. Eles estão trabalhando em branches do Git diferentes para evitar conflitos. Um engenheiro sênior sugere uma alternativa melhor para essa colaboração.**

- Qual funcionalidade do Databricks Notebooks suporta diretamente essa sugestão?
- 
- A. Coautoria em tempo real no mesmo notebook.
- B. Suporte a múltiplos idiomas dentro de um mesmo notebook.
- C. Rastreamento automático de alterações e versionamento.
- D. Criação de visualizações interativas diretamente no notebook.

**✅ Resposta correta:** A
💬 *Comentário:* A coautoria em tempo real no Databricks Notebooks permite que vários usuários colaborem simultaneamente em um mesmo notebook, reduzindo conflitos.

## Questão n° 97
**Como o recurso Repos no Databricks facilita fluxos de trabalho de CI/CD na plataforma Lakehouse?**

- A. Facilita solicitações de pull, revisões e aprovação antes de mesclar branches.
- B. Armazena o repositório Git usado como fonte única de verdade.
- C. Permite criar e disparar pipelines de automação Git diretamente.
- D. Commite ou envia alterações de código para iniciar processos CI/CD automaticamente.

**✅ Resposta correta:** D
💬 *Comentário:* O recurso Repos do Databricks permite realizar commits diretamente no código, iniciando processos de CI/CD automaticamente.

## Questão n° 98
**Como o Delta Lake é descrito corretamente em relação à sua função como camada de armazenamento?**

- A. Um formato de armazenamento aberto que oferece confiabilidade, segurança e desempenho.
- B. Um mecanismo de análise open source utilizado para grandes volumes de dados.
- C. Uma plataforma para gerenciar todo o ciclo de vida de aprendizado de máquina.
- D. Um formato proprietário de armazenamento de dados distribuídos.

**✅ Resposta correta:** A
💬 *Comentário:* O Delta Lake é descrito como um formato de armazenamento aberto que oferece confiabilidade, segurança e desempenho, sendo projetado para atender às necessidades modernas de dados.

## Questão n° 99
**Qual comando SQL permite criar uma tabela Delta com o esquema especificado, garantindo que ela será criada apenas se ainda não existir uma tabela com o mesmo nome?**

- A. CREATE OR REPLACE TABLE
- B. CREATE TABLE IF NOT EXISTS
- C. CREATE TABLE AS SELECT
- D. CREATE OR REPLACE TABLE WITH COLUMNS

**✅ Resposta correta:** B
💬 *Comentário:* O comando CREATE TABLE IF NOT EXISTS cria uma tabela Delta apenas se ela ainda não existir, garantindo que não ocorra erro se a tabela já estiver presente.

## Questão n° 100
**Qual comando SQL é utilizado para adicionar novas linhas a uma tabela Delta existente?**

- A. INSERT INTO
- B. UPDATE
- C. COPY
- D. MERGE

**✅ Resposta correta:** A
💬 *Comentário:* O comando INSERT INTO é utilizado para adicionar novas linhas a uma tabela Delta existente sem modificar os dados já presentes.

## Questão n° 101
**Qual das opções descreve corretamente a função de um plano de dados (data plane) no Databricks?**

- A. Gerencia permissões e metadados na plataforma.
- B. Hospeda nós de driver e worker em clusters gerenciados.
- C. Controla o acesso aos recursos por meio de uma interface web.
- D. Armazena logs de auditoria para compliance.

**✅ Resposta correta:** B
💬 *Comentário:* O plano de dados (data plane) hospeda os nós de driver e worker em clusters gerenciados, enquanto outras opções se referem a funcionalidades diferentes.

## Questão n° 102
**Qual é a diferença principal entre um cluster de uso geral (all-purpose cluster) e um cluster de jobs (job cluster)?**

- A. Clusters de uso geral são utilizados apenas para tarefas de produção.
- B. Clusters de jobs são temporários e focados em executar tarefas automatizadas.
- C. Clusters de uso geral oferecem maior performance em pipelines ETL.
- D. Clusters de jobs permitem a execução de múltiplas tarefas simultâneas.

**✅ Resposta correta:** B
💬 *Comentário:* Clusters de jobs são temporários e otimizados para execução de tarefas automatizadas, sendo encerrados automaticamente após o término do trabalho.

## Questão n° 103
**Um arquiteto de dados está projetando um modelo que precisa suportar tanto dados não estruturados quanto ACID compliance. Qual tecnologia atende a essas necessidades?**

- A. Apache Hadoop.
- B. Um armazém de dados tradicional.
- C. Delta Lake.
- D. Apache Hive.

**✅ Resposta correta:** C
💬 *Comentário:* O Delta Lake suporta dados não estruturados e conformidade ACID, tornando-o ideal para cenários que exigem transações confiáveis e análise de dados variados.

## Questão n° 104
**O que acontece ao usar o comando CREATE TABLE AS SELECT no Databricks?**

- A. O esquema da nova tabela é adotado do resultado da consulta SQL.
- B. A tabela será criada apenas se ela ainda não existir no sistema.
- C. Os dados existentes na tabela serão substituídos.
- D. Uma tabela temporária será criada para uso exclusivo na sessão atual.

**✅ Resposta correta:** A
💬 *Comentário:* O comando CREATE TABLE AS SELECT cria uma nova tabela baseada no resultado de uma consulta, inferindo o esquema diretamente dos dados consultados.

## Questão n° 105
**Qual método de otimização pode melhorar a performance de uma consulta em tabelas Delta Lake cujos dados estão distribuídos aleatoriamente?**

- A. Data skipping.
- B. Z-Ordering.
- C. Bin-packing.
- D. Compactação de arquivos.

**✅ Resposta correta:** B
💬 *Comentário:* O Z-Ordering organiza fisicamente os dados no disco, o que melhora o desempenho de consultas que filtram frequentemente por valores em colunas específicas.

## Questão n° 106
**Um engenheiro de dados quer criar uma tabela relacional a partir de duas tabelas existentes. A nova tabela deve estar disponível para outros engenheiros e evitar cópias físicas dos dados. Qual opção o engenheiro deve usar?**

- A. Criar uma view.
- B. Criar uma tabela temporária.
- C. Criar uma tabela Delta.
- D. Criar um banco de dados.

**✅ Resposta correta:** A
💬 *Comentário:* Views são usadas para criar uma representação relacional dos dados existentes, sem a necessidade de replicá-los fisicamente.

## Questão n° 107
**Um engenheiro de dados percebe que ao usar tabelas Parquet em sistemas externos, consultas no Databricks não retornam os novos dados. Como resolver isso?**

- A. Converter as tabelas para o formato Delta.
- B. Atualizar o cluster antes de executar as consultas.
- C. Adicionar metadados para evitar caching.
- D. Configurar refresh automático no Databricks.

**✅ Resposta correta:** A
💬 *Comentário:* Converter tabelas Parquet para o formato Delta resolve o problema de atualizações não refletidas, pois o Delta Lake gerencia metadados mais eficientemente.

## Questão n° 108
**Qual das opções representa corretamente o uso do Z-Ordering em tabelas Delta Lake?**

- A. É uma técnica para compactar os arquivos físicos.
- B. Ordena fisicamente os dados para melhorar a eficiência das consultas.
- C. Reduz o tamanho dos arquivos para melhorar a performance de escrita.
- D. Garante a exclusividade das chaves primárias em tabelas Delta.

**✅ Resposta correta:** B
💬 *Comentário:* O Z-Ordering organiza fisicamente os dados no disco para melhorar a eficiência das consultas, especialmente ao filtrar por colunas.

## Questão n° 109
**Um engenheiro de dados quer combinar horizontalmente duas tabelas utilizando uma coluna em comum como chave, retornando apenas as linhas que existem nas duas tabelas. Qual comando SQL é apropriado?**

- A. INNER JOIN
- B. LEFT JOIN
- C. OUTER JOIN
- D. UNION

**✅ Resposta correta:** A
💬 *Comentário:* O INNER JOIN retorna apenas as linhas que existem em ambas as tabelas, atendendo ao requisito da questão.

## Questão n° 110
**Um engenheiro de dados precisa transformar uma coluna JSON em múltiplas linhas, extraindo valores individuais. Qual função SQL deve ser usada?**

- A. FILTER
- B. EXPLODE
- C. FLATTEN
- D. MAP

**✅ Resposta correta:** B
💬 *Comentário:* A função SQL EXPLODE transforma elementos de uma coluna JSON em múltiplas linhas, extraindo valores individuais.

## Questão n° 111
**Um engenheiro de dados quer criar uma tabela Delta que só será atualizada com os novos dados inseridos. Qual comando SQL deve ser usado?**

- A. UPDATE
- B. INSERT INTO
- C. COPY INTO
- D. MERGE

**✅ Resposta correta:** B
💬 *Comentário:* O comando INSERT INTO adiciona apenas novos dados a uma tabela existente, sem modificar os registros já presentes.

## Questão n° 112
**Um engenheiro de dados está criando uma nova tabela Delta e deseja garantir que ela seja sobrescrita se já existir. Qual comando SQL é apropriado?**

- A. CREATE TABLE
- B. CREATE OR REPLACE TABLE
- C. CREATE TABLE IF NOT EXISTS
- D. ALTER TABLE

**✅ Resposta correta:** B
💬 *Comentário:* O comando CREATE OR REPLACE TABLE cria ou sobrescreve uma tabela Delta, garantindo que novos dados possam substituir os antigos.

## Questão n° 113
**Qual das opções melhor descreve o comportamento de um comando MERGE no Delta Lake?**

- A. Insere dados duplicados em uma tabela existente.
- B. Atualiza ou insere dados dependendo de uma condição específica.
- C. Sobrescreve os dados existentes com base na ordem dos arquivos.
- D. Remove as linhas que não satisfazem as condições da consulta.

**✅ Resposta correta:** B
💬 *Comentário:* O comando MERGE no Delta Lake atualiza ou insere dados com base em condições específicas, como comparação de chaves.

## Questão n° 114
**O que acontece quando o comando VACUUM é executado em uma tabela Delta?**

- A. Compacta os arquivos físicos da tabela.
- B. Remove versões antigas dos arquivos não referenciados.
- C. Garante conformidade com as transações ACID.
- D. Atualiza os índices da tabela.

**✅ Resposta correta:** B
💬 *Comentário:* O comando VACUUM remove arquivos antigos e não referenciados de uma tabela Delta, liberando espaço em disco.

## Questão n° 115
**Um engenheiro de dados está usando Auto Loader para processar dados incrementais de arquivos JSON. Qual parâmetro é necessário para habilitar o rastreamento do esquema automaticamente?**

- A. .option("cloudFiles.autoSchema", "true")
- B. .option("cloudFiles.schemaLocation", "/path/to/schema")
- C. .option("jsonSchema.auto", "true")
- D. .option("schemaTracking.enabled", "true")

**✅ Resposta correta:** B
💬 *Comentário:* O parâmetro .option("cloudFiles.schemaLocation") define um local persistente para rastrear a evolução do esquema, essencial no Auto Loader.

## Questão n° 116
**Qual é a vantagem do Z-Ordering sobre compactação padrão em tabelas Delta Lake?**

- A. Reduz o espaço em disco.
- B. Melhora a performance de consultas que utilizam filtros por coluna.
- C. Otimiza operações de escrita em tabelas grandes.
- D. Garante exclusividade em chaves primárias.

**✅ Resposta correta:** B
💬 *Comentário:* O Z-Ordering melhora a performance de consultas aplicando filtros, reorganizando dados fisicamente de forma otimizada.

## Questão n° 117
**Qual dos seguintes comandos SQL pode ser usado para remover duplicatas de uma tabela Delta?**

- A. SELECT DISTINCT * FROM table_name
- B. DELETE DUPLICATES FROM table_name
- C. ALTER TABLE table_name REMOVE DUPLICATES
- D. UPDATE table_name DROP DUPLICATES

**✅ Resposta correta:** A
💬 *Comentário:* O comando SELECT DISTINCT remove duplicatas ao retornar apenas valores únicos de uma tabela.

## Questão n° 118
**Um engenheiro de dados precisa identificar a localização exata de um arquivo armazenado em uma tabela Delta. Qual comando deve ser usado?**

- A. DESCRIBE FORMATTED
- B. SHOW FILES
- C. LIST FILES
- D. DESCRIBE DETAIL

**✅ Resposta correta:** D
💬 *Comentário:* O comando DESCRIBE DETAIL fornece informações detalhadas sobre a localização e outros metadados dos arquivos em uma tabela Delta.

## Questão n° 119
**Qual é o comportamento padrão do Delta Lake em relação à conformidade ACID?**

- A. Permite apenas transações de leitura e escrita sequenciais.
- B. Garante que todas as transações sejam atômicas, consistentes, isoladas e duráveis.
- C. Requer que as transações sejam aprovadas manualmente.
- D. Fornece controle de versão apenas para dados não estruturados.

**✅ Resposta correta:** B
💬 *Comentário:* O Delta Lake garante que todas as transações sejam atômicas, consistentes, isoladas e duráveis (ACID compliance).

## Questão n° 120
**Qual recurso do Databricks é usado para definir permissões detalhadas, como acesso a tabelas ou colunas específicas?**

- A. Databricks Repos
- B. Data Explorer
- C. Unity Catalog
- D. Databricks Jobs

**✅ Resposta correta:** C
💬 *Comentário:* O Unity Catalog é usado para definir permissões detalhadas, incluindo acesso a tabelas e colunas específicas.

## Questão n° 121
**Qual comando pode ser usado para reverter uma tabela Delta para uma versão anterior?**

- A. VACUUM
- B. RESTORE
- C. REVERT
- D. ROLLBACK

**✅ Resposta correta:** B
💬 *Comentário:* O comando RESTORE permite reverter uma tabela Delta a uma versão anterior, útil para recuperação de dados.

## Questão n° 122
**Ao configurar uma pipeline com Delta Live Tables, qual funcionalidade ajuda a definir dependências entre tabelas?**

- A. Utilizar o comando CREATE LIVE TABLE.
- B. Usar o MERGE INTO.
- C. Criar uma DAG (Directed Acyclic Graph).
- D. Definir chaves primárias nas tabelas Delta.

**✅ Resposta correta:** A
💬 *Comentário:* O comando CREATE LIVE TABLE no Delta Live Tables ajuda a definir dependências entre tabelas automaticamente.

## Questão n° 123
**Um engenheiro de dados precisa combinar duas tabelas Delta usando uma coluna-chave, mas deseja incluir todas as linhas, independentemente de corresponderem ou não na outra tabela. Qual comando SQL deve ser usado?**

- A. LEFT JOIN
- B. INNER JOIN
- C. FULL OUTER JOIN
- D. UNION

**✅ Resposta correta:** C
💬 *Comentário:* O FULL OUTER JOIN retorna todas as linhas de ambas as tabelas, mesmo que não correspondam.

## Questão n° 124
**Ao usar Auto Loader para ingestão de dados incrementais, qual vantagem ele oferece em relação à ingestão manual?**

- A. Atualiza automaticamente as permissões do Unity Catalog.
- B. Garante performance otimizada com compactação automática.
- C. Monitora novas alterações nos dados sem necessidade de configuração manual.
- D. Reduz os custos de computação em até 50%.

**✅ Resposta correta:** C
💬 *Comentário:* O Auto Loader monitora alterações nos dados automaticamente, simplificando a ingestão incremental sem configuração manual.

## Questão n° 125
**Ao criar tabelas no Delta Live Tables, qual é o comportamento esperado ao processar dados que violam as expectativas configuradas?**

- A. Os dados são descartados silenciosamente.
- B. Os dados são adicionados a uma tabela de quarentena.
- C. A execução da pipeline falha imediatamente.
- D. Os dados são armazenados com um indicador de validação.

**✅ Resposta correta:** B
💬 *Comentário:* Dados que violam expectativas no Delta Live Tables são adicionados a uma tabela de quarentena, permitindo auditoria e ajustes.

## Questão n° 126
**Um engenheiro de dados quer criar uma tabela gerenciada no Databricks. Qual comando é apropriado?**

- A. CREATE TABLE table_name USING DELTA LOCATION '/path/to/data'
- B. CREATE MANAGED TABLE table_name (id STRING, value INT)
- C. CREATE TABLE table_name (id STRING, value INT)
- D. CREATE TABLE table_name LOCATION '/path/to/data'

**✅ Resposta correta:** C
💬 *Comentário:* O comando CREATE TABLE cria uma tabela gerenciada, permitindo que o Databricks gerencie automaticamente os metadados e o armazenamento.

## Questão n° 127
**Qual comando SQL pode ser usado para criar uma visualização temporária de dados em um Spark DataFrame?**

- A. CREATE TEMP VIEW view_name AS SELECT ...
- B. CREATE VIEW view_name AS SELECT ...
- C. CREATE OR REPLACE TEMP VIEW view_name AS SELECT ...
- D. CREATE OR REPLACE VIEW view_name AS SELECT ...

**✅ Resposta correta:** C
💬 *Comentário:* O comando CREATE OR REPLACE TEMP VIEW cria ou substitui visualizações temporárias de dados para análises rápidas.

## Questão n° 128
**Ao configurar pipelines de produção no Databricks, qual das opções representa corretamente o uso de múltiplas tarefas em um único job?**

- A. Permite que as tarefas sejam executadas em paralelo sem dependências.
- B. Exige que todas as tarefas sejam executadas sequencialmente.
- C. Suporta tarefas com dependências definidas de forma linear.
- D. Garante que todas as tarefas sejam executadas no mesmo cluster.

**✅ Resposta correta:** C
💬 *Comentário:* As tarefas em um job podem ter dependências lineares definidas, garantindo a execução na ordem correta.

## Questão n° 129
**Ao usar Delta Live Tables, qual é o modo de execução recomendado para desenvolvimento e testes?**

- A. Production Mode
- B. Development Mode
- C. Testing Mode
- D. Debugging Mode

**✅ Resposta correta:** B
💬 *Comentário:* O Development Mode no Delta Live Tables é ideal para desenvolvimento e testes, permitindo alterações iterativas.

## Questão n° 130
**Ao configurar uma política de retenção em tabelas Delta, qual comando define o tempo de retenção para versões antigas?**

- A. ALTER TABLE table_name SET RETENTION 7
- B. ALTER TABLE table_name SET TBLPROPERTIES ("delta.logRetentionDuration" = "interval")
- C. VACUUM table_name RETAIN 7 DAYS
- D. SET TABLE RETENTION 7

**✅ Resposta correta:** C
💬 *Comentário:* O comando VACUUM RETAIN define o tempo de retenção para arquivos antigos em tabelas Delta, removendo dados obsoletos.

## Questão n° 131
**Qual das opções é uma vantagem principal de usar Delta Live Tables para pipelines de dados?**

- A. Oferece um ambiente completamente sem código.
- B. Garante versionamento automático dos dados processados.
- C. Simplifica a definição de dependências entre tabelas.
- D. Fornece escalabilidade ilimitada para grandes volumes de dados.

**✅ Resposta correta:** C
💬 *Comentário:* O Delta Live Tables simplifica a definição de dependências entre tabelas, reduzindo erros manuais e melhorando a gestão.

## Questão n° 132
**Ao configurar um SQL Endpoint no Databricks, qual configuração pode melhorar a latência de consultas sequenciais?**

- A. Aumentar o tamanho do cluster associado ao endpoint.
- B. Habilitar o recurso Serverless no endpoint.
- C. Configurar o Auto Stop para minimizar custos.
- D. Aumentar o limite de tempo para inatividade do endpoint.

**✅ Resposta correta:** B
💬 *Comentário:* O recurso Serverless nos SQL Endpoints melhora a latência ao gerenciar automaticamente os recursos de execução.

## Questão n° 133
**Qual funcionalidade do Databricks permite o envio automático de alertas baseados em condições específicas de uma consulta SQL?**

- A. Notificações de pipeline.
- B. Dashboards automatizados.
- C. Regras de alerta em queries SQL.
- D. Configuração de notificações no Unity Catalog.

**✅ Resposta correta:** C
💬 *Comentário:* As regras de alerta em queries SQL enviam notificações automáticas com base em condições definidas pelo usuário.

## Questão n° 134
**Um engenheiro de dados quer garantir que um job no Databricks será reexecutado automaticamente em caso de falha. Qual configuração é apropriada?**

- A. Ativar o recurso de auto-scaling.
- B. Configurar uma política de retry no job.
- C. Garantir que o job use um cluster exclusivo.
- D. Habilitar a opção de fail-safe manualmente.

**✅ Resposta correta:** B
💬 *Comentário:* Configurar uma política de retry nos jobs garante a reexecução automática em caso de falha.

## Questão n° 135
**Qual dos comandos é usado para conceder permissões completas sobre uma tabela no Unity Catalog?**

- A. GRANT SELECT ON TABLE table_name TO user@domain.com
- B. GRANT ALL PRIVILEGES ON TABLE table_name TO user@domain.com
- C. GRANT CREATE ON TABLE table_name TO user@domain.com
- D. GRANT SELECT, INSERT ON TABLE table_name TO user@domain.com

**✅ Resposta correta:** B
💬 *Comentário:* O comando GRANT ALL PRIVILEGES concede todas as permissões para uma tabela no Unity Catalog, atendendo às necessidades de gerenciamento de acessos.
