# Protein Structure into Sound <img src="https://media.giphy.com/media/wLsePI5c7koHGj699C/giphy.gif" width="60" height="60"/>

<a href="https://colab.research.google.com/drive/1GC9Fpg1bvaHyKphn1A858xKnQE9NCqN7?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Protein Structure into Sound (PSS)
Notebook in collaboration with Ford Combs



This is a tutorial/implementation of of a novel technique to transform protein sequence into sounds. This implementation aims to be an useful tool to attribuite sounds quality to every specific protein ID. Here is the code that uses geometrical transformaions to generates this sinusoid IDs.

Step 1: Download a list of PDB files from the dunbrack lab.

Step 2: Choose your PDB file directly from RCSB PDB

Step 3: Calculate Convex hull, Max Width or farthest distance from the center

Step 4: Calculate Volume of Convex Hull, Farthest Distance using Rotating Calipers and Calculate number of positive and negative points on each axis.

Step 5: Add characteristics to a Combinational Wave

Step 6: Try our further work section to proof software scalability
