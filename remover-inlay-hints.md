# Como remover os nomes dos parâmetros ao chamar métodos no Java no VSCode (Inlay Hints)

Ao utilizar o plugin Java da RedHat no VSCode, é comum que ao chamar um método, o editor exiba o nome dos parâmetros como uma dica visual. Por exemplo:

```java
pessoaService.criarPessoa(nome: "João", idade: 30);
````
Se você quiser remover essas dicas de nomes de parâmetros (conhecidas como Inlay Hints), siga o passo a passo abaixo:

Passo a passo para desativar os nomes dos parâmetros
1. Acesse as configurações do VSCode

- Use o atalho: Ctrl + , (Windows/Linux) ou Cmd + , (macOS)

2. Pesquise por:
````
java inlay hints parameter names
````
3. Desative a opção:
````
Java › Inlay Hints: Parameter Names
````
Desmarque essa opção para que os nomes dos parâmetros deixem de ser exibidos.

# 💡 Alternativa: Editando o settings.json

Se preferir, você pode desativar diretamente pelas configurações JSON:

Pressione Ctrl + Shift + P e digite Preferences: Open Settings (JSON)

Adicione a seguinte linha no seu arquivo settings.json:

`````
"java.inlayHints.parameterNames.enabled": "none"
`````
