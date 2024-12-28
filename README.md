# Projeto de Análise e Visualização de Dados com Power BI - Esquema Estrela para Gestão de Ordens de Serviço 🚀

Estou muito feliz em compartilhar um projeto que finalizei hoje no Power BI! Este trabalho envolve a criação de um modelo de dados em **Esquema Estrela** para aprimorar a gestão de Ordens de Serviço. O destaque é a conexão direta com o banco de dados **MariaDB**, utilizando SQL para garantir que os dados no Power BI estejam sempre atualizados conforme as mudanças no banco.

## 💼 O que inclui o projeto?
- **ETL dos Dados**: Realizei um processo cuidadoso de ETL (Extração, Transformação e Carregamento) para garantir que todas as informações estivessem tratadas e consistentes antes de entrarem no modelo, facilitando análises mais assertivas.
  
- **Estrutura em Dimensões e Fato**:  
  - O modelo de dados foi organizado em tabelas de dimensão – **Cliente**, **Contrato**, **Setor**, **OS** – que representam diferentes perspectivas de análise.  
  - A tabela fato centraliza as métricas principais, como `Cliente-id`, `Contrato-id`, `Setor-id`, e `OS-id`, além de datas importantes como abertura, finalização, agendamento e reagendamento das OS, permitindo relacionamentos precisos com as dimensões.

## 📊 Vantagens do Esquema Estrela, ETL e Conexão Automática:
- Navegação rápida e intuitiva pelos dados.
- Insights sempre atualizados e prontos para apoiar decisões importantes.
- Melhor organização e flexibilidade para análises em diferentes contextos.

---

**Agradecimento especial a:**  
👨‍🏫 Andre Iacono, pelos conhecimentos compartilhados e suporte durante o projeto. 🤝🏻
