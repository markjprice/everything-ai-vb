Everything AI Visual Bible
Book 1, Chapter 1.2: How Machines Learn from Examples
Sample files for the Try it now task

Use these pictures if you don't have a webcam. They replace the thumbs-up
and open-hand pictures in the task.

What's in this folder
---------------------
train/croissants   30 pictures of croissants, for training
train/muffins      30 pictures of muffins, for training
test               5 pictures the model never sees during training:
                   test-1.jpg  a croissant
                   test-2.jpg  a muffin
                   test-3.jpg  a croissant
                   test-4.jpg  a muffin
                   test-5.jpg  a donut, which is neither a croissant
                               nor a muffin

The pictures use different backgrounds, plates, lighting, sizes, and
angles. That variety helps the model learn what a croissant or a muffin
looks like, rather than learning the background, as Chapter 1.2 explains.

How to use them in Teachable Machine
------------------------------------
1. Follow steps 1 to 3 of the task.
2. Rename Class 1 to Croissant, and Class 2 to Muffin.
3. In the Croissant panel, click Upload, then choose all 30 pictures in
   the train/croissants folder.
4. In the Muffin panel, click Upload, then choose all 30 pictures in the
   train/muffins folder.
5. Click Train Model and wait for training to finish.
6. In the Preview panel, change the input from Webcam to File, then
   choose each picture in the test folder in turn.
7. Watch which label the model chooses for test-5.jpg, the donut. It has
   only two labels, so it must pick one of them, often with high
   confidence.

About the pictures
------------------
All pictures were drawn by computer for this book. They're original
illustrations, not photos of real food, and you're free to use them for
learning.
