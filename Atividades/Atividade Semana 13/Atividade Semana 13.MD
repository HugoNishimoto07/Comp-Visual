> Nome: Fernando Bastos Arbache
> RA: 31806211

> Nome: Hugo Shiniti Nishimoto
> RA: 32048416

> Nome: Lucas Souza Silva
> RA: 32058179

> Nome: Vinicius Rodrigues Figueira de Faria
> RA: 32013639


# Atividade Semana 13 – Computação Visual

Resolução:

## Definição

Toon shading é uma técnica de renderização não-fotorrealista que busca a aparência do mundo "físico", isto é, pegar elementos "imaginários" e representa-los de forma que se consiga visualizar uma conexão com objetos/elementos do mundo físico. Basicamente, a técnica do toon shading cria cores planas em cima da cor base com a finalidade de dar uma aparência 2D à uma figura 3D.

##Viga fez
Toon Shading é um estilo de renderização nao fotorrealista criado para emular uma superfície 2D em um objeto 3D, é caracterizado por contornos pretos e cores sólidas, após a renderização, o objeto renderizado ganha uma característica que lembra desenhos animados, essa técnica comecou a ser utilizada no final do século 20 em alguns filmes animados, mas foi a partir dos anos 2000 que esse estilo comecou a ser mais adotado, principalmente na televisão e em jogos eletrônicos, Zelda: The Wind Waker, a saga Borderlands,  Okami e o mais recente, Hi-Fi Rush, são alguns jogos que utilizam essa técnica de renderização.
O cel shading funciona a partir da criação de um modelo 3D de algum objeto, a partir disso é necessário criar um esquema de cores nesse modelo, colocando uma cor sólida e tirando qualquer gradiente de cor no modelo, após isso é aplicado um sombreamento plano no objeto, através do calculo da luz e aplicação dessas sombras nas áreas que não a recebem diretamente, essas sombras são aplicadas como uma cor sólida no modelo e não como um gradiente suave, a partir disso é necessário detectar os contornos do modelo e aplicar um preto nítido nessas bordas e entao renderizar o modelo.
	A principal semelhança entre o cel-shading, Gouraud e Phong é são técnicas de sombreamento utilizadas em objetos 3D e calculam a luz na superfície do objeto, mas enquanto o cel-shading é mais simplista e busca o estilo não realista, criando um visual animado, o Gouraud e Phong criam uma aparência realista na superfície 3D, o Phong sendo mais preciso que o Gouraud, por calcular a iluminação em cada ponto da superfície do objeto, enquanto o Gouraud calcula apenas nos vértices do objeto, no cel shading o cálculo da iluminação é pela direção da fonte de luz, criando as sombras onde a luz não consegue alcançar e essa sombra sendo uma cor sólida.


## Exemplo de Toon Shading

<img width="874" alt="image" src="https://github.com/HugoNishimoto07/Comp-Visual/assets/89364149/f2527651-d5c3-49de-8fff-396da425da78">

![image](https://github.com/HugoNishimoto07/Comp-Visual/assets/64180986/9ddabc0f-1b56-46e1-884e-e604d0c0150b)

![image](https://github.com/HugoNishimoto07/Comp-Visual/assets/64180986/dc28e97e-c342-4dc0-8433-e0a830277fa6)

![image](https://github.com/HugoNishimoto07/Comp-Visual/assets/64180986/047f03f3-8e6e-478d-9960-dd679334b111)

![image](https://github.com/HugoNishimoto07/Comp-Visual/assets/64180986/5e835adc-632b-4c0d-8f74-ab04c65a83cf)



## Exemplo de comparativo entre Toon Shading x Gouraud Shading x Phong Shading

![maxresdefault](https://github.com/HugoNishimoto07/Comp-Visual/assets/89364149/1cb13629-90f8-4c5d-8686-d28d431289be)

![image](https://github.com/HugoNishimoto07/Comp-Visual/assets/64180986/5425b239-1b01-4311-b549-a8deecce0a50)


A partir dessas imagens comparando as três técnicas é nítida a diferença entre elas, Cel Shading entrega um visual animado, enquanto o Gouraud e Phong Shading buscam entregar algo mais realista e, sendo o Phong o mais preciso entre os três 

>> Referências:
- https://knoow.net/ciencinformtelec/informatica/cel-shading/

- https://en.wikipedia.org/wiki/Cel_shading

- https://danielilett.com/2019-06-08-tut2-2-cel-shading/

- https://roystan.net/articles/toon-shader/

- https://www.cin.ufpe.br/~dfp/files/PG/cel-shading.pdf

- https://tecnoblog.net/responde/o-que-e-cel-shading/

- https://www.adobe.com/uk/creativecloud/animation/discover/cel-shading.html#:~:text=Cel%20shading%20animation%20is%20a,hand%2Ddrawn%2C%202D%20appearance.
