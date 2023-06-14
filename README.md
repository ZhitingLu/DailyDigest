# Daily Digest

The Daily Digest App is a web application developed in Go that utilizes the News API to provide users with access to a wide range of news articles. With this app, users can search for news based on specific keywords or topics, view article details, and stay up-to-date with the latest news.

## Features

- **News Search:** Enter keywords or topics of interest to search for relevant news articles.
- **Pagination:** Navigate through multiple pages of search results.
- **Article Details:** View detailed information about each news article, including title, author, description, source, and publication date.
- **Responsive Design:** Enjoy a seamless experience across different devices and screen sizes.

## Technologies Used

- Go: Backend development using the Go programming language.
- News API: Integration with the News API to retrieve news data.
- HTTP Requests: Utilizes the `net/http` package for making HTTP requests to the News API.
- JSON Parsing: Parses the response data from the News API using Go's built-in JSON encoding and decoding capabilities.
- HTML Templating: Renders dynamic HTML templates using the `html/template` package.
- CSS Styling: Applies CSS styling for an appealing user interface.
- Error Handling: Properly handles errors during API requests and data processing.

## Getting Started

To get a local copy of the Go News App up and running, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/ZhitingLu/DailyDigest/

2. Install dependencies:

   ```bash
   go mod download
   
3. Set up environment variables:

Rename the .env.example file to .env.
Replace the placeholder values in the .env file with your actual News API key and any other required configuration.

4. Build and run the application:

   ```bash
   go build -o DailyDigest

   ./DailyDigest

5. Access the app in your web browser:
   ```
   http://localhost:3000
