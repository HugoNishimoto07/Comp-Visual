## Terceira atividade Teórica - Aplicações da Computação Visual

>***Integrantes do Grupo***:

> Fernando Bastos
> RA: 31806211

> Hugo Shiniti Nishimoto
> RA: 32048416

> Lucas Souza Silva
> RA: 32058179

> Vinicius Rodrigues Figueira de Faria 
> RA: 32013639
> 
O artigo "Multiple Object Recognition with Focusing and Blurring" aborda o problema de reconhecimento de objetos em cenas com múltiplos objetos. 
O desafio é identificar corretamente os objetos presentes em uma cena, mesmo quando eles estão parcialmente ocultos ou sobrepostos.
A solução proposta pelos autores envolve o uso de uma abordagem de foco e desfoque. A ideia básica é, utilizar algoritmos de detecção como faster R-CNN e 
YOLO para a identificação de todos os itens que compõem uma imagem, classificá-los, com base na importância em vez de tentar segmentar cada objeto individualmente, 
o modelo deve se concentrar em regiões de interesse na imagem e desfocar o resto da imagem. Isso permite que o modelo dedique mais recursos de processamento às regiões de interesse, melhorando a precisão do reconhecimento de objetos.

<img src="Comp-Visual/Atividades/blurring.png" width=300>

Figura 1: Exemplo do foco e desfoque
O uso do filtro de suavização (Blur)  é essencial nesta abordagem, pois permite que o modelo concentre seus recursos de processamento nas regiões de interesse. 
Além disso, o Blur também ajuda a reduzir o efeito de sobreposição de objetos, tornando mais fácil para o modelo identificar os objetos individuais.

Referência: 
•	Multiple object recognition with focusing and blurring. http://cs231n.stanford.edu/reports/2016/pdfs/259_Report.pdf
