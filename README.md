# assignment-7: Exploring R Packages
A repo to submit a package exploration for FISH 549

# Package Title
Today I'll be exploring the package "FD".

# Location
You can find this package on [CRAN](https://cran.r-project.org/web/packages/FD/index.html) and also on [Github](https://github.com/cran/FD) as a read-only mirror of the CRAN repository. 

# Vignettes
There are no vignettes as part of this package. 

# Applications
I haven't found any applications of this package yet outside of scientific publications. It's a relatively new package. 

# Review
The primary purpose of this package is for community ecologists to analyze functional trait data. Functional traits are characteristics of species that describe the ecological niche they occupy within a community. Once a user has created matrices of site x species and species x trait data they can use this package to calculate several diversity indices using the $dbFD$ function. For example, these indices include functional richness, evenness, and divergence, which are all aspects of alpha (within community) diversity. The diversity indices are based on a Principal Coordinate Analysis (PCoA) and users can extract the PCoA coordinates from the $dbFD$ output to visualize the ordination. I like this package because the output of one function gives quite a bit of information about a community dataset. I do, however, wish there was more documentation and more help files to make it more user-friendly. You have to have your input matrices formatted in a very particular way, and there's no examples online of how to do this, so using the package involves a lot of trial and error therefore making it a little tricky to learn how to use. I would recommend this package because I think the output is super interesting, but in recommending the package to a friend I would also share my R code with them so they could have an easier time getting started. 
