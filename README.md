# tribute-page-project
A tribute page for freeCodeCamp Resposive WEeb Design module. The page features a responsive layout with centered images, a detailed biography, and a link to additional resources about her life and legacy.

## Tribute Page Overview

This **tribute page** is built with HTML and CSS to honor the life and work of **Nise da Silveira**, a trailblazer in the field of psychiatry and art therapy. It includes the following features:

- **Main Element**: Contains all the content with an `id="main"`.
- **Title and Description**: The page begins with a centered title and a brief description (`id="title"` and `id="description"`).
- **Image Section**: An image of Nise is displayed within a `div` (`id="img-div"`) with the image (`id="image"`) and a caption (`id="img-caption"`).
- **Tribute Information**: Detailed sections about her life and achievements are in the `#tribute-info` container, styled for readability.
- **Responsive Design**: The layout adapts using flexbox and max-width properties to maintain a clean look on all devices.
- **Link**: An external link (`id="tribute-link"`) is provided, opening in a new tab (`target="_blank"`), for more information on Nise da Silveira.

### CSS Styling

- **Flexbox Layout**: The `main` element uses `display: flex` and `flex-direction: column` for vertical alignment of content.
- **Responsive Images**: The `#image` is set with `max-width: 100%` and `height: auto`, ensuring it resizes based on the parent container.
- **Text Formatting**: Text is centered, with specific sections highlighted using `background-color: #eeeeee` for emphasis.
- **Navigation**: The footer includes a link to the freeCodeCamp course, styled with custom colors.
