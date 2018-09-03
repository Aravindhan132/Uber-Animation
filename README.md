# Uber Animation
Animate the camera on the map in the direction of the path represented by the first 2 points.
Start animating a marker moving along these 2 points (first and second).
When it reaches the second point, animate the camera so that it points to the third point.
Start animating a marker moving along these 2 points (second and third).

Animating the camera on the map is one of the many cool new features of the Google Maps Android API v2.

We’ll start our animation by simply animating to the different markers on the map. For the moment we won’t even take into account the bearing of the camera.

We’ve already placed a couple of markers on the map to get us started.

In order to animate the camera, we first need to define where it should be pointed at. We do this by building a new CameraPosition object.

