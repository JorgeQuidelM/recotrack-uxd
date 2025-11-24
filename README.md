# RecoTrack UXD Project

User Experience Design (UXD) for **RecoTrack**, a mobile application created to provide real-time tracking of garbage collection trucks in Temuco, facilitating access to **schedules**, **smart alerts**, and **recycling points**.

---

## 📖 Index
- [🏁 Introduction](#-introduction)
- [🎯 UX Strategy](#-ux-strategy)
- [👷 Team & Roles](#-team--roles)
- [💡 Research and UX Elements](#-research-and-ux-elements)
- [🧩 Benchmark](#-benchmark)
- [👥 Personas](#-personas)
- [🗺️ Customer Journey](#%EF%B8%8F-customer-journey)
- [🧭 Navigation Flow](#-navigation-flow)
- [📲 Functional Wireframes (Low-Fi)](#-functional-wireframes-low-fi)
- [🔄 Interface Evolution](#-interface-evolution)
- [🎨 High-Fidelity Prototype](#-high-fidelity-prototype)
- [🩺 Heuristic Evaluation](#-heuristic-evaluation)
- [🔗 Resources](#-resources)
- [📜 License](#-license)

---

## 🏁 Introduction

### 1.1. Understanding the Context

In Temuco, garbage collection is scheduled on different days and at specific times across the various sectors of the city. Although information regarding these collection routes is available, it remains limited and does not account for service delays, early arrivals, or other potential disruptions.

As a consequence, residents are often left uncertain about the precise arrival time of collection trucks, which commonly results in two situations:

- Residents place their waste outside too early, leaving it exposed on the streets for extended periods
- Residents fail to put out their waste in time, leading to the accumulation of garbage within their homes

---
### 1.2. Proposed Solution

To address these challenges, we have proposed the development of a mobile application called **RecoTrack**, which enables residents of Temuco to track garbage collection trucks in real time and receive notifications when a truck is approaching their sector. This solution will allow residents to anticipate collection schedules, manage waste disposal more efficiently, and minimize unnecessary accumulation.

#### 📍 Real-Time Route Visualization

- Interactive city map showing garbage truck routes live
- Personalized route display tailored to the user's selected sector
- Integrated schedule details that enables users to anticipate service days and plan waste disposal accordingly

#### 🔔 Smart Notifications for Waste Disposal

- Alerts sent 5, 15, 30, or 60 minutes before truck arrival
- Notifications for garbage truck arrivals, recycling points, and temporary containers
- Reduces waste accumulation and improves collection efficiency
- Requires GPS, location access, and notification permissions

### ♻️ Recycling and Container Integration

- Map includes locations for recycling plastics, glass, batteries, and more
- Map also displays temporary container points requested from the municipality, with availability dates and times
- Route generation and directions to nearest recycling stations or active temporal containers
- Promotes proper waste separation and reduces contamination

### 📡 GPS-Based Truck Tracking

- Mobile GPS devices installed in trucks
- Enables accurate location data and predictive route modeling
- Supports dynamic scheduling and operational optimization

---

## 👷 Team & Roles

| Member | Role |
|---|---|
| **Jorge Quidel** | Project Manager & Presenter |
| **José Alonso** | UX/UI Designer |
| **Agustín Raposo** | UX Research & Analysis |

---

## 🎯 UX Strategy
**Objective:** Enhance the citizen experience with hyperlocal and reliable information.  
**Result:** Prioritized functionalities include a live map, proximity alerts, and a neighborhood-based schedule.

### Value Proposition Canvas
Value Proposition Canvas aligning RecoTrack’s services with user needs, identifying pain relievers, gains, and core benefits such as real-time tracking and improved neighborhood organization.
<p align="center"><img src="./assets/value_proposition_canvas.png" width="720"/></p>

---

## 💡 Research and UX Elements
| UX Level | Focus | Techniques |
|---|---|---|
| **Strategy** | Needs and objectives | Interviews, observation |
| **Scope** | Requirements | Listing and prioritization |
| **Structure** | IA / Flows | Navigation diagrams |
| **Skeleton** | Interaction / Layout | Low-Fi Wireframes |
| **Surface** | UI | Hi-Fi Prototypes |

---

## 🧩 Benchmark
Benchmark analysis comparing RecoTrack with competitors like Línea Verde, Komtainer, and iRecycle. Highlights differentiating features such as real-time routes, user alerts, and eco-education.
<p align="center"><img src="./assets/benchmark_canvas.png" width="720"/></p>

---

## 👥 Personas
User persona representing a homemaker who values cleanliness and organization. Juana symbolizes users managing family routines and seeking reliable waste collection information.
<p align="center"><img src="./assets/persona_ux_1.png" width="720"/><br/></p>

User persona representing an independent young professional. Tomás embodies tech-savvy users who balance work and home tasks, needing efficient digital tools for waste management.
<p align="center"><img src="./assets/persona_ux_2.png" width="720"/><br/></p>

User persona representing a community leader. Carmen reflects socially active users engaged in neighborhood well-being and environmental awareness.
<p align="center"><img src="./assets/persona_ux_3.png" width="720"/></p>

---

## 🗺️ Customer Journey
Customer Journey Map outlining user interactions across five stages: Awareness, Consideration, Installation, Familiarization, and Daily Use. Emphasizes emotional transitions and app touchpoints.
<p align="center"><img src="./assets/customer_journey_map.png" width="960"/></p>

---

## 🧭 Navigation Flow
App navigation flow showing the main structure of RecoTrack, from login and guest sessions to the core sections such as Home-Map, Calendar, EcoTips, and Community. The flow illustrates user accessibility and logical screen hierarchy.
<p align="center"><img src="./assets/navigation.png" width="960"/></p>

---

## 📲 Functional Wireframes (Low-Fi)

### 🏠 Home and Authentication
Simple welcome and access through **login**, **register**, or **guest mode**.
<p align="center">
  <img src="./assets/welcome.png" width="360" alt="Welcome" />
  <img src="./assets/login.png" width="360" alt="Login" />
  <img src="./assets/register.png" width="360" alt="Register" />
</p>

### 🗺️ Maps and Location
Real-time map with **route**, **truck position**, and **directions**.
<p align="center">
  <img src="./assets/mapa_general.png" width="360" alt="General Map" />
  <img src="./assets/mapa_detalles.png" width="360" alt="Detailed Map" />
  <img src="./assets/mapa_indicaciones.png" width="360" alt="Map Directions" />
</p>

### 🗓️ Calendar
Displays **collection days** by sector.
<p align="center">
  <img src="./assets/calendar.png" width="360" alt="Calendar" />
  <img src="./assets/calendar_detail.png" width="360" alt="Calendar Detail" />
</p>

### 👤 Profile, Address and Settings
Profile management and **alert/map preferences**.
<p align="center">
  <img src="./assets/perfil.png" width="360" alt="Profile" />
  <img src="./assets/domicilio.png" width="360" alt="Address" />
  <img src="./assets/settings.png" width="360" alt="Settings" />
</p>

### 🌱 Ecotips
Environmental education: tips, recycling guides, and contact details.
<p align="center">
  <img src="./assets/ecotips.png" width="360" alt="Ecotips" />
  <img src="./assets/ecotips_1.png" width="360" alt="Ecotips 1" />
  <img src="./assets/ecotips_2.png" width="360" alt="Ecotips 2" />
  <img src="./assets/ecotips_3.png" width="360" alt="Ecotips 3" />
</p>

---

## 🔄 Interface Evolution
- Expanded **map area** for better visibility.  
- **Permissions** explained before requesting GPS/Notifications.  
- Added **guest mode** to reduce onboarding friction.  
- **Alert presets** at 5/15/30/60 minutes.  
- **Special pickup** feature included based on community requests.

---

## 🎨 High-Fidelity Prototype

### 🟢 Onboarding and Access
This category presents the initial user flow of RecoTrack, including the welcome, login, and registration screens. It allows users to quickly access the app—either by signing in, creating an account, or entering as guests—ensuring a smooth and intuitive start to the experience.
<p align="center">
  <img src="./assets/Init.png" width="360" alt="" />
  <img src="./assets/Login.png" width="360" alt="" />
  <img src="./assets/Register.png" width="360" alt="" />
</p>

### 🗺️ Map and Navigation
This category displays the navigation system that guides users to their waste collection or recycling destinations in real time. The interface provides clear directions and estimated arrival times, helping users anticipate when the garbage truck will reach their area. The visual route on the map, along with intuitive icons and prompts, ensures a smooth and practical navigation experience aligned with RecoTrack’s goal of improving urban waste management efficiency.
<p align="center">
  <img src="./assets/19d0e6bd-ddf7-4a5b-87ee-7fde8509ace2.png" width="360" alt="Map Hi-Fi 1" />
  <img src="./assets/484a1230-eadd-4eb2-a718-69f1b98639c7.png" width="360" alt="Map Hi-Fi 2" />
</p>

### 🕓 Collection Schedules
This category presents the weekly garbage collection schedules organized by neighborhood sectors. Each screen displays the route and the specific collection days for each zone, allowing users to easily check when and where waste pickup will occur. The visual layout combines maps with clear time slots, helping users plan their waste disposal efficiently and stay aligned with their local collection timetable.
<p align="center">
  <img src="./assets/Calendar.png" width="360" alt="Schedule Hi-Fi" />
  <img src="./assets/CalendarDetail.png" width="360" alt=""/>
  <img src="./assets/CalendarDetail2.png" width="360" alt=""/>
  <img src="./assets/CalendarDetail3.png" width="360" alt=""/>
</p>

### 👤 Profile and Configuration
This category showcases the user’s personal profile and customizable settings within RecoTrack. Users can add their address for location-based services, adjust alert preferences, and manage map display options such as showing recycling points or specific truck routes. The clean and intuitive interface allows for a personalized experience, ensuring that notifications and navigation align with each user’s daily routine and environmental goals.
<p align="center">
  <img src="./assets/810acbd4-69c9-4cc0-936d-e81c43d5c87e.png" width="360" alt="Profile Hi-Fi" />
  <img src="./assets/a3fc7439-ea3f-4e65-b18c-26905df831b4.png" width="360" alt="" />
  <img src="./assets/d0818c4d-cd20-4198-a03e-3eb42d406619.png" width="360" alt="" />
</p>

### ♻️ Ecotips
This category focuses on promoting environmental awareness and sustainable habits among users. It includes practical advice on managing household waste, recycling correctly, and reducing disposable product use. Through sections like “How to Recycle” and “Managing My Waste,” users can explore step-by-step eco-friendly practices. Additionally, the “Contact Us” section connects users with RecoTrack and local institutions, reinforcing collaboration toward a cleaner and more sustainable community.
<p align="center">
  <img src="./assets/Ecotips.png" width="360" alt="" />
  <img src="./assets/Ecotips2.png" width="360" alt="Ecotips Home Hi-Fi" />
  <img src="./assets/Ecotips3.png" width="360" alt=""/>
  <img src="./assets/Contact.png" width="360" alt=""/>
</p>

---

## 🩺 Heuristic Evaluation

Following the development of the high‑fidelity prototype, a heuristic evaluation was performed on the interfaces. This process revealed several usability shortcomings, primarily stemming from inconsistencies in interface elements, and resulted in an average SUS score of 60, which is considered below the acceptable benchmark. In response, the design of the final UI version prioritized resolving the most significant issues identified during the evaluation.

---

| **Problem**                                                  | **Solution**                                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| User account registration was unjustified, as the experience did not require persistent information storage. | The user account functionality was removed. Instead, the application only stores the address provided by the user. |

<p>
  <img src="./assets/heuristic-ev-1.png" width="360" alt="Heuristic Evaluation 1" />
</p>

---

| **Problem**                                                  | **Solution**                                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Ambiguity in the schedule format: the representation used for the details of a route created multiple uncertainties. | The schedule format was enhanced to include additional details such as the month, exact collection time, and information about each stop. |

<p>
  <img src="./assets/heuristic-ev-2.png" width="360" alt="Heuristic Evaluation 2" />
</p>

---

| **Problem**                                                  | **Solution**                                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Missing standard usability controls in critical flows. Common icons and buttons were absent, and the option “Search your address on the map” was not presented as a clear button. | Added explicit buttons and dedicated sections for entering and selecting the address on the map. |

<p>
  <img src="./assets/heuristic-ev-3.png" width="360" alt="Heuristic Evaluation 3" />
</p>

---

## 🎨 Improved Prorotype

### Home and Widget
On the home screen, a widget can display relevant information such as the garbage truck’s current location or the next scheduled pickup.
<p align="center">
  <img src="./assets/home.png" width="360" alt="Widget before pickup" />
  <img src="./assets/home-2.png" width="360" alt="Widget after pickup" />
</p>

### 🟢 Onboarding and Access
After the splash screen, the application takes the user directly to the address entry screen. Once the address is entered, the user can access the application.
<p align="center">
  <img src="./assets/splash.png" width="360" alt="Splash screen" />
  <img src="./assets/address.png" width="360" alt="Insert address" />
  <img src="./assets/address-2.png" width="360" alt="Confirm address" />
</p>

### 🎓 Tutorial
Before gaining full access, the application presents a quick tutorial explaining how the maps work.
<p align="center">
  <img src="./assets/tutorial.png" width="360" alt="Tutorial part 1" />
  <img src="./assets/tutorial-2.png" width="360" alt="Tutorial part 2" />
  <img src="./assets/tutorial-3.png" width="360" alt="Tutorial part 3" />
</p>

### 🗺️ Map and Navigation
The application displays not only recycling points but also temporary containers nearby, providing directions to both types of locations from the user’s current position. It also stores app notifications for later access.

<p align="center">
  <img src="./assets/map.png" width="360" alt="Map Hi-Fi 1" />
  <img src="./assets/map-2.png" width="360" alt="Map Hi-Fi 2" />
  <img src="./assets/map-3.png" width="360" alt="Map Hi-Fi 2" />
</p>

### 🕓 Collection Routes
The application provides detailed information about the different garbage collection routes in Temuco. A search bar and filters allow for more refined searches, and users can also view details about the stops along each route and the collection schedule.

<p align="center">
  <img src="./assets/routes.png" width="360" alt="Routes" />
  <img src="./assets/filters.png" width="360" alt="Filters" />
  <img src="./assets/routes-2.png" width="360" alt="Routes Detail"/>
</p>

### ♻️ Ecotips
The content of these sections was rearranged to improve readability and comprehension.
<p align="center">
  <img src="./assets/ecotips.png" width="360" alt="Ecotips" />
  <img src="./assets/ecotips-2.png" width="360" alt="Ecotips content part 1" />
  <img src="./assets/ecotips-3.png" width="360" alt="Ecotips content part 2"/>
  <img src="./assets/ecotips-4.png" width="360" alt="Ecotips content part 3"/>
  <img src="./assets/ecotips-5.png" width="360" alt="Ecotips recycling"/>
  <img src="./assets/contacts.png" width="360" alt="Contact us"/>
</p>

### ⚙️ Settings
Since the accounts feature was removed, this section now focuses on general settings for the map and notifications.
<p align="center">
  <img src="./assets/settings.png" width="360" alt="Settings" />
  <img src="./assets/settings-2.png" width="360" alt="Map settings" />
  <img src="./assets/settings-3.png" width="360" alt="Alerts settings" />
</p>

---

## 🔗 Resources

Figma Wireframe & Prototype: [RecoTrack](https://www.figma.com/design/LT7WAZXoFXdRK8uyBaTN49/RecoTrack)

---

## 📜 License
**MIT License — 2025 RecoTrack UXD Project**
