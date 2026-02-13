# ⚙️ CotacoesWorker - Microserviço de Resiliência

![.NET](https://img.shields.io/badge/.NET-8.0-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)

Este projeto é um Worker Service .NET que consome cotações de uma fila Kafka, salva no banco de dados e implementa estratégias de retry, idempotência, circuit breaker, fallback e observabilidade. O serviço de operações deve funcionar mesmo se o serviço de cotações estiver indisponível.


## 🚀 Funcionalidades Técnicas
- **Consumo Kafka:** Integração com tópicos de cotações.
- **Resiliência:** Implementação de estratégias de Retry e Idempotência.
- **Stability Patterns:** Uso de Circuit Breaker e Fallback para proteção do sistema.
- **Observabilidade:** Logs estruturados e métricas de consumo.

## 🏗️ Estrutura
- **Program.cs:** Inicialização e configuração do Host.
- **Worker.cs:** Lógica principal de processamento e persistência no banco.

## ⚙️ Como Rodar

1. **Clonar o Repositório:**
   ```bash
   git clone [https://github.com/GabrieldosSantos8/TesteBancario_MicroServico.git](https://github.com/GabrieldosSantos8/TesteBancario_MicroServico.git)
