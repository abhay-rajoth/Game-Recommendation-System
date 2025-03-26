# Game Recommendation System

## Overview
This project implements a **game recommendation system** using **TF-IDF vectorization** and **cosine similarity**. It suggests games based on genres, tags, and descriptions, ensuring relevant and diverse recommendations. The system also evaluates recommendations using **genre match rate** and **diversity scores**.

## Features
- **TF-IDF Vectorization**: Converts text data (genres, tags, and descriptions) into numerical representations.
- **Cosine Similarity**: Measures game similarity based on text features.
- **Genre Match Rate**: Evaluates how well recommendations align with input genres.
- **Diversity Score**: Ensures varied recommendations.
- **Tested on 50,000 Games**: Accuracy was assessed by comparing results with external sources like **Mythic Map**.

## Dataset
The dataset used for this project contains **50,000 games** with their metadata. Due to its large size, it is hosted on Google Drive.

**Download the dataset here:** https://drive.google.com/file/d/11y_DfHYHpDP-_GhYVBx5i1dKGR6t-S32/view?usp=sharing)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/game-recommendation-system.git
   cd game-recommendation-system
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download and place the dataset in the project directory.

## Usage
1. Run the preprocessing script:
   ```bash
   python preprocess.py
   ```
2. Generate recommendations:
   ```bash
   python recommend.py --game "Game Title"
   ```

## Evaluation
The system was tested by comparing its recommendations with external sources. **Genre match rate** and **diversity scores** were calculated to assess recommendation quality.

## License
This project is licensed under the MIT License.

## Contact
For any queries, feel free to reach out or open an issue in the repository.
