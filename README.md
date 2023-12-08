# Real Estate: Modern UAE Real Estate Website (Casaz)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Casaz is a state-of-the-art Real Estate website focused on providing a seamless and delightful experience for users exploring properties in the UAE. Built with cutting-edge technologies like Next.js, React.js, Chakra-UI, SSG (Static Site Generation), SSR (Server-Side Rendering), and powered by the Rapid API, Casaz is designed to redefine how users interact with real estate listings.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Development](#development)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Modern UI/UX:** Casaz offers a sleek and intuitive user interface, ensuring a delightful experience for users browsing real estate listings.

- **Dynamic Property Pages:** Each property has its own dynamically generated page for detailed information, utilizing the power of Server-Side Rendering (SSR) with Next.js.

- **Static Site Generation (SSG):** Benefit from fast loading times and SEO advantages with SSG, ensuring efficient delivery of static pages to users.

- **Chakra-UI:** The UI is designed using Chakra-UI, a simple, modular, and accessible component library for React.

- **Rapid API Integration:** Casaz leverages Rapid API for fetching real-time data, ensuring accurate and up-to-date property information.

## Getting Started

To get started with Casaz, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Oxygeeeen/real-estate.git
   cd real-estate
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables:**
   Create a `.env` file in the root of your project and add the following, replacing `[YOUR_API_KEY]` with your Rapid API key eg: `"b71bf074camsh74d8c0..."`:
   ```env
   RAPID_API_KEY=[YOUR_API_KEY]
   ```

4. **Run the Development Server:**
   ```bash
   npm run dev
   ```

   The development server will start at `http://localhost:3000`.

## Technologies Used

- [Next.js](https://nextjs.org/)
- [React.js](https://reactjs.org/)
- [Chakra-UI](https://chakra-ui.com/)
- [Rapid API](https://rapidapi.com/)

## Project Structure

The project structure follows best practices for Next.js applications:

```
real-estate/
|-- pages/
|-- features/
|-- lib/
|-- public/
|-- styles/
|-- ...
|-- README.md
|-- package.json
|-- ...
```

## Development

During development, you can use the following npm scripts:

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the production-ready application.
- `npm start`: Starts the production server.

## Deployment

This project can be deployed to platforms like Vercel or Netlify, ensuring a seamless deployment process.

### Environment Variables

In both local development and deployment, ensure you set the following environment variable:

- **Local Development:** Create a `.env` file in the root of your project and add the following, replacing `[YOUR_API_KEY]` with your Rapid API key:
  ```env
  RAPID_API_KEY=[YOUR_API_KEY]
  ```

- **Deployment:** Set the `RAPID_API_KEY` environment variable in your deployment environment.

## Contributing

Contributions are welcome! Please follow our [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
  
---

Feel free to adapt this template to your specific needs, and make sure to replace `[YOUR_API_KEY]` with your actual API key in the `.env` file.