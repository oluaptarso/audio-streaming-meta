# Audio Streaming

Audio Streaming is an application developed for testing/learning purposes.
<br />

The web application has three core functionalities:
- Fetch and display the available music from the API;
- The player, which allows the user to play, pause, mute/unmute, and control the time;
- Control the playlist, adding, removing, and reordering the music on the playlist.

The API has two core endpoints:
- List the available music;
- Streaming music.


You can check the working version [here](https://audio-streaming.paulotarso.dev).

## Meta repository

This meta[¹](#meta) repository manages the multi-project web application.

## Projects

### **[audio-streaming-api](https://github.com/oluaptarso/audio-streaming-api)**:
Backend REST API project, developed with [Nest](https://nestjs.com)

### **[audio-streaming-web-app](https://github.com/oluaptarso/audio-streaming-web-app)**:
Frontend web application project, developed with [Next.js](https://nextjs.org)

## Requirements
- Node.js - 16.18.1;
- npm - 8.19.2.

Visual Studio Code is optional but is highly recommended.

## How to install
Install meta using npm or yarn:

```bash
npm i -g meta
# or
yarn global add meta
```

Clone the meta and children repositories using git meta:

```
meta git clone https://github.com/oluaptarso/audio-streaming-nestjs-react-redux
```

Install the meta project dev dependencies:
```
cd audio-streaming-nestjs-react-redux
```
```bash
npm install
# or
yarn
```

Install the dependencies of the projects:
```bash
meta-npm install
# or
meta-yarn install
```

## How to run using docker
```bash
docker compose up
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Running/Debugging using Visual Studio Code

There are four launch configurations to debug in VS Code, one for the API:
- API (NestJs): Debug server

And three options for the web application:
- WebApp (Next.js): Debug server-side;
- WebApp (Next.js): Debug client-side;
- WebApp (Next.js): Debug full stack.



## Additional information

The music used in this project is from the [Riot Sessions](https://sessions.riotgames.com/en-us/event/sessions/).<br />
Sessions is a collection of music developed in partnership with a number of talented musicians that anyone can use in their content without concern of copyright strikes.

<a name="meta"></a>¹ - [meta](https://github.com/mateodelnorte/meta#readme) is a tool for managing multi-project systems and libraries.