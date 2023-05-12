# Tutorial 6: Build a Spotify-integrated App

This tutorial consistes on discovering the spotify API by regestering in spotify as a developer, creating an application and finaly interacting with the Spotify services.

## Getting started

First of all we started by creating a new account and regestering as a develpper so we will be able to create application.

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
In order to test the webApp we have used the code given.
This code is a Streamlit web application that demonstrates clustering of Spotify songs based on their audio features.
The code creates an app which provides the user with a sidebar to select the range of top songs he wants to analyze and depending on the user's selection the top tracks are fetched and stored. If the clustering button is clicked, the selected songs are processed and the clustering algorithm is applied.
The resulting clusters are plotted in a scatter plot and finaly the scatter plot should be displayed in the Streamlit web app.

First, to run this code, we need to install the spotipy library.

![img_7.png](img_7.png)

We had some other uninstalled dependencies, so we installed those as well.

![img_8.png](img_8.png)
![img_9.png](img_9.png)

Sklearn didn't work, we needed to install scikit-learn instead.

![img_10.png](img_10.png)


![img_11".png](spotify-autho.png)


![img_11'.png](img_11'.png)

## Spotify API exploration
In this step we want to connect to the Spotify API with Python using the spotpi library in order to retrieve information about a specific playlist from the Spotify API and then obtains details about the songs contained in that playlist as the name of the song, URI, popularity and some details about the main artists. 

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