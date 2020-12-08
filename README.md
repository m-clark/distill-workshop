distill-workshop


This will introduce R users to the [Distill format for R Markdown](https://rstudio.github.io/distill/), for scientific communication and building websites. 


If you just want the slides, [go here](https://m-clark.github.io/distill-workshop/), though admittedly, like most slides, they are likely not going to be very useful without the context.

If attending the workshop, run the following in your R session to get the associated RStudio project.  If you want, change the `destdir` to save the project in a specific place (not necessary, should default to desktop).  It will open the RStudio project for you.


```r
install.packages('usethis')  # if you don't have it

usethis::use_course(
  'https://github.com/m-clark/distill-workshop/blob/master/distill-workshop.zip?raw=true', 
  destdir = NULL
)
```

If you have issues, just download that zip file (click or paste the link above into your browser), unzip it to a location of your choosing, then:

- Click on the blue .Rproj icon inside

OR

- With RStudio - File/Open Project - Navigate to the folder - Open


With your RStudio project set up, you may install Distill via `install.packages('distill')`, and are ready to participate.
