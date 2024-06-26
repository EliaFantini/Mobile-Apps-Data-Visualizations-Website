<p align="center">
  <img alt="📈 Mobile_Apps_Data_Visualizations " src="https://github.com/EliaFantini/Mobile-Apps-Data-Visualizations-Website/assets/62103572/603e0da9-9ba1-4528-9e13-065f6abde299">
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/y/EliaFantini/Mobile-Apps-Data-Visualizations-Website">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/EliaFantini/Mobile-Apps-Data-Visualizations-Website">
  <img alt="GitHub code size" src="https://img.shields.io/github/languages/code-size/EliaFantini/Mobile-Apps-Data-Visualizations-Website">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/EliaFantini/Mobile-Apps-Data-Visualizations-Website">
  <img alt="GitHub follow" src="https://img.shields.io/github/followers/EliaFantini?label=Follow">
  <img alt="GitHub fork" src="https://img.shields.io/github/forks/EliaFantini/Mobile-Apps-Data-Visualizations-Website?label=Fork">
  <img alt="GitHub watchers" src="https://img.shields.io/github/watchers/EliaFantini/Mobile-Apps-Data-Visualizations-Website?abel=Watch">
  <img alt="GitHub star" src="https://img.shields.io/github/stars/EliaFantini/Mobile-Apps-Data-Visualizations-Website?style=social">
</p>

This repository contains the code for the website containing Data Visualizations about Mobile Apps made in the frame of the Data Visualization (COM-480) project.

