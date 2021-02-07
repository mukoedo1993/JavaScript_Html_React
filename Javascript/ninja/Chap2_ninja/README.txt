The lifecycle overview:
1: User actions:
1: Enters URL(or clicks link)
2: The browser generates a request and sends it to
the server.

3:The server perforfms actions or get a resource; sends response 
to client.
(2<->3 can switch as many times as necessart)

4: The browser processes HTML, CSS, and Javascript, and builds
resulting page.

5: The browser monitors event queue, processing any events one at a time.
(5<->6)
6: The user interacts with page elements

7: The user closes web app.


DOM Model: CSS, JS, HTML
JS Model: IO<-> Events Timers;


Function code V.S. Global code:
The code contained in a function is called function code, whereas the code placed outside
all functions is called global code.


Global objects in Javascript:
The primary global object that the browser exposes to Javascript engine is the window object,
which represents the window in which a page is contained. The window object is the global object through
which all other global objects, global variables (even user-defined ones), and browser APIs are accessible.

One of the most important properties of the global window object is the document, which represents the DOM
of the current page. By using this object, the Javascript can alter the DOM of the current page. By using this
object, the Javascript code can alter the DOM of the page to any degree, by modifying or removing existing
elements, and even by creating and inserting new ones.



GLOBAL and FUNCTION JAVASCRIPT CODE:
The main difference between two types of the code is their placement: the code contained in a function is
called function code, whereas the code placed outside all functions is called global code.
Difference:
Global code executed automatically by the Javascript engine in a straightforward fashion, line by line, as it's 
encountered.
On the other hand, function code, in order to be executed, has to be called by sth else:
either by global code, by some other function, or by the browser.


EVENT HANDLING:

single-threaded execution model:
The browser execution environment is, at its core, based on the idea that only a single piece
of code can be executed at once: the so-called single-threaded execution model.

EVENT ARE ASYNCHRONOUS:
Events, when they happen, can occur at unpredictable times and in an unpredictable order (it's tricky
)


Conclusion:
The lifecycle of a client-side web application starts with the user specifying
a website address (or clicking a link) and ends when the user leaves the web 
page. It's composed of two steps: page building and event handling. 