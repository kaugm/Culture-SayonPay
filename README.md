# Culture-SayonPay
Thesis for Msc Global Strategic Management

The .DOCX file is the final thesis\
The .PPT file is the thesis presentation

### How do Individualist and Collectivist Ideals Influence Investor Say-On-Pay Votes for Companies

Final thesis for M.S. Global Commerce and Msc Global Strategic Management. We collected data from a diverse group of MBA students and young investors from around the world and asked them to vote in a mock proxy vote regarding a CEO's compensation to discover if there was a relationship between the Individualism - Collectivism dimension (as part of Hofstede's 4 cultural dimensions) and perception of CEO pay (as execessive or not)

We used a simple javascript function that ran when users clicked the *take survey* button on a website we put up to randomly sort our respondant into 1 of 2 surveys on qualtrics (code is below). The surveys differed in the proxy vote scenario, as necessary for our statistical analysis.

        $ var urls = [
              "URL FOR QUALTRICS SURVEY ONE",
              "URL FOR QUALTRICS SURVEY TWO",
          ];

          function randomsort() {
              var url = urls[Math.floor(Math.random()*urls.length)];
              window.location = url; // redirect
          }

### Analysis Performed

Descriptive Statistics
Bivariate Correlation
Pearson Correlation
Chi-Squared Test
Logistic Regression (5 different models)


The remnants of the poorly coded website we used is here: [Thesis Website](https://github.com/kaugm/Thesis-Website)\


