# HTML Links, JS Functions, and Intro to CSS Layout

# Links

links are defining features of the web and allow you to move from one page to another. links are created using the 'a' tag and then you specify the page you want to link using the 'href' atribute.

<a> href="youonlyliveonce.com">yolo</a>

* Creating links
  Relative URL's can be used when linking to pages within your own site. You can create links to a specific part of a page and open links in new windows.

* Linking to other sites
  Users can click on anything betwen the opening and closing 'A' tag as shown in the example above.

* Email links
  To create an email link that starts up the users email address use the opening and closing 'A' tags, except instead of using the href attribute you start with mailto:

  <a>href="mailto:yolo@vibewithme@gmail.com">Email Yid</a>

  you can use the id attribute to target elements within a page that can be linked to.

  # Layout

  HTML Layout is all about screen design and creating a site that is more attractive. Using the <Div> element you can group together sections of a page. Css allows you to treat each HTML element as if it were in it's own box, giving you more cotrol over images, positioning, color, etc. you can also create a site that can be viewed on different size screens such iphones, ipads, macs, and bigger PC's. There are different kinds of layouts, one of which is a fixed layoput which means the screen does not change size as the user increases or decreases the size of their browser. liquid layouts however do increase and decrease in the users browser. You can layout grids which add another layer of creativity to your site and keeps the layout consistant and makes it easier to add new content. you can use different style sheets 

  You can control the position of elements to create more flexible designs.
  - Normal Flow
  - positioning
  - Overlapping and Floating Elements
  - using float to paste elements side by side
  fixed width and liquid layouts
  - Grid based layouts 

  These are just a few of the things you can control using layouts. You can link multiple style sheets in both HTML and CSS giving you even more control over your site.

  # Functions Methods and Objects

  Functions
    - functions considt of a series of statements that have been grouped together for a specific task. a method is the same as a function except methods are created inside.

    Objects
      - Objects are used to create models of the world using data and are made up of propertie and methods.

A  basic function would look something like this:

var message = 'Drop a like and receive a free track';
function updateMessage(){
  var el = document.getElementById('message');
  el.textContent = msg;
}
updateMesage;
