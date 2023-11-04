Projeto Final
Aluno: Lucas Bernardo da Costa
Projeto: Classificar os tipos de panelas em um catálogo de panelas de cozinha. As classes são: Travessa de forno, Frigideira e Panela de Pressão.
Metodologia: Foi usado o Roboflow para classificar as panelas, dividindo entre 70% de treino, 20% de teste e 10% de validação. 
Após isto, foi usado um algorítimo YoloV5 para realizar o treino e validação do sistema. Foram usados 5 epochs.
# Projeto Final - Modelos Preditivos Conexionistas

### Lucas Bernardo da Costa

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|Classificação de Imagens<br>|YOLOv5|Tensorflow|

## Performance

O modelo treinado possui performance de **100%**.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```text
     test_loss    top1_acc    top5_acc
       1/5        0G        1.15        1.08       0.474           1: 100% 7/7 [00:19<00:00,  2.84s/it]
       2/5        0G        1.06        1.06       0.474           1: 100% 7/7 [00:16<00:00,  2.41s/it]
       3/5        0G        1.01        1.07       0.474           1: 100% 7/7 [00:17<00:00,  2.56s/it]
       4/5        0G       0.982         1.1       0.474           1: 100% 7/7 [00:19<00:00,  2.73s/it]
       5/5        0G       0.936        1.06       0.474           1: 100% 7/7 [00:17<00:00,  2.51s/it]
  ```
</details>

### Evidências do treinamento
<img width="430" alt="exemplo de classe" src="https://github.com/zlucasbernardo/Panela-velha-que-faz-Programa-o-boa/assets/147263402/44fa92e7-79a1-4f27-8a85-2f906838a24b">


## Roboflow

Nessa seção deve colocar o link para acessar o dataset no Roboflow
[https://universe.roboflow.com/cesar-school-h4lgz/classificador-de-panelas]
