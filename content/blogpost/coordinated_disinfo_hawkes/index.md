---
title: "Discovering coordinated disinformation via Hawkes processes"
authors:
  - Marian-Andrei Rizoiu
date: "2021-09-27"
output: html_document
categories: [Presentation]
image:
  placement: 1
  focal_point: "Center"
  preview_only: true
summary: "ECREA 2021 presentation: \"Discovering the Strategies and Promotion Schedules of Coordinated Disinformation via Hawkes Intensity Processes\" "
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/kzGkvZRjnoI?start=70" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Recording of the presentation "Discovering the Strategies and Promotion Schedules of Coordinated Disinformation via Hawkes Intensity Processes" (Tim Graham, **Marian-Andrei Rizoiu**, Axel Bruns, Dan Angus), presented at the [European Communication Conference (ECREA) 2021](https://www.ecrea2021.eu/), 8 Sep. 2021. 

Discovering the Strategies and Promotion Schedules of Coordinated Disinformation via Hawkes Intensity Processes
===

[Tim Graham](https://www.qut.edu.au/about/our-people/academic-profiles/timothy.graham), Digital Media Research Centre, Queensland University of Technology  
[Marian-Andrei Rizoiu](/authors/ma-rizoiu/), Data Science Institute, University of Technology Sydney  
[Axel Bruns](https://www.qut.edu.au/about/our-people/academic-profiles/a.bruns), Digital Media Research Centre, Queensland University of Technology  
[Dan Angus](https://www.qut.edu.au/about/our-people/academic-profiles/daniel.angus), Digital Media Research Centre, Queensland University of Technology  

‘Fake news’ and broader ‘information disorders’ [6] such as mis- and disinformation have emerged as global issues that threaten to undermine democracy and authentic political communication on social media [1]. Increasingly sophisticated coordination strategies have intensified the scale and scope of the impact that disinformation has on public opinion and democratic trust. Howard et al. [3] found that coordinated disinformation operations are now occurring in 48 countries, and in 2019 the European External Action Service detected and exposed over 1,000 cases of disinformation within the European Union [2]. Whilst disinformation has attracted much scholarly attention, most studies to date have focussed on the diffusion and impact of individual content (e.g. ‘fake news’ articles) and the activity of individual accounts (e.g. bots and trolls). 

An emerging problem is to understand message coordination strategies, where content authored and distributed by agents (e.g. Twitter trolls) is governed and scheduled by some unknown principal actor [4]. We know that coordinated promotion (e.g. sharing, liking, retweeting) of ‘fake news’ articles by trolls and social bots can greatly increase and amplify the negative effects of these attempts to sow discord and manipulate public conversations about election candidates and partisan issues such as immigration and climate change. Likewise, it is evident that disinformation campaigns unfold via ‘collaborative work’ that co-opts and cultivates organic systems in order to produce desired effects such as increased polarisation, distrust in news media and confusion of the audience [7]. This makes identifying ‘inauthentic’ versus ‘organic’ activity ever more difficult, as they are intricately enmeshed in real-world disinformation campaigns. 

In this paper, we tackle the problem of inferring the coordinated promotion schedules of ‘fake news’ articles using a novel approach known as Hawkes Intensity Processes (HIP; see [5]). We analyse the diffusion of articles from ten major sources of hyperpartisan information and ‘fake news’ within over 16.5 million tweets that linked to content from these sites during July to September 2019. Using HIP, we uncover not only coordination strategies but also the promotion schedules of ‘fake news’ content, where agents (in this case Twitter accounts) are being centrally managed by principals (e.g. state operatives, government officials, etc.) in order to strategically promote ‘fake news’ content and maximise its virality and longevity in the social memory. This paper provides preliminary results from this ongoing research, highlighting the current challenges as well as open problems and gaps for future work. 

### References
[1] Benkler, Y., Faris, R., & Roberts, H. (2018). Network propaganda: Manipulation, disinformation, and radicalization in American politics. Oxford University Press.  
[2] European Commission. (2019). Action plan against disinformation: Report in progress. Retrieved 20 November 2019 from: https://ec.europa.eu/commission/sites/beta-political/files/factsheet_disinfo_elex_140619_final.pdf.  
[3] Howard, P. N., & Kollanyi, B. (2016). Bots, #StrongerIn, and #Brexit: Computational Propaganda during the UK-EU Referendum. SSRN Electronic Journal. doi:10.2139/ssrn.2798311  
[4] Keller, F. B., Schoch, D., Stier, S., & Yang, J. (2019). Political Astroturfing on Twitter: How to Coordinate a Disinformation Campaign. Political Communication, 1-25.  
[5] Rizoiu, M. A., Xie, L., Sanner, S., Cebrian, M., Yu, H., & Van Hentenryck, P. (2017, April). Expecting to be hip: Hawkes intensity processes for social media popularity. In Proceedings of the 26th International Conference on World Wide Web (pp. 735-744). International World Wide Web Conferences Steering Committee.  
[6] Wardle, C., & Derakhshan, H. (2017). Information disorder: Toward an interdisciplinary framework for research and policymaking. Council of Europe Report DGI (2017) 09.  
[7] Wilson, T., Zhou, K., & Starbird, K. (2018). Assembling Strategic Narratives: Information Operations as Collaborative Work within an Online Community. Proceedings of the ACM on Human-Computer Interaction, 2(CSCW), 183.

## The panel: "Coordinated Inauthentic Behaviour in Social Media: New Methods and Findings"

### Panel Rationale

Social media platforms are increasingly forced to address what Facebook now describes as ‘coordinated inauthentic behaviour’ (Gleicher 2018): online influence operations that seek to trick platform algorithms into promoting and recommending ‘problematic information’ (Jack 2017), to mislead the human users of such platforms into accepting and sharing such content, and thereby also to affect broader issue frames and news agendas in mainstream media coverage. Concerns about such coordinated inauthentic behaviour extend earlier fears about the influence of malignant social bots, but also transcend them: drawing on social bots as well as human labour, coordinated inauthentic behaviour is likely to involve a combination of manual and automated activity. This additional human factor also complicates the detection of such coordinated activities, and their distinction from genuine, organic, authentic coordinated actions.

This cross-national and interdisciplinary panel approaches the study of coordinated inauthentic behaviour from a number of directions. It outlines novel and innovative detection and analysis approaches for a number of leading social media platforms, and presents their results in the context of domestic and international political debates across several national contexts. Further, it also considers how mainstream journalism might report on and respond to such activities in order to protect news audiences from being affected by coordinated inauthentic behaviours.

The first two papers in this panel focus especially on coordinated inauthentic link-sharing practices. Paper 1 introduces Hawkes Intensity Processes (HIP), a novel technique for inferring the coordinated content promotion schedules of automated social media accounts, and applies this to a major dataset of 16.5 million tweets containing links to ten major sites identified as sources of hyperpartisan content and ‘fake news’. In doing so, it uncovers new networks of inauthentic Twitter actors. Paper 2 investigates similar coordinated link-sharing activity on Facebook in Italy during the 2018 Italian and 2019 European elections. It uncovers evidence for the involvement of dozens of pages, groups, and public profiles in such media manipulation attempts. Paper 3 complements this work by focussing especially on the temporal posting patterns in such coordinated activity. It employs the recurrence plotting technique to identify traces of inauthentic actors’ use of automated scheduling tools in systematically posting content to a network of apparently unrelated pages, focussing here especially on a group of far-right pages on Facebook. Paper 4 examines ten coordinated disinformation campaigns across the globe (e.g., Hong Kong, Russia, USA, Spain and Germany) and identifies important traits that help distinguish between those participating in the disinformation campaign and the regular users they try to imitate. Paper 5, finally, shifts our attention to a core target of such coordinated inauthentic behaviour: the journalists and editors whose perception of current political moods such influence operations often aim to affect. Drawing on a series of in-depth interviews with Danish news workers and related stakeholders, it examines their understanding of and responses to coordinated mis- and disinformation campaigns.

Collectively, these studies contribute substantially to advancing the methodological toolkit and extending the empirical evidence base for the study of coordinated inauthentic behaviour, while also not losing sight of the stakeholders that such work seeks to support. They offer an independent assessment of the nature and extent of the problem across several leading social media platforms, complementing the platform providers’ own investigations into such activities and identifying possible responses to such concerns for both social and mainstream media actors.

### The papers presented are (presenters bolded):

* Discovering the Strategies and Promotion Schedules of Coordinated Disinformation via Hawkes Intensity Processes (Tim Graham, **Marian-Andrei Rizoiu**, Axel Bruns, Dan Angus)
* It Takes a Village to Manipulate the Media: Coordinated Link Sharing Behaviour during 2018 and 2019 Italian Elections (**Fabio Giglietto**, Nicola Righetti, Luca Rossi, Giada Marino)
* Recurrence Plotting for Detecting Duplicate Online Posting Activities (**Dan Angus**, Tim Graham, Tobias Keller, Brenda Moon, Axel Bruns)
* Astroturfing in Hong Kong and Elsewhere: Patterns of Coordination in Hidden Twitter Campaigns (**Franziska B. Keller**, Sebastian Stier, David Schoch, JungHwan Yang)
