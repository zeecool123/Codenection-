# Codenection-

# Codenection-

**TripSync by Tiki Taka**

**Team:** Ooi Chong Zee, Chan Zhi Ying, Khor Mei Shi

**Problem Statement:** Travel Planner

**Video Presentation:**

**Presentation Slides:**

## 1. Project Overview

**The Problem:** Current tour guides do not have the actual tools to make lots of different itineraries for customers to actually decide on an itinerary that everyone can agree to and be satisfied. Even so, ChatGPT and lots of chatbots don't really have the visuals to persuade users to go to destinations — they use word forms to elaborate what sights or food you'll be seeing or eating, while users can't really imagine those visually. The main problem still is current tour guides just average out all possible interests and print it out on your itinerary, when instead you could give them a separate option where they get to choose specific interests. For example, one option with more food-related places, while another has more historical sites — since people don't only have one interest, they might have several.

**Our Solution:** We presented an app that easily addresses those issues. Our app has an AI agent that generates different itineraries based on different interests and ideal routes, and if not satisfied, users can keep voting until everyone is satisfied, as the smart AI will combine the top options into another option for people to choose. Not only that, users get to preview the point of view of the places from the itinerary option they chose, to really look into it visually and see what to expect. Moreover, to address this preference issue, the different generated options can each focus on a different theme — one more on food, another more on cultural aspects — since some cities might have specific strengths, like historical sites, food, or culture.

## 2. Ideation

### 2.1 Ideas We Considered

| Idea | Why it was dropped / kept |
|---|---|
| Push notifications recommending nearby food or places during free time on the trip, based on the itinerary | Dropped — too many unique functions, making the app complicated |
| Recommending places using data pulled from various internet sources, instead of traditional curated tour-guide spots | Dropped — unrealistic, as sources could be unpredictable |
| AI voting system that keeps voting until all users is satisfied with a hybrid route feature | Kept — Very good for satisfaction of users, having them agreed in common interest |
| AI agent recommending relevant places in specific cities  | Kept - Able to recommend better theme for specific cities, food and cultural for some rural places in China for example |
| POV preview system for destinations in routes | Kept - Let users understand what to expect in destinations |

### 2.2 Ideation Boards
This section shows how we extended our idea from the ground up. We started by identifying the common problems people face when planning a trip — both from our own experience and from gaps we noticed in existing travel planning apps (our competitors). These problems became the foundation we branched our ideas from.

