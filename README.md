# simple-ai-chat-bot


PURPOSE -: 

The purpose of the chatbot is to serve as a simple conversational agent that can engage in text-based conversations with users. Specifically, this chatbot is designed to understand and respond to a set of predefined intents, which are categories of user input, and generate appropriate responses based on those intents. Here are some of the primary purposes this chatbot can serve:

Greeting and Engagement: The chatbot can respond to greetings from users and engage them in conversation, creating a friendly and interactive user experience.

Providing Information: It can answer questions about the items or products available for sale, accepted payment methods, and delivery times. This makes it suitable for use as a basic customer support or information retrieval tool.

Handling Expressions of Gratitude: The chatbot can recognize and respond to expressions of thanks, enhancing the user experience by being polite and responsive.

Entertainment: It can tell jokes or provide humorous responses when users request something funny. This can be used to entertain users and create a more enjoyable interaction.

Basic Natural Language Understanding: While simple, the chatbot demonstrates basic natural language understanding by associating user input with predefined intents. This allows it to respond contextually based on what the user says.



AI used -:


1> Natural Language Processing (NLP): NLP is a subfield of AI that deals with the interaction between computers and human languages. In this project, NLP techniques are used for tokenizing, stemming, and processing natural language text.

2>Neural Networks (NN): The project employs neural networks, specifically a feedforward neural network, to recognize patterns in user input and map them to predefined intents. The neural network is implemented using PyTorch.

3>Machine Learning (ML): The chatbot's model is trained using machine learning techniques. It learns from a dataset of labeled examples (patterns and corresponding intents) to make predictions about user input.

4>Text Classification: The main task of the chatbot is text classification. It classifies user input into one of the predefined intent categories (e.g., greetings, thanks, items, payments) using the neural network.

5>Data Preprocessing: Data preprocessing techniques are applied to clean and prepare the text data for training and prediction. This includes tokenization (splitting text into words or tokens), stemming (reducing words to their root forms), and building a bag-of-words representation.

6>PyTorch: PyTorch is a deep learning framework used for building and training neural networks. It provides the infrastructure for defining the neural network architecture, loss functions, and optimization.

7>Cross-Entropy Loss: The chatbot uses the cross-entropy loss function as a measure of the difference between predicted and actual intent labels during training. It is a common loss function for multiclass classification tasks.

8>Adam Optimizer: The Adam optimizer is used to update the model's parameters during the training process. It's an optimization algorithm that adapts the learning rate during training.

9>GPU (CUDA): The project checks for the availability of a GPU (CUDA) and utilizes it for faster training if one is available. This accelerates the neural network training process.






