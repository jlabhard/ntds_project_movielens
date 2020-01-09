# Movie recommender system using signal diffusion
In this project, we created a movie recommendation system based on graph signal processing. The task is to recommend movies to a user given some ratings of that user.  More details can be found in our final report.

## Dependencies

In order to run the code, the following dependecies need to be dowloaded on your machine.

### Libraries
For a detailed way of installing most of libraries all at once follow these
[installation instructions](https://github.com/mdeff/ntds_2019#installation).
You will also need the following library.
* [Surpise] - Install Surprise library

    ```sh
    $ conda install -c conda-forge scikit-surprise
    ```

### Data

The data containing can be dowloaded here [MovieLens 100k](https://grouplens.org/datasets/movielens/) and should be moved inside the `Data` folder.

## Files

- Main.ipynb: Contains our recommendation system. To get the 10 most relevant recommendations for a given user you can run the `get_recommendations()` function.
We also compare our model with a matrix-factorization based recommendation system. You can get the prediction given by this model using the `baseline_recommendations()` function.

## Contributors

- Deniz Ira
- Jonathan Labhard
- Daniil Dmitriev
- Paul Griesser
