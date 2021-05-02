---
layout: page
title: Research
sitemap:
    priority: 0.7
    lastmod: 2017-11-02
    changefreq: weekly
---
 <span class="image right"><img src="{{ "images/LSS_yellow.png" | absolute_url }}" alt="" /></span> 
I am a cosmologist, whose aim is to answer fundamental physics questions about our Universe: <i>what is our Universe made of? what is the nature of dark matter and dark energy? how did galaxies and all other objects in the Universe form and evolve?</i> My research focuses on the formation of the large-scale structure in the Universe, made of extended halos of dark matter which are interconnected by filamentary structures and surrounded by empty voids. I am particularly interested in understanding the characteristic final properties of halos and their relation to the initial conditions of the Universe. Understanding the evolution of dark matter halos and the connection between halos and galaxies can provide answers to some of the most fundamental questions in Cosmology.

I use a combination of analytic modelling, numerical simulations and artificial intelligence algorithms to learn about the Universe. In particular, I have been exploring the potential of artificial intelligence (AI) algorithms to generate new knowledge about the underlying physics driving cosmological structure formation. By understanding and explaining how and why these complex algorithms reach particular decisions, one can use them to shed light into physics problems that may be too hard to tackle with standard statistical and analytical approaches.

<hr />

### Deep learning insights into cosmological structure formation 


<img src="{{ "/images/dl_flowchart2.pdf" | absolute_url }}"  width="60%" height="60%" style="float:left; padding-left:-1px;
padding-bottom:25px; padding-right:25px ; padding-top:10px" alt="" />

This paper presents insights into the formation of dark matter halos using a deep learning framework. We trained a 3D convolutional neural network (CNN) to learn the non-linear relationship between the initial density field and the final mass of dark matter halos. While deep learning algorithms are generally seen as "black-boxes", we develop techniques that allow us to physically interpret the mapping learnt by the CNN. We removed anistropic information about the initial density field from the inputs and re-trained the CNN. We found no change in the model’s predictive accuracy, meaning that the features learnt by the CNN are equivalent to spherical averages over the initial density field. In other words, anisotropic information in the initial density field does not play a significant role in predicting the final mass of halos.

<a href="https://arxiv.org/abs/2011.10577"><b>Full article</b></a>, submitted to <i>Nature Machine Intelligence</i>, 2020. See also this <a href="https://www.mpa-garching.mpg.de/915942/hl202102?c=27981">press release article</a> published in MPA's monthly research highlights.

<hr />

### An interpretable ML framework for dark matter halo formation

<span class="image right"><img src="{{ "/images/shear_imps_errorbars.pdf" | absolute_url }}" alt=""/></span>

In this work, we developed an interpretable machine learning framework to study the impact of tidal shear effects on the formation of dark matter halos. We trained a gradient boosted tree (GBT) algorithm on an N-body simulation to infer the final mass of the halo to which each dark matter particle belongs at z=0. With GBTs, we can measure the relevance of each input feature in training the algorithm to predict the correct target variable; this allowed us to determine which features are most informative in predicting final halo masses. We first trained the algorithm with information about the density contrast in the particles' local environment in the initial conditions. The addition of tidal shear information does not yield any improvement over density information alone; the former contains irrelevant information to final halo mass. This result led to a re-evaluation of existing interpretations of ellipsoidal collapse theories of halo formation.

<a href="https://arxiv.org/abs/1906.06339"><b>Full article</b></a>, published in <i>Monthly Notices of the Royal Astronomical Society</i>, Volume 490, Issue 1, November 2019, Pages 331–342.

<hr />


### Machine learning cosmological structure formation

<span class="image left"><img src="{{ "/images/ROC_density_shear_final.pdf" | absolute_url }}" alt="" /></span>
In this paper, we first proposed a machine learning framework to gain new insights into the physics driving halo formation. We train a machine learning algorithm to learn cosmological structure formation from N-body simulations. The algorithm learns to predict whether or not dark matter particles will end up in halos of a given mass range, based on different types of information from the initial conditions.  When trained on spherical overdensities, the resulting predictions match those of spherical collapse approximations such as extended Press-Schechter theory. Additional information on the shape of the local gravitational potential is not able to improve halo collapse predictions; the linear density field contains sufficient information for the algorithm to also reproduce ellipsoidal collapse predictions based on the Sheth-Tormen model. 

<a href="https://arxiv.org/abs/1802.04271"><b>Full article</b></a>, published in <i>Monthly Notices of the Royal Astronomical Society</i>, Volume 479, Issue 3, September 2018, Pages 3405–3414.
