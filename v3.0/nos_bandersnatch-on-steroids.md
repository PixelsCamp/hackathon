
# NOS

## “Bandersnatch” on steroids!

![“Bandersnatch” on steroids!](https://raw.githubusercontent.com/PixelsCamp/hackathon/master/v3.0/assets/nos_bandersnatch-on-steroids.jpg "“Bandersnatch” on steroids!")

## Context

Inspired on Bandersnatch movie experience (from netflix) the goal is to playout video based on user/viewer decisions. However the path or script can be created dynamically and on the fly (the steroids part)

## Details

How it works?
Well this is a big challenge to be addressed at once, there are several levels that can be explored from video stuff to application layer. You can go through:
Metadata creation based on video inspection/index by frame processing and take all the metadata related with that clip or video sample (we can provide video samples)
Based on that metadata extracted above, create metadata relations/links
From metadata model (relations created above), create a script dynamically that links several video samples/clips and takes in account questions/suggestions/interactions asked to the user (similar to Bandersnatch: simple question with 2 options answer)
Create a app that playout the video integrated in a UI that interacts with the user and perform the video transitions (smoothly via preload for instance)
 
A participation can address all the topics above or some of them trying to simulate (or mock up) dependencies.
 
Use case scenario:
A video sample with a character (person) drinking something. Question to the viewer: water or beer? If beer was chosen a video related with beer (via metadata extracted) starts playing…

## Resources


