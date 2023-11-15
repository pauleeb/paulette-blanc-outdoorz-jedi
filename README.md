
# Project Title
OutdoorzJEDI

## Overview

What is your app? Brief description in a couple of sentences.

This is an application focused on well-being designed to connect people to activities outdoors and beneficial mental health practices. Outdoor activities have been shown to have a number of benefits for mental health, including reducing anxiety, stress, and depression. Mental health practices, such as mindfulness and meditation, can also be helpful for improving mental well-being. The app is designed to increase the amount of time people spend outdoors to positively impact their mental health by providing a platform for people to connect with activities outdoors and mental health practices. 

### Problem

Why is your app needed? Background information around any pain points or other reasons.

Many people today are struggling with their mental health or seeking to improve their overall well being. 

According to the National Institute of Mental Health, one in five adults in the United States experiences mental illness in a given year (1). There are many factors that contribute to poor mental health, including stress, anxiety, and depression.

Think about negative experiences that people have

Lack of information about local environment

Average American spends 5 or less hours outside in nature each week. ( 2)

Positive benefits of getting outdoors (3)

Providing activities for “bad weather” (disclaimer for being outdoors in dangerous conditions)

Using users’ activities to fund nature projects


### User Profile

Who will use your app? How will they use it? Any special considerations that your app must take into account.

This app will be an available tool for anyone who is looking for outdoor activities, to improve their mental health, or create a community for outdoor adventures. The app is easy to use and provides a variety of features that can help users to connect with activities outdoors and mental health practices. The app will be accessible on all devices that can access a web browser.

### Features

List the functionality that your app will include. These can be written as user stories or descriptions with related details. Do not describe _how_ these features are implemented, only _what_ needs to be implemented.

A list of outdoor activities that are available in the user's area and a gamified experience to increase motivation

A calendar of events that are related to outdoor activities and mental health that could be connected to one’s calendar

A library of resources and videos on topics such as stress relief, mindfulness, and positive psychology that can be done outdoors

A community forum where users can connect with others 

A tracking tool that users can use to monitor their progress and set goals

## Implementation
The app is a client-server application. The client-side of the app is written in NextJS, and the server-side is written in Node.js. The client-side app communicates with the server-side API using JSON. The server-side API is responsible for providing data to the client-side app, such as a list of outdoor activities, a list of local events, and resources and videos on mental health.

Data Management:The Well-Being App uses SQL to store data. 
Location Services: Mapbox or Apple Maps API will provide location services. Mapbox provides a variety of features that make it easy to add maps, directions, and search to the app. The app uses Mapbox to display a map of the user's area and to provide directions to outdoor activities.

### Tech Stack

List technologies that will be used in your app, including any libraries to save time or provide more functionality. Be sure to research any potential limitations.

NextJS
SQL Database
Mapbox: A mapping platform that provides a variety of features, including maps, directions, and search

### APIs

List any external sources of data that will be used in your app.

Weather API
Maps API
Self-created API/Database
Data on local events
OpenAI

### Sitemap

List the pages of your app with brief descriptions. You can show this visually, or write it out.

Home: The home section displays a list of outdoor activities that are available in the user's area.

Discovery: The activities section allows users to search for outdoor activities by location, type, and date.

Events: The events section displays a calendar of events that are related to outdoor activities and mental health.

Resources: The resources section provides users with access to articles and videos on topics such as stress relief, mindfulness, and positive psychology.


### Mockups

Provide visuals of your app's screens. You can use tools like Figma or pictures of hand-drawn sketches.

Mock up link: https://www.canva.com/design/DAF0LzJYfjk/FVOREgl4C5DXXmBKH_8vgg/view?utm_content=DAF0LzJYfjk&utm_campaign=designshare&utm_medium=link&utm_source=editor

### Data

Describe your data and the relationships between them. You can show this visually using diagrams, or write it out. 

Local outdoor events
User profiles

### Endpoints

List endpoints that your server will implement, including HTTP methods, parameters, and example responses.

The authorization component is development

### Auth

Does your project include any login or user profile functionality? If so, describe how authentication/authorization will be implemented.

The authorization component is development

## Roadmap

Scope your project as a sprint. Break down the tasks that will need to be completed and map out timeframes for implementation. Think about what you can reasonably complete before the due date. The more detail you provide, the easier it will be to build.


Task
Completion Date
Create application
11/14/23
Create database structure
11/18/23
Design structure
11/20/23
Write the code
11/23/23
Add data 
11/26/23
Test features
11/28/23



## Nice-to-haves

Your project will be marked based on what you committed to in the above document. Under nice-to-haves, you can list any additional features you may complete if you have extra time, or after finishing.
 
A personalized feed of activities and events that are based on the user's interests

A virtual reality experience that acts like a live tour guide that allows users to explore their current outdoor environments

A chatbot that can provide support and guidance to users


-------------------------------

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
