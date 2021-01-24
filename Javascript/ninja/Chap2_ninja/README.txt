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

Conclusion:
The lifecycle of a client-side web application starts with the user specifying
a website address (or clicking a link) and ends when the user leaves the web 
page. It's composed of two steps: page building and event handling. 