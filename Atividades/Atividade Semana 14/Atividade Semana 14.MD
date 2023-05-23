> Nome: Fernando Bastos Arbache
> RA: 31806211

> Nome: Hugo Shiniti Nishimoto
> RA: 32048416

> Nome: Lucas Souza Silva
> RA: 32058179

> Nome: Vinicius Rodrigues Figueira de Faria
> RA: 32013639


# Atividade Semana 14 – Computação Visual

Resolução:


> Modulate 

A operação de multiplicação de texturas, ou modulate, segue o seguinte formato: textura fonte * textura de destino. Além disso, há um fator que entra na equação que é o chamado "alpha channel", o qual permite que sejam definidos níveis de transparência, com o intuito de permitir que a luz passe através dos objetos.

Referência(s): 
- https://docs.unrealengine.com/4.26/en-US/RenderingAndGraphics/Materials/MaterialProperties/BlendModes/
- https://learn.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/graphics/skiasharp/effects/blend-modes/separable

> Mul()

A função mul(), presente na linguagem de programação HLSL, realiza uma multiplicação de texturas a partir de multiplicação de matrizes. Por envolver multiplicação de matrizes, o eixo x e o eixo y devem possuir tamanho "igual", ou seja, o número de linhas deve ser igual ao número de colunas.

Referência(s): 
- https://learn.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl-mul


Outras referências: 
- https://docs.blender.org/manual/en/2.79/render/blender_render/materials/properties/transparency.html#:~:text=Materials%20in%20Blender%20can%20be,to%20its%20RGB%20color%20values.
