# Sistema de cadastro de jogos

> **Status do projeto**: *Em desenvolvimento (0.1%)*<br><br>
Para rodar o projeto em sua máquina, por favor digite:
```
node app.js
```
## IMPORTANTE
> Esse projeto é para fins de aprendizagem no ambiente GitHub, não sendo necessariamente um projeto válido.

### Dicas sobre a linguagem MarkDown:
Para marcar um conteúdo como *Blockquote*, basta inserir o sinal \> no início da linha.<br>
Serve inclusive com conteúdo vazio (o que adiciona uma linha em branco no *Blockquote*<br>
As dicas abaixo serão descritas como *Blockquote*:<br>
> Quebra de linha: \<br\> <br>
>
> *Itálico*: \*palavra\*<br>
>
> Negrito: \*\*palavra\*\*<br>
>
> ***Itálico e Negrito***: \*\*\*palavra\*\*\*<br><br>

O *Blockquote* também pode ser **aninhado** em subitens, bastando para isso utilizar \> e \>\><br>
> Texto principal<br>
>> Texto secundário<br><br>
Tópicos numerados
1. Primeiro tópico<br>
  1.1 Primeiro subtópico<br>
  1.2 Segundo subtópico<br>
2. Segundo tópico<br>
3. Terceiro tópico<br><br>

> Site (da Alura) que contém um manual resumido sobre **Git/GitHub**:
  - [Manual do Git e GitHub](https://guilhermeonrails.github.io/manual-do-git-e-github/)

> Site que contém diversas dicas sobre o **git log**:
  - [git lot cheatsheet](https://devhints.io/git-log)
Principais comandos do Git Bach:<br>
> Para clonar o projeto:
- *git clone url_do_projeto*

> Para ***enviar*** arquivos ao GitHub:
-  Apenas 1 arquivo:
  - *git push app.js -m "mensagem explicativa"*
- Todos os arquivos:
  - *git push . -m "mensagem explicativa"*
- Forçar um *push*:
  - *git push --force origin main*

> Para fazer o commit (local)<br>
- Commit de apenas 1 arquivo:
  - *git commit app.js -m "texto explicativo do commit"*
- Commit de todo o projeto:
  - *git commit . -m "texto explicativo do commit"*

> Para visualizar todos os commits<br>
- Numa linha (cada):
  - *git log --oneline*
- Detalhado:
  - *git log -p*
- Formatado:
  - *git log --pretty="format:%h %s"*

> Para restaurar determinada versão dos códigos:<br>
- Restaurar apenas 1 arquivo ***(xxxxxxx é o hash do código)***:
  - *git restore*<br>
- Restaurar todo o projeto ***(xxxxxxx é o hash do código)***:
  - *git restore . xxxxxxx*<br>
