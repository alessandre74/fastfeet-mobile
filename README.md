### Desafio final Fastfeet

É necessário instalar o node.js, yarn, expo, docker e baixar o container do postgres e redis.

**Mobile**

````
clonar o projeto e executar os comandos abaixo

ativar o docker
docker start fastfeet
docker start redisfasfeet
cd mobile 
yarn
yarn start
com o expo aberto podemos clicar no botao ao lado esquerdo Run on IOS simulator com o simulador 
aberto só autorizar o pedido de instalação do aplicativo. Podemos também rodar direto no device 
baixando o aplicativo expo pela Appstore e ativando pelo qrcode através da câmera do próprio device,
vai pedir autorização é só aceitar. Pelo device não podemos esquecer de trocar a url no backend pelo 
IP que aparece logo acima do qrcode, a url do model de file também.

OBS: Mobile só testado no IOS, foi desenvolvido todo pelo react native cli, porém 
tive muitos problemas para testar a câmera e para poder entregar o desafio completo, 
por isso criei um novo projeto expo e transferi todo o projeto já feito porém com algumas 
adaptações para funcionar.

````
