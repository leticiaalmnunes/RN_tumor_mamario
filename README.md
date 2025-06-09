![Logos](https://github.com/user-attachments/assets/d84c618a-1539-457d-877f-430a6f84defc)

# Otimização de hiperparâmetros de NN para classificação de tumor mamário
🩷🎗️ Rede Neural Profunda para classificação de tumor mamário a partir de dados extraídos de mamografia. Projeto final da disciplina _Redes Neurais e Algoritmos Genéticos_, ministrada pelo Prof. Dr. Daniel Cassar, do 3º semestre do BSc. em Ciência e Tecnologia da Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais.

## 🎯 Objetivo
Otimizar os hiperparâmetros de uma rede neural do tipo MLP para resolver um problema de interesse científico.
### Hiperparâmetros otimizados
`OTIMIZADOR`: Otimizadores. Opções: ['SGD', 'Adam'] <br>
`TAXA_APRENDIZADO`: Taxa de aprendizado da rede. Opções: [10<sup>-1</sup>, 10<sup>-2</sup>, 10<sup>-3</sup>, 10<sup>-4</sup>, 10<sup>-5</sup>] <br>
`DROPOUT_RATE`: Taxa de *dropout*. Opções: [0.05, 0.1, 0.2, 0.3] <br>
`FUNC_ATIVACAO`: Função de ativação dos neurônios. Opções: ['sigmoid', 'ReLU'] <br>
`NUM_CAMADAS`: Número de camadas ocultas. Opções: [2 a 10] <br>
`NUM_NEURONIOS`: Número de neurônios por camada. Opções: [1 a 50] <br>

## 🗂️ Arquivos
- Tarrasque.ipynb - _Jupyter Notebook_ com o código da rede neural e a otimização de hiperparâmetros.
- Estudo optuna tumor.db - Arquivo do estudo realizado pelo _Optuna_ durante a otimização de hiperparâmetros.
- cancer_mama.csv - Dataset sobre tumores mamários extraído da plataforma _Kaggle_.

## 🤝 Contribuição de cada colaborador
[<img src="https://avatars.githubusercontent.com/u/172425156?v=4" width=80>](https://github.com/leticiaalmnunes)
**Letícia Almeida Nunes** - Pesquisa; Implementação (idealização, auxílio e revisão); Documentação (escrita).

[<img src="https://avatars.githubusercontent.com/u/172424921?v=4" width=80>](https://github.com/pedrocoelhogf)
**Pedro Coelho Gimenes de Freitas** - Pesquisa; Implementação (idealização, escrita do código); Documentação (revisão).
