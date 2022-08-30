## This is a youtube video browser application implemented using vue.js.

## How to run this project?
- Install latest version of webpack and vue.js in your environment.
- Clone this repository to your local directory.
- open the **Video-Browser** directory in you code editor(ie. VSCode).
- enter into the **Video-Browser** directory using terminal and run the following commands serially:
  - ```npm install```
  - ```npm run serve```

## Components
- **App** component is responsible for binding all the components together.
- **SearchBar** component is responsible for the Searchbar.
- **VideoList** component is responsible for showing the video list. It shows a maximum list of 5 items, as youtube data api is configured by default.
- **VideoListItem** component is responsible for showing each item of the video search result.
- **VideoDetail** component is responsible for showing the details of a single video upon clicking on any search result video item.

**Main.js** file is connected with the main **App component** written inside the **App.vue** file. 

The **App** component is connected with 3 child components namely **VideoDetail**, **SearchBar** and **VideoList**. Among this 3 sibling components, only **VideoList** component has child component namely **VideoListItem**.


### Comments
- The video-browser won't work properly without enabling JavaScript. Please enable it if disabled.


