# Lab 6 - *Photo Map*

**Name of your app** is an app that allows the user to search for locations using the [Foursquare API](https://developer.foursquare.com/docs) and create a pin with an image annotation.

Time spent: **2** hours spent in total

## User Stories

The following **required** user stories are complete:

- [x] User can view a map (+2pt)
- [x] User can take a photo (+1pt)
- [x] User can tag a location (+1pt)
- [x] User can drop a pin with image annotation (+1pt)

The following **stretch** user stories are implemented:

- [x] User sees a custom annotation (+1pt)
- [x] User can see Fullscreen Picture (+1pt)
- [x] User sees a custom image for the "pin" (+1pt)

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1.  For step 3-2 "Set the delegate from the prepareForSegue method of PhotoMapViewController" was not helpful in telling the student what to perform. what needed to be done in the prepareForSegue method  "let vc = segue.destination as? LocationsViewController
vc?.delegate = self"
2.  Change MKPinAnnotationView to MKAnnotationView in the "mapView(_ mapView: MKMapView, viewFor annotation: MKAnnotation)" method to get the image instead of red pin.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src="/gifs/Photo_Map.gif?raw=true" width="" alt= 'Video Walkthrough'>

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## License

Copyright [2018] [Eli Armstrong]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
