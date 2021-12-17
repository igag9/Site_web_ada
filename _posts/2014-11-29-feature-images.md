---
layout: post
title: Is it possible to predict the rating of a movie by using Quotebank and determine if gender has an impact on it?
feature-img: "assets/img/feature-img/caclul3.jpg"
thumbnail: "assets/img/thumbnails/feature-img/caclul3.jpg"
---

We wonder if it’s possible to predict movie’s ratings regarding several features.

What are the **features**?

- *gender_speaker_pct* : proportion of male (for the speakers)
- *gender_movie_pct* : proportion of male (for all participants in the creation of the film)
- *nb_quoteID_norm* : number of quotes occurences (standardized)
- memorability:
  - *gender_movie_pct* : proportion of male (for all participants in the creation of the film)
  - *days_mean_norm_before*: average number of days before the release date (standardized)
  - *days_max_norm_before* : number of days from the first day we talk about it until the release (standardized)
  - *nb_quote_month_norm_before*: the number of situations one month before the exit (standardized)
  - *days_mean_norm*: average number of days after the release date (where it is discussed) (standardized)
  - *days_max_norm* : number of days until the last day that it is discussed (standardized)
  - *nb_quote_month_norm* : the number of situations one month after discharge (standardized)

What is the **response**?

- The rating of a film

{% include aligner.html images="feature-img/q3_a.jpeg" column=3 %}

As we can see on the graph and the value of the r2=-0.10, it does not seem possible to predict the score with the proposed features
