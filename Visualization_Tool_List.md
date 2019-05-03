# List of Visualization Tools

## Cytoscape
**Ranking:** 2 <br/>
<br/>
**Background:** https://cytoscape.org/ --> "Although Cytoscape was originally designed for biological research, now it is a general platform for complex network analysis and visualization."<br/>
<br/>
**Paywall?:** No. <br/>
<br/>
**Data types (import):** .csv, .xlsx, SIF (Simple Interaction Format), GML, XGMML, BioPAX, PSI-MI, GraphML, KGML (KEGG XML), SBML, OBO, and Gene Association.<br/>
<br/>
**Data types (export):** .cys (Cytoscape Session files including networks, attributes, properties, etc.), as well as PDF, PS, SVG, PNG, JPEG, and BMP files. Using additional applications, it is possible to export networks as JSON files.<br/>
<br/>
**Types of visualizations:** Network graphs.<br/>
<br/>
**Special/Unique features:** According to their website, "Most of the features in Cytoscape supports languages other than English, including Eastern Asian languages using two-byte characters."<br/>
<br/>
**Analysis:** This is a powerful tool that can be used both by beginners as well as more experienced users. Loading the data itself, particularly if the structure is domain specific, does take a few minutes to figure out. While it is not necessary to understand complex elements of network analysis, being familiar with some terminology makes using this tool easier. There is quite a bit of documentation and a rather extensive online community, so troubleshooting any issues is not terribly complex. There are many ways to customize the visualized output, including shape and color. There are also analysis options, where Cytoscape can automatically analyze the user's data, allowing more complex visualizations.<br/>
<br/>

## Gephi
**Ranking:** 3<br/>
<br/>
**Background:** https://gephi.org/ --> "Gephi is a tool for data analysts and scientists keen to explore and understand graphs. Like Photoshop™ but for graph data, the user interacts with the representation, manipulate the structures, shapes and colors to reveal hidden patterns. The goal is to help data analysts to make hypothesis, intuitively discover patterns, isolate structure singularities or faults during data sourcing."<br/>
<br/>
**Paywall?:** No. <br/>
<br/>
**Data types (import):** GEXF, GDF, GML, GraphML, Pajek NET, GraphViz DOT, CSV, UCINET DL, Tulip TPL, Netdraw VNA, Excel workbook<br/>
<br/>
**Data types (export):** <br/>
<br/>
**Types of visualizations:** Networks.<br/>
<br/>
**Special/Unique features:** <br/>
<br/>
**Analysis:** <br/>
<br/>

## Graphviz
**Ranking:** 4?<br/>
<br/>
**Background:** https://www.graphviz.org/ --> "Graph visualization is a way of representing structural information as diagrams of abstract graphs and networks. Automatic graph drawing has many important applications in software engineering, database and web design, networking, and in visual interfaces for many other domains."<br/>
<br/>
**Paywall?:** No.<br/>
<br/>
**Data types (import):** <br/>
<br/>
**Data types (export):** <br/>
<br/>
**Types of visualizations:** <br/>
<br/>
**Special/Unique features:** <br/>
<br/>
**Analysis:** <br/>
<br/>

## LodLive
**Ranking:** 3 <br/>
<br/>
**Background:** http://en.lodlive.it/ --> LodLive runs in a broswer. "LodLive is an experimental project that was set-up to spread and promote the linked-open-data philosophy and to create a tool that can be used for connecting RDF browser capabilities with the effectiveness of data graph representation. LodLive is the first navigator to use RDF resources based solely on SPARQL endpoints." This tool appears to still be in the early stages, as much is labeled as "Coming Soon."<br/>
<br/>
**Paywall?:** No <br/>
<br/>
**Data types (import):** Because LodLive works in the browser and directly with SPARQL endpoints, most data being "imported" comes from a URI. Within the Simple Search element, the user is able to browse keywords from either DBpedia or Freebase. Once a keyword is chosen, the beginnings of a graph will appear. <br/>
<br/>
**Data types (export):** Unknown or non-existent. <br/>
<br/>
**Types of visualizations:** Linked data relationships. <br/>
<br/>
**Special/Unique features:** While it is still "Coming Soon," hopefully in the near future users will be able to insert their own RDF data for analysis. Additionally, in the graphical interface, when selecting a resource, it is possible to view additional information. For example, this author investigated DBpedia's "Zika virus" keyword in the "Simple Search" feature. When selecting the icon that appears like a small document, information from the DBpedia page on the Zika virus appear, including images and a description. Should this feature be included once users can upload their own RDF, users would be able to provide their own labels. The graphical interface also connects to Google maps, however this is currently still just for development purposes. <br/>
<br/>
**Analysis:** Because this tool is rooted in linked data and SPARQL, prior knowledge of these topics can assist with navigating the space. Understanding the linked data nature of the generated data as well as the terms utilized assists with understanding the querying and the output. Additionally, there is a bit of a learning curve in navigating the tool, as many symbols are utilized to stand in for specific concepts (i.e. inverse relations, direct relations, groups of direct relations, etc.). It is also important to note that this tool is good for exploring data and subsequent linked data relationships but would not be suitable for an easily accessible, public-facing visualization. This is a new tool, still actively being developed, meaning that elements of the tool, as well as any available documentation, is in flux and can alter at any time. <br/>
<br/>

