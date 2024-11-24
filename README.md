# YouTube Clone (React)

This project is a YouTube clone built using React and powered by the YouTube Data API v3. It allows you to search for videos, view video details, and explore related videos, mimicking some of the basic features of the YouTube platform.

## Features
- Search for videos by query.
- View details of a selected video (such as title, description, and statistics).
- Display related videos based on a selected video.

## Tech Stack
- **React**: Frontend library for building the user interface.
- **Axios**: Promise-based HTTP client for making API requests.
- **TailwindCSS**: Utility-first CSS framework for styling.
- **YouTube Data API v3**: API used to fetch YouTube video data.

## Setup and Installation

### 1. Clone the repository
Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/your-username/youtube-clone.git
```
### 2.Install Dependencies
```bash
cd youtube-clone
npm install
```
### 3. Set up API Key

You’ll need a valid API key from the Google YouTube Data API v3. Follow these steps to obtain one:

- Go to the Google Cloud Console.
- Create a new project or select an existing one.
- Go to APIs & Services > Credentials.
- Create an API Key.
- Replace the API_KEY value in the src/api.js file with your API key.
