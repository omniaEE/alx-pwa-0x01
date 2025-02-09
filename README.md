## API Overview

The Open Movie Database OMDb API.
The OMDb API is a RESTful web service to obtain movie information

## API Version

Version 1

## Available Endpoints with Request and Response Format:

- Search for Movies
  http://www.omdbapi.com/?s=SEARCH_TERM&apikey=YOUR_API_KEY

- Get Movie Details by IMDb ID
  http://www.omdbapi.com/?i=IMDB_ID&apikey=YOUR_API_KEY

- Search by Title
  http://www.omdbapi.com/?t=TITLE&apikey=YOUR_API_KEY

- Filter by Year
  http://www.omdbapi.com/?s=SEARCH_TERM&y=YEAR&apikey=YOUR_API_KEY

- Filter by Type (movie, series, episode)
  http://www.omdbapi.com/?s=SEARCH_TERM&type=TYPE&apikey=YOUR_API_KEY

- Get Full or Short Plot
  http://www.omdbapi.com/?i=IMDB_ID&plot=full&apikey=YOUR_API_KEY

- Pagination
  http://www.omdbapi.com/?s=SEARCH_TERM&page=PAGE_NUMBER&apikey=YOUR_API_KEY

## Authentication

API Key:
An API key is required to use the OMDb API. You must include it as a query parameter in all requests.

## Error Handling

The OMDb API provides error messages in the response to help diagnose issues. Here's how errors are handled:

- Invalid API Key

  Message: "Invalid API key!"

- API Key Not Provided

  Message: "No API key provided!"

- Movie Not Found

  Message: "Movie not found!"

- Too Many Results

  Message: "Too many results."

- Request Limit Reached

  Message: "Request limit reached!"

- issing Required Parameters

  Message: "Something went wrong."
