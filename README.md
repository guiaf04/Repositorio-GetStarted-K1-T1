
# Comandos Git

* Nesse repositório irei fazer um breve resumo dos principais comando do git e suas funcionalidades, de forma a fixar o conteúdo aprendido e facilitar revisão posterior

## Utilitários

### Status

* Utiliza o comando ```git status```
* Retorna informações sobre a situção do repositório, de modo que podemos verificar arquivos que não estão sendo rastreados pelo git, e arquivos que está na área de preparação

### Log
* Utiliza o comando ```git log```
* Retorna informações sobre o repositório, como os últimos commits feitos, o códigos deles, o conteúdo, autores, entre outros
    
## Controle básico do repositório
### Add

* Utiliza o comando ```git add```
* Adiciona um (passando o nome do arquivo) ou todos (utilizando . após o add) arquivo na área de de arquivos rastreados pelo git, de forma que ele possa identificar mudanças neles

### Push
* Utiliza o comando ```git push```
* Envia mudanças do repositório local para o repositório remoto, mas apenas se for possível sem que haja conflitos, a não ser que seja passado a flag -f junto do push, que força a alteração, com o conteúdo do repositório local se sobressaindo

### Pull
* Utiliza o comando ```git pull```
* Traz mudanças do repositório remoto para o repositório local, mas que deve ser realizado com cuidado, pois mudanças não adicionadas no repositório local serão perdidas

## Branches
* São estruturas que permitem que novas funcionalidades sejam desenvolvidas em paralelo, sem que seja nececssário realizar mudanças constantes na branch principal
* Utilizamos o comando ```git branch``` para criar branches
* Importante ressaltar que mudanças são levadas juntos ao ficar alternando entre branches

## Conflitos
* Ocorrem quando o código no repositório remoto possui um versão de um arquivo que tem um conteúdo que foi alterado pela versão do repositório local
* A maneira mais comum de resolução de conflitos se dá pelo chamado de ```merge```, onde deve-se escolher que parte de cada versão será mantida, ou se elas serão mescladas, para formar a versão final


