# Blossom Hackathon

## Link of dataset: 
https://www.kaggle.com/spaics/hackathon-blossom-flower-classification

## Started at:
Satarday, July 13th 00:00GMT 
## Ended at:
Monday, July 15th 00:00GMT 

## Winners:

**Winner:** *Venkata Rathnam Muralidharan*

**FIRST RUNNER UP:** *Shivu*

**2nd runner up:** *Abhishek Lalwani*

Important Announcements
-- 

- **DO NOT** make your kernel public while the hackathon is still running.

**DO** make it public after **Monday 23:59 GMT**. Any modification to your kernel code after that time counts as disqualification.

This is to avoid risks of people copying each other's code.

- We have now uploaded the test set into Kaggle under the name "test set.zip", so you can finally test your model! 

- In order for our judges to evaluate models, we need you guys to **Print The Predictions On The Test Set**, if you didn't do it in your last submission. These predictions should display both **the filenames and corresponding labels**. (We noticed some people printed their predictions without filenames. If your shuffle=True on your test_set , we wouldn't know files correspond to the predictions) .
You can do something like this:

 `im, _=cloader.dataset.imgs`
 
 `print(im, prediction class )`
 
The output will look something like:
 
`mh1.jpg, 1` 

`au2.jpg, 50`

`gc23.jpg, 4`


We understand some people maybe confused why the test set have no labels, this is because in real life when your model is deployed , it is going to do predictions on data that has not been labeled. So, in order to do a true evaluation of your model, it has to work with that kind of data.
Our judges have the true labels for this data, so they'll compare them with the output of your predictions.

We are adding an extra 24hrs for you guys to do this and then recommit your models.  This time it starts 11:59 GMT Monday (midday) and ends at  **11:59 GMT Tueday**(midday) too.





**TIP FROM @Ronit**

*Why is committing my kernel taking a lot of time*

- Committing a kernel runs the entire kernel from cell to cell and then saves it. If you have a cell for training the model, the entire model will be trained from the start which can result in long commit times. I suggest you save your model file and then load it to predict labels for the test data. This way your model won't have to be re-trained every time you commit your kernel.
- Please Sort the Predictions by the Image names in Ascending Order, that way there will be no discrepancies in the order of the predictions which may occur due to different methods of importing the test data. For example, here are my predictions sorted in an ascending manner:

![sc](https://user-images.githubusercontent.com/14244685/61531580-0f726300-aa49-11e9-8842-29edb101e263.png)


