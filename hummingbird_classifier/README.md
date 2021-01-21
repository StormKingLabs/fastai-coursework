# Identifying Hummingbird Species of the Rocky Mountains

This project serves as a simple FastAI example for how to apply transfer learning on a new dataset and then to deploy the model via Voila. This app has been adapted from Course 2 of FastAI v4.

For this project, let's focus on hummingbirds since they're [extraordinary little creatures](https://nationalzoo.si.edu/migratory-birds/hummingbirds). Here, our goal is to classify any specicies of hummingbird that's resident in Colorado.  It was interesting to see how quickly we can use transfer learning on some (relatively noisy) Bing Image results to produce a decent working classifier.

Audubon [observes the following](https://rockies.audubon.org/blog/habitat-hero/backyard-hummingbirds
) about hummingbird species in the Rockies:

> In Wyoming and Colorado there are four main species that you will see. Broad-tailed (Selasphorus platycercus) and Rufous (Selasphorous rufus) Hummingbirds are the most common you will probably see. Less common species are the Calliope (Selasphorus calliope) and Black-chinned (Archilochus alexandri) Hummingbirds.

|  |  |  |  |
|---|---|---|---|
| ![]( https://nas-national-prod.s3.amazonaws.com/styles/bird_illustration/s3/2735_Sibl_9780307957900_art_r1.jpg?itok=m1TzaJDi ) | ![]( https://nas-national-prod.s3.amazonaws.com/styles/bird_illustration/s3/2747_Sibl_9780307957900_art_r1.jpg?itok=LXCr5qsa ) | ![]( https://nas-national-prod.s3.amazonaws.com/styles/bird_illustration/s3/2760_Sibl_9780307957900_art_r1.jpg?itok=pnOj0j9q ) | ![]( https://nas-national-prod.s3.amazonaws.com/styles/bird_illustration/s3/2733_Sibl_9780307957900_art_r1.jpg?itok=kM3iVfa8 ) |


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/StormKingLabs/fastai_projects/main?urlpath=%2Fvoila%2Frender%2Fhummingbird_classifier%2Fwebapp_colorado_hummingbird_classifier_v1.ipynb)
