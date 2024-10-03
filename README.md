# SPACE DEORBITING SYSTEM(SDS)

- The SDS_prototype.html file is the working prototype of the software. It requires internet to work.
  - It takes 3-4 seconds to load.
  - Yellow dots are space debris, blue dots are satellites, and red dots are entities(debris/satellites) which are dangerous or endangered and qualify for deorbiting.
  - All dots can be clicked and their deorbiting path will be visible.
  - Double clicking on a dot allows you to follow it on its deorbiting path.

- The time wheel at the bottom left corner allows you to set the simulation as real-time(clicking the clock icon), or fast forward by dragging the scroller.

- Satellites far away from the earth will not be able to deorbit fully, as the animation possible in CesiumJS is limited to 1 day, whereas these far-away satellites might take months to reach the earth's surface.

- If you double click and follow the selected entity to the surface, the camera will be underground. You can use the "RESET VIEW" button on the top right corner to come back into default view.

- Thanks for viewing the project!