Here is our website: [App Data Visualization](https://com-480-data-visualization.github.io/project-2023-insightsquad/website/index.html)

You can read the process book [here](https://github.com/com-480-data-visualization/project-2023-insightsquad/blob/master/Process%20Book.pdf)

The screencast of our website is accessible [here](https://drive.google.com/file/d/1oxTCTbaSyfDESRPNZTkW6QAaLD89s7Wa/view?usp=sharing).

## Authors 

-  [Fantini Elia](https://github.com/EliaFantini)
-  [Adrien Vauthey](https://github.com/Lugiasc)
-  [Konrad Litwiński](https://github.com/MirazSpecial)

### Problematic

Mobile applications have become an integral part of our daily lives and their market grows rapidly. According to recent studies ([source 1](https://www.grandviewresearch.com/industry-analysis/mobile-application-market#:~:text=Report%20Overview,13.8%25%20from%202023%20to%202030), [source 2](https://www.statista.com/statistics/292751/mobile-gaming-revenue-worldwide-device/#:~:text=In%202022%2C%20mobile%20games%20are,U.S.%20dollars%20in%20global%20revenue)), the global mobile application market size was valued at USD 206 billion in 2022 and is projected to grow at a CAGR of 13.8% from 2023 to 2030. Mobile games alone held the largest revenue share of more than 42% and are expected to generate approximately 92.2 billion U.S. dollars in annual revenue, accounting for 50% of the global gaming market in 2022 and overtaking the results obtained by AAA console and PC games. Gaming apps are then followed by Music & Entertainment, Social Networks, and Health and Fitness apps. 

With this growth and potential for profit, it is crucial for publishers and indie developers to understand what makes an app successful, and how to utilize the app store's potential to create the next million-dollar app. In this context, data visualization can be a powerful tool to gain insights and identify strategies to create popular apps, as well as highlight failure cases. Additionally, this visualization can be useful for marketers, investors, and researchers who are interested in understanding the dynamics of the mobile app market and its potential for growth.

The goal of this project is then to develop such visualizations by analyzing Google Play Store's data of 2.3 million+ applications together with  1.2 Million+ applications' data from Apple's AppStore.  Our visualization aims at showing the success factors of top-ranked apps: is there a relation between average rating and the number of installs? Does the app support ads and microtransactions? Is it free? Are there better monetization strategies for different categories? All this and more with insightful and aesthetically pleasant visualizations.

### Dataset

The [first dataset](https://www.kaggle.com/datasets/gauthamp10/apple-appstore-apps) from Kaggle is a collection of data related to iOS apps available on the Apple App Store. It includes information on over 1.2 million apps and similar to the previous dataset it contains details such as the app's name and ID, category, rating, price, developer information, content rating, and users' ratings and reviews.  

The [second dataset](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps) is again from Kaggle, from the same author as the first one, and for this reason, it shares many similarities. It is a comprehensive collection of data related to Android apps available on the Google Play Store, with information on over 2.3 million apps. Among the information that can be found, there are the same as in the App Store one plus some precious data such as the number of installs, privacy policy, if it contains in-app purchases or not, and if it has been selected as "Editors' choice". This dataset will be even more useful to analyze the popularity of different types of Android apps and understand trends in the Android app market, while the Apple Store's dataset is more limited but can be used to do some comparison and spot possible differences among the two platforms.

Kaggle already provides the most fundamental info about the datasets, such as missing data, distributions, and pie charts of categorical data. In addition, there is our EDA as well as others from Kaggle's notebooks. The data is already in good condition for the categories we will use, there are a lot of missing values in "Developer website" in the Apple dataset and some in size for the Play Store one. Unfortunately, the "Editors Choice" is useless as all data is equal to "False". Some distributions look regular whereas others present some outliers that are likely very meaningful, such as huge apps with a lot more downloads than the average. We see that little preprocessing and cleaning will be needed and it will vary depending on which information we will decide to focus on among the provided ones.

### Exploratory Data Analysis

Our exploratory data analysis can be found in this [notebook](https://github.com/com-480-data-visualization/project-2023-insightsquad/blob/master/initial_notebook.ipynb)

### Related work

The Google Play Store dataset is a quite famous dataset on Kaggle and has already been explored by many notebooks, and some works can be found on the Apple Store dataset too. Most such notebooks do general exploratory data analysis of the dataset, while others try to train predictors of the number of reviews of a certain app or other simple classifiers. None of these works were trying to address the specific problem that we described and especially not by putting together Android and iOS data. Furthermore, these notebooks provided basic visualizations and statistics, while we plan to go further and tell a "story of success" by creating interactive visualizations that allow users to explore the data in a more intuitive way, as well as more insightful and aesthetically pleasant representations.

To do so, we took inspiration from the best websites about data visualisation such as:

- [The 25 Best Data Visualizations of 2023](https://visme.co/blog/best-data-visualizations/)
- [Dataviz Inspiration](https://www.dataviz-inspiration.com/)
- [Web Design Done Well: Delightful Data Visualization Examples](https://www.smashingmagazine.com/2022/06/web-design-done-well-delightful-data-visualization-examples/) 
- [The D3 graph gallery](https://d3-graph-gallery.com/)
- [DataIsBeautiful from Reddit](https://www.reddit.com/r/dataisbeautiful/)

Among those, we found the first two full of very creative ideas, and we could learn how showing data in a visually pleasant way really makes the difference from learning something out of the data or not. We then aim to do similarly, not only showing useful data in a clear and useful way but also from an original point of view.  More precisely, the following projects really caught our attention:
- [What it takes to go to space](https://www.behance.net/gallery/86241381/Data-Visualisation-What-it-takes-to-go-to-space)
- [The Slow Loss](https://www.behance.net/gallery/151474693/The-Slow-Loss-La-Lettura-dataviz)
- [X-Men comics exploration](https://r-graph-gallery.com/web-streamchart-with-ggstream.html)
- [Adyen's Shareholder report](https://www.visualcinnamon.com/portfolio/adyen-report-2019/)

Following these great examples, we'll try to create our own original and unique visualization.

# Local Website Setup Guide

This guide will walk you through the process of running a website locally on your machine. You will need to download the project repository, open it with Visual Studio Code (VSCode), and use Live Server to host the website.

## Prerequisites

Before you begin, make sure you have the following installed on your machine:

- [Visual Studio Code](https://code.visualstudio.com/download)
- [Live Server Extension for VSCode](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

## Step 1: Download the Project Repository

1. Create a new folder on your machine where you want to store the project.
2. Download the project repository files and extract them into the folder you just created.

## Step 2: Open the Project in VSCode

1. Open Visual Studio Code (VSCode).
2. Click on "File" in the top menu and select "Open Folder".
3. Navigate to the folder where you extracted the project repository files and select it.
4. VSCode will open the project folder.

## Step 3: Install and Use Live Server

1. Open the Extensions view in VSCode by clicking on the square icon on the left sidebar or by pressing `Ctrl+Shift+X`.
2. Search for "Live Server" in the search bar.
3. Click on "Install" to install the Live Server extension.
4. Once the extension is installed, you will see a "Go Live" button at the bottom-right corner of the VSCode window. Click on it.
5. A new browser tab will open, and you will see your website running locally using Live Server.


That's it! Any changes you make to the project files will automatically be reflected in the browser. 

# Design of the website

#### Table of contents:
  * [Website description](#website-description)
    + [First part: Homescreen](#first-part-homescreen)
    + [Second part: Sankey Diagram](#second-part-sankey-diagram)
    + [Third part: Streamgraph](#third-part-streamgraph)
    + [Fourth part: Treemap](#fourth-part-treemap)
  * [Tools to be used and inspirations from lectures](#tools-to-be-used-and-inspirations-from-lectures)


A visual draft of the website is provided below:
![Homepage 1](https://user-images.githubusercontent.com/62103572/235930972-bbe4e114-932d-4167-bdfd-83ad363d4efc.png)


### Website description

The website is designed to provide an overview and detailed analysis of mobile apps from different categories on both Apple and Android platforms. The website is built as one single page that can be divided in four subparts, each containing different data visualizations. \
At the top, there will be a horizontal menu to jump to each part of the website.


#### First part: Homescreen

It is a general overview of the website's content and what users can expect to find. A big heading with the number of total apps covered by the dataset as well as the cumulative amount of downloads of such apps will be displayed. Then we might also put a short phrase to better explain the aim of the visualizations.

<img width="805" alt="image" src="https://user-images.githubusercontent.com/62103572/235963915-40e1020a-cc07-4563-a643-66543f058a09.png">


#### Second part: Sankey Diagram

We have a Sankey diagram, which provides a wider and more general visual representation of the dataset and gives insight into the revenue model and success of different categories. The Sankey diagram will contain all or a subset of the following information: categories, free/paid, with/without ads, with/without in-app purchases, number of downloads and reviews, stars, content rating. We will experiment to find the optimal order of such informations to better convey the message of different revenue models related to different categories, popularity level and so on.  

A slider will allow users to switch between Apple and Android markets. In addition, it will allow users to switch to "Editor's choice", allowing the Sankey DIagram to show only the apps that were selected to be part of this special category on Google Play Store. This Sankey diagram could be slightly different, containing the following information: categories, free/paid, with/without ads, with/without in-app purchases, top 10/100/1000 number of downloads and reviews, stars, content rating.


<img width="803" alt="image" src="https://user-images.githubusercontent.com/62103572/235966770-5d6852ed-0713-4b78-8377-b9ee28c81fff.png">


#### Third part: Streamgraph

Users can view a time evolution plot, which shows the change of the top 5 most present categories in time with a Streamgraph. Users can switch from category to content rating with a slider. As previosuly, another slider will allow users to switch from "Android" to "Apple" or "Editor's choice". On the side, there are several famous apps and hovering/clicking on them show when they were launched in the timeline.

**Extra ideas**: 
- We will display the logo of most famous apps directly on the streamgraph timeline, as shown in the sketch below.
- Extract application’s logo with API and show logos together with apps' names.

<img width="873" alt="image" src="https://user-images.githubusercontent.com/62103572/236196714-a8be2f7a-2049-4904-a955-6d1a554a3067.png">

#### Fourth part: Treemap

Users can choose among different categories using the Android/Apple slider. There is a treemap of all the categories (the size of the category will be proportional to the number of downloads of apps in that category), and when users click on one of them, they  get extra information about it: the top 10 apps of that category will be displayed with their number of downloads. There is also a button to choose between free or paid apps, and users can view the proportion within each rectangle.

There will be a Donut chart with the 10 most common words in that category's apps. The aim of this is to understand "trends" in that category, for example in "Tools" we migth find that "Calculator" is the most common word and therefore app.

Finally, there is also a stacked bar plot that shows free/paid apps and those with ads or not, with in-app purchases or not, of all apps of the category, or only the top 1000, 100, or 10.

**Extra ideas**:
- Instead of showing the top 10 apps of that category as a list, clicking on a category on the treemap will turn the treemap in a circular packing chart of 10/100/1000 (can be chosen with a button) most downloaded apps. Hovering one of them will show specific information about that app as shown in the image below (top right).
- Extract application’s logo with API and show logos together with apps' names.
- Smoother transitions\animations when interacting with the visualizations and using sliders to change the content of plots.
- A 2D correlation density plot of reviews rating and install number, as in the image below. If users click a category, it goes from general data to that category's data. 

<img width="712" alt="image" src="https://user-images.githubusercontent.com/62103572/236201533-57f1e961-ebc6-45f4-abed-0ea4bbf059e6.png">


## 🛠 Skills

- Python for data processingm. Pandas library for loading dataset. 
Scikit-learn library  for more complex statistic to be done on the data.
- HTML, CSS and JavaScript for the  website skeleton and behaviour.
- D3.js for visualizations.
- Lecture 1,2,3: basics of HTML, CSS, and JavaScript
- Lecture 4: Presentation of D3.js and some basic use case.
- Lecture 5: Interactivity for our charts.
- Lecture 7: Used the advices on dos and donts of data visualizations for the design of our website and choice of the visualizations.
- Lecture 9: Chose a donut chart instead of a word cloud for most common words due to the cons of word clouds explained in this lesson.
- Lecture 10: Treemap.
- Lecture 11.1: Stacked area chart, Sankey diagram.
- Lecture 12.1: About how to display a chart to be more appealing and telling for the information we want to show, what kind of fonts to choose.

## 🔗 Links

[![My portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://eliafantini.github.io/Portfolio/)
[![My linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/-elia-fantini/)


