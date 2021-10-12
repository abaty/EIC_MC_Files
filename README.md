Install PYTHIA 8.306 with the ROOT6 and Fastjet3 libraries.  First install and build ROOT and fastjet, then build pythia and follow  the instructions on how to link the other libraries in the pythia README.  It involves commands when running the PYTHIA configuration script.

Go to the 'examples' folder of PYTHIA and copy in the EIC.cc and Make macro from this repo.

run 'make EIC' and make sure there are no build errors.  I have no errors when using g++ on iOS.

run the EIC executable with './EIC'

An output EIC.root should be created.  Changes to the code can be made in the EIC.cc file.
