![Logos](https://github.com/user-attachments/assets/d84c618a-1539-457d-877f-430a6f84defc)

# Otimização de hiperparâmetros de NN para classificação de tumor mamário
🩷🎗️ Rede Neural Profunda para classificação de tumor mamário a partir de dados extraídos de mamografia. Projeto final da disciplina _Redes Neurais e Algoritmos Genéticos_, ministrada pelo Prof. Dr. Daniel Cassar, do 3º semestre do BSc. em Ciência e Tecnologia da Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais.

## Introdução

O câncer de mama é uma condição neoplástica caracterizada pela proliferação desordenada de células mamárias anormais. De acordo com a Organização Mundial da Saúde, mais de 2.3 milhões de mulheres foram diagnosticadas com câncer de mama em 2022, o que o torna o tipo de câncer mais prevalente na população feminina. Além disso, em 95% dos países, o câncer de mama é a primeira ou a segunda principal causa de morte por câncer em mulheres. [1, 2]

Nesse contexto, a detecção preventiva do tumor pode reduzir os gastos com sistema de saúde público, além da quantidade de mortes associadas a essa doença. Para isso, diversos exames para investigação preventiva do câncer de mama – como mamografia, imageamento por ressonância magnética ou por tomografia computadorizada, por exemplo – são utilizados para mapeamento dos casos. No entanto, os métodos tradicionais de detecção do câncer de mama enfrentam desafios, como a complexidade das imagens mamográficas e a possibilidade de resultados falso-negativos na identificação do tipo de tumor, devido às dificuldades em identifica-los nos estágios iniciais da doença.

Recentemente, modelos de aprendizado profundo têm sido explorados para a detecção do câncer de mama. Esses modelos têm a capacidade de aprender características complexas e hierárquicas, aumentando a sensibilidade e a especificidade na detecção, o que contribui para um diagnóstico mais precoce e preciso. Na literatura, muitos estudos têm adotado redes neurais para a classificação do câncer de mama, seja para identificar subtipos ou para diferenciar casos benignos de malignos. 

## 🎯 Objetivo
Desenvolver e avaliar **redes neurais** otimizadas, especificamente MLP (Perceptron Multicamadas), utilizando técnicas de aprendizado profundo para **classificar** tumores de mama como benignos ou malignos, com base em dados extraídos de imagens de mamografias. Para isso, serão exploradas técnicas para evitar o sobreajuste do modelo, bem como a aplicação do _Optuna_ para **otimização dos hiperparâmetros**.

### Hiperparâmetros otimizados
`OTIMIZADOR`: Otimizadores. Opções: ['SGD', 'Adam'] <br>
`TAXA_APRENDIZADO`: Taxa de aprendizado da rede. Opções: [10<sup>-1</sup>, 10<sup>-2</sup>, 10<sup>-3</sup>, 10<sup>-4</sup>, 10<sup>-5</sup>] <br>
`DROPOUT_RATE`: Taxa de *dropout*. Opções: [0.05, 0.1, 0.2, 0.3] <br>
`FUNC_ATIVACAO`: Função de ativação dos neurônios. Opções: ['sigmoid', 'ReLU'] <br>
`NUM_CAMADAS`: Número de camadas ocultas. Opções: [2 a 10] <br>
`NUM_NEURONIOS`: Número de neurônios por camada. Opções: [1 a 50] <br>

## 🗂️ Arquivos
- Tarrasque.ipynb - _Jupyter Notebook_ com o código da rede neural e a otimização de hiperparâmetros.
- tumor.db - Arquivo do estudo realizado pelo _Optuna_ durante a otimização de hiperparâmetros.
- cancer_mama.csv - Dataset sobre tumores mamários extraído da plataforma _Kaggle_.

## 🤝 Contribuição de cada colaborador
[<img src="https://avatars.githubusercontent.com/u/172425156?v=4" width=80>](https://github.com/leticiaalmnunes)
**Letícia Almeida Nunes** - Pesquisa; Implementação (idealização, auxílio e revisão); Documentação.

[<img src="https://avatars.githubusercontent.com/u/172424921?v=4" width=80>](https://github.com/pedrocoelhogf)
**Pedro Coelho Gimenes de Freitas** - Pesquisa; Implementação (idealização, escrita do código); Documentação.
