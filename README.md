# Spotify Clone

![Spotify Clone Screenshot](spotify_clone/spotify_image.png)

This project is a custom Spotify-like platform where songs are dynamically uploaded and displayed on the website. It leverages AWS services, a database, and an external API to manage and deliver a seamless user experience.

## Features
- **AWS S3 Integration**: Songs are stored in an S3 bucket for secure and scalable storage.
- **Lambda Functions**: Automatically upload songs to the website when added to the S3 bucket.
- **Database**: Tracks and stores metadata for songs, such as title, artist, and upload date.
- **External API Integration**: Provides additional functionality, such as fetching song details or integrating music-related data.
- **Dynamic UI**: A responsive web interface displays the uploaded songs in real-time.

## How It Works

1. A song is added to the AWS S3 bucket.
2. An AWS Lambda function is triggered by the S3 event, which:
   - Processes the uploaded file.
   - Extracts metadata.
   - Updates the database.
3. The website dynamically fetches and displays the new song using the API and database.

## Technologies Used
- **AWS Services**: S3, Lambda
- **Database**: [Specify Database Here]
- **External API**: [FastAPI]
- **Programming Language**: Python, SQL
