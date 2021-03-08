---
layout: project
permalink: /:title/
category: projects
date: 2020-04-21

meta:
  keywords: "Candor Feedback Service"

project:
  title: "Candor"
  type: "Gojek"
  url: "https://www.gojek.com/blog/gojek/fitur-laporan-perjalanan/"
  logo: "/assets/images/projects/gojek-candor/logo.jpg"
  tech: "Golang, Kafka, Config Store"
  description: "Candor is a feedback service we use to display feedback cards on the OTW screen. It allows customers to provide feedback for pickup location accuracy and any feedback for their trip. We built the forms in-house with various categories such as multiple choice, yes/no, and free form."
  impact: "We were able to take feedback from customers and make them actionable via Salesforce tickets automatically or data points for us to improve the operations. We were also able to take the service and platformize it for other teams such as for the Transport Pickup Experience team which allowed them to request customers to give feedback on their pickup location's accuracy. This is very valuable data so Places Of Interest (POI) can be corrected to have the actual lat/long points."

dev:
  title: "Jason Ganub"
  url: "https://github.com/jasonganub"
  year: "2020"

images:
  - image:
    url: "/assets/images/projects/gojek-candor/screenshot-1.jpg"
    alt: ""
  - image:
    url: "/assets/images/projects/gojek-candor/screenshot-2.jpg"
    alt: ""
---
<p>I created Candor with my colleague and platformized it for other teams within Gojek as a feedback service. We also integrated it with Salesforce so that critical feedback would raise a ticket between our customer care unit and the customer to resolve.</p>