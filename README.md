# search-files-cli

Node.js CLI
Exemplo de uma CLI em Node para procurar arquivos em uma pasta.

##### Instalação
Para instalar localmente e poder usar o comando no terminal, use o comando:
`npm link`

*será criado um link entre a pasta node_modules da maquina para a node_modules no diretório do projeto.*

##### Rodando
O comando search-files vai estar disponível no terminal. Você pode usar o comando passando o nome do arquivo que deseja procurar no diretório atual:

` search-files + .extension`

*Para pesquisar qualquer arquivo que tenha a extensão desejada dentro da pasta, digitar o comando e a extensão.*

`search-files .json`
Neste exemplo, listaria todos os arquivos com a extensão .json.

##### Editando o comando
Você pode editar livremente o arquivo bin/search-files-cli para mudar o comportamento do comando sem precisar rodar o comando npm link novamente. Qualquer alteração feita nesse arquivo já irá refletir no comando search-files.