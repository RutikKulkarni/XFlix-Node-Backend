# XFlix-Node

XFlix is a video sharing platform designed to host and share videos with the world. It facilitates video uploading through external links (e.g., from Youtube) and provides a seamless video playback experience.

## Live URL

- [Frontend](https://your-frontend-url.com)
- [Backend](https://xflix-node-teqb.onrender.com)

## Project Overview

During the development of XFlix, the following milestones were achieved:

- **Built XFlix Backend**: Developed the backend infrastructure using Node.js, Express.js, and MongoDB from scratch.
- **Implemented REST APIs**: Developed a set of 5 REST APIs to handle various functionalities of the platform.
- **Enhanced `GET /v1/videos` Endpoint**: Improved the `GET /v1/videos` endpoint to support features such as video title search, filtering by genres and content rating, and sorting by upload date or view count.
- **Utilized MongoDB**: Leveraged MongoDB for persisting video data, ensuring efficient storage and retrieval.
- **Full-stack Deployment**: Integrated the backend with XFlix frontend and deployed the full-stack application for public access.

## Scope of Work

The project scope included the implementation of the following REST APIs:

- `GET /v1/videos`: Retrieve a list of videos with various filtering and sorting options.
- `GET /v1/videos/:videoId`: Retrieve details of a specific video.
- `POST /v1/videos`: Upload a new video.
- `PATCH /v1/videos/:videoId/votes`: Update votes for a specific video.
- `PATCH /v1/videos/:videoId/views`: Update views count for a specific video.

## Skills Utilized

The development of XFlix involved the application of various skills, including:

- **Node.js**: Used for server-side scripting and backend development.
- **Express.js**: Employed to build robust and scalable APIs.
- **MongoDB**: Utilized as the database management system for storing video data.
- **REST API**: Designed and implemented RESTful APIs for communication between frontend and backend.
- **Postman**: Used for testing and documenting APIs during development.

## Images

![XFlix API contract in Postman](https://github.com/RutikKulkarni/XFlix-Node-Backend/assets/86470947/740699c5-a2f3-4d9b-9f34-f97b59c08b4d)

![Request variants supported by “GET /v1/videos” endpoint](https://github.com/RutikKulkarni/XFlix-Node-Backend/assets/86470947/99946a8d-e774-48c7-9741-66465e9e589d)

## Getting Started

To get started with XFlix, follow these steps:

1. Clone this repository.
2. Install dependencies using `npm install`.
3. Start the server using `npm start`.
4. Access the XFlix application through your web browser.
5. Use Postman or any other tool to interact
