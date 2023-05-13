# TezKhuraak

According to Maslow, diet is a fundamental need but the existence of nearly-infinite recipes deplete the limited willpower in an era where we need it even more especially when preferences and restrictions are taken into consideration taking the limited local data into account

This is where Tez-Khurak comes in as a one-stop solution to all your daily meal-planning problem. 
Just tell us the meal you liked in the past, your favourite cuisine, the time or utensils you have at hand or your health choices and leave the job of deciding what you should eat to us.
If you are someone who does not cook for themselves, but others, we have got you covered, you can fine-tune the system based on your menu.

Based on the recipe input by the user, the recipes with the similar (Cosine) ingredients (TF-IDF Vectorization) are fetched (from the dataset) and those whose attributes (cuisine, course, preparation time, utensils, dietary preferences or restrictions) match the cases set by the user, a list of recommendations is generated (with their relevant attributes) and instructions.
“The list of recipes that are similar to the recipe you entered and meet the your preferences and restrictions”

## Tech-Stack

[![Python 3.x](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/downloads/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.2-blue)](https://scikit-learn.org/)
[![NumPy](https://img.shields.io/badge/numpy-1.20.3-blue)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/pandas-1.2.4-blue)](https://pandas.pydata.org/)

## Getting Started

### Prerequisites

- Python 3.x
- Scikit-learn
- NumPy
- Pandas

### Installation

1. Clone the repository
2. Install the required packages: `pip install -r requirements.txt`

### Usage

1. Run `python main.py` in your terminal
2. Enter the recipe name and your preferences and restrictions
3. The system will generate a list of recommendations along with their relevant attributes and instructions

### Contributing

1. Fork the project
2. Create your feature branch: `git checkout -b feature/new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/new-feature`
5. Submit a pull request

### License

This project is licensed under the MIT License.
