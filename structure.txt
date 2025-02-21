rosenbaum_whatsapp_ai/
│── main.py                   # Arquivo principal do Streamlit
│── requirements.txt          # Dependências do projeto
│── README.md                 # Documentação do projeto
│── .gitignore                # Ignorar arquivos sensíveis no Git
│── secrets.toml              # Configurações sensíveis (NÃO subir para o Git!)
│
├── config/                   # Configurações do projeto
│   ├── settings.py           # Configurações gerais (ex.: URLs, chaves de API)
│
├── models/                   # Modelos de IA e funções de ML
│   ├── train.py              # Código para treinar o modelo no BigQuery ML
│   ├── predict.py            # Código para fazer previsões com o modelo treinado
│
├── pages/                    # Módulos de páginas do Streamlit
│   ├── 1_classificacao.py    # Página para classificar mensagens e treinar IA
│   ├── 2_envio_mensagens.py  # Página para aprovar e enviar mensagens
│   ├── 3_monitoramento.py    # Painel de métricas e monitoramento (ex-dashboard)
│
├── services/                 # Integrações e serviços externos
│   ├── bigquery.py           # Funções para leitura/escrita no BigQuery
│   ├── timelines.py          # Integração com Timelines AI para envio de mensagens
│
├── utils/                    # Funções auxiliares
│   ├── auth.py               # Gestão de usuários e autenticação
│   ├── helpers.py            # Funções genéricas de suporte
│   ├── preprocess.py         # Pré-processamento de mensagens
│
├── assets/                   # Recursos estáticos
│   ├── css/                  # Estilos personalizados para Streamlit
│   ├── images/               # Logos e imagens utilizadas
