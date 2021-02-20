# 🌐 giloliveira.net

## What is this?

This is the source code for my personal website. It is not the actual HTML/CSS that is running on the server, but rather the code that is used to generate the static pages using a static page generator.

## What technologies/services are you using?

- [**Markdown**](https://daringfireball.net/projects/markdown/) (.md files) for the website content.
- [**Wowchemy**](https://wowchemy.com) for the theme (Academic) and the website builder system.
- [**Hugo**](https://gohugo.io) for the static page generation.
- [**Netlify**](https://www.netlify.com) for building, hosting and CDN.

## How do you build the website?

The workflow of my website basically goes like this:

1. I edit the website content which is written in Markdown;
2. Commit the changes to this GitHub repo;
3. The commit triggers the Hugo website building script on Netlify;
4. The generated static website is deployed to the Netlify CDN.

## Are you paying anything for this?

Basically nothing... most of the software I am using is open-source and the services I use are all on their free tiers. The only thing I am actually paying for are the domain names.

## Am I being tracked when browsing your website?

Well......... the short answer is... yes, but it can be bypassed.

The website uses Google Analytics in order for me to have an idea of who visits the website. I am not the biggest fan of these kinds of services, but, unfortunately, the Wowchemy builder only natively supports Google Analytics and Microsoft Clarity. I went for Google's option because I am more familiar with it, but may consider switching to Microsoft in the future. I am also considering researching if there's a way to use a more privacy-friendly service.

Netlify *may* also be involved in tracking purely because I am relying on their CDN but I didn't research into that.

In the meantime, you can use a content blocker to block Google Analytics which probably will take care of any tracking concerns.
