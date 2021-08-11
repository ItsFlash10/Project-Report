<h2 align="center">Brand-Imaging using mining of Brand-related User Generated content on Social Networking Services using Textual and Visual data inputs </h1>

<h3 align="center"> Abstract </h1>

<p align="left"> This paper revolves around the approach to interpret data from Hashtags, Captions and Images of Social Networking Services to study brand related user generated content in order to gather insights of performance of brand related products using technologies involving emotion-sensing, image-classifcation, Label-clustering and mathematical indexing of output based on satisfaction levels of dierent products. product from images is combined with the sentiment calculated from hashtags and captions to and the satisfaction level of various products that the brand wishes to know the performance of. </p>

<h3 align="left"> Problem Statement </h1>
<p align="left">Brand Imaging through emotion-sensing and Integration of Textual and Image content of Brand-Related User-generated data on Social Networking Services.</p>

<h3 align="left"> Proposed Methodology </h3>

- We can see that Social Networking Services (SNS) are often flooded with Brand Related User Generated content, SNS has also come up to be a platform for Grievance sharing and redressal and therefore mixed views on all products are coming up giving a fair share of representation to all kinds of ideologies

- We use this opportunity to find all relevant posts in a given timeframe from Instagram through relevant hashtags making direct association with the brand, for example in our program we use hashtags like #McD and #McDonaldsIndia and scrap most recent posts with these hashtags. The posts are scrapped using my.apify.com

- We then store the Caption, Image, and Hashtags separately to be analyzed together. 

- As explained in the Literature survey about captions presenting the true emotion of statements in given posts, we run dynamic emotional sensing on the caption by finding all hot and relevant keywords. The generated emotion is categorized in polarity points of Positive Neutral and Negative.

- Once the sentiment pertaining to all the captions has been found out we set on to the next task that is classification and clustering of different labels that the image carries. We run our model to find all the relevant labels that the image contains. We make a broad set of Labels or the main labels that are actually the products on which the brand wants image interpretation, for example in this we have found out all associated labels to main labels like Ice Cream, Crispy Chicken, Coffee, Sandwich, Burger, Salad, mocktail, and Pizza. There are a plethora of association labels that are excavated from the image classification and then clustered or mapped to the relevant label as given.

- Once the labels have been identified, we project those labels to the field that contains the actual sentiment value associated to the post containing the image from which the labels have been dug out. The labels are then given the index score of Positive, Neutral, or Negative as ascertained from the captions. 

- Once the mapping is complete we find the aggregate resultant of all the labels and posts that were taken as input. The aggregate result through statistical measure is then attributed to map whether the public sentiment relating to the specific target label is positive and what is the associated confidence of the particular product.  

- The final result is shown in a tabulated form with all intermediary and final outputs including positive cases, negative cases, etc. This is further made more visually appealing by fixing the color gradient with respect to the confidence generated.  

<h3 align="left"> Hardware and Software Requirements </h3>

**Hardware** - Computer System, GPU.
<br />
**Libraries Used** - Pandas, re, string, NumPy, textblob, preprocessor, nltk, stopwords, vaderSentiment, google.cloud, google.cloud.vision, urllib.request
<br />
**API Required** - Google Cloud Vision API
<br />
**Software** - Spyder (Python 3.7), Anaconda Enviroment.
<br />
