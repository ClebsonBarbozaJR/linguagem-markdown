# Linguagem-Markdown
Guia de linguagem Markdown tirado do curso de Git e GitHub do Curso em Vídeo. Para acessar o curso completo [clique aqui](https://www.cursoemvideo.com/curso/curso-de-git-e-github/).

## Títulos

Para adicionar um título, basta colocar # no início do texto. A quantidade de # diz o nível do título, que vai do 1 até o 6.

# Título de nível 1

## Título de nível 2

## Título de nível 3

#### Título de nível 4 e por aí vai...

## Formatações simples

### Negrito
Abrir e fechar com ** ou __
Exemplo: **Texto em negrito**

### Itálico
Abrir e fechar com * ou _
Exemplo: *Texto em Itálico*

### Texto Deletado
Abrir e fechar com ~~
Exemplo: ~~Texto deletado~~

### Listas

#### Listas numeradas
Basta digitar 1. no começo de cada linha que vai ser numerada normalmente ou após terminar uma linha, apertar Enter, que já vai ser automaticamente preenchido.

1. Teste 1
2. Teste 2
   1. Teste Sub
   1. Teste Sub
4. Teste 3

#### Listas demarcadas

São Listas sem marcação. Pode ser usado * ou - no começo.

- Teste
- Teste
   - Teste
   - Teste
- Teste

### Lista de tarefas

Basta digitar - [ ] no começo. Quando a tarefa estiver concluída, é só adicionar um x dentro do espaço dos colchetes.

- [x] Tarefa 1
- [x] Tarefa 2
- [ ] Tarefa 3
- [ ] Tarefa 4


## Adicionando imagens

Arraste a imagem que deseja ou clique no que está escrito: **''Paste, drop, or click to add files''**. O recomendado é adicionar imagens com no máximo 500 de largura, imagens muito grandes podem atrapalhar a leitura.

![Octopus Cat](https://github.com/user-attachments/assets/9b16c46c-62be-44ee-bc20-bb267fb433dd)

## Criando um link

Adicione colchetes e parênteses. O colchete é para adicionar um texto e os parênteses é para por o link.

[Acesse meu perfil no Github](https://github.com/ClebsonBarbozaJR)

## Tabelas

Primeiro, criamos os títulos das colunas usando a barra reta (exemplo: Coluna 1 | Coluna 2 | Coluna 3), e em seguida, abaixo deles, adicionamos três sinais de menos (---) no lugar dos títulos, seguindo a mesma quantidade de colunas feitas anteriormente (no exemplo fica assim: --- | --- | --- ). 
Abaixo disso, é só digitar os campos, dá um espaço e adicionar uma |.

id | Nome | Curso
--- | --- | ---
1 | Gustavo | MySQL
2 | Victor | HTML5
3 | Ana | Python 3
4 | Alana | PHP

## Formatação para códigos

Existe um tipo de formatação nas linguagem de programação feitas exclusivamente para códigos ou trechos de programas por ser monoespaçada. Para um código específico, basta abrir e fechar crase no texto.

`document.getElementById()`

Mas caso queira mostrar um trecho de um programa, basta abrir três crases no início e no fim, e digitar o código dentro dele.

```
num = int(input('Digite um número: ')
if num % 2 == 0:
    print(f'O número {num} é PAR)
else:
    print(f'O número {num} é ÍMPAR)
```

## Emojis

Para adicionar emojis, basta digitar : e a texto que representa tal emoji, tudo junto. Para ver todas as sintaxes de todos os emojis, acesse o [repositório da ikatyang](https://github.com/ikatyang/emoji-cheat-sheet). 👈 👈 

## Reply

Para fazer um Reply (responder alguém), basta colocar antes do texto, um > ou clicar na opção Quote Reply nas reticências.

> Texto que quero responder.

Minha resposta.
