# ImageCaptioning

Flow of project :-

## Extract image features
Will be using inception v3 model to form image embeddings which will be fed into RNN for predictions.

## Data preprocessing - Captions and images
1. Generate a Vocabulary - Vocabulary is list of all the words with occurances >= n (some number) and every word is given a number.
2. Using these word to number maping in vocabulary , we will convert tokens to indices (Formating the sentences)
3. Padding every sentence to fix size

## Training

[Images Features] - RNN 

TO DO LIST - 
1. LSTM implementation.
2. Training
3. Validation.






