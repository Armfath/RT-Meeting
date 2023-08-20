# RT-Meeting (RT-Meet)

RT-Meeting is an open-source WebRTC-based video conferencing app powered by Next.js and Nest.js. It allows users to host and join real-time video meetings with ease.

## Table of Contents

- [Features](#features)

- [Technologies](#technologies)

- [Installation](#installation)

- [Usage](#usage)

- [License](#license)

## Features

- Real-time video conferencing using WebRTC technology

- Host and join video meetings

- Instant messaging during video calls

- Mute and unmute audio during calls

- Enable and disable video streaming

- Responsive user interface for different devices

- Minimalistic design for intuitive use

## Technologies

This project follows a monorepo structure managed by Monorepo Turbo. It includes the following packages and apps:

- `server`: A Nest.js backend server

- `client`: A Next.js frontend app

Each package/app is written in TypeScript.

## Installation

To run RT-Meeting locally, follow these steps:

1. Clone the monorepo:

```sh

git  clone  git@github.com:Armfath/RT-Meeting.git

cd  RT-Meeting

pnpm  install

pnpm

```

2. Install dependencies for both packages:

```sh

pnpm  install

```

## Usage

To start the development servers, run the following command:

```sh

pnpm  run  dev

```

Once the development servers are running, open your web browser and visit [http://localhost:3000](http://localhost:3000) to access RT-Meeting.

## License

RT-Meeting is released under the MIT License.
