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


![img_11.png](img_11.png)


![img_11'.png](img_11'.png)
We needed to change the credentials with the ones from the raco maybe.
## Spotify API exploration

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

TODO it doesn't work for me.

## General opinion
