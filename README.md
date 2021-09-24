# EfficientNet V1 fine-tuning para classificação de radiografias COVID19
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Repositório para o projeto das disciplinas ECOM178-M REDES NEURAIS E APRENDIZADO PROFUNDO e ECOM181 - FUNDAMENTOS DE IA APLICADOS AO DIAGNÓSTICO MÉDICO.

Neste trabalho, foi realizado um fine-tuning da rede neural EfficientNetB5, com os pesos treinados no dataset ImageNet. Para o problema deste trabalho, o fine-tuning foi feito para classificar radiografia de tórax em 3 classes: `atypical`, `indeterminate` e `typical` para COVID19. Mais informações sobre o `dataset` estão disponíveis no arquivo [README.md](datasets/README.md) do diretório [datasets](datasets/).

O código que faz a conversão de `.dcm` para `.png`, que monta o dataframe com os pares `imagem-classe`, que faz a redestribuição do dataframe em `treino` e `teste`, que carrega essa distribuição em `data generators` e faz o `fine-tuning` da `EfficientNetB5` está contido no diretório [src](src/).

Por favor, não esqueça de verificar a licensa deste projeto. Você também pode contribuir, basta sugerir modificações por um Pull Request.
