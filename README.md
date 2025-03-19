# gender-violence-lyrics-analysis
This project analyzes the language of gender-based violence in hit song lyrics across Spanish, German, and Turkish music charts. The goal is to collect, clean, and analyze lyrics to identify linguistic patterns and differences across these languages.

# gender-violence-lyrics-analysis
Spotify & Genius API Integration

This project utilizes the Spotify API to retrieve song data and the Genius API to fetch corresponding lyrics. The goal is to seamlessly integrate both services for analyzing music and lyrics.

 Collaborators:
 - [ gpiren ](https://github.com/gpiren)
 - [ tedesco-g ](https://github.com/tedesco-g)


🚀 Getting Started

To use the Spotify and Genius APIs, follow these steps:

**🔹 Step 1: Create a Spotify Developer Account**

*Sign Up or Log In:*

 - Go to [Spotify Developer Dashboard](https://developer.spotify.com).

- Log in with your Spotify account or create a new one

*Create an Application:*
- Click Dashboard → Create an App.
- Enter an App Name, Description, and a Redirect URL (e.g., http://localhost:8080).
- Select the Web API option, agree to the Developer Terms of Service, and click Create.

*Obtain API Credentials:* 
- In your app's dashboard, go to Settings.
- Copy your Client ID and Client Secret.

**🔹 Step 2: Create a Genius Developer Account**

*Sign Up or Log In:*
- Visit the [Genius API Developer Page](https://docs.genius.com).
- Log in or create a Genius account
- Register an Application
- Click New API Client
- Provide the required information (App Name, Description, and a Redirect URL (e.g., http://localhost:8080)).

*Obtain API Credentials:*
- Once approved, navigate to your app settings.
- Copy your Client ID and Client Secret.

**🔹 Step 3: Environment Setup**

To securely store API credentials, create a .env file in your project directory and add the following lines:

SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
GENIUS_ACCESS_TOKEN=your_genius_access_token

*Install Required R Packages:*
Before making API requests, install the necessary R packages:

install.packages(c("httr", "jsonlite", "dplyr", "dotenv"))
library(httr)
library(jsonlite)
library(dplyr)
library(dotenv)

*Load API Credentials in R*
Your .Rmd file will use the .env file to load credentials securely
_run these in an R chunk_
load_dot_env()
spotify_client_id <- Sys.getenv("SPOTIFY_CLIENT_ID")
spotify_client_secret <- Sys.getenv("SPOTIFY_CLIENT_SECRET")
genius_access_token <- Sys.getenv("GENIUS_ACCESS_TOKEN")


Enjoy exploring music data and lyrics with this integration! 🎶
