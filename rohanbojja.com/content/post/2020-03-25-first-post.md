---
title: First post!
subtitle: Machine learning for classifying music.
date: 2020-03-25
tags: ["music classification", "machine learning", "deep learning", "Xamarin", "Azure", "ML.NET"]
---

This is my first post, how exciting! I'm going to be talking a little bit about my upcoming project which deals with classifying music.
I'll also be sharing my Git repo once I have a working prototype. (Pull requests are always welcome! :smile: )

Music classification is an interesting field with a lot of applications, from Shazam finding that random song you like to Spotify's Daily Playlists. However, it is a cumbersome task to classify music by ear! Almost every song I know has influences from a few genres, but usually can be broadly classified into one or the other super-genre(More on this in my upcoming post). <br>  

#### A few applications from the top of my head,

* Categorizing your library for different moods.
* Finding the genre of a song.
* Finding songs that are similar to that one song you can't get out of your head.

Machine learning has been applied in the field of music classification for decades now and has proven to be a reasonable approach. But of course, there are a lot of things to consider when we talk about apply machine learning techniques to audio data. From what I can think of, we can train our machine learning model on,

* Audio features extracted from our audio files.
* Sonograms generated from our audio files.
* Both! (:scream:)

#### The entire project can be split into,

* The machine learning model
* A machine learning pipeline (A pipeline is used to help automate the workflow)
* An interface that serves predictions from our model
* An application that interacts with the interface ^^
* Developing a tool to extract features from our library (dataset)

#### A few things to consider while building the model,

* Identifying features which are important
* Removing outliers from our dataset
* Tuning training parameters to maximize accuracy

For passable accuracies, we can rely just on the audio features extracted and training a simple MLP. (Which isn't super ideal, but hey, it works for testing our framework.)

Besides, we can always swap out the model later!

I'll be talking more about my project, which classifies audio data recorded from a smart phone or from a web browser, in my next post!