[![Circle Process Diagram Infographic Graph](https://github.com/zeecool123/Codenection-/raw/main/assets/ideation/Circle_Process_Diagram_Infographic_Graph.png)](/zeecool123/Codenection-/blob/main/assets/ideation/Circle_Process_Diagram_Infographic_Graph.png)

The diagram above maps out the problems we identified with travel planning today, branching out from the core issue into specific pain points — such as booking info being scattered across apps and emails, group trips being hard to coordinate, and plans falling apart when something unexpected happens mid-trip. These problem statements directly shaped the feature ideas we explored in the rest of this section.

[![Feature-narrowing ideation board](https://github.com/zeecool123/Codenection-/raw/main/assets/ideation/idea-narrowing-with-mentor-advice.png)](/zeecool123/Codenection-/blob/main/assets/ideation/idea-narrowing-with-mentor-advice.png)

We shortlisted five features across the trip lifecycle. Three were cut early because of privacy, technical-complexity, and timeline constraints. The remaining two — AI-driven recommendations and group preference matching — were brought to mentor consultation on 5 September; following the advice to focus on one core feature, we selected group preference matching as our MVP.

[![User POV design flow](https://github.com/zeecool123/Codenection-/raw/main/assets/ideation/user_pov_design_flow_2.png)](/zeecool123/Codenection-/blob/main/assets/ideation/user_pov_design_flow_2.png)

Once we settled on group preference matching as our core feature, we mapped the design from the user's point of view — starting with what a user would want at each stage, then designing the screen to answer that need. The host isn't locked into a single AI-generated route: they can keep combining and re-voting on favourite segments in a loop until the group reaches a route everyone's happy with, before the final itinerary is visualised on the map.

### 2.3 Mentor Consultation

#### 5 Sep 2026, 9:20 PM — Zach Khong

**Feedback received**
- **Idea:** Be original in how you present data. Maximise one core feature rather than spreading thin; users are usually not comfortable providing a lot of input.
- **Pitching:** Build the pitch around one core feature, rather than presenting a long feature list.
- **UI/UX:** Keep the interface simple.

**What we changed**
- Narrowed the app to one standout core feature instead of trying to solve every travel-planning pain point at once.
- Reduced the manual input expected from users by relying more on swipe and quick-choice interactions rather than forms.
- Simplified the UI direction so the core feature is clear, without extra functions competing for attention.

## 3. Prototype Walkthrough

### 3.1 Start a group trip

[![Radiant Route home page](https://github.com/zeecool123/Codenection-/raw/main/assets/prototype/01-home.png)](/zeecool123/Codenection-/blob/main/assets/prototype/01-home.png)

The landing page introduces Radiant Route and gives the host a clear **Plan New Trip** starting point for creating a collaborative trip.

### 3.2 Set up the trip group and preferences

[![New trip setup](https://github.com/zeecool123/Codenection-/raw/main/assets/prototype/02-trip-setup.png)](/zeecool123/Codenection-/blob/main/assets/prototype/02-trip-setup.png)

After selecting **Plan New Trip**, the host enters the trip's initial details, such as the destination, number of travellers, dates, and the group's interests. These inputs give the AI the context it needs to create relevant itinerary options.

### 3.3 Compare AI-generated routes and vote

[![AI-generated route choices](https://github.com/zeecool123/Codenection-/raw/main/assets/prototype/03-route-voting.png)](/zeecool123/Codenection-/blob/main/assets/prototype/03-route-voting.png)

The AI produces several route alternatives with different mixes of experiences. Each traveller can review the choices and vote for the route that best matches their preferences, whether that means culture, history, food, or another travel style.

### 3.4 Let the host choose how to decide

[![Host route decision options](https://github.com/zeecool123/Codenection-/raw/main/assets/prototype/04-host-decision.png)](/zeecool123/Codenection-/blob/main/assets/prototype/04-host-decision.png)

Once voting is complete, the host can either confirm the highest-voted route or ask the AI to combine ideas from the leading options into a more balanced itinerary for the group.

### 3.5 Select routes to integrate

[![Route integration selection](https://github.com/zeecool123/Codenection-/raw/main/assets/prototype/05-route-integration.png)](/zeecool123/Codenection-/blob/main/assets/prototype/05-route-integration.png)

For a balanced plan, the host selects the route options and preference mixes to integrate. This gives the group control over which experiences should be preserved in the new itinerary.

### 3.6 Review and vote on the balanced route

[![Integrated route detail](https://github.com/zeecool123/Codenection-/raw/main/assets/prototype/06-balanced-route.png)](/zeecool123/Codenection-/blob/main/assets/prototype/06-balanced-route.png)

Radiant Route presents a newly generated itinerary that combines the selected preferences. Travellers can inspect its route details, leave a review, and vote on the updated plan before the group finalises it.

### 3.7 Visualise the journey on a map

[![Route map and travel details](https://github.com/zeecool123/Codenection-/raw/main/assets/prototype/07-map-view.png)](/zeecool123/Codenection-/blob/main/assets/prototype/07-map-view.png)

The map view shows every stop in the itinerary and makes the journey easy to imagine. Travellers can see where they will go, how long each transfer takes, and whether to walk or use another mode of transport between stops.

## 4. What Makes Our Idea Different

**Core Functionality:** The AI agent groups the friends' pooled interests and generates distinct itinerary options, where each option is heavily anchored around a single, specific interest theme (e.g., Option 1 is 80% Food-focused, Option 2 is 80% History-focused).

**The Twist:** Unlike other apps that give everyone a watered-down, generic mix of everything, this app creates clear, intentionally biased archetypes. This allows the group to vote on a vibe or dominant theme for the itinerary, forcing a clear decision on what matters most to them. This way, all users can still be satisfied, since each can lean into the type of places they value more.

Secondly, traditional travel tools use static images linked to specific venue listings. Here, the visual preview dynamically adapts alongside the mutating AI itinerary, giving users instant visual context for every algorithmic modification — so they know what to expect at each place, offering more convenience than just googling a place and checking what to expect there.

## 5. Technical Architecture & Feasibility

### Tech Stack

| Components     | Technology | Reason for choice | Constraints |
| -------------- | ---------- | ----------------- | ----------- |
| Frontend       | React Native (JavaScript) | <ul><li>Cross-platform framework with mature Android support.</li><li>Allows the team to develop the mobile app using a single JavaScript codebase.</li><li>Large community and library ecosystem helps to build user interfaces and interactions efficiently.</li></ul> | <ul><li>May need to handle differences between Android devices.</li><li>External services such as Google Maps and Firebase need to be properly integrated with React Native.</li></ul> |
| Backend        | Django + Django REST Framework (Python) | <ul><li>Django provides a structured framework for developing the backend.</li><li>Django REST Framework allows the mobile app to communicate with the backend through APIs.</li><li>Provides a clear structure for managing data and API endpoints.</li></ul> | <ul><li>The team needs to design and connect multiple API endpoints for trips, groups, voting, and itineraries.</li><li>Additional configuration may be required when integrating third-party services such as Gemini.</li></ul> |
| Database       | PostgreSQL | <ul><li>Open-source relational database suitable for storing structured application data.</li><li>Works well with Django and supports relationships between users, trips, groups, itineraries and votes.</li><li>Supports flexible JSONB fields when needed for itinerary-related data.</li></ul> | <ul><li>The database schema needs to be planned carefully to manage relationships between different entities.</li><li>Changes to the schema during development may require corresponding backend adjustments.</li></ul> |
| AI Model       | Gemini 2.5 Flash | <ul><li>Fast response time makes it suitable for an itinerary planning experience.</li><li>Optimised for low latency and cost compared with larger models.</li><li>Can generate itinerary recommendations based on user preferences and trip information.</li></ul> | <ul><li>Dependent on Google API availability, rate limits, and available usage quotas.</li><li>AI-generated itineraries may not always be consistent or accurate, so prompts and outputs need to be handled carefully.</li></ul> |
| Maps & Places  | Google Maps Platform APIs | <ul><li>Provide location and route-related data needed by the application.</li><li>Supports map display, place information and route-related functionality.</li><li>Has strong support for Android and React Native map integration.</li></ul> | <ul><li>Requires proper API configuration and a billing account for Google Maps Platform services.</li><li>Usage limits and API key security need to be managed carefully.</li></ul> |
| Notifications  | Firebase Cloud Messaging (FCM) | <ul><li>Provide push notifications for important group activities.</li><li>Well supported on Android and integrates with React Native.</li><li>Suitable for push notification delivery without building a notification system from scratch.</li></ul> | <ul><li>Notification delivery depends on device permissions and network connectivity.</li><li>Needs to manage device tokens and configure FCM correctly.</li></ul> |
| Authentication | JWT (JSON Web Tokens) | <ul><li>Provides authentication between the React Native mobile app and Django backend.</li><li>Allows users to make authenticated API requests without repeatedly entering their login credentials.</li><li>Suitable for stateless REST API authentication.</li></ul> | <ul><li>The team needs to handle token expiration and refresh.</li><li>Tokens must be stored securely on the mobile device.</li></ul> |
| Hosting        | Render | <ul><li>Provides cloud hosting for the Django backend and PostgreSQL database.</li><li>Allows the mobile application to communicate with the backend through the internet.</li><li>Simple deployment reduces the need for the team to manage its own server infrastructure.</li></ul> | <ul><li>Free or limited hosting resources may affect backend performance.</li><li>Services may experience cold-start delays after periods of inactivity, depending on the hosting plan.</li><li>Requires internet connectivity for communication with the backend.</li></ul> |

### System Architecture Diagram

![System Architecture Diagram](https://github.com/user-attachments/assets/c8ca3b96-5eb9-4367-b3a8-6de8619a9dc7)

The React Native mobile app communicates with the Django REST API, which manages application data, authentication and integrations with AI, Maps and notification services.

### Build Plan & Scope

#### Build Plan

The prototype will be developed in phases, **prioritising the core features first** within the available building period. Supporting features will only be implemented after the core features are completed, allowing the team to focus its limited development time and resources on the main features.

**Phase 1 - Mobile App Foundation & Setup**
- Set up mobile app structure and navigation
- Build basic UI components
- Set up backend and database

↓

**Phase 2 - Trip & Group Management**
- Build trip setup and travel preferences
- Implement group creation and joining using a unique group code

↓

**Phase 3 - AI Itinerary Generation**
- Integrate the AI service
- Implement itinerary generation based on user preferences
- Generate 3 itinerary options

↓

**Phase 4 - Group Decision-Making**
- Implement itinerary review and voting
- Display voting results
- Implement host selection of 2 preferred plans for the AI Round 2 recommendations when needed

↓

**Phase 5 - Itinerary & Map**
- Build the daily itinerary view
- Integrate planned activities and locations
- Integrate the map to display the planned locations and routes

↓

**Phase 6 - Supporting Features**
- Implement essential supporting features such as notifications, sign out, and privacy settings
- Integrate all core modules

<br>

#### Prototype Scope

The prototype will focus on the core features needed to plan, compare, and decide on a solo or group trip: 
- Trip Setup
  - Users can set up a trip by selecting the destination, trip duration, number of travellers, and travel preferences.
- Group Creation
  - Users can create a travel group and invite other members using a unique group code.
- AI Itinerary Recommendations
  - AI generates **3 initial itinerary plans** based on user preferences and input.
- Group Voting & Review
  - Each group member can review the recommended plans and vote for their preferred itinerary. Users can review the voting results and determine the preferred plans.
- AI Round 2 Recommendation
  - The host can select **2 preferred plans**, which the AI combines to generate **1 additional itinerary** if there is no clear group preference.
- Itinerary & Map
  - Users can view the selected itinerary by day, including activities and locations, and view the planned locations and route on a map.

The goal is to demonstrate the complete journey from trip setup and AI recommendations to solo or group decision-making.

<br>

#### Out of Scope

To keep the prototype achievable within the available development time, the following features are outside the current scope:
- Flight and hotel booking
- Payment processing
- Full navigation or navigation guidance
- Real time traffic optimisations
- Real time weather forecasts
- Complex multi-city or multi-country trip planning
- Emergency trip replanning
- Integrations with travel booking platforms

These features may be considered for future development but are intentionally excluded from the prototype to keep the core experience focused and achievable.

