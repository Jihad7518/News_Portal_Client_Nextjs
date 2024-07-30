# News Portal Client (Next.js)

## Overview
This repository contains the client-side application of the News Portal, built with Next.js. The client-side application offers a rich user experience for browsing news articles, searching for content, and viewing current headlines. 

## Features

### Homepage
- **Current Date and Logo:** Displays the current date and the news portal's logo prominently at the top.
- **Advertisement Section:** Dedicated area for displaying advertisements.
- **Navigation Bar:** A responsive navigation bar showcasing all news categories.
- **Current Headlines:** A dynamic slider showcasing the latest headlines.
- **Latest News Slider:** Automatically sliding section for the latest news articles.
- **Search Bar:** A search bar for users to find news articles by keywords.
- **Recent News:** A section displaying the most recent news articles.
- **Related News:** Shows related news articles when a specific article is clicked.
- **Popular News:** Highlights the most popular news articles based on user engagement.
- **Footer:** Contains communication links, social media icons, and other essential links.

## Project Structure
- **`pages/`**: Contains all the pages of the application.
  - **`index.js`**: The homepage of the news portal.
  - **`[category]/index.js`**: Dynamic category pages.
  - **`[news_id].js`**: News article detail pages.
  - **`_app.js`**: Custom App component for global styles and layout.
- **`components/`**: Reusable UI components.
  - **`Navbar.js`**: The navigation bar component.
  - **`Footer.js`**: The footer component.
  - **`NewsSlider.js`**: Slider component for latest and popular news.
  - **`SearchBar.js`**: Component for the search functionality.
- **`styles/`**: Contains global and component-specific CSS styles.
- **`public/`**: Static files like images and icons.

## Contributing
Feel free to contribute to the project by submitting issues or pull requests. For more information, please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or inquiries, please reach out to [mdjihad.ewu@gmail.com].

