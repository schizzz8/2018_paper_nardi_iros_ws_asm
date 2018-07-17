This is a template paper in IEEE style (ICRA, IROS, RSS, RA-Letter, etc.), start from this repository if you want to write a new paper.


NOTES ON PAPER WRITING
===

* Rename the paper.tex file into your paper name. Use the bibtex key policy (see below)
* Use a Spell Checker with US English as spelling language
* Use Academic Writing Check: https://github.com/devd/Academic-Writing-Check
* Use GIT for version control. Use our gitlab sever, fork from this repos.
* Make sure your Makefile is working correctly and compiles the documents 
* All images go to the subfolder pics
* Make sure the source files for images are in the pics folder as well (unless they are huge)
* Place the reviews as txt files in the folder reviews.

NOTES ON BIB ENTRIES
====

Bibtex Key Policy
--
* All in lower case
* Use the key structure: <lastnamefirstauthor><2 digit year><conference/journal><extra>
* Use <extra>:
  * for workshops: -ws,
  * for multiple papers: -a, -b, -c, ... ordered by title in alphabetical order
  * additionally add -a, -b, -c, ... ordered by title in alphabetical order in case of multiple workshops
* Examples: stachniss08icra, stachniss08icra-ws, stachniss08icra-a, stachniss08icra-b
* Use the bibtex key also at the filename for the paper, e.g., stachniss08icra.pdf

Bibtex Entries
--

* Use strings for conferences and journal name in order to keep obtain consistent entries
* Use the identical abbreviations for conference name, e.g., “Proc. of the IEEE Int. Conf. on Robotics and Automation (ICRA)”
* Avoid adding location in addition to the city or street of the conference.
* Use doi for the official document on the publisher webpage. 
* Abbreviate the first name of the authors, e.g., C. Stachniss instead of Cyrill Stachniss
* In case of a first name and a middel name, use no space between them, e.g., C.J. Stachniss


# 2018_paper_nardi_iros_ws_asm
