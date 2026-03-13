# Docker Infrastructure Stack 🐳🚀

Este repositório demonstra a orquestração de serviços essenciais para aplicações modernas, utilizando Docker Compose para criar um ambiente resiliente e isolado.

## 🛠️ Arquitetura do Projeto
- **Nginx (Web Server):** Configurado para atuar como a camada frontal de acesso.
- **MySQL (Database):** Camada de persistência de dados com isolamento de rede.
- **Docker Networks:** Segregação de tráfego para garantir que o banco de dados não seja exposto diretamente à rede externa.

## 🚀 Como subir a infraestrutura
1. Certifique-se de ter o Docker e Docker Compose instalados.
2. Clone o repositório:
   `git clone https://github.com/LeticiaAugusto-tarxz/docker-infrastructure-stack.git`
3. Execute o comando:
   `docker-compose up -d`

## 📊 Diferenciais Técnicos
- **Resiliência (Auto-healing):** Uso da diretiva `restart: always`, garantindo que o serviço reinicie automaticamente em caso de falhas críticas ou reboot do servidor host.
- **Infraestrutura como Código (IaC):** Toda a stack é versionada e replicável em segundos em qualquer ambiente Linux.
