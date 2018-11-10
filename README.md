# Al-Bayane School Website

This website helps the school to provide updated information in the form of news and events, 
announce the available programs and the school branches;beside enhancing the communication with parents through email or direct messaging.

## Website Compatibility

This website is built using bootstrap library and is Compatible with all devices

## Running Website:
All you need is to download the file Al-Bayan website using this link:
https://github.com/ZeinaKittaneh/Al-Bayane-Website
then upload it to your server

----------------------------------------------------------------------------------

## Working hours report:
the project took about 19 hours to be done which is much more than the expected time (10 hours), that is because of the design and the problem solving phase
which took longer than planned.

Here is how much time I spent on each phase:
a) Planning and research: 2 hours
b) Data gathering : 1 hours
c) Design ( logo, banner,colors,fonts and pictures ) : 3 hours
d) Development of code : 12 hours
e) Documentation : 1 hours

## Modules used in the website:
1. Index page: includes a slider using the bootstrap carousel for displaying news and a calender using the FullCalendar library.
2. Programs page: includes a table of school programs available using html table.
3. School branches page: a map showing the school branches locations using google maps api (using my google map api key);
			address of each branch is sent to google server via AJAX request to get the longitude and latitude of eachaddress 
			then an another request is sent to google server to get the map and put markers on each longitude and latitude point.
			branches are created using function constructors and are stored in array of objects.
4. Events page: events are displayed using bootstrap collapsed panels, date object was used to display the amount of time till the next event.
5. Contact Us: an html from to receive messages from website users, font awesome icons were used for phone, mail and facebook icons.

## information resources:
I used the following websites for coding and design the website:
1. Bootstrap documentation : https://getbootstrap.com/docs/3.3/
2. FullCalendar documentaion : https://fullcalendar.io/docs
3. Font-awesome tutorial and contact form design: 
   https://azmind.com/bootstrap-social-icons/
   https://www.nicesnippets.com/snippet/bootstrap-4-contact-us-form-with-map-page-design
4. Google maps api tutorial: https://developers.google.com/maps/documentation/javascript/tutorial
   