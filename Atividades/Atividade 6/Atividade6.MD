## Atividade 6 Teórica

>***Integrantes do Grupo***:

> Fernando Bastos
> RA: 31806211

> Hugo Shiniti Nishimoto
> RA: 32048416

> Lucas Souza Silva
> RA: 32058179

> Vinicius Rodrigues Figueira de Faria 
> RA: 32013639

1)Realizar a limiarização de uma imagem usando Python e scikit-image.
Utilizando a função threshold_otsu da biblioteca skimage.filters é possível limiarizar a imagem que for passada como parâmetro na função.

![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)
![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)

2)Plotar o histograma de uma imagem tons de cinza usando Python, scikit-image e matplotlib.
Dentro da biblioteca skimage existe a função exposure.histogram, capaz de criar um histograma a partir da imagem recebida como parâmetro.

![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)
![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)

3)Plotar o histograma de uma imagem colorida (um histograma por canal de cor) usando Python, scikit-image e matplotlib.
Utilizando o mesmo exposure.histogram, mas separando a imagem pelos canais 1, 2 e 3 e entao plotando os 3 histogramas criados.

![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)
![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)


4)Equalizar o histograma de uma imagem usando Python e scikit-image.
Dentro do scikit-image existe a função exposure.equalize_hist, própria para a equalização do histograma que for passado como parâmetro.

![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)
![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)


5)Detectar (concluir) que uma foto está subexposta ou que está superexposta, analisando o histograma.
Uma imagem que está subexposta, ou seja, escura, terá um histograma onde os picos ficarão no lado esquerdo, enquanto uma imagem superexposta, com brilho alto, seus picos ficarão no lado direito do histograma.

![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)
![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)


6)Detectar (concluir) se uma imagem está com baixo contraste ou alto contraste, analisando o histograma.
Para identificar se uma imagem possui baixo ou alto contraste, podemos observar a distribuição dos valores de intensidade no histograma. Se a distribuição for uniforme e concentrada no centro do histograma, como no histograma a esquerda, que possui seu pico entre 25 e 50 no nível de cinza, a imagem tem baixo contraste. Por outro lado, se houver picos marcantes em diferentes partes do histograma, como no histograma a direita, que abrange do 50 ao 200, a imagem tem alto contraste.

![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)
![fig1](https://github.com/HugoNishimoto07/Comp-Visual/blob/c66a3b8c7e589a70c99913c0088e560e2583b099/Atividades/Atividade%204/blurring.png)



Referencias Utilizadas

https://scikit-image.org/docs/stable/auto_examples/segmentation/plot_thresholding.html#thresholding
https://scikit-image.org/docs/stable/auto_examples/color_exposure/plot_equalize.html
https://danielmuellerkomorowska.com/2020/06/17/analyzing-image-histograms-with-scikit-image/
https://scikit-image.org/docs/stable/auto_examples/applications/plot_rank_filters.html#sphx-glr-auto-examples-applications-plot-rank-filters-py
https://scikit-image.org/docs/stable/api/skimage.exposure.html#skimage.exposure.adjust_gamma
https://scikit-image.org/docs/stable/api/skimage.exposure.html#skimage.exposure.rescale_intensity
https://scikit-image.org/docs/stable/api/skimage.html
