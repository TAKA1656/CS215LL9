# CS215LL9
### Project Ideas

- Look at canvas data and find correlations we can find from the outputted data. Check my usage of AI such as ChatGPT, Gemini.
  - Questions that may be answered
    - How would AI usage affect my academic activities?
    - What subject actually got helped by the usage of AI?
  
- Get a dataset of US economic growth, both nominal and real, and find a factor that actually affect it by taking various inputs such as interest rates, tax revenue, amount of invested, fiscal and monetary policy data, imports, exports, savings, consumption.
  - Questions that may be answered
    - What economic factor in the US has a big impact on the economic growth?
    - Are there any ways to forecast the change in economic conditions by observing a change in each variable?

- Look at an engineering career path dataset, preferably that categorizes students with majors, and have career paths, income, employment rates, etc.
  - Questions that may be answered
    - What career path is the most successful for each major?
    - Is it actually better to get a post graduate degree?
      
### Week 10 Update
 - I will work on my own
 - I am thinking of working with economic data and explore the tendency of variables over time
 - I will likely use the FRED data, because it is the most reliable, the pro is that there are so many data that I can explore, the con I can think of is that there might be empty datapoints which might cause a problem.
 - Questions that can be answered
   - What boosts the investments in the US?
   - How do interest rates act in reaction to a change in economic variables?
   - Building off the idea of forecasting the economy, is there any ways to create a formula to find the future status given the present data
- Some stuff I might have to figure out
  - What specific data do I want to look into? (Because I have so many options to explore.)
  - How can I model something not only graphically but also mathematically in python?
  - What kind of visualizations should I create to make it clear for those who see the project?
    
### Week 11 Update
 - I decided to work with the FRED database, quarterly real GDP. I think the real GDP is the best quantity to know how the living standards in the US has changed over time. I will combine this with potentially population growth, nominal GDP, price level, and net exports, etc. This data is a public data, since it is collected by Federal Reserve Bank of St.Louis. The data collection was probably funded by them, and also conducted by them. They don't identify any subpopulations, and the data itself looks very neutral. Discovering how the data was collected might give us an idea of how this dataset might be biased. 
 - I just went to the FRED database and downloaded it as a csv file online. If I were to do more detailed analysis that requires me to pull more specific data, I would use the API and give more descriptive information in the data collecting process.
 - I used the population growth data to calculate the real GDP per capita, and found that the living standards actually rose by a lot since 1950. 
 - The cleaning / wrangling I had to do in the analysis above was to adjust the population data frequency to that of the real GDP data. I could only find the yearly population data, so I had to repeat the same number four times for each year in the population data.
 - A potential challenge is that the research is going to be a general and boring one unless I make my own economic logic and test it. I will try to think of an interesting question to ask, so I can make the research process fun and meaningful. Another challenge I think I might struggle with are the units, since GDP are going to be in dollars while if I look at GDP in different countries, they will be measuring them in different currencies. To avoid the confusion, I think I will need to know exactly what each number shown in the dataset means, and make sure I take the units into account to make a mathematical hypothesis.

### Week 12 Update
 - <iframe
  src="Alaska_destinations_delays.html"
  width="100%"
  height="600"
  frameborder="0">
</iframe>
