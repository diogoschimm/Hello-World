# hello-world
Repositório com projetos de Hello World

## CSharp 
### Console Application (.Net Framework)
Projeto de Exemplo (Hello World), exemplo com interpolação de string (variavel nomeLinguaguem)

    static void Main(string[] args)
    {
        string nomeLinguagem = "C#";
        Console.Write($"Hello Word {nomeLinguagem}");
        Console.ReadLine();
    }

## Javascript
### Projeto Javascript puro
Projeto de Exemplo (Hello World), exemplo com Template Strings (Variavel nomeLinguagem)

    var nomeLinguagem = 'Javascript';
            
    // Utilzando alert
    alert(`Hello World ${nomeLinguagem} `);
    
    // Utlizando Console.log
    console.log(`Hello World ${nomeLinguagem}`);
    
    // Escrevendo no DOM
    var divElement = document.querySelector('div');
    var textElement = document.createTextNode(`Hello World ${nomeLinguagem}`);
    
    divElement.appendChild(textElement); 

## VB.NET
### Console Application (.Net Framework)
Projeto de Exemplo (Hello World), exemplo com interpolação de string (variavel nomeLinguaguem)

    Sub Main()
        Dim nomeLinguagem As String = "VB.NET"
        Console.WriteLine($"Hello World {nomeLinguagem}")
        Console.ReadLine()
    End Sub


