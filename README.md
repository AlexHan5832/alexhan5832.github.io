# MIAS Group Official Webpage

Welcome to the source code for the website of the MIAS Group. 

Technologies this website uses:  

    Jekyll
    GitHub Pages
    jQuery

## Steps to install a local copy of this website (e.g. for testing):

* Clone a copy of this repo.

* cd into the repo.

* Install Jekyll:

```
sudo apt install ruby-full
sudo gem install bundler jekyll
```
* Start an instance of the website (change or increment the port number if needed):
```
jekyll serve --port 4000 --watch --baseurl=""
```
* Go to this address in a browser (change or increment the port number if needed):

    localhost:4000

* When you are finished, you should kill the process with ctrl + c.

## Update the webpage:

To update this webpage, simply navigate to `_data` and edit the .yml files.