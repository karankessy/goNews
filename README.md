# GoNews - News Search Application

GoNews, a modern, responsive news search application built with Go and HTML/CSS. It provides a clean and intuitive interface for searching and browsing news articles from various sources.

## Features

- 🔍 Real-time news search functionality
- 📱 Responsive design that works on all devices
- 🎨 Modern and clean user interface
- 📄 Pagination support for browsing through results
- 🔗 Direct links to original news articles
- 🖼️ Article thumbnails and previews
- 📊 Result count and page information

## Prerequisites

- Go 1.16 or higher
- News API key (get it from [NewsAPI.org](https://newsapi.org))

## Installation

1. Clone the repository:
```bash
git clone https://github.com/karankessy/goNews.git
cd goNews
```

2. Install dependencies:
```bash
go mod download
```

3. Set up your environment variables:
Create a `.env` file in the root directory and add your News API key:
```
PORT=YOUR_Desired_PORT
NEWS_API_KEY=your_api_key_here
```

## Running the Application

1. Start the server:
```bash
go run main.go
```

2. Open your browser and navigate to:
```
http://localhost:3000
```

## Usage

1. Enter your search query in the search bar
2. Browse through the search results
3. Click on article titles to read the full story
4. Use the pagination controls to navigate through results

## Project Structure

```
goNews/
├── assets/
│   └── style.css
├── main.go
├── index.html
├── go.mod
├── go.sum
└── README.md
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Go](https://golang.org/)
- News data provided by [NewsAPI](https://newsapi.org)
- Inspired by [Freshman](https://freshman.tech/about/)
