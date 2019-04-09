# Exercise description

Our goal for this exercise is to evaluate your ability to:

* Analyze data using SQL or Python
* Think creatively about how to solve problems and drive your ideas forward
* Identify and call out infeasible/too vague/low-value requests

To help us evaluate this, we have provided you a .dbc file (Databricks archive format) that contains some canned employment data, and a number of questions about that data.

Some of these questions are trivial, some are tricky, and some are impossible to answer (either because required data is missing or the question is too vague). Also, some of these questions are interesting and some are not. By "interesting", we mean that the question is related to a real business concern, or reveal an answer which promotes some useful action being taken by a business.

For instance, take the example question provided, "How many unique people are there?" This is easy to answer, but it is not interesting. Who cares how many unique people there are? The decision about what is interesting and what is not is yours to make. Use your intuition and try to think from the perspective of an employer.

Your task is to go through these questions and pick a subset of them that you think are particularly interesting, and then either answer them or explain why they can't be answered.

Specifically, you need to do the following:

* Pick 10 questions out of the list, based on which questions are best aligned with problems a business would face, or improvements that a business may want to make.
* We expect a mix of questions that you can answer, and those you cannot answer. For example, some questions might be very interesting, but you have not been provided enough data to answer them.
* Also, please come up with 2 new questions that you think would be interesting for a business to know:
    * One that can be calculated from the data you have, and please provide the answer
    * One that cannot be calculated, and please describe what is needed to answer it
* Your deliverable is an updated version of the .dbc file you received, with the response section for each question filled out as follows:
* For each answerable question you picked, include code to calculate the answer
* For each unanswerable question you picked, describe what extra data or information you need in order to answer
* For each question you did not pick, just leave the response area blank
* Fill out the cells for the two new questions you added, at the end of the notebook

In your on-site interview, we will review this file, and you should be prepared to explain:

* Why you chose what you chose (why is this valuable to a business?)
* Why you did not choose what you did not choose (why is this not valuable?)
* How you would approach the unanswerable questions you chose, if you were provided with the extra data or information you need.
* How you did your calculations for the answerable questions you chose, and how you might solve them using other tools.

## Databricks instructions

### Sign up

First step is to sign up for the free Databricks Community Edition: [https://databricks.com/signup#signup/community](https://databricks.com/signup#signup/community)

After you've signed up and logged in, you should be at the homepage with "Welcome to databricks" at the top.

### Upload provided assignment

To upload the assignment (.dbc file):

1. Click on "Workspace" in the left side panel
2. Select Users, then your username (should be your email). This is your "home directory" within Databricks.
3. Create a folder to store your exercise by right-clicking, selecting "Create" and then "Folder"
4. Inside of that folder, right-click and select "Import"
5. Click on the "browse" link in the popup window and navigate to the provided .dbc file. Then click Import.
6. This will place a file called  "WP\_DA\_exercise" in your folder. Click on it to open it up.

### Export

1. Select "File" at the top of the screen
2. Then select "Export"
3. Select "DBC Archive" as the format
4. Then email us back the downloaded file