---
layout: post
title:  "Angular's Tour of Heroes"
date:   2021-09-28 23:28:17 -0500
categories: angular javascript
---

As I've recently landed a job that has an Angular front end, I started to shift off of React and into experimenting more with Angular.  Much like I did with React, it seemed obvious to start out with the tutorials directly on [Angular's website](https://angular.io/tutorial).  During this tutorial, I took the time to set up a local development environment on my Windows workstation as well, so the development of this tutorial was split between my MacBook and my Windows workstation (not that it matters).

This tutorial I thought was a pretty nice introduction to Angular as it introduces you to concepts like adding components and services relatively early.  I particularly like the Angular CLI as using CLI tools is something I used to do quite a bit of, but being a .NET developer took me away from to a degree (Thanks to .NET Core/.NET5 for making command line usage a joy!).  In general, I'd say I prefer TypeScript over pure JavaScript like what was being used over in the React stuff.  Angular (at least in my incredibly limited experience) seems to be a little closer to what I'm familiar with doing in XAML when using WPF as far as interpolation and data binding is concerned.

The tutorial walks you through displaying a list of heroes, and having a way to search for heroes, show a top heroes list, as well as edit hero information.  This was a nice introduction to how forms worked in Angular as well as just basic setup of components and how they interact with one another.  There was an extended tutorial that instructs you on how to build a template driven form.  I "followed" this template in some ways, but kind of applied it to the Tour of Heroes app I already had instead of creating a new component.

Now that I've completed that, I installed @angular/material and have started to update the application to use material design controls.  In my previous job, we used [Material Design in XAML](https://github.com/MaterialDesignInXAML/MaterialDesignInXamlToolkit).  Fortunately because of this, I was relatively familiar with the concepts and terminology of material design, so converting this app over to using it was relatively painless.  Most of my struggles seem to be coming from my rustiness with CSS in general.  :)

As always, feel free to check out the current progress of that application [here](https://mcbtay.github.io/angular-tour-of-heroes).