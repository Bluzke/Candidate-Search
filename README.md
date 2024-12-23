# Candidate Search Application

## Description

This is a web application built with TypeScript that serves as a Candidate Search Tool. The goal of the project is to enable employers to efficiently review and shortlist candidates using data retrieved from the GitHub API. The application is designed to dynamically display candidate profiles and allow employers to save or skip candidates. It is responsive and user-friendly, providing smooth navigation between sections.

### Why

This application helps employers quickly identify potential candidates for open positions. By reviewing candidate details such as name, username, location, email, and GitHub profile, employers can evaluate candidates' qualifications and determine their suitability for a role.

### How

The app uses TypeScript for static typing and enhanced development experience, React for creating dynamic user interfaces, and CSS for styling. It fetches data from the GitHub API through an intermediate API built for this project. The application is deployed to Render for easy access.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Questions](#questions)
- [Links](#links)

## Installation

1. Open in terminal and run npm i && run build

2. run npm run dev

## Usage

Once the application is running, you can perform the following actions:

1. Candidate Review Page:
   - View a candidate's information, including name, username, location, avatar, email, GitHub profile link, and company.
   - Click the `+` button to save the candidate to the potential candidates list and view the next candidate.
   - Click the `-` button to skip the current candidate and view the next one.

2. Potential Candidates Page:
   - View a list of saved candidates with their detailed profiles.
   - If no candidates are available, an appropriate message is displayed.

3. Persistence:
   - The list of saved candidates persists across page reloads.

## Features

- Dynamic Candidate Profiles: Fetches and displays candidate data from the GitHub API.
- Saving and Skipping: Save candidates to a potential list or skip them as needed.
- Persistent Data: Saved candidates are stored locally and persist between sessions.
- User-Friendly Navigation: Seamless transition between the candidate review and saved candidates pages.

## Questions

For any questions, you can contact me via the following links:

- GitHub: [https://github.com/YourUsername](https://github.com/YourUsername)
- Email: your.email@example.com

## Links

GitHub URL: https://github.com/Bluzke/Candidate-Search

Render URL: https://candidate-search-1c4x.onrender.com/
