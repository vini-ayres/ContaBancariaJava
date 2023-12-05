# Projeto Conta Bancária em Java 🏦

Este é um simples projeto em Java denominado `ContaTerminal` que simula a criação de uma conta bancária. O código utiliza a classe `Scanner` para interagir com o usuário, coletando informações essenciais para a criação da conta. Os dados solicitados incluem o número da agência, o número da conta, o nome do titular e o saldo inicial.

## Funcionalidades

1. **Número da Agência:** Solicita ao usuário o número da agência da conta.
2. **Número da Conta:** Solicita ao usuário o número da conta.
3. **Nome do Titular:** Solicita ao usuário o nome do titular da conta.
4. **Saldo Inicial:** Solicita ao usuário o saldo inicial da conta.

O código utiliza a classe `Locale` para garantir a correta interpretação dos números decimais, independentemente da configuração regional do usuário.

## Execução do Programa

Ao executar o programa, o usuário será guiado a fornecer as informações necessárias. Após a entrada dos dados, o programa exibe uma mensagem de boas-vindas contendo os detalhes da conta recém-criada.

```java
// Exemplo de saída
Olá [Nome], obrigado por criar uma conta em nosso banco. Sua agência é [Agência], conta [Número], e seu saldo de [Saldo] já está disponível para saque.
```

## Pré-requisitos do Projeto Conta Bancária em Java

Antes de executar o projeto `ContaTerminal` em Java, certifique-se de ter os seguintes pré-requisitos configurados em seu ambiente de desenvolvimento:

1. **JDK (Java Development Kit):** Certifique-se de ter o JDK instalado em sua máquina. Você pode baixar o JDK mais recente no [site oficial da Oracle](https://www.oracle.com/java/technologies/javase-downloads.html) ou utilizar uma distribuição como o OpenJDK.

2. **Configuração das Variáveis de Ambiente do Java:** Após a instalação do JDK, configure as variáveis de ambiente `JAVA_HOME` e adicione o caminho do executável `bin` à variável `PATH`. Isso permite que o sistema encontre os comandos Java.

3. **IDE (Ambiente de Desenvolvimento Integrado):** Embora você possa compilar e executar o código Java por meio da linha de comando, é altamente recomendável utilizar uma IDE para facilitar o desenvolvimento. Algumas opções populares incluem Eclipse, IntelliJ IDEA ou NetBeans.

4. **Git (Opcional):** Se você optar por clonar o repositório usando o Git, certifique-se de tê-lo instalado. Você pode baixar o Git em [git-scm.com](https://git-scm.com/).

## Como Executar o Projeto

Siga as etapas abaixo para executar o projeto `ContaTerminal`:

1. **Clone o Repositório (Opcional):** Se você não baixou o projeto manualmente, pode clonar o repositório usando o seguinte comando:

    ```bash
    git clone https://github.com/vini-ayres/ContaBancariaJava.git
    ```

2. **Navegue até o Diretório do Projeto:**

    ```bash
    cd ContaBancariaJava
    ```

3. **Compile o Código:**

    ```bash
    javac ContaTerminal.java
    ```

4. **Execute o Programa:**

    ```bash
    java ContaTerminal
    ```

5. **Siga as Instruções:** O programa solicitará informações sobre a conta bancária. Insira os dados solicitados e aguarde a mensagem de boas-vindas.

Ao seguir esses passos, você deve conseguir executar o projeto `ContaTerminal` em Java em seu ambiente de desenvolvimento. Certifique-se de ter todos os pré-requisitos configurados corretamente para evitar problemas durante a execução. 🚀
