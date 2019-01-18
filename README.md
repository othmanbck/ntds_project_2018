# Feminism in Hollywood

This project was done as part of the EE-558 (A Network Tour for Data Science) class, and it tries to answer the following problem : <b>"Does 'Feminism' sell in Hollywood ?"</b>, using the Kaggle TMDB dataset.<br><br>

This repository is the submission of Team 31, composed of Othman BENCHEKROUN, Sinan BURSA, Sinan GÖKÇE and Dilara GÜNAY.

## Dependencies

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following dependencies that were not used in any of the milestones:

```bash
pip install requests
pip install tmdbsimple
```

## Files & Folders

- <b>milestones :</b> as the name indicates, this folder contains all the notebooks that we submitted during the semester. It also contains the analysis of the new network we have made for the project.
- <b>data :</b> this folder contains our database as well as the files that we created in order to save our elements.
- <b>project :</b> this is the folder that contains the most important files for the project <i>per se</i>. The <i>Bechdel_Retrieval</i> notebook was used to complement our database with the Bechdel score of each movie. The <i>Bechdel_Analysis</i> notebook was used to understand a bit more about the Bechdel data and treat it to only keep 2 variables: either the movie passes the test, or it doesn't. The <i>Project_Discovery</i> notebook was used to implement the approach we wanted to use in order to get meaningful information from our network. These are the steps that were used later on. Finally, the <i>.gexf</i> files were used visualize our data.
- <b>adjacencies :</b> this folder contains the 3 different types of adjacencies that we constructed for the project in 3 different folders with their respective feature and adjacency csv outputs and .gexf output for Gephi analysis
- <b>tests :</b> this folder contains 4 different signals for each different adjacency that was constructed in the previously described <i>adjacencies</i> folder

## License
[MIT](https://choosealicense.com/licenses/mit/)
