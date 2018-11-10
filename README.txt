# Al-Bayane School Website

This website helps the school to provide updated information in the form of news and events, 
announce the available programs and the school branches;beside enhancing the communication with parents through email or direct messaging.

## Website Compatibility

This website is built using bootstrap library and is Compatible with all devices

----------------------------------------------------------------------------------

# Working hours report:
the project took about 19 hours which is much more than the expected time (10 hours), because of the design and the problem solving phase
a) Planning and research: 2 hours
b) Data gathering : 1 hours
c) Design ( logo, banner,colors,fonts and pictures ) : 3 hours
d) Development of code : 12 hours
e) Documentation : 1 hours

# Modules used in the website:
1. Index page: includes a slider using bootstrap carousel for displaying news and a calender using FullCalendar library.
2. Programs page: include a table of school programs available using html table.
3. School branches page: a map showing the school branches location using google maps api (using my google map api key);
			address of each branch is sent to google server to get the longitude and latitude of the address 
			then an AJAX request is sent to google server to get the map and put markers on each longitude and latitude.
			branches are created using function constructors and are stored in array of objects.
4. Events page: events are displayed using bootstrap collapsed panels, date object was used to display the amount of time till the next event.
5. Contact Us: an html from to receive messages from website users, font awesome icons were used for phone, mail and facebook icons.