# NBA Game Predictor (Version 1)

## Description

This project utilizes machine learning and data science to analyze past regular season NBA games and predict winners. The gradient boosting model is trained on 
data from tens of thousands of NBA games from the past five years and attempts to classify each game as a 0 (loss) or 1 (win). Statistical features include basic team stats, 
like points, rebounds and assists, as well as advanced statistics, like true shooting percentage and effective field goal percentage. 
The model achieves roughly 80% accuracy on past NBA games, and is capable of predicting winners of future NBA games above 50% accuracy.

## Getting Started

### Dependencies

Data is imported using the `nba_api` for Python. `pandas` and `numpy` are required for data manipulation. ML models, predictions, and testing come from `scikit-learn`.

### Installing

* All of the necessary code to run this app may be found in the Jupyter Notebook named after the repository.
* This notebook was created using a local Python 3.12.4 kernel.

### Executing program

Code cells may be executed individually, but it is recommended to run all code cells at once. The notebook features Markdown cells that explain what each code segment does.

## Authors

Author: Kishore Annambhotla

## Version History

This project will not be updated in the future; however, there are plans to improve upon this project with more data and a new player-based model capable
of predicting player stat-lines and team totals.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

Basic data manipulation was inspired from a Medium post by [Julius Cecilia](https://medium.com/@juliuscecilia33/predicting-nba-game-results-using-machine-learning-and-python-6be209d6d165).

Other resources:
* ["Predicting the Outcome of NBA Games" by Matthew Houde](https://digitalcommons.bryant.edu/cgi/viewcontent.cgi?article=1000&context=honors_data_science#:~:text=The%20most%20common%20features%20used,rating%2C%20and%20true%20shooting%20percentage.)
* ["XGBoost and SHAP models in NBA game outcome predictions" by Ouyang, et al.](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0307478)
