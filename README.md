# AWS-CloudFormation

🔹 Introdução
O que é AWS CloudFormation

Vantagens de usar IaC (Infraestrutura como Código)

🔹 Objetivos do Projeto
Demonstrar como criar uma Stack básica

Implementar uma Stack de Firewall simulando regras de segurança

🔹 Tecnologias Utilizadas
AWS CloudFormation

Amazon EC2

Amazon VPC

Security Groups


🔹 Estrutura dos Templates
Explicação do template stack-basica.yaml: criação de uma instância EC2 simples

Explicação do template stack-firewall.yaml: criação de Security Groups com regras de entrada e saída

🔹 Como Executar
Passo a passo para subir os templates via Console ou AWS CLI

🔹 Resultados Esperados
Instância EC2 criada com segurança configurada

Stack visível no console do CloudFormation

🔹 Capturas de Tela
Imagens da execução da Stack e dos recursos criados

🔹 Aprendizados
Como estruturar templates YAML

Como aplicar boas práticas de segurança com Security Groups

🔗 Conexão entre os Stacks
Este projeto foi dividido em três stacks complementares que, juntos, formam uma infraestrutura segura e funcional na AWS:

Stack EC2: Cria uma instância virtual na AWS que servirá como servidor principal.

Stack Apache: Instala e configura o servidor web Apache na instância EC2, permitindo o acesso via HTTP/HTTPS.

Stack Firewall: Define regras de segurança por meio de Security Groups, protegendo a instância EC2 contra acessos não autorizados. Apenas portas específicas (como 22 para SSH e 80/443 para web) são liberadas.

Em conjunto, essas stacks provisionam uma instância EC2 com Apache instalado e configurado, acessível pela internet de forma segura e controlada.
