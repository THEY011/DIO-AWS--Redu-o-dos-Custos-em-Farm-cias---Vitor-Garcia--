# Manual Prático para Configuração do AWS EC2

## Introdução
O Amazon Elastic Compute Cloud (EC2) oferece capacidade de computação escalável na nuvem, permitindo criar e gerenciar servidores virtuais de forma simples e eficiente. Aqui está um passo a passo para configurar suas instâncias EC2.

## Passos para Configurar sua Instância EC2

1. **Login no Console AWS**  
   - Acesse sua conta na AWS e vá para o [Console de Gerenciamento da AWS](https://aws.amazon.com/console/).

2. **Navegar até o Serviço EC2**  
   - Na barra de busca do console, digite “EC2” e selecione o serviço.

3. **Iniciar a Criação de uma Instância**  
   - Clique em “Launch Instance” para começar a configuração de uma nova máquina virtual.

4. **Escolher a Amazon Machine Image (AMI)**  
   - Selecione uma AMI que melhor atenda às necessidades do seu projeto, seja Linux, Windows ou outras distribuições.

5. **Selecionar o Tipo de Instância**  
   - Escolha o tipo de instância com base no uso esperado (exemplo: t2.micro é elegível para o nível gratuito).

6. **Configurar Detalhes da Instância**  
   - Ajuste configurações como número de instâncias, redes, sub-redes e roles IAM, se necessário.

7. **Configurar Armazenamento**  
   - Defina o volume de armazenamento EBS, tipo e tamanho conforme a demanda do seu projeto.

8. **Configurar Grupo de Segurança (Firewall)**  
   - Adicione regras para liberar portas essenciais, como SSH (porta 22) para Linux, RDP para Windows, HTTP/HTTPS para servidores web, etc.

9. **Revisar e Iniciar a Instância**  
   - Faça uma última revisão de todas as configurações e clique em “Launch”. Selecione ou crie um par de chaves para acesso seguro.

10. **Acessar e Gerenciar sua Instância**  
    - Use SSH (para Linux) ou RDP (para Windows) para conectar-se à instância usando a chave privada correspondente. Gerencie sua instância pelo console ou via AWS CLI para operações avançadas.

## Considerações Finais  
Sua instância EC2 está pronta para uso! Lembre-se de monitorar desempenho e custos regularmente para manter a eficiência da sua infraestrutura na nuvem.
