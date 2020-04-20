## Como se tornar um Desenvolvedor Frontend
### Aula 1

- O que é Front End
- Requerimentos para Desenvolvimento Front End
- Criando a primeira página


## O que é Front End?

O desenvolvimento WEB é feito em camadas. A camada mais próxima ao usuário é chamada de **Front End**. Tudo que o usuário visualiza e interage ao abrir um site é considerado front end. A camada mais distante do usuário é chamada de **Back End** e é responsável por controlar dados e regras de negócio do sistema. Permissões para salvar e manipular dados são feitas pelo o back end.

Este curso tem como objetivo ensinar como desenvolver na área mais próxima do usuário, que é o **Front End**. No fim dessa aula, você será capaz de abrir uma página que você criou no seu Browser.

## Requerimentos para Desenvolvimento Front End

Para começar a desenvolver seu primeiro site, você precisará dos seguintes softwares:

### 1. Browser

Browser é a ferramenta que você utiliza para acessar sites da internet. Você poderia utilizar qualquer Browser para o desenvolvimento da sua primeira página, porém eu indico um dos Browsers abaixo:

- [Google Chrome](https://www.google.com.au/chrome/)
- [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/)
- [Opera](https://www.opera.com/)
- Safari
- Microsoft Edge

*O uso de Internet Explorer não é recomendado por limitações de funcionalidade e segurança. Internet Explorer é uma ferramenta obsoleta que deveria ser descartada na utilização do dia a dia.*

### 2. Editor de código

Um bloco de notas seria o suficiente para começar a produzir seus códigos. Hoje em dia existem ferramentas que ajudam muito no desenvolvimento web e elas deveriam ser utilizadas para te ajudar a entender e produzir códigos.

A ferramenta que eu indico e uso é o [Visual Studio Code](https://code.visualstudio.com/)

## Criando a primeira página

Abra o seu VS Code (Visual Studio Code) e clique em Novo Arquivo (New File). Dentro desse arquivo digite:

```html
<html>

</html>
```

Os sinais `<html>` e `</html>` são chamados de tags. Existem diversos tipos de tags, sendo a tag `html` a principal para que o Browser entender que esse arquivo é um arquivo HTML. Todo o código que iremos criar será criado entre essas tags, assim mostrando ao browser que tudo ali dentro tem que ser tradado como código HTML. salve o arquivo como `aula01.html` em uma nova pasta. Ao salvar o arquivo com extensão `.html`, o seu VS Code mudará a cor das tags para te ajudar a visualizar o código HTML da sua página.

Edite o seu arquivo `aula01.html` e adicione as seguintes tags dentro da tag `html`:

```html
<html>
    <head>

    </head>
    <body>

    </body>
</html>
```

Nós adicionamos as tags `head` e `body` dentro da tag `<html>` e `</html>`. logo, a nossa tag `html` tem dois **filhos**, `head` e `body`. Para ajudar na visualização do que é tag pai e tag filho, nós **indentamos** o código. Indentar é o processo de adicionar espaços antes de iniciar e finalizar uma tag, para sabermos que essas tags estão dentro de uma tag pai. Como vocês podem ver, existe um espaço entre o começo do arquivo e as tags `<head>`, `</head>`, `<body>` e `</body>`. Por cause disso, sabemos que essas tags estão dentro da tag `<html>`. Para o Browser, a indentação é irrelevante, pois ele entende que as tags `head` e `body` estão dentro do `html` devido á eles estarem entre a abertura de tag `<html>` e o fechamento de tag `</html>`.


A tag `head` é aonde colocamos o cabeçalho do código HTML. O cabeçalho serve para configurar o arquivo HTML. dentro dele é adicionado outros arquivos para enriquecer nossa página, como arquivos **javascript** e **css**. Explicarei mais sobre esses arquivos mais para frente.

A tag `body` é o corpo do HTML. Tudo que você quer mostrar para o usuário estará dentro dessa tag. Então para exemplificar o que eu estou querendo dizer, faremos a seguinte modificação

```html
<html>
    <head>

    </head>
    <body>
        Olá Mundo!
    </body>
</html>
```

Nós adicionamos o texto "Olá Mundo!" dentro da tag `body`. Como vocês notaram, o texto "Olá Mundo!" não é uma tag pois não estrá entre a estruture `<>`. Vamos abrir nosso arquivo no Browser agora. Vá para a pasta que você salvou o arquivo `aula01.html`. Clique com o botão direito no arquivo `aula01.html` e selecione **Abrir com > Google Chrome** ou outro browser que você estiver utilizando.

Você acabou de criar a sua primeira página HTML. como você pode ver, o Browser está mostrando apenas o conteúdo "Olá Mundo" na página. Isso é por que o Browser entende que o resto do código são marcações HTML e não devem ser mostradas ao usuário.

Na próxima aula, ensinarei como construir mais componentes no seu arquivo HTML



