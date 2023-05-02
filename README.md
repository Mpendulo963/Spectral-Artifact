# Spectral-Artifact
This repository explains the attached spectral artefact algorithm notebook that is used to detect small artefacts that repeat every 64 channels in the narrowband Meerkat observations. The algorithm checks artefacts in old observations and also monitors if they have returned in new observations. The issue is explained in detail at https://skaafrica.atlassian.net/l/cp/M4SCjArV.  



### User guide
The notebook referred to in this repository is https://github.com/Mpendulo963/Spectral-Artifact/blob/ef4554c83a00a01f529a5e2ebb53cfb39b428140/Spectral_artifact_notebook.  

To test the artefact in the user data of interest, which is found in the SARAO archive https://archive.sarao.ac.za/. The user must get the archive data link and replace the current link in the notebook **"fn_obs = htt..."** as shown in the figure below, then run all the notebook cells. At the moment this algorithm checks for periodic artefacts with a period of 64 channels. To intensify the results, you can modify the script to check for artefacts with a range of periods of 2, 3, 4, 5 ... 64 channels for a specific auto or cross-product. Necessary comments are added to the notebook, and futher modifications will be updated once done. 



![plot](https://github.com/Mpendulo963/Spectral-Artifact/blob/f6d8136d51ab0f56d86519d05a434dba7b947df7/Screenshot%202023-05-02%20at%2010.00.51.png)

