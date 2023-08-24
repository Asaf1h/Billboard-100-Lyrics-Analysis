# **Analyzing Top 100 Billboard Song Lyrics**

## Introduction:
This project aims to derive insights into the themes and trends of the top 100 Billboard songs by analyzing their lyrics. By employing techniques such as web scraping, data processing, and visualization, the project sheds light on the lyrical landscape of popular music, bridging the gap between music and data analysis.

## **Workflow Breakdown**


### Step 1: Web Scraping Billboard Songs' Titles and Artists

Initially, the project utilizes Python libraries like requests and BeautifulSoup to extract essential information such as song titles and artists' names from the top 100 Billboard songs. This involves navigating through relevant websites to gather the necessary data for subsequent analysis.

### Step 2: Storing Song Details in SQL Database
Moving forward, the focus shifts to establishing a structured storage approach. By setting up an temperarly SQL database we minimizes redundant data retrieval, allowing more emphasis on processing new additions and analysis.

**Note:** At this stage, we're storing the Billboard 100 song details. We'll enrich the database with lyrics in the upcoming steps as we successfully retrieve them.

###Step 3: Extracting Lyrics through Web Scraping

Once the names of the songs and the names of the artists have been obtained, you can proceed to the next step. The project then employs advanced web scraping techniques to obtain song lyrics. By targeting specific websites known for hosting lyrics, it navigates their structures to extract the lyrics associated with each song. This process requires a deep understanding of the websites' data organization.

###Step 4: Text Preprocessing and Stop Word Removal
Once the lyrics are collected, the next step involves text preprocessing. This stage includes removing special characters, symbols, and unnecessary words that do not contribute significant meaning. The goal is to prepare the lyrics for more meaningful analysis.


### Step 5: Visualizing Most Frequent Words
To provide visual insights into the dominant themes, the project employs visualization libraries like matplotlib and WordCloud. This step generates graphical representations showcasing the most frequently occurring words in the lyrics, revealing prevalent topics and themes across the songs.


### **Important note: Data Usage and Ethics**

The project maintains a commitment to ethical data use procedures. This project minimizes the potential impact on external websites during web scraping and emphasizes adherence to legal and ethical standards.It is important to note that unauthorized data scraping is not approved. The information collected is used solely for private educational purposes and is not used for commercial purposes and it is deleted after use.

![הורדה (2)](https://github.com/Asaf1h/Billboard-100-Lyrics-Analysis/assets/88323673/db899202-becb-4155-ab3a-582ad6c9d3da)



https://github.com/Asaf1h/Billboard-100-Lyrics-Analysis/assets/88323673/05929ec8-07e2-4149-9bcd-fb1024d87d43



