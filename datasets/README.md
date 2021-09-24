# Datasets
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

Para acessar o dataset original usado neste trabalho, basta acessar o link do [Kaggle](https://www.kaggle.com/c/siim-covid19-detection). Porém, isso não é recomendado já que o dataset tem tamanho maior que 100GB. Para este repositório, foi feito a conversão dos `.dcm` para `.png` desses dados do Kaggle e, então, feito uma redução de dimensão para 600x600 pixels.

Para rodar este projeto, você deve usar este [dataset](https://drive.google.com/file/d/1asNV1LAUf32JskYSpplUQgmjQf0W5eLZ/view?usp=sharing)

Também há este outro [link](https://drive.google.com/file/d/1DS7ye5Xeosv8vLtixWdfjSVtPGC_B7Wr/view?usp=sharing) para baixar o dataset, mas para a reprodução deste projeto foi usado o link anterior, já que ele se encontra numa estrutura própria para ser embaralhado e servir de input para os modelos de redes neurais feitos no keras, usando data generators.

Você também precisa baixar os arquivos [train_image_level.csv](https://drive.google.com/file/d/17hTJnGSKpQiZN9-OFs1Y7gZtYe_SQJxr/view?usp=sharing) e [train_study_level.csv](https://drive.google.com/file/d/1-5xCGnpWNcFkgXEJW2VLePjeBH_07zN-/view?usp=sharing), que são usados para saber de quais classes as imagens são.

Por favor, não esqueça de conferir a licensa deste dataset, que se encontra neste mesmo diretório, no arquivo [LICENSE.md](LICENSE.md)
