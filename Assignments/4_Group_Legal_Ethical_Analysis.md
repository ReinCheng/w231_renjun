## Group Project: Legal/Ethical Analysis of Reidentification in Open Datasets 

### Overview

For this assignment, we will assign you to a group of 2 to 4 students. We want you to start with information in a public (open) dataset and see what sleuthing you can do to find more information about a person/population of interest across other publicly-available datasets - in short, what kinds of reidentification are possible starting with your dataset, and what the legal or ethical implications of that reidentification may be. You could think of this as demonstrating the implications of various kinds of unexpected PII that exist in the dataset you choose. It is pretty effective to demonstrate this with a couple of specific case studies, connecting them to other datasets to show just how much data is out there on the individual(s) of interest you found in your starting dataset, but it isn't the only way to go about it. Example open datasets to begin with are listed below; however, you are welcome to use any dataset. 

Please write up an analysis of the legal and ethical implications of having this dataset open, _written as if you are addressing the group that decided to make it open._ As such, please write clearly and persuasively, acknowledging the reasons the group might have had in making the dataset public but then succinctly explaining the possible issues you've identified and the frameworks that back up your assessment. (Imagine that your team are consultants hired by this group, if that helps.) You will be graded on clarity and persuasiveness - take this as an opportunity to practice convincing someone who may not know much about the ethical implications here! Please do write your critique about one dataset primarily, even if you draw on others to demonstrate your point.  Please review the [Writing Practices](https://github.com/UC-Berkeley-I-School/w231/blob/master/README.md#writing-practices) section of the syllabus for more detail about expectations for your writing in this course.

Be sure to describe this dataset and trace the implications of its openness through demonstration. In addition to a description of the analysis and findings, please address the following questions:
* Was anything surprising about the data included in this dataset? Why or Why not?
* Consider the issues that you have identified through the lens of the privacy frameworks we've learned about. Focusing on one or more of these frameworks - as many as needed to make a persuasive case! - what could be employed to address some of the privacy risks or concerns that you have highlighted?
  * Solove's Privacy Taxonomy: Consider aspects of Information Collection, Processing, Dissemination and Invasions that could be addressed. How might you address a few specific items?
  * Nissenbaum's Contextual Integrity: How might you employ enhancements to both transparency and choice to address some of the risks identified?
  * Mulligan/Koopman's Privacy Analytic: Identify some dimensions of Theory, Protection, Harm, Provision, and Scope that could be used to frame an approach toward addressing some of the risks identified.
* What are the issues you have identified and how could they be addressed? Can they be addressed through technical means, more laws and regulations, better practices and education or some combination? Or is it not really clear they could be addressed at all?
* Should the use of Open Data be governed by a code of conduct or subject to a review process before being released? What would this change for your dataset, if anything?
* In order to enhance privacy, should governments develop guidelines to release sampled or perturbed data (e.g. using differential privacy or other methods), instead of entire datasets? What would this change for your dataset, if anything?
* When datasets contain potentially identifiable information, should there be a notice-and-comment proceeding that includes proposed technological solutions to anonymize, de-identify or otherwise perturb the data? Again, what would this change for your dataset, if anything?

### Deliverables
The deliverables for this assignment are both **an 8-minute in-class presentation and a written report**. 

For your **presentation,** please have slides to present a summary of your analysis to date and any additional work you plan to do, and remember to address your presentation to the group that decided to make the dataset you started with open. Your papers do not need to be fully completed when you present; just note any work still in-progress in your slides. Remember that your performance in this presentation is NOT a part of your grade, so please don't stress about this! We hope this is a safe place to practice a skill that some may find to be challenging, but is a common part of being a data scientist and also important for doing advocacy work. If you would rather pre-record your presentation instead of presenting live, please let us know and we can accommodate that instead.

Your **written report** can be organized however your group sees fit, though do please attend to all of the questions listed above. The written report is due after the presentation to allow for you to adjust your report based on in-class feedback. There is no firm word length requirement for this assignment, since things will depend a lot on what you are able to find. However, even if you don't have any PII or other ethical implications to report, you should be thorough in your discussion of why that is the case. As a rough guide, based on past assignments the bare minimum seems to be at least four concise and well-argued pages - about 1200 words double spaced - but will very likely be more like 8-12 pages.

