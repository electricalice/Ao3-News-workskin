Live example and tutorial for a news article extract that include website header, fake social media buttons, title and author of the article for you Ao3 fanfics. 

[Live Example here](https://archiveofourown.org/works/21974437)

It is quite easy to achieve. It requires 2 parts: HTML code and a workskin in css. 

# How to use it
**Set up a new work skin**
This is easy don't worry. Ao3 makes it really fast.
* Go to your **dashboard** on Ao3 and then on the right you'll find **"Skins"**. Click on there
* On the left there's a button **"Create site Skin"**
* Set the **Type** as **'Workskin'**, this is important!
* Add a title for you to remember it (something like 'News Article' should work fine)
* Now Scroll and copy paste  [this code](https://github.com/electricalice/Ao3-News-workskin/blob/master/workskin-code.css)  in the part labelled **"CSS"**
* Now press submit!
* This is it!
Now your workskin is set and if you want you can use it for multiple fanfic. You don't need to set it up multiple times!
**How to modify the article to your needs**
* The first thing to do should be to open your ao3 work and find the option **"Select Work Skin"** and find in the dropdown menu the workskin you just saved.
* Now go edit your fic (or fic chapter) and **copy paste** [this code](https://github.com/electricalice/Ao3-News-workskin/blob/master/article-code.html)  where you want to put the article
* Modifying should be fairly self-explanatory because I put comments on pretty much everything.
* If you want to remove any part of the article (newspaper logo, title, image of the author etc) **make sure to delete the part that is between the beginning and the end** of that part.
	* I made sure to mark all the parts, so if you want to remove the pic of the author you remove everything that's between `<!--Pic Autor-->` and `<!--End pic author-->`
	* It should be pretty straightforward.
* The Newspaper title has the option of having the **first letter bigger than the rest of the logo.** So insert the first letter between the <span> tags. Like this:
`<h1><span class="first-letter-big">N</span>ewspaper <span class="first-letter-big">L</span>ogo</h1>`
	* This can also e simply removed and your code can just be like this: `<h1>Newspaper Logo</h1>`
* Remember to insert the **url image in the Pic author**, instead of this: `http://insert-your-pic-url-here.jpg`. Please don't use gigantic images, it will just make the download of the page longer for your readership. The code will resize the image at 100px for 100px, so that size should be perfect.
* Write your fic article in its proper place! (Where it says `<!--start of the article-->` and before `<!--End of the article-->`)
And this is it. Be sure to preview your work, as something might have happened that made everything wonky!
