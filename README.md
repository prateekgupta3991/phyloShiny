phyloShiny
==========

This is a web2py application developed by Team Shiny (Meg Pirrung, Christian Zmasek, Chris Baron, Holly Bik and Arlin Stoltzfus) at the 1st phylotastic hackathon (June, 2012, NESCent), and improved subsequently by Greg Jordan.

The main code repository is https://github.com/phylotastic/phyloShiny .

The main thing that phyloShiny does is to implement "Reconcili-o-tastic", a proof-of-concept application for integrating phylotastic tree-querying into a system for reconciling gene trees and species trees.

The repo is called "phyloShiny" rather than "reconciliotastic" because it was conceived originally as having a broader scope.

Creating a local installation is relatively easy. First install web2py. Then checkout the phyloShiny repository. Then run the commands

git submodule init

git submodule update

in the phyloShiny folder. This will install the dependency BioPython. Put phyloShiny folder in web2py/applications. Make an alias (to phyloShiny) called "shiny". The demo will be running at http://127.0.0.1:8000/shiny/reconciliotastic/index . 
