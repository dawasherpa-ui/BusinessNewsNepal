# Business News Nepal - JSON Data Repository

This repository contains JSON data of business news articles collected daily from various sources. The data is structured and updated regularly to provide a reliable source of information for analysis, research, or other purposes.

##Extracts data every 6hrs interval

## 📂 Available Data

The JSON files are organized by date and can be accessed via the following structure:

```
https://dawasherpa-ui.github.io/BusinessNewsNepal/news_<YYYY-MM-DD>.json
```

### URL Structure
- Replace `<YYYY-MM-DD>` with the desired date in the format `year-month-day`.
- Example for December 28, 2024:
  [news_2024-12-28.json](https://dawasherpa-ui.github.io/BusinessNewsNepal/news_2024-12-28.json)

### Data Format
Each JSON file contains an array of news objects with the following structure:

```json
{
  "slug": "gold-price-rises-by-rs-400-per-tola-silver-up-by-rs-15",
  "title": "Gold price rises by Rs 400 per tola, silver up by Rs 15",
  "image": "https://cdn4.premiumread.com/?url=https://thehimalayantimes.com/thehimalayantimes/uploads/images/2024/12/27/36958.jpeg&w=1200&q=1080&f=jpg",
  "content": "The price of gold in the domestic market increased by Rs 400 per tola on Friday.",
  "longContent": "KATHMANDU, DECEMBER 27The price of gold in the domestic market increased by Rs 400 per tola on Friday.According to the Federation of Nepal Gold and Silver Dealers' Association, fine gold is now being traded at Rs 150,700 per tola, up from Rs 150,300 per tola on Thursday.Similarly, the price of silver also saw an increase of Rs 15 per tola. Silver, which was priced at Rs 1,800 per tola on Thursday, is now being traded at Rs 1,815 per tola.",
  "link": "https://thehimalayantimes.com/business/gold-price-rises-by-rs-400-per-tola-silver-up-by-rs-15",
  "timestamp": 1735290970291
}
```

### Fields Description
- **slug**: A unique identifier for the news article.
- **title**: The headline of the news article.
- **image**: URL to the article's representative image.
- **content**: A brief summary of the news article.
- **longContent**: Detailed content of the news article.
- **link**: URL to the original news article.
- **timestamp**: Unix timestamp of when the news was published.

## 🔄 Daily Updates

- News data is updated daily.
- As more sources are integrated, the quantity and diversity of the data will increase.

## 🛠️ Usage

You can use these JSON files in your applications or projects by fetching the data using the provided URLs. Here is a quick example using JavaScript:

```javascript
fetch('https://dawasherpa-ui.github.io/BusinessNewsNepal/news_2024-12-28.json')
  .then(response => response.json())
  .then(data => {
    console.log(data); // Process the news data here
  })
  .catch(error => console.error('Error fetching news data:', error));
```

## 🌐 Contributing

We welcome contributions! Here are a few ways you can help:

- Suggest new sources to include.
- Report issues or inaccuracies in the data.
- Share ideas to improve this repository.

## 📄 License

This project is licensed under the [MIT License](LICENSE). You are free to use the data and code for any purpose, as long as proper credit is given.

## 📧 Contact

For any inquiries or suggestions, please feel free to open an issue or contact us directly.

---

Thank you for using the **Business News Nepal** repository! We hope you find this resource helpful and valuable for your projects.

