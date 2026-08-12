# Teachable Machine — Reconhecimento de Imagem

## Descrição

Esse projeto foi feito para criar um modelo de Inteligência Artificial capaz de identificar, através de uma imagem da webcam, se uma pessoa está **com celular** ou **sem celular**.

Para isso, utilizei o **Teachable Machine**, criando um modelo de classificação de imagens com duas classes:

* **Com celular**
* **Sem celular**

Depois de treinar o modelo, fiz alguns testes usando a webcam para verificar se ele conseguia identificar corretamente cada situação.

## Como o modelo foi treinado

O modelo foi treinado com duas classes:

| Classe          | O que representa                                 |
| --------------- | ------------------------------------------------ |
| **Com celular** | Quando a pessoa aparece na imagem com um celular |
| **Sem celular** | Quando a pessoa aparece na imagem sem um celular |

As imagens foram usadas para ensinar a IA a perceber as diferenças entre as duas situações.

## Origem dos dados

Os dados foram **gravados por mim utilizando a minha própria webcam**.

Não utilizei nenhum dataset externo, como os encontrados no Kaggle. Eu mesmo gravei as imagens utilizadas para treinar as duas classes do modelo.


## Link do modelo exportado

O modelo treinado no Teachable Machine pode ser acessado pelo link abaixo:

**https://teachablemachine.withgoogle.com/models/KDzA0pL4bu/**

## Código-fonte

O código da aplicação está disponível no meu repositório do GitHub:

**https://github.com/nicoleebm/TeachableMachine/blob/main/site.html**

## Prints / Evidências

### Painel de treinamento

Aqui está um print mostrando o painel do Teachable Machine durante o treinamento do modelo:

****

### Teste do modelo

Aqui estão os prints mostrando os testes realizados, onde o modelo tenta identificar se a pessoa está com ou sem celular:

Teste: [`Com celular`](./teste-com.png)
Teste: [`Sem o celular`](./teste-sem.png)

Painel de Treino: **[`paineldetreino.png`](./paineldetreino.png)**

### Vídeo
O vídeo mostra o funcionamento do modelo e alguns testes feitos utilizando a webcam.

****

## Reflexão
Durante os testes, o modelo apresentou alguns erros na hora de identificar as imagens. Acredito que isso aconteceu por causa do excesso de informações nas imagens, dos diferentes ângulos e posições, além da iluminação e da qualidade da imagem. Esses fatores acabaram dificultando um pouco a identificação correta pela IA. Acho que, com mais dados e imagens em situações diferentes, o modelo poderia ter resultados melhores e mais precisos.


