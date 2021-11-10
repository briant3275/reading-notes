# 102 notes

    # Welcome fellow mammals

        My name is Brian Thornburg, my pronouns are he/him. I'm from Cedar Rapids Iowa and currently work as a cook at Big Grove Brewpub. I attended University of Northern Iowa studying studio art and still enjoy working on illustration, painting, digital work, print and performance. I am married to my majesctic wife Abby with which I have sired a child, Milo, who is 2 years old. Most of my time is dedicated towards spending time with them followed by cooking, gardening, making art, coding, gaming and petting our three cats.


        ## Growth Mindset


        Believing in your ability to learn new things and to not become discouraged when faced with difficulties but rather use them as opportunities to expand your knowledge 

        **Reminders on how to stay in a growth mindset**

        1. "Dude, suckin' at something is the first step to being sorta good at something." - Jake the Dog from Adventure Time
        2. When frustrated with a problem, take a break and revisit the problem with fresh eyes
        3. Do not think less of yourself when comparing yourself to others with more skills, use them as an example of what skills you can learn

        ### GitHub

        [Brian's Reading Notes Page](https://briant3275.github.io/reading-notes/)

        *For my final trick I present you with an awe-inspiring line of italicized text*

        #### Text Editors

        All computers will come with a generic form of text editor such as "Text Edit" or "Notepad" however not all text editors have the same features/plugins. Some features that may come in handy are syntax highlighting and code completion, as well as word completion and function completion. Some of these editors and their functions may align better with the coding language you plan to use.

        ##### Terminal Cheat Sheet

        1. **echo** used to display messages
        1. **up and down arrows** used to traverse history
        1. **pwd** print working directory
        2. **ls** list
        3. **~** home directory
        4. **.** current directory
        5. **..** parent directory
        6. **cd** change directory
        7. **file** shows file type
        8. **ls -a** shows directory contents including hidden files
        9. **man <command>** look up the manual page for command
        10. **/<term>** perform a search for term
        11. **n** select next item
        12. **mkdir** make directory
        13. **rmdir** remove directory
        14. **touch** create blank file
        15. **cp** copy
        16. **mv** move
        17. **rm** remove
        18. and many more that I will add later!


## 201 notes

    #HtmlChapter6 Tables

        tables are made of rows and columns. ex: financial reports, tv schedules, sports results. each block in grid is called a table cell. 
        <table> creates table
        <tr> indicates start of table row
        <td> table data
        <th> table heading
        scope="col">  indicate column
        colspan="number"
        rowspan="number"
        <thead> table head
        <tbody> table body
        <tfoot> table foot

    #JSChapter3
        Object.Key = value
        object['key'] = 'park'
        this.checkAvailability = function() {return this.rooms - this.booked;};
        let object = new key (values)
        you can add new properties to object after its created
    
    #HTMLChapter15
        - scc treats html elems as if its in box, either a block-level box or inline box
        - if block-level elem sits inside another, the outer is the containing or parent
        - positioning schemes
            - normal flow : position static
            - relative positioning : position relative
            - absolute positioning : ''
            - fixed positioning : ''
            - floating elements : float
        - z-index allows control of whats on top
        - clearing floats  : clear
        - left, right, both, none
        - columns : width, float, margin
        - fixed width layouts
        - liquid layouts : stretch and contract with browser size
        - grid layout
        - mult style sheets : @import, link

    #HTMLChapter7
        - forms used to gather info from user
        - all <form>s need an action and is sent via a method
        - <input> used to create several form controls
        - info from forms sent in name/value pairs
        - type="password name="username" size="a number" maxlength="a number"
        - <textarea> used to create multi'line text input
        - "radio" allows one number of options
        - "checkbox" allows one or more options
        - <select> creates dropdown list box
        - <option> specifies user options
        - size attribute controls having more than one option
        - type="file" if you want user to upload a file
        - type="submit" sends form to server
        - value used to control the text on the button
        - type="image" if you want image for button
        - <button> gives more control over how buttons appear
        - <label>
        - <fieldset> group related form controls
        - <legend> comes after fieldset, identifies purpose of group
        - form validation for if form not filled out correctly
        - <input>
        

    #HTMLChapter14
        - list style types: decimal, decimal-leading-zero, lower-alpha, upper-alpha, lower-roman, upper-roman
        - list-style-image to use image as bullet points
        - list-style-position outside: marker sits to left of box, inside: marker sits inside box
        - list-style to style list
        -
        

    #JSChapter6

    #JSChapter10
        - there is one global execution context plus each function creates a new execution context
        - eval context: text executed like code in internal function called eval ()
        - js processes on line at a time, when statement needs data from another function, it stacks new function on top
        - prepare: new scope, vars functions args are created
        - execute: assign values, reference functions, execute statements
        - hoisting: you can call functions before they are declared, and assign values to variables before they are declared
        - each execution context has variables object,can access parents variables object
        - children can get info from parents but parents cant get info from children
        - if js generates an error it throws an exception, exceptions should notify user when there is a problem
        - if there is no exception with an error occuring then the script stops
        - errors: syntax: syntax incorrect, reference: var doesnt exist, type: value is unexpected data type, range: number outside range
        - debug code or handle with try, catch, throw
        - where is problem, what is it? listed in console
        - use breakpoints to check stored values at a given time
        - set multiple breakpoints to step thru 1by1
        - conditional breakpoints with debugger keywords
        - try: specify the code in suspect, catch: catch exceptions, finally: code runs either way, throw: creates error object
        - debug tips:pg 484
        - common errors: pg 485
        
    #HTMLChapter16
        - WE can use css to control imnage sizes
        - use different class names for diff sizes
        - also use class names for alignment
        - in order to center, use display: block on imgs
        - background-image to place image in background
        - background-repeat: repeat-x, repeat-y, background-attachment: fixed, scroll
        - background-position: center top
        - rollover for when cursor is on image, click for 3rd
        - when an img is used in several places it is called a sprite
        - :hover subclass
        - linear-gradient(color1,color2)
        - use screen behind text and over hi-contrast img

    #HTMLChapter19
        - SEO: search engine optimization
        - on page and off page techniques
        - keywords appear in: page title, url, headings, text, link text, img alt text. page description
        - brainstorm, organize, research, compare, refine, map
        - tracking code right before head for google analytics
        - visits, unique visits, page views,pages per visit, avg time on site
        - bounce rate shows if users left from page they arrived on
        - referrers: shows sites linked to you
        - domain name and web hosting
        - disk space, bandwidtth, backups, email, server-side languages and databases are all factors used to determine which hosting company to use
        - FTP programs allow you to xfer files from local to web server


    #Chart.js API article
        - <canvas>
        - Chart().Line();
        - Labels for base of chart, datasets for values on chart
        - strokeColor, pointColor, pointStrokeColor
        - Chart().Pie(pieData, pieOptions)
        - let pieOptions = { segmentShowStroke : false
        animateScale : true}
        - Chart().Bar(barData)

    #Canvas API notes
        - canvas is initially 300px wide by 150px high, can be sized with css but if it doesn't fit the ratio it will appear distorted
        - specify width and height explicitly in th <canvas> attributes
        - good idea to put a class on the canvas
        - element can be styled just like a img but it won't affect the actual drawing on the canvas
        - when no styling is applied, canvas will be transparent by default
        -for fallback content, browsers with support will ignore content and display canvas, browsers without support will ignore container and show content
        - getContext() used to obtain rendering, takes one parameter "2d"
        - can check for browser support with if statement
        - draw shapes by specifying coordinates, top left is 0,0
        - fillRect(x,y,width,height) strokeRect() clearRect()
        - beginPath(), closePath(), stroke(), fill()
        - moveTo(x,y), arc(parameters for arcs)
        - lineTo(x,y)
        - quadraticCurve(cp1x, cply, x, y), bezierCurveTo(cp1x, cp1y, cp2x, cp2y, x, y)

    #Local Storage Article
        -os typically provides layer of abstraction for storing data like prefs or runtime state
        - for local storage you can imbed your own database, invent file format, etc.
        - bad things about cookies: included in http requests which can slow down app, sends unencrypted data over internet, limited to 4 kb of data
        - microsoft made dhtml behaviors, one called userData with 64 kb of data per domain
        - 2002 flash6 allowed up to 100 kb data per domain
        - 2007 google gears could store unlimited data per domain in sql database tables
        - 2009 dojox could auto detect flash,gears,air and an early html5
        - html5 set out to standarize api
        - html5 storage provided local storage
        - from js access storage thru localstorage object
        - data stored as a string in a key:value pair
        - setitem() and getitem() removeitem() key()
        
        