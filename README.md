
# Data Challenge

# Overview
For this data challenge, your goal is to use new baseball data on bat speed and swing length to analyze some aspect of the pitcher/batter interaction. We provide pitch-level data from Baseball Savant for 346,250 Major League Baseball plate appearances from 4/2/2024 to 6/30/2024, including relevant Statcast data along with bat speed and swing length on pitches with a swing tracked. Data from the second half of the season will be added after the conclusion of the regular season. Your analysis should involve bat speed and swing length to study any topic related to the batter, pitcher, or batter-pitcher interaction during an at bat.

Since these data are new, there are a variety of topics that have not previously been studied. Below are a few example topics. However, we note that this list is far from exhaustive. Participants should feel free to study any aspect of the batter, pitcher, or batter-pitcher interaction that interests them, provided that bat speed and swing length are used in the analysis in some meaningful way.
  - Batter Specific Plate Discipline. Can bat speed and swing length be used to measure some aspect of plate discipline?
      - Are these data useful in analyzing a batter’s decision to swing at a pitch? For example, can faster swingers be more patient?
        - Are bat speed or swing length related to a hitter’s ability to foul off 2-strike pitches, or protect the plate?
        - How is pitch location related to the above ideas? See https://baseballsavant.mlb.com/visuals/swing-take?playerId=545361 which may give you some ideas.
    
  - Do players have different types of swings? Are these swing types related to situation (count, base runners, outs), pitcher, pitch location, pitch type, or anything else?
    
  - Do pitchers modify batter behavior or do batters modify pitcher behavior (or neither! Or both!!):
        - Can pitchers “dictate” swings, or is it all the batter? Are swing lengths longer against certain pitchers? To what extent is that due to pitch velocity or spin rate, as opposed to other pitcher-specific factors?
        - Do pitchers modify behavior against batters with higher/lower bat speed (e.g. throw to different locations, throw different types of pitches, etc.)?
    
# Data
The data is in this shared folder. The csv file is large and may not open in the online version of Excel in your web browser. You'll have to click Download and create a local copy on your computer. The file contains data up through June 30, 2024. Data from the second half of the season will be updated at the end of the regular season.

The data is also available in Apache Arrow format, which is an efficient, columnar, in-memory format designed to facilitate fast data analytics and interoperability between different systems. Example codes to read the data into Julia, Python, and R are on GitHub here or on Kaggle here.

Please see here for a glossary of terms and here for background on how Statcast bat tracking data works.

# Data Challenge Registration
Given the challenge's popularity, we would like to know the number of participating teams to adequately prepare and recruit the necessary judges. Please register for the data challenge by December 1, 2024.

# Submission
Students must submit a zip file containing:
  - A pdf report describing their results (max 3000 words)
  - A folder with
        - Documented code files
        - A README file describing what each file does.
        - (Optional) If you use additional public data, include it here to ensure your work is fully reproducible

Note: Students can include other files including any app code or supporting documents. Any code or apps included need to be self-contained and able to run on reviewers’ computers without modification.

# Eligibility
The CSAS 2025 Data Challenge is open to students only. You must be enrolled as a high school, undergraduate, or graduate student at some point during the 2024-25 academic year. Participants must register using their school email address.

Teams must enter one of the following two tracks:
  - High School / Undergraduate Track
  - Graduate Track
    
To be eligible for the High School / Undergraduate ALL members of the team must consist of either high school and/or undergraduate students. Each team can have up to 3 members. The team captain, if 18 years old or over, should fill out the registration form for the entire team using their school email addresses. If all team members are under 18, a faculty advisor needs to be the point of contact and register for the team.

# Judging Criteria
A panel of judges from across academia and the sports industry will judge your submissions based on the following:
  - How original is the analysis?
  - How applicable is the analysis?
  - How appropriate were the methods used?
  - How well did you communicate your findings? This includes both written text and visualizations. How did the use of facts, data-supported narratives, anecdotes etc. enhance your storytelling?

# Prizes
Finalists (Six teams: three high school / undergraduate and three graduate) will be invited to present their work at CSAS 2025 in New Haven, CT, and will receive some travel support and have their registration fees waived. Winning teams will have the opportunity to showcase their team’s work to data scientists in the baseball industry. The winning teams will also receive a cash prize and a plaque.

# Webinar Introduction/Office hours
An introductory workshop led by members of the CSAS organizing committee and members of the baseball industry will be planned in early October. We will give a short introduction and spend most of the time on Q+A.

# Important Dates
  - Data challenge release: September 13, 2024
  - Webinar introduction: coming soon!
  - Participation registration: December 1, 2024; given the challenge's popularity, we need to know the number of participating teams to adequately prepare and recruit the necessary judges.
  - Submission deadline: January 15, 2025
  - Finalists notified: February 15, 2025
  - CSAS 2025: April 11-12, 2025
