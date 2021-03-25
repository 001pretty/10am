# 10 am

![Node Version](https://img.shields.io/badge/node-v12.16.2-green.svg) &nbsp;
![React Version](https://img.shields.io/badge/react-v16.14.0-blue.svg)<br/>

[Demo](https://tenam.herokuapp.com/) &nbsp; &nbsp; &nbsp; [Repository](https://github.com/777pretty/tenam)<br/>

![preview](https://github.com/001pretty/ixmusic/blob/main/ixmusic-preview.png)

**Description**<br />
💬 A simple chat application built with socket.io.

Application utilizes the MERN stack.<br />
Frontend is built with React.<br />
Backend is powered by Node and Express.<br />
Chat rooms, messages and users are being emitted with socket.io.<br />
<br/>

## Table of content

- [Features](#features)
- [Motivation](#motivation)
- [**Installation**](#installation)
- [Built With](#built-with)
- [Ideas for future releases](#ideas-for-future-releases)
- [License](#license)
- [Contact](#contact)

<br/>

## Features

- Create room
- User can add his name
- User can join room
- Users can send messages to each other
- Numerous rooms can exist separately in real-time
- Numerous users can chat with each other at the same time
- Notifications if other users have joined/left
- Chat messages are wiped when all users exit a room
- Relaxing theme
- Responsive/mobile-friendly

<br/>

## Motivation

The idea behind building this application was to practice aplicattions which emit data in real-time, from backend to frontend and other way around. For handling this I chose WebSockets library socket.io as it seemed one of the best at doing its job. As a theme for this application I chose coffee shop/wood/city/morning theme.

<br/>

## Getting Started

### Installation

To run application on your local machine follow these steps:

1. Clone or download the project from the [repository](https://github.com/777pretty/10am).
2. Install both backend and frontend dependencies with this one command:

   ```bash
   # with npm
   npm run iall

   # or with yarn
   yarn run iall
   ```

3. Start development mode with command:

   ```bash
   # with npm
   npm run dev

   # or with yarn
   yarn run dev
   ```

4. Run the application in the browser with url:
   ```javacript
   localhost:3000
   ```

<br />

## Built With

Frontend bootstrapped with create-react-app

**Backend dependencies**

- node
- express
- cors
- compression
- socket.io

**Frontend dependenceis**

- react
- react-dom
- query-string
- socket.io-client

<br/>

## Ideas for future releases

- User authentication
- Messages to save to database
- Room persistance
- User avatar
- Invite links
- Add room to favorite

<br/>

## License

This project is licensed under the [MIT License](https://github.com/001pretty/ixmusic/blob/main/LICENSE)

<br/>

## Contact

With any ideas or questions...

You can contact me via email: oliverzaj@gmail.com <br/>
Or fill the contact form at my [personal website](https://thezajac.com)
