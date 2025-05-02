# Documentation

## Beginnings
- I started by looking at the racheldevorah.studio page and source code. I learned how to use topnav, breaks, and some simple formatting
- I wanted to implement my own font, so I figured out how to do so on google's font page, and they have direct code you can implement there for certain fonts. `<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link       href="https://fonts.googleapis.com/css2?family=Encode+Sans+Expanded:wght@100&display=swap" rel="stylesheet">` is the HTML and `.encode-sans-expanded-thin {font-family: "Encode Sans Expanded", sans-serif;font-weight: 100;font-style: normal;}` is the CSS.
- 

## Formatting
- I used ChatGPT a LOT for this. Starting with html with `<hr>`, but I chose to do most of this in CSS because I wanted to my HTML to be mainly for what is literally there and not a lot of stylizing/formatting. Most of what I used ChatGPT for here was different variables. `.topnav a {margin-top: 10px;background-color: #000000;float: center;color: white !important;font-family: "Encode Sans", sans-serif;width: 40%;text-align: center;padding: 6px 10px;font-size: 20px;text-decoration: none;border: 1px solid #b50000; margin: 0;z-index: 1;}`
## Embedding + 

## Biggest Struggles
- By far the biggest struggle for me was formatting. For so long I couldn't figure out how to make the topnav padding not overlap with the header and horizantal line I have.
- Another hard thing for me was learning the difference between a variable in CSS that has a period first and one that doesnt. I eventually understood that whenever you have a period first, you are making a specific class that you need to call in the html, what I did for an alternate background image one navigation page was this: CSS `.body2 {background-image: url("AbstractPainting(red)GerhardRichter.webp");margin: 0px;}` HTML `<body class="body2">`