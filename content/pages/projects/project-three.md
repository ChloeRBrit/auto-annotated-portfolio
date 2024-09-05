---
type: ProjectLayout
title: Web Application Dashboard
colors: colors-a
date: '2022-01-22'
client: Awesome client
description: >-
  It’s hard to imagine that I’ve that I wrote all this code by myself, probably
  because I worked with an entire team :) but they definitely followed my lead
  most of the time.
featuredImage:
  type: ImageBlock
  url: /images/opera_uj56CSawe2.png
  altText: Project thumbnail image
media:
  type: ImageBlock
  url: /images/opera_uj56CSawe2.png
  altText: Project image
bottomSections: []
---
The project involved developing a web-based dashboard for an animal shelter management system using the Dash framework within Jupyter notebooks. The main functionalities included data visualization, interactive filtering, and geolocation mapping of animal rescue data. MongoDB was chosen as the database backend due to its flexibility with JSON-like documents, which align well with Python's data structures.

This allowed seamless integration and efficient retrieval of data for display on the dashboard. The dashboard layout was designed using Dash's component-based architecture, incorporating components such as dash\_table. DataTable for displaying animal data, dcc. Graph for dynamic pie chart visualizations, and dl. Map for interactive geolocation mapping.![](https://preview--chloerbrit-930a6.stackbit.dev/images/opera_41PoCfSgDK.png) Callback functions were implemented to handle user interactions, updating the displayed data based on filters selected by the user. This included filtering animals based on rescue types like Water Rescue, Mountain/Wilderness Rescue, or Disaster Rescue, and dynamically updating charts and maps accordingly. Throughout the development process, challenges included ensuring smooth integration between Python and MongoDB, particularly with data retrieval and conversion using Pandas. Designing robust callback functions to maintain responsiveness and data consistency across multiple dashboard components was also a critical aspect. Testing was conducted locally to validate functionality, and the dashboard was deployed for further testing and use in managing animal rescue operations effectively. Overall, leveraging tools like JupyterDash, MongoDB, and the Dash framework facilitated the creation of a scalable and interactive dashboard for animal shelter management, enhancing operational efficiency and decision-making processes.
