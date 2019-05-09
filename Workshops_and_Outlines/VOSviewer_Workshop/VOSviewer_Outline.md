# Learning VOSviewer, a quick introduction

## Background
"VOSviewer is a software tool for constructing and visualizing bibliometric networks. These networks may for instance include journals, researchers, or individual publications, and they can be constructed based on citation, bibliographic coupling, co-citation, or co-authorship relations. VOSviewer also offers text mining functionality that can be used to construct and visualize co-occurrence networks of important terms extracted from a body of scientific literature." - http://www.vosviewer.com/

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
8. This next screen allows you to choose the number of authors you would like to select for your dataset. We will leave this at 65. Select Next.
9. This final screen will allow you to individually select authors. Since we chose 65, all 65 authors will appear on this screen. You are able to check and uncheck the boxes next to the authors to specifically select certain authors to be accounted for. It also shows how many documents each author is associated with as well as the calculated "link strength." We will leave all authors selected for this exercise. Select Finish to finish uploading the dataset.
10. A pop-up will appear letting you know that not all data in this dataset connects to one another. The pop-up is offering to just select the largest cluster. For this example, we will select No. We want to see the entire collection.

## Navigating the Workspace: Understanding the Graphs
Three types of graphs display with this dataset and can be changed using the tabs at the top of the screen. The first is a "standard" network graph. The authors who have worked together on different papers are shown in clusters. You can zoom and move the viewer around using the arrows as well as the plus and minus buttons on the top righthand corner of the screen. Using the scroll and zoom settings, navigate to the larger cluster on the left that says "abrams j". If you hover your mouse over a name, the specific co-author relationships are highlighted. </br>
</br>
The second type of graph, the Overlay, shows the authors clustered in a similar fashion. What is different here, however, are the colors of the clusters. As you can see, the colors vary from yellow to blue. This is important because, if you look at the bottom righthand corner of the display screen, you will see a timeline sporting the same color range. Therefore, the clusters within this graph are color-coded based on the year of the referenced papers' pulications. </br>
</br>
The third type of graph, Density, shows the clusters once again, however the lines connecting these clusters has now vanished. Instead, the clusters are indicated by names of various sizes as well as a color range. Denser clusters (ones containing more authors) are larger spots and the authors with more connections appear in larger font sizes. </br>
</br>
**Activity:** Write down some positives and negatives of using each of these three types of graphs. What graph do you think best displays this data? Why?

## Navigating the Workspace: Understanding/Manipulating the Controls
At the very bottom of the screen, some basic information is displayed about your graph. Here, it confirms how many total items were selected, how many clusters were created from these items, how many total links exist between items, and the calculated total strength of the links.

### Visualization Customization
The very right side of the screen contains ways to customize your visualization output. That customization bar changes depending on whether you have selected Network, Overlay, or Density Visualization at the top of the middle segment. Let's experiment with the customization settings for an Overlay Visualization.

Going from top to bottom:
* Scale - Impacts the size of the graph on the screen.
* Weights - Impact how the clusters are individually sized. For example, selected Links will enlargen the clusters with a greater number of links.
* Size variation - Impacts the size of the nodes on the screen.
* Circles and frames - Impacts the shape of the nodes.
* Max length - Details how many letters can be contained within a label on a node.
* Min strength and Max lin - Allows you to customize which lines you see. To only see lines in clusters with 3 or more connections, you can adjust the min strength.
* Overlay colors - Allows you to adjust the colors that make up the graph

### Analysis
The very left size of the screen, where we initially created this project, also contains two other tabs: items and analysis. Items gives a list of every cluster in the graph as well as the authors contains. By double-clicking a specific author, the center screen will readjust to view that specific cluster. </br>
</br>
In the analysis tab, there are further ways of altering your data and visualization output. There are ways to normalize your data as well as ways to alter your layout. Leave the normalization method as is, but let's un-select the "use default values" box under layout. Let's change the attraction variable from 2 to 8. Whenever you alter anything under normalization or layout, you must then select update layout to see changes in your graph. Clustering operates in a similar fashion, however alters how your data clusters on screen.</br>
</br>
The final section, Rotate/flip, operates as it says, and will rotate or flip your visualization based on your desired inputs.

### Saving your Work
There are two ways to save your work. The first would be to take a screenshot. On the lefthand side of the application, under the file tab, there is an option that says screenshot. Here, you are able to save your image as a variety of different image formats.</br>
</br>
The other way of saving your work would be to go to Save (just above screenshot). Try saving this document as "VOSviewer map file" as a CSV. Save this somewhere you will be able to find it. If you open your file directory and open that CSV file, you will see various information as well as analytics have been stored. This includes not just the node "labels," your authors," but also which cluster they are grouped in as well as the x and y coordinates that node existed in within the VOSviewer program. Should you wish to re-open this project, you would be able to import this map file and your created visualization will reappear.

## Practice with CSV Files
Make sure the CSV file (Zika_authors.csv) is downloaded somewhere easily accessible on your machine. For this dataset, we will just be creating a standard map. Experiment with the different import settings. Once imported, experiment with the different visualization options and controls.

## Wrap up Questions
* What worked well for you? 
* What did not? 
* What do you like about using VOSviewer?
* What do you not like?
