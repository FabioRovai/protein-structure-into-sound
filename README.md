# Protein Structure into Sound <img src="https://media.giphy.com/media/wLsePI5c7koHGj699C/giphy.gif" width="60" height="60"/>

<a href="https://colab.research.google.com/drive/1GC9Fpg1bvaHyKphn1A858xKnQE9NCqN7?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Notebook in collaboration with Ford Combs


This is a tutorial/implementation of a novel technique to transform protein sequences into sounds. 


This implementation aims to be a useful tool to attribute sounds quality to every specific protein ID. Here is the code that uses geometrical transformations to generates sinusoid IDs


<h1>Step 1:</h1> Download a list of PDB files from the Dunbrack lab


<h1>Step 2:</h1> Choose your PDB file directly from RCSB PDB


<h1>Step 3:</h1> Calculate Convex hull, Max Width or farthest distance from the centre


<h1>Step 4:</h1> Calculate Volume of Convex Hull, Farthest Distance using Rotating Calipers and Calculate the number of positive and negative points on each axis


<h1>Step 5:</h1> Add characteristics to a Combinational Wave


<h1>Step 6:</h1> Try our further work section to prove software scalability
