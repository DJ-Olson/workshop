# Methodology

## Introduction:

Rio is a growing city with over 6 million residents, however, more than 25% of the city lives below the poverty line, surviving on an average family income of $5.50 per day. To understand why a developing city with so much urbanization and economic potential also has so many residents struggling to make ends meet, it is important to look at how the city's regions are broken down. Rio’s population is severely segregated, with massive divides between rich and poor regions prohibiting some communities from properly developing as much of the city continues to advance. 

Integrating Rio’s communities is no easy task, however, I believe one effective way to start is through a socioeconomic analysis of each region, specifically focusing on the poorer regions known as the Favelas. In doing so, this will allow for the city of Rio and the Brazilian government to properly allocate resources to the regions most in need. It is important not to simply throw money at poorer regions, but instead identify the exact causes of economic stagnation, and address them. If we can understand why a region is economically struggling by specifically identifying the region's setbacks, money can be most effectively spent, and this will accelerate the pursuit of economic equality within the city.

## Inquiry Type:
	
In order to carry out this socioeconomic analysis I will use explanatory inquiry. The best way to understand why Rio is so segregated is by identifying the causes and effects of economic inequalities, and this is what explanatory inquiry sets out to do. To understand how to help regions, we need to understand what hurt them in the first place. We must learn from the city’s economic history to strive for a better future.

## Basic City Overview:

Before we breakdown the two methodologies I believe will most effectively analyze Rio’s socioeconomic status, it is important to have an image of what the problem looks like. Below is a map of the city of Rio, with the regions separated and categorized by average GDP per capita. It shows how Rio has developed economically from 1950-2010, but also shows how this development has not been equal among the regions. The Favelas (located in northern and central Rio) show very little progress, whereas the most urbanized parts of the city along the coast have continued to economically advance. 

