# Protein Structure into Sound <img src="https://media.giphy.com/media/wLsePI5c7koHGj699C/giphy.gif" width="60" height="60"/>

(if !wget link is broken please use this instead https://raw.githubusercontent.com/FabioRovai/protein-structure-into-sound/main/PDB.txt)

<a href="https://colab.research.google.com/drive/1GC9Fpg1bvaHyKphn1A858xKnQE9NCqN7?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Notebook in collaboration with Ford Combs


This is a tutorial/implementation of a novel technique to transform protein sequences into sounds. 


This implementation aims to be a useful tool to attribute sounds quality to every specific protein ID. Here is the code that uses geometrical transformations to generates sinusoid IDs


<h1>Step 1:</h1> Download a list of PDB files from the Dunbrack lab

Example format : 

| IDs           | length        | Exptl.        | resolution    | R-factor      | FreeRvalue    |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 3NIRA         | 46            | XRAY          | 0.48          | 0.13          | 1.00          |




<h1>Step 2:</h1> Choose your PDB file directly from RCSB PDB


<h1>Step 3:</h1> Calculate Convex hull, Max Width or Farthest Distance from the centre


<h1>Step 4:</h1> Calculate Volume of Convex Hull, Farthest Distance using Rotating Calipers and Calculate the number of positive and negative points on each axis


<h1>Step 5:</h1> Add characteristics to a Combinational Wave


<h1>Step 6:</h1> Try our further work section to prove software scalability


<h1>Audio Links</h1>

<h2>1QOWB</h2>

Geometric: https://soundcloud.com/fabio-rovai/1qowbgeometric/s-bBWgCSxMDht

Twelfth Root: https://soundcloud.com/fabio-rovai/1qowb-12/s-OZr18gDybEy

Highest Frequency: https://soundcloud.com/fabio-rovai/1qowb-high/s-pdkaoL69HYw

<h2>3CALD</h2>

Geometric: https://soundcloud.com/fabio-rovai/3caldgometric/s-7vljmSNDAeU

Twelfth Root: https://soundcloud.com/fabio-rovai/3cald-12/s-W7BZOrD4J1t

Highest Frequency: https://soundcloud.com/fabio-rovai/3caldhigh/s-gdanARqXvZE

<h2>5NW3A</h2>

Geometric: https://soundcloud.com/fabio-rovai/5nw3a-geo/s-iaIr4O1UcDw

Twelfth Root: https://soundcloud.com/fabio-rovai/5nw3a-12/s-148d19VCjZs

Highest Frequency: https://soundcloud.com/fabio-rovai/5nw3a-high/s-U6cYMqdvpdo

<h2>6SBAB</h2>

Geometric: https://soundcloud.com/fabio-rovai/6sbabgeo/s-IHrzG8bDMCt

Twelfth Root: https://soundcloud.com/fabio-rovai/6sbab-12/s-vyA9keH31Jr

Highest Frequency: https://soundcloud.com/fabio-rovai/6sbabhigh/s-42egzQBzIQ0 

<h2>6S2MA</h2>

Geometric: https://soundcloud.com/fabio-rovai/6s2ma-geo/s-sA6L78R2cCP

Twelfth Root: https://soundcloud.com/fabio-rovai/twelve-tone-comb-wave/s-VOYeCrQQmYH

Highest Frequency: https://soundcloud.com/fabio-rovai/6s2mahigh/s-eejsK0SHG9A 

<h2>3X2MA</h2>

Geometric: https://soundcloud.com/fabio-rovai/3x2ma-geo/s-jzSefJPldVh

Twelfth Root: https://soundcloud.com/fabio-rovai/twelve-tone-comb-wave-1/s-AOd5l0SBaCc

Highest Frequency: https://soundcloud.com/fabio-rovai/3x2mahigh/s-ZQq8irD6QEg
