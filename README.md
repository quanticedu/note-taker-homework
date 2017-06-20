# Smartly Frontend Homework

As part of our application process, we'd like to see what you can create by giving you a small assignment. It should take you no more than a few hours to complete the assignment, but any extra polish or features you might want to put in will not go unnoticed.

## Overview: The Note Taker

We would like you to create a small app that allows annotating an article with comments, similar to Kindle or Medium. The annotations should be created by directly selecting sections of the text, after which the user is given the opportunity to include an optional comment with the annotation. Annotations should be persisted in a way such that when you reopen the app, previously saved annotations are reloaded.

## Features

 - [ ] Create an "Article" view that displays a single hard-coded article, along with a list of any associated annotations
 - [ ] Allow selecting a string of text in the article and saving a record of it as an annotation, along with an optional attached comment
 - [ ] Allow removing annotations from the list of saved annotations for an article
 - [ ] Persist the annotations so users don't lose them between runs of the app

## Persistence

You may choose to integrate with a real backend like Firebase or MongoDB, or persist your data via a browser-side technology like LocalStorage.

#### Ideas for extra credit

 - [ ] Create "Library" view with a list of articles to select (these can be hard-coded, or loaded from a remote source)
 - [ ] Show the annotations within the article as highlights (can get creative with this UI)
 - [ ] Design a nice UI for saving the annotations in a pop-up right where you highlight them in the text 
 - [ ] Support rich-text/HTML for the article (how will you handle selection across elements like bulleted lists, etc.?)
 - [ ] Support multiple-user accounts in the app (no need for authentication for this demo, but feel free if you like)
 - [ ] Social annotations! Make it possible to see other's annotations in the article. View counts? Heuristics for surfacing "popular" highlights?
 - [ ] Mobile browser support

## Requirements

You can use any frameworks or libraries you prefer; we simply ask that you build the app as a single-page Javascript application.

## Turning it in

To complete your homework, please fork this repo and commit your work to your fork. When you are ready for us to look at it, give us access to your fork so we can review and run it.

If you have any questions, please ask. And good luck!