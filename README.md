# AIm_for_CheckMate

<h1 align="center">
  <p align="left">Project of Tactical Themes in games of chess</p>
  <img align="center" width="500" height="400" src="https://preview.redd.it/92we6q514qx61.jpg?width=5334&format=pjpg&auto=webp&v=enabled&s=e7850668255c3dd5298e2a1dc427d6bf94fc4543">
</h1>

# Proyect Chess - Themes

The objective is for an AI model to recognize and predict tactical motives from a game of chess.


# Approach

The aim of this project is to develop an AI model that predicts tactical motifs in a game of chess based on a sequence of positions or FEN (Forsyth–Edwards Notation) notation. The FEN sequences will be generated using the dataset provided by lichess, which includes FEN positions along with metadata and themes.

Project Outline:

    1. Data Collection: Obtain a large dataset from lichess that consists of FEN positions, metadata, and themes. This dataset will serve as the basis for training the AI model.
    2. Data Preprocessing: Clean and preprocess the dataset to remove any irrelevant or noisy data. Extract the FEN positions and their corresponding tactical motifs.
    3. Feature Engineering: Transform the FEN positions into meaningful features that can be used as input for the AI model. This may involve encoding the chessboard state, piece positions, and other relevant information.
    4. Model Development: Design and build an AI model, such as a deep learning neural network, capable of learning from the FEN sequences and predicting tactical motifs. Train the model using the preprocessed dataset.
    5. Model Evaluation: Assess the performance of the trained model by measuring its accuracy, precision, recall, and other relevant metrics. Fine-tune the model if necessary to improve its predictive capabilities.
    6. Deployment: Integrate the trained model into a user-friendly interface or application, allowing users to input a sequence of FEN positions and obtain predictions for tactical motifs in real-time.
    7. Testing and Validation: Validate the model's predictions by comparing them with known tactical motifs in a set of test positions. Conduct thorough testing to ensure the model's reliability and accuracy.
    8. Iterative Improvement: Continuously refine and improve the model based on user feedback, additional training data, or algorithmic enhancements.
    9. Documentation and Presentation: Document the entire project, including data collection, preprocessing, model development, and evaluation. Prepare a comprehensive report and presentation to communicate the project's findings and methodologies.

By creating an AI model that can accurately predict tactical motifs in chess games, this project aims to assist chess players in analyzing and improving their gameplay by providing insights and suggestions for strategic moves.

# :mechanical_arm:State of the Project
:construction:Project could be improved with fine-tuning or transfer learning from pre-trained models such as LCZero together with Stockfish:construction:

*We are always trying to innovate and improve our algorithms!*


## :hammer:Functionalities of the project

- `Functionality 1`: Implementing pattern recognition in a sequence of moves

- `Functionality 2`: Tactical theme classification system

- `Functionality 3`: 2 models - Machine Learning and Deep Learning

## 📁 Access to the project

*Download the contents of the public repository* >> https://github.com/RaulMuM/AIm_for_CheckMate

## 🛠️ Open and run the project

1. Create an environment specifically for this project. For example with conda
```
conda create -n nombreEntorno
```
2. Inside this environment it will be necessary to install all the libraries used, you can do it from file :
```
requirements.txt
```
3.From the terminal, go to the folder that contains the app files and from there run
```
python model_cnn_3D.py

python model_LGBMClassifier.py
```

# :wrench: Technologies used:

   - **Metodology Scrum:** Trello 
   - **Developement:** Git y GitHub, Jupyter, Visual Studio Code, LGBM, tockfish, lichess dataset
   - **Presentación:** Canva (https://www.canva.com/design/DAFZy34-Tb8/cIZek4UlllgtuwDvqkMtcQ/edit?utm_source=shareButton&utm_medium=email&utm_campaign=designshare) 

# Autors



## :mailbox:Contact us:

- Email: rodriguezppp@gmail.com ;
        sergio.rodrigo@hotmail.es ;
        bentocode0@gmail.com
