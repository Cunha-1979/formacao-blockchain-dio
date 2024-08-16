### Desafio aula :book: :desktop_computer:
# Criando e Utilizando a Sua Carteira de Criptomoedas

Neste desafio proposto foi dado um fork do repositório [GitHub](https://github.com/digitalinnovationone/formacao-blockchain-dio) da Dio.

O desafio propõe criarmos uma aplicação para criar uma carteira utilizando o VSC para elaborar o código, sendo necessário instalar algumas aplicações para implementar e testar o desafio proposto.

## Iniciando o desafio 

> [!IMPORTANT]
> Baixe o fork do GitHub no computador.
> 
> Baixe e instale o nodejs, após a instalação.
> 
> Os links estão nas referências.

Depois abra o VSC e dentro abra o diretório do fork que esta no computador.

Feito esta etapa abra a aba terminal no VSC e execute as seguintes linhas:

`node -v` Irá mostrar a versão do nodejs, caso não retone a informação de versão seu nodejs não foi instalado corretamente.
`npm -v` Irá mostrar a versão do npm, como no caso do comando anterior se não apresentar a informação de versão ele não foi instalado.

Após confirmado as versões do nodejs e do npm agora devemos instalar módulos necessários para o código. No terminal digite e execute o seguinte comando:

`npm install bip39 bip32@2.0.6 bitcoinjs-lib --save`

Com esta etapa concluída, ainda dentro do terminal, entre na pasta src do diretorio

`cd .\src\`

Tendo já efetuado estes passos, agora iremos executar o código e ele irá nos dar o endereço e chaves solicitadas.

No terminal digite e execute o seguinte comando:

`node .\createWallet.js`

Com os dados da wallet apresentados no terminal agora é hora de testar.

Instale o Electrum Bitcoin wallet, depois de instalado procure no computador a versão _Electrum Testnet_ e execute-o, quando questionado se deseja criar uma carteira, **selecione a opção de importar**.

Para fazer o teste na wallet para ver se tudo ocorreu de forma correta vá em um site que envie faucects de bitcoin e envie para sua walllet para confirmar utilize o site de explorador de bloco.

## Referências

### Repositório
[![GitHub](https://img.shields.io/badge/-github-000?style=for-the-badge&logo=github&logoColor=fff)](https://github.com/digitalinnovationone/formacao-blockchain-dio)


### Aplcativos necessários
Foi instalado as seguintes aplicações:

[![Node.js](https://img.shields.io/badge/-node.js-fff?style=for-the-badge&logo=node.js&logoColor=228B22)](https://nodejs.org/pt/download/prebuilt-installer) 

[![Electrum](https://img.shields.io/badge/-electrum-0000CD?style=for-the-badge&logo=electrum&logoColor=0000CD)](https://electrum.org/#download) - Carteira Bitcoin utlizada para validar e testar a criação do endereço e chaves da wallet criada pelo codigo do desafio.

### :link:Links úteis

- Explorador de bloco da testnet do Bitcoin
    
     [Blockstream](https://blockstream.info/testnet/)

- Faucets do bitcoin:
        
    [Coinfaucet](https://coinfaucet.eu/en/btc-testnet/)

    [Testnet](https://testnet.help/en/btcfaucet/testnet)



## Autores

- [@Cunha-1979](https://www.github.com/Cunha-1979) - arquivo README.md e alteração no código
- [@Cassiano](https://https://github.com/cassianobrexbit) - Criador do código, Expert da Dio.
