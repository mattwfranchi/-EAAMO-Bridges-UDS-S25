# EAAMO-Bridges-UDS-S25
This is the repository for the Urban Data Science & Equitable Cities Working Group (Spring 2025), an [EEAMO Bridges](https://bridges.eaamo.org/) working group. 

By 2050, the UN projects that 68% of the population will live in a city. Cities are an increasingly important aspect of daily life, affecting long-term health and access to job opportunities. The use of data to guide decision-making, improve the responsiveness of local government, and reduce inequality has become critical. With the advent of the open data movement for cities, the volume of urban data has exploded. In addition to officially-published open datasets, unique sources of unstructured data, including text and images, are becoming more abundant, providing new opportunities for analyzing urban environments and their occupants. In this EEAMO Bridges working group on urban data science & equity, we host speakers, study papers, and workshop late-stage work relating to the sophisticated computational analysis of urban data, emphasizing topics that both explore and address inequities in urban life. This group began meeting in Summer 2024 as a Cornell reading group on urban data science, incorporating members from information science, computer science, urban planning, sociology, and public policy. 

We meet every other week for a presentation from an invited speaker or group member, followed by sustained discussion.

Our current meeting time is **Monday, 12-1pm EST**. Send us a message to be included in regular communications and get the Zoom link.

<form action="https://www.list.cornell.edu/subscribe/subscribe.tml" method="POST">
        <table border=0 cellspacing=0 cellpadding=3>
            <tr>
                <td align="right">
                    <font size=1>Email address: </font>
                </td>
                <td>
                    <input type="text" name="email" value="" SIZE=10>
                </td>
                <td>
                <input type="submit" class="btn" value="subscribe" title="subscribe" alt="subscribe"  name="subscribe" align="left">
                </td>
            </tr>
        <tr>
            <td align="right">
                <font size=1><I>(required)</I> Your name: </font>
            </td>
            <td>
                <INPUT TYPE="text" NAME="name" VALUE="" SIZE=10 MAXLENGTH=100>
            </td>
        </tr>
        </table>
    <input type="hidden" name="list" value="urban-data-science-rg-l"><input type="hidden" name="lists" value="urban-data-science-rg-l" >
<input type="hidden" name="demographics" value="" >
<input type="hidden" name="name_required" value="T" >
<input type="hidden" name="pw_required" value="" >
<input type="hidden" name="confirm" value="one" >
<input type="hidden" name="showconfirm" value="T" >
<input type="hidden" name="url" value="https://github.com/mattwfranchi/EAAMO-Bridges-UDS-S25" >
<input type="hidden" name="appendsubinfotourl" value="" >
<input type="hidden" name="secx" value="880cb564" >

</form>

## Program 

### Spring 2025 Schedule:

#### Monday, February 10 2025 
  - Semester overview (~10 minutes)
  - Guest speaker: [Naveen Raman](https://naveenraman.com)
    - Presentation title: **Global Rewards in Restless Multi-Armed Bandits**
    - Abstract: Restless multi-armed bandits (RMAB) extend multi-armed bandits so pulling an arm impacts future states. Despite the success of RMABs, a key limiting assumption is the separability of rewards into a sum across arms. We address this deficiency by proposing restless-multi-armed bandit with global rewards (RMAB-G), a generalization of RMABs to global non-separable rewards. To solve RMAB-G, we develop the Linear- and Shapley-Whittle indices, which extend Whittle indices from RMABs to RMAB-Gs. We prove approximation bounds but also point out how these indices could fail when reward functions are highly non-linear. To overcome this, we propose two sets of adaptive policies: the first computes indices iteratively, and the second combines indices with Monte-Carlo Tree Search (MCTS). Empirically, we demonstrate that our proposed policies outperform baselines and index-based policies with synthetic data and real-world data from food rescue.
    - Associated readings:
      - [Global Rewards in Restless Multi-Armed Bandits](https://arxiv.org/abs/2406.00738)
  - Discussion on food rescue in urban settings.
    - Recommended additonal readings:
      - [Improving Efficiency of Volunteer-Based Food Rescue Operations]([https://www.sciencedirect.com/science/article/pii/S0049089X16301764](https://ojs.aaai.org/index.php/AAAI/article/view/7051))

#### Monday, February 24 2025 
  TBD
  
#### Monday, March 10 2025 
  TBD

#### Monday, March 24 2025 
  TBD

#### Monday, April 7 2025 
  TBD

#### Monday, April 21 2025 
  TBD

#### Monday, May 5 2025 
  TBD
  
#### Monday, May 19 2025 
  TBD


### Invited Speakers: 
- [Zhi Liu](https://zhiliu724.github.io) (10/09)
- [Sidhika Balachandar](https://sidhikabalachandar.github.io) (10/09)
- [AJ Alvero](https://ajalvero.com) (11/06)
- [Wonyoung So](https://wonyoung.so) (11/20)
- [Andrea Vallebueno](https://andreavalleai.com) (12/04)
- [Naveen Raman](https://naveenraman.com) (02/10)

### Organizers: 
We welcome involvement in this working group! If you're interested in joining, please reach out to one of the organizers: 
- Jennah Gosciak (jrg377 AT cornell dot edu) 
- Matt Franchi (mwf62 AT cornell dot edu)
- Gabriel Agostini (gs665 AT cornell dot edu)
  
-------------------------------------------------------------
### Fall 2024 Schedule: 

#### Wednesday, September 25 2024 
  - Short introductions (1-2 minutes each)
  - Discussion on our working definition of urban data science. Readings:
    - [Urban analytics defined](https://journals.sagepub.com/doi/10.1177/2399808319839494)
    - [Defining urban data science](https://journals.sagepub.com/share/ZRN9UCWSQHPWJHYWBGYY?target=10.1177/2399808319882826)
  - Gauging interest in working group research collaborations
    - [Strava metro dataset](https://www.strava.com/clubs/231407/posts/32218967)
   
#### Wednesday, October 9 2024
  - Guest speakers: [Zhi Liu](https://zhiliu724.github.io) and [Sidhika Balachandar](https://sidhikabalachandar.github.io)
    - Presentation title: **Models to Correct Under-Reporting in Urban Crowdsourcing Systems**
    - Abstract: Decision-makers often observe the occurrence of events through a reporting process. City governments, for example, rely on resident reports to find and then resolve urban infrastructural problems such as fallen street trees, flooded basements, or rat infestations. Without additional assumptions, there is no way to distinguish events that occur but are not reported from events that truly did not occur. Because disparities in reporting rates correlate with resident demographics, addressing incidents only on the basis of reports leads to systematic neglect in neighborhoods that are less likely to report events. We show how to overcome this challenge in three different settings and estimate reporting rates. First, we leverage the fact that events are spatially correlated and propose a latent variable Bayesian model. Second, we propose a method to fit graph neural networks with both resident report and city inspection data. And third, we incorporate the report delay and the possibility of multiple reports in a Poisson Bayesian model. Our work lays the groundwork for more equitable proactive government services, even with disparate reporting behavior.
    - Associated readings:
      - [Quantifying Spatial Under-reporting Disparities in Resident Crowdsourcing](https://arxiv.org/abs/2204.08620)
      - [A Bayesian Spatial Model to Correct Under-Reporting in Urban Crowdsourcing](https://arxiv.org/abs/2312.11754)
  - Discussion on biases and uses of resident crowdsourcing data.
    - Recommended additonal readings:
      - [Using small data to interpret big data: 311 reports as individual contributions to informal social control in urban neighborhoods](https://www.sciencedirect.com/science/article/pii/S0049089X16301764)

#### Wednesday, October 23 2024 
  - Working group activity: **Crafting Research Abstracts: Strava dataset**
  - Goal: Gauge interest to collaborate on a project using the [Strava metro dataset](https://www.strava.com/clubs/231407/posts/32218967) + outline a project proposal
  - Instructions:
     - Read and familiarize yourself with the [Strava metro dataset](https://www.strava.com/clubs/231407/posts/32218967)
     - Think of a research project you would like to pursue with the dataset. If possible, focus on areas of common interesting to the group (equity, urban mobility, housing, policy, etc).
     - Please submit a ``dream research abstract'' on a paper using the Strava dataset. That is, write an abstract as if you have published a paper using the dataset.
       - Include clear motivations and problem statements.
       - Outline briefly the methods you would plan to use.
       - Include ``expected results'': ideally, what do you expect to find? This will help us understand whether, assuming the research is successful, the project is worth pursuing.
       - (Optional) Include a small bibliography of related work.
    - We will get in breakout rooms and analyze a few selected abstracts. Working group members are encouraged to select aspects of each proposed project that are of interest.
      
#### Wednesday, November 6 2024
  - Guest speaker: [AJ Alvero](https://ajalvero.com)
    - Presentation title: Who Do Large Language Models Write Like? A Sociolinguistic Perspective on AI-Generated Texts
    - Abstract: When large language models (LLMs) generate "human-like text", which humans do they write like? The answer to this question has strong implications for their use as methodological tools across the social sciences, but they also point to new dynamics to consider in important social processes. In this presentation, I will discuss ongoing work that compares the text produced by LLMs with personal statements written by applicants to selective colleges and universities. We use the Linguistic Inquiry and Word Count (LIWC) dictionary to compare stylistic features backed by psychological research and various embedding approaches that are popular in computational social science. Both approaches yielded similar sets of findings: LLM writing style is distinctive from humans but is closer to those with higher social status. Conversely, we also find that LLMs are stylistically narrow but have broad vocabularies. These results helped us formulate two perspectives for future research on the intersection of sociolinguistics, text, and LLMs: the sampling perspective, based on linguistic closeness (in our case, LLMs were closer in their text to higher social status applicants); and the distributional perspective, based on variation in text features (in our case, LLMs had notably distinctive distributions from any group of humans). We hope this work can help spur not just more empirical work but also theoretical work about human language as it compares and interacts with LLMs.
    - Associated readings: [Large language models, social demography, and hegemony: comparing authorship in human and synthetic text](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-024-00986-7)
     
#### Wednesday, November 20 2024
  - Guest speaker: [Wonyoung So](https://wonyoung.so)
    - Presentation title: Reparative Urban Science: Challenging the Myth of Neutrality and Crafting Data-Driven Narratives
    - Abstract: I offer how urban planning should approach technology within the context of systemic racism, advocating for a reparative approach to address the issues of urban technology perpetuating today’s racial inequality and hindering efforts to redress historical oppression. I identify three mechanisms – formalization, context removal and legitimization, and penalization and extraction – that illustrate how urban technology perpetuates historical inequalities, often penalizing marginalized groups under the pretext of neutrality and fairness. Then, I discuss methodologies of reparative urban science, aiming to use urban technology to challenge race-neutral ideologies and create data-driven narratives for reparations.
    - Associated readings: [Reparative Urban Science: Challenging the Myth of Neutrality and Crafting Data-Driven Narratives](https://www.tandfonline.com/doi/full/10.1080/14649357.2024.2397017)

#### Wednesday, December 4 2024 --- CANCELLED
  - Guest speakers: [Andrea Vallebueno](https://andreavalleai.com)
        
#### Wednesday, December 18 2024
  - Working group activity: Finding EAAMO-suitable projects in UDS
