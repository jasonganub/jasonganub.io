---
layout: project
permalink: /:title/
category: projects
date: 2020-01-01

meta:
  keywords: "Instant Service"

project:
  title: "Instant Service"
  type: "Gojek"
  url: "https://www.gojek.com/blog/gocar/pesan-gocar-di-bandara-soekarno-hatta/"
  logo: "/assets/images/projects/gojek-instant/logo.jpg"
  tech: "Clojure, Ziggurat, Kafka, Firehose, Redis Geo, Firebase"
  description: "Instant is an alternative allocation mode for Transport where you and driver's match in-person at a designated hub such as train stations, airports, and malls. It has proven to be on average; faster than regular allocation."

dev:
  title: "Jason Ganub"
  url: "https://github.com/jasonganub"
  year: "2020"

images:
  - image:
    url: "/assets/images/projects/gojek-instant/screenshot-1.jpg"
    alt: "Red Pineapple website on tablet, mobile and desktop"
  - image:
    url: "/assets/images/projects/gojek-instant/screenshot-2.jpg"
    alt: "Red Pineapple website on a desktop device"
---
<p>I developed the Instant service for the Transport team. I lead the development of features, engineering improvements, and scaling new locations with above 90% code coverage. I leveraged Redis's geo functionality so we can consume driver locations and send a notification to nearby drivers if supply is low at an Instant location.</p>