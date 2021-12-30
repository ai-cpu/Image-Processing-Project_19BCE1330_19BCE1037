# Image-Processing-Project_19BCE1330_19BCE1037
Natural Disaster Detection


In this tutorial, you will learn how to automatically detect natural disasters (earthquakes, floods, wildfires, cyclones/hurricanes) with up to 95% accuracy using Keras, Computer Vision, and Deep Learning.

I remember the first time I ever experienced a natural disaster — I was just a kid in kindergarten, no more than 6-7 years old.

We were outside for recess, playing on the jungle gym, running around like the wild animals that young children are.

Rain was in the forecast. It was cloudy. And very humid.

My mother had given me a coat to wear outside, but I was hot and uncomfortable — the humidity made the cotton/polyester blend stick to my skin. The coat, just like the air around me, was suffocating.

All of a sudden the sky changed from “normal rain clouds” to an ominous green.

The recess monitor reached into her pocket, grabbed her whistle, and blew it, indicating it was time for us to settle our wild animal antics and come inside for schooling.

After recess we would typically sit in a circle around the teacher’s desk for show-and-tell.

But not this time.

We were immediately rushed into the hallway and were told to cover our heads with our hands — a tornado had just touched down near our school.

Just the thought of a tornado is enough to scare a kid.

But to actually experience one?

That’s something else entirely.

The wind picked up dramatically, an angry tempest howling and berating our school with tree branches, rocks, and whatever loose debris was not tied down.

The entire ordeal couldn’t have lasted more than 5-10 minutes — but it felt like a terrifying eternity.

It turned out that we were safe the entire time. After the tornado had touched down it started carving a path through the cornfields away from our school, not toward it.

We were lucky.

It’s interesting how experiences as a young kid, especially the ones that scare you, shape you and mold you after you grow up.

A few days after the event my mom took me to the local library. I picked out every book on tornados and hurricanes that I could find. Even though I only had a basic reading level at the time, I devoured them, studying the pictures intently until I could recreate them in my mind — imagining what it would be like to be inside one of those storms.



Natural disasters cannot be prevented — but they can be detected, giving people precious time to get to safety.

In this tutorial, you’ll learn how we can use Computer Vision and Deep Learning to help detect natural disasters.

To learn how to detect natural disasters with Keras, Computer Vision, and Deep Learning, just keep reading!


Looking for the source code to this post?

Detecting Natural Disasters 
In the first part of this tutorial, we’ll discuss how computer vision and deep learning algorithms can be used to automatically detect natural disasters in images and video streams.

From there we’ll review our natural disaster dataset which consists of four classes:

Cyclone/hurricane
Earthquake
Flood
Wildfire
We’ll then design a set of experiments that will:

Help us fine-tune VGG16 (pre-trained on ImageNet) on our dataset.
Find optimal learning rates.
Train our model and obtain > 95% accuracy!
Let’s get started!
