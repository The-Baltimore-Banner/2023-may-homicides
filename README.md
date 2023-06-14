2023 Midyear Homicide Analysis
================
 - [Overview](#overview)
 - [Data](#data)
 - [Methodology](#method)
 - [Limitations](#limitations)
 - [License](#license)
 
 ## Overview
### Homicides in Baltimore down, part of a national trend

Baltimore is on track to reverse its most deadly trend. If the current pace of fatal shootings holds, it would be the first year since 2018 that the homicide rate went down, not up, and the first year since 2014 with fewer than 300 people killed in the city.

The promising development comes despite a [troubling and continuing rise in](https://www.thebaltimorebanner.com/data/teens-youth-gun-violence-baltimore-data-trends-7O6ZQUL4OVEMDLRYUM7IB2I3W4/) youth gun violence. The city is projected to end the year with 275 homicides, if trends continue, but a Baltimore Banner analysis found reasons to be cautious.

The decrease in homicides tracks with a [national downward trend](https://www.theatlantic.com/ideas/archive/2023/06/us-murder-rate-decline-crime-statistics/674290/) that is gaining notice from gun violence experts. But the lessening violence is not being felt evenly across the city, and there are recent years that started off on a promising trend, before a surge of summer-fueled shootings brought the numbers back up above 300 homicides.

Read the story: [Homicides are down in Baltimore. But gun violence data show reasons to be cautious](https://www.thebaltimorebanner.com/data/homicide-rate-baltimore-QH5MJLQLZFBCDNQGKVSI6KWD6M/)

<a id="method"></a>

## Methodology
### How we forecasted Baltimore homicides for the rest of the year

This analysis of Open Baltimore Part 1 crime victims database defines a homicide as one person who was killed. However, we mapped unique events that included homicides. In that case, we would map one event with multiple victims. Victims only included the number of people killed. A shooting even that led to two homicides and 3 gunshot victims would only list 2 victims.

The Baltimore Banner used an overaggressive integrated moving average (ARIMA) to forecast a model for 2023 homicides. We then compared the first 5 months of 2023 to that forecast. Overall, the actual count was 83% of the forecast. To predict the rest of 2023, we multiplied each amount forecasted for the month by 83%. 


<a id="limitations"></a>

## Limitations and reproductions
### 

There are known errors in the public Part 1 Crimes Database. The database is also frequently changing. Crimes that were once classified as homicides are often reclassified, making it difficult to recreate mid-year BPD reports at the end of the year. A slight variation is to be expected. 

This analysis relies on a version of the Part 1 Crimes Database that includes data through June 10, 2023. Using this code to analyze earlier or newer versions will likely return slightly different results.

Not every year in the database is reliable. In response to previous questions from The Banner, BPD admitted that shooting data before 2014 should not be relied on. They have never said why. Further analysis has led The Banner to question data in 2014 as well, leaving only the last seven years for analysis. 

The geocoded coordinates may not be exact locations. Some times appear to default to midnight.

Some entries list impossible ages such as negative numbers or very large numbers. The error is less common in shootings and homicides. There are 52 shooting victims who do not have an age listed or have a negative age. About half of these errors are from years before 2017. The number of ageless victims went up in 2022. 


<a id="license"></a>

## License

Copyright 2023, The Venetoulis Institute for Local Journalism

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

