# Classificació de Fruites Fresques i Podrides

Aquest projecte utilitza models de visió per computador per classificar fruites com a fresques o podrides a partir d'imatges. L'objectiu és entrenar un model de xarxa neuronal convolucional (CNN) per identificar l'estat de les fruites en funció de les seves imatges.

## Descripció

El conjunt de dades utilitzat en aquest projecte consta de dues categories: fruites fresques i fruites podrides. Es farà servir un model de classificació per identificar en què estat es troba cada fruit.

[Conjunt de dades](https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification/data)
[Repositori GitHub]([https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification/data](https://github.com/Gabriel1634021/Fruit_Classification))

## Experiments i Metodologia

Durant el desenvolupament d'aquest projecte, hem experimentat amb diverses estratègies i models per millorar la precisió de classificació:

1. **Extracció de característiques**:
   - HOG (Histogram of Oriented Gradients).
   - Histograma d'intensitats.
   - LBP (Local Binary Patterns).
   - Hu Moments.
   - GLCM (Gray Level Co-occurrence Matrix).

2. **Classificadors tradicionals**:
   - **SVM**: Provant kernels com el lineal, polinòmic i RBF , i utilitzant estratègies OVO (One-Versus-One) i OVA (One-Versus-All).
   - **KNN**: Realitzant un **Grid Search** per trobar els millors paràmetres.

3. **Models preentrenats**:
   - **EfficientNet**: Provant les variants B0 i B2.
   - **VGG16**: Per comparar el rendiment amb arquitectures més complexes.

## Integrants
- Luis Adrián Gómez
- Gabriel Marcos Martínez
