--- 
title: "Just a Recommender System Based on Google Applications Data "
author: "Alfredo Méndez, Eduardo D. Martínez, Alaín Cabrera, Pedro Hernández - ITAM"
date: "2017-05-24"
site: bookdown::bookdown_site
documentclass: book
biblio-style: apalike
link-citations: yes
description: "A short description of the study driven"
---

# Abstract

This study examined the development of a Recommender System based on _Google Takeout_ data. This system is built on a web application that is will be documented on this paper. The main motivation to develop it is this following concept: Make the Google Data accessible to everyone.
We already know that every person that has a Google account is able to download their information, but not everyone has the ability to handle or even understand what _mbox_ or _json_ files are. Then we created a web app that allows every person can "read" their own data.  

On this document, the reader will find out a little view of the process of the development itself. First, is been used the anonymized data from project's volunteers, it is been downloaded the historical records of _Gmail_, Location and Searching from Google. Then It was driven an exploratory data analysis in order to understand the nature of features. After that, it is been predicted the most frequent places the individual has been, this step using Non-supervised _Machine Learning_ algorithms based on density. It is been found the network that the individual can be influenced by, and all the important keywords used, in order to filter topics the person is likely to find out using text mining algorithms. All the process it is been documented and it is open code, the reader can easily try the beta version or reproduce the app instead.  

There is a lot of work left to do, but it is been settle the first steps, one thing is sure: one can find out that sites of interest around the most visited places for a person, can be high accuracy recommended based on searching history, and networking.  
