---
Title: "COVID-19 Vaccine Hesitancy on Social Media: Building a Public Twitter Data Set of Antivaccine Content, Vaccine Misinformation, and Conspiracies"
Date: 17.11.2021
Authors: 
Keywords: 
References: 42
Citations: 182 (03.11.2024)
Correspondence: 
Abstract: 
Completed: 
Extras: 
Journal/Q index: Q1, https://www.scimagojr.com/journalsearch.php?q=21101030810&tip=sid&clean=0
URL: https://publichealth.jmir.org/2021/11/e30642
Dataset: AvaxTweets https://github.com/gmuric/avax-tweets-dataset
---
Identifying Low- and High-Credibility Media Sources We leveraged urllib, the Python URL handling module, to parse the URLs found in the data set. Each URL was broken into several components, including the addressing scheme, network location, and path. A third-party data set that contains the domains associated with websites that share misinformation was used as a ground truth to tag the domain names [20]. For URLs that were not in the data set, we queried the Media Bias/Fact Check website [21] for further identification. Because URL shortening services such as Bitly [22] are widely used on Twitter, shortened URLs appeared frequently. We used urlExpander [23] to expand the shortened URLs and retrieve the full URLs where possible. Domain names of popular news aggregators and social networks such as Twitter, Facebook, Instagram, Periscope, and YouTube were ignored in the analysis.
In Figure 4, we list the top 10 URLs that can be found in the streaming collection, and we illustrate the number of times each appears. The vast majority of those websites can be found in the Iffy+ database of low credibility sites [20].

### Extras: 
### Problem: 
### Results: 
### Achieved: 
### Dataset:


