Project for DATA 608 visualizing New York City TLC data from 2014-2015.

To use this repo:
1) Clone this repo
2) run `conda env create -f data_608_final.yml` or alternatively `conda create --name data_608_final --file requirements.txt` to set up a new environment and install packages.

If you don't have the data, you can run the code under the first 3 headings in final_project.ipynb. The 4th heading "Current app version" is code related to the panel app itself. The just_app.ipynb is the same code under final_project.ipynb's 4th heading, split out to easily serve the panel app via `panel serve just_app.ipynb`.
