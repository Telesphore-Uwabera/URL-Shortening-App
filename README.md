# URL Shortener

## Introduction
This is a simple web-based URL shortener application. It allows users to input long URLs and get shortened versions of those URLs. The application also keeps track of the user's recent shortened URLs for easy access.

## Features
- Shorten long URLs to a more manageable format.
- Display the recently shortened URLs.
- Save recent URLs to browser storage for easy retrieval.

## Technologies Used
- HTML: For creating the structure of the web page.
- CSS: For styling the web page.
- JavaScript: For handling user interactions and making API requests.
- [shrtco.de API](https://shrtco.de/docs/): For URL shortening functionality.
- Local Storage: For saving and retrieving recent shortened URLs.

## How to Use
1. Enter a long URL in the input field.
2. Click the "Shorten" button to generate a shortened URL.
3. The shortened URL will be displayed on the page, and it will be saved in the recent URLs list.
4. You can view your recent shortened URLs on the page.

## Configuration
You can adjust the number of recent URLs to display by changing the `MAX_RECENT_URLS` variable in the JavaScript code.

```javascript
const MAX_RECENT_URLS = 5; // Adjust the number of recent URLs to display
```

## Installation
There is no installation required for this web application. Simply open the `index.html` file in a web browser to use it.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
[Your Name]

## Acknowledgments
- The [shrtco.de API](https://shrtco.de/docs/) for providing URL shortening services.
- Inspiration and guidance from various online tutorials and resources.

This is the link to my shortening-App https://telesphore-uwabera.github.io/URL-Shortening-App/
