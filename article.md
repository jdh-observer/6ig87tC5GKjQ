---
jupyter:
  jupytext:
    formats: ipynb,md
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.16.4
  kernelspec:
    display_name: Python 3 (ipykernel)
    language: python
    name: python3
---

<!-- #region citation-manager={"citations": {"": []}} tags=["title"] -->
# Chronoferencing the Italian-Slovenian Borderlands. Citizen Science, Oral History and Output Criticism

<!-- #endregion -->

<!-- #region tags=["keywords"] -->
Citizen Science, Oral History, Borders, Italy, Slovenia, Digital Hermeneutics
<!-- #endregion -->

<!-- #region tags=["contributor"] -->
### Machteld Venken [![orcid](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-0358-0827)
University of Luxembourg
<!-- #endregion -->

<!-- #region tags=["contributor"] -->
### Johanna Jaschik [![orcid](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-0197-6748)
University of Luxembourg
<!-- #endregion -->

<!-- #region tags=["copyright"] -->
 [![cc-by](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)
© Machteld Venken - Johanna Jaschik. Published by De Gruyter in cooperation with the University of Luxembourg Centre for Contemporary and Digital History. This is an Open Access article distributed under the terms of the [Creative Commons Attribution License CC-BY](https://creativecommons.org/licenses/by/4.0/)
<!-- #endregion -->

<!-- #region tags=["copyright"] -->
 [![cc-by-nc-nd](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
©<AUTHOR or ORGANIZATION / FUNDER>. Published by De Gruyter in cooperation with the University of Luxembourg Centre for Contemporary and Digital History. This is an Open Access article distributed under the terms of the [Creative Commons Attribution License CC-BY-NC-ND](https://creativecommons.org/licenses/by-nc-nd/4.0/)
<!-- #endregion -->

<!-- #region tags=["abstract"] -->
This article unravels the opportunities and limits for generating new academic knowledge about the use of articulations of time in interviews conducted and produced by students. We narrate the experiences of a citizen scientist throughout an interdisciplinary experiment in which citizen scientists and border scholars expressed what borders mean to them. Analysing citizen scientist Termime’s (pseudonym) oral and written expressions as a case study with the help of Achim Landwehr’s concept of *Chronoferenzen* (chronoferencing), we decipher the intricate links citizen scientists identify between the past, the present and the future in the way they see borders within the three different genres practised during the experiment: a monologue, a dialogue and a digital café.

At the same time, the article also presents a reflection on the digital research process applied during the study. The hermeneutic layer evaluates the methods and tools we used throughout the workflow, from organising the experiment to analysing the oral data and presenting the findings in the *Journal of Digital History* with respect to the three well-known stages in digital hermeneutical research: digital source criticism, tool criticism and visualisation criticism. Adding ‘output criticism’ as a fourth step enables us to present our reflection on the presentation possibilities and constraints of digital publishing and propose changes.  
<!-- #endregion -->

<!-- #region tags=["narrative"] -->
## Introducing the ‘Talking Borders’ Experiment

How to consider new testimonies as a potential source of enquiry has long been a prevalent question within contemporary historiography. As Rizzo observed: ‘Rather than assuming that knowledge comes only from archives, official records, or outside observation, collaborating with community members recognizes that their lived experience is knowledge and has value’ (<cite data-cite="8820477/X8S2B2KD"></cite>). Oral historians and anthropologists, most prominently, consider narrators to be experts when it comes to their past lived experiences (<cite data-cite="8918850/WGVEPWZA"></cite>, 35). Within the citizen science experiment ‘Talking Borders. From Local Expertise to Global Exchange’, we considered Bachelor students in the humanities studying at universities in various border regions throughout the former Habsburg region as experts about daily life in the borderlands. To mark the hundredth anniversary of the dissolution of the Austro-Hungarian Empire, these citizen scientists were invited to participate in an exchange of ideas about international borders and the communities engendered by borders at the Second World Conference of the Association for Borderlands Studies (ABS) held in Vienna and Budapest in July 2018. We assumed that they would ‘bring a very real authority’ in giving meaning to the borders they encounter in their daily lives, an authority ‘grounded in a culture of experience’ (<cite data-cite="8820477/PASUJEDM"></cite>, xxii).

<!-- #endregion -->

The digital era has offered new opportunities to share authority and stimulate an active dialogue between experience and expertise (<cite data-cite="8820477/RVAR4E8B"></cite>, 136). Within citizen science, researchers are currently investigating the border between expertise and experience, or, in other words, between the production and consumption of science. In a rare edited volume about citizen science in the humanities, Oswald and Smolarski wrote: ‘The [...] borders between professional research, which generates new knowledge, and the public, who consume this knowledge, were barely challenged during the first years of the social web.’(<cite data-cite="8820477/AVQJUUMG"></cite>, 12) Nowadays, however, these borders are pitched in projects in linguistics, archaeology, art and philosophy, as well as history. Citizen humanities offers great potential to include citizens beyond the data collection phase, because nuances, ambiguity and room for interpretation are characteristics that are at the essence of every research stage, from formulating a hypothesis to data collection to analysis and interpretation. One example is the German project ‘Kino in der DDR’, launched in 2020, which asked citizens for testimonies and historical objects reflecting personal memories and experiences of cinema visits in the GDR as a way of exploring the everyday history of cinema culture in communist East Germany. Such a project demonstrates how concerns that citizens may lack the required skills in academic research can be embraced as part of the scientific process. Citizens’ personal experiences and memories of cinema in the GDR as expressed in written and oral testimonies are considered fruitful ground for a variety of research questions (<cite data-cite="8820477/X2SCIUKM"></cite>). Such an approach of citizen science methodology moves beyond the conventional understanding of citizen scientists as actors who perform tasks of 'compiling, organising, analysing and sharing sources' (<cite data-cite="8918850/PPQDKB7W"></cite>, 6). Similar to the 'Kino in der DDR' project, the bachelor students in the Talking Borders experiment were regarded as actors with expertise, who were the creator of their own sources (<cite data-cite="8918850/GEPQU8AU"></cite>, 69–70).  


Today, oral history research projects in partnership with community groups are experimenting to determine ‘the limits of what we can expect from public expertise and contributions’, as this has the potential to ‘drive methodological innovations as well as leave us in a better position to address potentially serious objections that are likely to be raised by the wider scientific community towards the use of publicly gathered data’. (Riesch and Potter, 116). These experiments range from offering intensive training to citizen scientists on how to conduct interviews to crowdsourcing by means of digitally self-recorded stories generated without the support of professional historians. ‘Talking Borders’ also offered training to citizen scientists during a try-out session the day before the experiment, but it did not provide more in-depth training on how to record each other’s stories, as was offered in the project ‘Surviving Katrina and Rita in Houston’ (<cite data-cite="8820477/2TWIE7HC"></cite>), for example. We asked citizen scientists to talk to each other and record their stories themselves, without the intervention of an historian, but in contrast to the idea of composing an open memory bank, for example, we selected a specific group of citizen scientists and provided the format of a one-hour conversation provoked by one question: ‘What does a border mean to you?’ (<cite data-cite="8820477/HD7TRXCH"></cite>).


Without downplaying the ‘general enthusiasm over citizen science’, Riesch and Potter insist on the need to investigate ‘potential pitfalls’ of the discipline. The ‘Talking Borders’ experiment contributed to that endeavour. The border between expertise and experience was thematised by inviting citizen scientists to an academic conference to discuss their understanding of borders. We define borders as ‘typically rooted in historically constructed structures of meanings labelled […] as discursive landscapes of social power’. (<cite data-cite="8820477/7R9HBA6T"></cite>, 116). In addition, we use digital hermeneutics in order to bring us closer to understanding the limits of public expertise by articulating ‘the “interventions” of the digital into historical practices’ by means of a ‘critical engagement with digital infrastructures, data and tools’ (<cite data-cite="8820477/Q827WAU3"></cite>, 7). Our approach enables us to reveal the relevance of the past for meaning-making purposes in the present. Indeed, in turning the Association for Borderlands Studies Second World Conference into a platform for a citizen science experiment, the Talking Borders project aimed to apply border research:


> Border research then takes on an applied dimension, as we seek to discover, and promote, those mechanisms which enable borders to be opened, reducing the frictions and tensions of socially constructed difference. This is the desire to “overcome” borders through reimagining them as places where people can meet, to overcome the social construction of spatial fixation (<cite data-cite="8918850/M3C5QNR7"></cite>). This is a major challenge of border research – to understand the functional impact and role of borders in a world which has become more spatially flexible, where territory and group affiliations and identities are undergoing a process of internal restructuring. (<cite data-cite="8820477/QDMEEP3Q"></cite>, 23)



Could the spoken ideas gathered within Talking Borders be considered as oral history sources? As in oral history, our experiment facilitated an encounter. Alessandro Portelli referred to oral history as (<cite data-cite="8820477/HIZ25PXV"></cite>, 3) ‘what the source and the historian do together at the moment of their encounter in the interview’. Shopes (<cite data-cite="8820477/TZKQ8RTH"></cite>, 103) even stressed that it is a ‘dialogue that defines the interview process itself’. In this article, we demonstrate that the citizen scientists in the Talking Borders experiment expressed their thoughts about the meaning of their lives in borderlands through chronoferencing (<cite data-cite="8820477/RRDDC742"></cite>). Referencing the past was essential for them to understand their contemporary reality and project their imaginations for the future.


The citizen scientists participating in Talking Borders grew up in borderlands witnessing the opening up of state borders following the collapse of communism and experiencing how EU expansion softened border regimes (<cite data-cite="8820477/S957L83I"></cite>, 1-2). They informed us about economic, cultural, political and social aspects of the transformation that took place within post-Soviet borderlands while recalling the everyday practices that they, their families and their acquaintances engaged in. They also expressed their historical knowledge about the borderlands where they came from, a knowledge that was concentrated more on the last 30 years than on earlier times. This observation was a surprise to us, as the citizen scientists had been recruited to participate in the experiment specifically to mark the hundredth anniversary of the dissolution of the Austro-Hungarian Empire.


We distilled information about the way in which citizen scientists referenced time from the ideas they expressed during the experiment. As individuals, they live in a social setting, and, whether consciously or not, they exchange their representations with others. This is how people learn to gauge what practices are acceptable for the social group(s) they are part of, and what behaviour needs to be silenced for the sake of social group identification. People tend to practise the customs of their social group, although they are seldom aware of this (<cite data-cite="8820477/V4LJQEAY"></cite>). In this article, we assume that individual practices as expressed during the experiment are windows onto borderland communities in which what is characteristic for these communities becomes visible and comparable (<cite data-cite="8820477/JDSUQQE4"></cite>, 343). The experiment therefore enabled us to reconstruct the way in which time was referenced in the social borderland life-world during the transformation period.


To attribute meaning to borders, the citizen scientists recalled their own and their relatives’ personal border experiences in the past, drew on border realities as shaped by geopolitical events and common regional border practices in the present, and used their past and present border experiences to make predictions about border regulations for the future. Achim Landwehr’s notion of ‘Chronoferenzen’ (<cite data-cite="8820477/RRDDC742"></cite>) encapsulates these multiple overlapping temporal layers. The concept of Chronoferenzen, derived from the Greek word chrono (time) and the Latin word referre (carry back), supports an analysis of the intricate links identified by citizen scientists between the past, the present and the future and the way in which these links influence their views of borders. Landwehr argues that individuals and groups use temporally absent imaginaries of the past and the future to attribute meaning to present realities, and he strives to include the analysis of such references in the study of the past:


‘The notion of chronoference can help to overcome a practised dualism that is well established in historical work (academic and non-academic): the juxtaposition of present and past (or present and future) is usually assumed to be an integral part of our understanding of time. But in reality this dualism artificially separates something that cannot be separated in this form. “Past” is not simply the detached counterpart of a present that has to be painstakingly regained using historical methods. Rather, the “past” is always already part of a present description.’ (<cite data-cite="8820477/RRDDC742"></cite>, 249-250).


Focusing on the simultaneity of multiple temporal layers allows us to approach our citizen scientists’ thoughts about borders from an angle of multiple temporalities (‘Vielzeitigkeit’); that is, to understand the parallel occurrence of different temporal dimensions in oral and written expression. In what follows, we investigate how citizen scientists related the past and future to the present and how temporal dimensions could occur parallel or in competition to each other. We also decipher how citizen scientists navigated differences when expressing their thoughts, and what they chose to leave unmentioned, which therefore remained absent.


The principle of multi-layered publishing introduced in academia by the Journal of Digital History enables us to present our dataset, research methodology and narrative interpretation together. The dataset of this article consists of all the monologues and dialogues recorded during the experiment, as well as the raw data of the project website on which the digital café was hosted. The hermeneutic layer of our article includes motivations, explanations and reflections of the research methods we used throughout the different steps of our workflow: while recording, transcribing and analysing the monologue, dialogue and interventions in the digital café. In the narrative layer, we use our interpretation of the involvement of Termime in the experiment to reveal how she gave meaning to time in the life she lives in the Italian-Slovenian borderlands. The major advantage of displaying oral sources within the Journal of Digital History, is that it widens the possibilities for the consultation of oral sources. One can simultaneously listen to an interview fragment and read the narrative analysis of the fragment. Moreover, one can watch how the analysis was conducted in the digital tool Clarin Elan.

<!-- #region tags=["hermeneutics"] -->
## Expanding the Scheme of the Digital Research Process

Fickers and others developed an ‘ideal-typical scheme of the research process, demonstrating the concept of digital hermeneutics as a combination of digital literacy (skills) and critical reflection’ throughout ‘fluent, interconnected’ stages (<cite data-cite="8820477/Q827WAU3"></cite>). The process distinguishes the four digital history practices of ‘search’, ‘data management & curation’, ‘analysis’ and ‘visualisation, interpretation, publication’, which are each linked to their hermeneutic counterparts ‘algorithm criticism’, ‘digital source criticism’, ‘tool criticism’ and ‘interface and simulation criticism’ (<cite data-cite="8820477/Q827WAU3"></cite>, 10).
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
The path we followed during our research adheres to this process to some extent, but not entirely. We distinguish a preparation stage for the citizen science experiment, including the creation of a website as well as the selection of participants, the latter only partly through a digital search method (see ‘Preparing the Experiment and Search Criticism’). This was followed by a ‘data collection, management and curation’ historical practice combined with digital source criticism (See ‘Making Sources’) and tool criticism, including reflections on the use of transcription software Wreally (See ‘Transcribing Sources’). We subsequently selected the data for our analysis, which we considered as a second moment of digital searching, this time with the help of qualitative research software MAXQDA (See ‘Selecting Termime’). We then conducted the analysis of the monologues and dialogues gathered during the experiment by means of the software program Clarin Elan, which required a critical reflection on the capacities of this digital tool. Finally, we carefully considered how to present a selection of our oral sources to the listeners and readers of this article in order to communicate our findings, a historical practice that goes beyond visualisation. We therefore propose exchanging the words ‘visualisation, interpretation, publication’ for the more general ‘presentation’, as seen in our subheading ‘Presenting Termime’s monologue’.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
A next step was to discuss the third genre of storytelling included in the Talking Borders project: the digital café. To that end, we needed to inform our readership about the selection and presentation of data in the digital café, and offer interface criticism as the hermeneutic counterpart (‘Developing the Digital Café’). This is followed by a narrative analysis of Termime’s performance in the digital café. Prompted by our experience of working with the Journal of Digital History template, rather than discussing ‘publication’ within the visualisation stage of the research process, as proposed by Fickers and others, we decided to add another stage to our path, composed of what we call the historical practice of ‘digital dissemination’ and accompanied by a hermeneutic ‘output criticism’. Our research process can be summarised as displayed in the following figure:
<!-- #endregion -->

```python jdh={"module": "object", "object": {"source": ["Modified Digital Hermeneutics Scheme, originally published by \u00a9 Andreas Fickers, Ghislain Sillaume et al., 2021. Licensed under Attribution-NonCommercial-ShareAlike 4.0 International. The new version removed the term 'Publication' from the fourth cycle 'Interface & Simulation Criticism' and is extended by the fifth cycle 'Output Criticism'."]}} tags=["hermeneutics", "figure-digital-history-practices-*"]
from IPython.display import Image
display(Image("media/alternative_graph.png"))
```

<!-- #region tags=["hermeneutics"] -->
## Preparing the Experiment and Search Criticism
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
The Talking Borders experiment consisted of three stages: the collection of monologues, dialogues, and the digital café. The monologues and dialogues were produced and collected on a single day during the conference, while the digital café went online after the conference. The conversations gathered within Talking Borders each consisted of a twenty-minute monologue given by either a citizen scientist or a border scholar. This was followed by a twenty-minute dialogue between two interlocutors, either two citizen scientists or a citizen scientist and a border scholar, prompted by the question: ‘What does a border mean to you?’ In total, 21 conversations between a citizen scientist and a border scholar and 18 between two citizen scientists occurred. This resulted in a total of 57 citizen science monologues and 22 border scholar monologues. We also possess 18 dialogues between two citizen scientists and 21 dialogues between a citizen scientist and a border scholar. Owing to technical problems during the experiment, 3 dialogues between a border scholar and a citizen scientist, one between two citizen scientists, as well as 5 citizen science monologues and 2 border scholar monologues were never recorded. Following the conference on 10 July 2018, we hosted a global digital café that functioned as an online discussion forum. The digital café operated for 100 working days, where we posted extracts from the conversations to facilitate an environment for discussions between the citizen scientists and the border scholars.
<!-- #endregion -->

<!-- #region jdh={"object": {"source": ["Number of Participants per Conversation Format"], "type": "table"}} tags=["hermeneutics", "table-participants-per-*"] -->
| Participant | Monologue | Dialogue | Digital Café |
|-----------------|-----------------|-----------------|-----------------|
| Border Scholars  | 22 | 21 | 4 |
| Citizen Scientists | 57  | 59 | 9 |


<!-- #endregion -->

<!-- #region jdh={"object": {"source": ["Number of Participants who participated in all Conversation Formats"], "type": "table"}} tags=["hermeneutics", "table-participants-all-*"] -->
| Participant        | Number |
|--------------------|--------|
| Border Scholars    | 3     |
| Citizen Scientists | 9     |

<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
The citizen scientists came from a wide range of disciplinary backgrounds in the humanities and social sciences. Their specific background depended on the scholar with whom the Principal Investigator was in contact at the various border region universities and research institutes involved in the project. The scholars were recruited from within the network of scholars working at the Institute for Eastern European History at the University of Vienna. Approximately 44% of the citizen scientists were recruited from history departments, especially the participants studying at universities in Rzeszów (Poland), Lviv (Ukraine), Sarajevo (Bosnia-Herzegovina), Novi Sad (Serbia), Cluj (Romania) and Trieste (Italy). Other disciplinary backgrounds included education science – participants from Vienna (Austria) – and anthropology – the majority of citizen scientists from Zagreb (Croatia) and Ljubljana (Slovenia). The participants recruited to represent the Czech Republic and Slovakia, about 11% of the total number of participants, studied at the multilingual Komenský secondary school in Vienna. The Hungarian partner, employed at the Central European Service for Cross-Border Initiatives (CESCI), approached seven universities to recruit citizen scientists from Hungary. All students, with the exception of those from the University of Vienna, were invited to participate and had the option to decline. They were provided with complimentary travel, accommodation in Vienna, and a reception at the Polish Embassy. The students from the University of Vienna participated in the event as part of their 'Introduction to Scientific Methods' course at the university. The experiment was conducted during their scheduled course hours, requiring no additional time commitment from them.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
The composition of the citizen scientists was based on the indication of mother tongue in the 1910 census (published in 1912), the last of the decennial censuses conducted under the Habsburg monarchy. The methodology practised in these censuses differed slightly between regions: while citizens were asked about their mother tongue in Transleithania, in Cisleithania and Bosnia they were asked to indicate the language they used in everyday conversation. In addition, Bosnian ‘Serbo-Croatians’ (the inhabitants of Bosnia who identified ‘Serbo-Croatian’ as their mother tongue) were then differentiated according to their religion and minorities constituting less than 1% of the populace were not considered. (<cite data-cite="8820477/3LJPVN9B"></cite>, 557.)
<!-- #endregion -->

<!-- #region jdh={"module": "object", "object": {"source": ["table 1: Composition of citizen scientists based on census data from 1910"]}} tags=["hermeneutics", "table-mother-tongue-*"] -->
Mother tongue|Percentage of the population in 1910|Proposed number of of Citizen Scientists|Actual number of participants
---|---|---|---
German|23.9|24 (from Austria)| 18
Hungarian|20.2|20|5
Czech|12.6|13|2
Polish|10|10|8
Ukrainian|7.9|8|7
Romanian|6.4|6|6
Croatian|5.3|5|4
Slovakian|3.8|4|2
Serbian|3.8|4|4
Slovenian|2.6|3|3
Italian|2|2|2
Bosnian|1.2|1|1


<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
Although some participants withdrew from the project during the preparation phase, many of them were eventually replaced. The success of the recruitment process for Talking Borders differed greatly depending on the respective country. The low participation rate for Hungary can potentially be explained by the fact that parliament passed a law at the end of June 2018 making the provision of assistance to asylum seekers a criminal activity for lawyers and activists. Although visiting a seminar on borders and migration was not included in the scope of the legislation, it may have put people off.
<!-- #endregion -->

```python
!pip install plotly
!pip install --upgrade pip
```

```python jdh={"module": "object", "object": {"source": ["Distribution of citizen scientists by country in percent"]}} tags=["figure-pie-chart-citizen-scientistists-country-*"]
import plotly.graph_objects as go
import plotly.io as pio
pio.renderers.default = 'notebook'

# Data for the pie chart
labels = ['Austria', 'Poland', 'Ukraine','Romania', 'Hungary', 'Croatia', 'Serbia', 'Slovenia','Italy','Slovakia', 'Czech Republic', 'Bosnia and Herzegovina']
values = [29, 13, 11, 10, 8, 7, 6, 5, 3, 3, 3, 2]

# Create the pie chart figure
fig = go.Figure(data=[go.Pie(labels=labels, values=values)])

# Set the layout
fig.update_layout(title='Distribution of Citizen Scientists by Country (in %)')

# Set the font color to white
fig.update_traces(textfont_color='white')

# Display the chart
fig
```

<!-- #region tags=["hermeneutics"] -->
The border scholars specialised in borders or border-related research topics, with only a minority being historians. The disciplines of linguistics (4) and sociology (4) were the best represented, followed by economics (3), history (3), geography (3) and media studies (2). Other disciplines with one representative each were political science, urban planning, communication studies, anthropology, public administration and African studies. Most of the scholars worked in the United States (seven), followed by France (four) and the United Kingdom (three). Only three border scholars were employed within the former borders of the Habsburg monarchy (in Slovakia, Hungary and Poland). Other countries included Denmark, Germany, Canada, Italy, Switzerland and Finland.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
During the 2018 spring semester, [anonymised] taught an introductory course on scientific methods for Bachelor students in education at the University of Vienna, in which 19 students were involved in preparing the experiment. They brainstormed and discussed what they wanted the project website to look like. This process of requirement engineering resulted in a brief for the website programmer. They then co-created the website for the citizen science project (<cite data-cite="8820477/3NFGF8UP"></cite>). The website was an information site about the citizen science experiment, where participants could also download key documents such as the informed consent form. At the start of the experiment, each participant was assigned a pseudonym as a user name. The real names of the interview participants are known to the members of the project team.
<!-- #endregion -->

```python jdh={"module": "object", "object": {"source": ["figure 3: A cartoon produced by citizen scientists Christopher Pomerenke and Selina Ehrenhofer during preparations for the citizen science experiment"]}} tags=["hermeneutics", "figure-cartoon-*"]
from IPython.display import Image
display(Image("media/cartoon.png"))
```

<!-- #region tags=["hermeneutics"] -->
The students on the course at the University of Vienna acted as citizen science ambassadors for the other citizen scientists before their arrival in Vienna, mainly via email and, if both parties agreed, via WhatsApp. On the day before the experiment, a try-out session was organised for the citizen scientists where they were given an introduction to interviewing, digital recording and transcription. There was also time to test the digital dictaphones.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
This article uses the term ‘citizen scientists’ to refer to the bachelor students, although we acknowledge potential issues linked to the term ‘citizen,’ which often refers to  a legal or national status that excludes non-citizens, such as immigrants, refugees, and stateless individuals. In this study, we define 'citizen' as being a member of a community.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
## Making Sources
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
Participants prepared for the experiment in different ways. While some citizen scientists read out prepared written monologues (see [conversation 4](https://github.com/jdh-observer/6ig87tC5GKjQ/blob/main/script/transcripts/004_Tec_Creator.docx)) or consulted notes during the conversation (see [conversation 36](https://github.com/jdh-observer/6ig87tC5GKjQ/blob/main/script/transcripts/036_Gift_GamingScorpion.docx)), others came to the experiment without preparation. The latter struggled to define concepts or come up with the right words in English, which was the language of the experiment but not the mother tongue of the citizen scientists. The level of preparation had an impact on the length of the monologue and the quality of the ensuing dialogue (see, f. ex., the two exceptionally long monologues in [conversation 25](https://github.com/jdh-observer/6ig87tC5GKjQ/blob/main/script/transcripts/025_LostFairy_Response.docx)).
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
On the day of the experiment, the participants were seated in groups of two in proximity to each other in the main hall of the venue. They were given a time slot of 1.5 hours to hold the conversation. Each participant received a digital dictaphone to ensure that conversations were recorded twice in case one device experienced technical issues. Despite the trial run the day before, some citizen scientists did not manage to record their dialogues or were unsure about the instructions (Pseudonyms: Life, Wolverival, Zerobot, GamerKraken, Positive Twin, Baroqueen, Spillager). After 18 minutes of monologue, Termime, for example, said:
<!-- #endregion -->

```python tags=["narrative", "hermeneutics", "sound-conversation-length-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_1.m4v')  # Replace with the actual file path

```

<!-- #region tags=["hermeneutics", "dialog-conversation-length-*"] -->
Termine | Aura
------ | ---
And euhm, euhm, what can I say? Hm. Euhm. So, hm. But we have to do 20 minutes each? | &nbsp;
&nbsp; | Oehm, yeah, but I have also only 15 minutes.
Yeah, you were twelve. Ok, I have to talk at least two minutes. | &nbsp;
&nbsp; | Okay.
Okay. | &nbsp;
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
Even though most of the conversations were about borders, some conversations veered away from this path. In one dialogue, for example, the citizen scientists began to discuss who they were rooting for in the football World Cup that was taking place in Russia in 2018:
<!-- #endregion -->

```python tags=["sound-worldcup-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/PA_AUDIOCUT_1.m4v')  # Replace with the actual file path
```

<!-- #region tags=["hermeneutics", "dialog-worldcup-*"] -->
| Priestar | Aspect |
|------- | ------ |
| So, who do you think about it? Who will win the World Cup? | &nbsp; |
| &nbsp; | Well, Croatia, I hope. I hope Croatia, yeah yeah.
| This is very bad, very, so this is very bad for me because yeah | &nbsp; |
| &nbsp; | Because England... |
| I have a father from, aeh, but it deserves, absolutely!<br> Nowadays Croatia, it’s like 20 years ago when<br> Croatia had the best striker in all Slavic world.<br> Davor Suker, was the best. | &nbsp; |
| &nbsp; | Yeah, yeah. But I like this team but I have no problems with other teams too. I like (unclear) team.<br> The only one who I don’t like is Harry Kane.<br>
| Oh no Harry Kane is the best out of England’s team. Because, without Harry Kane England, It's no good. | &nbsp; |
| &nbsp; | Yeah, yeah it is true that he can score goal, but I don’t like him. I don’t know why.<br>
| Could be worse. So. | &nbsp; |

<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
In many other conversations we can observe how participants expressed appreciation or admiration for their interlocutors’ contributions. This phenomenon was also observed in the conversation between Termime and Aura.
<!-- #endregion -->

```python tags=["narrative", "hermeneutics", "sound-admiration-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_2.m4v')  # Replace with the actual file path
```

<!-- #region tags=["hermeneutics", "dialog-admiration-*"] -->
| Termine | Aura |
| ------- | ------- |
| really well<br> That text that you wrote was very | &nbsp; |
| &nbsp; | Okay, thank you |
| [chuckles] You're welcome | &nbsp; |
| &nbsp; | Bu it's only the Google translator |
| ah okay | &nbsp; |
| &nbsp; | the text was in German
| It was okay | &nbsp; |
| &nbsp; | and eaah in German is it much better |
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
## Transcribing Sources
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
Taped conversations were first transcribed with the help of Wreally transcription software, and later corrected by an English native speaker. Wreally transcription software, given a conversation between two native speakers in a relatively quiet environment, is able to produce 90% accurate transcriptions of oral sources. However, the conversations took place between two non-native speakers in a noisy environment, and the dictaphone was often not placed close enough to record the conversation clearly. The results were frequently incomprehensible. So we needed to listen to the recordings closely in order to correct and shape the transcript. The dialogues between citizen scientists proved particularly challenging. The amount of background noise, the varying levels of English and the lack of an experienced interviewer to help shape the dialogue served as obstacles to the production of a satisfying text. Nevertheless, despite occasional gaps, as the speaker struggled to find the appropriate words or external factors rendered their words inaudible, it was ultimately possible to capture an authentic exchange between people of different backgrounds discussing what borders meant to them.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
The aim of the transcription was to produce a readable, authentic record of the dialogues, to capture the voices of the participants, their rhythms and idiosyncrasies of speech. Thus their words are recorded as they were spoken, with the majority of grammatical and lexical errors, as well as any distinguishing verbal tics (‘so to speak’, ‘you know’, ‘like’, ‘let’s say’) included. Errors were only corrected in very extreme circumstances when a speaker was having serious difficulty in making him or herself understood. Where this was done, the added word is included within parentheses, e.g. ‘I had (gone) to the mountains.’ Wherever possible, though, mistakes have been left unchanged. It is to be hoped that the judicious use of punctuation throughout the transcriptions will aid the reader in deciphering the meaning of what was originally said. Unfinished words or sentences that were begun but left incomplete have been excised. Where a speaker went back to correct him or herself, the corrected version of the sentence is the one that has been recorded. Where speakers discussed practical matters, such as how to operate the dictaphone, the time left to speak, and so on, a brief summary has been added in parentheses, e.g. (they talk in German about what to do next). When the utterance constituted a noise intended to indicate consent, disagreement or surprise, this has been recorded accordingly, e.g. ‘Ummm, not really.’ Utterances that did not interrupt the narration of the interviewee but merely served to indicate, say, agreement, are not transcribed. Nonverbal expressions with an emotional meaning are indicated between brackets, e.g. (laughs). Where it proved impossible to identify a geographical reference, or where the recording was incomprehensible or inaudible, it is marked (unclear). Where the transcriber was unsure about an unclear word, the word is included in parentheses with a question mark.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
For the narrative analysis of the monologues, we opted for an ethnopoetical transcription of a selection of fragments (<cite data-cite="8820477/6VPUMXCI"></cite>). Ethnopoetics uses poetic lines instead of prose, and removes interpunctuation, so as to open up the transcription to a wider interpretation, for example including silences and emphases. In the case of Termime’s monologue, for example, the first transcription of the first fragment analysed was as follows:
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
> So to me the border it has a very familiar, like it’s very familiar to me, because I grew up on the border with Slovenia, and in fact, I am part of the Slovene minority in Italy. So, since I was born, I was little, I always with my family, we always travelled from Italy to Slovenia like on the regular basis and daily. So to me the border wasn’t at the beginning when there was still like the physical border with these (unclear) that goes up and down there was like, I wouldn’t call it a shock, because I grew up with it, so I got to know it, but like police stop you at the border and said to you, ‘give me your ID give me your (in Slovenian)’ – which was a type of passport the people who lived on the border had. That was quite like it wasn’t normal for me. And then when the border was taken down, and now you can pass it whatever you like it or how many times you like it, now it’s different.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
The ethnopoetical transcription of the same fragment brings, for example, the repeated words ‘very familiar’ to the foreground.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
> so to me the border it has a very familiar<br> like it’s very familiar to me<br> because I grew up on the border with Slovenia
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
In the dialogues, interjections such as ‘hm’, ‘oh’ or ‘wow’ pointed to implicit knowledge about the interlocutors’ opinions: they ‘reveal what is going on in speakers’ minds in relation to the situation they are in’ (<cite data-cite="8820477/4FST6UNI"></cite>, 8). In the following example we see how the interpretation of a dialogue fragment changes if we pay attention to the interjections made by the interlocutors.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
A comparison of the first and second transcription of a fragment from the dialogue revealed how the interpretation of a dialogue fragment changes:
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
> **Aura**: _I didn’t know anything about Sopron, for example, I, I only see that the people, the the country is, Austria is, Austria is a rich country. Hungary was always a, a poor country, and, but I had never_
<!-- #endregion -->

```python tags=["hermeneutics", "sound-rich-poor-countries-*", "narrative"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_3.m4v')  # Replace with the actual file path
```

<!-- #region tags=["table-rich-poor-countries-*", "dialog-rich-poor-countries-*"] -->
| Termime | Aura |
| ------- | ------- |
| I didn’t know anything about Sopron for example I<br> I<br> I only see that the people<br> eh the the the countries | &nbsp;
| &nbsp; | Mhm [agreeingly] |
| Austria<br> Austria is<br> Austria is a rich country | &nbsp; |
| &nbsp; | Yes |
| Hungary was always a<br> a poor country<br> and ehm yeah | &nbsp; |
| &nbsp; | Okay [chuckling with doubt]
| But<br> I had never | &nbsp; |
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
The second fragment reveals two particularly striking elements. Firstly, it demonstrates Aura’s struggle to formulate his argument in a foreign language (English), suggesting that his simplistic description of Austria being ‘rich’ and Hungary being ‘poor’ might have been more nuanced in his mother tongue. This is not obvious in the first transcription, which suggests a degree of fluency and therefore leaves little room to interpret whether Aura personally identifies with his statement or not. Secondly, it indicates whether Termime’s interjections express agreement or disagreement. Moreover, the last utterance articulated by Termime in the second sequence, ‘Okay’, is not part of the first transcription. This utterance suggests an emotive response of doubt towards Aura’s statement about the economic discrepancies between Austria and Hungary, an arguably important articulation that adds additional information to Termime’s perception of her interlocutor and the content of their conversation.
<!-- #endregion -->

## Introducing Termime

<!-- #region tags=["narrative"] -->
Termime was selected from the University of Trieste, where she was enrolled on a Bachelor course in international relations. She was recruited for the Talking Borders experiment by Giulia Caccamo, the lecturer of a course on contemporary history. Termime considers herself a member of what she calls ‘the Slovenian minority in Italy’ (see [conversation 64](https://github.com/jdh-observer/6ig87tC5GKjQ/blob/main/script/transcripts/064_Aura_Termine.docx)). In the conversation with her interlocutor Aura, she explains how she grew up in Italy at the border with Slovenia and frequently travelled back and forth between Italy and Slovenia. To understand the implications of identifying as part of the ‘Slovenian minority’ in Italy, we must look at the history of the region.
<!-- #endregion -->

Following the dissolution of the Austro-Hungarian monarchy, the peace treaties signed at the Paris Peace Conference in 1919 caused a major redrawing of the map of Europe. Two treaties recognised the independent status of newly emerged nation-states on the territory of the former Austro-Hungarian Empire. The Treaty of Saint-Germain-en-Laye divided the Austrian part of the Dual Monarchy between the interwar Austrian state, Czechoslovakia, Poland, Romania, Italy and the Kingdom of Serbs, Croats and Slovenes. The Treaty of Trianon divided the Hungarian part of the Dual Monarchy between the interwar Hungarian state, Romania, Czechoslovakia, the Kingdom of Serbs, Croats and Slovenes, Austria and the Free State of Fiume (nowadays Rijeka), which emerged in 1921, operated under the auspices of the League of Nations and was annexed to Italy in 1924. In the Adriatic, the division of land between Italy and the Kingdom of Slovenes, Croats and Serbs was specified in the 1920 Treaty of Rapallo. The Austrian Littoral (also referred to as the Venezia Giulia) was a strip of land east of Trieste that was included in Italy; it contained approximately 300,000 or one quarter of the world’s Slovenian-speaking population (<cite data-cite="8820477/CKCWHURP"></cite>, 4).

<!-- #region jdh={"module": "object", "object": {"source": ["Changes to the Italian Eastern borders from 1920 to 1975. Public Domain. Source: Wikipedia."]}} tags=["figure-changes-to-border-*"] -->
![Image](https://upload.wikimedia.org/wikipedia/commons/9/9d/Litorale_1.png)
<!-- #endregion -->

Most of this territory switched to Yugoslavian state sovereignty in the aftermath of the Second World War, which also led to the displacement of between 200,000 and 350,000 ‘ethnic Italians’ (as they were described at the time) from the Venezia Giulia to the other side of the Slovenian-Italian border (<cite data-cite="8820477/DQ3YL59B"></cite>). The city of Trieste was the most important exception; it operated as a Free Territory under the control of the United Nations Security Council in between Italy and Yugoslavia for seven years, before being split into three in 1954 and divided between Italy, which received the urban area and the port; the socialist republic of Slovenia (part of Yugoslavia), which received access to the sea and developed a new urban centre; and the socialist republic of Croatia (also part of Yugoslavia) (<cite data-cite="8820477/HFYFSL9Z"></cite>). A Slovenian minority remained in Italy – a census in 1971 recorded 52,194 Slovenian speakers in Friuli-Venezia Giulia (<cite data-cite="8820477/7BLBZR4G"></cite>).


At least from the mid-1700s, Termime’s family lived in the Gorizia province, although the borders changed over time. They were Slovenian speakers living in the Habsburg Empire, and in Italy following the adoption of the Treaty of Rapallo in 1920. Only one of her grandmothers was born in 1940 in the Idrija province in the Kingdom of Italy, which became part of Yugoslavia in 1947. However, once she married Termime’s grandfather, she moved to the Gorizia province of Italy.


In the 1950s, Yugoslavia feared an economic regression and attempted to circumvent an economic decline by reforming its migration policies and allowing citizens to go abroad for work purposes, most of them to the Federal Republic of Germany. Following the signing of the London Memorandum in 1954 and the delimitation of the borders, the border region turned into a site of cross-border activity. While in 1954, around 3,000 Yugoslavian citizens worked in Western Europe (2,000 of them in West Germany), by 1961 the number had risen to 28,000 (of which 17,000 were in West Germany). By the late 1960s Yugoslavia’s open-border policy was what famously distinguished it from the Soviet model (<cite data-cite="8820477/P85Z4LZU"></cite>, 74–76). Socialist Yugoslavia followed a different border regime from what is usually associated with other socialist countries behind the ‘Iron Curtain’, such as the Soviet republics.


The Italian-Yugoslav border along the cities of Trieste and Gorizia was a special case. The former province of Gorizia was divided between Yugoslavia and Italy in 1947, and 74 percent of its population was incorporated into Italy. In 1954, after the short-lived period of the Free Territory of Trieste (1947–1954), the city of Trieste was annexed by Italy. Recognising the negative economic impact the new border could potentially have, already in 1949, Italy and Yugoslavia signed the Udine agreement allowing special border passes for borderland citizens who owned property on both sides of the border. This was followed by a further relaxation of the cross-border regulations for all border dwellers, which increased border traffic in Gorizia by 900 percent (<cite data-cite="8820477/GJC3BGW4"></cite>, 182). As a result, during the Cold War, the border between Italy and Slovenia (Yugoslavia) was exceptionally open. By the 1970s it had become a hotspot of cross-border practices, with Italians crossing to Yugoslavia daily for shopping and tourism, and Slovenians crossing for work and grocery shopping (<cite data-cite="8820477/GJC3BGW4"></cite>). Then followed the end of the Cold War, the collapse of Yugoslavia, and Slovenia’s membership of the European Union in 2004. Bialasiewicz and Minca described its inclusion into the Schengen Area three years later as a ‘surreal experience for Trieste’ because the border ‘suddenly became much more important than it had ever been over the previous decades [...] In its disappearance, the border was reborn – but as a symbol of something else. The fiction of a limit was thus transformed into the fiction of no limits: the fallen ex-Cold-War border became a symbol of a “borderless Europe”’ (<cite data-cite="8820477/J2CVNUTW"></cite>, 1085; <cite data-cite="8820477/VIN7VLMB"></cite>).


Today, the estimated number of inhabitants identifying as a Slovenian minority in Trieste varies. Statistics provided by the Italian National Institute of Statistics in 2015 suggest that a total of 46,000 Slovenian-speaking residents live in Friuli-Venezia Giulia (FVG) (corresponding to 3.7 percent of the entire population in that region), 25,000 of whom live in the Province of Trieste (corresponding to 10.6 percent of the entire population in that region). However, the Slovene Research Institute (SLORI) suggests twice as many Slovenian-speaking residents in FVG (<cite data-cite="8820477/JNWJBU8I"></cite>, 53). Officially, the use of Slovenian as a minority language is regulated under National Law 38/2001, which accepts it as an official monitory language but does not require authorities to use it. This results in Italian being the official language in use in day-to-day activities in Trieste. Despite the official recognition of Slovenian-speaking schools and media broadcasting in Trieste, the use of Slovenian is decreasing (<cite data-cite="8820477/3J63LLCQ"></cite>, 108). Slovenian is predominantly used in intimate contexts such as with family members, or in social contexts, such as Slovenian associations and organisations (<cite data-cite="8820477/EBJEKEBH"></cite>, 199). It is therefore not surprising that Termime chooses to speak Slovenian with her family members but Italian in most other situations.


According to the official website of the Regional School Office, the FVG region has eight schools and six higher education institutions in which Slovenian is the language of instruction ([website](https://usrfvg.gov.it/it/home/menu/uffici/ufficio-scuole-slovene/scuole/), USRFVG 2022). In the provinces of Trieste and Gorizia, these schools operate in the same way as Italian schools. By the end of secondary school, pupils are expected to have reached C1 level in Italian and Slovenian ([website](https://usrfvg.gov.it/it/home/menu/uffici/ufficio-scuole-slovene/presentazione/), USRFVG 2022). Like most Slovenian-speaking children (<cite data-cite="8820477/3J63LLCQ"></cite>, 109), Termime attended a bilingual school in Italy, where she was taught Slovenian as a first and Italian as a second language. She later attended the University of Trieste. For many Slovenian-speaking residents, the change from school to work or university shifts the social environment, bringing together many people from different mother tongue backgrounds and resulting in Italian being used by default as the main language of communication (<cite data-cite="8820477/EBJEKEBH"></cite>, 202). Termime presented herself as a member of the ‘Slovenian minority’, but also emphasised that she ‘definitely [has] more things in common’ with Italian culture.


Termime’s interlocutor Aura was born and grew up in Vienna, but spent his weekends and holidays in his grandparents’ village in the eastern canton of Burgenland, near the Hungarian border. The information he provides about his family background is sparse and difficult to decipher. His grandparents and mother were part of the Croatian-speaking minority in Austria. His grandparents learned German in school and honed their language skills during their professional career in Vienna (<cite data-cite="8820477/TRSW6ACK"></cite>). Given the fact that his ‘Mum’s side was communist’, we could potentially conclude that his family members voted for the communist party (<cite data-cite="8820477/KCHDHFDE"></cite>). Based on the scarce information we received about his father, we assume that he is an Austrian citizen living in Austria. Nevertheless, Aura indicated that he identifies more with Hungarian than Austrian culture and values. He stated that he shares ‘the same values’ and that Hungarian culture and cuisine is ‘very similar to ours’. By ‘ours’, he was most likely referring to his Croatian minority background (see [conversation 64](https://github.com/jdh-observer/6ig87tC5GKjQ/blob/main/script/transcripts/064_Aura_Termine.docx)). Aura does not reveal any information about whether he speaks Croatian, Hungarian or both languages.

<!-- #region tags=["hermeneutics"] -->
## Selecting Termime
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
To research the way in which citizen scientists referred to time during the experiment, we decided to carry out an in-depth analysis of one conversation. The experiment provided the possibility of conversating in three stages: the monologue, the dialogue and the digital café. While all citizen scientists produced a monologue and participated in a dialogue on the day of the experiment, not everybody participated in the digital café. The opportunity for digital participation stretched over 100 days, which might have been too time-consuming for most of the citizen scientists. Out of 62 citizen scientists, only 9 participated digitally, and four were exceptionally active.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
In the digital café, most comments were made by citizen scientist DeadSaint from Sarajevo (a total of 95). Termime, from Italy, posted 44 comments, and two citizen scientists from Serbia, Thinkerer and HammerTurkey, posted 27 and 12 comments respectively. The other five citizen scientists produced 1 to 3 comments each. Clearly, citizen scientists from Italy and Serbia were the most active. In order to be able to analyse contributions in the three genres of the experiment, we decided to choose a citizen scientist who was exceptionally active in the digital café, either DeadSaint or Termime. As we were interested in the interaction between citizen scientists, we opted for Termime, who was in dialogue with another citizen scientist, and not for DeadSaint, who conversed with a border scholar.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
## A Digital Analysis of Termime’s Oral Articulations
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
As Michael Frisch noted, the digital era brings ‘within reach all of the content and meanings in interviews not easily captured in transcription. Now we can see, hear, study, and select nuances that are not readily representable in transcripts, and often not lexical at all. This is what it means to say that the orality of oral history is moving excitingly back into primacy’ (<cite data-cite="8820477/RVAR4E8B"></cite>, 132). The software program Clarin Elan enabled analysis of the following parameters: intonation (affirmative, negation, excitement, etc.), exaggeration, repetition/clarification, emphasis, pauses and temporality. Working with the software was time-consuming, however, and we did not manage to work collaboratively within one digital working environment while being in different locations or to include different user statuses for the analysis of fragments, which would have enabled them to provide an Open Access version of pseudonymised fragments. We therefore opted to show readers and listeners an insight into our working method by means of this video:
<!-- #endregion -->

```python
from IPython.display import IFrame

src_url = "https://cdnapisec.kaltura.com/p/2753661/sp/275366100/embedIframeJs/uiconf_id/45459391/partner_id/2753661?iframeembed=true&playerId=kaltura_player&entry_id=1_7uy0dr3v&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=1_gjkkigo5"
IFrame(src_url, width=608, height=402)


```

## Narrating Termime’s Monologue


In her 20-minute monologue, Termime spoke about her past border experiences and shared her historical knowledge about borders. These utterances are inherently linked to how she described the way in which she deals with the past today. Termime started her monologue by recalling her past border experiences.

```python tags=["narrative", "hermeneutics", "sound-border-xp-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_4.m4v')  # Replace with the actual file path
```

<!-- #region tags=["dialog-border-xp-*"] -->
| Termine | Aura |
|-------- | -------- |
| so eahm to me the border it has a very familiar<br> like<br> it’s very familiar to me because<br> I grew up on the border with Slovenia | &nbsp; |
| &nbsp; | Yeah |
| and in fact<br> I am part of the Slovenian minority in Italy | &nbsp;
| &nbsp; | OK |
| so since I was born<br> I was little<br> I always<br> with my family we always travelled from Italy to Slovenia<br> like on the regular basis daily<br> so to me the border wasn’t at the beginning<br> when when there was still like<br> the euhm physical border with the (unclear) that goes up and down<br> there was like<br> I wouldn’t call it a shock<br> because I grew up with it so I got to know it<br> but like when euhm like the the police stop you at the border and said to you<br> give me your ID give me your prekusnica<br> which was a type of passport the people who lived on the border had<br> that was quite like euhm it wasn’t normal for me<br> and then when the border was taken down<br> and now we can you can pass it whatever you like it<br> or how many times you like it<br> now it’s different but eahm<br> so as I said | &nbsp;
<!-- #endregion -->

Born after the collapse of communism, Termime remembered how she could pass border control with a border traffic passport for borderland inhabitants, a practice that remained in place until the border was opened on 21 December 2007 when Slovenia entered the Schengen Area. Termime’s descriptions of the past support Bialasiewicz’s and Minca's observations of discrepancies at the Cold War border: ‘what makes this Cold War border particularly interesting from a political-geographic point of view is the tremendous gap between the rhetorical and symbolic “weight” of this border in the early Cold War imaginary - both at the national as well as the international scale, in many ways an “overdetermination” of the border, as Balibar (<cite data-cite="8820477/B2EDQNF9"></cite>) would term it- its subsequent reimagination following the Tito-Stalin split in 1948, and its ongoing lived experience’ (<cite data-cite="8820477/J2CVNUTW"></cite>, 1098).


Encouraged by Aura, who shared his monologue earlier, Termime narrated a contrast between crossing the border as a child and as a young adult. As a child, there was a tension; she described how crossing the Italian-Slovenian border was both ‘very familiar’ and yet ‘not normal’. Her understanding of normality at the moment of the experiment was of being able to cross the border without having to show one’s papers. This interpretation can be much more easily read from an ethnopoetic transcription than from the first transcription, thanks to which, for example, the repetitions of ‘very familiar’ and ‘always’ are given a poetic quality. Hearing the fragment, and analysing it in Clarin Elan, offers the additional advantage of noticing the affirmative intonation of the exaggerations ‘very familiar’, ‘on a regular basis and daily’, ‘whatever you like’, ‘as many times as you like it’. Especially prominent is how the fragment gains its temporal significance through emphasis on ‘still’, ‘and then’, and ‘now’, small words that are less noticeable in the written transcription but clearly indicate how Termime linked the past to the present.


The fragment does not offer us new historical knowledge about lived experiences in the borderlands. Even while recalling her own past experiences, Termime did not contextualise them within the Cold War era; interestingly, we receive no information about the fact that already from the 1960s onwards, crossing the border had become a living reality (<cite data-cite="8820477/VIN7VLMB"></cite>). Offering us only a brief insight into her own past border experiences, Termime’s contribution is similar to that of other citizen scientists. Citizen scientists frequently referred to their own past in their monologues, but these descriptions rarely went beyond their own lived experiences. Only in a few cases did citizen scientists relate how their ancestors lived during the Austro-Hungarian Empire, how these experiences were given meaning within their families for several generations and continued to affect their view of the world at the moment of the recording (see, for example, [conversation 85](https://github.com/jdh-observer/6ig87tC5GKjQ/blob/main/script/transcripts/085_Thinkerer_Golem.docx) or [conversation 26](https://github.com/jdh-observer/6ig87tC5GKjQ/blob/main/script/transcripts/026_Weaselfie_Idea.docx)).


The monologues recorded during the experiment were interactive (<cite data-cite="8820477/V5MRJS2B"></cite>). As Termime clarified in an email to us (16.01.2023) after the experiment: ‘Before beginning to record my conversation with my interlocutor Aura, he expressed that he didn’t know where Gorizia was located, which is why I referred to my hometown as being near Trieste since that was the town that was known to my interlocutor’. Termime also had the feeling that she needed to give a brief explanation of what the dissolution of the Austro-Hungarian Empire looked like from the perspective of Italian-Slovenian borderland inhabitants:

```python tags=["narrative", "hermeneutics", "sound-slovenian-italian-border-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_5.m4v')  # Replace with the actual file path
```

> the Slovenian and Italian border is also quite  
euhm torn apart because of the historical side  
because Gorizia and Trieste where I live  
which is the border of Italy  
was euhm from forever part of the Austro-Hungarian Empire  
so in reality euhm Gorizia and Trieste shouldn't be part of Italy  
they just  
have been there  
and after, after the war it was taken by Italy  
so there's also that aspect  
so the historical aspect  
which is  
it’s difficult


The historical knowledge Termime displays in her monologue is concise. Termime ironically mentioned that Trieste was ‘forever’ part of the Austro-Hungarian Empire, whereas in reality, it joined the House of Habsburg in 1382 as a free city. Her depiction of how Gorizia and Trieste became a part of Italian territory in the aftermath of the First World War seems to present a dichotomic view of eternal ‘Austrianness’ contrasted with an eternal Italian state which ‘took’ the territory. Termime did not adhere to the existing dominant narrative of memory in which Trieste is presented as a ‘cosmopolitan port city’ that is becoming ‘a battleground for competing understandings of territoriality, identity, and belonging’ (<cite data-cite="8820477/J2CVNUTW"></cite>; see also <cite data-cite="8820477/A8PZJFEA"></cite>, <cite data-cite="8820477/AUKIAN6I"></cite>).


Termime said that Trieste and Gorizia were ‘taken over’, after which she seems to bring in some reflection about that shift of sovereignty (‘they shouldn’t be there’). Did she want to say that Austrians resented the fact that Trieste and Gorizia were not a part of the interwar Austrian state (<cite data-cite="8820477/DQ3YL59B"></cite>)? That there were voices within Italy that deplored the lack of homogeneity within the interwar Italian state (<cite data-cite="8820477/QA55V2AY"></cite>, 107)? Or is she critical about the emergence of the idea of an ethno-national border, which arose in the late 19th century (<cite data-cite="8820477/G9Y5Z6B7"></cite>)? Termime did not clarify what ‘taken by Italy’ meant, and it is worth bearing in mind that the Austro-Hungarian army included Italian-speaking soldiers: ‘When between 350,000 and 400,000 Austro-Hungarian troops surrendered to Italy on 3 and 4 November 1918, only about a third consisted of ethnic Germans. (…) The rest included 83,000 Czechs and Slovaks, 61,000 South Slavs, 70,000 Poles, 32,000 Ruthenians, 25,000 Romanians and even 7,000 Italians.’ (<cite data-cite="8820477/TY8XC6F2"></cite>, 234; see also <cite data-cite="8820477/SHCB9CC7"></cite>). Termime’s understanding seems more in line with an Italian narrative on war memory developed in the interwar years focusing on a nationally conscious Italian army including the volunteers who had deserted from the Austro-Hungarian army and joined the Italian army after the outbreak of the First World War (<cite data-cite="8820477/L5WUW7NP"></cite>). It is striking that Termime contextualised the past so concisely. For example, she did not explain that after the Second World War, the Italian city Gorizia where she was born and grew up was divided by means of a border fence installed in the middle of the railway station square, leaving the old city centre on the Italian side and prompting the construction of a new city centre on the Slovenian side known as Nova Gorica (<cite data-cite="8820477/G9Y5Z6B7"></cite>).


Immediately after the second fragment, Termime continued with a fragment that indicates how she visited the past in order to give meaning to the present:

```python tags=["narrative", "hermeneutics", "sound-situation-today-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_6.m4v')  # Replace with the actual file path
```

> so the situation today  
I think that the people became much more open  
and much more like keen to know the difference  
so there’s like a saying that says that  
no there’s not a saying  
the pope said it that today borders should not be borders  
so walls  
but they should be bridges from a culture to another  
so we shouldn’t take the borders like  
the difference  
but a way to connect with someone that is different from you  
so you can learn something  
get the knowledge that you don’t have  
you can get to experience like food  
and see things that are different  
and euhm yes  
the border  
can became meeting point for people  
it doesn’t have to be difficult or something like that  
but then euhm  
so now the border where I live from Slovenia and Italy  
it’s it’s very it’s very peaceful it’s nothing happening there  
but I know that like between Slovenia and Croatia  
the border is  
it's a very conflicted area  
there are walls and you can’t really easily pass it  
or like that  
so I know that it’s a very diverse topic  
and it’s not the same everywhere  
like for example in America Trump wants to build a wall between Mexico and the US  
so you can see that like he he as he says  
he wants to take control of the situation  
but maybe  
the fact is that you are also kind of afraid of the difference  
and you don’t want it to come to your euhm to your nation


After stating that the past was ‘difficult’ in the second fragment, Termime continued explaining why today, it ‘doesn’t have to be difficult’ any longer, as peace is guaranteed (‘it’s very peaceful nothing is happening’). Termime perceived the ‘open’ Italian-Slovenian border in 2018 as a bridge. This perception adheres to a narrative that gradually developed within the region. The Friuli-Venezia Giulia region saw the creation of the Alps-Adriatic Working Group in 1978, which included regions from both sides of the Iron Curtain and improved transport connections, for example, and it also became part of the larger Trans-European Network in the 1990s. Border crossings became easier after the collapse of communism, the independence of Slovenia and its membership of the European Union. These initiatives contributed to a new understanding of the border as a bridge towards another culture (<cite data-cite="8820477/NK838DI9"></cite>, 40). Termime was not entirely sure at first where she had heard the analogy, but she then introduced the Pope as an authority figure to underline the importance of her statement. Less than a year before the citizen science experiment, Pope Francis had indeed said that ‘society should not create “walls but bridges” to encourage good relations among people’ (<cite data-cite="8820477/SPKKPYX7"></cite>). He did not explicitly refer to US President Donald Trump, who at that time was publicly pushing for the construction of a wall on the Mexican-American border, but it was generally understood that the insinuation was clear.


Termime’s narration here reached a higher degree of affection than in the earlier fragments. Her understanding of a border as a privileged place to ‘connect with someone that is different from you’ was first followed by four examples of ways in which people can meet across borders (through learning, acquiring knowledge, eating and observing), and then by an affirmative yes to an understanding of the border as a ‘meeting point’. She used contrast as a narrative technique, first with the past (it is now ‘much more open’, ‘much more’) and then with the Slovenian-Croatian and American-Mexican state border. Termime clearly prefers the open nature of today’s Italian-Slovenian border, maybe even more so because she is aware of its constructed character. Slovenia’s entry to the Schengen Area in 2007 turned the Slovenian-Croatian border into an external border of the European Union. When Croatia joined as the 28th Member State in 2013, the border between the two countries became an internal Schengen border. When the region became part of migrants’ Balkan corridor to other countries in the European Union in 2015, about one third of the border was fenced off and surveillance increased. It is somewhat puzzling that Termime finalised her monologue with:

```python tags=["narrative", "hermeneutics", "sound-Nova-Gorica-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_7.m4v')  # Replace with the actual file path
```

Her teleologically positive story ended with Gorizia/Nova Gorica taking on the role of European Capital of Culture in 2022. Whereas in 2022, Esch-sur-Alzette in Luxembourg was designated the title, in 2025, Nova Gorica will share the honour with Chemnitz ([European Capital of Culture](https://culture.ec.europa.eu/policies/culture-in-cities-and-regions/designated-capitals-of-culture)). But contrary to what Termime suggested, ‘that’s’ not ‘it’. It is remarkable that she did not mention the efforts by both the Slovenian government and the Italian government to harden the respective Croatian-Slovenian border or Italian waters in the Mediterranean Sea by denying asylum seekers the opportunity to exercise their rights and deporting people eligible to apply for refugee support instead of opening the national border (<cite data-cite="8820477/7L64HE4D"></cite>).


> there is this project going on for the best city in Europe  
for like the European prize  
and Gorizia which is the Italian city and Nova Gorica which is the Slovenian city wants  
want to apply together to the European best city of Europe like 2022 I think  
so just that gives it away  
what is the euhm like feeling in the air  
so that there is cooperation  
differences yes  
but so much cooperation and so much positivity  
and that’s it


An analysis of how Termime referenced time in her monologue revealed that her memories of her own past experiences are too concise to offer a deeper insight into past living experiences of borderland inhabitants and that the historical knowledge she displayed is too limited to decipher the dominant narratives to which she referred. The main purpose of her references to the Slovenian-Italian border in the past (that it was ‘difficult to cross’) was to juxtapose these with the meaning she attributed to that border in the present (‘borders are open’) and the future (the application of Gorizia to become a cross-border European capital). In other words, she constructed an entangled narration of the past, present and future in order to navigate her understanding of reality.  

<!-- #region tags=["narrative"] -->
## Narrating Termime’s Dialogue
<!-- #endregion -->

In the second part of the experiment, Termime engaged in a dialogue with citizen scientist Aura. While the monologue genre was a representation of individual experiences, the dialogue genre facilitated a conversation in which ideas and opinions were exchanged (<cite data-cite="8820477/6K25WIP8"></cite>, 148–149). Time references discussed in the dialogue between Termime and Aura were past and present border experiences, socio-political events in the year 2018 that sparked debates about state borders, questions of belonging, and generational differences in attitudes. Based on Landwehr’s concept of ‘Chronoferenzen’, we will now identify the multiple layers of temporality referenced in the dialogue and analyse how specific imaginaries of the past or future occurred.  


The dialogue between Termime and Aura was fuelled by information shared in the monologues. Termime began the dialogue with a question about Aura’s connection to Hungary. In his monologue, Aura had described how he spent his weekends and holidays as a child at his grandparents’ house in an Austrian village on the border with Hungary. Termime falsely believed that Aura grew up there. Despite this misunderstanding, Termime correctly concluded that Aura must have visited Hungary and began the dialogue by asking Aura about this experience.

```python tags=["narrative", "hermeneutics", "sound-Hungary-bg-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_8.m4v')  # Replace with the actual file path
```

<!-- #region tags=["dialog-Hungary-bg-*"] -->
| Termine | Aura |
| ------- | ------- |
| eh you<br> like<br> grew up when (unclear)<br> so on<br> on the Hungarian border<br> well on the Austrian border | &nbsp; |
| &nbsp; | yeah |
| yeah  with Hungary<br> and so you travel to Hungary then when<br> because you said that that you didn’t know<br> what to expect from | &nbsp; |
| &nbsp; | only with my parents<br> when they go shopping |
| ah yeah | &nbsp; |
<!-- #endregion -->

When Aura mentioned that he went shopping across the border, Termime explained that she had had similar experiences with her parents:

```python tags=["narrative", "hermeneutics", "sound-border-shopping-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_9.m4v')  # Replace with the actual file path
```

> Yeah me too  
me too  
we go to buy things in aeh


Termime and Aura agreed that they had both done cross-border shopping (across the Italian-Slovenian and the Austrian-Hungarian border respectively). In the 1970s, socialist Slovenia had already developed into a shopping destination for cheap products for residents in Italy, and Yugoslavian citizens crossed the border to Italy to buy luxury goods such as Levi jeans or Marlboro cigarettes (<cite data-cite="8820477/M9MZBR8D"></cite>, 66-68). Post-socialist Slovenia has adapted to the neoliberal economic system of Western European countries, opening the Slovenian market to desired Western products, which are nevertheless often sold at a lower price than in Italy (<cite data-cite="8820477/MJPS3VKP"></cite>, 100). According to newspaper articles, the number of Italians crossing the border to Slovenia to buy everything from meat to petrol has increased in the last 20 years ([Slovenian Times](https://sloveniatimes.com/number-of-italians-shopping-in-slovenia-on-the-rise/)).


Communist Hungary, on the other hand, became a major shopping destination for socialist countries within the Eastern bloc in the late 1970s and early 1980s, since some degree of free-market activity was in place (Michalkó and Timothy, 2001, 5). With the dissolution of state socialism in the 1990s, Western European residents began to cross the border to former socialist countries, especially Hungary and Poland, to purchase consumer goods at lower prices. At the same time, residents in former socialist countries engaged in informal cross-border trade practices by selling domestic products such as meat, vegetables and clothing abroad (<cite data-cite="8820477/FJ7W3EZ9"></cite>, 5). When state socialism came to an end in 1990, Hungary became the main destination for shopping purposes for its neighbouring countries because of the ‘central geographical location of the country, the well-established retail network, the pleasant shopping milieu, as well as the quality and variety of products and their favourable price/value ratio’ (<cite data-cite="8820477/VJUN37LE"></cite>, 1323). Since Hungary joined the European Union in 2004 and the Schengen Area in 2007, cross-border shopping has increased. By 2018, according to the Hungarian Central Statistical Office, 25 percent of all trips to Hungary from outside visitors were for shopping purposes ([KSH 2023](https://www.ksh.hu/stadat_files/tur/en/tur0005.html)).


The dynamic displayed by Aura and Termime while talking about shopping recurred frequently throughout the dialogue. Both interlocutors asked and answered questions in order to find shared experiences. Here is an example of them experiencing xenophobic remarks expressed by members of their home societies:

```python tags=["narrative", "hermeneutics", "sound-xenophopic-remarks-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_10.m4v')  # Replace with the actual file path
```

<!-- #region tags=["dialog-xenophopic-remarks-*"] -->
| Termime | Aura |
| --- | --- |
| &nbsp; | Yeah genau at the beginning<br> But in the last years it's |
| it's aeh | &nbsp; |
| &nbsp; | but with Orban they want to<br> to have the borders again and<br> also the people in in in the village<br> they also want to have the borders again because<br> they doesn't like the people from Hungaria<br> They they <br/> they think they are<br> criminal and aeh |
| Oh really | &nbsp; |
| &nbsp; | other aeh<br> I think that most of the the <br/> older generation in the village<br> are very arrogant and feel<br> think that Austria is much better than Hungaria and other aeh<br> I think that most of the the<br> older generation in the village<br> are very arrogant and feel<br> think that Austria is much better than Hungaria and |
| yes, superior than Hungary | &nbsp; |
| &nbsp; | yeah |
| and aehm yeah also Italians are like that<br> like<br> we are more important than you and so on | &nbsp; |
| &nbsp; | yeah |
| and eahm<br> yeah<br> It’s not really nice when you come from like<br> like me when you come from both sides |
| &nbsp; | yeah |
| and you see how everyone is behaving yeah | &nbsp; |
| &nbsp; | yeah |
| yeah I think that should be a thing that <br/> the people on the border should work on it it's true that | &nbsp; |
<!-- #endregion -->

When Aura stated how especially older residents in rural areas (most likely he is referring here to his grandparents’ village) tend to be ‘arrogant’ and do not ‘like the people from Hungary’ because they are ‘criminal’, Termime expressed how she observed a similar attitude amongst ‘Italians’ towards others. The citizen scientist stated how the Italian borderland inhabitants she encountered (‘people on the border’) believed they are ‘more important’ than Slovenians. Termime did not specify whether she was referring to Slovenian citizens of Slovenia, or Italian citizens speaking Slovenian. In contrast to Aura, Termime did not specify an age group, but generalised the people she engaged with: ‘also Italians are like that’. As in the previous sequence, Aura and Termime indicated that they had shared a contemporary experience by living in or frequently engaging with a borderland community (<cite data-cite="8820477/Z5VWIYTF"></cite>).


While Termime’s and Aura’s dialogue unfolded with an exchange of contemporary borderland experiences, it also showed the use of absent imaginaries of the past. The imaginaries of the past remained vague and contradictory and co-existed with assessments of the present. These imaginaries did not reference the Austro-Hungarian history of Termime’s and Aura’s home countries. Instead, the temporal focus of historical references was shifted towards the past 70 years. Why were these specific imaginaries of the past chosen over others? The citizen scientists may have related to the past through their grandparents’ and parents’ memories, as well as through their own memories as children growing up in the late 1990s and the beginning of the 21st century. It might have felt more natural for Termime and Aura to reference a time period that is more tangible for them. The historical references used by Termime and Aura indicate that they regard the past as a time lived by their parents and grandparents not so long ago, rather than as historical periods academically often referred to as ‘communist’ and ‘post-communist’ times. A second explanation could be that they considered their knowledge about other historical periods, including the Austro-Hungarian past, to be limited. While Termime provided concise information about the Austro-Hungarian Empire in the written monologue that she had prepared prior to the experiment, in the unscripted situation of the dialogue guided by the interlocutors’ ability to present and discuss certain topics without written notes, she no longer referred to this historical period.


The imaginaries of the communist and post-communist past articulated in the dialogue remained vague and partially flawed, and were deployed with the aim of giving meaning to the contemporary reality. Both interlocutors recalled for example that their parents had experienced a strict border regime under communism and that this has shaped the current relationship between inhabitants on both sides of the border. Termime explained how her parents grew up in Italian Gorizia, on the border with the former Yugoslavia. She pondered whether the strict socialist border regime may have stoked fears among the population on both sides of the border, resulting in conflicts that are still visible today.

```python tags=["narrative", "hermeneutics", "sound-communism-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_11.m4v')  # Replace with the actual file path
```

<!-- #region tags=["dialog-communism-*"] -->
| Termime | Aura |
| --- | --- |
| yeah also eahm Italians are like that<br> like<br> we are more important than you | &nbsp; |
| &nbsp; | yeah |
| and so on<br> and eahm<br> yeah<br> It’s not really nice when you come from like<br> like me when you come from both sides | &nbsp; |
| &nbsp; | yeah |
| and you see how everyone is behaving yeah | &nbsp; |
| &nbsp; | yeah |
| yeah I think that should be a thing that<br> the people on the border should work on it it's true that<br> like my parents<br> they aehm<br> they grew up like with a strict border with Yugoslavia | &nbsp; |
| &nbsp; | yeah |
| so aehm<br> you also couldn't like<br> it was like on the other side there was someone different but they had their reasons<br> like aeh it was like<br> aehm<br> I think it's all connected with history<br> because maybe the the people that live in the village near the border with Hungary<br> they had some experiences that<br> like driven them apart from the thinking like that we should go on the other side<br> And because where I live it was like that<br> it was full of tension and conflict<br> till now<br> Because aeh<br> yeah<br> it wasn't really<br> really easy<br> so | &nbsp; |
<!-- #endregion -->

Termime did not give any details as to what specific ‘tension and conflict’ at the border between Italy and Yugoslavia had lasted ‘till now’ and may not have been ‘really easy’. She may have been referring to the question of whether Trieste and Gorizia should belong to Slovenia or Italy, as discussed in the analysis of her monologue. The description of the border between Italy and Yugoslavia also remains vague. Indeed, following the Second World War, Yugoslavia had a ‘strict border’ that controlled the movement of traffic and people into the country. But already in 1948, Yugoslavia experienced a liberalisation of its migration policies and an increase in cross-border travellers (<cite data-cite="8820477/GI2GB8AN"></cite>).


How did Termime understand the ‘strict border’ between Yugoslavia and Italy? Maybe her parents shared memories with her about their life at the border? Maybe her understanding of a ‘strict border’ is a simple equation of border controls? Termime was born in 1998, almost one decade before Slovenia joined the Schengen Area in 2007. Termime had already enjoyed freedom of movement within the European Union as an Italian citizen since her birth, and she frequently travelled to Slovenia as a child. During these border crossings, she experienced regular border controls, including the verification of identification documents. This childhood memory, paired with her experiences after Slovenia’s incorporation into the Schengen Area in 2007, may have led her to a flawed understanding of the definition of a strict border. She may associate any sort of border control with a ‘strict’ border. Even though this explanation seems plausible, it may be controversial given what Termime uttered at the end of her dialogue:

```python tags=["narrative", "hermeneutics", "sound-closed-or-open-borders-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_12.m4v')  # Replace with the actual file path
```

> ehm<br> if<br> do would you<br> what do you think?<br> You are pro eh borders or <br> like you are for closed borders or open borders<br> controlled borders or not controlled borders


Both interlocutors provide a very brief answer.

```python tags=["narrative", "hermeneutics", "sound-open-borders-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_13.m4v')  # Replace with the actual file path
```

<!-- #region tags=["dialog-open-borders-*"] -->
| Aura | Termime |
| ---- | ---- |
| I think I am for open borders because I'm<br> I feel<br> ehm<br> I feel I am a part of Europe not not only of Austria<br> And I feel<br> that is<br> you know Bratislava is is near to me and<br> and Innsbruck is | &nbsp; |
| &nbsp; | yeah |
| I have nothing to do with people from Tyrol and Vorarlberg<br> and Bratislava Budapest<br> that’s<br> that’s near to me<br> so<br> I am often in Germany<br> in Hamburg and in Amsterdam and<br> So I<br> I think we should open the borders<br> and and<br> I understand why my<br> my nation or the state’s interest say<br> they have to<br> they have to to put borders and aeh<br> I'm<br> I am for<br> | &nbsp; |
| &nbsp; | Open borders |
| Yeah<br> Open borders [laughing] | &nbsp; |
| &nbsp; | Well me too<br> because I can't imagine to have once again closed borders<br> like with Slovenia<br> It's<br> yeah<br> I, I can’t imagine really<br> but I'm<br> eeh<br> I am for<br> like<br> controlled borders<br> like<br> I'm not saying like<br> with like with the army or something like that<br> but like<br> a minimum of control of the border within like<br> police or something like that<br> Because<br> like it it happens that when eh<br> there's no control there is advantage<br> and it gets out of hands | &nbsp; |
<!-- #endregion -->

Termime articulated an understanding of closed borders that contradicted her earlier interpretation. She clearly differentiated here between what she called a ‘closed border’, previously referred to as a ‘strict’ border, and the concept of ‘border controls’. She explained that she would like to live in a place with open borders but with a minimal level of control provided through the ‘police’, since she explained that she was afraid that ‘no control’ would lead to chaos. She did not specify what kind of control she had in mind. It seems reasonable to assume that Termime’s understanding of a strict/closed border in the historical context of the Italian-Slovenian border during communism refers to an impermeable physical barrier that cannot be crossed by ordinary citizens. A border that actually reflected such a definition was the border between the Polish People’s Republic and the Ukrainian Socialist Soviet Republic, which was a ‘hermetically sealed and exceptionally well-guarded frontier, a state which changed little until 1985’ (<cite data-cite="8820477/9Z6R95NZ"></cite>, 246), in contrast with the more open border between Yugoslavia and Italy. This could potentially imply that Termime’s knowledge about the Italian-Slovenian borderland during socialism is flawed. Interestingly, and in contrast to Aura, this fragment also shows that Termime wants to re-establish a minimum level of border control, presumably, as she is an Italian citizen, at the Italian border. At the moment of the conversation, such a border practice had not been exercised at any Italian border since 2007, when Slovenia joined the Schengen Area. It remains unclear if Termime was therefore also considering whether her personal cross-border practices would be affected by such a regulation.


The interpretation of another fragment from the dialogue can help us to determine the reasons for Termime’s desire for control at the border. Before Termime’s plea for ‘police or something like that’, the topic of discussion between the two citizen scientists was the ‘refugee crisis’ and how the Hungarian President Viktor Orban and the Italian Minister of the Interior, Matteo Salvini, advocated for the closure of their respective state borders in 2018:

```python tags=["narrative", "hermeneutics", "sound-controlled-border-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_14.m4v')  # Replace with the actual file path
```

<!-- #region tags=["dialog-controlled-border-*"] -->
| Aura | Termime |
| ---- | ---- |
| I doesn't understand why why<br> why are our government<br> has this few because because<br> the problem with refugees are not only the problem of Italy or Greece<br> It is also<br> part of our problem<br> with Europe we are once [one] and and I don't understand<br> why we make or<br> aehm<br> why we try to make this borders again | &nbsp; |
| &nbsp; | mhm yeah I saw it but you know now that in Italy we have the new government<br> which is like<br> like our vice president of the government Matteo Salvini he is very like against<br> aehm immigrants and so on<br> He he wants to make some changes because<br> now Italy was the first point where all the immigrants stopped<br> and he now wants to stop that<br> And so also Italy is moving I don't know what will happen<br> but also Italy is moving more to the fact that we are going to close borders and it's<br> yeah I really don't know<br> yeah well I get it that they're different from us and<br> but yeah still<br> it's difficult also Hungary<br> it's very strict with borders right |
| yeah | &nbsp; |
<!-- #endregion -->

Since Termime did not specify why she considered border controls to be necessary, we can only presume that the influx of asylum seekers into the European Union, especially Italy and Greece, experienced from 2015 onwards, may have played a role in her reasoning.


The dialogue also included an interaction about the post-communist past. The sequence emerged after Aura had shared his experience of crossing the border from Austria to Hungary as a child with his parents for shopping. To understand what such a cross-border practice looked like, Termime asked Aura if he had crossed a ‘physical border’ with an ‘ID check’:

```python tags=["narrative", "hermeneutics", "sound-post-communist-past-*"]
import IPython.display as ipd
ipd.Audio('media/Audio_Fragments/AT_AUDIOCUT_15.m4v')  # Replace with the actual file path
```

<!-- #region tags=["dialog-post-communist-past-*"] -->
| Termime | Aura |
| ------- | ------- |
| But it was like a<br> it was like a physical border like you have to go there<br> and check<br> like<br> | &nbsp;
| &nbsp; | Yeah |
| give them your ID<br> Okay | &nbsp; |
| &nbsp; | Yeah |
| but you have some limits of times<br> that you<br> | &nbsp; |
| &nbsp; | Yeah genau at the beginning<br> But in the last years it's |
| it's aeh | &nbsp; |
| &nbsp; | but with Orban they want to<br> to have the borders again and |
<!-- #endregion -->

Termime’s question shows a level of detail that might indicate that she has personally seen the ‘physical border’ and experienced border ‘check[s]’. Although Termime wanted to have a conversation about border-crossing experiences to Hungary before the country joined the Schengen Area in 2007, Aura took this moment as an opportunity to draw a comparison with the border regime developed by the government led by Viktor Orban. Following the high influx of refugees in 2015, the Hungarian government initiated several anti-migration procedures to hinder asylum seekers wishing to cross the border. These included a crackdown by border guards on asylum seekers at Hungarian-Serbian border crossings, leading to violent clashes, as well as the installation of barbed-wire fences between Hungary and Serbia (<cite data-cite="8820477/WCUQEWBZ"></cite>, 552). In June 2018, roughly at the same time the Talking Borders experiment took place, the Hungarian government passed a new law that criminalised providing assistance for asylum seekers (<cite data-cite="8820477/FA7AKHR4"></cite>).


This fragment shows how both interlocutors experienced identification checks at the border. It also indicates how they talked about these experiences from different time perspectives. While Termime hinted at Hungary’s post-communist but pre-European Union period, Aura drew a connection to his current reality. Similar entanglements of the past and the present were observed on numerous occasions during the dialogue. In the sequence about xenophobic remarks made by people in Italy and Austria, for example, Termime sought to explain such behaviour in Italy (present) by drawing on past border experiences of her parents as well as subtly hinting at past border conflicts over Trieste and Gorizia (past). In statements made following the discussion around ‘open borders’ or ‘closed borders’, this interwovenness of different time levels encompassed the past, the present and the future. In her answer, Termime first insisted on the need for an ‘open border’ (present) and dismissed the idea of a restoration of the ‘old’ border regime between Slovenia and Italy before EU membership (past). Secondly, she expressed a desire for the border regime to be changed by introducing a minimum level of control at the border (future), since the high influx in asylum seekers crossing to Italy via the Mediterranean Sea led to chaos (past) at the Italian border when no control measurements were in place. In their dialogue, the citizen scientists Termime and Aura made use of the past to attribute meaning to their understanding of the border in the present. While the historical references in Termime’s monologue refer to a distant past (Austro-Hungarian Empire), the historical references uttered during the dialogue represent a more tangible past. Aura and Termime drew on recollections of the communist and post-communist past as experienced by themselves or their relatives in order to make judgements on the border in the present and the future. The value of the dialogue therefore lies in the strategy employed by the two citizen scientists of using questions and answers to identify similarities and differences in their time-layered personal experiences.

<!-- #region tags=["hermeneutics"] -->
## Developing the Digital Café
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
A third genre of the Talking Borders experiment aimed to elicit yet another perspective on the past. After the in-person stage of the experiment, the search for the meaning of borders was lifted out of the dialogical context and placed into a global digital café, with the aim of demonstrating how scientific knowledge on the global meaning(s) of borders could be generated by means of online chat. Initially, the idea was to make use of a Facebook page for this aspect of the Talking Borders project, however this was rejected by the Data Protection Officer at the University of Vienna, as it would require every participant to have or open a Facebook account and would mean that all users would be traceable by their usernames and profiles and that the research data would be owned by Facebook. We needed a non-public discussion space behind a login and we did not want to ask users to register with their email addresses (the archive of the website can be found here [TCS project - Talking Borders](https://zenodo.org/record/8178990)). We decided to use random user names and passwords distributed during the on-site experiment. The citizen scientists were invited to transcribe their three favourite fragments of their conversations and upload the transcriptions to the project website. This was the first step in participants’ interaction with the digital café environment behind the login. The uploads of each participant to the database were checked before the citizen scientists were handed their certificate of participation.

<!-- #endregion -->

```python tags=["figure-upload-transcribed-fragments-*"]
from IPython.display import Image
metadata={
    "jdh": {
        "module": "object",
        "object": {
            "type":"image",
            "source": [
                "Upload area for transcribed interview fragments of the Talking Borders digital café"
            ]
        }
    }
}
display(Image("media/Image_1_page_digital_cafe.png"), metadata=metadata)
```

<!-- #region tags=["hermeneutics"] -->
Citizen scientists uploaded 231 transcribed fragments. A hundred fragments were chosen by the project team to be posted in the digital café from 1 August 2018 to 8 November 2018 ([Digital Café Database](https://github.com/jdh-observer/6ig87tC5GKjQ/blob/main/script/Digital_Cafe_posts_comments.txt)). These fragments are referred to as posts. The project team divided the posts into nine categories (see [this figure](#figure-average-no-comments-per-post-*)): 1: Physical vs mental borders (10); 2: Now vs then (10); 3: Similarity across borders (5); 4: Pro border (11); 5: Against borders (10); 6: Various types of borders / Role of borders in different contexts (14); 7: Influence of borders on personality / personal life (12); 8: Borders in Europe (15); 9: Transgressing borders / Recognising their constructedness (13). Fragments were chosen because they could be easily understood or contained a well-developed argument. If the transcribed quotes lacked words or were marked with signs indicating that the transcribers had not understood something, the quotes were dismissed.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
Posts frequently offered comprehensive descriptions of how contrasting definitions or perspectives on borders shape lives and social communities in one specific country or across countries. Arguments can especially be found in the posts included in the categories ‘Pro border’ and ‘Against borders’, which was a contentious topic and generated a range of comments, from slightly (such as comment 30) to strongly (such as comment 29) in favour of borders, or from slightly (such as comment 42) to strongly (such as comment 43) against borders (see table 2). Whenever posts fitted equally well into two categories (e.g. post 37 would also fit into the category ‘Various types of borders’), the category that had fewer posts was preferred. Participants were given the possibility of engaging in a written online conversation about the content of the posts with other participants over the course of 100 days.
<!-- #endregion -->

```python tags=["figure-dig-cafe-published-posts-*"]
from IPython.display import Image
metadata={
    "jdh": {
        "module": "object",
        "object": {
            "type":"image",
            "source": [
                "Page of the digital café showing published posts"
            ]
        }
    }
}
display(Image("media/Image_2_page_digital_cafe.png"), metadata=metadata)
```

<!-- #region tags=["hermeneutics"] -->
In order to enter a comment, participants had to click the button on the right side of a post. Afterwards, they would see the post as well as its comments, and could add a new comment. When participants entered the system, they did not see how many (if any) new comments had been posted since their last visit; they could only find this out by clicking on every post. This complicated workflow may have contributed to the low average number of comments per post, which stood at 2.23 (see website code [TCS project - Talking Borders](https://zenodo.org/record/8178990)).
<!-- #endregion -->

```python tags=["figure-post-comments-*"]
from IPython.display import Image
metadata={
    "jdh": {
        "module": "object",
        "object": {
            "type":"image",
            "source": [
                "Page of the digital café showing a post and its comments"
            ]
        }
    }
}
display(Image("media/Image_3_page_digital_cafe.png"), metadata=metadata)
```

<!-- #region tags=["hermeneutics"] -->
By 10 November, 226 comments had been posted in the digital café. The number of comments was highest in the first category and then decreased towards the end. Efforts were made to recruit more participants. After five new citizen scientists registered when posts in category six were made available online, the number of comments increased, before decreasing again towards the end of the project. The categories ‘physical vs mental borders’, ‘pro border’ and ‘influence of borders on personality’ triggered most comments. Four participants were especially active during the whole hundred days, one of them being Termime. These participants were awarded a digital recorder as a prize for their commitment.
<!-- #endregion -->

```python tags=["figure-average-no-comments-per-post-*"]
from IPython.display import Image, display

metadata = {
    "jdh": {
        "module": "object",
        "object": {
            "type": "image",
            "source": [
                "Average number of comments per post for each category, number of posts per category in brackets"
            ]
        }
    }
}

display(Image("media/graph_number_of_comments.png", width=1000), metadata=metadata)

```

<!-- #region tags=["narrative"] -->
## Termime in the Digital Café
<!-- #endregion -->

To evaluate the usefulness of the citizen science digital café for historians, this section follows Achim Landwehr’s advice to ‘work historically’ by selecting and researching ‘present references to past times’ (<cite data-cite="8820477/RRDDC742"></cite>, 250). Of the hundred posts in the digital café, six included the word history (post 33, 44, 65, 156, 159, 224). Posts 33 and 159 generated three comments, the other original posts generated two comments. In addition, of the 226 comments, 16 included the word history, two of which were a response to a post mentioning the word history as well (post 224). The second category of posts was called ‘Now vs then’ and included ten original posts. Among the seven posts in this category not mentioning the word history, there were four posts implicitly talking about the past, which we included in the analysis as well (post 36 and 47 about grandparents; post 37 about the Treaty of Schengen and living in the borderlands, and post 40 in which Termime left a comment). We selected 22 posts and their comments for the analysis. This small number shows that when citizen scientists talked about contemporary borders in Europe, they mostly did so without referring to the past.

<!-- #region jdh={"module": "object", "object": {"source": ["table 2: List of all posts and comments from the Digital Caf\u00e9 referenced in this article"]}} tags=["hermeneutics", "narrative", "table-digital-cafe-*"] -->
| PostID | PostText | User who uploaded Post | CommentID | CommentText |User who made Comment | Role |
|-----|-----|-----|-----|-----|-----|-----|
| 21 | When it comes to that genuine human contact and friendship, borders represent nothing, they suddenly become not important at all | Binghost | 30 | When speaking about geopolitical and economical borders this is true, but we need social and cultural limits to understand our own identity. Only when we understand who we really are we will be able to interact with other people | DeadSaint | CS |
| 33 | For me borders mean the place where a country is. That's what separates countries from each other. The history of borders used to work as the place which separated and saved each country's culture and habits from other countries. And it also used to defend places in wars. | Gift | 146 | Therefore, the geopolitical boundary protects the integrity of a state that consists of its territory, language, culture, tradition. The border protects the territory but also the cultural heritage of a state. | Thinkerer | CS |
| 33 | For me borders mean the place where a country is. That's what separates countries from each other. The history of borders used to work as the place which separated and saved each country's culture and habits from other countries. And it also used to defend places in wars. | Gift | 163 | And this is great. However, under no circumstances should we forget about other countries and about keeping alive our relationships with them | DeadSaint | CS |
| 33 | For me borders mean the place where a country is. That's what separates countries from each other. The history of borders used to work as the place which separated and saved each country's culture and habits from other countries. And it also used to defend places in wars. | Gift | 197 | I can relate to this point. The Border is a sign post - hey you are entering a new culture and language zone. I do not see that as bad. It lets people know where they stand, literally and figuratively. But the Border is being used by the far right in a way that denies our celebrating and integrating with different cultures. That makes me sad and angry. It shows how the Border has different roles and values for diff peoples | GamingScorpion | BS |
| 36 | My grandparents are still communists, which is to me very interesting, because, you know, there are all these restrictions, but they grew up that way and that's basically the only thing they knew, they feel like it's what is right, I guess. | Feature | 193 | It is similar with people in my country. The older population describes the period of communism as a period of welfare and carelessness. They also say that when they look from this perspective they see negative side. They see it was not good for everyone, but that they lived well if the rules were respected. | Thinkerer | CS |
| 36 | My grandparents are still communists, which is to me very interesting, because, you know, there are all these restrictions, but they grew up that way and that's basically the only thing they knew, they feel like it's what is right, I guess. | Feature | 203 | It is actually really tough to pass over changes, that is why the elders are so nostalgic; perhaps we will behave the same way in the future. However, since we are now the NEW generation, we are supposed (and we would better to) to manage and adapt to changes | DeadSaint | CS |
| 36 | My grandparents are still communists, which is to me very interesting, because, you know, there are all these restrictions, but they grew up that way and that's basically the only thing they knew, they feel like it's what is right, I guess. | Feature | 213 | For me its fascinating that until recently whole Europe was divided in two. There were practically two Europes: east, communist one and west, capitalist one. | PeskyLlama | CS (only participated in Digital Cafe) |
| 37 | BS: The border as a state border wasn't the topic of my thinking because the first experience, maybe this is connected with the so-called national methodology in Poland, but our studies are more oriented on the borderland question not border question. | Witness | 182 | With the Schengen treaty, living near the border is something really peculiar because it lets you get in touch with other people and traditions weekly or even daily. I feel it is terrific | DeadSaint | CS |
| 37 | BS: The border as a state border wasn't the topic of my thinking because the first experience, maybe this is connected with the so-called national methodology in Poland, but our studies are more oriented on the borderland question not border question. | Witness | 184 | As an active member of a minority that lives on the borderland of my country, I can relate to this comment. Maybe because our two countries are on relatively good terms but for me, it was not really a fact of borders but as Witness had stated, more of the borderland territory, how to improve it or how to embrace it. Usually, the borderland of a country is one of the richest areas of the whole nation, that may be because is the meeting point of different cultures. | Termime | CS |
| 37 | BS: The border as a state border wasn't the topic of my thinking because the first experience, maybe this is connected with the so-called national methodology in Poland, but our studies are more oriented on the borderland question not border question. | Witness | 189 | Since I grow up (I still live) in the border zone (borderland), I have always wondered what the border is. I asked myself how the river could be a border and to whom the river belongs. The term border was untouchable for me. I saw the river, but I did not could understand what that river divided except two coats. Now, I can see that river like natural border between two countries divides language, culture, religion and law. But also, in my town I can see that borderland provides multinational and multicultural environment and that is advantageous. Growing up in a multinational and multicultural environment means that you do not see the strict boundaries between cultures, because they are somehow a compound of all cultures in that area. Over time, people assimilate and the boundaries between people disappeared, first and the foremost by the respecting of each other. | HammerTurkey | CS |
| 40 | Borders have a hard meaning because they were the foundation of building a nation, something that united people. | LittleChampion | 96 | Sometimes geopolitics helps in this: in the last century, Italy did not feel complete without Trieste and Trento and without having the entire control on the Adriatic Sea, which was conceived as an Italian lake. However only with a specific propaganda was this made clear to the public opinion and was it possible to strenghten the idea of Italian nationality | DeadSaint | CS |
| 40 | Borders have a hard meaning because they were the foundation of building a nation, something that united people. | LittleChampion | 105 | During World War I, at the battle of Isonzo river (Soca) Italians were just being defeated at Caporetto (Kobarid) by the Austrian army, who started to push the Italians even further on till the river Piave. And right there the Italian army had the strength to fight back at the Austrians because they were protecting their homeland, their borders. They understood that if they let the Austrians push any forward than that the enemy will take their home. The border united them. | Termime | CS |
| 40 | Borders have a hard meaning because they were the foundation of building a nation, something that united people. | LittleChampion | 150 | The good side about national borders is that nowadays we have a multiple cultures in the world. Also, that is a way for people to know the history of their nation and to know their roots. | HammerTurkey | CS |
| 44 | When I think about borders, I think very much about the Berlin Wall. And I've been to Berlin once, and I was very fortunate to see the wall, I found it a very moving experience, because I have always had a great love of history. | Gift | 196 | The Wall is an excellent example of a place divided. There are still Walls that divide - see the Middle East. They remind us that division is a permanent aspect of a Border. I am not condoning that, but it is something we must deal with. People who say they do not recognise Borders, I say look at these examples. Borders are reality. | GamingScorpion | BS |
| 44 | When I think about borders, I think very much about the Berlin Wall. And I've been to Berlin once, and I was very fortunate to see the wall, I found it a very moving experience, because I have always had a great love of history. | Gift | 205 | This summer I attended an exhibition on borders where there were many pictures collected by ANSA . These show boundaries all over the world which are extremely similar to the Berlin Wall. I highly recommend it, try to look up the internet for it | DeadSaint | CS |
| 47 | CS: Nowadays we perceive borders differently from how our parents and grandparents did, because my grandparents and parents grew up under communism and they could not travel like we can now, they had some limitations and they could only travel to some countries, they had to wait until their application to travel was approved and there were thorough border controls to prevent smuggling. | ArchTauren | 52 | Travelling freely is one of society best conquests: this really helps us to see different environments from ours and to try new experiences. It is a new way that let young people grow differently from their parents, creating the basis for a potential multicultural society | DeadSaint | CS |
| 65 | As a history student I'm more than interested in the phenomenon of borders, not only from the political aspect but from the cultural as well. Taking into consideration that I'm originally from Bosnia, that I was born in Croatia, but raised and educated in Serbia. When someone mention borders, firstly, I think about geopolitical lines that separate different countries. | Creator2 | 148 | I completely concord with this sentiment. I too feel that Borders ARE geopolitical constructs used to distinguish between separate lands. I suspect many other people hold a similar view; for example, the media and politicians. But whereas they see the Border as a gatepost for exclusion, which privileges some or others, I prefer the Border to be a signpost for a different land and culture. Something that can be celebrated for signifying difference in terrain, language, food, and culture. By embracing the different, we find out how much we have in common. | GamingScorpion | BS |
| 65 | As a history student I'm more than interested in the phenomenon of borders, not only from the political aspect but from the cultural as well. Taking into consideration that I'm originally from Bosnia, that I was born in Croatia, but raised and educated in Serbia. When someone mention borders, firstly, I think about geopolitical lines that separate different countries. | Creator2 | 161 | I do believe that boundaries are born with geopolitical aims, but, strange as it may seems, they also play a fundamental role for social integrity. Anyway, you should be an extremely interesting person to know; I wish we had met in Vienna | DeadSaint | CS |
| 66 | CS: I would like to summarize those things that affect someone's perception of borders as context, because, if we want to understand why someone thinks something or in some way about borders, we need to understand where he comes from, what time we are talking about. | LostFairy | 43 | As the author Neblett said "We are the sum total of our experiences. Those experiences â€“ be they positive or negative â€“ make us the person we are, at any given point in our lives. To understand someone's position regardless borders we have to understand where the person comes from to be able to find the best compromise, solution. | Termime | CS |
| 68 | CS: There are several types of borders. If we start with the political ones, the first that defined them were the Mesopotamians and the Egyptians that had wars over these territories. Then, with time passing, there intervened other borders, let's call them interracial borders, language borders, and geographical and cultural borders. | SneakyWarthog | 66 | Political borders the way we think of it nowadays are deeply linked with the invention of nation states. The Treaty of Westphalia defined in 1648 sovereignty, that is the relationship between a power, a population and a territory. From that moment and with the help of progress in cartography, rulers were able to precisely define borders. Population census and identity card came later as new technology for controlling flows. We know examples of people on the Franco-Belgian border in the 19th century who took advantage of the imprecision of the border line for registering on the side which was the best for their personal or professional interest. I would argue that borders have hardly been more closed than in the modern society. | GrassPixie | BS |
| 73 | CS: Borders play a very important role in defining the identity of individual or ethnic groups. The drawing of new borders which strictly limit the space of a nation of another nation. The ideal nation-state emerges from an organic structure that is meant to bring together all citizens of an ethnicity. | Spillager | 92 | I think this is very well said. And I think that this is the essence of states and borders in the geopolitical sense, to bring together all citizens of an ethnicity. | Thinkerer | CS |
| 73 | CS: Borders play a very important role in defining the identity of individual or ethnic groups. The drawing of new borders which strictly limit the space of a nation of another nation. The ideal nation-state emerges from an organic structure that is meant to bring together all citizens of an ethnicity. | Spillager | 103 | Usually things like borders, national identity, national culture, and language or even rooting for their national soccer team awaken some kind of patriotism in the hearts of every citizen of each country. Having something that you care for that is just yours as in your Country makes you want to not give up and you feel close as ever to your fellow citizens. In history, we have many examples where politics used the idea of defending borders and fight for your country to mobilize entire nations. | Termime | CS |
| 73 | CS: Borders play a very important role in defining the identity of individual or ethnic groups. The drawing of new borders which strictly limit the space of a nation of another nation. The ideal nation-state emerges from an organic structure that is meant to bring together all citizens of an ethnicity. | Spillager | 114 | This is the essence of nation-states from the modern era. However at that time, and sometimes still nowadays, also economical and political elite and their potential advantages from geopolitics influenced the defining of a national identity | DeadSaint | CS |
| 92 | So I can say that political and culture borders are not the same thing because we have an example, not all people in Croatia are Croatians, not all people in Germany are Germans, of course. So we have many cultures in a land-national minority. | DreamBlackberry | 79 | I assume DreamBlackberry got the point. If I consider the border region where I am born and where I live, I notice that almost four different ethnies spread on both sides of the border which have been living together with no wall separating them. Moreover, I conceive this as a factor which enrich the cultural experience of a territory. | DeadSaint | CS |
| 92 | So I can say that political and culture borders are not the same thing because we have an example, not all people in Croatia are Croatians, not all people in Germany are Germans, of course. So we have many cultures in a land-national minority. | DreamBlackberry | 87 | Totally agree with both DreamBlackberry and Deadsaint. Having many nationalities within one territory it s a very unique experience, it has its good sides and its more complicated one. The minority from my country, basically goes back from the Austro Hungarian empire, one of the most famous multicultural nations in history. | Termime | CS |
| 94 | CS: I do not know a lot about borders. I study anthropology and we had fieldwork in Prekmurje in Slovenia and we talked with people that live there close to the Hungarian border and we asked them how the border influenced them, the difference between the past and now, what changes borders brought. They said that borders influenced the past much more than now. | MoneyMobster | 65 | There are definitely strong debordering processes in the world, but we can also observe countermovement of rebordering processes. For example, the total length of borders in the world is increasing and some borders are building up fences. Look at the contradiction of crossing borders in a globalized world: a dead cow will easily cross every border as a steak for sell; but a human being with the wrong passport would not be allowed to travel. This applies even in the European Union with dramatic consequences. Roma people with Romanian and Bulgarian nationality are being deported from France, while Syrian and Ethiopian refugees stay in slum camps before passing the Channel Strait to the United Kingdom. | GrassPixie | BS |
| 104 | If we did not have any borders, we would need to have one government or no government. So people would be fighting over land all the time. So, we all have borders. If you live in an apartment you have a border between your apartment and the next apartment. | Enchantra | 110 | Boundaries are necessary to improve a country administration. To be more specific, they are also extremely useful in avoiding that two countries get into a conflict for this kind of issues | DeadSaint | CS |
| 104 | If we did not have any borders, we would need to have one government or no government. So people would be fighting over land all the time. So, we all have borders. If you live in an apartment you have a border between your apartment and the next apartment. | Enchantra | 124 | It is proven by history that borders and boundaries are necessary or at least the make interactions and relationships between countries easier. But I think, and I saw this kind of comments, that oversimplifying and applying different examples to such a complex topic, like borders it s not the best. I think when we do that we kind of lose the meaning of the topic itself. | Termime | CS |
| 116 | CS: Borders can be constructed, as in the case of nations - a lot of the time those borders are meeting landmarks. But most of the time I think they're constructed. There are borders not only related to countries but also personal borders or psychological borders. | HollowDrummer | 34 | Borders could be meeting points from which the divided populations can exchange their culture and their identity. They are born as division, but we can use them as crossroads as well | DeadSaint | CS |
| 117 | For example, it's my first time in Vienna. And we are living in a dormitory. Yesterday we wanted to eat something especially from Vienna. But, we couldn't find anything but Turkish, Turkish, Turkish, Turkish. So I think that now Europe has mixed with Arabs. I think we should use the ideas of walls. Maybe not build them, but use the idea. | CarefulKraken | 91 | I can agree with my colleague, we all noticed that Vienna is a multinational and multicultural city. Using walls as an idea, this is a very unusual and good thought. But I think its much easier to use before the damage,conditionally stated, is made. Imagine, for example, if we would implement that strategy in Vienna, would we have more damage or benefit from it? | Thinkerer | CS |
| 117 | For example, it's my first time in Vienna. And we are living in a dormitory. Yesterday we wanted to eat something especially from Vienna. But, we couldn't find anything but Turkish, Turkish, Turkish, Turkish. So I think that now Europe has mixed with Arabs. I think we should use the ideas of walls. Maybe not build them, but use the idea. | CarefulKraken | 97 | I believe Vienna is one of the most evident examples of multiculturality, as the historical capital city of such vaste empire. Maybe looking at its history we can learn something useful about managing ethnical minorities. Speaking about Arabs, researches show that they are little minorities, even if sometimes economically competitive | DeadSaint | CS |
| 117 | For example, it's my first time in Vienna. And we are living in a dormitory. Yesterday we wanted to eat something especially from Vienna. But, we couldn't find anything but Turkish, Turkish, Turkish, Turkish. So I think that now Europe has mixed with Arabs. I think we should use the ideas of walls. Maybe not build them, but use the idea. | CarefulKraken | 100 | History has proven that when different people come together in a meeting point, two things can happen: a conflict or new and different ways to enrich the culture and the ways of living. When we were in Vienna I also saw that in the area where we were staying there were a lot of Turkish places, but also many Italian restaurants and I even saw some English pubs. This is the consequence of centuries of migrations and a very present globalization. | Termime | CS |
| 137 | BS: I think I have a lot of experience just as a person in this world or as a professional. I also pick up on a kind of paradox that borders divide and unite. So on the one hand, there are different countries with their own laws and culture. For example, the differences between USA and Mexico, not so economically developed in the case of Mexico, but powerful and wealthy in the case of the USA. On the other hand, a border is an INVITATION to cross, it is a barrier. You have to deal with different customs. | Form | 42 | That is a very interesting point. Every country has different customs and if you visit a specific country you have to respect it's customs and adapt. | ArchTauren | CS |
| 156 | I think the borders are something that is all the time changing. It is nothing constant. The shape and the configurations of borders are changing all the time. There are many examples in history that the big empires have fallen. And sometimes nothing is left after them. | Reply | 236 | Many experts suggest that borders will change for sure. We just ought to be prepared for it | DeadSaint | CS |
| 156 | I think the borders are something that is all the time changing. It is nothing constant. The shape and the configurations of borders are changing all the time. There are many examples in history that the big empires have fallen. And sometimes nothing is left after them. | Reply | 249 | François de La Rochefoucauld said that the only thing constant in life is change. | Termime | CS |
| 159 | If we want to understand why someone thinks something or in some way about borders, we need to understand where he comes from, what is the town we are talking about, what is the history and background of the region he comes from. | Response | 154 | This is true, we have to consider that vision and thinking about the borders in some way depends on the environment in which we are. This is a very nice comment, stimulated me to think. | Thinkerer | CS |
| 159 | If we want to understand why someone thinks something or in some way about borders, we need to understand where he comes from, what is the town we are talking about, what is the history and background of the region he comes from. | Response | 158 | Surely this should be the main principle of international relations and of diplomacy. A simple but not easy way to understand somenone could be learning his language | DeadSaint | CS |
| 159 | If we want to understand why someone thinks something or in some way about borders, we need to understand where he comes from, what is the town we are talking about, what is the history and background of the region he comes from. | Response | 188 | Exactly, knowledge is power. Understanding the other facilitate communication between two parts. | Termime | CS |
| 171 | When I think about borders in some different and deeper way, a more cultural way, I see them as much more complex things that sometimes can bond us but sometimes can disconnect us. Some borders and some changing borders have big consequences for someone, while for others, they don't feel it at all, you know, it really doesn't affect them. | Thinkerer | 177 | Well usually people who live near the frontier feel the change. I am now thinking about all of those German people at the east border who after WW1 had to change life after they were included in new countries | DeadSaint | CS |
| 171 | When I think about borders in some different and deeper way, a more cultural way, I see them as much more complex things that sometimes can bond us but sometimes can disconnect us. Some borders and some changing borders have big consequences for someone, while for others, they don't feel it at all, you know, it really doesn't affect them. | Thinkerer | 185 | Deadsaint, with his/her comment, pointed out that the question of the border often has to be reconnected to history. History always can explain to us why relationships between state are as they are, and why people feel like that towards borders. For that matter engagements like this one are extremely important. | Termime | CS |
| 177 | CS: As for me, a border isn't just a line on a map. It is a complicated question, because a border is also mental, religious, in the economy, for example. As for me, I think borders are very important, because it is the area where one person and another can meet. | Aspect | 29 | Borders delimit the area where we can move freely without damaging the other. Moreover, this freedom helps the development of our own identity; within these limits we can understand what we really are and what we really want | DeadSaint | CS |
| 177 | CS: As for me, a border isn't just a line on a map. It is a complicated question, because a border is also mental, religious, in the economy, for example. As for me, I think borders are very important, because it is the area where one person and another can meet. | Aspect | 32 | I think it is less the place where two people can meet but where they face difficulties trying to meet. A border implies a difference (geographic borders for example a difference in location, a mental border shows a difference in perception...) | Witness | CS |
| 177 | CS: As for me, a border isn't just a line on a map. It is a complicated question, because a border is also mental, religious, in the economy, for example. As for me, I think borders are very important, because it is the area where one person and another can meet. | Aspect | 47 | Borders are meeting point. Where we get the chance to meet the other, someone that is different from us and I mean different by language, culture etc. So when we face the "other" can better understand who we really are. Living on a border gives you an exceptional opportunity not only to get to know who is different from you and see a reality that is not ours but also put in a way our lives in perspective. | Termime | CS |
| 177 | CS: As for me, a border isn't just a line on a map. It is a complicated question, because a border is also mental, religious, in the economy, for example. As for me, I think borders are very important, because it is the area where one person and another can meet. | Aspect | 63 | Beside meeting point, borders also enrich relations between people in general as well as the people living near the border because history is a great proof that the borders are not just lines on a map. Every border has its own and unique history of events that defined it as we know it today and I believe that besides people can use it to meet each other that they all understand why that border is there and how did it affect two sides that the border separates. Using that knowledge, people can understand why someone sees or thinks of a border in some way instead of judging the other side for its opinion on borders | LostFairy | CS |
| 178 | BS: Have the borders stopped you from doing something that you like? CS: Mm, not really, no. BS: No? CS: But I live in Vienna. I mean, if I go to other countries, I don't need documents or change the money or take a visa. But if I came from another country, then of course that would be a problem. | Tec | 201 | Since many times here we have discussed the Schengen model, I now believe that this is effective only when it involves few countries, so it could not become a universal idea. What do you all think? | DeadSaint | CS |
| 178 | BS: Have the borders stopped you from doing something that you like? CS: Mm, not really, no. BS: No? CS: But I live in Vienna. I mean, if I go to other countries, I don't need documents or change the money or take a visa. But if I came from another country, then of course that would be a problem. | Tec | 220 | If we think about it in a realistic way I do not think It will be possible to have Schengen as a universal idea. Not only because of the history between different countries but also because of the economic, politic and strategic interests that characterize modern countries. | Termime | CS |
| 178 | BS: Have the borders stopped you from doing something that you like? CS: Mm, not really, no. BS: No? CS: But I live in Vienna. I mean, if I go to other countries, I don't need documents or change the money or take a visa. But if I came from another country, then of course that would be a problem. | Tec | 231 | On the first comment, suppose that is true like you said if you are from a EU country, but if you are for example from Serbia, you need visa, passport, waiting | AuthorityWizard | CS (only participated in Digital Cafe) |
| 178 | BS: Have the borders stopped you from doing something that you like? CS: Mm, not really, no. BS: No? CS: But I live in Vienna. I mean, if I go to other countries, I don't need documents or change the money or take a visa. But if I came from another country, then of course that would be a problem. | Tec | 242 | AuthorityWizard you are right: I am from an EU country, but I thought an universal spread of Schengen, like Termime affirmed. Personally I hope Serbia and other European countries will be included in this area | DeadSaint | CS |
| 182 | CS1: Do we need borders? CS2: I think yes, without borders I think there would be chaos, because there are too many different people, I think, who can't live with each other, like with religions, because they are too different. I think we need borders for the same ethnic people who can stay in only one place not spread all around the word. | Aspect | 81 | I think that without a border, the society would start the paths of anarchy. Sometimes there are boundaries to tell us what we can and what we can not do. For example, the boundaries in good behaviour. When we violate the rule, it is followed by a sanction. | Thinkerer | CS |
| 182 | CS1: Do we need borders? CS2: I think yes, without borders I think there would be chaos, because there are too many different people, I think, who can't live with each other, like with religions, because they are too different. I think we need borders for the same ethnic people who can stay in only one place not spread all around the word. | Aspect | 86 | Today I happened to be searching for some information about the North Korea for an upcoming history exam that I have to take at my University. And it popped up on my screen a photo taken on the border between North and South Korea, which portrait to mans holding hands through a window of a bus. One man was on the bus ready to leave and the other was standing outside. The image captured perfectly the feeling across their faces. It was pain, both of them were crying. This particular photo stuck with me for the rest of the day. In this days the two countries emanated a special pass to nearly 400 families that were divided at the time of the Korean war that took place in the fifties so that the separated families could have a chance to see again the relatives that couldn't see each other for more than six decades. Do we need borders? I think that when we talk about different countries, cultures, religions borders are a good thing, because, within them, we as a country are able to be ourselves and just with the acceptance of the fact that we are different, we are truly able to comprehend the others and fully accept and embrace the difference between nations. And I also think that boundaries are a good thing, obviously to some extent. But then I came across at photos of divided families from North and South Jorea or America and Mexico etc. and I ask myself what kind of borders do we really need? | Termime | CS |
| 182 | CS1: Do we need borders? CS2: I think yes, without borders I think there would be chaos, because there are too many different people, I think, who can't live with each other, like with religions, because they are too different. I think we need borders for the same ethnic people who can stay in only one place not spread all around the word. | Aspect | 116 | However, if we think about the Berlin Wall or Middle East borders, we would notice that actually chaos ruled and rules over there | DeadSaint | CS |
| 212 | BS: One small river between Poland and Silesia (Bystrica) was a border. In the 20th century it wasn't there anymore but nevertheless people felt divided. Polish people say: My daughter will never marry somebody from the other side. | CrashGoblin | 33 | This is a clear example of how much the territory where a community lives can affect the community itself. If there is a historical division between different populations which does not exist anymore, they should discuss about it | DeadSaint | CS |
| 212 | BS: One small river between Poland and Silesia (Bystrica) was a border. In the 20th century it wasn't there anymore but nevertheless people felt divided. Polish people say: My daughter will never marry somebody from the other side. | CrashGoblin | 41 | I am not really sure, that a discussion would help to solve this problem. People there were told, since they were kids, that people from the other side are bad. To solve this problem, it would be necessary to change the way of thinking of the people. | ArchTauren | CS |
| 224 | CS: Maybe you have an idea how to destroy mental borders between people? BS: I think one way to really help people to lower the border is to understand history BS: History is a really powerful way to eliminate or minimize such borders. | ShortSprite | 234 | Mmm actually I do not agree with you, because history can show the reason whay different start fighting. For example, in the area where I live there are two different ethnics living together whose relationships are improving with the passing of time, but if you studied history, you would see harsh fights which would remember to these people the reasons why they started hating each other. Concluding, I believe we should learn how to dialogue to minimise border between people | DeadSaint | CS |
| 224 | CS: Maybe you have an idea how to destroy mental borders between people? BS: I think one way to really help people to lower the border is to understand history BS: History is a really powerful way to eliminate or minimize such borders. | ShortSprite | 248 | I find myself torn on this topic. But I agree with both of you. I do not think that it is better to not consider history, regardless of how complicated and difficult it may be, because I believe that being aware of the past helps us shape the future. But then I understand DeadsSaints s point because It is not productive to be stuck in the past. In the end, dialogue and an open perspective are key. | Termime | CS |
<!-- #endregion -->

Termime was the second most active participant in the digital café, leaving 44 comments, ten of which included the word history, with one further comment about the past (Termime referred to the past in a comment to the original posts 40, 73, 92, 104, 117 and 156, after a comment by Deadsaint, 159, after a comment by Thinkerer and Deadsaint, and 171, 178, 182 and 224, after a comment by Deadsaint). The most active citizen scientist in the digital café was Deadsaint, who left 91 comments. Termime also exchanged quite frequently with Thinkerer, who left 27 comments. Termime’s references to the past evolved in four stages throughout the digital café. She started with an appreciative comment on how she considered national borders and Italian nationalism to be intertwined. History was discussed in posts and comments before Termime decided to start to talk about history (see comment 33; defence - wars - 34; borders between historical periods as imaginary - 41; division / Berlin Wall - 65 geopolitical constructions - ‘as a history student I know this’ - 66; history affects perception on borders). Termime was prompted to refer to the past in a comment on post 40, which was a response to a post and an earlier comment submitted by Deadsaint:  


**Post 40**

*Borders have a hard meaning because they were the foundation of building a nation, something that united people.*



>**Deadsaint’s comment**: *Sometimes geopolitics helps in this: in the last century, Italy did not feel complete without Trieste and Trento and without having the entire control on the Adriatic Sea, which was conceived as an Italian lake. However only with a specific propaganda was this made clear to the public opinion and was it possible to strengthen the idea of Italian nationality.*


>**Termime’s comment**: *During World War I, at the battle of Isonzo river (Soca), Italians were just being defeated at Caporetto (Kobarid) by the Austrian army, who started to push the Italians even further on till the river Piave. And right there, the Italian army had the strength to fight back at the Austrians because they were protecting their homeland, their borders. They understood that if they let the Austrians push any forward then that the enemy will take their home. The border united them.*


Termime often followed up on comments Deadsaint wrote. He was the only participant from Sarajevo, a Bachelor student in history whose comment described how Italian nationalists used propaganda to strengthen the feeling that the regions of Trieste and South Tyrol belonged to and should be included within the state borders of Italy (see also <cite data-cite="8918850/4A3EZD7C"></cite> and <cite data-cite="8918850/PXQ5C8ZA"></cite>, 30–49. Termime answered incorrectly that Italian soldiers fought against ‘the Austrians’ ⁅there was no Austria, but an Austro-Hungarian Empire – MV and JJ⁆ to protect their home. Borders united Italian soldiers; borders were the ‘foundation of building’ the Italian nation (Post 40; see also <cite data-cite="8820477/G9Y5Z6B7"></cite>).


By the moment Termime reached day 73, she had changed her mind. In a comment, she used the word ‘history’ as a rhetorical tool to bring critical distance to the discussion, but without having to provide an insight into her own opinion or life experiences. It is not clear from the comment what she thought or to what extent she thought the phenomenon she described was relevant to her.  


**Post 73**

*Borders play a very important role in defining the identity of individual or ethnic groups. The drawing of new borders which strictly limit the space of a nation of another nation. The ideal nation-state emerges from an organic structure that is meant to bring together all citizens of an ethnicity.*


>**Termime’s comment**: *Usually things like borders, national identity, national culture, and language or even rooting for their national soccer team awaken some kind of patriotism in the hearts of every citizen of each country. Having something that you care for that is just yours as in your country makes you want to not give up and you feel close as ever to your fellow citizens. In history, we have many examples where politics used the idea of defending borders and fight for your country to mobilize entire nations.*


Later, however, she openly wrote about her own life experiences and connected these to the contemporary past of the Italian-Slovenian borderland. A comment she left beneath post 92, for example, reads:   


**Post 92**

*So I can say that political and culture borders are not the same thing because we have an example, not all people in Croatia are Croatians, not all people in Germany are Germans, of course. So we have many cultures in a land-national minority (DreamBlackberry).*



>**Deadsaint’s comment**: *I assume DreamBlackberry got the point. If I consider the border region where I am born and where I live, I notice that almost four different ethnies spread on both sides of the border which have been living together with no wall separating them. Moreover, I conceive this as a factor which enrich the cultural experience of a territory.*


>**Termime’s comment**: *Totally agree with both DreamBlackberry and Deadsaint. Having many nationalities within one territory it’s a very unique experience, it has its good sides and its more complicated one. The minority from my country, basically goes back from the Austro-Hungarian empire, one of the most famous multicultural nations in history.*


Using the myth of positive Habsburg multiculturalism (<cite data-cite="8820477/ZZHXIVV8"></cite>), Termime presented her lived experiences in the Italian-Slovenian borderland as naturally evolving from the past, thereby keeping silent about what happened in the hundred years in between. She described enjoying her life in the borderland and was happy to sympathise with two other citizen scientists on multiculturalism within countries (DreamBlackberry) or border regions (Deadsaint) (see also her comment 124 on post 104).


In a last phase, Termime expressed how she was learning from reading the comments of other participants in the digital café and how that caused her to apply a more nuanced understanding of past bordering practices to her own worldview. Termime applied this perspective either alone (comments 249, 188, 185, 220, 86) or in response to Deadsaint (comments 47, 248) and also produced shorter interventions. In one comment, she testified in writing, for example, how studying the history of North Korea for a class at university made her think: ‘What kind of borders do we really need?’ (comment 182). At the end of the digital café, moreover, she concluded that history cannot teach you anything unless you have ‘an open perspective’ and are willing to ‘dialogue’ with others.


**Post 224**

Citizen Scientist: *Maybe you have an idea how to destroy mental borders between people?*


>**Border Scholar**: *I think one way to really help people to lower the border is to understand history. History is a really powerful way to eliminate or minimize such borders.*


>**Deadsaint’s comment**: *Mmm actually I do not agree with you, because history can show the reason why different start fighting. For example, in the area where I live there are two different ethnies living together whose relationships are improving with the passing of time, but if you studied history, you would see harsh fights which would remember to these people the reasons why they started hating each other. Concluding, I believe we should learn how to dialogue to minimise border between people.*


>**Termime’s comment**: *I find myself torn on this topic. But I agree with both of you. I do not think that it is better to not consider history, regardless of how complicated and difficult it may be, because I believe that being aware of the past helps us shape the future. But then I understand DeadsSaints’ point because it is not productive to be stuck in the past. In the end, dialogue and an open perspective are key.*


Additionally, the learning effect observed in Termime's comments in the digital café resembles similar findings found in a study on the use of online forums in the citizen science platform Zooniverse, in which a learning effect amongst forum users was observed by analysing the shift in the users' terminology. The study identified two groups of forum users, one group that already indicated a highly topic-specified vocabulary with no change over the course of their activity in the online forums, and a second group that acquired new terminology over time (<cite data-cite="8918850/VDUU7TTQ"></cite>, 321–322). While the study focused on the users' development of topic-specific vocabulary, the learning effects in Termine's activities in the digital café becomes evident in her strategy to reference terminology used by others in her responses. Termime used the same or similar terminology from the posts and expanded the idea conveyed in the post through additional information to indicate agreement, increase credibility of the post and to formulate her own opinion (e.g. 'Exactly, knowledge is power', comment 188),'François de La Rochefoucauld said that the only thing constant in life is change.', comment 188). In the digital café, due to its limited time-span, we cannot observe if the posts and comments articulated by other users has determined Termime's use of terminology permanently. We can, however, identify that the terminology used by others navigated her participation in the digital café, and thus would allocate her into the second group of online forum users as identified by Luczak et al.


By the moment Termime reached the end of the digital café, she had developed a respectful relationship with Deadsaint, sometimes agreeing (comment 87), sometimes nuancing (comment 248) and sometimes rejecting (comment 105) his point of view. The digital café functioned as a learning environment for Termime, where she changed her references to the past as a result of interactions with other citizen scientists. Termime’s experience was rare – only three citizen scientists left enough comments to observe a change in attitude. We therefore conclude that the digital café had the potential to function as an innovative learning format to encourage reflection on the use of the past for meaning-making in the present.

<!-- #region tags=["hermeneutics", "narrative"] -->
## Conclusion: Towards Output Criticism
<!-- #endregion -->

<!-- #region tags=["hermeneutics", "narrative"] -->
We conclude with a reflection on the data, narrative and hermeneutic layer of our article, as well as on the intertwined presentation of these layers within the Journal of Digital History. We propose to upgrade the data layer of the journal to a third layer in its own right, equal to the narrative and hermeneutic layer. We suggest extending the possibilities to store data, for example by means of a data protocol and storage possibilities for data that cannot be made available in open access because of the GDPR. Here follows a short description of why and how our data were stored in open access. We differentiated between GitHub, where we published the figures, tables, Excel tables, audio fragments and transcriptions analysed in the article. On Zenodo we stored all conversations and the archived project website including the digital café in its entirety. For a born-digital collection like ours, with a Creative Commons license, we found it regrettable that scans of the original Informed Consent Forms with the signatures of all citizen scientists, as well as a list linking the names of the citizen scientists to their pseudonyms, could not be stored with the other data behind a password.
<!-- #endregion -->

<!-- #region tags=["hermeneutics", "narrative"] -->
The narrative layer discussed how talking about borders within the three genres of storytelling of the Talking Borders experiment – the monologue, the dialogue and the digital café – led to contributions that revealed entangled perspectives on time. The citizen scientists made use of past, present and future understandings and experiences of borders to express the meaning they attach to borders today. Termime, for example, juxtaposed her childhood memory of an Italian-Yugoslavian border that was difficult to cross with her understanding of the Italian-Slovenian ‘open’ border functioning as ‘a bridge’ today. Like the other citizen scientists living in borderlands and participating in the experiment, Termime explained how personal and family memories of the border impacted her understanding and opinions of contemporary border realities and future border regulations, indicating that the past, present and future are intertwined concepts of time that cannot only be imagined but also materialise in the present (<cite data-cite="8820477/RRDDC742"></cite>, 240). Interestingly, Termime’s and Aura’s memories of the past that they used to attribute meaning to contemporary borders during the unprepared dialogue did not reach beyond two past generations, even though referring to the Austro-Hungarian Empire would have reflected the theme of the conference they attended, organised to mark the hundredth anniversary of the dissolution of the Austro-Hungarian Empire, and Termime referred to the Austro-Hungarian Empire in the monologue she had prepared in writing before attending the conference. The citizen science dialogue revealed an overlap in border experiences and practices of interlocutors from different European borderlands. This leads us to the conclusion that the border memories ingrained in the citizen scientists had a temporal limit, which may very well become less important for future generations, eventually vanish and be replaced by new memories. The analysis of how Termime referred to the past in the digital café, in turn, shows that the digital environment can support a learning process leading to a more historically contextualised understanding of border regimes, as long as citizen scientists are more actively encouraged to seriously engage with it for its entire duration.
<!-- #endregion -->

We aimed to keep the relative weight of the narrative and hermeneutic layer of this article in balance, offering frequent switches between the two layers. The hermeneutic layer followed an adapted version of the digital research process presented by Fickers and others, and offered a careful reflection on the opportunities and constraints of the various existing digital tools used during the recording, transcription and analysis as well as the digital environment (the digital café) developed for the project.

<!-- #region tags=["hermeneutics", "narrative"] -->
After writing the article in the format of the Journal of Digital History, we conclude that multimodal digital storytelling requires an additional step of reflective criticism, which we call output criticism. Output criticism differs from visualisation criticism; the latter proposes, for example, reflecting upon the quality of a geographic visualisation created based on data inserted in a database. Output criticism, by contrast, refers to scholarly reflection on a multimodal digital storytelling format in which, for example, such a self-created geographic visualisation is included. We opted for the concept of ‘output criticism’ instead of publication criticism, because we see potential in its usefulness for other output formats, such as digital exhibitions, IWalks or innovative forms of transmedia storytelling.
<!-- #endregion -->

<!-- #region tags=["hermeneutics", "narrative"] -->
Our output criticism mainly focuses on the display opportunities and constraints of intertwining the hermeneutic and narrative layers. By opting to add the step of output criticism, we were able to show more clearly how our methods and tools influenced our narration. The video showing how the analytical parameters were set in Clarin Elan for the analysis of one fragment of Termime’s monologue serves here as an example. A detailed manual ethno-poetical transcription of fragments that went beyond the limitations of machine-generated transcriptions also revealed certain nuances in the analysis of Termime’s conversation that would otherwise have remained undiscovered. However, we noted that the technical restrictions inherent in the way the digital café was developed, which made it impossible for citizen scientists to receive an overview of the latest comments on one screen, probably meant that it was too much of an effort for many citizen scientists to engage frequently.
<!-- #endregion -->

<!-- #region tags=["hermeneutics", "narrative"] -->
The analysis presented in the narrative layer resulted in a suggestion of future choices regarding research design, methods and tools. Most importantly, the analysis of Termime’s dialogue with citizen scientist Aura showed how useful it can be to plan such interactions in future experiments instead of leaving them to serendipity. The analysis of how Termime’s understanding of borders evolved during the digital café demonstrated how the possibility of following entire chat conversations and keeping an overview of postings supported her learning process. The challenge for the future is to turn the digital café from a learning environment for highly motivated citizen scientists to one inclusive learning environment reaching out to more participants.
<!-- #endregion -->

<!-- #region tags=["hermeneutics", "narrative"] -->
We are of the opinion that the intertwining nature of the narrative and hermeneutic layer could be developed further. The presentation model of the journal, which prescribes using black for the text included in the narrative layer and green for the hermeneutic text sections, creates a binary segregation that does not entirely correspond to the way in which the methods and tools we used influenced our interpretation and findings. We propose opening up the Journal of Digital History for non-binary presentations of findings. We found it especially challenging to have to choose one of the two colours for the introduction and the conclusion. We would also have liked to be able to merge the hermeneutic section ‘A Digital Analysis of Termime’s Oral Articulations’ with the narrative counterparts ‘Narrating Termime’s Monologue’ and ‘Narrating Termime’s Dialogue’.  
<!-- #endregion -->

## Acknowledgements




<!-- #region tags=["hidden"] -->
## Bibliography
<!-- #endregion -->

<!-- #region tags=["hidden"] -->
<div class="cite2c-biblio"></div>
<!-- #endregion -->
