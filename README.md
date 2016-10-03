# You won't regret buying this
This is an experiment in fighting the paradox of choice. The philosophy is simple: we spend too much time and energy optimizing buying things we don't really care about. This site attempts to break that by presenting viewers with a single option that is good enough. It's not the best thing. It's not the cheapest thing. But it works and you won't regret buying it - so now you can move on with your life.

# I want to suggest something
Want to add a recommendation for something? Awesome!

It's pretty simple: all you really need is a Github account. You can do pretty much all of this from the Github website.

1. Fork this repository. If you don't know how to do this, look for the button labeled "fork" at the top of the page and click it. [Github also has some nice instructions on how to do it](https://help.github.com/articles/fork-a-repo/).

2. Go to the _posts folder, and create a new file. It must follow the naming convention `YYYY-MM-DD-ITEM-NAME.markdown`. For example, if you wanted to add a recommendation for an awesome spatula, you would create a file named `2016-10-01-spatula.markdown`.

3. Write your recommendation in the new file you just created. Follow this templating structure (note that the `short` property defines the hover text on the main page, so make it descriptive):  
   ```
   ---  
   layout: default
   title:  "YOUR TITLE"
   short: "SHORT DESCRIPTION OF THE ITEM"
   ---
   This is the first paragraph of description.
   
   This is the second paragraph of description.
   ```  

4. Add an image, if you want! Adding images is ever so slightly more complicated than adding text, but it's not too hard.
  * You need to upload your image to the `assets` folder. Give it a simple, descriptive name like `spatula.jpg`.
  * Add a link to your image in your recommendation file. Use this syntax: `![CAPTION]({{ site.github.url }}/assets/FILENAME.EXTENSION)`. For example, inserting a picture of a pen would work like this: `![a picture of a pen]({{ site.github.url }}/assets/pen.jpg)`.
  
5. Submit a pull request with your changes to the `gh-pages` branch. [Github has some instructions on how to do that](https://help.github.com/articles/creating-a-pull-request/).
