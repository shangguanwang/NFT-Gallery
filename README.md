# NFT-Gallery
Showcase my NFT Art Collection in Masonry Layout. You can check out it <a href="https://shangguanwang.github.io/NFT-Gallery/" target="_blank">live here</a>

## Why I built this:
I was at ETHDenver 2023 Conference, and I found people intrigued about what I do as an NFT art collector. Since one picture is better than a thousand words, I built this gallery to showcase my top pick NFT art collections. This is also a great opportunity to sharpen my HTML and CSS skills after completing the responsive web design course on freeCodeCamp.

## Reflection:
I started out by getting some inspiration from designer portfolio websites and art gallery websites. Throughout the process I learned there are couple popular gallery layouts and I decided to go with Masonry layout. Then I drawed the wireframe. On the top I want a website header with a one-line description below, the image layout section with 3 columns, and the footer section which includes my bio links. I also want to add a shadow effect which links to artists' bio when people hover over each NFT. 
One challenge I encountered is the overlay would sit on top of the video play button, so users cannot play the video. I had to create a separate class and adjust the overlay height and flex position to resolve that issue.
Another key challenge is that initially I wanted to use the mansory-layout.JS package, but I keep running into module import error. After spending couple hours on this, I decided to go with simple CSS grid, and it worked. Lesson learned here is the simplier the better. Don't be reliant on external packages, existing knowledge might already be sufficient.



