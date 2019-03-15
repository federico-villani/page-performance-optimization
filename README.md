# Page optimization 🤷‍

## Table of contents
  - **SEO** 🧐
    - being SEO compliant usually means you used the standards properly
  - **Framework development** / **VanillaJS** / **Custom development** 💀 ☠
    - detached frontend
    - cms theming
    - use built in functionality of the framework vs custom
    - one source of truth (unique)
    - one way data-flow
    - one way data-binding
    - single responsibility for functions/components    
  - **Best Practices** 🤓
    - Structure 
        - Lazy load
        - Critical Path and Render Blocking Resources (CSS + JS)
        - Avoid redirect and 404
        - Mobile first ?
        - first paint of the page vs content 
        - reduce http requests
    - JS
      - javascript modules
      - how to import external libraries
        - CDN
        - async js / defer
          ```<script async src="foobar.js"></script> ```
        - Move your scripts to the bottom of the page right before your </body> tag.
        - Concatenate your JS files into one file (with HTTP/2 this is no longer as important)
        - HTTP/2
      - Add/Remove event listener and bindings
      - Avoid infinite loops
      - Avoid unreachable code
    - CSS
      - concatenate your CSS files into one file
      - Use media queries to mark some CSS resources as non-render blocking
      - webfonts
      - iconfont/SVG vs immagini (icomoon) 
    - Server side  
      - Cache ( client and server side )
      - dns prefetch and preconnect
      - gzip/ file compression
      - SQL query opt  
  - **Minification / Uglify** 👹
    - drop_console, remove comments, uglify, .map files
    - concat css and combine media queries
    - image optimization ( manual and automatic )
  - **DevTools** 🤖
    - for testing purposes
      - Lighthouse/Audit
        - Mobile / Desktop
        - Audits Performances
        - Throttling
      - Performance tab
        - loading
        - scripting
        - rendering
        - painting
        - other 
        - idle
      - IDE code inspections
      - PageSpeed modules server side (apache/nginx)
      - SpeedTest tools online
        - [WebPageTest](https://www.webpagetest.org)
    - for development purposes
      - Dev/Production ENV & Build
        - .env files
      - Webpack/Parcel
      - Gulp/Grunt
      - Babel
      - ESLINT
  - **Extra** 🤟
    - [Thanos.js](https://thanosjs.org)


## Contributing


Feel free to send you own contribution to this repo.
Anyone is welcome to [contribute](.github/CONTRIBUTING.md),
however, if you decide to get involved, please take a moment to review
the [guidelines](.github/CONTRIBUTING.md):

* [Bug reports](.github/CONTRIBUTING.md#bugs)
* [Feature requests](.github/CONTRIBUTING.md#features)
* [Pull requests](.github/CONTRIBUTING.md#pull-requests)


## License

The code is available under the [MIT license](LICENSE.txt).
