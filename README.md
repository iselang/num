# Num. A Code Kit like ISE

## Introduction

Num is a powerful and lightweight web kit designed to complement the ISE language. It provides developers with essential tools and components for building efficient, scalable, and high-performance web applications.

## Features

-   **Lightweight & Fast** – Optimized for speed and performance.
-   **ISE Inspo** – Works seamlessly like ISE language.
-   **Modular Design** – Flexible components for a variety of web applications.
-   **Cross-Platform** – Works across all modern browsers.
-   **Extended Element Functionality** - Adds custom properties and methods to HTML elements for simplified DOM manipulation.
-   **Media Handling** - Provides functions for capturing and recording screen and camera feeds.
-   **Gesture and Keyboard Control** - Includes functions for swipe and keyboard press event handling.
-   **Accessibility and DOM Management** - Automated accessibility enhancements and DOM structure management.
-   **Data Storage and Retrieval** - Local storage manipulation with hexadecimal encoding.
-   **Network Requests** - Simplified GET and POST requests.
-   **File Handling** - Upload and save data with various file types.

## Installation

To install Num, use the following template as your base HTML:

```html
<!DOCTYPE html>
<meta ref="convert:num">
<head>
<link rel='preload' as="script" href='https://iselang.github.io/load.js'>
</head>
<body>
</body>
<script src="https://iselang.github.io/load.js"></script>
<script>
app('Name of my NUM');
</script>
```

## Core Functions


## Part (Components)

[Nav](part/nav.md)
-   A Top navigation

[Task](part/task.md)
-   A Task Bar / Bottom navigation

[Ask](part/ask.md)
-   a input / textarea version of Num.

[Tap](part/tap.md)
-   a button version of Num.

[Card](part/card.md)
-   A box for your info/ Card

[Preview](part/preview.md)
-   A Preview for like Card but scrollable

[Container / Box / Hero](part/cont.md)
-   A Container its where you put stuff some call this a box or hero.

[Slide / Courosel](part/slide.md)
-   A Slide like courosel


### Element Manipulation

-   **`pick(selector)`**: Selects an element using a CSS selector.
-   **`pick.all(selector, callback)`**: Selects all elements matching a CSS selector and optionally applies a callback function to each.
-   **`make(elementTag)`**: Creates a new HTML element.
-   **`load(link)`**: Dynamically loads JavaScript or CSS files.
-   **`path(url, state)`**: Manages URL paths and history.
-   **`prot.at(attr, value)`**: Sets or removes an attribute on an element.
-   **`prot.rem(name)`**: Removes an attribute from an element.
-   **`prot.put(atrg)`**: Appends content to an element.
-   **`move(etl, mot)`**: Moves one element into another.
-   **`move.up(selector)`**: Moves an element up in the DOM.
-   **`move.down(selector)`**: Moves an element down in the DOM.
-   **`element.set`**: Sets the content of an element, handling different input types.
-   **`element.get`**: Gets the content of an element.
-   **`element.put`**: Appends elements or text to an element.
-   **`element.say`**: Sets the text content of an element.
-   **`element.val`**: Gets or sets the value of an element.
-   **`element.at`**: Sets attributes on an element.
-   **`element.rem`**: Removes attributes from an element.
-   **`element.del`**: Removes an element from the DOM.
-   **`element.hide`**: Hides an element.
-   **`element.show`**: Shows an element.
-   **`element.toggle`**: Toggles the visibility of an element.
-   **`element.tap`**: Adds tap event listeners to an element.
-   **`element.ask`**: Adds an input event listener to an element.
-   **`element.do`**: Executes functions with optional delay or loop.
-   **`element.delay`**: Sets a delay for the `do` function.
-   **`element.loop`**: Sets a loop for the `do` function.
-   **`element.text`**: Gets or sets the inner text of an element.

### App Configuration

-   **`app(title)`**: Sets the document title.
-   **`app.cover(imageUrl)`**: Sets the cover image meta tags.
-   **`app.icon(iconUrl)`**: Sets the favicon.
-   **`fav(iconUrl)`**: Alias for `app.icon`.
-   **`app.key(keywords)`**: Sets the meta keywords.
-   **`app.url(canonicalUrl)`**: Sets the canonical URL.
-   **`app.info(description)`**: Sets the meta description.

### Utility Functions

-   **`copy(text)`**: Copies text to the clipboard.
-   **`uuid()`**: Generates a UUID.
-   **`ran(max)`**: Generates a random integer.
-   **`pop.up(url)`**: Opens a URL in a new window.
-   **`bit.set(address, value)`**: Sets a value in local storage like a memory using hexadecimal encoding.
-   **`bit.get(address)`**: Gets a value from local storage like a memory using hexadecimal decoding.
-   **`net.get(url)`**: Makes a GET request.
-   **`net.post(url, data)`**: Makes a POST request.
-   **`on.feed()`**: Opens a screen feed.
-   **`on.cam()`**: Opens a camera feed.
-   **`on.mic()`**: Opens a microphone feed.
-   **`off.feed()`**: Closes a screen feed.
-   **`off.cam()`**: Closes a camera feed.
-   **`off.mic()`**: Closes a microphone feed.
-   **`rec.start(target)`**: Starts recording a camera or screen feed.
-   **`rec.stop()`**: Stops recording a camera or screen feed.
-   **`snap(target)`**: Captures a snapshot from a camera or screen feed.
-   **`swipe.left(selector, callback)`**: Adds a swipe left event listener.
-   **`swipe.right(selector, callback)`**: Adds a swipe right event listener.
-   **`swipe.up(selector, callback)`**: Adds a swipe up event listener.
-   **`swipe.down(selector, callback)`**: Adds a swipe down event listener.
-   **`press(keyCombo, callback)`**: Adds a key press event listener.
-   **`num.accessibility()`**: Enhances accessibility by adding alt and aria attributes.
-   **`num.dom()`**: Manages the DOM structure, including doctype, lang, and viewport meta tags.
-   **`num.edit()`**: Enables content editing on elements with the 'ask' attribute.
-   **`num.link()`**: Links input elements to target elements.
-   **`num.tap()`**: Adds click event listeners to elements with the 'go' attribute.
-   **`num.js()`**: Executes JavaScript code from 'do' attributes or 'do' element content.
-   **`num.upload()`**: Handles file uploads.
-   **`num.save()`**: Saves element content as a file.
-   **`num.origin(url)`**: Sets the canonical URL.
-   **`func()`**: Executes all the ise functions.
-   **`num`**: empty function.

## Usage

Num provides a simple API to integrate with your web projects. Use the provided functions and components to build interactive and efficient web applications.

## License

Num is released under the MIT License. See `LICENSE` for more details.

## Contact & Support

For issues and inquiries, reach out via [GitHub Issues](https://github.com/iselang/num/).

Happy Coding with Num!
