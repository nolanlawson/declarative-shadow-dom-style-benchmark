# declarative-shadow-dom-style-benchmark

This is a browser benchmark of loading 100 declarative shadow roots, each containing `<link rel=stylesheet>`s for Bootstrap.css, plus some HTML markup, versus roughly the same thing using `<link>`s in the `<head>` and light DOM.

Usage:

    npx http-server -p 8080 # or your favorite HTTP server

Then navigate to http://localhost:8080/light-dom.html and compare to http://localhost:8080/shadow-dom.html.
