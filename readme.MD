# Run NPM packages in the developers console in the browser

Great for testing, for example with cheerio (in this example). 
Just replace it with another package and install the package and run it again, to update the bundle!

# Installation

`npm install`  
`npm run serve`

Copy paste this to your developers console in the browser:
```
const script = document.createElement('script');
script.src = 'localhost:666/bundle.js';
document.body.appendChild(script);
```

# Blog

You can read my blog here: [Run NPM packages in the developers console](https://dev.to/wimdenherder/run-npm-packages-in-developers-console-on-any-site-2a78)