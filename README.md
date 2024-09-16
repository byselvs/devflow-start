# Devflow Start

### Introdução

Olá DevFlower, neste capitulo você irá incluir uma linha de "log" no output da aplicação e poderá visualizar esta saída ao executar a aplicação pela linha de comando.

### Pré-requisitos

- Fazer o clone do projeto base configurado com spring-boot e java 21.

### Execução

- localize o arquivo "StartApplication.java" e adicione a seguinte linha no método "main":

   ```java
      System.out.println("Hello World Command Line");
   ```

- execute no terminal o seguinte comando:

   ```shell
      mvn spring-boot:run
   ```

- visualize o output no terminal, com a frase: "Hello World Command Line", conforme exemplo abaixo.
   ```log
   2024-09-16T03:19:50.508Z  INFO 28814 --- [start] [           main] c.b.devflow.start.StartApplication       : Starting StartApplication using Java 21.0.4 with PID 28814 (/workspaces/devflow-start/target/classes started by codespace in /workspaces/devflow-start)
   2024-09-16T03:19:50.510Z  INFO 28814 --- [start] [           main] c.b.devflow.start.StartApplication       : No active profile set, falling back to 1 default profile: "default"
   2024-09-16T03:19:50.947Z  INFO 28814 --- [start] [           main] c.b.devflow.start.StartApplication       : Started StartApplication in 0.783 seconds (process running for 1.065)
   Hello World Command Line
   ```


