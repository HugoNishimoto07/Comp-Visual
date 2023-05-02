> Nome: Fernando Bastos Arbache
> RA: 31806211

> Nome: Hugo Shiniti Nishimoto
> RA: 32048416

> Nome: Lucas Souza Silva
> RA: 32058179

> Nome: Vinicius Rodrigues Figueira de Faria
> RA: 32013639


# Atividade Semana 11 – Computação Visual

Resolução:

## API gráfica 1: OpenGL

> Pipeline OpenGL

![Imagem do WhatsApp de 2023-04-25 à(s) 18 09 47](https://user-images.githubusercontent.com/89364149/234404728-25480f61-9b3c-487d-b80c-878dfa0726e7.jpg)

- Vertex Specification

O Vertex Specification remete a fase inicial, onde os vértices são postos em buffers da GPU

- Vertex Shader

Nessa etapa, o vértices que foram direcionados para a GPU, são divididos em vértices de entrada e saída, e tais valores agora recebem o nome de "valores variantes". Após feita essa separação, esses valores são enviados para alimentar o rasterizador que passará os mesmos para o fragment shader.

- Tesselation

O tesselation é um estado opcional que irá melhorar o nível de detalhamento do modelo gráfico.

- Geometry Shader

O geometry shader é responsável por dar efeitos de sombreamento ao modelo, ou seja, o mesmo pode adicionar vértices adicionais ao modelo para reproduzir tal efeito.

- Vertex Post Processing

Após os vértices serem processados, as saídas dos mesmo passam por diversos processos antes de chegar na fase de rasterização.

- Primitive Assembly

Nessa etapa, os vértices são transformados em valores primitivos. Tal alteração influencia no formato que os triangulos vão assumir.

- Rasterization

A fase de rasterizacão promove uma eliminação das partes dos triangulos que ficaram fora do espectro definido. Para as partes que permaneceram dentro, elas são "quebradas" em fragmentos.

- Fragment Shader

O fragment shader é responsável por pegar os valores das variáveis do vertex shader e interpolalos na fase de rasterização. O resultado é a definição das cores finais do modelos

- Per Sample Operation

A etapa final da pipeline consiste em mostrar o buffer de frames resultante. Essa fase consiste em mostrar a imagem gerada pelo processo.

> Shader(s) do OpenGL:

- GLSL

> Exemplo de uso do OpenGL:

<img width="194" alt="image" src="https://user-images.githubusercontent.com/89364149/235786713-32f161d5-ad07-4a6f-a1cb-aa221bd1ca63.png">

> Código fonte OpenGL:

[Exemplo cubo vermelho simples](https://github.com/HugoNishimoto07/Comp-Visual/blob/main/Atividades/Atividade%20semana%2011/redsquare.c)

> Exemplo de aplicação do OpenGL:

O jogo Minecraft utiliza uma biblioteca chamada LWJGL para que seja possível a utilização dos gráficos 3D. Por sua vez, tal biblioteca faz uso do OpenGL para realizar a renderização dos gráficos.

## API gráfica 2: WebGL

> Pipeline WebGL

![pipelineWEBGL](https://user-images.githubusercontent.com/89364149/235649335-f3c3ca69-7dc4-4569-a991-519001e5ccc6.png)

*A imagem é do site: https://medium.com/trabe/a-brief-introduction-to-webgl-5b584db3d6d6

- Vertex Shader 

O vertex shader lida com o procesamento dos vértices do gráfico em questão

- Triangle Assembly



- Rasterization 

- Fragment Shader

- Testing and Blending

> Shader(s) do WebGL:

- GLSL

> Exemplo de uso do WedbGL:

<img width="481" alt="image" src="https://user-images.githubusercontent.com/89364149/235779394-aaff1bcd-7503-4b87-b907-9a97120933bf.png">

> Código fonte:

- [Exemplo triangulo simples](https://github.com/HugoNishimoto07/Comp-Visual/blob/main/Atividades/Atividade%20semana%2011/triangle.html)

> Exemplo de aplicação do WebGL:

O webGL é utilizado principalmente para renderização de gráficos 2D e 3D, e considerando essa característica, ele é aplicado para criar elementos para jogos, como por exemplo uma água com efeitos realistas. Ainda considerando sua usabilidade nos jogos, O WebGL tambem é utilizado para criar ambientes de realidade virtual.


>> Referências:

- https://pythonprogramming.net/opengl-rotating-cube-example-pyopengl-tutorial/#:~:text=First%20off%2C%20PyOpenGL%20is%20just,of%20OpenGL%20to%20other%20languages.

- https://medium.com/@pulkit.16296/the-opengl-rendering-pipeline-in-a-nutshell-b14874ce8aa2

- https://learnopengl.com/Getting-started/Shaders

- https://www.khronos.org/opengl/wiki/Shader

- https://www.opengl.org/archives/resources/code/samples/glut_examples/examples/cube.c

- https://www.lwjgl.org

- https://medium.com/trabe/a-brief-introduction-to-webgl-5b584db3d6d6

- https://www.tutorialspoint.com/webgl/webgl_drawing_a_triangle.htm

- https://get.webgl.org

- https://madebyevan.com/webgl-water/

