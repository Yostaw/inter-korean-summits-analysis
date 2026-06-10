# Framing the 2018 Inter-Korean Summits in South Korean Newspapers

## Project Description

This repository contains the replication package for the final paper *"Framing the 2018 Inter-Korean Summits in South Korean Newspapers: A Comparative Text Analysis of Chosun Ilbo and Hankyoreh"* completed for the BA2 Digital Korea course.

The project examines how two major South Korean newspapers, Chosun Ilbo and Hankyoreh, framed the 2018 inter-Korean summits. These newspapers are commonly associated with different political orientations, making them useful for studying variation in media framing of the same political events.

## Research Question

How did Chosun Ilbo and Hankyoreh frame the 2018 inter-Korean summits differently?

## Methods

The analysis was conducted using Orange Data Mining and the Orange Text Mining add-on.

The following computational text analysis methods were used:

- Sentiment analysis
- TF-IDF keyword extraction
- Latent Dirichlet Allocation (LDA) topic modelling

The dataset was filtered to include only articles published in 2018.

## Repository Structure

```
inter-korean-summits-analysis/
├── analysis/      # Orange workflow (.ows)
├── data/          # Dataset documentation
├── figures/       # Figures used in the paper
├── resources/     # Stopword lists and sentiment lexicons
├── scripts/       # Python preprocessing scripts
├── README.md
├── requirements.md
├── LICENSE
└── CITATION.cff
```

## Reproducing the Analysis

1. Install Orange Data Mining.
2. Install the Orange Text Mining add-on.
3. Open the workflow file in the `analysis/` folder.
4. Ensure all required scripts and resources are available.
5. Load the inter-Korean summit dataset.
6. Run the workflow to reproduce the analyses and figures reported in the paper.

## Data Source

The dataset was provided as part of the Digital Korea course materials and consists of newspaper articles from Chosun Ilbo and Hankyoreh covering inter-Korean summits between 2000 and 2018.

Additional information about the dataset can be found in:

- `data/SOURCE.md`
- `data/data_dictionary.md`

## Author

Yosta Wullink

BA2 Digital Korea

Leiden University
