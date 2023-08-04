Mouse Movement Logger
Description
This JavaScript code records mouse movements on a webpage and displays the mouse coordinates (X and Y) in the console. It uses event listeners to detect mouse movements and log the coordinates whenever the mouse is moved on the page.

How it Works
The code selects the target element (document.body in this example) on which the mouse movements will be tracked.

A mousemove event listener is added to the target element. Whenever the mouse is moved over the target element, the logMouseMovement function is executed.

The logMouseMovement function extracts the mouse's X and Y coordinates from the event object and prints them to the console using console.log().

The code includes an optional part where it removes the mousemove event listener after 30 seconds using setTimeout(). This is done as a precautionary measure to stop tracking mouse movements after a certain time.

How to Use
Copy the provided JavaScript code into your HTML file or link it as an external script.

If you want to track mouse movements on a specific element, replace document.body in the code with the selector of your desired target element.

Open your webpage in a web browser.

As you move the mouse on the page, the X and Y coordinates will be printed in the browser's console.

To stop logging mouse movements after 30 seconds (or any other desired time), check the console for the message indicating that the event listener has been removed.

Compatibility
This code is written in JavaScript and should work in modern web browsers that support event handling. Please ensure your target browsers support the mousemove event.

Mouse Click Detector
Description
This JavaScript code is a simple utility to detect mouse clicks on a webpage and identify whether the left or right mouse button was clicked. It uses event listeners to capture both the mousedown (button press) and mouseup (button release) events to determine which mouse button was clicked.

How it Works
The code selects the target element (document.body in this example) on which the mouse clicks will be detected.

Two event listeners are added: one for mousedown and another for mouseup. Whenever the user clicks the mouse button, these event listeners trigger the handleMouseClick function.

The handleMouseClick function checks the event.button property to identify the clicked button. It logs a message to the console indicating whether the left or right mouse button was clicked.

How to Use
Copy the provided JavaScript code into your HTML file or link it as an external script.

If you want to detect mouse clicks on a specific element, replace document.body in the code with the selector of your desired target element.

Open your webpage in a web browser.

Once the page is loaded, click either the left or right mouse button on the target element.

Check the browser console (usually accessible by pressing F12 or right-clicking the page and selecting "Inspect" or "Inspect Element") to see the messages indicating which mouse button was clicked.

Compatibility
This code is written in JavaScript and should work in modern web browsers that support event handling. Please ensure your target browsers support the mousedown and mouseup events.
