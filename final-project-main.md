[Back to Home](https://sarahpearman.github.io/data-stories/)

---

# Smart speakers & privacy choices

## Summary

This page summarizes my work on my final project for Telling Stories with Data, Spring 2020. I use existing data to describe users' attitudes towards smart speakers, especially what we know about their privacy concerns, and I also describe data I collected from these devices and their accompanying smartphone apps to assess the usability of their privacy controls.

In short: these devices are increasingly popular, but people are also increasingly worried about their privacy implications, and there's a lot of room for improvement on the usability of their privacy controls!

## Table of contents

[Part 1](https://github.com/sarahpearman/data-stories/blob/master/final-project-main.md#part-1)

[Part 2](https://github.com/sarahpearman/data-stories/blob/master/final-project-main.md#part-2)

[Part 3](https://github.com/sarahpearman/data-stories/blob/master/final-project-main.md#part-2)
* [Links to final deliverables](https://github.com/sarahpearman/data-stories/blob/master/final-project-main.md#final-deliverable)
* [Intended audience](https://github.com/sarahpearman/data-stories/blob/master/final-project-main.md#intended-audience)
* [Design process](https://github.com/sarahpearman/data-stories/blob/master/final-project-main.md#design-process-for-final-story)
* [Final reference list](https://github.com/sarahpearman/data-stories/blob/master/final-project-main.md#references)
* [Other notes](https://github.com/sarahpearman/data-stories/blob/master/final-project-main.md#other-notes)

---

## Part 1

For Part 1, I knew I wanted to work on the general topic of smart speakers and privacy, but I wasn't sure exactly what the story was or what data I would use. I knew Pew Research data would be useful because it's some of the largest-scale data available, even if it's based on mostly a few high-level questions. I sketched some ideas of how I would tell a story with the 2017 and 2019 Pew data and with some data points from published academic papers. I wasn't satisfied with this story--it felt like just the introduction to a story--but I wasn't sure what data I would use, since part of the problem I'm trying to portray here is that we don't have enough data yet to fully understand this problem.

For more information about Part 1, visit [the Part 1 page](https://sarahpearman.github.io/data-stories/final-project-part1.html).

## Part 2

At some point in brainstorming for Part 2, I realized that I could tell a more interesting story if I collected some data on my own. I collected data from asking my own smart speakers privacy-related questions, and I also explored their corresponding apps and gathered metrics on how difficult it was to find privacy settings in the apps as well as how complex the language in the settings was.

For the last chart, I originally envisioned some kind of matrix to show how hard it was to access settings plotted against the readability metrics. (Actually, I was completely stuck on what data to add to this project to proceed with Part 2, and then that matrix popped into my head when I was out on a run one day, and I had to stop on a street corner and email myself the idea so I didn't forget—-it's funny how that works.) I quickly realized that the matrix didn't actually make sense, especially given that all of the data points would be in the "performed poorly on both metrics" quadrant anyway, but I liked the idea of finding two metrics to show how easy or hard it was to work with the privacy settings for each voice assistant, so I iterated until finding a way to do that. This chart will hopefully be an interesting proof-of-concept for additional research in this space.

I then built a wireframe of a story with the data from Part 1 plus the data I collected in Part 2. I tested that wireframe with three users--one expert user with a background similar to mine, one user who is not an expert in technology or privacy but who has more visual design background than I do, and one general-audience user. I iterated based on their feedback and arrived at a final wireframe.

For more information about Part 2, visit [the Part 2 page](https://sarahpearman.github.io/data-stories/final-project-part2.html).
 
## Part 3

### Final deliverable

I used my final wireframe to build various charts in Tableau, and I presented a story using those charts in Shorthand. I also added pieces of supporting information from a number of sources along the way.

* Data stories:
  * Abridged presentation version: [https://carnegiemellon.shorthandstories.com/smartSpeakerPrivacy-presentationVersion/index.html](https://carnegiemellon.shorthandstories.com/smartSpeakerPrivacy-presentationVersion/index.html)
  * Full version: [https://carnegiemellon.shorthandstories.com/smartSpeakerPrivacy/index.html](https://carnegiemellon.shorthandstories.com/smartSpeakerPrivacy/index.html)
* Github repository: [https://github.com/sarahpearman/data-stories](https://github.com/sarahpearman/data-stories)

### Intended audience

I wanted this story to be accessible and compelling for multiple audiences. Since I knew I would be presenting it in this class, I wanted to give enough background that it would make sense to someone with experience with data and charts but without a great deal of technical knowledge or experience with information privacy issues. However, I also wanted it to offer information that would be of interest to someone who was familiar with the research in this area, since I would like to use this as a starting point for pitching more research on this topic (and potentially applying for more funding for such research).

To make it accessible to a more general audience, I included the "brief history of voice assistants" section, which wouldn't really be necessary for an audience in my field, where it's generally accepted that voice assistants and Internet of Things devices are a growing and important space. I also discussed and included photos of some of the most popular smart speakers in case people were not as familiar with this category of products. This is also important since the terms people use for these products are often conflated. For example, the Amazon device is an Echo, and the underlying voice tech is Alexa, but people often use the terms interchangeably. This is fine in most contexts, but here it was necessary to try to disambiguate them to talk about some of the specifics of the applications of these devices on smart speakers.

I wanted to make everything accessible for a general audience, but I wanted the story to still show an expert audience what this problem space is and what further research is needed. The data on this topic is pretty limited in the academic world. We have some NPR and Pew data that is very high-level, and we also have a small number of studies with qualitative sample sizes. This can make it difficult to demonstrate what the problem space is. I tried to use the existing data to lay the groundwork as well as I could for an expert audience, but I knew that for that type of audience, that data wouldn't tell them anything they didn't already know. (Smart speakers are popular, and sometimes they are recording when they're not supposed to be or when people don't know they are, and that causes privacy concerns. Okay. What else?)

While we have data about users' self-reported attitudes toward smart speakers, what we don't have much of, from an expert standpoint, are the usability metrics that we would expect to see for a visual interface. To understand why so many people find these devices to be "creepy" despite the companies' efforts to respond to bad press, a crucial aspect is understanding what people actually experience if they try to find more privacy information or change their privacy settings. Some of my colleagues have worked on this recently for website privacy settings and opt-out mechanisms, so what I wanted to do here was give a glimpse of what would happen if we gave the voice interface the same treatment that people have been giving to visual privacy interfaces. I couldn't conduct extensive usability testing with lab studies and so forth for this course, but I could still collect some data, so I tried to answer the following questions and present the results in a way that would make sense to both audiences:
- Can the devices answer privacy questions or perform privacy tasks in a useful way within the voice interface?
- (Since I knew from past experience that the answer to the above would be no) How hard is it to find the privacy settings when you are sent to the visual interface? (Using steps/clicks as a simple proxy)
- Once you find them, how hard is it to figure out what they mean? (Using readability as a proxy)

I knew the latter two would be a little less clear to a non-expert audience without context for standard usability guidelines (although the ideas of steps and grade levels are still pretty accessible), but they are still easier proxies to understand than if I had included more variables or done more complex lab studies. I figured that if nothing else, the chart with 
red X's would make it clear that there is room for improvement and that the devices aren't optimized to help users with privacy concerns, which were the main points I wanted a general audience to understand.

### Design process for final story

The earlier steps of the design process are described above (and in more detail on the [Part 1](https://sarahpearman.github.io/data-stories/final-project-part1.html) and [Part 2](https://sarahpearman.github.io/data-stories/final-project-part2.html) pages).

#### Building story in Shorthand

A lot of my design decisions happened in Part 2, so after that point, I was just refining and figuring out how to work within the constraints of Tableau and Shorthand.

My first step for building the story in Shorthand was to take the final wireframe and build the most important charts that I knew I would want to show during the presentation, as well as insert the most important text blurbs to show the flow that I had set up in the wireframe and create the transitions from one chart to the next.

After that, I iterated on the images and the text as I figured out what did and did not display correctly in Shorthand, and as I realized what did and did not contribute to the overall story once I saw it all together. The overall structure of the story remained roughly the same as in my final wireframe, but here are some important changes that I made:
* I originally planned to show the growth in smart speaker adoption using a line graph, but this just wasn't compelling once I mocked it up in Tableau since I only had three years of data. I decided a bar chart would be better for drawing attention to the fact that the number had more than doubled from 2017 to 2019, since the bars make it easy to compare those proportions. (I colored the bars green since that seemed representative of growth, and since at that point I didn't want to imply negative valence, since that would come later when I talked more about privacy concerns and switched to more red tones for the charts.)
* I went back and forth about what date range to include in the line chart about the Google search trends. In the presentation, I used 2017 to 2019, since that matches the adoption trend from the bar graph before that, but the overall trend is clearer if I start at Alexa release in late 2014, so I decided to put that in the full Shorthand.
* I decided to use a different stat to make the point I was making with the third pie chart in the wireframe. Instead of saying that 26.8% of users don't realize they can delete device history, I decided it was more compelling to include the stat indicating that only 11% of users had actually done so.

A design struggle that I faced at first was figuring out how to ensure that charts would display fully in the wide aspect ratio that Shorthand uses. Shorthand does not necessarily shrink images to fit vertically, so I had to build wide chart images with extra whitespace on the sides to ensure that the whole chart would fit on the screen at once (while also maximizing the chart size to make sure it was legible, especially when projected). I also had to make fonts a lot larger than I otherwise would have to ensure that they would project at a readable size for the presentation. (Admittedly, it was very helpful to present on the second day and adjust based on charts that were difficult to read in other people's presentations on the first day.)

#### Fonts

I found it odd that Shorthand uses a sans serif font for headings but a serif font for body text, since I've always been taught that serif fonts are harder to read on screens. (It also just looked weird and distracting to me to have so many different fonts.) I added some custom CSS to force Shorthand to use a sans serif font everywhere (it should be displaying in Helvetica Neue wherever possible). I also found it jarring to have Tableau's font mixed in with that, so I changed all my charts to Helvetica-family fonts as well (mostly Helvetica Neue, although I think there might be some annotations in other Helvetica versions). I don't mind the Tableau font, but it definitely screams "THIS CHART CAME FROM TABLEAU."

#### Pie charts

I decided to make the pie charts really, really simple, not even labeling both sections in some cases, and trusting the user to understand that if one big section had "No" in it then the other section represented "Yes." This seemed fine during my user testing, and I wanted to minimize the text on the charts, especially for purpose of the presentation.

#### Iterating & feedback

Beyond those aspects, I just iterated *many* times, adding notes where I realized there would be a gap in understanding (especially for a general audience), and changing charts to make them as simple and visually pleasing as possible.

My "user with more design background than me" from Part 2 looked over the almost-final version to help me catch anything egregious. He mostly restated issues that we discussed in Part 2 but never found a solution to.
* Overall, he found the final chart to be a little more complicated than he would like. I think that one is really more expert-audience focused and would be more readily received by people like me who read charts every day and are already familiar with the types of variables used in the chart. The problem I was never able to solve in Part 2 was that I wanted to show both axes in one graph so that you could get a general picture of whether a data point was towards the top right (hard to find/read) or the bottom right (easy).
* He also objected to the question in the final chart's title, saying that he preferred titles to just be simple statements. I agreed with this point, couldn't remember why I had a question there in the first place, and changed the title to a statement version.
* We talked about how the pie charts were almost overly simple, and that there would probably be a way to combine some of the data in those that came from the Pew 2019 data into one chart to get across multiple points of information simultaneously. I agreed with this and would have done this if I had the raw data, but since the raw 2019 dataset isn't available yet, all I had was the overall percentages, so I couldn't do anything more complicated that would require having access to the individual responses.
* We also talked about the design decision to leave the labels off of the gray portion of some of the pie charts, where I mentioned previously that I labeled one section "no" and trusted the user to figure out that the other section was "yes." He wondered why I did this but then agreed that for the intended audience, who would have at least some data visualization literacy, this was a reasonable choice and helped to minimize unnecessary text.


### References

#### Data sources, news sources, websites, and apps referenced in Shorthand report

Amazon Alexa iOS app, version 2.2 (February 2020).

T. Ammari, J. Kaye, J.Y. Tsai, and F. Bentley. [Music, Search, and IoT: How People (Really) Use Voice Assistants](http://web.mit.edu/bentley/www/papers/iot.pdf). ACM Transactions on Computer-Human Interaction, Vol. 26, No. 3, Article 17. April 2019. Mozilla's summary blog post also available [here](https://blog.mozilla.org/ux/2019/12/how-people-really-really-use-smart-speakers/).

Apple Settings app, Siri & Search, iOS version 13.3.1 (February 2020).

D. Bohn. [Apple was a little behind on Siri privacy, now it’s way ahead](https://www.theverge.com/2019/8/29/20837077/apple-siri-privacy-opt-out-voice-human-grading-review). The Verge. August 29, 2019.

M. Day, G. Turner, and N. Drozdiak. [Amazon Workers Are Listening to What You Tell Alexa](https://www.bloomberg.com/news/articles/2019-04-10/is-anyone-listening-to-you-on-alexa-a-global-team-reviews-audio). Bloomberg News. April 10, 2019.

Google Home iOS app, version 2.17 (February 2020).

[Google Trends query for "Alexa Privacy"](https://trends.google.com/trends/explore?date=2014-01-01%202020-02-14&geo=US&q=alexa%20privacy). Downloaded csv [here](https://github.com/sarahpearman/data-stories/tree/master/final-project-files/google-trends-data). Data shown in line graph only includes a subset (2017-2019).

J. Lau, B. Zimmerman, and F. Schaub. [Alexa, Are You Listening? Privacy Perceptions, Concerns and
Privacy-seeking Behaviors with Smart Speakers](https://www.key4biz.it/wp-content/uploads/2018/11/cscw102-lau-1.pdf). CSCW 2018.

[NPR Smart Audio Report Winter 2019](https://www.nationalpublicmedia.com/insights/reports/smart-audio-report/).

Pew Research Center 2017 [voice assistants report](https://www.pewresearch.org/wp-content/uploads/2017/12/voice-assistants-TOPLINE-and-METHODOLOGY-FINAL-COPY-EDITED.pdf), based on 2017 American Trends Panel Wave 27 conducted May 1-15, 2017. The  full American Trends Panel dataset can also be downloaded [here](https://www.pewresearch.org/internet/dataset/american-trends-panel-wave-27/) (with free account registration).

Pew Research Center 2019 [smart speaker report](https://www.pewresearch.org/wp-content/uploads/2019/11/FT_19.11.21_SmartSpeaker_methods-topline-final-11.21.pdf) based on 2019 American Trends Panel data. Full dataset not yet available for download: percentage numbers used in pie charts were taken directly from topline report.

https://www.theverge.com/2019/8/29/20837077/apple-siri-privacy-opt-out-voice-human-grading-review

[WebFX Readability Test Tool](https://www.webfx.com/tools/read-able/) used to calculate readability metrics for app settings. The readability data can be found [here]().

https://en.wikipedia.org/wiki/Amazon_Alexa (just to retrieve the Alexa release date)

#### Self-collected data

Some data was collected from direct voice interactions with Amazon Echo Dot and Google Home Mini.

Any data that is not linked above, including the data I collected myself, is included in my GitHub repository.
* [Readability data](https://github.com/sarahpearman/data-stories/tree/master/final-project-files/readability)
* [Recordings from my voice interactions with smart speakers](https://github.com/sarahpearman/data-stories/tree/master/final-project-files/recordings)
* [Categorical data created from the recordings](https://github.com/sarahpearman/data-stories/blob/master/final-project-files/device-data/voiceInterface_privacyInfo.xlsx)

Any other relevant files or notes can be found in this directory: [https://github.com/sarahpearman/data-stories/final-project-files](https://github.com/sarahpearman/data-stories/tree/master/final-project-files)

#### Image sources

Images from Pixabay (user HeikoAL), Wikimedia Commons (users SimonWaldherr, Y2kcrazyjoker4, Gregory Varnum, TKsdik8900), Robert Couse-Baker on Flickr, and vpnsrus.com.

See [full Shorthand story](https://carnegiemellon.shorthandstories.com/smartSpeakerPrivacy/index.html) for more details on individual images and licenses.

#### Tools

Tableau Desktop 2019.4, Excel for Mac 16.33, BBEdit, Preview, Github, Balsamiq Wireframes.

#### Other

Intentionally did *not* add a reference line for the number of steps/clicks/touches that would be ideal to get to the setting in the final chart based on these references:
* [https://www.nngroup.com/articles/3-click-rule/](https://www.nngroup.com/articles/3-click-rule/)
* [https://www.nngroup.com/articles/interaction-elasticity/](https://www.nngroup.com/articles/interaction-elasticity/)
* [http://web.mit.edu/bentley/www/papers/iot.pdf](http://web.mit.edu/bentley/www/papers/iot.pdf)
