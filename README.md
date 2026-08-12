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

**[https://teachablemachine.withgoogle.com/models/KDzA0pL4bu/]**

## Código-fonte

O código da aplicação está disponível no meu repositório do GitHub:

**https://github.com/nicoleebm/TeachableMachine/blob/main/site.html**

## Prints / Evidências

### Painel de treinamento

Aqui está um print mostrando o painel do Teachable Machine durante o treinamento do modelo:

**[COLE AQUI O PRINT DO PAINEL DE TREINO]**

### Teste do modelo

Aqui está um print mostrando um dos testes realizados, onde o modelo tenta identificar se a pessoa está com ou sem celular:

**[COLE AQUI O PRINT DO TESTE]**

### Vídeo
O vídeo mostra o funcionamento do modelo e alguns testes feitos utilizando a webcam.

**[COLE AQUI O LINK DO VÍDEO]**

## Reflexão
Durante os testes, o modelo apresentou alguns erros na hora de identificar as imagens. Acredito que isso aconteceu por causa do excesso de informações nas imagens, além dos diferentes ângulos e da iluminação. Essas mudanças podem dificultar a identificação correta pela IA. Talvez, com mais dados e imagens em diferentes situações, o modelo pudesse apresentar resultados melhores.

## Conclusão
Com esse projeto, consegui entender um pouco melhor como funciona o treinamento de um modelo de Inteligência Artificial para classificação de imagens. Mesmo tendo alguns erros, o modelo conseguiu diferenciar as duas classes, **"Com celular"** e **"Sem celular"**, usando imagens capturadas pela webcam.
