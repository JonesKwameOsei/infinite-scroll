# Infinite Scroll Project

This project implements an **infinite scroll** feature using the Unsplash API to dynamically load and display images as the user scrolls down the page. The application is built with **HTML**, **CSS**, and **JavaScript**.

## Features

- **Dynamic Image Loading**: Fetches random images from the Unsplash API and displays them on the page.
- **Infinite Scrolling**: Automatically loads more images when the user scrolls near the bottom of the page.
- **Loader Visibility**: Displays a loader while images are being fetched and hides it once all images are loaded.
- **Optimized Performance**: Uses event listeners and efficient DOM manipulation to ensure smooth scrolling and image rendering.

## Technologies Used

- **HTML**: For structuring the webpage.
- **CSS**: For styling the loader and layout.
- **JavaScript**: For fetching data from the Unsplash API, handling events, and dynamically updating the DOM.
- **Unsplash API**: For fetching high-quality random images.

## How It Works

1. **Fetching Images**:
   - The application uses the Unsplash API to fetch a batch of random images.
   - The API key is used to authenticate requests.

2. **Displaying Images**:
   - Images are dynamically added to the DOM using JavaScript.
   - Each image is wrapped in a clickable link that opens the image in a new tab.

3. **Infinite Scrolling**:
   - A `scroll` event listener checks if the user is near the bottom of the page.
   - When triggered, it fetches and displays the next batch of images.

4. **Loader**:
   - A loader is displayed while images are being fetched.
   - The loader is hidden once all images in the current batch are fully loaded.

## Project Structure

- **HTML**: Contains the basic structure of the webpage, including the container for images and the loader.
- **CSS**: Styles the loader and ensures a responsive layout for the images.
- **JavaScript**: Handles API requests, DOM manipulation, and event listeners for infinite scrolling.

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/infinite-scroll.git
   ```

2. Navigate to the project directory:

   ```bash
   cd infinite-scroll
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000/` to view the project.
