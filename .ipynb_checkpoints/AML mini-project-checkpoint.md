In the project, you will use machine-learning techniques in a realistic setting. We will provide a set of [projects and corresponding datasets](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#projects) that you can choose from. You will work in groups of 3 people[1](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#fn:1), using [Piazza](https://piazza.com/ed.ac.uk/fall2023/infr1121120234sv1sem1/home) to [find teammates](https://support.piazza.com/support/solutions/articles/48001158117-search-for-teammates), and will collaborate to produce a project report that will be assessed.

> Each group only submits **one** report. All members of the group will receive the same grade, excepting any special/extenuating circumstances. The grade will be based on the final report only.

You will have considerable freedom in the projects, but it should involve most parts of techniques described in the lectures. This would typically involve

- reading up on some relevant background to well understand the task and what has been done previously (via google scholar, internet search, in some cases references are provided)
- some exploratory data analysis
- if classification is the goal, choosing methods that might work well on the task, based on the earlier steps
- evaluating the results of the different methods on the task (e.g. assessing generalisation performance).

Note that you’re not required to outperform prior methods. The important thing is that the approaches taken are reasonable, methodologically correct, and clearly described in the report. Good projects would nonetheless discuss possible reasons for performance differences compared to more advanced approaches.

> - Sample project reports that provide a rough guide for what goes into the projects
>     - [Example 1](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/data/example-1.pdf): scored around 70% and slightly above
>     - [Example 2](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/data/example-2.pdf): scored around 60%

## [](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#faq-)FAQ

1. Are we allowed to explore methods that are not explicitly covered in the course?
    
    Yes, that’s perfectly fine. There is no requirement to stick to just using what is taught in the course. Having said that, it is your responsibility to ensure that your report covers enough of the background material for whatever methods you employ so that an intelligent reader will be able to follow your reasoning and evaluate your findings.
    
2. What needs to be put in the main report and what goes in the appendix?
    
    All the text and figures required to understand and evaluate your contributions need to go within the 6-page limit. If you wish, you may include an optional additional appendix after the references and your statement of contribution.
    
    The appendices are not directly evaluated; much like is standard practice for academic papers. The purpose of an appendix is to allow for extra material that is not essential to the understanding of the main paper, but helps provide a more comprehensive understanding of the undertaken research. The reviewers/markers are not obligated to read appendices/supplementary material. They may choose to do so, but don’t have to.
    
3. What details about the team should we provide in the report.
    
    You should only provide the student IDs (UUNs) of the team members (not exam numbers). Please don’t provide your names, emails, or other information. We have updated the template to reflect this.
    
4. Can we use Generative AI (ChatGPT, etc) for the coursework?
    
    Please see [Guidance on the use of Generative AI](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/about/#genai) in the course information page.
    

## [](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#important-dates)Important Dates

Fri 06 Oct, noon (wk 3)

Each group (any **one** member) should fill-in the [project details form](https://forms.office.com/e/SMuXX7RyXC) with the student numbers (UUNs) of the members and the choice of project topic.

TBA

Each group must upload a progress report using the [project interim report form](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/). The report should be maximum 2 pages long, and should use the same latex template provided for the full report. It should include a section on “Current Progress” and “Plans for Completion”. The interim report will not form part of your mark for the course. The goal here is to ensure your project has the right scope and that you are on track.

TBA

Final report due. You should submit the report as a single PDF, including references and appendices, with the filename as your 2-digit group number. For example, group 6 would submit `06.pdf`.

The maximum page limit is 6 pages, and the references, statement of contribution, and appendices do not count towards the page limit.

## [](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#authors-instructions)Authors’ Instructions

The report should be maximally 6 pages long (excluding references), using this [report template](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/data/aml_latex_template.zip)[2](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#fn:2) (adapted from the NeurIPS template). It should contain the following in some manner:

- description of the task
- relevant background and related previous work
- explanation of the significance/relevance of the objective/task
- information on the data preparation
- exploratory data analysis
- description of the learning (e.g. classification) methods used
- results and evaluation
- conclusions

You are expected to discuss the work within your group, and to work on your report together. You should write up the project as a whole, including the work of the others in your project. Please cite your sources (data, methods, etc.) appropriately.  
At the end of the report, there should be a short description of how each member of the group contributed to the project, which can be on an additional page (not counted for page limit).

## [](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#marking)Marking

The marking criteria include the appropriateness of the machine learning methods chosen, quality of the analysis, the quality of the evaluation, the amount of work, and the quality of the explanation of the report (both text and graphics). While you will be marked out of 100 in line with the [common marking scheme](https://web.inf.ed.ac.uk/infweb/student-services/ito/students/common-marking-scheme), an interpretation of the scheme with letter grades can be seen as:

A:

Well explained description of points above plus extra achievement at understanding or analysis of results. Clear explanations, evidence of creative or deeper thought will contribute to a higher grade.

B:

Well explained description of points above.

C:

Good description of points above but significant deficiencies.

D:

Evidence that the student has gained some understanding, but not addressed the specified task properly.

E/F/G:

Serious error or slack work.

### [](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#good-scholarly-practice)Good Scholarly Practice

Please remember the good scholarly practice requirements of the University regarding work for credit. You can find guidance at the School’s page on [academic misconduct](https://web.inf.ed.ac.uk/infweb/admin/policies/academic-misconduct).

---

## [](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#projects-)Projects

### [](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#spotify-analysis)Spotify Analysis

You are a [skunkworks](https://en.wikipedia.org/wiki/Skunkworks_project) team within Spotify tasked with exploring ways by which the company can get better insight about the artists, albums, and user preferences for music. You’ve been given access to data from the “Top 200” playlists published globally by Spotify from 01/01/2017 to 31/05/2023 comprising of nearly 0.5M songs composed of different regional charts! This data has canonical information such as track titles, artist info, url, and so on.

To help you analyse things better, you have been authorised access to additional information compiled by the User-engagement and Metrics team, which includes:

- scores for features associated with tracks, like ‘danceability’, ‘instrumentalness’, and so on,
- custom overall rank from a points system for tracks based on individual-playlist rank (200 points for first, 1 for last), and
- per-artist scores where multiple artists have collaborated on track (equal split)

Your task is to analyse the data given to you and explore predictive tasks that could provide the company with insight on some burning questions such as:

- What drives cross-regional popularity of music; is it the artist, or something about the song?
- Can we figure out which artists or genres are going to be popular in 2024 given the historic data from 2017?
- Does the popularity of a track in one region predict its (upcoming?) popularity in other regions?
- Are there any patterns in what day(s) of the week and/or months experience the most streams?

Note

Please use delimiter `";"` to read the data csv file correctly.

[Link to data](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/data/spotify_data.zip)

### [](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#species-analysis)Species Analysis

You’re an NGO looking into ecology and the preservation of animal species in the world. The data you have available to you is the geospatial distribution of animal sightings and prevalence, which identifies what species of animals have been seen where in the world. As part of the analyses into understanding what measures can be taken to help conservation efforts, there are a number of potential questions that one might consider, including

- For any given species, where can one find them in the world?
- For a given region in the world, what species may be observed there, and to what prevalence?
- Can we answer such questions for multiple species or regions _simultaneously_?

The data has been processed for you in terms of train and test files already, including some additional training data if you would like to use it to explore different questions. A simple script that details how to load and minimally visualise this data is also included.

[Link to data](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/data/species_data.zip)

1. Excepting special/extenuating circumstances. [↩](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#fnref:1)
    
2. You can use Overleaf through the University to create and edit LaTeX documents. See [https://www.overleaf.com/edu/edinburgh](https://www.overleaf.com/edu/edinburgh). [↩](https://www.inf.ed.ac.uk/teaching/courses/iaml/aml/mini-project/#fnref:2)