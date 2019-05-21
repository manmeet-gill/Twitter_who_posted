# Twitter_who_posted
A machine learning project to identity the original owner of the post. This application analyses the tweets from the users to identify other posts form them.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites/ Dependencies
1. sklearn
2. twitter api package
3. twitter api keys, secret key
4. pandas
5. Numpy
6. re
7. datetime package
8. collections
9. textacy

## Installing
1. clone the repository
2. run the command
pip install -r requirements.txt
3. launch the jupyter notebook to make the code working

## Built With
Twitter - The web api package for social site Twitter
sklearn - machine learning tools
textacy - Used in Natural Language Processing(NLP) for data
Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

# Steps for code preparation
*import basic requirements
*initialize twitter keys and api
*get the userdata from twitter api providing the twitter handle
*used tweet miner code (miner.ipynb) to get tweet texts
*Create the training data
    1. Mine first person's tweets
    2. Create a tweet dataframe
    3. Mine Second person's tweets
    4. Append results to our dataframe
* find ngrams from text using tfidvectorizer
* Processing the tweets and building a model
    1. Vectorizing input text data.
    2. Intializing a model.
    3. Grid Searching for optimal hyperparameters.
    4. Training and fitting optimized model.
    5. Evaluating the performance of the model.


# Authors
Manmeet Gill (Initial work - Eleiken)
See also the list of contributors who participated in this project.

License
This project is  without a license, the default copyright laws apply, meaning that all rights are retained by the Owner to the source code and no one may reproduce, distribute, or create derivative works from this repository work.

Acknowledgments
some code help taken from elaiken
