#### ROBÔ Welcome-Kit

- [x] ClosedXML

O componente ClosedXML pode ser encontrado no Nuget e funciona tanto em aplicações .NET Framework, quanto .NET Core.

A idéia é ter informações inputadas pelo pelo .NET Core e ter o arquivos armazenado em memoria. Primeiro é preciso ler uma planilha dentro do código em C#. Então apresento uma solução console que irá ler todas as linhas e colunas de nossa planilha.

#### Para criar a aplicação, rode os seguintes comandos:

```
dotnet new console -o LerPlanilhaExcel
cd LerPlanilhaExcel
dotnet add package ClosedXML 
```
Os comandos acima criam o projeto e depois, dentro da pasta, adicionam o pacote do componente ClosedXML.

Se você está no Visual Studio, pode ir no Nuget Package Manager e procurar por ClosedXML.

#### Construindo classes e metodos para ler a Planilha em C#
```
using System;
using System.Linq;
using ClosedXML.Excel;

namespace LerPlanilhaExcel
{
    class Program
    {
        static void Main(string[] args)
        {
           var xls = new XLWorkbook(@"C:\Temp\ExemploExcel.xlsx");
           var planilha = xls.Worksheets.First(w => w.Name == "Planilha1");
            var totalLinhas = planilha.Rows().Count();
            // primeira linha é o cabecalho
            for (int l = 2; l <= totalLinhas; l++)
            {
                var codigo = int.Parse(planilha.Cell($"A{l}").Value.ToString());
                var descricao  = planilha.Cell($"B{l}").Value.ToString();
                var preco = decimal.Parse(planilha.Cell($"C{l}").Value.ToString());
                Console.WriteLine($"{codigo} - {descricao} - {preco}");
            }
        }
    }
}
```

<a href="https://www.linkedin.com/in/mateus-macedo-937a32163/">
 <img style="border-radius:50%" width="100px; "src="https://avatars.githubusercontent.com/u/63172367?s=460&u=11fd26ea8a7f5663d7707d7ef254e4f8bfca1b05&v=4"/>
 <p>Mateus Macedo</p>
</a>
