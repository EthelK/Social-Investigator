# Social-Investigator
Investigates the presence of entities on social media 


The **Social Investigator** tool is a collection of multiple libraries and codes that creates, all together, a precise yet complete 
overview of an individual or entity on social media. 

This is a exploratory approach, there are a lot of things to be added and the objective is to find a creative and efficient way to 
depict sentiment and stats around the entity/person (and even more later). 

This process have different components: 

## **The Source** 
Which social media provide the right key to access usable and relevant information? 
Can we regroup information across social media platform and, if so, how could we create a consistant way to do it? 
_At this stage, the only social media used is Twitter_

## **The Collection** 
Two subcomponents here: 
  * How do we search for particular entities or persons? Is there a set of steps that we can create in advance to assure the consistency of our queries 
  * How do we store our the data once collected? 
  __at this stage, the data is collected through the Google Sheet API to get an idea of how the search work in real-time. A stream listener is in progress__ 
  
## **The Analysis - part I** 
Analysis can take into account stats about the entities but that's not the funniest part. I am moving towards network analysis but that 
would require a more important set collected --> Reason why the stream listener is prioritized at this stage. 

## **The Analysis - part II** 
Sentiment analysis and NLP: At this stage, two NLP libraries are applied to the tweets for comparison. They haven't been leveraged and 
there could be better libraries or way to apply this. 

## **The Predictions** 
How could we predict the reactions of social media depending on metadata/content/pattern? How could we define those reactions? Haven't been
prioritized yet. 

## **Ethics** 
This project also aims to understand the level of privacy those social media offers and how can we do these research above and respect 
the other entities and people connected to those? How can we rethink social media scraping? This is not a component on its own but a 
philosophy that will flow through the process of the Social Investigator 

