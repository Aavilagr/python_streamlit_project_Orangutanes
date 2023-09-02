# Orangutan Behavior Study

## Overview

This project aims to assess the impact of caretaker interactions with a group of six captive orangutans (Pongo pygmaeus) from the Barcelona Zoo. The study focuses on observing orangutan behavior during different phases of interaction with a caregiver, including pre-game, game, and post-game phases.

## Table of Contents

- [Project Description](#project-description)
- [Setup](#setup)
- [Usage](#usage)
- [Data](#data)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Description

In this study, we conducted behavioral observations of a group of captive orangutans to understand how interactions with a caregiver affect their behavior. The project is divided into three phases of observation:

- **Pre-Game Phase:** During this phase, the caregiver was present, but no play was allowed.
  
- **Game Phase:** This phase involved thirty-minute playing sessions with the caregiver, during which the caregiver imitated distinctive behaviors displayed by orangutans during social play.

- **Post-Game Phase:** This phase served as a follow-up to ensure that the results of the playing sessions persisted.

The frequency and duration of observed social and individual behaviors were recorded during each phase.

## Setup

To set up and run this project locally, follow these steps:

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/your-repo.git

2. (Opcional) You can create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. Install project dependencies:

pip install -r requirements.txt

## Usage

To run the project, execute the following command:
streamlit run src/main.py

This will start the Streamlit app, and you can view it in your web browser by opening the provided URL.

## Data
Information about the dataset used in this project can be found in the data directory.
To understand better the behavior tags use this: 
Macro-behaviors:

["bra","cam","corr","tre"]),'macro_bhv'] = 'moving'
["sen","quad","tum"]),'macro_bhv'] = 'resting'
["alim","forr"]),'macro_bhv'] = 'feeding'
["groo","hur","ras","chup"]),'macro_bhv'] = 'grooming'
["jsol","jexp","jacrob"]),'macro_bhv'] = 'playing'
["ins"]),'macro_bhv'] = 'exploring'
["sex"]),'macro_bhv'] = 'sex'
["con","marc","huir"]),'macro_bhv'] = 'agonistic'
["lucha","perj"]),'macro_bhv'] = 'social-playing'
["pub"]),'macro_bhv'] = 'interacting with public'
["jun","aprox","trans","toca","solj","alogroo"]),'macro_bhv'] = 'social'

Positive behavior:
- Conductas lúdicas
- Lúdico-sociales
- Afiliativas

Individual behavior:
- Reposo 
- Locomoción
- Alimentación
- Higiene
- Conductas de exploración
  
Negative behavior:
- Agonísticas
- Interacción con el público

Sexuales

Previous study in gorillas:
https://www.zoobarcelona.cat/sites/default/files/2019-03/Proyecto%20Juego%20y%20Bienestar%20en%20Primates%20cautivos.pdf

## Results
The results of the orangutan behavior study can be found in the streamlit visualization. The therapy was efective in gorillas but sadly it was not in orangutans.



Mixed models:
    https://jbhender.github.io/Stats506/F18/GP/Group16.html
    https://www.pythonfordatascience.org/mixed-effects-regression-python/
    https://www.statsmodels.org/stable/mixed_linear.html
    https://www.kaggle.com/code/ojwatson/mixed-models