## Payola
**Ranking:** 5<br/>
<br/>
**Background:** https://github.com/payola/Payola --> "Payola is an HTML5 web application which lets you work with graph data in a completely new way. You can visualize Linked Data using several preinstalled plugins as graphs, tables, etc. This also means, that you no longer need Pubby to browse through a Linked Data storage (via its SPARQL endpoint). Moreover, you can create an analysis and run it against a set of SPARQL endpoints without deep knowledge of SPARQL language itself. Analysis results are processed and visualized using the embedded visualization plugins." <br/>
<br/>
**Paywall?:** No.<br/>
<br/>
**Data types (import):** Because Payola works in the browser and directly with SPARQL endpoints, most data being "imported" comes from a URI. The author was unable to determine if other data imports were possible, such as .csv, .txt, or even RDF.<br/>
<br/>
**Data types (export):** .png. Based on available documentation, the author was unable to determine if other data exports were possible.<br/>
<br/>
**Types of visualizations:** Payola comes with several visualization plug-ins. Examples of potential visualizations include circle, gravity, or even tree visualizations. Can also produce various types of charts (i.e. bar, pie, etc.).<br/>
<br/>
**Special/Unique features:** Possesses many types of plug-ins so that the user would be able to further customize and analyze their data and output.<br/>
<br/>
**Analysis:** This tool is particularly difficult to use. Just to install the application, a Scala environment is required on the user's machine. In addition to the server, a Squeryl-compatible relational database as well as a Virtuoso server is necessary. In addition to the initial download, configuration and compilation of the Virtuoso and H2 servers are also necessary. The initial installation also requires the use of Git and the command line. The application displays in HTML5. The author of this list was unable to complete the installation process or to actually launch this program. There are many unique visualizations that Payola claims to be able to produce, but the installation processes as well as the interface itself is exceptionally complex, particularly for newcomers.<br/>
<br/>

## RDF Studio
**Ranking:** <br/>
<br/>
**Background:** http://www.linkeddatatools.com/rdf-studio --> <br/>
<br/>
**Paywall?:** Yes. RDF Studio can be used for free for 21 days. At the end of that time, the user will be prompted to purchase a subscription or license for the product. Students or academic institutions may qualify for free or discounted rates. <br/>
<br/>
**Data types (import):** <br/>
<br/>
**Data types (export):** <br/>
<br/>
**Types of visualizations:** <br/>
<br/>
**Special/Unique features:** <br/>
<br/>
**Analysis:** <br/>
<br/>

## VOSviewer
**Ranking:** 1 <br/>
<br/>
**Background:** http://www.vosviewer.com/ --> This tool was initially built as a way to "visualize scientific landscapes." The VOSviewer GUI can be downloaded for personal use. <br/>
<br/>
**Paywall?:** No.<br/>
<br/>
**Data types (import):** .csv, .txt, reference management files (RIS, EndNote, RefWorks), database files (from Web of Science, Scopus, Dimensions, and PubMed), and select APIs.<br/>
<br/>
**Data types (export):** .csv, .txt, .eps, .gif, .jpg, .pdf, .png, .svg, .swf, .tiff. <br/>
<br/>
**Types of visualizations:** Networks (bibliographic, co-citation, co-authorship, co-occurance). Can be visualized as network, overlay, or density visualizations.<br/>
<br/>
**Special/Unique features:** This tool allows some elements of analysis to occur once data is imported. This varies from adjusting the clustering to the normalization of the data points selected.<br/>
<br/>
**Analysis:** While this tool is fairly easy to use, the customizable options are extremely limited. Unlike other network-based tools, the user is only able to employ 3 basic models for their data (network, overlay, and density) and can only manipulate certain aspects. The clusters of visualized data, as far as this author can tell, is unable to be manually moved. This tool is particularly useful for novices or for someone looking to create something quickly and easily.<br/>
<br/>

## WebVOWL
**Ranking:** 2<br/>
<br/>
**Background:** http://vowl.visualdataweb.org/webvowl.html --> "WebVOWL is a web application for the interactive visualization of ontologies. It implements the Visual Notation for OWL Ontologies (VOWL) by providing graphical depictions for elements of the Web Ontology Language (OWL) that are combined to a force-directed graph layout representing the ontology. Interaction techniques allow to explore the ontology and to customize the visualization."<br/>
<br/>
**Paywall?:** No. <br/>
<br/>
**Data types (import):** Ontology files (the author is unsure at this time which specific file extensions).<br/>
<br/>
**Data types (export):** JSON, SVG, URL, TeX (alpha), and TTL (alpha).<br/>
<br/>
**Types of visualizations:** Ontology networks.<br/>
<br/>
**Special/Unique features:** This application runs in the user's browser and does not require and software downloads or GUIs. Once specific nodes are selected, the application is able to provide certain context (i.e. a description, definition, associated elements, as well as statistics).<br/>
<br/>
**Analysis:** This application is not a typical data visualization software, as it was built specifically to visualize ontologies. This allows the user to explore the relationships within an ontology, both established as well as customized ones. Because this tool is domain-specific (ontologies), it does require some background knowledge or understanding to utilize. That being said, the interface itself is extremely simple to navigate and use.<br/>
