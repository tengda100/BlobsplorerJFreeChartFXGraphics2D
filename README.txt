Blobsplorer version 3.0 23/7/2014

GENERAL USAGE NOTES
———————————————————

- This application displays contigs based on GC content, coverage information and taxonomic annotations in the form of taxon-annotated GC-coverage plots (TAGC plots) while facilitating the filtering of contigs in the aid of creating a better assembly.

- Filtering options include taxonomic rank, taxon, minimum coverage value, maximum E-Value and contig length.
  
- The application only accepts input files that match the novel formatting found at https://github.com/blaxterlab/blobology/tree/master/dev,

-Blobsplorer allows for the creation of several export files, including: SVG files of the TAGC plot,  the coverage and GC content subplots and the legend; a new blobplot.txt containing only visible contigs; a history file of filtering steps; and two files containing included and excluded contig IDs for further processing respectively.

-Taxonomic annotations are only as good as the resource from which they were gathered. 

Installation
———————————————————
Required:
-Java 1.8
-JFreeChart 1.0.17
-JCommon 1.0.22
-Batik 1.7
-FXGraphics2d 1.0

Steps for Installation:
1)Download GitHub repository
2)Either use the build.xml script by typing ‘ant’ to build Blobsplorer 3.0 or use the precompiled version 
3)Type java -jar Blobsplorer 3.0 to run the application
Contact details

Association: IEB, University of Edinburgh
email: fridayjocelyn@gmail.com or jocelynfriday@yahoo.com

