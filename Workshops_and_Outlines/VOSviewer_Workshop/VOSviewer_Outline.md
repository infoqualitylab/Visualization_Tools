# Learning VOSviewer, a quick introduction

## Background
VOSviewer is a software tool for constructing and visualizing bibliometric networks. These networks may for instance include journals, researchers, or individual publications, and they can be constructed based on citation, bibliographic coupling, co-citation, or co-authorship relations. VOSviewer also offers text mining functionality that can be used to construct and visualize co-occurrence networks of important terms extracted from a body of scientific literature.

## Installation
**Note:** You MUST have a version of Java installed on your computer to run this program. If you need to download Java, it can be installed by opening the following link: https://www.java.com/en/download/</br>
</br>
**Download and Run**
1. Open the following website in your browser: http://www.vosviewer.com/download
2. Select the download best suited for your system
3. Unpack the zip file
4. Open the application
</br>

**Web Run**
1. Open the following website in your browser: http://www.vosviewer.com/download
2. Go to the "Web Start" tab
3. Select Launch
4. A new tab will open. Follow prompts.
5. Application will open within a few minutes

## Definitions 
* Network graph - This type of visualization specifically demonstrates the relationships between different objects. It is comprised of nodes and edges.</br>
* Edges - The line that connects two objects.</br>
* Nodes - The objects being linked.</br>
* Citation map - A way of visualizing the relationship between one paper and another.</br>
* Research Information Systems (file extension) - A bibliographic citation file. This file can be produced by software such as Zotero.</br>
* Co-author analysis - The relationship between authors in a paper.</br>

## Importing the Dataset
1. Open VOSviewer - The main screen is split into 3 columns. The left column allows for the opening of a file or the creation of a project, as well as some potential analysis (we will come back to this later). The middle column, the largest of the three, is where the visualization will be produced. The right column contains ways in which to customize the visualization itself (we will come back to this later.
2. In the left column, select Create. A pop-up will appear. 
3. We are going to be creating a map based on bibliographic data. Select Next.
4. We will be reading in data from a reference manager file (our RIS file). Select Next.
5. Under the RIS tab, select the three dots on the right to open your File Explorer. Find the file citation_dataset.ris on your machine. Select OK and then Next.
6. This next page allows you to inform the program about your dataset. For the purposes of this example, we are employing a co-authorship analysis. We will also be utilzing "full counting" and not fractional. For documents with many authors, you can instruct the program to ignore any document that contains more than a specified number of authors. In this case, let's adjust the maximum number of authors per document to 6. Then select Next.
7. This next page involves choosing the "threshold," or where we want a document to cut off. If you lower the minimum number of documents of an author from 2 to 1, you will see the number of authors that meet the threshold rise from 5 to 65. Make sure that the threshold is set to 1 so that our entire dataset is selected. Select Next.
8. 
9. 

## Navigating the Workspace: Understanding the Graphs
Three types of graphs display with this dataset and can be changed using the tabs at the top of the screen. The first is a "standard" network graph. The authors who have worked together on different papers are shown in clusters. You can zoom and move the viewer around using the arrows as well as the plus and minus buttons on the top righthand corner of the screen. [select a cluster to inspect] If you hover your mouse over a name, the specific co-author relationships are highlighted. </br>
</br>
The second type of graph, the Overlay, shows the authors clustered in a similar fashion. What is different here, however, are the colors of the clusters. As you can see, the colors vary from yellow to blue. This is important because, if you look at the bottom righthand corner of the display screen, you will see a timeline sporting the same color range. Therefore, the clusters within this graph are color-coded based on the year of the referenced papers' pulications. </br>
</br>
The third type of graph, Density, shows the clusters once again, however the lines connecting these clusters has now vanished. Instead, the clusters are indicated by names of various sizes as well as a color range. Denser clusters (ones containing more authors) are larger spots and the authors with more connections appear in larger font sizes. </br>
</br>
**Brief activity:** Write down some positives and negatives of using each of these three types of graphs. What graph do you think best displays this data? Why?

## Navigating the Workspace: Understanding/Manipulating the Controls

### Saving your Work

## Practice with CSV Files
Make sure the CSV file (Zika_authors.csv) is downloaded somewhere easily accessible on your machine. For this dataset, we will just be creating a standard map. Experiment with the different import settings. Once imported, experiment with the different visualization options and controls. </br>
</br>

## Wrap up Questions
* What worked for you? 
* What did not? 
* What do you like about using VOSviewer?
* What do you not like?
