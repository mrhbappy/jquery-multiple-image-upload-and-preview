# Multiple Image Upload And Preview

![GitHub](https://img.shields.io/github/license/mrhbappy/jquery-multiple-image-upload-and-preview)

A simple JavaScript functionality to preview images before uploading. It allows users to select multiple and single image files using an `<input>` element of type "file" and displays a preview of each selected image along with a remove button.

## Features

- **Image Preview**: Selected images are displayed as thumbnails before uploading.
- **Remove Image**: Users can remove selected images before uploading.
- **Dynamic Image Preview Container**: The preview container is created dynamically if it doesn't exist.

## Installation

1. Include jQuery library in your project.
2. Add the `image-input` class to your file input element (`<input type="file" class="image-input">`).
3. Include the provided JavaScript code in your project.

```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="script.js"></script>



Usage
Call the imageUpload method on the .image-input selector to initialize the functionality.
$('.image-input').imageUpload();

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
This project is inspired by similar projects and utilizes jQuery library.




