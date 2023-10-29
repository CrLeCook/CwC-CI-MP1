<h1 align="center">Cooking with Craig - Milestone Project 1</h1>

[View the live project here](https://crlecook.github.io/CwC-CI-MP1/)

# MP1
To begin with, "Cooking with Craig" wasn't the first idea I had. Originally, I had the idea of a creating a fictional Cryptocurrency - whilst the scope of this assignment would've allowed me to focus on the subject matter, the ideas I had for it and the tools at my disposal didn't align and decided to put the idea on the shelf until more advanced technologies - such as JavaScript and/or Python - are involved.

Therefore, Cooking with Craig was born. The subject matter was flexible enough to make it personalised to my liking (I get to pick the recipes, yum) and implementing the various requirements wouldn't be too difficult. Essentially, I wouldn't be blinded by the websites contents.

## Purpose & Value
The purpose of the website is to provide the user the desired recipe as simply and easily as possible. The value of the website is the ease of use it provides. The colour scheme and font choice allow for a high level of readability. The navigation bar is simple, yet effective and the layout of the contents are easy to understand.

## Features
### Landing page gif
The custom made gif previews the 3 recipes the website offers, it's eye catching and let's the user know exactly what's being offered.

### CwC
Instead of having a useless Home page button on the home page, I replaced it with:
```HTML
<a class="nav-link disabled" href="#">
```
 ![image](/documentation/CwC_screenshot.png) 

Apart from the obvious explained above, I believe it makes the website appear more professional.

### Navigation Bar

Similarly, within the navigation bar I have implemented colour changes for mouseovers and used the same trick as above to prevent a link to the page the user is already on.

![image](/documentation/Nav_screenshot.png)

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

## Deployment

The website was coded in Visual Studio Code and was deployed to GitHub very early on. This was because I wanted to get used to using both as early as possible. Towards the end I published the website to GitHub Pages.

### VSC Extensions Used

-   [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - A code formatter
-   [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) - A development local server for checking code changes on the fly
-   [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) - Self-explanatory

## Issues Encountered

Apart from the regular beginner coding issues - an extra div or not closing out an element somewhere, the only real issue I encountered was when I deployed my website to GitHub Pages.

To begin with, none of my hyperlinks worked between pages. I read into the issue on StackOverflow and realised it is because I hadn't used the [Relative Path](https://www.w3schools.com/html/html_filepaths.asp). Once the Hyperlinks were fixed I realised my images had the same issue. These required ".." at the beginning of the source to tell the website the images folder is located one level above. The link above helped me resolve this.

## Testing

The website has been tested on:

- Firefox 119.0 (Windows)
- Google Chrome Version 118.0.5993.118 (Windows)
- Firefox 119.0 (Android) (see below)

![image](/documentation/android_screenshot.jpg)

## References

- [Landing Page GIF Maker](https://ezgif.com)
- [Nachos Image](https://www.allrecipes.com/thmb/D7DaS599F_3YYecHu0CK_MXHMMk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/1652036285Air20Fried20Quick20and20Easy20Nachos-2000-c55ba88542cc444e921569e06260c582.jpeg)
- [Nachos Recipe](https://www.bbcgoodfood.com/recipes/speedy-nachos)
- [Sunday Roast Recipe](https://www.kitchensanctuary.com/roast-beef-dinner/)
- [Sunday Roast Image](https://www.kimbersfarmshop.co.uk/blog-admin/wp-content/uploads/2021/10/shutterstock_53001679-scaled.jpg)
- [Chicken Tikka Image](https://static.onecms.io/wp-content/uploads/sites/43/2023/01/31/239867chef-johns-chicken-tikka-masala-ddmfs-3X4-0572.jp)
- [Chicken Tikka Recipe](https://www.allrecipes.com/recipe/239867/chef-johns-chicken-tikka-masala/)