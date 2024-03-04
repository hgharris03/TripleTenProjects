# Computer Vision
The objective was to predict the age of customers buying alcohol from a store to determine if customers are old enough. The source dataset consisted of images of individuals and ages ranging from 1 year to 100 years. 

The first step was analyzing the data and understanding the spread of the data in the dataset. I used a histogram to see the distribution:

![image](https://github.com/hgharris03/TripleTenProjects/assets/106608681/7eb1c509-daeb-4695-8a5f-0fd8d7041202)

The distribution is right-skewed, with more pictures of people over 21. 

 - TensorFlow was used for the modeling.
 - Mean absolute error was the metric used to measure the accuracy of the models.

 The model was runand tested using GPU, below is the script run for the model:

 ![image](https://github.com/hgharris03/TripleTenProjects/assets/106608681/a1610623-fbd9-4944-aff5-58d7487f1207)

 - The training of the model resulted in a test MAE of 6.85.
 
This model would be sufficient to predict the age of a consumer. Despite the low error, this model could not substitute as a legal check for age but it would help flag customers who were around the legal age. As many stores are implementing more self-checkout lanes computer vision can help these lines run more efficiently without sacrificing the legal implications of selling alcohol to a minor. Computer vision has certainly increased in popularity and is now relied upon for everyday security for example on cell phones and laptops.
