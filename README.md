# Projetos de Redes Neurais - IA353

## Descrição Geral
Este repositório contém projetos desenvolvidos na disciplina **IA353 (2024) - Redes Neurais**, como parte do programa de pós-graduação da **FEEC-Unicamp**, sob a orientação do professor **Fernando José Von Zuben**. Os exercícios propostos abordam a modelagem, treinamento e análise de redes neurais, aplicando técnicas como regressão linear regularizada, aprendizado extremo, MLPs e CNNs.

---

### **PC01 - Regressão Linear Regularizada (MNIST)**
O objetivo do PC01 foi implementar um classificador linear para a base de dados **MNIST** (dígitos manuscritos), utilizando a técnica de **regressão linear regularizada** (*ridge regression*). Este projeto incluiu:
- Busca de um coeficiente de regularização ideal utilizando validação holdout (70% treino e 30% validação).
- Ajuste do modelo final com todos os dados de treinamento.

O notebook correspondente pode ser encontrado [aqui](./PC01_LC_MNIST.ipynb).

---

### **PC02 - Validação Cruzada com Classificadores Lineares (MNIST e CIFAR-10)**
Neste projeto, foi implementado o método de **validação cruzada** para ajustar classificadores lineares. O notebook foi adaptado para as bases de dados **MNIST** e **CIFAR-10**, avaliando os classificadores com métricas de desempenho e respondendo às questões propostas.

O notebook correspondente pode ser encontrado [aqui](./PC02_LC_CV.ipynb).

---

### **PC03 - Máquinas de Aprendizado Extremo (ELM)**
Utilizando **Extreme Learning Machines (ELM)**, foi implementado um classificador com uma camada intermediária. O modelo foi testado nas bases **MNIST** (1.000 neurônios) e **CIFAR-10** (2.000 neurônios), avaliando o desempenho e respondendo às perguntas contidas no notebook.

O notebook correspondente pode ser encontrado [aqui](./PC03_ELM.ipynb).

---

### **PC04 - Redes Neurais MLP (MNIST e CIFAR-10)**
O PC04 envolveu a implementação de redes neurais **MLP (Multilayer Perceptron)** usando o framework Keras. O treinamento incluiu ajuste de hiperparâmetros com **grid search** para definir o número de camadas, neurônios, taxa de dropout, e outras configurações.

O notebook correspondente pode ser encontrado [aqui](./PC04_MLP_PartA.ipynb).

---

### **PC05 - Redes Neurais Convolucionais (CNN)**
Neste projeto, redes convolucionais (**CNN**) foram implementadas para classificação das bases **MNIST** e **CIFAR-10**. O modelo utilizou camadas convolucionais com maxpooling e dropout, ajustando hiperparâmetros e comparando os resultados com os métodos anteriores.

O notebook correspondente pode ser encontrado [aqui](./PC05_CNN.ipynb).

---

## Participação
Este projeto foi desenvolvido em parceria com **Beatriz Akiria de Assis Quaresma**.

---

## Licença
Este repositório está licenciado sob a [Licença MIT](./LICENSE).
