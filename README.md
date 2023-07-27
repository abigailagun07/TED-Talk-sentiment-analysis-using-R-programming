# TED Talks sentiment analysis using R-programming.
This project performs text analysis on transcripts from two TED talks - "Embrace the Shake" by Phil Hansen and "Robots that Fly...and Cooperate" by Vijay Kumar. The analysis compares the topics, ideas, context, and emotions conveyed in the two speeches using R programming.

## About the Speeches

- Phil Hansen's 2013 talk "Embrace the Shake" discusses how he overcame limitations and transformed challenges into creative possibilities after being diagnosed with nerve damage. He encourages the audience to embrace challenges and limitations to find new creative outlets.

- Vijay Kumar's 2012 talk "Robots that Fly...and Cooperate" discusses the challenges of building agile robots and the involved technologies. He highlights how his robots can revolutionise society through applications like search and rescue, and construction.


## Analysis Methods 
The analysis utilised the following R packages:
- tidyverse - for data manipulation and visualisation
- tidytext - for text mining and analysis 
- ggplot2 - for data visualisation
- knitr - for reproducible reporting

The workflow included:
- Data cleaning: Lowercasing text, removing punctuations, numbers, whitespace
- Tokenization into words 
- Removing stop words
- Word frequency analysis
- Sentiment analysis using Bing and NRC emotion lexicons
- Visualisations with bar plots and scatterplots


## Key Findings
- Vijay Kumar used more words overall but both speakers' frequent words related to their respective fields 
- Phil Hansen had more negative sentiment words while Vijay Kumar had more positive sentiments
- Different emotions like trust, fear, anticipation, and surprise were associated with each speaker


## Limitations
- Analysis was purely text-based without considering tone, delivery, visuals etc. 
- Lexicons have limitations in capturing context and meaning


## Future Work 
- Incorporate audio, video, and visual elements of talks for analysis
- Perform comparative analysis across more TED talks


## References
Kumar, Vijay. “Robots That Fly ... and Cooperate | Vijay Kumar.” TED, https://www.ted.com/talks/vijay_kumar_robots_that_fly_and_cooperate 
Hansen, Phil. “Embrace the Shake | Phil Hansen.” TED, https://www.ted.com/talks/phil_hansen_embrace_the_shake
