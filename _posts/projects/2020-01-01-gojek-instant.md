---
layout: project
permalink: /:title/
category: projects
date: 2020-01-01

meta:
  keywords: "Gojek Instant"

project:
  title: "Gojek Instant"
  type: "Gojek"
  url: "https://www.gojek.com/blog/gocar/pesan-gocar-di-bandara-soekarno-hatta/"
  logo: "/assets/images/projects/redpineapple/logo.png"
  tech: "Clojure, Ziggurat, Kafka, Redis Geo"

dev:
  title: "Jason Ganub"
  url: "https://github.com/arnolds/pineapple"
  year: "2020"

images:
  - image:
    url: "/assets/images/projects/redpineapple/devices.jpg"
    alt: "Red Pineapple website on tablet, mobile and desktop"
  - image:
    url: "/assets/images/projects/redpineapple/desktop.jpg"
    alt: "Red Pineapple website on a desktop device"
  - image:
    url: "/assets/images/projects/redpineapple/mobile.jpg"
    alt: "Red Pineapple website on a mobile device"
---
<p>Developed the Instant service for the Transport team. Instant is Gojek's alterantive allocation flow where customers and drivers connect via an in-person queue system using an OTP code. I lead the Instant product for features, improvements, and scaling new locations with above 90% code coverage. We also leveraged Redis's geo functionality to automatically react with notifications when driver supply is low.</p>