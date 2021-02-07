# Cov-Misinfo-Tracker
#uOttawaHacks 2021

Collaborators: Aziz Uddin, Ryan Walsh, Adithya Shankar 

## Who are we?

We are Cov-Misinfo Tracker and we are a team of biomedical engineers eager to solve the world's next challenging problem with the power of Google Cloud and Twitter. 

## What is the problem?

Due to the ever-present and rising hysteria about the on-going pandemic, misinformation about COVID-19 can be found spreading like wildfire through social media. This becomes a problem for most people as they are dependent on various forms of social media for their daily pandemic updates. 

## What is our solution?

Our proposed solution is a system that would analyze tweets based on queries typically used in non-factual COVID-19 related statements to determine the key words typically used in non-factual COVID-19 statements and categorize them based on how often they occur in non-factual statements. We focused on using Twitter as the primary social media platform since it focuses on key words and allows people to post to a wider audience than other channels. Moreover, Twitter has been successfully used in prior research on blogs, images and textual information   

## How is it done?

Using the diverse functionalities and API's available through the Google Cloud Platform as well as the Twint tool to scrape through desired tweets, we are able to create an application that can be used as a means of understanding as well as education. We used the Twint tool to query and extract specific tweets, to be stored temporarily in Firebase. Using the Natural Language processing API we will be able to extract pertinent information from the stored tweets and store the analyzed extractions in a readable format back to our Firebase. Firebase will store that information and parse through that information and will interact with the Cov-Misinfo platform where it will display the results to the user.



