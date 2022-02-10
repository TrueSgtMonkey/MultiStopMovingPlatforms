# MultiStopMovingPlatforms
Moving platforms that stop at multiple spots and loop back around on themselves in different ways

Necessary Features:
* Mutliple Spatials or 3D Coordinates to stop at.
  - Can use the Vector3 of a spatial or just a Vector3 location in general.
  - It will move like a normal moving platform (as seen in previous videos) to the next spot.
  - Instead of moving back, it will keep moving forward until the last Spatial/Vector3 is reached.
  
* Should have Looping Options.
  1. No Loop - means that it goes to the last location and then stops there.
  2. Linear Loop - Goes to the last location, stops there, and resets to the original location.
    (Based on if we want to reset with a signal or simply a timer after it completes)
  3. Ping Pong Loop - Goes to the last location, and then starts moving backwards until it reaches the first location.
    (Definitely the best loop imo)
    (It can also wait for a signal to start moving back to the original location)
