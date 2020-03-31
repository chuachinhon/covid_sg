#  Covid-19: Analysis and Visual Notes From Singapore

This is an ongoing series of notebooks and datasets looking at various aspects of the Covid-19 outbreak in Singapore. While many data analysts are focusing on the global outbreak, or on bigger countries, I chose to go deep in just one country.

The sections are arranged in reverse chronoglogy, with the most recent one upfront.

---
---

# II. The Second Covid-19 Wave In Singapore

![](https://miro.medium.com/max/4800/1*wJDgaTUgz3cVeKA49DhPZQ.jpeg)

Singapore’s battle against the novel coronavirus entered a new phase around March 10, when the number of imported cases began to spike sharply. The city-state’s experience could be a canary in the coal mine for other countries still grappling with the first phase of the outbreak.

Fuller background in my Medium post [here](https://medium.com/@chinhonchua/covid-19-the-second-wave-in-singapore-91e886b3d444).

---

## 1. DATA SOURCE
This [dataset](https://github.com/chuachinhon/covid_sg/blob/master/data/covidsg_2ndwave.csv) covers 732 confirmed cases (415 imported, 317 local) announced by the Singapore authorities between January 23 and March 27. Data for the charts were compiled from daily Covid-19 updates on the health ministry’s [website](https://www.moh.gov.sg/news-highlights/).

![](https://miro.medium.com/max/1400/1*ynziY1C0Nh2ZDn_uNw4Esg.jpeg)


## 2. NOTEBOOK
Through a series of charts in this [notebook](https://github.com/chuachinhon/covid_sg/blob/master/notebooks/2.0_covidsg_2nd_wave_cch.ipynb), I try to examine the inflection point between the First and Second Wave of the Covid-19 outbreak in Singapore, and see where they differ.

I used Flourish Studio's survey template for a quick breakdown of key demographic data in the two phases. You can access the first interactive chart [here](https://public.flourish.studio/visualisation/1732543/), and the second one [here](https://public.flourish.studio/visualisation/1722034/).


![](https://miro.medium.com/max/2000/1*Slu3_Rf9TAOA68LdOJSHyA.jpeg)

---
---
#  I. Visual Notes From Singapore’s First 100 Fully Recovered Covid-19 Patients

![](https://miro.medium.com/max/7674/1*OXrvgbMbeR165fPlybBbfg.jpeg)

How long does it take to be certain that you’ve been infected with Covid-19? And if indeed infected, how long would it take for you to be free of the novel coronavirus? These are tough questions to answer conclusively, but here’s what the first 100 fully recovered cases in Singapore can tell us.

Fuller background in my Medium post [here](https://towardsdatascience.com/visual-notes-from-singapores-first-100-fully-recovered-covid-19-patients-aad7f2e1d0a0).

---

## 1. DATA SOURCE
I assembled the [dataset](https://github.com/chuachinhon/covid_sg/blob/master/data/covid100_recovered.csv) for the first 100 fully recovered cases manually from daily press releases issued by [Singapore’s Health Ministry](https://www.moh.gov.sg/news-highlights/). 

![](https://miro.medium.com/max/3020/1*_15c6rT77DJVn1mTGC38Rw.jpeg)




## 2. DEFINITIONS

The two definitions used in this post are unfortunately clunky, but I opted to be as unambiguous as possible so that we are focused on what the limited public data actually says, instead of going down the slippery road of over-interpreting what we think the data is saying.

### DEFINITION #1: Confirmation-Discharge Window
In this post, I’ll use the term “confirmation-discharge window” as a shorthand for the number of days between a patient’s Covid-19 infection confirmation date, and his/her official discharge date, as announced by the Singapore health ministry. These dates are matters of public record and are not in dispute.

![](https://miro.medium.com/max/3840/1*W1T_7KZxsJnPi56Beq25RA.png)



### DEFINITION #2: Symptoms-Confirmation Window
The pre-confirmation phase is tricky territory given the global disparity in access to medical facilities and Covid-19 test kits. To avoid over-complicating matters, I’ll use a straightforward definition of the pre-confirmation phase as the “symptoms-confirmation window”, ie, the number of days between the reported onset of symptoms and official confirmation of Covid-19 infection.

![](https://miro.medium.com/max/3804/1*yVtCVELokClYZJF3FM9E-w.png)


## 3. DEMOGRAPHIC BREAKDOWN OF SINGAPORE’S FIRST 100 FULLY RECOVERED PATIENTS

![](https://miro.medium.com/max/3528/1*b05W_WTwl68sxUAPK-NPEA.jpeg)

I don’t intend to duplicate the excellent Covid-19 dashboards already out there. But some charts broken down along demographic lines would still be useful for the analysis in this post. For this, I created an interactive chart on Flourish that can get the job done quickly. You can access it [here](https://public.flourish.studio/visualisation/1506209/).

## 4. NOTEBOOK

Through a series of boxplots, frequency distribution charts, and Gantt charts, I try to address questions surrounding the confirmation-discharge and symptoms-confirmation windows. The detailed notebook is [here](https://github.com/chuachinhon/covid_sg/blob/master/notebooks/1.0_covid100_recovered_cch.ipynb). 

![](https://miro.medium.com/max/3644/1*0ivjSdCInexwIDxeU-s56A.jpeg)


This is not a medical study, obviously, and I’m not an epidemiologist. But I have taken extra care to use labels/definitions that are clear, unambiguous and non-alarmist.

My goal here is to try to present the underlying trends in the public data in a manner that is clear and easy to understand, while being upfront with the limits of the dataset and my lack of domain expertise.

Singapore has won praise for its early handling of the Covid-19 outbreak, but signs are that this early success inadvertently bred complacency among some residents. At a time when the outbreak has gone global, this sense of complacency would prove costly given Singapore’s high population density.

From my past experience as a journalist, most people tune out when you try to engage them on “big picture” explanations. But they may pay a little bit more attention if the impact on their personal wellbeing is spelt out more clearly.

This is what I hope to achieve with this post.