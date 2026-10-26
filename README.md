# Smart India Hackathon Workshop
# Date: 25.10.26
## Register Number: 212224040197
## Name: Mohanaprabha S
## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea
The proposed idea is to develop a Smart Railway Station Navigation System that helps passengers easily find platforms, ticket counters, restrooms, food courts, waiting halls, lifts, and other facilities inside railway stations.

The system provides interactive 2D/3D maps, step-by-step directions, voice-guided navigation, and real-time updates. Passengers can access it through a mobile application or touchscreen kiosks installed at railway stations. Special accessibility features support visually impaired passengers, senior citizens, and people with disabilities.

The system can also help railway staff update facility locations and provide information about platform changes or temporary closures. By reducing confusion and unnecessary movement, the solution aims to improve passenger convenience, accessibility, and crowd management.

## Proposed Solution / Architecture Diagram


## Use Cases
1.Finding Platforms: Passengers search for a platform number and receive directions from their current location.

2.Locating Facilities: Users find ticket counters, restrooms, drinking water, food courts, waiting halls, and enquiry counters.

3.Voice-Guided Navigation: Visually impaired passengers receive spoken directions to their destinations.

4.Accessible Routes: Senior citizens and passengers with disabilities can find routes using ramps, lifts, and accessible pathways.

5.Digital Kiosk Navigation: Tourists and passengers without the application can use touchscreen kiosks to locate station facilities.

6.Real-Time Platform Updates: Passengers receive updated directions when platform assignments or accessible routes change.

7.Multilingual Support: Users can select their preferred language to understand navigation instructions.

8.Railway Staff Management: Authorized staff update facility information, report temporary closures, and maintain station maps.


## Technology Stack
1. Mobile App: Flutter
2. Frontend: HTML, CSS, JavaScript, React.js
3. Backend: Node.js, Express.js
4. Database: PostgreSQL
5. Maps: Leaflet, OpenStreetMap
6. Route Calculation: Dijkstra’s Algorithm
7. Voice Navigation: Text-to-Speech (TTS)
8. Real-Time Updates: WebSockets
9. Cloud Hosting: AWS
10. Version Control: Git, GitHub


## Dependencies
1.Station Map Data: Accurate indoor maps showing platforms, entrances, exits, stairs, lifts, and other facilities.

2.Railway Information Access: Permission to access relevant railway information, including platform changes, train schedules, and service updates.

3.Location Identification: Suitable indoor positioning methods, such as QR codes, Bluetooth beacons, or Wi-Fi-based positioning, because GPS may not work reliably inside stations.

4.Real-Time Data Feeds: Reliable updates about platform changes, facility closures, and route restrictions.

5.Cloud and Network Connectivity: Hosting and communication infrastructure for mobile applications, kiosks, and staff dashboards.
