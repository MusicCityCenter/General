#Test 1

This test will evaluate the user story: 

"As a visitor to the MCC, I can search 
for an event, select it, and then see a route to that event displayed on top of 
a floor plan image so that I can get there."


###Step 1
Starting from the landing page of the app, a visitor should type into the search
bar: "Taylor Swift Concert"
The user should then click the "search" or "go" button next to the search bar.
![](https://raw.github.com/MusicCityCenter/General/master/user-test-plans/iteration-1/test-1/step1.png)

This should direct the user to a list of events.


###Step 2
The displayed list of events must all "match" the search criteria. In this case,
only the single event should be displayed, since no other events currently say
anything about "Taylor Swift Concert."
![](https://raw.github.com/MusicCityCenter/General/master/user-test-plans/iteration-1/test-1/step2.png)

Please note that "All" tab should be highlighted, not the "near me." It would 
also be acceptable for the details for the event to not be visible yet. They
should be visible upon clicking, though (click to expand), and clicking on the
event again should take the user to the Room page matching the room in which
the event will take place.


###Step 3
At this page, all the events for this room should be displayed. A button for
"route" should be available to be clicked on.
![](https://raw.github.com/MusicCityCenter/General/master/user-test-plans/iteration-1/test-1/step3.png)

Clicking on the route button will direct the user to another page where the
event's floor is displayed, and a route is overlayed on the floor's blueprint.


###Step 4
The starting point for the route should be randomly generated from available
nodes on the same floor. The route must follow hallways, and must be the 
shortest route available.
![](https://raw.github.com/MusicCityCenter/General/master/user-test-plans/iteration-1/test-1/step4.png)


Credit goes to Austin for the FluidUI mockups.
