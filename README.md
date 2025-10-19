# ISI_a27484

# ETL e Análise de Dados

## Descrição do Projeto
Este projeto foi desenvolvido como **trabalho individual** no âmbito da unidade curricular **Integração de Sistemas Informáticos**, do curso de **Licenciatura em Sistemas Informáticos (Ensino Pós-Laboral)**.

O objetivo do trabalho é apoiar uma iniciativa de uma ONG dedicada à promoção da ciência junto de crianças do ensino básico. O projeto implementa um **processo ETL (Extract, Transform, Load)** para consolidar, tratar, integrar e analisar dados de cientistas e municípios, permitindo planear visitas, gerar estatísticas e comunicar com os participantes.

---

## Funcionalidades
- Importação de dados de **Google Forms/Sheets** através de uma API e ficheiros Excel locais.
- Tratamento e normalização de dados
- Exportação de dados para **JSON, XML e Excel**, com histórico de ficheiros.
- Envio automático de email
- Visualização de dados com **gráficos no KNIME** e no **Power BI**.

---

## Ferramentas Utilizadas
- **Google Forms**: recolha automática de inscrições.
- **Google Sheets**: armazenamento das respostas do formulário.
- **Google Apps Script**: transformação do Google Sheet em ficheiro Excel (.xlsx) com triggers automáticos.
- **KNIME Analytics Platform**: desenvolvimento do processo ETL completo.
- **Power BI**: análise e visualização interativa de dados.

---

## Estrutura do Projeto
project-root/
├── README.md # Este ficheiro
├── Relatorio.pdf # Relatório final do trabalho
├── KNIME.zip # Ficheiros KNIME do projeto
├── files/
│ ├── imported/
│ │ ├── APIGoogleScripts/ # Código Google Apps Script para criar XLSX a partir de Google Sheets
│ │ ├── municipios_inscritos.xlsx # Ficheiro com dados de municípios
│ │ └── Inscrição de Cientistas (Responses).xlsx # Ficheiro com dados de cientistas
│ └── exported/ # Ficheiros exportados após o ETL (JSON, XML, XLSX)
│ │ ├── PowerBI/ # Gráficos produzidos no PowerBI
│ │ ├── XML # Pasta com ficheiros XML
│ │ ├── Rejected # Pasta com ficheiros com linhas eliminadas pelos filtros
│ │ └──FinalResult.xlsx # Ficheiro excel 
