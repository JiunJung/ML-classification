# Classificarion using K-nearest neighbors algorithm

There are two classes of data. Bream and smelt. <br/>

And they have length data and weight data.<br/>

Using KNeighborsClassifier in Kscikit-learn, we can train the machine using K-nearest neighbors model. <br/>

---------------------

## Result


![Result image](/images/result_image.jpg)

- Circle and diamond data are the data for training.

- Triangle data is a new fish to guess.

- K-nearest neighbors model found nearest 5 data. (diamond shaped data)

- You can see the result of prediction in your terminal.<br/>
  (1 : Bream, 0 : Smelt) <br/>

  Result :
      
      [1.]

-----------------------
## How to use this repo

- You have to install python and pip. <br/>
  Install python : <https://www.python.org/downloads/>

- Install pipenv if you don't have.

      pip install pipenv

- After you clone this repo, you have to install dependencies.

      pipenv install

- To run the main file, 
      
      pipenv run python main.py