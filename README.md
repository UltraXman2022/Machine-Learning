<h1>Project description</h1>
Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra.
You have access to behavior data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis course). For this classification task, you need to develop a model that will pick the right plan. Since you’ve already performed the data preprocessing step, you can move straight to creating the model.

Develop a model with the highest possible accuracy. In this project, the threshold for accuracy is 0.75. Check the accuracy using the test dataset.

<h2>Project instructions</h2>
<ul><li>Open and look through the data file</li>
<li>Split the source data into a training set, a validation set, and a test set</li>
<li>Investigate the quality of different models by changing hyperparameters. Briefly describe the findings of the study</li>
<li>Check the quality of the model using the test set</li>
<li>Additional task: sanity check the model. This data is more complex than what you’re used to working with, so it's not an easy task. We'll take a closer look at it later</li></ul>

<h2>Data description</h2>
Every observation in the dataset contains monthly behavior information about one user. The information given is as follows:
<ul><li>сalls — number of calls</li>
<li>minutes — total call duration in minutes</li>
<li>messages — number of text messages</li>
<li>mb_used — Internet traffic used in MB</li>
<li>is_ultra — plan for the current month (Ultra - 1, Smart - 0)</li></ul>
