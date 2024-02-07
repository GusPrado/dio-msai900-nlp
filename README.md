# MS Azure Language Studio

> Acesso via [Language Studio](https://language.cognitive.azure.com/)

Para utilizar esta ferramenta voce deve criar primeiro um novo recurso de `Language Service` (ou Serviço de Linguagem) no seu portal do MS Azure e depois fazer o link desta instância no Language Studio. Instruções detalhadas em: <https://aka.ms/ai900-text-analysis>

Neste modalidade também há várias opções para encurtar o caminho para quem precisa de alguma análise de linguagem natural - ou coloquial.

As sentenças foram geradas a partir da IA Generativa Bing disponivel no navegador da própria MS - o Edge. Este foi o prompt utilizado e o resultado retornado pelo Bing voce vê no arquivo `/inputs/sentences.txt`

> Hello bing! Could you please write some sentences in brazilian portuguese that reflects three types of sentiments? The types are (one of each):
> - NEGATIVE
> - POSITIVE
> - NEUTRAL

Dos testes realizados no módulo de `Análise de sentimentos e opiniões` os resultados esperados para sentenças positivas e negativas atingiram a expectativa. Porém quando é uma sentença tendendo mais a um tom neutro, ttalvez pelo fato de serem algumas frases a inteligencia pontuou algumas como negativa e apenas uma delas como neutra - o que possivelmente tenha levado a uma análise de sentimento negativo quando na realidade não era necessariamente.

Portanto ainda existe um grande espaço de evolução no treinamento deste tipo de avaliação.

Seguem os prints dos resultados:

**Resultado POSITIVO:**
![Sentença positiva](/output/positive.png)

**Resultado NEGATIVO:**
![Sentença negativa](/output/negative.png)

**Resultado NEGATIVO** *(Esperado como NEUTRO)*:
![Sentença negativa](/output/neutral.png)