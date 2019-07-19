# Blossom Hackathon

** Link of dataset: ** https://www.kaggle.com/spaics/hackathon-blossom-flower-classification

** Started at: ** Satarday, July 13th 00:00GMT 
** Ended at: ** Monday, July 15th 00:00GMT 

Important announcements
--

 ## Announcemetns from *Ngong Ivoline*

ATTENTION GUYS 
You really did amazing in past 48 hours.
We are so happy that you all were able to dedicate 48hrs this weekend to the hackathon. We hope you all had fun and learned something new.  This was our first time organizing something like this and we are sorry if there were any problems you faced and hope to do better for upcoming hackathons.

We will like to make another request and we hope it doesn't cause any inconveniences.

In order for our judges to evaluate your models, we need you guys to **Print The Predictions On The Test Set**, if you didn't do it in your last submission. These predictions should display both **the filenames and corresponding labels**. (We noticed some people printed their predictions without filenames. If your shuffle=True on your test_set , we wouldn't know files correspond to the predictions) .
You can do something like this:

 `im, _=cloader.dataset.imgs`
 
 `print(im, prediction class )`
 
The output will look something like:
 
`mh1.jpg, 1` 

`au2.jpg, 50`

`gc23.jpg, 4`


We understand some people maybe confused why the test set have no labels, this is because in real life when your model is deployed , it is going to do predictions on data that has not been labeled. So, in order to do a true evaluation of your model, it has to work with that kind of data.
Our judges have the true labels for this data, so they'll compare them with the output of your predictions.

We are adding an extra 24hrs for you guys to do this and then recommit your models.  This time it starts 11:59 GMT Monday (midday) and ends at  *11:59 GMT Tueday*(midday) too

========
**TIP FROM @Ronit**
Why is committing my kernel taking a lot of time
Committing a kernel runs the entire kernel from cell to cell and then saves it. If you have a cell for training the model, the entire model will be trained from the start which can result in long commit times. I suggest you save your model file and then load it to predict labels for the test data. This way your model won't have to be re-trained every time you commit your kernel
