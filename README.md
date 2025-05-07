<link rel="preload" as="style" href="https://actwu.github.io/md2.css">
<link rel="stylesheet" href="https://actwu.github.io/md2.css">

[` NUM JS `](https://github.com/iselang/iselang.github.io/blob/main/num.js) [` Part `](https://github.com/iselang/num/tree/main/part) [` Samples `](sample.md)
[` Github `](https://github.com/iselang/num/)

[` Icon `](https://fontawesome.com/search?o=r&ic=free&s=solid)


# [Num](https://iselang.github.io/num)[` .txt? `](rm.txt)

# Num. A Code Kit by ISE Team.

## Introduction

Num?, It's programming language that runs on the fly.. like no installation needed. It's fast, user-friendly, and built with dynamic UX in mind.. it is a powerful and lightweight code kit designed to complement like the ISE language. It provides developers with essential tools and components for building efficient, scalable, and high-performance web applications.


## NOTE
- This is half open source.
- This is a CDN-Based Language.


[Benchmark it.](https://pagespeed.web.dev/analysis?url=https%3A%2F%2Fiselang.github.io%2Ftest.html)

## Using it / Installation 

To install Num, use the following template as your base.
```html
<!DOCTYPE html>
<meta ref="convert:num">
<head>
<link rel='preload' as="script" href='https://cdn.jsdelivr.net/gh/iselang/iselang.github.io@main/num.min.js'>
</head>
<body>

</body>

<script src="https://cdn.jsdelivr.net/gh/iselang/iselang.github.io@main/num.min.js"></script>
<script>
load("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css")
load('num/ux.js');load('num/ui.css');
app('Name of my NUM');
</script>
```

## Recommendations
1. Never use `INNER HTML` num is not HTML, plus `innerHtml` is unsafe. use `.set`
2. Never use HTML default elements. Its because html only works on web. NUM elements is cross platform UI, Pleaee use that only.


## How it works

1. JavaScript’s Three-Phase System

NUM operates within JavaScript’s existing structure.. the Prototype Phase, the Mainframe Phase, and the Interpretation Phase.

In the Prototype Phase, NUM extends JavaScript’s prototype-based inheritance, adding custom methods to objects and making it easier to manipulate the DOM, handle events, and interact with the system.

During the Mainframe Phase, users interact with core application functionalities like the DOM, conditional logic `if()`, and event-driven programming. NUM simplifies this phase with an easy-to-use API that works directly with the browser’s environment.

In the Interpretation Phase, NUM runs directly in the browser or is interpreted by the system, allowing dynamic execution of code without needing complex dependencies.

2. NUM + C for Native Integrations

NUM extends JavaScript’s capabilities by adding C for WebView functionality, enabling interaction with native components for advanced and performance-sensitive tasks.

Using C for WebView integration, NUM bridges web and native environments, letting developers create native applications with the WebView component. This makes NUM suitable for cross-platform mobile apps and desktop environments that require native functionality.

NUM also provides native control, allowing access to native APIs and deeper interaction with the device's hardware or system-level features. C code runs efficiently, adding a layer of native functionality to the web-based interface.

3. Using [Median.co](https://median.co) for Android Compilation

NUM leverages Median.co for Android application compilation, providing a simple way to convert NUM code into Android-compatible applications.

Median.co compiles NUM code into native Android code, allowing you to deploy NUM-based applications on Android devices without the complexity of traditional Android development. You simply write NUM code, and Median.co handles the compilation.

After the code is compiled, the application runs natively on Android devices, taking full advantage of the platform's power while keeping the development process simple.

4. WebAssembly for Cross-Platform Compilation

NUM uses WebAssembly (Wasm) to compile code for native environments, allowing it to target platforms like Linux, Windows, and embedded systems. This ensures that NUM runs at near-native speed, while still offering the flexibility of a high-level language.

5. Full Cross-Platform Support

NUM simplifies building both web and native applications.

For web applications, NUM runs directly in the browser as a CDN-based language. It uses JavaScript for dynamic execution, manipulating the DOM, handling events, and offering a smooth user experience without complex setups.

For native applications, NUM uses C for WebView and Median.co for Android to compile apps for mobile devices and native desktop environments. This provides the performance of native apps while maintaining the simplicity of web development.

NUM also offers cross-platform compilation, enabling developers to write one codebase and compile it for different environments like web browsers, Android, or desktop using WebAssembly and Median.co.

6. Why Use NUM

NUM combines the best of both worlds.

For web development, NUM lets you write once and run anywhere. Its simple, modular design and CDN-based approach make it easy to develop cross-platform applications that work seamlessly in web environments.

For native applications, NUM lets you compile your code to run natively, offering the performance of native applications without sacrificing ease of use.

It results to being lightweight, fast, and optimized for both web and native environments, delivering smooth and responsive applications.


## Features

Modules you can load.

 - Num UI* (RECOMMENDED)
```js
load('num/ux.js'); load('num/ui.css');
```
 - Hardware (Like Camera, Mic, Screen Control, Keyboard, For now.. Soon is Servo.. Which is good for arduino, and more)
```js
load('num/sys/hardware.js');
```
 - Compiling (Make)
```js
load('num/sys/make.js');
```
 - Md
```js
load('num/sys/md.js');
```
 - Move (List)
```js
load('num/sys/move.js');
```
 - Network (Connect to wifi lol)
```js
load('num/sys/net.js');
```
 - Other
```js
load('num/sys/oth.js');
```
 - Swipe events
```js
load('num/sys/swipe.js');
```

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
-   **Auto UI** - Will generate a cdn / add a cdn for the respective ui element.
  
## Core Functions


## Part (Components)

[Nav](part/nav.md)
```html
<nav bol2 bbg>
</nav>
```
-   A Top navigation

[Task](part/task.md)
```html
<task bol2 bbg>

</task>
```
-   A Task Bar / Bottom navigation

[Ask](part/ask.md)
```html
<ask say="Input">
</ask>
```
-   a input / textarea version of Num.

[Tap](part/tap.md)
```html
<tap>
<say>Button</say>
</tap>
```
-   a button version of Num.

[Card](part/card.md)
```html
<cards>
<card bol2>Card 1</card>
<card bol2>Card 2</card>
<card bol2>Card 3</card>
<card bol2>Card 4</card>
<card bol2>Card 5</card>
<card bol2>Card 6</card>
</cards>
```
-   A box for your info/ Card

[Preview](part/preview.md)
```html
<previews>
<preview bol2>preview 1</preview>
<preview bol2>preview 2</preview>
<preview bol2>preview 3</preview>
</previews>
```
-   A Preview for like Card but scrollable

[Container / Box / Hero](part/cont.md)
```html
<cont>
<say big>Hero!</say>
</cont>
```
-   A Container its where you put stuff some call this a box or hero.

[Slide / Courosel](part/slide.md)
```html
<slides bol2>
<slide>Slide 1</slide>
<slide>Slide 2</slide>
<slide>Slide 3</slide>
</slides>
```
-   A Slide like courosel


### Element Manipulation

-   **`pick(selector)`**: Selects an element using a CSS selector.
-   **`pick.all(selector, callback)`**: Selects all elements matching a CSS selector and optionally applies a callback function to each.
-   **`make(elementTag)`**: Creates a new HTML element.
```js
mySay=make("say");
mySay.set="Hellow";
pick("MyTarget").put=mySay;
```
-   **`load(link)`**: Dynamically loads JavaScript or CSS files.
-   **`path(url, state)`**: Manages URL paths and history.
-   **`prot.at(attr, value)`**: Sets or removes an attribute on an element.
-   **`prot.rem(name)`**: Removes an attribute from an element.
-   **`prot.put(atrg)`**: Appends content to an element.
-   **`move(etl, mot)`**: Moves one element into another.
-   **`move.up(selector)`**: Moves an element up in the DOM.
-   **`move.down(selector)`**: Moves an element down in the DOM.

-   **`element.set=`**: Sets the content of an element, handling different input types.
-   **`element.get=`**: Gets the content of an element.
-   **`element.put=`**: Appends elements or text to an element.
-   **`element.say=`**: Sets the text content of an element.
-   **`element.val=`**: Gets or sets the value of an element.
-   **`element.at="Attribute='Value'";`**: Sets attributes on an element.
-   **`element.rem="Attribute='Value'";`**: Removes attributes from an element.
-   **`element.del=`**: Removes an element from the DOM.
-   **`element.hide;`**: Hides an element.
-   **`element.show;`**: Shows an element.
-   **`element.toggle;`**: Toggles the visibility of an element.
-   **`element.tap=`**: Adds tap event listeners to an element.
-   **`element.ask=`**: Adds an input event listener to an element.
-   **`element.do=`**: Executes functions with optional delay or loop.
-   **`element.delay=`**: Sets a delay for the `do` function.
-   **`element.loop=`**: Sets a loop for the `do` function.
-   **`element.text=`**: Gets or sets the inner text of an element.

### App Configuration

-   **`app(title);`**: Sets the document title.
-   **`app.cover(imageUrl);`**: Sets the cover image meta tags.
-   **`fav(iconUrl);`**:  Sets the favicon.
-   **`app.key(keywords),`**: Sets the meta keywords.
-   **`app.url(canonicalUrl);`**: Sets the canonical URL.
-   **`app.info(description);`**: Sets the meta description.

Sample
```js
app('My num app');
app.cover(2);

fav(24)
app.key('Apple Falling, Sus, Code');
app.url('localhost://'); // WHY proud hosting offline? if you can use github?
app.info('yeah my num app's info')
```


### Mya db integration

- **`bit.init()`**: Initializes IndexedDB, setting up the database and creating a `BroadcastChannel` for communication between tabs/windows.
- **`bit.up(name, data)`**: Stores or updates data in IndexedDB under the specified `name`. It also broadcasts the updated data to other tabs/windows using `BroadcastChannel`.
- **`bit.push(name, data)`**: Appends new data to the existing data stored in IndexedDB under the specified `name`. If no existing data is found, it creates a new array with the new data. It also broadcasts the updated data to other tabs/windows.
- **`bit.get(name)`**: Retrieves data from IndexedDB by the specified `name`. It returns the data from the IndexedDB or `null` if the data does not exist. If the data is a stringified JSON, it parses it before returning.

Sample

```js
await bit.init();

const data = { name: "John Doe", id: 123 };

await bit.up("user", data);

const newData = { name: "Jane Doe", id: 456 };
await bit.push("user", newData);

let userData = await bit.get("user");
console.log(userData); 
```

### Utility Functions

-   **`copy(text)`**: Copies text to the clipboard.
-   **`uuid()`**: Generates a UUID.
-   **`ran(max)`**: Generates a random integer.
-   **`pop.up(url)`**: Opens a URL in a new window.

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
-   **`func()`**: Executes all the setup functions.

-   **`make.file(Name, Type, Data)`**: Used to make you a file, and saves to your device.
```js
make.file(pick('#name').get,'text', pick('#data').get);
```

### Compilation / Making
-   **`make.PLATFORM`**: compilation to what platform you like `android`, `linux` and `windows`.

Sample
```js
make.linux();
```
Compiling a Portable App for linux this easy.


## Tested with Google tool

ISE & NUM has been tested by Google, FAR, Other team using [Google's](https://google.com) tools like

- **Language Test**
- **Code Test**
- **LightHouse**
- **Page Speed**

Results:

### Native + Web

**Performance** 
100% in a 12GB RAM test with only 100KB–20MB usage.

**Execution Speed** 
0.007s compile & interpret time.

**Load Speed** 
0.7s–12s across different setups.

**Optimization Score**
 11/11, 7/7, 3/3 across Google’s testing tools.

**UI and I.S** 
12points | 3 User Experience Range which is highest than other.

- **90-100%** in those tests.

![image](https://github.com/user-attachments/assets/d4b5f546-450e-4ea2-9909-2c8aaf63b3f3)

- **11/11 test passed**

![image](https://github.com/user-attachments/assets/d6d11e58-395f-4ade-a95d-5209a21e5604)
- **12-0.7ms** speed compilation and performance rate.
![image](https://github.com/user-attachments/assets/950bbda3-3656-48b6-86ad-a4f7f2380d29)
![image](https://github.com/user-attachments/assets/e24f0035-6aea-4517-8e45-d2597ef3ef5e)

### Latest Test

```csv
Test	NUM	ISE	NEXTJS	REACT
Performance Score	100%	100%	90%	87%
Compile Speed	100%	98%	70%	80%
Execution Speed	100%	100%	80%	75%
Load Speed	100%	100%	70%	85%
Optimization Score	100%	100%	80%	82%
UI and UX Score	100%	90%	90%	90%
Resource Efficiency	100%	100%	70%	86%
Consistency	100%	100%	90%	75%
Web Compatibility	100%	97%	100%	100%
```
| Test                | NUM  | ISE  | NEXTJS | REACT |
|---------------------|------|------|--------|-------|
| Performance Score    | 100% | 100% | 90%    | 87%   |
| Compile Speed        | 100% | 98%  | 70%    | 80%   |
| Execution Speed      | 100% | 100% | 80%    | 75%   |
| Load Speed           | 100% | 100% | 70%    | 85%   |
| Optimization Score   | 100% | 100% | 80%    | 82%   |
| UI and UX Score      | 100% | 90%  | 90%    | 90%   |
| Resource Efficiency  | 100% | 100% | 70%    | 86%   |
| Consistency          | 100% | 100% | 90%    | 75%   |
| Web Compatibility    | 100% | 97%  | 100%   | 100%  |


## Usage

Num provides a "simple" API to integrate with your web projects. Use the provided functions and components to build interactive and efficient software.

Ise / NUM
## Used by/in (projects)
`Actwu`, `NOW SIGN ASL protoype`, `HanBy`, `selhue.com`, `CDNM`, `covNav`, `sellit by selhue`, `dropBy`, `INSB`, `PallTe`, `Codeen`, `Far`, `LycheLi`, `Aftei`, `FloxUse`, `bio it`, `myURL`, `Again`, `Soiĺ`, `numOS`,`voltOs` and more..

## License

Num is released under the MIT License. See `LICENSE` for more details.

## Contact & Support

For issues and inquiries, reach out via [GitHub Issues](https://github.com/iselang/num/issues).

Happy Coding with Num!
