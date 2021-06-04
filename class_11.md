# Assorted Topics
 
 # CSS

This read is revisiting topics covered, one of which is Css design. Css contains the rules that affect the presentation of your page in the css and out of the HTML markup. you can achieve several effects using css. You can set background images and specify the size and alignment of an image, and create image rollover using css. To reduce the number of images your browser has to load, you can create image sprites.

An image sprite is a collection of images put into a single image. A web page with many images can take a long time to load and generates multiple server requests. Using image sprites will reduce the number of server requests and save bandwidth.

### Example
#navlist {
  position: relative;
}

#navlist li {
  margin: 0;
  padding: 0;
  list-style: none;
  position: absolute;
  top: 0;
}

#navlist li, #navlist a {
  height: 44px;
  display: block;
}

#home {
  left: 0px;
  width: 46px;
  background: url('img_navsprites.gif') 0 0;
}

#prev {
  left: 63px;
  width: 43px;
  background: url('img_navsprites.gif') -47px 0;
}

#next {
  left: 129px;
  width: 43px;
  background: url('img_navsprites.gif') -91px 0;
}

# Practical information

When launching a successful website there are certain things you need to consider. It would help if you understood the basics of search engine optimization which helps you increase your websites visibility on search engines. You can use analytics to understand how people are using your site after it's launched. When people visit your site you can analyze how they found it. one of the tools you can use to do this is google analytics. Using analytics you can track the amount of visits, unique visits, page views, pages per visit, and average time on a site. This allows you to learn more about your visitors, where your visitors are coming from, and what they are looking at.

# Domain Names and Hosting

In order to put your site on the web you will need a domain name and web hosting. your domain name is your web address such as google.com or bbc.co.uk. Web hosting is so other people can see your site and you'll need to upload it to a web server. Web Servers are computers that are constantly connect to the internet. They are specially set up to serve web pages when they are requested. FTP (File Transfer Protocol) programs allow you to transfer files from your local computer to your web browser. Many companies provide platforms for blogging, email, newsletters, e-commerce and other popular website tools. These can help in you having to write sites from scratch.
