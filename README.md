```markdown
# Image Processor Web Application

## Summary
This is a minimalistic web application designed to process and display images based on a URL query parameter. It defaults to a sample landscape image if no URL is provided. The application displays the image and its metadata, including the URL, dimensions, and MIME type.

## Setup
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/image-processor.git
   ```
2. Navigate to the project directory:
   ```bash
   cd image-processor
   ```
3. Open `index.html` in your preferred web browser to run the application locally.

## Usage
- To display a custom image, append `?url=YOUR_IMAGE_URL` to the URL when accessing the application.
  Example:
  ```
  http://localhost/index.html?url=https://example.com/photo.jpg
  ```
- If no URL is provided, the application will display a default landscape image.

## Code Explanation
- **HTML Structure**: The page consists of an `img` element for displaying the image and a `div` for metadata.
- **CSS Styling**: The styling is minimal for a clean, modern look, using flexbox for centering content.
- **JavaScript Logic**: The script extracts the URL parameter, loads the image, and displays its metadata. Error handling is included to manage invalid URLs.

## License
This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
```