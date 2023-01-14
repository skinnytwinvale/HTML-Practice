# HTML-Practice
In this session I was using the basic HTML tags and attributes to create a basic HTML page that included
1. Unordered list
2. Ordered list
3. Page breaks
4. Lines
5. Images
6. Hyperlink
7. Bold text

### Getting started with HTML
HTML, which stands for Hyper Text Markup Language, is one of the fundamental building blocks of the web. When you visit a webpage, your browser reads HTML and renders the document on the page. HTML is primarily responsible for holding the content of a page; the styling is defined by CSS, and much of the interactivity is controlled by JavaScript (we'll get to these technologies soon enough)

### The Structure of HTML
If you've never seen HTML before, one of the first things you'll notice is probably the number of elements, which are the building blocks of HTML. We specify the name of the element using its name along with opening and closing brackets (<>). To denote the ending of a tag, we use </>. 

To bring up the basic structure of the HTML page, type in the ! and press enter and it should come up automatically.

Notice that sometimes elements are nested inside of other elements. meta and title are inside of head, h1 is inside of body, and everything is inside of html. These are commonly referred to in the language of parents and children: we say that the h1 element is a child of the body element, for example, and that the body element is the parent of the h1 element. Elements with the same parent are called siblings; the meta and title tags are siblings in the document above.

### Essential HTML tags

<html> - This is where we place all of our elements that comprise the contents of our page.
<head> - This is the container for the elements that have content that does not need to be displayed on
the page (like metadata, the title, or, as we will see, scripts and stylesheets).
<meta> - This is a tag for providing metadata (data about our data) to the page. We can use meta tags to display what character set we are using or for SEO (Search Engine Optimization) purposes.
<title> - This tag gives the page a title that can be displayed in the tab of your browser.
<body> - This defines the main content of the HTML page.
  
### Attributes and Content
  
Our sample HTML page contains a number of elements. Some of those elements contain content: for instance, the content of the h1 tag is the text "Here's some important text!" Some elements also contain attributes, which are used to provide additional information about an element. The attributes are always set inside of the opening tag of the element, and take the form attribute_name="attribute value". In our sample HTML, there are two attributes:

  1. The html tag has a lang attribute set to "en". This tells the browser that the HTML document is written in English. This will probably be the default you'll want for all of the web pages you create. For more on the lang attribute, check out this article.

  2. The meta tag has a charset attribute of "UTF-8". This specifies the character encoding for the file. You don't need to worry too much about this for now, but if you'd like to learn more about UTF-
8, you can start with this Wikipedia article.

  
Link to my HTML page: http://127.0.0.1:5500/my_first_html_page.html
