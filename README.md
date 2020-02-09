# hello-world
Repositório com projetos de Hello World

## CSharp 
### Console Application (.Net Framework)
Projeto de Exemplo (Hello World), exemplo com interpolação de string (variavel nomeLinguaguem)

```c#
    static void Main(string[] args)
    {
        string nomeLinguagem = "C#";
        Console.Write($"Hello Word {nomeLinguagem}");
        Console.ReadLine();
    }
 ```

## Javascript
### Projeto Javascript puro
Projeto de Exemplo (Hello World), exemplo com Template Strings (Variavel nomeLinguagem)

```js
    var nomeLinguagem = 'Javascript';
            
    // Utilzando alert
    alert(`Hello World ${nomeLinguagem} `);
    
    // Utlizando Console.log
    console.log(`Hello World ${nomeLinguagem}`);
    
    // Escrevendo no DOM
    var divElement = document.querySelector('div');
    var textElement = document.createTextNode(`Hello World ${nomeLinguagem}`);
    
    divElement.appendChild(textElement); 
   ```

## VB.NET
### Console Application (.Net Framework)
Projeto de Exemplo (Hello World), exemplo com interpolação de string (variavel nomeLinguaguem)

```vb
    Sub Main()
        Dim nomeLinguagem As String = "VB.NET"
        Console.WriteLine($"Hello World {nomeLinguagem}")
        Console.ReadLine()
    End Sub
```



## Delphi
### Console Application (Delphi)
Projeto de Exemplo (Hello World), exemplo com showMessage

```delphi
		
	uses
	  System.SysUtils,
	  Vcl.Dialogs;

	begin
	  ShowMessage('Hello World');
	end.

```

## ReactJS
Projeto de Exemplo (Hello World), exemplo com React.Render

Scripts para adicionar na página HTML
```
	https://unpkg.com/react/umd/react.development.js
	https://unpkg.com/react-dom/umd/react-dom.development.js
``` 

HTML
```html
	<div id="root"></div>
```

JAVASCRIPT
```js
	ReactDOM.render(
	  <h1>Hello, world!</h1>,
	  document.getElementById('root')
	);
```


