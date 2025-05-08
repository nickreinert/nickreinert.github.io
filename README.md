# Documentation

## Motivation + Inspiration
- I chose the simplest option of creating my own website but saw it as an opportunity to learn a lot more about html and css, as well as a good opportunity to make a website, something I've been thinking about
- Immanuel Wilkin's Webstite

## What Works
- Topnav
- Soundcloud player
- Some Formatting

## What Doesn't
- Certain Pages are blank... lol
- Some writing...
- Home page is boring
## Beginnings
- I started by looking at the racheldevorah.studio page and source code. I learned how to use topnav, breaks, and some simple formatting
- I wanted to implement my own font, so I figured out how to do so on google's font page, and they have direct code you can implement there for certain fonts. `<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link       href="https://fonts.googleapis.com/css2?family=Encode+Sans+Expanded:wght@100&display=swap" rel="stylesheet">` is the HTML and `.encode-sans-expanded-thin {font-family: "Encode Sans Expanded", sans-serif;font-weight: 100;font-style: normal;}` is the CSS.
- 

## Formatting
- I used ChatGPT a LOT for this. Starting with html with `<hr>`. I chose to do most of this in CSS because I wanted to my HTML to be mainly for what is literally there and not a lot of stylizing/formatting. Most of what I used ChatGPT for here was different variables. `.topnav a {margin-top: 10px;background-color: #000000;float: center;color: white !important;font-family: "Encode Sans", sans-serif;width: 40%;text-align: center;padding: 6px 10px;font-size: 20px;text-decoration: none;border: 1px solid #b50000; margin: 0;z-index: 1;}`
	`/*header spacing*/.header {
	display: flex;
	justify-content: space-between;`
## Embedding + Supplements
- I used ChatGPT to tell me how to implement the soundcloud players. It was really easy, you just have to go to the track and click share > embed, and there is direct code to put in your html. (iframe is used for embedding)`<iframe width="40%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1822302552&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/1nicksxlo" title="1nicksxlo" target="_blank" style="color: #cccccc; text-decoration: none;">1nicksxlo</a> · <a href="https://soundcloud.com/1nicksxlo/spring-pluggnb-samples-24-ft-alex-reid-rippnova-goyxrd" title="May Pluggnb Samples 2k24 (Feat. Alex Reid, Rippnova, Goyxrd)" target="_blank" style="color: #cccccc; text-decoration: none;">May Pluggnb Samples 2k24 (Feat. Alex Reid, Rippnova, Goyxrd)</a></div>`

## Biggest Struggles
- By far the biggest struggle for me was formatting. For so long I couldn't figure out how to make the topnav padding not overlap with the header and horizontal line I have. I had a long convo with ChatGPT, I figured out that it was an issue with the fact I was initially using `.topnav a` only, and not `.topnav`.
- Another hard thing for me was learning the difference between a variable in CSS that has a period first and one that doesnt. I eventually understood that whenever you have a period first, you are making a specific class that you need to call in the html, what I did for an alternate background image one navigation page was this: CSS `.body2 {background-image: url("AbstractPainting(red)GerhardRichter.webp");margin: 0px;}` HTML `<body class="body2">`
	
## Future
- More formatting and better writing on the actual website.
- Finishing the saxophone and sound design parts
- Animations..?
- Pictures of me
