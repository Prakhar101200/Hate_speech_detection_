#Twitter Hate Speech Detection
Overview
This project mainly aims to identify all the hateful and offensive comments on twitter using NLP (Natural Language Processing) methods. This project involves:- Importing the data, Cleaning and Preprocessing the dataset, Creating Vectors for the text and lastly creating a ML model to indentify the language tone of the tweets or the comments of the soical media.
In the times of social media, things have become more sensitive around people. There are lot's of hateful and racisits people, trying to spread out negativity, that affects people's mind and influence them in a wrong direction. 

Dataset
The dataset used in this project is stored in csv file naming 'twitter.csv'. It contains various parameters columns with 'class' and 'tweets' for each comments or tweets. But, before we go further in building this code, we will need to clean and preprocess the data.

Setup
Clone or download the project to your local machine.

Ensure you have Python 3.x version installed along with the neccessary libraries.

Install the required dependencies using: pip install -r requirements.txt

Run the Python script Hate_Speech_Detection_Model.ipynb to perform the function. 

Usage
The main usage of this model is to analyse the sentiments of the tweets and comments to help companies to maintain the positive environment of the social media platforms. This model mainly helps the social media companies to find and eliminate all the negativity from their platform.

The Script Hate_Speech_Detection_Model.ipynb performs tasks:-
1. Loads the dataset from the CSV file using pandas.
2. Creates a new column 'label' and drop all the un-neccessary columns to make our data more workable during the project. Also this was done to create cleanliness in the data so to make it easy to understand.
3. Cleans the tweets to eliminate hyperlinks, stopwords, special characters and non-ASCII characters.
4. Splitting the data and vectorizing  it.
5. Splitting the data into train and test parts
6. fitting the data into the model and printing the accuracy score with creating the prediction.
7. Lastly, creating a function for the user to enter their choice of text comment and letting the code to analyse and give the output of sentiment of the text input.

File Structure

Hate_Speech_Detection_Model.ipynb: Python script containing the main logic of the model.
README.MD: Documentation file providing an detailed overview of the project and instructions for usage.

Results 
The model gives out the outputs in the form of comment like if the comment input is - Hateful, Offensive or Neutral. 

Hardships Faced
While creating the model first tried to create it with the Multinomial NB algorithm. But face multiple errors. So, I went with with the Decision Tree model.

#Personal Reflection

Persistence and Learning: Despite the challenges, the project provided an opportunity to learn and grow as a coder. The perseverance to overcome obstacles ultimately led to successful results.

Room for Improvement: Acknowledging that there is always room for improvement, future iterations of the project can focus on refining the code and exploring additional techniques for further enhancing accuracy.

Contributions

Prakhar Raj Gupta

Acknowledgements I would like to acknowledge the numerous sources available over the internet that helped me throughout this project hardships.

Along with this, I would like to acknowledge "Miss Suchisita Mondal" for teaching me this concept in the class.

I would also like to appreciate 'Eduonix' for creating this Data Science Certification Module that enabled me to explore the world of Data Science and make myself more knowledgable in the concepts. .Lastly, I would like to appreciate myself for not giving up and fighting all obstacles on daily basis, whether its in coding or any other theoritical concepts or in life.

This project was inspired by the need to analyse sentiments of the language over social media using NLP techniques and machine leraning models.

Thanks to the Python community for developing and maintaining the libraries used in this project.

Thank you!
