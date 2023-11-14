# Sentiment Analysis (French tweet)

### Objectives
    1. Build a sentiment analysis model, that takes as input a comment, and predicts the sentiement behind it.
    2. To do so, I adopt the transfert learning approach.
    3. I used Bert as basemodel, the I add a layer with 64 units to finetune the model on my task.

### Life cycle of project
    1. Install the dependencies
    2. Collect data
        - Dataset source : Kaggle.
        - The dataset was stored in google drive.
    3. Data Analysis & Visualisation (more details in the notebook)
    4. Data preparation
        - Tokenization (Bert tokenizer).
        - Word embedding.
        - Generate training data (the format accepted by Bert model).
        - Divide the data into batches.
        - Split data into training and testing sets.

    5. Model building
        - Load the Bert model.
        - Build the model.
        - Create a customed earlystoping function (Stops the training 5 pochs after if the model accuracy is highe than 85% and under 95%) to avoid overfiting.
        - Start training the model.
        - Analyse the model performance.
    6. Prediction



### Software and tools requirements

    1. Github
    2. Jupyter or Google Colab
