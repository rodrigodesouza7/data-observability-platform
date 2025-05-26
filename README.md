📘 Data Observability Platform

Plataforma modular e escalável para monitoramento da qualidade, latência e anomalias em fluxos de dados empresariais simulados.

# 🧪 Monitoramento de Qualidade de Dados e Detecção de Anomalias

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)]()


Projeto 100% executado online com ferramentas gratuitas. Ideal para aplicar práticas de Engenharia de Dados, Arquitetura de Software e Ciência de Dados com foco em observabilidade.
🎯 Objetivo Geral
Desenvolver um pipeline automatizado que realiza:

Simulação de dados realistas (vendas, clientes, transações)
Validação de integridade e formatos
Detecção de anomalias estatísticas (Z-score e IQR)
Geração de relatórios e gráficos analíticos
Envio de alertas automáticos via e-mail
🧱 Estrutura Modular
📦 data-observability-platform/
├── notebooks/
│   ├── validador.ipynb               # Validação estrutural e semântica
│   ├── relatorio_qualidade_dados.ipynb # Análise e visualização de erros
│   ├── detector_anomalias.ipynb     # Outliers via Z-Score e IQR
│   └── alertas_automaticos.ipynb    # Gatilho de alerta via SMTP
├── data/
│   ├── dados_simulados_com_anomalias.csv
│   ├── erros_detectados.csv
│   └── anomalias_detectadas.csv
├── src/
│   ├── validador.py
│   ├── detector_anomalias.py
│   └── alerta.py
├── .gitignore
├── README.md
└── requirements.txt
🧠 Disciplinas Aplicadas
Arquitetura de Sistemas: separação por camadas e módulos
Arquitetura de Software: clean code, reusabilidade, SRP
Engenharia de Dados: simulação, ingestão, validação e exportação
Desenvolvimento Python: scripts funcionais e documentados
Estatística Aplicada: uso de z-score, IQR e boxplots
Observabilidade: alertas automatizados por e-mail (SMTP + 2FA)
📦 Stack Tecnológica
Camada	Ferramentas Utilizadas
Simulação de Dados	faker, uuid, random, datetime
Transformação	pandas, numpy
Validação/Análise	re, matplotlib, seaborn, Counter
Armazenamento	Arquivos .csv via Google Colab
Orquestração	Google Colab (execução 100% remota e gratuita)
Alertas	smtplib, email.mime + SMTP Gmail com 2FA
📊 Funcionalidades
✅ Geração sintética de dados empresariais
✅ Validação de formatos, tipos e domínios
✅ Visualização da distribuição de erros
✅ Detecção estatística de anomalias
✅ Exportação de erros e outliers
✅ Envio de alertas automáticos
✅ Separação clara entre notebooks e scripts
✅ Totalmente executável em ambiente gratuito
🛠️ Requisitos
Instale as dependências com:

pip install -r requirements.txt
Ou execute direto no Google Colab sem instalação local.
⚠️ Segurança
Nunca exponha sua senha do Gmail diretamente nos notebooks.
Use senhas de app com 2FA.
Ou configure via variáveis de ambiente:
import os
senha_app = os.getenv("SENHA_GMAIL_APP")

👤 Sobre o Autor
Rodrigo de Souza Silva
**Rodrigo de Souza Silva**  
Profissional de Tecnologia da Informação com formação em Sistemas de Informação e pós-graduação em Data Science & Machine Learning. Atua no desenvolvimento de projetos práticos com Python, APIs REST, automações e análise de dados, aplicando os conhecimentos adquiridos em formação técnica e cursos especializados.

Apaixonado por dados, boas práticas de código e soluções que unem lógica, organização e utilidade real.

- [LinkedIn](https://www.linkedin.com/in/rodrigodesouzasilva)  
- [GitHub](https://github.com/rodrigodesouza7)

---

## 📜  Licença

Este projeto está licenciado sob os termos da licença [MIT](https://opensource.org/licenses/MIT).  
Você pode usar, modificar e distribuir com os devidos créditos ao autor.



