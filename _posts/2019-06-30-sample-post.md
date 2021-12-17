---
layout: post
title: Datasets selection
bootstrap: true
feature-img: "assets/img/feature-img/archive.jpg"
thumbnail: "assets/img/feature-img/archive.jpg"
excerpt_separator: <!--more-->
---
**Three databases were used to answer the research questions :**

<!--more-->
<!-- Page Content -->
<div class="container">

  <div class="row">
    <div class="col-lg-6 mb-4">
      <div class="card h-100">
        <a href="#"><img class="card-img-top" src="https://upload.wikimedia.org/wikipedia/commons/2/27/Wikidata_barcode.svg" alt=""></a>
        <div class="card-body">
          <h4 class="card-title">
            <a href="#">Wikidata</a>
          </h4>
          <p class="card-text">The Wikidata database was used because it contains information about people, films, etc. In order to answer our research questions, we need to extract the gender and age of movies' protagonists (speakers, producers, actors), and the movies' release date. Metadata about Quotebank's speakers are already provided in files speaker attributes.parquet. The informations for other people will be retrieve via the Wikidata API.</p>
        </div>
      </div>
    </div>
    <div class="col-lg-6 mb-4">
      <div class="card h-100">
        <a href="#"><img class="card-img-top" src="https://logowik.com/content/uploads/images/imdb-internet-movie-database5351.jpg" alt=""></a>
        <div class="card-body">
          <h4 class="card-title">
            <a href="#">IMDb</a>
          </h4>
          <p class="card-text">Internet Movie Database (IMDb) is an open source database that provides informations about movies. This database is available online, separated in six datasets. This datasets were concatenated and treated in one single dataset. Columns were filtrated regarding of the needs of the research. Columns of interest are the following : title, year, genres, crew (producer, cinematographer, writer), actors, ratings.</p>
        </div>
      </div>
    </div>
    <div class="col-lg-6 mb-4">
      <div class="card h-100">
        <a href="#"><img class="card-img-top" src="http://www.benoitmeylan.ch/ressources/img/Quotebank.png" alt=""></a>
        <div class="card-body">
          <h4 class="card-title">
            <a href="#">Quotebank</a>
          </h4>
          <p class="card-text">As said the 2018 data from quotebank was retrieved. To select the quotes talking about cinema, a selection using the names of films was made.</p>
        </div>
      </div>
    </div>
  </div>
  <!-- /.row -->

</div>
<!-- /.container -->
