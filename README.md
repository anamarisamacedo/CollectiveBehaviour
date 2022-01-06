# Collective detection based on visual information in animal groups

This project was based on the paper of Jacob D. Davidson et al., where the team investigated how is individual and collective visual detection dependant on various parameters ie. the number of individuals in a group, the state of the group, the position of the individual within the group etc. The goal of this project was to study and replicate the results that the team achieved using synthetic data and collect the same metrics, but also to implement a simple predator avoidance algorithm to observe how individual and collective visual information change with respect to the predator movement.
We could obtain the same results as the original paper, and analyse them on our report, but we weren't able to get results of the predator algorithm.


## References 
* Main paper: Davidson JD et al. (2021) Collective detection based on visual information in animal groups. Journal of The Royal Society Interface 18(180):202101
* Source code: https://github.com/jacobdavidson/collectivedetection
* Source data: https://datadryad.org/stash/landing/show?id=doi%3A10.5061%2Fdryad.sbcc2fr2h

## Run the simulation

Since this project needs a lot of memory to run, we need to run it on Google Colab using a GPU.

1. Open '4 - Data figures.ipynb' and '5 - Model.ipynb' on Google Colab
2. Add this folder to your Drive Disc: https://drive.google.com/drive/folders/1eYVarrWVUjaGSBkS8zIMZBZ1iaMGyrnO?usp=sharing
3. Run the files '4 - Data figures.ipynb' and '5 - Model.ipynb' to produce the results

Or if your pc has a GPU, run this:
1. Open Source code 'CollectiveBehaviour-main'
2. Download the file 'saved_data_and_results.zip' from the Source data link
3. Unzip the 'saved_data_and_results.zip' and put the 'savedresults-final' folder on the same folder that the 'CollectiveBehaviour-main' is located. Otherwise the directory should be changed inside the code
4. Only the files '4 - Data figures.ipynb' and '5 - Model.ipynb' are used to produce the results

Software used: VS Code, Anaconda3, Python 3.9.7

## Individual Contributions

Ana Macedo wrote the Abstract; part of the Introduction, Methods and Model; polished the report and the bibliography. Patricia Alcázar wrote the Results with their corresponding images and references. Vulnet Alija wrote the Problem Definition, Model, and Discussion with their appropriate references; uploaded the source code and the link to the necessary data to run the program. Žan Jonke wrote part of the Introduction and part of the Methods.
All authors studied the main and predator papers, and analysed the models.
