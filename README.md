# Connections Labs Week 4

Hi everyone 👋🏼

This is a submission for Week 4 (Midterm 1) of IMA Low Res @ NYU (Fall 2022). It's a work in progress for Midterm Project 1 for the Connections Lab class. The core idea is an Interactive Solar System which has a solar system visualizer. Clicking into a planet (or the sun) reveals certain facts, each with their own visualization.

Enjoy 😊

----------

**DOCUMENTATION WRITE UP:**
**Deployed Page link: https://is1379.github.io/Connections-Lab-Week-4/**

----------

Concepts & Intentions:

My primary intention with this project was to create an interesting, satisfying visualization of the solar system. I also wanted to include certain factual information to help the user learn a bit more about the planets that orbit the sun with us. I had seen a lot of solar system visualizers before creating the main "Orbiting" sketch, but a lot of them felt clunky or overly technical. I wanted to strip that down and create something that was approachable and satisfying to watch. I guess a major influence would be a screensaver or desktop background. Something ambient that you wouldn't mind watching or having spin around in the background.

----------

Production Decisions:

As far as technical decisions go, I wanted to encorporate p5.js (https://p5js.org). This was necissary since the core "Orbiting" sketch was done over the summer session in p5. Reworking it from scratch would have been a waste of time. I did refine the code to use a class to build the planets themselves which allowed me to manipulate the planets more efficiently on the page. It also helped with staging so planets could be easily hidden and shown without having to be deconstructed and reconstructed every time. 

Another technical decision was to include the jQuery library (https://api.jquery.com). It's a library that I'm very familiar with, so it made sense to use it to handle a lot of the js interactions with HTML. You can see instances of jQuery in the sketch.js file where $('#item_name') exist. It allows for the easy hiding and showing of html elements, the changing of css styling, and the manipulation of text and image links.

Lastly, I decided to use API calls to gather information about the planets. I used a service called API Ninjas (https://api-ninjas.com) as the resource for the information about the Sun and the Planets. The API was useful since it was free with a high call limit (50K calls per month). I did make a technical faux pas in exposing the API key, but I didn't feel that hiding the key was necissary since the service is free, and I don't plan on using it in the near future.

For design decisions, I wanted a minimal look for the page. I tried to have the individual visualizations feel relevant to the information they were protraying. For the distance to planet, there is a ship that goes from Earth to whichever other Planet the user selected. For the brightness of the sun, there is a pulsating circle to illustrate light coming off of the star's surface. I also tried to have the design be as intuitive as possible (underlining for linked text and on screen prompts).

----------

Challenges & Solutions:

I wouldn't say that there were any particular challenges other than the amount of time given for the project itself. Several of the current issues with the sketch could be easily fixed if given another week or two of work. Examples: Clicking on Earth gives a time to travel to Earth of 0 and the ship goes from Earth to Earth. If a user clicks on a planet before the API call is done, information won't populate.

I had some design challenges and went back and forth with different layouts for the information and visualizations, but I basically just kept playing with it until I got a layout that felt right for the page.

Another challenge/issue is the load of the page itself. With all of the moving parts within the sketch, the page takes a lot of CPU and energy to run which could be problematic for users with less powerful devices.

Lastly, the site is not fully responsive.

----------

Lessons Learned & Next Steps:

I think I learned a lot about design from this project. Creating nice visual elements that felt fun and interactive was not an easy task and definitely not something I am familiar with. On the technical side of things, I think the next steps are to fix the responsiveness of the page and the glitchy interactions (like clicking on Earth). I would also want to add more information and visualizations for a more robust page feel.

I think adding more interactive elements like sound (suggested by Brian) and maybe the ability to have a display of how many users have been to a planet or a way for users to plant their flag or explore a planet would be good extensions of the existing page.

----------

Resource Attributions:

• Brightness_Icon.png: https://www.flaticon.com/free-icons/brightness | User: Smashicon

• Distance_Icon.png: https://www.flaticon.com/free-icons/rocket | User: Freepik

• Orbit_Icon.png: https://www.flaticon.com/free-icons/orbit | User: Freepik

• Planet_Icon.png: https://www.flaticon.com/free-icons/planet | User: Good Ware

