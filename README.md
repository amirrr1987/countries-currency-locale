# Locales List

A comprehensive list of locales and their respective currencies for various countries. This project provides a structured way to access country information using TypeScript.

## Table of Contents

- [Installation](#installation)

- [Usage](#usage)

- [Type Definitions](#type-definitions)

- [Countries Included](#countries-included)

- [Contributing](#contributing)

- [License](#license)

## Installation

You can install the package via npm:

```bash

npm  install  countries-currency-locale

```

```bash

[yarn or pnpm or bun] add countries-currency-locale

```

## Usage

Here's how to use the `localesList` in your TypeScript project:

```typescript
import { localesList } from "countries-currency-locale";

const countryInfo = localesList["iran"];

console.log(`Locale: ${countryInfo.locale}, Currency: ${countryInfo.currency}`);
```

## Type Definitions

The project defines the following TypeScript types for better type safety:

```typescript
export interface CountryInfo {
  locale: string;
  currency: string;
}

export declare const localesList: {
  [key: string]: CountryInfo;
};
```

### Countries Included

The following countries are included in the `localesList`:

Afghanistan, Albania, Algeria, Angola, Argentina, Armenia, Australia, Austria, Azerbaijan, Bahrain, Bangladesh, Belarus, Belgium, Belize, Benin, Bhutan, Bolivia, Bosnia and Herzegovina, Botswana, Brazil, Brunei, Bulgaria, Burkina Faso, Burundi, Cambodia, Cameroon, Canada, Cape Verde, Central African Republic, Chad, Chile, China, Colombia, Comoros, Congo (Brazzaville), Congo (Kinshasa), Costa Rica, Croatia, Cuba, Cyprus, Czech Republic, Denmark, Djibouti, Dominica, Dominican Republic, Ecuador, Egypt, El Salvador, Equatorial Guinea, Eritrea, Estonia, Ethiopia, Fiji, Finland, France, Gabon, Gambia, Georgia, Germany, Ghana, Greece, Grenada, Guatemala, Guinea, Guinea-Bissau, Guyana, Haiti, Honduras, Hong Kong, Hungary, Iceland, Indonesia, Iran, Iraq, Ireland, Israel, Italy, Jamaica, Japan, Jordan, Kazakhstan, Kenya, Kiribati, Kuwait, Kyrgyzstan, Laos, Latvia, Lebanon, Lesotho, Liberia, Libya, Liechtenstein, Lithuania, Luxembourg, Macedonia, Madagascar, Malawi, Malaysia, Maldives, Mali, Malta, Marshall Islands, Mauritania, Mauritius, Mexico, Micronesia, Moldova, Monaco, Mongolia, Montenegro, Morocco, Mozambique, Myanmar, Namibia, Nauru, Nepal, Netherlands, New Zealand, Nicaragua, Niger, Nigeria, North Korea, Norway, Oman, Pakistan, Palau, Panama, Papua New Guinea, Paraguay, Peru, Philippines, Poland, Portugal, Qatar, Romania, Russia, Rwanda, Saint Kitts and Nevis, Saint Lucia, Saint Vincent and the Grenadines, Samoa, San Marino, Saudi Arabia, Senegal, Serbia, Seychelles, Sierra Leone, Singapore, Slovakia, Slovenia, Solomon Islands, Somalia, South Africa, South Korea, South Sudan, Spain, Sri Lanka, Sudan, Suriname, Sweden, Switzerland, Syria, Taiwan, Tajikistan, Tanzania, Thailand, Timor-Leste, Togo, Tonga, Trinidad and Tobago, Tunisia, Turkey, Turkmenistan, Tuvalu, Uganda, Ukraine, United Arab Emirates, United Kingdom, United States, Uruguay, Uzbekistan, Vanuatu, Venezuela, Vietnam, Yemen, Zambia, Zimbabwe.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](link-to-contributing-guidelines) for details on the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](link-to-license-file) file for details.

### Key Sections:

1.  **Introduction**: Briefly explains the purpose of the project.

2.  **Installation**: Instructions for installing the package.

3.  **Usage**: Example code on how to utilize the `localesList`.

4.  **Type Definitions**: Overview of the TypeScript types used in the project.

5.  **Countries Included**: A complete list of countries available in the `localesList`.

6.  **Contributing**: Information on how others can contribute to the project.

7.  **License**: Information regarding the license for the project.

Feel free to adjust the package name, URLs, or any other details as per your project specifics! If you need more modifications or additions, let me know!
