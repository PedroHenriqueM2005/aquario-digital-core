

<img width="1376" height="768" alt="Gemini_Generated_Image_c5xew9c5xew9c5xe" src="https://github.com/user-attachments/assets/2fa97559-8829-496d-8686-5b8200c46dac" />

## aquario-digital-core

O **aquário digital core** é o módulo central e motor backend responsável pelo gerenciamento, monitoramento e processamento de dados para o sistema de aquários inteligentes. O projeto tem como objetivo automatizar o controle de ecossistemas aquáticos através de IoT e análise de dados em tempo real.

---

##  Funcionalidades Principais

-  **Monitoramento de Parâmetros:** Leitura em tempo real de temperatura, pH, nível de água e qualidade.
-  **Automação de Dispositivos:** Controle automatizado de iluminação, alimentadores e filtros.
-  **Sistema de Alertas:** Notificações instantâneas para variações anômalas dos parâmetros do aquário.
-  **Histórico e Relatórios:** Armazenamento e análise de métricas para acompanhamento da saúde da fauna/flora.
-  **API RESTful / WebSockets:** Comunicação eficiente entre hardware (microcontroladores) e interfaces de usuário.

---

##  tecnologias usadas

- **Linguagem Principal:** Node.js / TypeScript *(ou Python/Java, ajuste conforme necessário)*
- **Framework:** Express / NestJS
- **Banco de Dados:** PostgreSQL / MongoDB
- **Comunicação IoT:** MQTT / WebSockets
- **Containerização:** Docker & Docker Compose

---

## como executar

### Pré-requisitos

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)

### passos para instalação

##Clone o repositório:
   ```bash
   git clone [https://github.com/PedroHenriqueM2005/aquario-digital-core.git](https://github.com/PedroHenriqueM2005/aquario-digital-core.git)
   cd aquario-digital-core


   ## verificar estar na main
git checkout main

# Crie e envie a branch de homologação (stage)
git checkout -b stage
git push origin stage

# Crie e envie a branch de desenvolvimento (develop)
git checkout -b develop
git push origin develop

 ##Crie a branch da nova funcionalidade
git checkout -b feature/controle-qualidade

# Para compilar o arquivo Java
javac ControleQualidadeAgua.java

# Para executar o programa (caso tenha uma classe principal/main)
java ControleQualidadeAgua

git add .
git commit -m "feat: implementa modulo de monitoramento da qualidade da agua"
git push origin feature/controle-qualidade
