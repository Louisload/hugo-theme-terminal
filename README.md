# Terminal Portfolio

![Terminal Portfolio](https://github.com/Louisload/hugo-theme-terminal-portfolio/blob/master/images/portfolio1.png?raw=true)

### Barebones demo - https://www.luisrodriguesalves.dev/hugo-theme-terminal-portfolio/
### Real life demo - https://hidden.land/portfolio

This is a fork of the amazing [Hugo theme named Terminal by panr](https://github.com/panr/hugo-theme-terminal).
It adds the possibility of showing a grid portfolio.

## How to Use
A portfolio works as any normal section would. Consider the example below, of a section called "portfolio" with three items:

```
- exampleSite
-- content
--- portfolio
---- _index.md
---- portfolio_item1.md
---- portfolio_item2.md
---- portfolio_item3.md
```

In the `\_index.md` file to your section, add the following to the header:
``isPortfolio = true`` 

Then, for each portfolio item, add an image to your static files. I recommend them being square as per the examples. Other resolutions might work too. Link the images to your portfolio items by adding the following to their header:
``portfolioCover = "path_to_image.png"``

If you want to add icons, add them to the header too:
``portfolioIcons=["icon1.svg", "icon2.svg", "icon3.svg"]``

I recommend getting icons from [SimpleIcons](https://simpleicons.org/)

Using the steps above, you can have as many portfolios in your site as you want. As an example, you could have a "Photography" section with photos and a "Drawings" with drawings.

## Sub sections
You can also organise your portfolio with subsections. Just add them as subfolders of the original section. For instance:
```
- exampleSite
-- content
--- portfolio
---- Mona Lisas
----- _index.md
----- portfolio_item1.md
----- portfolio_item2.md
----- portfolio_item3.md
---- Earrings
----- _index.md
----- portfolio_item1.md
----- portfolio_item2.md
----- portfolio_item3.md
```

![Terminal Portfolio with subsections](https://github.com/Louisload/hugo-theme-terminal-portfolio/blob/master/images/portfolio2.png?raw=true)

[Please visit the original fork page for the complete readme with the basic instructions of how to use the base theme.](https://github.com/panr/hugo-theme-terminal)