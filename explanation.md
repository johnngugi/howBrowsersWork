HOW WEB BROWSERS WORK



A web browser is a software application used to locate, retrieve and display content on the   world wide web. The content on the world wide web is made up of text, digital images, music files, animations etc. World Wide Web works on the client-server model. A user computer works as a client which can receive and send data to the server. The location of a resource is specified by the user using a URL (Uniform Resource Locater).



Before a web page is shown several steps take place:

1. Contact to DNS Server - When a user enters a URL into the address bar and
hits *enter*, the browser contacts the DNS server. Domain Name Servers (DNS) are the Internet's equivalent of a phone book. They maintain a directory of domain names and translate them to Internet Protocol (IP) addresses.

2. Contact to Server - After getting the IP address of the server for the requested web page, browser sends a request to that server for the desired files.

3. Server sends files to browser - After finding the files requested by the browser the server sends them to the browser.




HTTP and CSS:

The browser and the server communicate using hypertext transfer protocol (HTTP).  HTTP defines how messages are formatted and transmitted, and what actions Web servers and browsers should take in response to various commands. When web browsers contact servers, they’re asking to be sent pages built with Hypertext Mark-up Language (HTML). Browsers interpret those pages and display them on your computer.


Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a mark-up language such as HTTP. In web browsers it is used to set the visual style of web-pages. CSS dictates the layout, fonts, and colours of a web-page.

Structure of a web browser:

1. User Interface - The user interface (UI) is the visual part through which a user interacts with the computer. Some of the common browser user interface elements are - Address bar for inserting URL, back and forward buttons, bookmarking options, refresh and stop buttons and home button for taking you to your home page.

2. Browser Engine - It communicates the instructions from the UI to the   rendering engine.

3. Rendering Engine - It responsible for displaying the requested content on the screen. responsible for displaying requested content. For example, if the requested content is HTML, the rendering engine parses HTML and CSS, and displays the parsed content on the screen.

4. Networking - Responsible for sending various network calls. For example, sending the http requests to the server.

5. Java Script Interpreter - It is the component of the browser written to interpret the Java script code presented in a web page. Java script makes the web pages more interactive. JavaScript adds behaviour to the web page where the web page is capable of responding to actions by the users without needing to load a new web page in order to process their request. JavaScript is also used to add animations and to load new images and objects.

6. UI Back-end - This draws basic widgets on the browser like combo boxes, windows, etc.

7. Data Storage - It is small database created on the local drive of the computer where the browser is installed. This database stores various files like cache, cookies, etc.













Rendering Engine


The rendering engine is responsible for displaying the requested content (Rendering). The rendering engine will start getting the contents of the requested document from the networking layer. The content is usually gotten in 8 kilobyte packages. The rendering engine will start parsing (analysing) the HTML document and convert elements to DOM nodes in a tree called the "content tree". 

The Document Object Model (DOM) is a programming interface for HTML. It provides a structured representation of the document as a tree. The DOM defines methods that allow access to the tree, so that they can change the document structure, style and content. The DOM provides a representation of the document as a structured group of nodes and objects, possessing various properties and methods.


The rendering engine will parse the style data found in CSS. The styling information and the visual instructions contained in HTML, will be used to create a render tree. The render contains information about the layout of the web page. The render tree contains rectangles with visual attributes such as colour and dimension. The rectangles are arranged in the right order to be displayed on the screen.


After creating the render tree, the engine will go through a layout process. The process involves arranging the information in the exact position where it should be on the screen. After going through the layout the engine will ‘paint’ the render tree using the UI back-end layer.


All this is a gradual process. For better user experience, the render engine will display contents on the screen as soon as possible. It will not wait for all the HTML to be parsed before building the rendering tree. Part of the content will be displayed, while the rest of the information keeps coming from the network.

 
 




Plug-Ins


Sometimes, home pages contain links to files the web browser can’t play or display, such as sound or animation files. In that case, you need a plug-in or a helper application. You configure your web browser or operating system to use the helper application or plug-in whenever it encounters a sound, animation, or other type of file the browser can’t run or play.






Sources

http://ptgmedia.pearsoncmg.com/images/9780789736260/samplechapter/0789736268_Sample_Chapter_18.pdf

http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/

http://www.webopedia.com/TERM/B/browser.html

https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol

https://en.wikipedia.org/wiki/Cascading_Style_Sheets

https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model

http://javascript.about.com/od/reference/a/javascriptpurpose.htm
