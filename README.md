# Tutorial 6: Build a Spotify-integrated App

## Getting started

First we needed to create a spotify account. For the sake fo the excercise we created a new
one with our UPC email.

![img.png](img.png)

After listening to some Spanish music, we got back to work.

![img_1.png](img_1.png)

We visited to developer link and accepted the terms.

![img_2.png](img_2.png)
![img_3.png](img_3.png)

Now we created an app, everything so far went really smooth. The 
tutorial is clear and the spotify platform as well.

![img_4.png](img_4.png)
![img_5.png](img_5.png)
![img_6.png](img_6.png)

## Basic Demo WebApp

The tutorial supplied us with some streamlit code, so we copied it into our repo.

We need to install the spotipy library first.

![img_7.png](img_7.png)

We had some other uninstalled dependencies, so we installed those as well.

![img_8.png](img_8.png)
![img_9.png](img_9.png)

Sklearn didn't work, we needed to install scikit-learn instead.

![img_10.png](img_10.png)

This resulted in a blank page. Something is wrong here.

![img_11.png](img_11.png)

We needed to change the credentials with the ones from the raco maybe.

![img_12.png](img_12.png)
![img_13.png](img_13.png)

This is looking better:

![img_14.png](img_14.png)

![img_15.png](img_15.png)

The redirect URL didn't work, so we changed that in the code:

![img_16.png](img_16.png)

This looks better, this now results in another URL.
We needed to paste this in terminal, apparently.

![img_17.png](img_17.png)
![img_18.png](img_18.png)

This was actually not the solution! The problem was we need to run "streamlit run app.py"
instead of "python app.py":

![img_19.png](img_19.png)

This solved this issue, but now the next problem was the following:

![img_20.png](img_20.png)

We looked into the code and saw that it clustered our liked songs. As we made a new
account for this tutorial, we didn't have any. So we liked some songs ons spotify.

![img_21.png](img_21.png)

Awesome! No we can see the clustering at work!

![img_22.png](img_22.png)

## General opinion

This was a fascinating tutorial. First of all we learned that there is a free spotify developer API. Amazing! We use spotify every
day, and it is something we do in our free time. Now we can analyze our own listening habits. We encountered some
problems trying to get everything running, but that is probably on us. The tutorial was perfect and well documented
with enough images and screenshots.

If we were to grade this tutorial we would give a 10/10, definitely!