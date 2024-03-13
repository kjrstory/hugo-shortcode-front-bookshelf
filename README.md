# Hugo Front Bookshelf Shortcode

This Hugo shortcode allows you to display a front bookshelf on your site, showcasing books with their covers, titles, authors, and links to purchase or learn more. Inspired by [vijay verma’s site](https://vjy.me/book), this shortcode enhances your Hugo site with a visually appealing bookshelf, perfect for book reviewers, libraries, or anyone wanting to showcase a collection of books.

## Features

- Display book covers, titles, and authors in a visually appealing bookshelf layout
- Customizable for Tailwind CSS or Bootstrap projects
- Easy to integrate with any HugoBlox site
- Responsive design for all devices

## Prerequisites

Before you start, make sure your Hugo project is set up and running. This shortcode is compatible with HugoBlox sites using either Tailwind CSS or Bootstrap.

## Installation

1. **Create Shortcodes Directory**: If your project does not already have a `layouts/shortcodes` directory, create it.

    ```bash
    mkdir -p layouts/shortcodes
    ```

2. **Download the Shortcode**: Copy the `front-bookshelf.html` file into your `layouts/shortcodes` directory.

3. **Add CSS**:
    - For Tailwind templates, copy the `custom.css` file into your `assets/css` folder.
    - For Bootstrap templates, copy the `custom.scss` file into your `assets/scss` folder.

## Usage

To use the bookshelf shortcode in your blog post, insert the following into the front matter of your Markdown file:

```yaml
bookshelf_item:
  - cover_img: "URL_to_cover_image"
    cover_link: "URL_to_book_page"
```

Replace URL_to_cover_image, URL_to_book_page with the details of the books you want to display.

## Example
Here's an example of how to display a bookshelf with multiple books:

```yaml
bookshelf_item:
  - cover_img: "https://m.media-amazon.com/images/I/81TmnPZWb0L._SL200_.jpg"
    cover_link: "https://www.amazon.com/Dune-Chronicles-Book-1/dp/0441013597"
  - cover_img: "https://m.media-amazon.com/images/I/91Mv6oCERWL._SL200_.jpg"
    cover_link: "https://www.amazon.com/1984-Signet-Classics-George-Orwell/dp/0451524934"
```
Add this to your post's front matter, and the shortcode will automatically generate a bookshelf displaying these books.


## Demo

Experience the HugoBlox Bookshelf Shortcode in action! Check out the [demo](https://hugoblox-demo.netlify.app/blog/demo-front-shortcode-bookshelf/). This live demo showcases how the bookshelf looks and behaves on a HugoBlox site, giving you a clear idea of its appearance and functionality.

## License
This shortcode is open-source and available under the MIT License. Feel free to fork, modify, and use it in your projects.

## Support
For support, please open an issue on the GitHub repository page.