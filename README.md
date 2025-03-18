# gender-violence-lyrics-analysis
Analyzing gender violence language in Spanish, German, and Turkish hit songs.

This project analyzes the language of gender-based violence in hit song lyrics across Spanish, German, and Turkish music charts. The goal is to collect, clean, and analyze lyrics to identify linguistic patterns and differences across these languages.

# gender-violence-lyrics-analysis
Spotify & Genius API Integration

This project utilizes the Spotify API to retrieve song data and the Genius API to fetch corresponding lyrics. The goal is to seamlessly integrate both services for analyzing music and lyrics.


🚀 Getting Started

To use the Spotify and Genius APIs, follow these steps:

🔹 Step 1: Create a Spotify Developer Account

Sign Up or Log In:

Go to the Spotify Developer Dashboard.

Log in with your Spotify account or create a new one.

Set Up Your Developer Account:

Once logged in, familiarize yourself with the Spotify API documentation.

Create an Application:

Click Dashboard → Create an App.

Enter an App Name, Description, and a Redirect URI (e.g., http://localhost:8080).

Select the Web API option, agree to the Developer Terms of Service, and click Create.

Obtain API Credentials:

In your app's dashboard, go to Settings.

Copy your Client ID and Client Secret. These credentials will be used to authenticate your application.

🔹 Step 2: Create a Genius Developer Account

Sign Up or Log In:

Visit the Genius API Developer Page.

Log in or create a Genius account.

Register an Application:

Click New API Client.

Provide the required information (App Name, Description, Website URL, etc.).

Submit your application and wait for approval.

Obtain API Credentials:

Once approved, find your Access Token in the API dashboard.

🔹 Step 3: Environment Setup

To securely store API credentials, create a .env file in your project directory and add the following lines:

SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
GENIUS_ACCESS_TOKEN=your_genius_access_token

💡 Important: Never share your .env file or expose your credentials publicly!

🎉 You're Ready!

Now, you have successfully set up the required API access. You can start making API requests to fetch song data from Spotify and retrieve lyrics from Genius!

⚠️ Recommendations

Before running the full script, test if your credentials are stored correctly.

If any issues arise, double-check the .env file and API settings.

📌 Additional Resources

For more details, refer to the official API documentation:

Spotify API Docs

Genius API Docs

Enjoy exploring music data and lyrics with this integration! 🎶
