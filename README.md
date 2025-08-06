```
# Zoom Clone

Created by Ashwin Rustagi

## Introduction

This project is a feature-rich video conferencing application that replicates the core functionalities of Zoom. Built with Next.js and TypeScript, it allows users to securely log in, create and schedule meetings, and access a variety of in-call features like screen sharing and recording.

## Tech Stack

* Next.js
* TypeScript
* Clerk
* getstream
* shadcn
* Tailwind CSS

## Features

* **Authentication**: Secure user login and authorization via Clerk, supporting social sign-on and traditional email/password methods.
* **New Meeting**: Instantly start meetings with pre-join configuration for camera and microphone.
* **Meeting Controls**: Full control for participants, including recording, reactions, screen sharing, and participant management.
* **Scheduling**: Schedule meetings for a future date and time, with shareable links.
* **Meeting Lists**: View upcoming, past, and recorded meetings.
* **Personal Room**: A dedicated personal room with a unique, persistent meeting link for instant meetings.
* **Responsive Design**: A seamless user experience across all devices and screen sizes.

## Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:
* Git
* Node.js
* npm (Node Package Manager)

**Cloning the Repository**

First, clone the repository to your local machine. Replace the URL with the URL of your own GitHub repository once you've uploaded it.

git clone https://github.com/your-username/your-repo-name.git
cd zoom-clone

**Installation**

Install the project dependencies using npm:

npm install

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add your credentials from Clerk and Stream.

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=

**Running the Project**

npm run dev

Open http://localhost:3000 in your browser to view the project.

```
