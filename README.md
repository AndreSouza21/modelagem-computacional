# Segmentação de uma pluma de fumaça com SAM 2

Atividade de Modelagem Computacional

**Grupo:** André Ferreira Santos (176013), André Souza de Almeida (176024), Letícia Abrahão Moreira (176559), Lucas Alves Gazale (176565)

**Caso:** incêndio na Refinaria Henrique Lage (Revap), São José dos Campos (SP), em 29/09/2019.

## Arquivos

- `deteccao.ipynb`: notebook do Colab com o código, as figuras e a análise
- `plumaa.jpg`: imagem usada ([fonte: G1](https://g1.globo.com/sp/vale-do-paraiba-regiao/noticia/2019/09/29/incendio-na-revap-mobiliza-bombeiros-e-fumaca-assusta-moradores-em-sao-jose-sp.ghtml))
- `mascara_final.png`: máscara final gerada pelo notebook

## O que foi feito

Segmentação da pluma com o SAM 2.1, comparando seis configurações de prompt (ponto, caixa, pontos positivos e negativos), com pós-processamento e análise de iluminação, contraste e semelhança com nuvem.

## Como executar

1. Abra `deteccao.ipynb` no Google Colab e ative a GPU.
2. Envie `plumaa.jpg` para `/content/`.
3. Execute as células em ordem.
