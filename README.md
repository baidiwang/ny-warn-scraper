# What we know from NY Warning Notices

### By checking and analyzing the website of Worker Adjustment and Retraining Notification issued by NY Department of Labor, we are able to get some conclusions that worth paying attention on.

-   The story is based on findings from NY warn notifications of COVID_19 that are worthwhile to know. With the spread of coronavirus, the story is able to show some useful information for people to predict when the pandemic will end.
-   The single question the story answers is how does the coronavirus is influencing the unemployment issue.  
-   I believe the story will attract attentions from audiences, especially people losing jobs during the pandemic. The coronavirus lead to a huge increase of U.S. unemployment rate, and some findings of NY warn notification of labor market may help provide some hints for people to go over the hard time.

What else has been done on this topic (provide links)? How is your angle different or fresh?

-   [April’s job losses highlight the depth of the pandemic’s devastation(NYT)](https://www.nytimes.com/2020/05/08/business/stock-market-coronavirus-jobs-report.html?campaign_id=60&emc=edit_na_20200508&instance_id=0&nl=breaking-news&ref=headline®i_id=95580981&segment_id=26932&user_id=38aad6f9f85b35c65cae31d6aebc8214#link-7634dae)

Write up at least one or up to three findings from your analysis based on the data you found.

-   The majority reasons for filing the Warn Notices this year are temporary plant layoff and temporary plant closing because of the coronavirus.
-   The major reason for dislocation of filing notices is "Unforeseeable business circumstances prompted by COVID-19", which reflects the damage of the coronavirus.
-   Finding 3

Who are some potential human sources you could reach out to for more info?

I may directly call the NY labor department to confirm the accuracy of this source and also their suggestions for this source , and also I will call some businesses to ask their thoughts about this warn notice list.

What is the maximum (best) story possible? What's the minimum (fallback) story if your hypothesis doesn't prove out?

Whether the story is good depends on how many good finding I get from the source. I don't think I cannot find anything from the data, but at least one story can be told with the minimum findings I get, as there are several points in the list that are worth to be analyzed.

## How to publish and submit your project

1.  Make sure you have navigated to your `data-journalism` folder with your terminal first. Clone a fresh copy of this template and navigate to the folder.

        git clone git@github.com:JOUR73351/ny-warn-scraper.git
        cd ny-warn-scraper

2) Remove my git tracking from the project

    rm -rf .git

3) Create a new repository on GitHub called `ny-warn-scraper` with the following settings.
   <br>
   <img src="assets/newrepo.png" width="500">

4) Run these git commands to initialize the repo. Make sure you've checked `ssh`.

    git init
    git add -A
    git commit -m "first commit"
    git remote add origin git@github.com:YOUR-USERNAME-HERE/ny-warn-scraper.git
    git push -u origin master

5) Write your pitch in `README.md`.

6) Run `pipenv install` to install all of the python dependencies and run `pipenv run jupyter lab` to start Jupyter.

7) Scrape the [WARN notices](https://labor.ny.gov/app/warn) from the NY Department of Labor website and output to `data/warn.csv`. Your scraper code will live in `notebooks/scrape.ipynb`.

   Extra credit if you can scrape previous years' notices as well. Here's a clue:

    https://labor.ny.gov/app/warn/default.asp?warnYr=2019
    https://labor.ny.gov/app/warn/default.asp?warnYr=2018
    https://labor.ny.gov/app/warn/default.asp?warnYr=2017
    ...

   Can you do this in a loop?

8.  Come up with some questions about the data and try to answer them with pandas functions. Analyze the data you've scraped in `notebooks/analyze.ipynb`. You will probably need to do a bit of data cleaning in pandas and convert some columns to integers. Export the data you are visualizing in a chart in the `output` folder.

9) Write your story in and add your assets and charts to `index.html`. Feel free to play around with and change the styles in `style.css`, but you are not required to. Delete the code that you don't need for your story. The story itself should be no less than 150 words and include at least one chart from Datawrapper. You can embed a Datawrapper chart in your story by copying the embed code into your html as I have done in `index.html.`
   <br>
   <img src="assets/datawrapper.png" width="500">

10) You can preview a local version of your story by running a python server.

    python -m SimpleHTTPServer 8000

Then, navigate to `http://localhost:8000` in your browser. Before step 8, you must quit the python server by pressing `ctrl+c`.

11. To save a version of your story on GitHub, run the following git commands.


    git add -A
    git commit -m "YOUR-COMMIT-MESSAGE-HERE"
    git push

12. To publish, go to the settings of your GitHub repo, scroll down to GitHub Pages, and configure the source to the master branch.
    ![GitHub Pages](assets/ghpages.png)
