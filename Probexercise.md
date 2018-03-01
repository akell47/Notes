1. Calculate the probability of flipping a balanced coin four times and getting each pattern: `HTTH`, `HHHH` and `TTHH`.

    The probability of H or T each toss is .5 or 50%. The tosses are independent so `.5*.5*.5*.5 = .0625` or `6.25%`.

2. If a list of people has 24 women and 21 men, then the probability of choosing a man from the list is 21/45. What is the probability of not choosing a man?

    21 men, total = 45.  No man = 45 - 21 = 24  
    `P(man) = 24/45`

3. The probability that Bernice will travel by plane sometime in the next year is 10%. The probability of a plane crash at any time is .005%. What is the probability that Bernice will be in a plane crash sometime in the next year?

    independent events  
    `P(plane crash` $ \bigcap $ `travel by plane) =  P(plane crash) * P(travel by plane) = (.01) * (.00005) = .000005` or `.0005%`

4. A data scientist wants to study the behavior of users on the company website. Each time a user clicks on a link on the website, there is a 5% chance that the user will be asked to complete a short survey about their behavior on the website. The data scientist uses the survey data to conclude that, on average, users spend 15 minutes surfing the company website before moving on to other things. What is wrong with this conclusion?

    Where did the 15 minutes of surfing time come from? From the survey or from the users web stats, like google analytics? Has to be from the user analytics stats is he/she only using user data from the ones that fill out the survey? Likely users that fill out a survey are by default spending more time on the page to fill out a survey.  Is the time spend on the survey totaled with the time spent on the website or counted differently?
