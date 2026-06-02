# Web Development Sucks

Never been a big fan of web development. As someone who got into programming mostly as a result of learning you could mod Mario games on the Wii, I quickly came to appreciate the wonders of making things work efficiently for the hardware and keeping things simple. In web dev it seems to be the opposite?

*Disclaimer: This is mostly the view of an outsider to web development, and what puts me off of trying to get into this side of Computer Science.*

## Web Developers Love Abstractions

Now by default on all websites you have the option of HTML, CSS and maybe some JavaScript if you need it. This very website you are reading this on only makes use of HTML and CSS (for now), and I didn't feel the need for anything more (well, almost). Sure, this website isn't the most complicated thing ever. The lines that move across all the pages was probably the most complicated bit, but even then after reading enough stuff online and CSS documentation I eventually figured it out, and it looks nice enough in my opinion. And look, all the abstractions like React, Tailwind, Svelte, Angular, whatever the new hot one on the block is, I'm sure they have use cases once you get bigger and more complicated websites, but so often I see very simple websites being made with these large frameworks, and I just think what's the point? Computers and internet nowadays are fast and all but I'd rather reduce the strain on these things if possible?

And I'm not advocating for extreme optimisation in every area, because obviously that is a lot of time and effort for not much reward, but such low hanging fruit like just not using a web framework if not needed is such a big improvement. I know a lot of people go for these frameworks since they are meant to "improve the developer experience", but look, HTML and CSS is not that bad to write at a small scale.

## Abstracting without Hurting

Now when I said this website was written *purely* in HTML and CSS, I slightly lied. Yes the website you are on does only make use of that, but I made a small tool to convert markdown files into HTML files so I could write these blog posts (and reviews too) in a less verbose format. I believe this is called a Static Site Generator. You can check out the one I wrote [here](https://github.com/Randonlyh/Staticlyh). While I made my own, there are other already existing ones like [Jekyll](https://jekyllrb.com/) which are well maintained and popular (I only made my own one as a fun exercise). I bring this up because, I am technically doing what web developers love to preach in "improving the developer experience", but the difference here is that I'm not degrading the user experience in any way with my tool. In fact, it makes it better. It saves me copy pasting and taking longer to write out these posts, and I can basically guarantee the formatting looks right on every page, all while not sacrificing performance as it's just a pure HTML output.

If I were over-complicating the matter, I could try setting up a backend with a database that you could pull the latest posts from, but what would this actually solve? It would just make the pages longer to load and make things more annoying to setup and host. Sure it looks more impressive on a CV, or it's cooler to talk about how I used X technology to run Y website, but does it actually help the user at all? No.

## Conclusion or Something

I am basically writing this post to say hey, obviously it's important to make it easier to write up these sites, but be smart and selective about the abstractions and technologies you use. Not everything needs to have the tech stack of a multi-billion valued company, unless you actually are one.
