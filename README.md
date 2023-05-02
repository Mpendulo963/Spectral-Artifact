# Spectral-Artifact
This repository explains the attached spectral artefact algorithm notebook that is used to detect small artefacts that repeat every 64 channels in the narrowband Meerkat observations. The algorithm checks artefacts in old observations, and also monitor if they have returned in new observations. Issue futher explained in https://skaafrica.atlassian.net/l/cp/M4SCjArV.  



### User guide
To test the artifact in the data of intrest, which is found in the SARAO archieve https://archive.sarao.ac.za/. user must get the archieve data link and replace the current link "fn_obs = htt..." in the notebook https://github.com/Mpendulo963/Spectral-Artifact/blob/ef4554c83a00a01f529a5e2ebb53cfb39b428140/Spectral_artifact_notebook.ipynb as shoon in the figure bellow, then run all the notebook cells. At the moment this algorithm checks for periodic artefacts with a period of 64 channels. To intensify the results, you can modify the script to check for artefacts with a range of periods of 2, 3, 4, 5 ... 64 channels for a specific auto or cross product. Futher modifications will be updated once done. 



![plot](https://github.com/Mpendulo963/Spectral-Artifact/blob/f6d8136d51ab0f56d86519d05a434dba7b947df7/Screenshot%202023-05-02%20at%2010.00.51.png)

