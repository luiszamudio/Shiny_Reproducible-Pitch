Reproducible Pitch Presentation.Rpres
========================================================
author: Luis Zamudio
date: 24/09/2016

Introduction
========================================================

This application is developed using R Programming 
language in R Studio's IDE. The application
used shiny environment under R studio for interface
desigening.
This is a fairly good app that can be used to 
get some good suggestions about music and movies.
I'll be updating this app in future and will deploy
some algorithm combined with a good database to
provide better and wide range of suggestions.

Main uses of application are as follows:

- Predicting music according to mood
- Predicting movie according to genre


Instructions
========================================================

While inputting the mood and genre always keep caps-off

Below is the list of moods you can enter:

- happy
- sad
- alone
- angry
- bitchy
- blank
- confused
- depressed

========================================================

- energetic
- geeky
- high 
- lazy
- pleased
 
Below is the list of genre you can enter:

- action
- musicals
- biopic
- period
- romance

========================================================

- animation
- science fiction
- cult
- disaster
- spy
- drama
- fantasy
- thriller
- gangster
- war
- westerns
- horror


Slide With Code
========================================================

```r
x <- rnorm(100) 
y <- x + rnorm(100)
plot(x,y,xlab="smile", ylab="happiness", main="Relation b/w laughing and happiness" )
```

![plot of chunk unnamed-chunk-1](ReproduciblePitchPresentation-figure/unnamed-chunk-1-1.png)


