# PythonLib-OCI
Python Libraries for use in the OCI Database



## 🛠️ Bibliotecas Python para Integração com OCI

Abaixo, uma comparação das principais bibliotecas para envio e manipulação de dados na Oracle Cloud Infrastructure:

| Biblioteca | Principal Vantagem | Principal Desvantagem | Dificuldade |
| :--- | :--- | :--- | :--- |
| **OCI SDK (`oci`)** | Acesso total a TODOS os recursos da nuvem. | Verboza; exige muitas linhas para tarefas simples. | Média |
| **python-oracledb** | Dispensa instalação de Client Oracle (modo Thin). | Focada apenas em SQL/Banco de Dados. | Baixa |
| **oracle-ads** | Integração nativa com Pandas e fluxos de ML. | Biblioteca pesada (muitas dependências). | Média |
| **ocifs** | Trata o Bucket como se fosse um disco local. | Menos controle sobre metadados finos da API. | Baixa |
| **confluent-kafka** | Altíssima performance para dados em tempo real. | Requer conceitos de mensageria (tópicos/partições). | Alta |
| **SQLAlchemy** | Abstração que facilita trocar de banco no futuro. | Performance inferior ao driver puro. | Média |
| **boto3 (S3 API)** | Reutiliza código de quem já conhece AWS. | Funções avançadas da OCI ficam inacessíveis. | Baixa |
| **polars** | Processamento de Big Data extremamente rápido. | Integração com OCI ainda requer drivers extras. | Alta |
| **papermill** | Automatiza relatórios e salva resultados na nuvem. | Uso muito específico para Jupyter Notebooks. | Baixa |
| **loguru / Logging** | Monitoramento em tempo real da aplicação. | Exige configuração de handlers customizados. | Média |

