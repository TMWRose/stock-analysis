# stock-analysis

## Overview

In this module, we are helping Steve's parents pick where to invest their money in renewable energy stocks. They hadn't done much research and wanted to invest all of their money into DAQO New Energy Corp. Steve instead wanted to help his parents diverify their investment portfolio, so we used VBA to analyze a whole list of green energy stocks to give them options. 

## Results

As you can see in the picture below, almost all of the top 12 companies analyzed had a great year in 2017, with DQ having the highest return. If you looked at just this year you might think that majority of these companies would be a safe investment.

![2017 results](https://user-images.githubusercontent.com/100237685/188791897-1ccb6c50-aca7-49fe-aa85-50e180074612.png)


However, in the following year, almost every company took a hit except for two. It's not readily apparent as to why the stocks all lost value, but a look into world events at the time might provide some insight. In the summer of 2017, President Trump removed the U.S. from the Paris Agreement, an international effort towards the fight against climate change. It wouldn't be hard to imagine that all renewable energy companies within the country lost a good bit of money from investors as not many would put money into an industry that seemingly had no future.

![2018 results](https://user-images.githubusercontent.com/100237685/188791914-7f641a0a-caeb-4ae0-9f7a-36466c923af0.png)


### Load Times

![VBA_Challenge_2017](https://user-images.githubusercontent.com/100237685/188791957-272bfb5c-218f-4b7e-9c68-e1ac22144949.png)

![VBA_Challenge_2018](https://user-images.githubusercontent.com/100237685/188791966-55e29f5e-a0b8-45fb-8623-9632b5a86954.png)



## Summary

### Pro v Con: Refactoring

Refactoring code can be beneficial for user experience as it makes the code run fast and reduces loading times. On the other hand, refactoring the code can also signifigantly lower the readbility of the code between programmers. That's why it's important to added comments to your code so that if you have to step away from a project for a period of time or share it with other programmers, the intent of each line of the code can be understood. 

### Pro v Con: Original Script

The original code was a lot simpler and easier to understand/program. It fulfilled the basic request of the job. However, it had slower loading times and left the interpretation of the results up to the user's ability to understand stocks.

### Pro v Con: Refactored Script

The refactored code is not only quicker but also easier to read from a user's perspective. The coloring of the positive and negative values plus the differentiation between years and more accurate measuring code provides an overall better experience for Steven's parents. On the other hand, refactoring the code makes it a lot harder to share the code with other programmers unless there are several comments added explaining what each line does.
