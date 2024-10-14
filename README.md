# countries-currency-locale

A TypeScript library that provides country-specific currency and locale information for various countries. This library aims to facilitate internationalization (i18n) in applications by providing easy access to country-related data.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Installation

You can install the package via npm:

```bash
npm install countries-currency-locale
```

## Usage

Import the library into your TypeScript or JavaScript project:

```typescript
import { localesList } from 'countries-currency-locale';

// Access information for a specific country
const iranInfo = localesList.iran;
console.log(iranInfo); // { locale: "fa-IR", currency: "IRR" }
```

## Examples

Here are some examples of how to use the `localesList` object to access country information:

```typescript
// Get currency and locale for Afghanistan
const afghanistanInfo = localesList.afghanistan;
console.log(afghanistanInfo); // { locale: "fa-AF", currency: "AFN" }

// Get currency and locale for Albania
const albaniaInfo = localesList.albania;
console.log(albaniaInfo); // { locale: "sq-AL", currency: "ALL" }
```

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to report a bug, please open an issue or submit a pull request on the [GitHub repository](https://github.com/amirrr1987/countries-currency-locale).

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

```

### Key Sections Explained:

1. **Title and Description**: Introduces your package and its purpose.
2. **Table of Contents**: Helps users navigate through the README quickly.
3. **Installation**: Provides instructions on how to install the package.
4. **Usage**: Shows how to import and use the library.
5. **Examples**: Offers specific examples of how to access and use country information.
6. **Contributing**: Invites users to contribute, with a brief guide on how to do so.
7. **License**: Specifies the license under which the package is released.

### Tips for Customization:
- Update the examples to include more specific information if your library expands or changes.
- Add any additional sections relevant to your package, such as FAQ or known issues.
- Ensure that the links to the GitHub repository and license file are correct.

Feel free to adjust the content as necessary to better match your project's specifics!