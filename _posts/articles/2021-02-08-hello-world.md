---
layout: article
permalink: /:title/
category: articles
date: 2021-04-08

meta:
  keywords: "Sharing Sessions"

article:
  title: "Internal Sharing Sessions"
  type: "Gojek"
  url: "https://medium.com/@jasonganub/internal-technical-sharing-sessions-620851bad30f"
  logo: "https://miro.medium.com/max/700/1*4222erIq-FAcIxNiNAjkBA.jpeg"
  tech: "Clojure, Ziggurat, Kafka, Postgres"
  description: "Driver karma is a service to provide information to customers about the number of trips a driver has completed, the status of their temperature check, and if vehicles have the safety shield."
  impact: ""

dev:
  title: "Jason Ganub"
  url: "https://github.com/jasonganub"
  year: "2019"

images:
  - image:
    url: "/assets/images/projects/gojek-driver-karma/screenshot-1.jpg"
    alt: ""
  - image:
    url: "/assets/images/projects/gojek-driver-karma/screenshot-2.jpg"
    alt: ""
---
<p>Driver Karma was the first project I owned on my own with a lot of learnings on performance related to partitioning, indexing, caching, translations, etc. It was written in Clojure which was a pleasure to write both the implementation and unit tests in. REPL was a powerful tool that helped debug quickly using Cursive locally and on integration servers. Funny story is that I worked on majority of the project while I was in the U.S. during the day and syncing with product in the evening.</p>