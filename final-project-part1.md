# Final Project, Part 1: Smart Speakers & Privacy Choices

[On to Part 2](https://sarahpearman.github.io/data-stories/final-project-part2.html)

[On to Parts 3/4, Final Deliverable](https://sarahpearman.github.io/data-stories/final-project-main.html)

---

## Initial theme: *More and more people are putting smart speakers in their homes, but people still aren't sure whether they can trust these devices.*

![Outline drawn in class](https://raw.githubusercontent.com/sarahpearman/data-stories/master/sketches/story.jpg)

## Outline

I plan to tell a story about how adoption of smart speakers (e.g., Alexa devices) is increasing, while trust in their privacy practices does not seem to be increasing accordingly. I will use public Pew Research data from 2017 and 2019 that includes general adoption percentages for these devices as well as questions about people's usage of these devices and opinions about them. I may also use some other research data and news reports, depending on what I am able to scrape, but the Pew datasets will be my main source since they are public.

This will be useful for me in the future: I'm interested in conducting further research on data use disclosures and consent interfaces in voice user interfaces such as smart speakers and phone voice assistants (with the goal of helping to inform best practices for these devices, and potentially even future regulation of those practices). I will need to be able to succinctly tell a story of why this research is needed.

### Setup

Adoption of smart speakers and voice assistants is growing. Pew Research found that nearly half of Americans surveyed used voice assistants in May 2017, and 17% on a standalone device such as an Amazon Echo ([topline data here](https://www.pewresearch.org/wp-content/uploads/2017/12/voice-assistants-TOPLINE-and-METHODOLOGY-FINAL-COPY-EDITED.pdf)). About two years later, in their June 2019 American Trends Panel, Pew found that 25% of households surveyed had standalone voice assistant devices ([topline data here](https://www.pewresearch.org/wp-content/uploads/2019/11/FT_19.11.21_SmartSpeaker_methods-topline-final-11.21.pdf)).

### Conflict

Many people don't trust these devices (including some who own them), and people who own them and do trust them sometimes have fundamental misunderstandings of what may be happening with their data and may not know what options are available to help them manage their privacy.

### Resolution

The research and best practices on designing for usability and privacy in voice user interfaces needs to catch up to the surge of research on natural language processing and conversational agents. 

In the meantime, regular users should take note of whether these devices are using their data in ways they are comfortable with. Users can consider this when deciding what they do and do not want to purchase, and they can also choose to change the privacy settings on their devices from the defaults if they want more control over how their data is used.

## Initial sketches

![Charts showing increase in smart speaker adoption and high levels of concern about data privacy](https://raw.githubusercontent.com/sarahpearman/data-stories/master/sketches/pies.jpg)

![Data movement chart](https://raw.githubusercontent.com/sarahpearman/data-stories/master/sketches/data-movement.jpg)

![User data privacy concern chart](https://raw.githubusercontent.com/sarahpearman/data-stories/master/sketches/concern.jpg)


## The data

### Main data sources

My main data sources will be two sets of Pew Research survey results.

The first comes from the May 2017 American Trends Panel (Wave 27). That dataset is publicly available in full [from this list](https://www.pewresearch.org/internet/datasets/) with a free Pew Research account, but it can't be directly linked since signin is required to download the raw datasets from their website. The topline report for the relevant data is also available [here](https://www.pewresearch.org/wp-content/uploads/2017/12/voice-assistants-TOPLINE-and-METHODOLOGY-FINAL-COPY-EDITED.pdf).

The second source comes from the June 2019 American Trends Panel (Wave 35). The full raw dataset is not yet available (Pew usually has a delay of up to 1-2 years from collection to release of the full dataset), but the topline data contains what I need, and it's available [here](https://www.pewresearch.org/wp-content/uploads/2019/11/FT_19.11.21_SmartSpeaker_methods-topline-final-11.21.pdf). The parts I'm concerned with are also summarized in a report [here](https://www.pewresearch.org/fact-tank/2019/11/21/5-things-to-know-about-americans-and-their-smart-speakers/).

Both of these datasets consist of >4000 U.S. adults who are randomly selected from the general population.

### Additional context

I expect to use some data points from the two papers below. The original datasets are not publicly available, but I would just need to cite simple percentages or counts that are available in the papers themselves (both of which are publicly available).

J. Lau, B. Zimmerman, and F. Schaub. [Alexa, Are You Listening? Privacy Perceptions, Concerns and
Privacy-seeking Behaviors with Smart Speakers](https://www.key4biz.it/wp-content/uploads/2018/11/cscw102-lau-1.pdf). CSCW 2018.

T. Ammari, J. Kaye, J.Y. Tsai, and F. Bentley. [Music, Search, and IoT: How People (Really) Use Voice Assistants](http://web.mit.edu/bentley/www/papers/iot.pdf). ACM Transactions on Computer-Human Interaction, Vol. 26, No. 3, Article 17. April 2019. Mozilla's summary blog post also available [here](https://blog.mozilla.org/ux/2019/12/how-people-really-really-use-smart-speakers/).

### Other possible supplementary data sources

I am also exploring other context that may be useful, including statistics cited in academic papers and news publications listed below. As above, I may not be able to get the original dataset for these, but I can cite simple summary statistics from the publications.

[https://yixinzou.github.io/publications/popets2020-mhaidli.pdf](https://yixinzou.github.io/publications/popets2020-mhaidli.pdf)

[https://foundation.mozilla.org/en/privacynotincluded/](https://foundation.mozilla.org/en/privacynotincluded/)

[https://www.bloomberg.com/news/articles/2019-12-31/you-re-home-alone-with-alexa-are-your-secrets-safe-quicktake](https://www.bloomberg.com/news/articles/2019-12-31/you-re-home-alone-with-alexa-are-your-secrets-safe-quicktake)

[https://www.bloomberg.com/news/articles/2019-04-10/is-anyone-listening-to-you-on-alexa-a-global-team-reviews-audio](https://www.bloomberg.com/news/articles/2019-04-10/is-anyone-listening-to-you-on-alexa-a-global-team-reviews-audio)


## Method and medium

I plan to complete the final "story" for my project using Shorthand. Some of the essential visuals will be charts showing the increase in adoption of voice assistants (both on phones and on standalone devices), as well as some charts documenting statistics on users' concern about privacy, some of the known privacy issues (such as the frequency with which these devices start recording by mistake, when a wake word wasn't actually said), and some of the usability concerns (e.g., a stat from [this study](https://blog.mozilla.org/ux/2019/12/how-people-really-really-use-smart-speakers/) showing that >25% of people they studied did not know that they could delete data from the logs of these devices).

I also expect to use some visuals that show supplementary information that may not need to be presented as a chart. For example, I'm still trying to determine the best way to present conceptual visuals to emphasize where the data from these devices can flow to and the fact that employees at companies are sometimes listening to recordings from the devices directly.

I will probably build some charts using Tableau and some using ggplot. I intend to build as many as I can with Tableau, since one of my goals in this course is to become more familiar with Tableau, but it's better at some things than others, so I'll switch to R/ggplot when it can't do what I need.

---

[Back to Home](https://sarahpearman.github.io/data-stories/)
