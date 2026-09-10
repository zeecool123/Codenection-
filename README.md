# Codenection-

RADIANT ROUTE by Tiki Taka

Team : Ooi Chong Zee, Chan Zhi YIng, Khor Mei Shi

Problem Statement: Travel Planner

Video Presentation :

Presentation Slides :

1. Project Overview

The Problem: Current tour guides do not have the actual tools to make lots of different itinerary for customers to actually decide on an itinerary that everyone can agree to and be satisfied. Even so, Chat GPT and lots of chatbots don't really have the visuals to persuade users to go to destinations, they use word forms to elaborate what sights or food you'll be seeing or eating while users can't really imagine those visually. The main problem still is current tour guides just average out all possible interests and prints it out on your itinerary, what if you could give them a separate option where they get to choose specific interests. For example, 1st option with more places on food, while second option more places on historical sites, and people might not only have 1 interests, maybe they would all have the same interests.


Our Solution. We presented an app that easily address those issues. Our app has an AI agent that will generate different itineraries based on different interest and based on ideal routes, and if not satisfied they can keep voting until everyone is satisfied as the smart AI will combine top options and be set as another option for people to choose. Not only that, users get to preview the point of view of the places from the itinerary option that they chose to preview to really look into it visually what to be expected. Moreover to address this preference issue, as we talked about generating different options we could have options that focus more on food, another one that focus more on cultural stuff because some cities might have specific stuff that they excek in like historical sites, or even food, or cultural stuff.



2.1 Ideas WE CONSIDERED

Ideas                                                                                                                                                                       || Why it was dropped / kept

To make your phone buzzes and give you like recommended food or places to visit around you when app looks at your itinerary when u have free time                          || Too many unique functions making the app complicated


The planned places will be recommended by datas from the Internet from different sources to be different from traditional tour guides that bring you to crowded places     || Unrealistic, as sources could be unpredictable



2.2 Ideation Boards

![Feature-narrowing ideation board](./assets/ideation/idea-narrowing-with-mentor-advice.png)

We shortlisted five features across the trip lifecycle. Three were cut early because of privacy, technical-complexity, and timeline constraints. The remaining two—AI-driven recommendations and group preference matching—were brought to mentor consultation on 5 September; following the advice to focus on one core feature, we selected group preference matching as our MVP.



2.3 Mentor Consultation

### 5 Sep 2026, 9:20 PM — Zach Khong

**Feedback received**

- **Idea:** Be original in how you present data. Maximise one core feature rather than spreading thin; users are usually not comfortable providing a lot of input.
- **Pitching:** Build the pitch around one core feature, rather than presenting a long feature list.
- **UI/UX:** Keep the interface simple.

**What we changed**

- Narrowed the app to one standout core feature instead of trying to solve every travel-planning pain point at once.
- Reduced the manual input expected from users by relying more on swipe and quick-choice interactions rather than forms.
- Simplified the UI direction so the core feature is clear, without extra functions competing for attention.







3. Prototype walkthrough

    -1. Start a group trip

![Radiant Route home page](./assets/prototype/01-home.png)

The landing page introduces Radiant Route and gives the host a clear **Plan New Trip** starting point for creating a collaborative trip.

    -2. Set up the trip group and preferences

![New trip setup](./assets/prototype/02-trip-setup.png)

After selecting **Plan New Trip**, the host enters the trip’s initial details, such as the destination, number of travellers, dates, and the group’s interests. These inputs give the AI the context it needs to create relevant itinerary options.

    -3. Compare AI-generated routes and vote

![AI-generated route choices](./assets/prototype/03-route-voting.png)

The AI produces several route alternatives with different mixes of experiences. Each traveller can review the choices and vote for the route that best matches their preferences, whether that means culture, history, food, or another travel style.

    -4. Let the host choose how to decide

![Host route decision options](./assets/prototype/04-host-decision.png)

Once voting is complete, the host can either confirm the highest-voted route or ask the AI to combine ideas from the leading options into a more balanced itinerary for the group.

    -5. Select routes to integrate

![Route integration selection](./assets/prototype/05-route-integration.png)

For a balanced plan, the host selects the route options and preference mixes to integrate. This gives the group control over which experiences should be preserved in the new itinerary.

    -6. Review and vote on the balanced route

![Integrated route detail](./assets/prototype/06-balanced-route.png)

Radiant Route presents a newly generated itinerary that combines the selected preferences. Travellers can inspect its route details, leave a review, and vote on the updated plan before the group finalises it.

    -7. Visualise the journey on a map

![Route map and travel details](./assets/prototype/07-map-view.png)

The map view shows every stop in the itinerary and makes the journey easy to imagine. Travellers can see where they will go, how long each transfer takes, and whether to walk or use another mode of transport between stops.




4. What Makes our idea Different


Core Functionality: The AI agent groups the friends' pooled interests and generates distinct itinerary options, where each option is heavily anchored around a single, specific interest theme (e.g., Option 1 is 80% Food-focused, Option 2 is 80% History-focused).

The Twist: Unlike other apps of giving everyone a watered-down, generic mix of everything, the app creates clear, intentionally biased archetypes. This allows the group to vote on a vibe or dominant theme for the itinerary, forcing a clear decision on what matters most to them. The thing is we could satisfy all the users at the same time, as they might one more out of something instead of another type of places. 

Secondly. traditional travel tools use static images linked to specific venue listings. Here, the visual preview dynamically adapts alongside the mutating AI itinerary, giving users instant visual context for every algorithmic modification, so that they know what they are expecting in each places giving them more convenience instead of just googling the places and checking what to expected there.





















## 5. Technical Architecture & Feasibility
### Tech Stack
| Components | Technology | Reason for choosing it | Constraints |
| --- | --- | --- | --- |
| Frontend | xxx | xxx | xxx |
| Backend | xxx | xxx | xxx |
| Database | xxx | xxx | xxx |
| AI Model | xxx | xxx | xxx |
| Hosting | xxx | xxx | xxx |

### System Architecture Diagram
xxx

### Build Plan & Scope
xxx
