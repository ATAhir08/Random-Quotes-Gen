# Random-Quotes-Genrator


# Random Quotes Generator

## Overview

Welcome to the Random Quotes Generator project! This simple yet powerful application allows you to generate random quotes to inspire, motivate, or just add a touch of wisdom to your day. The project is designed to be easy to use, customizable, and suitable for integration into various applications or websites.

## Features

- **Random Quotes:** Get a random quote every time you run the generator.
- **Customization:** Easily customize the appearance and style of the generated quotes to match your application's design.
- **Easy Integration:** Integrate the Random Quotes Generator into your website or application with just a few lines of code.

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/random-quotes-generator.git
   ```

2. Open `index.html` in your web browser.

3. Enjoy a random quote!

## Configuration

You can customize the Random Quotes Generator by modifying the `config.js` file. Here are some of the available options:

- `quotesApiUrl`: The URL of the quotes API (default is a placeholder, replace it with a valid API URL).
- `backgroundColor`: The background color of the quote display.
- `textColor`: The text color of the quote.

Feel free to explore and adjust these settings to suit your preferences.

## Integration

To integrate the Random Quotes Generator into your website, include the following HTML snippet in your code:

```html
<div id="quote-container">
  <p id="quote-text">Loading...</p>
  <button id="new-quote-button">New Quote</button>
</div>

<script src="path/to/random-quotes-generator.js"></script>
```

Make sure to replace `"path/to/random-quotes-generator.js"` with the correct path to the script.

## Contributing

Contributions are welcome! If you have ideas for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to [Quotable API](https://api.quotable.io/) for providing a free and open API for retrieving quotes.

Happy quoting! 📜✨
