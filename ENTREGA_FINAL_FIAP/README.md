# Fase 6 — Visão Computacional com YOLO

**Aluno:** João Paulo Alves da Silva  
**RM:** rm573970

## Objetivo

Projeto de visão computacional da FIAP para detectar e diferenciar violões e guitarras utilizando um modelo YOLOv8n personalizado.

## Notebook

O notebook do projeto será disponibilizado neste repositório:

`Joao_Paulo_Alves_da_Silva_rm573970_pbl_fase6.ipynb`

Nele serão documentados o modelo, as métricas, as inferências e as conclusões.

## Resultados

Na última época registrada do treinamento de 50 épocas, foram obtidos:

- Precisão: 84,96%
- Recall: 50,00%
- mAP50: 76,77%
- mAP50–95: 46,68%

Os valores são da última época registrada e não necessariamente do melhor checkpoint. A validação utilizou apenas 12 imagens, portanto os resultados devem ser interpretados com cautela.

## Evidências

As imagens processadas pelo modelo serão incluídas na pasta `resultados_yolo/`.

## Vídeo demonstrativo

**YouTube não listado:** (https://youtu.be/PgVAc0KsVU0?is=GygsCjuQhtNtqS3l)

## Limitações e próximos passos

Ainda é necessário completar ou documentar a divisão de dados exigida no enunciado, executar uma segunda simulação com outra quantidade de épocas e comparar o YOLO personalizado com o YOLO padrão e uma CNN treinada do zero. Não foram atribuídos resultados fictícios a esses experimentos.

## Tecnologias

- Python
- Ultralytics YOLOv8n
- PyTorch
- OpenCV