![Screen Shot 2020-04-19 at 10 13 09 PM](https://user-images.githubusercontent.com/60228369/79708619-e871e780-828d-11ea-90f7-a6255cd83e28.png)

## Methodology 1 - Agent Based Simulations:

The first geospatial model we will discuss is Flavia Feitosa’s MASUS simulations. MASUS stands for multi-agent simulator for urban segregation, and it is used to predict the effects of population dispersal within cities and regions. In Flavia’s words, it is “a tool to explore alternatives for promoting inclusive cities.” Flavia’s work was done using the Brazilian city São José dos Campos, located to the West of Rio. The similarities between Rio and São José dos Campos makes Flavia’s work applicable to Rio. Creating an economically “inclusive city”, is exactly what Rio needs to ensure all of its regions develop. 

Flavia created and tested MASUS using a three step approach, each one consisting of an experiment that built off the previous. 

> The first experiment compares simulated outputs that replicate a past segregation scenario in the city with empirical data, and tests whether the model can provide an adequate representation of segregation patterns as observed in São José dos Campos. The aim of the second experiment is to demonstrate how MASUS can be used to test theoretical issues of segregation, exploring the relationship between income inequalities, and the configuration of segregation patterns. The third experiment demonstrates the ability of MASUS to provide insights regarding the impact of social-mix policies.

In essence, the first experiment was a test to make sure MASUS worked, the second proved that economic inequality does lead to segregated communities, and the third tested its capabilities to predict future scenarios using different independent variables and explain certain outcomes.

How MASUS actually works is by creating decision trees for theoretical agents within an Urban population model for the city being tested. Models use a set of equations to calculate a Monte Carlo simulation to identify agents' probability of making each possible decision. The simulation then identifies all possible effects by simulating all possible outcomes of certain decisions, and calculates each possible outcome’s likelihood of actually occurring. 

One can also set up a MASUS model with a certain outcome predetermined in order to predict what decisions need to be made to achieve the chosen outcome. Flavia identified that economic inequality leads to segregation in São José dos Campos. Thus, a good MASUS model to use in Rio would be one with the goal of decreasing segregation. When running this model in Rio you could monitor if economic equality increases as segregation decreases. If this is the case, then you can go back to the decision tree and see what choices agents made in order to decrease segregation to see what methods of desegregation are most highly correlated with economic equality. This would help Rio’s government implement the most effective anti-segregation policies that would integrate and economically balance the city’s regions.

### Examples of a MASUS agent decision tree and how the agent is integrated into the larger model are shown below:
![Screen Shot 2020-04-19 at 10 30 00 PM](https://user-images.githubusercontent.com/60228369/79708695-253dde80-828e-11ea-884a-6105f08ca42b.png)

![Screen Shot 2020-04-19 at 10 29 48 PM](https://user-images.githubusercontent.com/60228369/79708697-266f0b80-828e-11ea-8b90-516582c9f542.png)


## Methodology 2 - Administrative territorial unit models to rate and monitor development levels of urban areas:

The second methodology I have chosen is from a study conducted in Russia. It looked at ways for the government to monitor the socioeconomic development of urban areas. This study was done with the purpose of figuring out how to improve real estate value in certain areas to increase investor interest within these regions. However, I believe the method can be tweaked to help reach our goal of economic equality Rio. 
 	
The way this study was done was by surveying different regions of Russian cities, in order to provide a rating of socioeconomic development within these urban areas. Regions are broken down into Administrative Territorial Units (ATU’s) which are then subdivided further to create a hierarchy of local indicators. Thus, the models are able to provide explanatory indicators starting from a local level that scale up to encapsulate the region as a whole. Essentially the model uses a bottom up approach in order to show causes and effects of different variables at the local level, in order to piece together the more complex system that is the region as a whole. 

### Below is a functional model of area assessment, which explains how an ATU rating is given. A basic breakdown of how a tree like this is assembled is also provided.
![Screen Shot 2020-04-19 at 9 33 01 PM](https://user-images.githubusercontent.com/60228369/79708821-836ac180-828e-11ea-83db-b489d086f903.png)


### How this method could be applied in Rio:

Essentially what the study in Russia did was show how to optimally manage an administrative-territorial unit. What if instead of being used to increase real estate value, the data was used to optimally manage factors that contribute to economic prosperity. Models of regions within Rio could be created to seperate the city into different ATU’s. You could then select different local indicators that are believed to most greatly contribute to economic prosperity, and compare these indicators between ATU’s of different economic status. These models would help explain what economic factors on the local level are most greatly correlated with regional inequality, and thus, make it easier to assess what measures need to be taken. Instead of starting massive city-wide initiatives, each region could be allocated money to spend on what the data reflected would be most effective in increasing socioeconomic prosperity. Hopefully, this would in turn increase widespread equality within Rio. 

## Discussion:

Both methodologies have the potential to work if applied to Rio. However, no one method is going to provide the answer to creating widespread equality in Rio. All we can hope is that they help discover a piece to the complex puzzle. It is important to recognize that each one has its potential drawbacks. One gap in the literature I can identify in Flavia’s agent based simulations is correctly estimating the probabilities necessary to create agent decision trees. While her statistical equations made sense, it does not seem likely that you could ever have a model that would correctly determine decision probabilities for all cities. Her work may have been proven accurate in the city in which she created the decision trees. However, it does not seem probable that decision probabilities will remain constant as you change location or as time passes and people evolve. Thus I would have liked it if she discussed how you can change and create new probabilities to ensure that the MASUS model will accurately assess the region it is being used in. 

Additionally, in the Russian study I would have liked to have had a more in depth explanation of how local indicators were chosen. I think that there needs to be further testing done to provide a method for choosing local indicators for a specific region. The local indicators used in the study may have been good for assessing the socioeconomic status of Russian regions, however, I assume the indicators necessary will change as the location of the assessment changes. 

In closing, I believe that both of these methods will provide valuable insights into how to help Rio desegregate its regions by increasing socioeconomic equality. But, I wanted to be sure that it is recognized that much of this paper is theoretical. No assumptions can be confirmed until  these data science methods are actually tested in Rio. 

## Bibliography: 
1) Image 1 URL (can’t login to actually website to properly cite): https://www.researchgate.net/figure/Evolution-of-decennial-GDP-per-capita-in-the-Rio-de-Janeiro-State-municipalities-from_fig1_323100644

2) Feitosa, Flávia F., et al. “Multi-Agent Simulator for Urban Segregation (MASUS): A Tool to Explore Alternatives for Promoting Inclusive Cities.” Computers, Environment and Urban Systems, Pergamon, 3 July 2010, www.sciencedirect.com/science/article/pii/S0198971510000608.

3) AIP Conference Proceedings 1800, 050015 (2017). From:  https://doi.org/10.1063/1.4973075
