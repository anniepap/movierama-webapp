MOVIERAMA

> Technologies:
The project is as plain as possible, written in Vanilla JS, HTML, CSS.
I tried to avoid using Bootstrap or any framework that I am more familiar with at this time.
I have used Visual Studio Code and a handful of its extensions, such as Live Server, Beautify, etc.
Rather than using jQuery AJAX methods for exchanging data with the Movie Database API or XMLHttpRequest, I  preferred the Fetch API.
The reason is that Fetch API, in comparison with XMLHttpRequest, makes it easier to render asynchronous requests.
In parallel with jQuery AJAX, Fetch API will handle responses better since it will resolve normally even if the response includes an error status.

> Implementation:
For the implementation, I tried to structure the code to simulate an MVC pattern.
So theoretically, the 'App' class contains the logic, the 'Movie class represents the data, and the 'View' class exists to display the data.

> Requirements:
All the listed requirements have been fulfilled though there are things that I would like to improve.
Specifically, it would be nice to have more smooth animations on changing views or while rendering data.
Similar movie's preview is now limited to a single page, but it could probably be in a carousel view.
Clicking each similar movie could open the expansion panel for this movie. Also, on each similar movie hover, it could be better to have a tooltip showing the movie title.
I believe that the app acts responsively on window resize, though improvements are maybe necessary.
Cases, where the response is undefined, should be handled specially for a better user experience.
Finally, importing a library for testing would be a nice practice, especially for a more complex app.
For testing, I would probably use Jest.
For example, I could develop a test function for checking the request results of a specific movie.
