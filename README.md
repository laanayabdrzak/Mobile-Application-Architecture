# Mobile Application Architecture

Broadly, there are **two categories** of mobile apps available:
    
 **View-heavy data-driven**
             
         Email, Social, News, Todo
    
 
 **Graphics-heavy drawing**
            
         Games, Creative Art, Photo Editing

I gonna focusing on **data-driven** apps.

## Screen Archtypes

- **Login**
- **Register**
- **Stream**
- **Detail**
- **Creation**
- **Profils**
- **Settings**
- **Maps**

## Application Architecture

Learning to build real **data-driven** apps requires a few core concepts:

- **Views:** Common Controls and View Layout

- **Events:** Interaction and Event Handling

- **Navigation:** Screen Flows and Navigation

- **Data:** Models, Networking and Persistence

- **Platform:** OS Services, Hardware, Accessing Sensors

Real **data-driven** apps usually require an API.

- Apps **display data** and this comes from a **source**.

- Most mobile apps rely on **server-side APIs** for data.

- When developing mobile, consider what sources your app's data is coming from / being saved to. 

- Many apps **leverage existing APIs** while others require a custom server-side component.

## Mobile Client Architecture

 [![CodePath](http://i.imgur.com/XgxWfyF.png)](http://codepath.com)
 
## Full Application Architecture

 [![CodePath](http://i.imgur.com/XgxWfyF.png)](http://codepath.com)
 
 
## Controllers

Controllers work with views and models to **implement dynamic behaviors** including:

-  Network requests (API interaction)

-  Persistence (Storing data)

-  Event handling (Button clicks, Data Input)

-  Navigation (Moving between app views)

## Views
 
 - Views **display data** or **receive data** inputs.

## Models

Models on mobile usually reflect the server state for **data retrieved via APIs** including:

- Model definitions (properties, relationships)

- JSON/XML serialization/deserialization

- Persistence Storage (database)

- Data Formatters
    
## Networking

Networking on mobile means **interacting with a server in** one of the following ways:

- Interacting with models via a REST API

- Displaying external images in the view

- Audio/video playback

- Socket programming (rare)
    
## Hardware

Leveraging **device features** including:

- Camera

- GPS

- Accelerometer

- Bluetooth, AirDrop

- Contacts, Calendar, SMS, Mail
    
## Architecture Review

In summary, we have reviewed:

- Mobile is growing fast and demand is high
- We are focusing on data-driven app development
- **Data-driven** apps require a server-side API
- All mobile development has a consistent architecture
- Mobile largely is **MVC + Networking + Hardware**

## Implementation

check this [app](https://github.com/laanayabdrzak/Android-Boilerplate)

## Contributors

[laanayabdrzak](https://github.com/laanayabdrzak)

<a href="https://www.linkedin.com/in/laanayabdrzak">
  <img alt="Follow me on LinkedIn"
       src="https://raw.githubusercontent.com/florent37/DaVinci/master/mobile/src/main/res/drawable-hdpi/linkedin.png" />
</a>

## Contributions
 
 Any contributions are welcome! :smile:

    
