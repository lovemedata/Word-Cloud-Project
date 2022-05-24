# Word-Cloud-Project
This gives an highlight of choosing the most numerous word.
Wordcloud project analyses of several word data as seen on my background picture.

In this Project, we will analyze a large collection of words to discover the highest trends.

The techniques used here to handle large amounts of data applied to other text datasets as well.

.txt extension is most preferred to be used

The dominant data used here is my name- Akon_Usoh

Familiarity with Python, pandas, wordcloud is required to complete this Project.

Steps involved includes;

1.Wordcloud is first enabled by opening Anaconda and inputting the below code;

conda install -c conda-forge- wordcloud

to run as this option will aid download wordcloud package. Alternatively, you could use

conda install -c https://lnkd.in/d--mAdtn wordcloud

While your anaconda page is still opened, open jupyter and import the necessary libraries(pandas and wordcloud) import pandas as pd import wordcloud
Load the file with the data(the said file was saved in local disk under machine learning folder. text= pd.read_csv('C:\Machine_learning\test.txt')
View the file uploaded data for reconfirmation text
Prepare the data for analysis a.Join the processed data together view = ' '.join(text['Data_Science']) b.Create a wordcloud object wordcloud = wordcloud.WordCloud() c.Generate a word cloud wordcloud.generate(view)
Use the word cloud to visualize the preprocessed text data in image form. wordcloud.to_image() It can be observed that the more dominant the word data, the larger it is.
N/B: Per run of the object gives a different view of the image, so for each time you wish to change view, always remember to import wordcloud.

The result of the project is embedded herein, on my profile picture and also on my Linkedin page- https://www.linkedin.com/in/akon-usoh-mba-a47925b4/
