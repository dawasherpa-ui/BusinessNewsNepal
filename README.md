# Business News Nepal - JSON Data Repository

This repository contains JSON data of business news articles collected daily from various sources. The data is structured and updated regularly to provide a reliable source of information for analysis, research, or other purposes.

## 📂 Available Data

The JSON files are organized by date and can be accessed via the following structure:

```
https://dawasherpa-ui.github.io/BusinessNewsNepal/news_<YYYY-MM-DD>.json
```

### URL Structure
- Replace `<YYYY-MM-DD>` with the desired date in the format `year-month-day`.
- Example for December 28, 2024:
  [news_2024-12-28.json](https://dawasherpa-ui.github.io/BusinessNewsNepal/news_2024-12-28.json)

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

