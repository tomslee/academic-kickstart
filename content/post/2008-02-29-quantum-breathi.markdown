---
author: Tom Slee
comments: true
date: 2008-02-29 16:23:36+00:00
excerpt: "\n\t\t\t\t\t\t"
layout: post
link: http://tomslee.net/2008/02/quantum-breathi.html
slug: quantum-breathi
title: "\n\t\t\t\tQuantum Breathing\t\t"
wordpress_id: 189
---


				

Chris next door works at the [Perimeter Institute](http://www.perimeterinstitute.ca/); he is a physicist in the field of quantum information and I've been trying to read some of his papers. Interesting, if a bit beyond an ex-chemist. But reading quantum things again reminded me of The Best Quantum Thing I Ever Learned, which - outside chemists - seems little known. So I'll tell the story here as briefly as I can - Wikipedia now has a good set of entries on this if you want to know more, including fancy moving pictures: start at [haemoglobin](http://en.wikipedia.org/wiki/Hemoglobin). All the images here are borrowed from Wikipedia.

* * *

Breathe in.




What's going on? You draw oxygen into your lungs; from there it passes to the bloodstream; from there to muscles and nerves. To make that journey oxygen molecules (O2) stick to molecules of haemoglobin in red blood cells, which carry them until they get to a place where they are needed, at which point the oxygen molecules hop off the haemoglobin to do their work. 




More precisely, an oxygen molecule sticks to an iron atom at the centre of one of four "haem" or "heme" groups that are part of each haemoglobin molecule. Here is a picture of a haem group with its iron atom (Fe) surrounded by four nitrogen atoms. There is actually a fifth Nitrogen atom at right angles to the diagram ("behind" the Fe), that is in turn attached to the long "globin" chain.




![](http://docs.google.com/File?id=dfx7r5rf_108c2xffqct)  
If haemoglobin was just a passive lump onto which oxygen molecules stick then breathing would not work. The first oxygen molecule to bump into a haemoglobin can attach to one of four iron atoms, and so would tend attach more frequently than the second (which has only three spots to attach to), which would attach more frequently than the third and the fourth. So unless oxygen was present in great excess, there would be empty seats left on each haemoglobin as it stops by the lungs to collect its passengers. In the same way, when the oxygen molecules step off from the haemoglobin at the end of the line, the last one would have the least tendency to leave - haemoglobins may have some passengers returning for a round trip. We would have to breathe much harder than we do to get the oxygen to our muscles.




But, as Max Perutz found out a few decades ago, haemoglobin is much more than a passive lump. 




When haemoglobin is empty of oxygen, the haem groups - each of which is attached to one of the four "globin" strands that wrap themselves up to form the blob-shaped haemoglobin molecule - are near to the surface of the blob but are not openly exposed. When the first oxygen molecule attaches, it triggers a slight change in the local structure of the haem group, and this in turn tugs on the globin so that the other haem sites are exposed, and more easily attract oxygen molecules. It's this opening up as oxygen attaches that is the root of haemoglobin's efficiency, and the switch that triggers it is a quantum one.




Before the oxygen attaches, the iron sits slightly out of the plane of the four nitrogen atoms. But when the oxygen attaches, the iron atom moves into the plane of the ring. This slight movement is the switch, triggering the rearrangement of the globin chain and the exposing of the other haem binding sites. Here is a sideways view, in elaborate ASCII text graphics, of the iron moving into the haem plane.



    
              N<br></br>          |                               N<br></br>         Fe                               |<br></br>N-----N======N-------N           N-----N==Fe==N-----N<br></br>                                          |                                                                                 |<br></br>                                          O





What happens to the iron atom to shift it into the plane? To understand that you have to know a bit about how the electrons around the iron atom are arranged.





Electrons are arranged in shells of course, and each shell holds different numbers of electrons. The innermost shell holds two electrons, the second holds eight, and the third shell can hold 18 electrons. Iron has 14 electrons in the third shell and two electrons in the fourth shell. In haemoglobin, the iron exists as Fe2+, with the two electrons in the 4s orbital removed. We can focus on the 14 electrons in the 3 shell to understand the switch.




The 3 shell has a single orbital with zero angular momentum (3s) that, like any orbital, can hold two electrons (one "spin up", one "spin down"). It has three 3p orbitals (6 electrons) with an angular momentum of one and a slightly higher energy. And it has five 3d orbitals with an angular momentum of two and a slightly higher energy still. There are 6 electrons spread among the 3d orbitals (leaving four unoccupied spaces) and these d electrons are the key to the switch.




When six electrons occupy the five 3d orbitals they avoid pairing up if at all possible, and they have spins "pointing" the same way (Hund's Rule: a consequence of the Pauli Exclusion Principle). By occupying separate orbitals, which generally occupy different regions of space, they keep out of each others' way and this lets the negatively-charged get a little closer to the positively-charged nucleus (become more tightly bound) without repelling each other. So the 3d energy levels of an iron atom are like this (the vertical lines are electrons, the horizontal line shows an empty slot where an electron could fit). 



    
        ^<br></br>E   |        ||  |-  |-  |-  |- <br></br>    |




(The unpaired electrons here, all lined up with spins "pointing" the same way, are the reason that iron is magnetic.)




This labelling of orbitals as 3s, 3p, 3d, 4s and so on is precise only for isolated atoms. But place an iron in a cage and not all the 3d orbitals are at the same energy: there is a "ligand field" effect that raises the energy of some orbitals more than others. The Nitrogen atoms have a partial negative charge, and (like charges repel) electrons in orbitals that are located largely close to these atoms rise in energy. Those that are mainly distributed away from the Nitrogen atoms will be lower in energy.




The shape of the cage determines the change in energy levels (as well as a mixing among them which we can put to one side). Here is an iron atom in a square cage. The five 3d orbitals (in a line on the left of the diagram) have split into distinct levels on the right, with different energies. To untangle the configurations of orbitals in different environments you need to apply group theory ideas to quantum mechanics.




![](http://docs.google.com/File?id=dfx7r5rf_111dm3ftbcv)




If the split between the energy levels is small then Hund's Rule still applies and the electrons will tend to occupy orbitals singly, with spins aligned: this is called the "high-spin" case. If the split is bigger then the electrons pair up in the lower-energy orbitals: the "low-spin" case. In the haem group the iron is high-spin. But as the oxygen atom binds to it, bringing another negative charge close to the iron, the pattern changes and (crucially) the magnitude of the splitting among the energy levels increases, and the iron changes to being a low-spin case. And, to cut the story slightly short, this switch to a low-spin Fe2+ ion causes the iron to fit into the plane of the haem group instead of protruding from it, and it drags the fifth nitrogen atom and the globin chain along with it.




So breathing, in the end, works only because of a fine balance between magnetism and electron level splittings in iron atoms; it works because quantum mechanics says that electrons occupy discrete energy levels and because we can calculate the order and energy of those levels. What I like is that (unlike most popular quantum topics, which focus on weirdness) this phenomenon that lies behind every breath is no longer a mystery - it's a triumph of understanding and brings the most abstract topics, group theory and quantum mechanics, down to earth.


		
