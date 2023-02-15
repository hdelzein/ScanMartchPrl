### Scan Mathcing Localizatiion Project

This is a summary of the implementation of the results of Scan Matching Localization Project


## Step One. Filter scan using voxel filter

- 1- Line 263 to 273


## Step Two. Find pose transform by using ICP or NDT matching

I used ICP and the code is from:

- 1- Line 278 to 284


## Step Three. Created the ICP function reused from the homework

- 1- Line 103 to 155


## Step Four. Transform scan so it aligns with ego's actual pose and render that scan

- 1- Line 281 to 291


## Output of the transformation is shown in the image below

<img src="ICP_PassedImage.png"/>




