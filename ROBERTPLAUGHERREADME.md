README FOR FORKED PROJECT FROM anwala.github.io BY ROBERT PLAUGHER
#####################################################################
ANSWERS WILL BE UPLOADED AS A .PDF FILE WITH SUPPLEMENTARY COMMENTARY DONE IN THIS DOCUMENT

QUESTION 1: ISSUED THE COMMAND curl -X POST -F 'fname=robert' -F 'lname=plaugher' www.cs.odu.edu/~anwala/files/temp/namesEcho.php -v www.cs.odu.edu/~anwala/files/temp/namesEcho.php
QUESTION 2: DOWNLOADED AND INSTALL PYTHON 2.7.X WITH BEAUTIFULSOUP AND 

QUESTION 3: 
For this question I tried to imagine the nature of links and how they typically work on the Internet. Nodes with many links are usually popular websites
whereas nodes with few links are less popular. Assuming that logic, I have put the letters in the groups that I feel would best catagorize them based on
the number of links they send/recieve.

Can reach the SCC but not be reached by them. (I drew each node as a state and connected them via arrows like we had to do in Theorhetical Comp. Sci.)
IN: M, O, P, I, L, N

For Strongly Connected Components I used letters that had 2 or more links associated that were being pointed to. My logic is as follows: if you have a bunch of links leading to one specific website
then that website it obviously a hub for links (like Wikipedia or CNN for instance where many websites link to them). I understand that SCC are usually small in comparison to other items but feel like 
arguments could be made for many of these.
SCC: A, C, D, G, H

Can be reached by the SCC but not reach them. Although H is in SCC I felt like since there isn't much being linked to G except C and P that it could be 
other an OUT or SCC depending. I'd need more nodes to be able to tell for certain.
OUT: B, H

Pages that cannot reach the SCC nor be reached from the SCC. Depending on whether or not H could be considered a SCC, I put 'I' in here.
TENDRILS: I, K

Links an IN to an OUT bypassing a SCC. The only tube I could really see is a tube from I to H again operating under the assumption H could
be either a SCC or an IN.
TUBE: I, H

E and F were the only two nodes that had no links (aside from e-->f) and thus are isolated from any of the other nodes.
DISCONNECTED: E, F
