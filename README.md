# C#
# Introdução à linguagem
A linguagem de programação C# permite o desenvolvimento de diversos tipos de aplicativos, como aplicativos móveis, com base em nuvem, financeiros, de processamento de dados e etc, sendo ela fortemente tipada e possuindo uma sintaxe orientada a objetos.

### Neste repositório irá ser abordado:

* Primeiras linhas de código com C#
* Diagnósticos de erros
* Elementos da sintaxe C#, operadores, métodos e classes

Como de costume sempre que estamos começando o aprendizado de uma linguagem, devemos imprimir a mensagem "Hello world!", para isso é necessário ter um ambiente de desenvolvimento na sua máquina, por exemplo: 

* Visual Studio - https://visualstudio.microsoft.com/pt-br/vs/
* Visual Studio Code - https://code.visualstudio.com/download

Ápos a instalação do ambiente de preferência, inserir e executar o código abaixo:

```C#
Console.WriteLine("Hello World!");
```

Na janela de saída o resultado deve ser :

>Hello World!

Se por algum motivo, retornou uma mensagem de erro, deve ser verificado a existência de caracteres inseridos de forma incorreta :

```C#
console.WriteLine("Hello World!");
```

Escrevendo a linha de código acima, a saída gerada é:

>(1,1): error CS0103: The name 'console' does not exist in the current context

Que indica a linha e coluna que o erro ocorreu *(1,1)* e também que C# diferencia maiúsculas de minúsculas, significando que o compilador considera as palavras console e *Console* diferentes.

Usando aspas simples entre a cadeia de caracteres literal, também é retornado uma mensagem de erro:

```C#
Console.WriteLine('Hello World!');
```

>(1,19): error CS1012: Too many characters in character literal

* Uma frase colocada entre aspas duplas no código, é chamada de cadeia de caracteres literal. 
* A parte *WriteLine()* é chamada de método. Para identificar um método deve ser verificado se, após ele, existe um conjunto de parênteses. O trabalho do método *WriteLine()* é gravar uma linha de dados na Janela de Saída. Para invocar um método, sempre precisará usar os parênteses após o nome do método. Os parênteses são conhecidos como o operador de invocação de método.
* A parte *Console* é chamada de classe. Os métodos residem em uma classe. Para visitar o método, é necessário saber em qual classe ele está. Uma classe é uma maneira de armazenar e organizar todos os métodos que fazem coisas semelhantes. Nesse caso, todos os métodos que operam no painel de Saída são definidos na classe *Console*.
