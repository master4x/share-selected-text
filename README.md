# ShareSelectedText.js
*forked from [VincentLoy/share-selected-text](https://github.com/VincentLoy/share-selected-text)*
*share selected text on twitter! Inspired by [medium.com](https://medium.com)*

![share selected text - ShareSelectedText.js](demo/sst.jpg)

VincentLoy made this small javascript library for his [personal blog](http://vincent-loy.fr), the existing 
libraries doesn't fit his needs, so he created [that](https://github.com/VincentLoy/share-selected-text) one.

ShareSelectedText.js modifeid version currently support the following social media services:
- twitter

*You can open an issue or follow [the contribution guidelines](https://github.com/VincentLoy/share-selected-text#contribution-guidelines) if you want to add another service or social media*

## Getting started

Add the CSS file in the `head` HTML closing tag.
```html
<link rel="stylesheet" href="dist/shareSelectedText.min.css"/>
```

Add the Javascript file before `body` HTML closing tag.
```html
<script src="dist/shareSelectedText.min.js"></script>
```

Then, you can init the plugin (change your username!):
```javascript
// plugin initialization with default options
    <script>
      shareSelectedText('.container', {
        buttons: ['twitter'],
        twitterUsername: 'your_name'
      });
    </script>
```

## Other Builds
- Original Build:[share-selected-text](https://github.com/VincentLoy/share-selected-text) by [@Vincent Loy](https://github.com/VincentLoy)
- Ruby on Rails engine: [share-selected-text_rails](https://github.com/WendyBeth/share-selected-text_rails) by [@WendyBeth](https://github.com/WendyBeth)

## Contribution Guidelines
Please contribute to the original Repo. 

## Changelog
*forked from commit cca6817 from 23/09/2019*

