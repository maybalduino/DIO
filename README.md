# Criando Máquinas Virtuais no Azure

Este repositório tem como objetivo, documentar o processo de criação e configuração de uma máquina virtual na plataforma Microsoft Azure.

## 📚Documentação
[Microsoft Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)

## Criando a Máquina virtual
### Acessando a plataforma
💡A Microsoft disponibiliza para estudantes que possuam e-mail acadêmico crédito para praticar alguns serviços disponíveis, respeitando o valor do seu crédito.

💡Lembre de encerrar qualquer serviço ativado antes do seu período expirar, caso tenha cadastrado seu cartão de débito de forma não temporária no sistema, para evitar cobranças no futuro.

- Na página principal, busque em Serviços pela opção **Máquinas Virtuais**. Em seguida, escolha a opção de máquina gratuita.

### Entendendo a configuração da máquina
- Em Detalhes da Instância, além do nome da sua máquina, você precisa determinar a **Região** dela.  Se a zona que eu escolher colocar meu servidor, estiver muito longe do meu negócio pode haver problemas de instabilidade. O ideal é observar a melhor zona para a minha região, e se possível, espalhar máquinas por regiões diversificadas afim de evitar problemas de latência, influenciando a SLA.
- Logo após vem a opção de escolher de qual será o sistema operacional(**Imagem**) da sua máquina e sua capacidade de armazenamento(**Tamanho**).

### Definindo administrador e restrições de rede 
- A próxima etapa é o cadastro do login e senha do administrador.
- Nas regras de rede, é definida quais portas da máquina podem ser acessadas via internet pública. Por padrão, a plataforma restringe o acesso à fontes da mesma rede virtual e tráfego da Azure. No caso de teste, iremos seguir com a porta já selecionada.

### Revisão, aceite dos Termos e criação
- Na página seguinte, temos todos os detalhes e configuração da máquina criada, os termos de uso da plataforma e o valor que será gasto. Concordando, vamos criar a máquina e aguardar a sua implementação.



*Esse documento faz parte do projeto da Formação em Nuvem Azure da DIO*
