# Comments

## Notes on MP1-D




## Notes on MP1-C

Very good work here getting the mobile setup in place. Keep pushing to ensure the appropriate content styles take place at the large stops too. A few areas to push on more:

* Font weight sometimes needs to be pushed thinner than your comp in order to achieve the desired appearance. 
* font size on the "buy tickets" button can be matched closer. here remember that if you have 1.4em on the `p` and then make the inner `a` 1.8 you're actually making it 1.8 &times; 1.4, resulting in a larger size than desired. To achieve the desired size you need to either change the `a` to the correct ratio (1.8/1.4 is ~1.29) or just set the outer `p` to `1.8` with a class and don't put size on the `a`. Hope this makes sense...
* Should your `h2` elements have a little kerning or am I just reading into the comp more than is there? I see that Inspect didn't show any kerning modified but the letter spacing looks a little more gracious in your comp than in the browser.

## Notes on MP1-B

Great markup overall here. A few things to tweak:

* Consider using `<header>` for the `.title` element rather than `<div>`.
* If you want a container for your main content area, the new `<main>` tag is a good one to use instead of the more ubiquitous `<section>`. To that point, you can also consider moving the opening of this element below the `.title`.