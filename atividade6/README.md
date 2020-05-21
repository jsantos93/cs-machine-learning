# Clustering

## :pencil: Atividade 06

**k-Means**:

- Carregue a base `sample_stocks.csv`
- Visualize suas informações
- Plote a dispersão de returns vs. dividendyield
- Normalize os dados
- Plote novamente a dispersão
- Crie e treine o KMeans com um valor de k que achar válido
- Plote a dispersão juntamente com os `kmeans.cluster_centers_`
- Analise o valor de `K` utilizando o método `Elbow` baseado na inércia (`kmeans.inertia_`)

**Clustering Hierárquico**:

- Implemente Clustering Hierárquico
  - Caso seja lento, altere a distância utilizada (linkage) ou faça amostragem nos dados
- Plote o dendograma

**Implementação Livre**:

Implemente pelo menos mais uma forma de clustering a seu critério e compare as três formas de visualização.

- Sugestão: DBSCAN, Mean-Shift, ...

## :whale: Docker installation and usage

docker-compose up mounts the directory and starts the container
docker-compose down destroys the container

### Requirements

- [Docker](https://docs.docker.com/get-docker/)
- [Docker-compose](https://docs.docker.com/compose/install/)

### Building and running

First, make sure you are inside this repository's directory:

```bash
cd <path/to/clustering-yodistas_clustering>
```

Then, start the container:

```bash
docker-compose up --detach # starts the container in the background of your terminal
```

At this point, the Jupyter Notebook will be running at the following URL: `http:localhost:8888`

Once you're done, you may destroy the container with the following command:

```bash
docker-compose down
```
