# VideoStreamer-NodeMediaServer
[Front End Link](https://github.com/adnansadar/Video-Streamer-FrontEnd)
[Back End Link](https://github.com/adnansadar/VideoStreamer-Backend)
Node Media Server is an npm package required for live streaming our video

## Available Scripts

### `npm install`

Installs all the dependencies of the project.
To download NodeJS on your system if you already don't have it installed, you can download it from [here](https://nodejs.org/en/).

In the project directory, you can run:

### `npm start`
Runs Node Media WebSocket Server

### Install and Setup Open Broadcaster Software
Download and install it from [here](https://obsproject.com/)
Set up your display and audio output.
Open Settings->Stream ->service=custom, server=rtmp://localhost/live, stream key= 5(in my case) this is the key of the stream you are going to stream from, you can check the key of the stream from db.json in the [backend](https://github.com/adnansadar/VideoStreamer-Backend)
