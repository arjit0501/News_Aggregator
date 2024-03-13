# News Aggregator

## Description
News Aggregator is a Django-based web application that integrates web scraping with web development. It scrapes articles from 'www.theonion.com' and stores them in a SQLite3 database. Users can access these articles through a user-friendly interface categorized into sections such as Entertainment, Sports, Politics, etc. The frontend, designed with HTML, CSS, and Bootstrap, allows for seamless navigation and sharing options via social media platforms.

## Features
- Web scraping of news articles from 'www.theonion.com'
- Storage of articles in a SQLite3 database
- Categorized presentation of articles (Entertainment, Sports, Politics, etc.)
- Responsive and user-friendly frontend interface
- Sharing options via Facebook, WhatsApp, Telegram, and copying to clipboard

## Tech Stack
- Backend: Python, Beautiful Soup, Django
- Frontend: HTML, CSS, Bootstrap
- Database: SQLite3

## Installation
1. Clone the repository:
git clone https://github.com/arjit0501/News_Aggregator
2. Install dependencies
   pip install -r requiremnets.txt
4. Run the application:
python manage.py runserver

## Usage
1. Navigate to 'www.theonion.com' news aggregator.
2. Explore different categories (Entertainment, Sports, Politics, etc.).
3. Share articles via social media or copy article links to clipboard.

## Screenshots
![Latest](/screenshots/latest.png)
![Entertainment](/screenshots/entertainment.png)
![Sports](/screenshots/sports.png)
![Politics](/screenshots/politics.png)
![Breaking News](/screenshots/breaking_news.png)
![Opinion News](/screenshots/opinion_news.png)

## Credits
- Built by [Arjit Bhammu](https://github.com/arjit_0501)

## License
This project is licensed under the [MIT License](LICENSE).
