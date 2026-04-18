# Proyecto_DeepLearning_NLP_Oscar_Fernandez

Proyecto de NLP para analizar reviews de Trustpilot mediante embeddings,
clustering, analisis de sentimiento, visualizacion y modelado de topicos.

## Notebook principal

- `Review_NLP.ipynb`

El notebook se ejecuto con el kernel `master_ds_clean` y Python `3.11.15`.

## Dependencias

Versiones detectadas en el entorno asociado al kernel del notebook:

| Paquete | Version | Uso en el notebook |
| --- | --- | --- |
| `python` | `3.11.15` | Runtime principal |
| `ipykernel` | `7.2.0` | Ejecucion del notebook |
| `notebook` | `7.5.5` | Interfaz de notebook |
| `pandas` | `3.0.2` | Carga, filtrado y agregacion de datos |
| `matplotlib` | `3.10.8` | Graficos y visualizaciones |
| `seaborn` | `0.13.2` | Visualizaciones exploratorias |
| `scikit-learn` | `1.8.0` | KMeans, PCA, metricas y stopwords |
| `transformers` | `5.5.3` | Pipeline de analisis de sentimiento |
| `sentence-transformers` | `5.4.0` | Embeddings semanticos de reviews |
| `bertopic` | `0.17.4` | Modelado de topicos |
| `wordcloud` | `1.9.6` | Nubes de palabras |
| `torch` | `2.11.0` | Backend de modelos Transformer |
| `numpy` | `2.4.4` | Dependencia numerica base |
| `scipy` | `1.17.1` | Dependencia cientifica usada por scikit-learn/BERTopic |
| `hdbscan` | `0.8.42` | Dependencia de BERTopic |
| `umap-learn` | `0.5.12` | Reduccion dimensional usada por BERTopic |
| `plotly` | `6.7.0` | Visualizaciones interactivas de BERTopic |

Instalacion equivalente con `pip`:

```bash
pip install pandas==3.0.2 matplotlib==3.10.8 seaborn==0.13.2 scikit-learn==1.8.0 transformers==5.5.3 sentence-transformers==5.4.0 bertopic==0.17.4 wordcloud==1.9.6 torch==2.11.0 numpy==2.4.4 scipy==1.17.1 hdbscan==0.8.42 umap-learn==0.5.12 plotly==6.7.0 ipykernel==7.2.0 notebook==7.5.5
```

## Modelos externos

El notebook descarga/carga modelos desde Hugging Face durante la ejecucion:

- `sentence-transformers/all-MiniLM-L6-v2`: generacion de embeddings.
- `distilbert-base-uncased-finetuned-sst-2-english`: analisis de sentimiento con `transformers.pipeline`.

## Link a github

https://github.com/OscarFdz24/Proyecto_DeepLearning_NLP_Oscar_Fernandez
