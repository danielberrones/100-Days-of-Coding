# 100 Days Of Code - Log

### Day 1: April 25, 2020  - Saturday

**Today's Progress**: I spent time building a Survey Form for the Responsive Web Design Certification.  I learned how to use HTML fieldset, legend, and label tags better. I spent time understanding how the CSS box sizing property works.  I understood how to use the CSS box-sizing property.  It's good to use because you don't have to worry about an element's width or height changing if you adjust the border or padding.  So you set box-sizing to border-box to make sure the element's height and width stays the same.  

**Thoughts:** I feel like I need to improve on my ability to center things.  Whether it's a div, an image, some text, a heading, a video, a map --- literally anything.  I always to set the margin to 0 for the top/bottom and auto for left/right.  If it's a flex box you can set justify-content to center and align-items to center.  I have trouble remembering how to center an image so that it scales correctly when the viewport changes size. I will continue working on everything so I can remember it better when I code.  I can always quickly find the information that I need, but I wish I knew it instantly when I was coding.    

**Link to work:** [Survey Form](https://codepen.io/danielberrones/pen/KKpZoNx)


************************************************************************


### Day 2: April 26, 2020  - Sunday

**Today's Progress**: I used Font Awesome icons.  I learned more about Content Delivery Networks.  With just a simple link in the header tag, you can access pre-written pages of helpful CSS code.  I looked up info about Bootstrap and was amazed at how simple it is to put together a page.  I've been using inline CSS on occasion.  It's empowering to add the style directly into the HTML page instead of going back to the CSS document.  I'm still learning @media best practices.  They can be a little tricky!  I coded for about 3-4 hours today so I exceeded my 1 hour goal with ease.

**Thoughts:** I need to understand the Z-index better.  Some devs set it to 9999 while others set it to 1.  I had trouble getting some Font Awesome icons to render exactly how I wanted them to.  It was a bit frustrating and I kept checking to see if my CDN link had a typo in it.  I need to understand @media min/max width better.  I feel like some developers use min-width exclusively, whereas some chooser max-width.  I know it probably doesn't make much of a difference as long as your CSS is correctly written!  I'll continue coding more tomorrow.

**Link to work:** [Product Landing Page](https://codepen.io/danielberrones/pen/wvKdXmW)


************************************************************************


### Day 3: April 27, 2020  - Monday

**Today's Progress**: I used header, nav, ul, li, a, and div tags today.  I used both id's and classes for CSS.  I know that id's take precedence over classes.  I spent more time practicing @media queries to build mobile, and tablet versions of my sites.  I know that some developers prefer to build a mobile-responsive site first, then they scale up to tablet, desktop.  I personally like writing a desktop site first.  I grew up using desktop computer so maybe that's influencing my perspective.  I used top and left CSS properties today as well, but definitely need to practice them more.

**Thoughts:** I'm still working on the Product Landing Page for the Responsive Web Design Certification on [freeCodcamp.org](https://freeCodcamp.org).  I was hoping I would finish it today but it will have to wait until tomorrow.  I was getting frustrated with the CSS position property.  I spent time reading through MDN docs on the values: fixed/static/inherit/initial/relative.  Relative doesn't seem to make much sense to me, but I just need more practice.

**Link to work:** [Product Landing Page](https://codepen.io/danielberrones/pen/wvKdXmW)


************************************************************************


### Day 4: April 28, 2020  - Tuesday

**Today's Progress**:  I spent a lot of time trying to get my flexbox to work correctly with Font Awesome icons.  I used align-items, justify-content, and text-align and set them to center.  I'm getting very good with margin and padding property tweaks.  I can use Developer Tools in any browser with ease and comfort.  The more I look for CSS selectors, the better I get at being a web developer.  

**Thoughts:**  I think I underestimated flexboxes.  I'll spend more time with it tomorrow.  Overall, I am very pleased with my coding for today which I did for 2.5 hours total.

**Link to work:** [Product Landing Page](https://codepen.io/danielberrones/pen/wvKdXmW)


************************************************************************


### Day 5: April 29, 2020  - Wednesday

**Today's Progress**:  Great news!  I finished the Product Landing Page!  I still want to customize the CSS a little bit further.  I tried using <div id="page-wrapper"> and then I set the position to relative.  I can then next additional div tags into this "huge" wrapper.   

**Thoughts:**  I had fun with flexboxes today.  I understand the horizontal and vertical axis (justify-content and align-items).  

**Link to work:** [Product Landing Page](https://codepen.io/danielberrones/pen/wvKdXmW)


************************************************************************


### Day 6: April 30, 2020  - Thursday

**Today's Progress**:  I spent another 3 hours coding today.  I kept tinkering with flexboxes, margin, padding, align-items, justify-content.  I understand why devs use this code (and that makes me happy!)

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

**Thoughts:**  I am glad that I finished another coding challenge on www.freecodecamp.  I set the side nav to position: fixed;, and height:100%;  (I have been loving the power of CSS.  I plan to read about the box model tomorrow and global variables.)

**Link to work:** [Technical Documentation Page](https://codepen.io/danielberrones/pen/bGVodzG)


************************************************************************


### Day 7: May 1, 2020  - Friday

**Today's Progress**:  I went back and worked on the Tribute Page.  I chose to write about William James.  I put the entire page into a main tag with an id of "main".  It seems redundant to write my code like that, but I'm sticking with best practices... for now :)  I used the strong tag to make the years bold.  I wrapped them all in li tags.  I also used something like this:

<figure id="img-div">
<img id="image" />
<figcaption>My figcaption</figcaption>
</figure>

It was very helpful to wrap everything in that figure tag.  I'll continue using figure, img, and figcaption moving forward.

**Thoughts:**  I forgot that I had skipped the Tribute Page when I got to this section a few weeks ago.  Since I worked on the more complicated challenges first, finishing this one was relatively easy.  I had spacing issues that I had to tweak with line-height, margin, and padding properties.  I am also getting comfortable using px,rems, and vh.

**Link to work:** [Tribute Page](https://codepen.io/danielberrones/pen/KKdXQep)


************************************************************************


### Day 8: May 2, 2020  - Saturday

**Today's Progress**:  I'm starting to really excel at manipulating flexboxes.  To get started you'll want to creat a parent container.


.parent-container{
    display:flex;
    flex-direction:row;
    flex-wrap:wrap;  
}


Once you have a similar layout like that, you can start customizing the items you place into it.  It's a powerful feature.  

**Thoughts:**  I am getting significantly better.  I can quickly create flexboxes now.  Successful coding day of about 2.5 hours.

**Link to work:** [Personal Portfolio Page](https://codepen.io/danielberrones/pen/YzyraYo?editors=1100)


************************************************************************



### Day 9: May 3, 2020  - Sunday

**Today's Progress**:  I completed the Responsive Web Design Certification on freeCodeCamp.org.  I also spent time using the requests module in Python to send a post request to httpbin.org.  It was cool to see it work after parsing through the JSON.

**Thoughts:**  I am really starting to understand the CSS box model.  I'm looking forward to reading more about CSS animations, and transitions.  

**Link to work:** [Personal Portfolio Page](https://codepen.io/danielberrones/pen/YzyraYo?editors=1100)


************************************************************************



### Day 10: May 4, 2020  - Monday

**Today's Progress**:  I used JSON.stringifY().  I also created a JavaScript function counts the number of words (and letters!) in a string.  I assigned it to a variable using the let keyword.  I've been usig const too.  Then I console.log'd the variable.   

**Thoughts:**  I know how to write simple arrow functions.   


************************************************************************


### Day 11: May 5, 2020  - Tuesday

**Today's Progress**:  I spent an hour trying to solve freeCodeCamp's Record Collection question.  I read through hasOwnProperty() and getOwnPropertyNames() functions.  I wrote this function:

function updateRecords() {
    let obj1 = Object.getOwnPropertyNames(collection);
    console.log("Total: "+obj1.length+" properties.");
    console.log("Property names: "+ obj1);
    for (item in collection) {
        console.log("Property #"+item);
        console.log(collection[item]);
    }
}

updateRecords();

**Thoughts:**  I am getting comfortable reading MDN docs.  At first I was a bit apprehensive because I trusted W3schools.com more given that the latter doesn't have as many users!   


************************************************************************


### Day 12: May 6, 2020  - Wednesday

**Today's Progress**:  I priortized Python tonight.  I used pack() on a Tkinter Label to place data from the NY Times COVID-19 GitHub repo. 

**Thoughts:**  I developed a few mock websites this morning using HTML/CSS/Vanilla JS for about 90 minutes, and I coded in Python for 45 minutes tonight.


************************************************************************


### Day 13: May 7, 2020  - Thursday

**Today's Progress**:  I wrote semantic HTML, toggled border, margin, and padding CSS properties, and practiced the ternary operator in JavaScript.

**Thoughts:**  The ternary operator saves times, but I still like using if/else explicitly.


************************************************************************


### Day 14: May 8, 2020  - Friday

**Today's Progress**:  I used VIM to work on front end web development.  I created a button that called a JavaScript function which creates a variable based on the "style.backgroundColor", and it changes that setting.

**Thoughts:**  When using VIM, I know how to use (r) to replace the letter with a new one, (x) to remove a letter, (h) to move the cursor left, (j) to move the cursor down, (k) to move the cursor up, (l) to move the cursor right, (ˆ) to move the cursor to the beginning of the line, ($) to move the cursor to the end of the line, (v) to enter visual mode, (Y) to yank text, (p) to paste the text, (i) to insert, (a) to append, and (o) to start writing on a new line below the cursor.  

Using VIM to write html, head, style, body, section, article, h2, p, a, div, span, ul, li, nav, header, footer, main, input, form, fieldset, legend, video, audio, img, button, script, and strong tags was a challenge -- not because the tags were hard to understand---but because I couldn't just quickly click and drag text around like I would in VS Code, it complicated the whole process.  I plan to use "vimtutor" in the terminal again to sharpen my VIM skills.


************************************************************************


### Day 15: May 9, 2020  - Saturday

**Today's Progress** I spent time learning about JavaScript data structures.  I specifically learned about objects.  I spent time understanding how they are constructed.

**Thoughts:** Since I have spent the last 4 years practicing Python dictionaries that has helped me understand JavaScript objects. 


************************************************************************


### Day 16: May 10, 2020  - Sunday

**Today's Progress**:  I continued working on the Records Collection question on freeCodeCamp.  

**Thoughts:**  No solution.  Will do more tomorrow.


************************************************************************


### Day 17: May 11, 2020  - Monday

**Today's Progress**:  I spent time reading through MDN docs about JS objects.

**Thoughts:**  I know how to write a for.. in loop to iterate through the JS object keys.  I'm just having trouble fully answering the Records Collection question.  I had to watch a YouTube tutorial to explain the intricacies of this question.


************************************************************************


### Day 18: May 12, 2020  - Tuesday

**Today's Progress**:  I practiced hasOwnProperty() method.  I understand Object.keys(myObj)

**Thoughts:**  I'm still working on the Records Collection question.  I spent about 2 hours working on it.  I watched a YouTube tutorial explaining how to use for loops on JS objects.  I plan to solve the question tomorrow which i'm looking forward to.  


************************************************************************

### Day 19: May 13, 2020  - Wednesday

**Today's Progress**:  Gaining momentum! Finally figured out the Records Collection question.  And finished Basic JavaScript.

I read MDN docs about:
-Recursive functions and learned about base case.
-Number.isNaN()
-prototype
-Object.create()

**Thoughts:**  I am getting very comfortable with JavaScript objects.  I am excited to continue using them.

************************************************************************

### Day 20: May 14, 2020  - Thursday

**Today's Progress**:  Learned about JavaScript map(), reduce()

**Thoughts:**  Have focused nearly exclusively on JavaScript.

************************************************************************

### Day 21: May 15, 2020  - Friday

**Today's Progress**:  Tinkered with HTML/CSS/JavaScript.  Used getElementById(), and read about recursive functions.

**Thoughts:**  I really like flexboxes. By using the justify-content and align-items property, I can easily center items on the x and y axis.

************************************************************************

### Day 22: May 16, 2020  - Saturday

**Today's Progress**:  

**Thoughts:**  

************************************************************************

### Day 23: May 17, 2020  - Sunday

**Today's Progress**:  

**Thoughts:**  

************************************************************************

### Day 24: May 18, 2020  - Monday

**Today's Progress**:  

**Thoughts:**  


************************************************************************


### Day 25: May 19, 2020  - Tuesday

**Today's Progress**:  

**Thoughts:**  


************************************************************************

### Day 26: May 20, 2020  - Wednesday

**Today's Progress**:  

**Thoughts:**  

************************************************************************

### Day 27: May 21, 2020  - Thursday

**Today's Progress**:  

**Thoughts:**  

************************************************************************

### Day 28: May 22, 2020  - Friday

**Today's Progress**:  

**Thoughts:**  

************************************************************************

### Day 29: May 23, 2020  - Saturday

**Today's Progress**:  

**Thoughts:**  

************************************************************************

### Day 30: May 24, 2020  - Sunday

**Today's Progress**:  

**Thoughts:**  

************************************************************************

### Day 31: May 25, 2020  - Monday

**Today's Progress**:  

**Thoughts:**  
