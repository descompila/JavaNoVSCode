# ☕ Configurando o VSCode para Desenvolvimento em Java

Este guia mostra como configurar o Visual Studio Code (VSCode) para programar em Java utilizando o plugin [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack).

---

## ✅ Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado:

- [Java JDK (Java Development Kit) 17 ou superior](https://adoptium.net/)
- [Visual Studio Code](https://code.visualstudio.com/)

---

## 📦 Passo 1: Instalar o Java Extension Pack

1. Abra o **VSCode**.
2. Vá até a aba de **Extensões** (`Ctrl+Shift+X`).
3. Pesquise por: `Java Extension Pack`
4. Clique em **Instalar** no pacote da Microsoft:
   > 📦 vscjava.vscode-java-pack  
5. Esse pacote inclui:
   - Language Support for Java(TM) by Red Hat
   - Debugger for Java
   - Java Test Runner
   - Maven for Java
   - Java Dependency Viewer
   - Project Manager for Java

---

## ⚙️ Passo 2: Verificar a instalação do JDK

1. No terminal do VSCode (`Ctrl+Shift+'`), digite:
   ```bash
   java -version

Se o comando não for reconhecido, adicione o caminho do JDK à variável PATH do sistema.

Verifique também se o VSCode reconheceu o JDK:

Pressione `Ctrl+Shift+P` e digite: `Java: Configure Java Runtime`

Confirme se um JDK está selecionado. Caso contrário, adicione o caminho manualmente.

## 📁 Passo 3: Criar um projeto Java
Usando o Project Manager:
1. Pressione `Ctrl+Shift+P` e escolha: `Java: Create Java Project`
2. Escolha a build tool:
    - No Build Tools, Maven, ou Gradle
3. Escolha um local e dê um nome ao projeto.
4. O VSCode irá gerar a estrutura básica do projeto.

## 🛠️ Passo 4: Escrevendo seu primeiro código Java
1. No projeto criado, vá até `src` > `App.java` (ou crie um novo arquivo).

2. Escreva seu código:

```java
public class App {
    public static void main(String[] args) {
        System.out.println("Olá, Java no VSCode!");
    }
}
````
3. Clique com o botão direito no editor e selecione `Run Java`, ou clique no botão de ▶️ na parte superior.

## 🐞 Passo 5: Depuração (Debug)
1. Coloque um breakpoint clicando à esquerda da linha desejada.
2. Clique em ▶️ Run and Debug na parte superior ou use F5.
3. Explore as ferramentas de depuração do VSCode: variáveis, stack trace, etc.

## ✅ Pronto!
Agora você está com o VSCode configurado para desenvolvimento em Java. 🚀

## 🧩 Extra 

### Como remover os nomes dos parâmetros ao chamar métodos (Inlay Hints)? [Clique aqui](remover-inlay-hints.md)

> Notei que algumas pessoas gostam e outras odeiam o Inlay Hints, então resolvi mostrar como habilitar e desabilitar essa funcionalidade.

![image](https://github.com/user-attachments/assets/f2125960-76ef-4d27-9dd6-a49b6352090e)

Veja a [mais clicando aqui](remover-inlay-hints.md)




