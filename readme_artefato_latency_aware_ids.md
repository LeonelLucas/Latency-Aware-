# Latency-Aware Evaluation of Flow-based ML-IDS

Artefato referente ao artigo "Latency-Aware Evaluation of Flow-based ML-IDS: An Experimental Study on Instance Granularity and Input-Class Sensitivity".

Este repositório contém os códigos, modelos treinados, notebooks e arquivos utilizados nos experimentos conduzidos no artigo.

## Estrutura do Repositório

```text
Dataset/
├── class_cicids.csv

Estatística/
├── Medias_desvio_padrao/
├── Testes_estatisticos.ipynb

Latência de inferência/
├── Classe_benigna/
├── Classe_maliciosa/
├── Classes_mista/
├── Experimento_em_lote.ipynb
├── Experimento_instância_a_instância.ipynb

Modelos/
├── modelos treinados (.pkl)

Treinamento de modelos/
├── TreinamentoModelos.ipynb
```

### Descrição das Pastas

- `Dataset/`: contém o dataset utilizado nos experimentos.
- `Estatística/`: contém os notebooks e arquivos relacionados às análises estatísticas.
- `Latência de inferência/`: contém os experimentos relacionados à avaliação de latência de inferência.
- `Modelos/`: contém os modelos treinados utilizados para geração das inferências e execução dos testes.
- `Treinamento de modelos/`: contém os notebooks utilizados para treinamento dos modelos.

## Requisitos

- Python 3.x
- Jupyter Notebook

Principais bibliotecas utilizadas:

```python
pandas
numpy
scikit-learn
matplotlib
seaborn
scipy
scikit-posthocs
```

As dependências podem ser instaladas com:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn scipy scikit-posthocs notebook
```

## Execução

1. Instale as dependências necessárias.
2. Abra os notebooks `.ipynb` utilizando Jupyter Notebook ou JupyterLab.
3. Execute as células conforme necessário.

Os principais notebooks do projeto incluem:

- `TreinamentoModelos.ipynb`: treinamento dos modelos.
- `Experimento_em_lote.ipynb`: avaliação de latência em processamento em lote.
- `Experimento_instância_a_instância.ipynb`: avaliação de latência por instância.
- `Testes_estatisticos.ipynb`: execução das análises estatísticas.

## Observações

- Os modelos treinados já estão disponíveis na pasta `Modelos/`.
- Algumas execuções podem demandar tempo dependendo do hardware utilizado.

