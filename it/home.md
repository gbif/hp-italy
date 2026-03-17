---
lang-ref: home
layout: home
title: GBIF Italia
description: Questa è la pagina del Nodo Nazionale GBIF Italiano.<br>Qui trovate dati, dataset, data provider Italiani, oltre a informazioni utili e news sempre aggiornate.
background: /assets/images/banner.png
imageLicense: CC BY
height: 70vh
permalink: /it/
---


<div style="display: flex; flex-wrap: wrap; gap: 20px 40px; justify-content: center; align-items: flex-start;">

  <div style="display: flex; flex-direction: column; align-items: center; text-align: center; width: 200px;">
    <a href="https://www.gbif.org/occurrence/search?country=IT" target="_blank">
      <img src="/assets/images/icons/italy.png" alt="" />
      <p><h3><span data-ajax-path="data.occurrenceSearch.documents.total" data-ajax-url="https://graphql.gbif.org/graphql?query=query%0A%7B%0A%20%20occurrenceSearch%28%0A%20%20%20%20predicate%3A%20%7Btype%3A%20and%2C%20predicates%3A%20%5B%7Btype%3A%20in%2C%20key%3A%20%22country%22%2C%20values%3A%20%5B%22IT%22%5D%7D%5D%7D%0A%20%20%20%20size%3A%2010%0A%20%20%29%20%7B%0A%20%20%20%20documents%20%7B%0A%20%20%20%20%20%20total%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D%0A"></span></h3></p>
    </a>
    <a href="https://www.gbif.org/occurrence/search?country=IT" target="_blank" style="margin-top: 10px;">
      Record per l'Italia
    </a>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; text-align: center; width: 200px;">
    <a href="https://www.gbif.org/occurrence/search?publishing_country=IT" target="_blank">
      <img src="/assets/images/icons/occurrences.png" alt="" /><p><h3><span data-ajax-path="data.occurrenceSearch.documents.total" data-ajax-url="https://graphql.gbif.org/graphql?query=%0Aquery%20%7B%0A%20%20occurrenceSearch%28%0A%20%20%20%20predicate%3A%20%7B%0A%20%20%20%20%20%20type%3A%20and%0A%20%20%20%20%20%20predicates%3A%20%5B%0A%20%20%20%20%20%20%20%20%7B%20type%3A%20in%2C%20key%3A%20%22publishingCountry%22%2C%20values%3A%20%5B%22IT%22%5D%20%7D%0A%20%20%20%20%20%20%5D%0A%20%20%20%20%7D%0A%20%20%20%20size%3A%2010%0A%20%20%29%20%7B%0A%20%20%20%20documents%20%7B%0A%20%20%20%20%20%20total%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D%0A"></span></h3></p>
    </a>
    <a href="https://www.gbif.org/occurrence/search?publishing_country=IT" target="_blank" style="margin-top: 10px;">
      Record pubblicati da data provider Italiani
    </a>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; text-align: center; width: 200px;">
    <a href="https://www.gbif.org/publisher/search?country=IT" target="_blank">
      <img src="/assets/images/icons/publishers.png" alt="" /><p><h3><span data-ajax-url="https://api.gbif.org/v1/organization?country=IT&amp;limit=0&amp;isEndorsed=true">100,000</span></h3></p>
    </a>
    <a href="https://www.gbif.org/publisher/search?country=IT" target="_blank" style="margin-top: 10px;">
      Data provider Italiani
    </a>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; text-align: center; width: 200px;">
    <a href="https://www.gbif.org/resource/search?contentType=literature&literatureType=journal&relevance=GBIF_USED&countriesOfResearcher=IT&peerReview=true" target="_blank">
      <img src="/assets/images/icons/literature.png" alt="" /><p><h3><span data-ajax-url="https://api.gbif.org/v1/literature/search?contentType=literature&amp;literatureType=journal&amp;relevance=GBIF_USED&amp;countriesOfResearcher=IT&amp;peerReview=true">100,000</span></h3></p>
    </a>
    <a href="https://www.gbif.org/resource/search?contentType=literature&literatureType=journal&relevance=GBIF_USED&countriesOfResearcher=IT&peerReview=true" target="_blank" style="margin-top: 10px;">
      Articoli scientifici che usano dati mediati dal GBIF pubblicati su riviste peer-reviewed da ricercatori Italiani
    </a>
  </div>

</div>


