# Chapter 1.2: Train an image classifier without a webcam

This file is the no-webcam alternative to the **Try it now** task in Chapter 1.2, *How Machines Learn from Examples*. Instead of recording photos of your hand, you'll train the same kind of model in Teachable Machine using the photos of croissants and muffins in this folder. Then you'll test it with photos it has never seen.

It takes about ten minutes. You need a computer with a web browser. You don't need a webcam, an account, or any code.

## What's in this folder

- **Training photos**: photos of croissants and photos of muffins. You'll use these to teach the model.
- **Test photos**: a few extra photos that are *not* used for training. You'll use these to check whether the model learned general patterns or just memorized its training examples (see "Training, testing, and why you split the examples" in the chapter).

## Step 1: Download the photos

1. On this page, click the **Code** button at the top of the repository's main page, then click **Download ZIP**. Alternatively, open each photo in this folder and download it individually.
2. Unzip the download if you chose the ZIP option.
3. Find the `Chapter-1.2` folder (`files/Book1/Chapter-1.2`) and note where the croissant photos, muffin photos, and test photos are. You'll need to browse to them in a moment.

## Step 2: Create the project

1. In your web browser, go to <https://teachablemachine.withgoogle.com>.
2. Click **Get Started**.
3. Click **Image Project**, then click **Standard image model**.

## Step 3: Add the training photos

1. In the first panel, click the pencil icon next to **Class 1**, type `Croissant`, and then press **Enter**.
2. In the second panel, click the pencil icon next to **Class 2**, type `Muffin`, and then press **Enter**.
3. In the **Croissant** panel, click **Upload**, then click **Choose images from your files**. Select all of the croissant training photos and open them. Wait for the thumbnails to appear.
4. Repeat in the **Muffin** panel, selecting all of the muffin training photos.

> **Important:** Only upload the *training* photos here. Keep the test photos out of the training classes. The model must never see them during training, otherwise the test tells you nothing.

## Step 4: Train the model

1. In the **Training** panel, click **Train Model**.
2. Keep the browser tab open while it trains. Training usually takes less than a minute.

## Step 5: Test with photos the model has never seen

1. In the **Preview** panel, find the **Input** switch. Change the input from **Webcam** to **File**.
2. Click **Choose images from your files**, or drag a test photo onto the panel.
3. Look at the bars under **Output**. They show how confident the model is in each label, as a percentage.
4. Repeat for each test photo, and write down whether the model chose the right label and how confident it was.

## Step 6: See what happens with something it has never seen

The model only knows two answers, so it must pick one of them, even when the photo shows neither a croissant nor a muffin.

1. Find a photo of something else, such as a bagel, a cookie, a slice of bread, or a bowl of fruit. If any of the test photos in this folder show a different kind of baked good, use one of those. Otherwise, use any photo from your own device.
2. Upload it in the **Preview** panel, using the same steps as in Step 5.
3. Watch which label the model chooses, and how confident it is.

You should see the model choose either **Croissant** or **Muffin**, sometimes with high confidence. It can't say "I don't know."

## Check the result

- [ ] Did the model choose the correct label for most of the croissant test photos?
- [ ] Did it choose the correct label for most of the muffin test photos?
- [ ] Did the model get any test photos wrong? If so, what did those photos have in common (angle, lighting, background, plate or paper case)?
- [ ] When you showed it something that was neither a croissant nor a muffin, did it still choose one of its two labels?
- [ ] Can you explain, in one sentence, why the model can't say "I don't know"?

## Going further

These experiments show why varied examples matter (see "Good practice" in the chapter):

- **Remove some training photos.** Click the three-dot menu in a class panel, choose **Remove All Samples**, upload only a handful of photos, and retrain. Does the model get worse on the test photos?
- **Use unbalanced examples.** Train with many croissant photos and only a few muffin photos. Does the model start favoring croissants?
- **Look for the wrong pattern.** If every croissant in your training photos sits on a plate and every muffin sits in a paper case, the model may learn the plate or the case instead of the food. Do any of your test photos make it fail that way?

## What to ask next

If you have access to a chat assistant, ask it to help you understand your results. Replace the text in square brackets with what you saw:

```text
I trained an image classifier in Teachable Machine with two labels: "Croissant" and "Muffin". When I tested it with [describe a photo it got wrong], it said "[label]" with [confidence]% confidence. Explain why in plain English, and suggest two ways I could improve the training examples.
```

## Troubleshooting

- **The Upload button doesn't appear.** Make sure you chose **Image Project** and **Standard image model**, not an audio or pose project.
- **The preview doesn't change when I upload a photo.** Check that the **Input** switch is set to **File** and that you've finished training the model.
- **Training seems stuck.** Keep the tab open and visible. Some browsers slow down background tabs.
- **I want to start again.** Refresh the page and begin at Step 2. Teachable Machine doesn't save a project unless you save it to Google Drive.

Return to Chapter 1.2 in the book to continue. Chapter 1.3 looks inside the neural network that learned from your examples.