Please submit papers and slides **via ISVC.** Only one group member needs to submit the report and slides, though please make sure all member names are included on the assignment. There is no need to update the slide deck after your presentation, but please do submit it along with your paper just for our reference.

**The Null Case:** If you are unable to find any legal or ethical implications around privacy, fairness, etc. in the dataset(s) you examine, prepare a log of your process, including what you looked for and what tools might have impacted your ability to glean additional information. Also look into whether the data managers documented their process of deidentifying the dataset, and (optionally) consider comparing it to similar datasets collected elsewhere that may not have been deidentified in the same ways or as effectively. 

### Grading Rubric

Description | Exceptional | Good | Needs Work
-|-|-|-
Background | Clearly describes dataset and the context for its release; includes detail about how this information was found. | Describes dataset and its context, but with gaps. | Little or no description of what is in dataset and its context for release.
Privacy Frameworks | Judiciously chooses aspects of Solove, Nissenbaum, and/or the privacy analytic that best highlight strengths and weaknesses of the open dataset. | Applies aspects of Solove, Nissenbaum, and/or the privacy analytic, though without strong justification for why those are the most salient aspects to choose. | Misuses or omits discussion of privacy frameworks.
Addressing Issues | Clearly identifies issues in the dataset and suggests concrete solutions, grounded in course materials. | Identifies some issues and suggestions solutions, but lacks specificity or misses connections to course materials. | Misunderstands issues present or does not identify issues, does not identify solutions for these issues.
Addressing Common Solutions | Thoroughly explores how concerns would change with a code of conduct/review process, sampled/perturbed data, and notice-and-comment processes for PII. | Addresses at a superficial level how concerns would change with a code of conduct/review process, sampled/perturbed data, and notice-and-comment processes for PII. | Misunderstands or fails to address one or more of these.
Concrete Evidence | Provides persuasive concrete evidence for claims. | Does not consistently provide concrete evidence, but provides some. | Fails to provide concrete evidence (e.g. states opinions with no backing). 
Clarity of writing | Clearly organized and persuasive writing. Convincingly role-plays writing directly to group who released the dataset, using an appropriate tone for a report to this group. | Some difficulties following the argument, not as concise as it could be. Not clearly addressed to group who released the dataset. | Very hard to follow argument; either lots of filler or much too short/underdeveloped.

### Example Datasets

Here are a few examples to get you started; feel free to use them or find your own:
* US City Open Census Data: http://us-city.census.okfn.org/about/
* Open Data Vancouver: http://vancouver.ca/your-government/open-data-catalogue.aspx
* AWS Public Datasets: https://aws.amazon.com/datasets/
* DataShop: https://pslcdatashop.web.cmu.edu/
* OECD Statistics: http://stats.oecd.org/index.aspx
* UN Data: http://data.un.org/Explorer.aspx
* MDG Indicators: http://mdgs.un.org/unsd/mdg/Data.aspx
* Time Series Data Library: https://robjhyndman.com/TSDL/
* National Centers for Environmental Information: https://www.ngdc.noaa.gov/ngdc.html
* Data.gov.uk: https://data.gov.uk/
* World Bank Open Data: https://data.worldbank.org/

### Groups

Group assignments will be posted a few weeks before the assignment is due, and will be posted on [Slack](https://app.slack.com/client/T0WA5NWKG/C6WKWFVR6/).

**NOTE** that while you may divide up the work as you see fit, all group members are expected to contribute roughly equally to the project. If you feel that a member of your group isn't pulling their weight, please feel free to reach out to us to help resolve it. We *may* ask everyone for an estimate of how much each member of their team contributed either during or after the group project.

We also want to remind you of the commitment in this class more generally of being constructive and respectful of your classmates at all times, which certainly extends to group work. If you experience or witness behavior that is not in keeping with this commitment, please let us know so we can address it. We also encourage you to be mindful of whether a group member is dominating conversations, talking over others, etc., and reaching out for help resolving any issues as needed. Please remember our overall course commitment to [being a good team player](https://github.com/UC-Berkeley-I-School/w231/blob/master/README.md#statement-of-diversity-and-inclusion).
