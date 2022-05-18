# Gerenciamento de estado Context API

## Apresentando o problema com um contador

`vamos ver sobre gerenciamento de estado:`
- Iremos ver que ainda não conseguimos fazer com que o nosso Contador reflita no nosso Cabecalho,como podemos fazer isso? `ai que esta o problema:` Conseguimos passar o estado para qualquer componenete filho do meu componente Contador, mas não conseguimos passar para um componente que esta no mesmo nivel "um componente irmão"

 -    uma maneira de se resolver isso, `que muitas vezes nao faz sentido é` subir o estado para o componente PAI APP,`não faça isso` !!!
 -   `Vamos ver uma solução melhor usando o Context API`


