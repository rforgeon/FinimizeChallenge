# Finimize Challenge

## **Challenge:** Come up with a way for users to track progress towards their goals.


## Outline
1. Organizing Persona and Creating User [Job] Story.
2. Wire Framing
3. Graphing & Sketch
4. Discoveries and Alterations
5. Next Steps

## Organizing Persona and Creating User [Job] Story.

Our persona is Jason, a 26 year old, male, consultant, from London. He makes a "good" salary and his financial level is intermediate. This means "he’s never invested but he understands the basics of things and has been reading Finimize for some time."

I've organized Josan into a User Story using As a.., When..., I Want..., So...
Below is a preview of the story, but click [here](https://airtable.com/shriib91ZPRXZPMLf/tblCpRmyH2pHx5oiI/viwkChBkmkV4NldO1) to view the full document.

![](https://cldup.com/Ikl4oNQFvJ.png)

## Wire Framing

After establishing what Jason's story might look like to track progress towards his goal, I began putting pen to paper. Bellow are a couple of my initial sketches. However, be sure to open the above 👆 Airtable User Story document to reference the sketches with each story line.

![](https://cldup.com/-vFGBQebfu.png)

While putting together some ideas, I immediately realized how useful [HighCharts](https://www.highcharts.com/) would be for this feature.

I began playing around with the HighCharts API to see if something could be created inline with my initial wire framing. Check out the JsFiddle [here](http://jsfiddle.net/cwgeg9r3/).

## Graphing & Sketch

Once I had an idea of how to layout the UI, I dove into Sketch. The starter template greatly helped to match Finimize's design.

This is where I brought together my wire frames, JsFiddle graph, and Finimize's design to show off a potential full package.

![](https://cldup.com/WwnYCBZVi7.png)
![](https://cldup.com/GSlQCJquhB.png)

## Discoveries and Alterations

While wire framing, I came to a nice discovery that allowed me to eliminate a step for the user in the tracking process.

You can see these steps in the "Deprecated" section of my Airtable User Story document.

I was first asking the user if they had made any new savings in the first modal screen, then asking them to enter the savings amounts.

I decided to eliminate the first step and simply have the user click update with pre-filled ￡0 if they have not made any savings.

![](https://cldup.com/65zFp-jKn6.png)

## Next Steps

### Feature Role Out

🔴 Notification on the goal should allow for the majority of feature discovery or interaction. It also might be nice to have an Intercom notification of the visual tracking once a user hits the /goals page.

### User Follow UP On Feature

* When did you notice it? What did you think? Did you use it straight away?
* What attracted you to it?
* Were there any barriers to you using it?
* Have you told anyone about what you use it? What did you say?
