## 3.2.1 (2019-XX-XX)

- Add tooltip title
- Little adjustment for tooltip title
- Ignore location in infowindow if type is LineString


## 3.2.0 (2019-05-13)

- Use location as the default attribute for the coordinates attribute.
- Remove support for the deprecated `currentLocation` option used on the map
    widgets.


## 3.1.2 (2018-05-05)

- Fix some problems managing entity coordinates.


## 3.1.1 (2018-05-05)

- Fix bug managing object encoded input data. Fix #1


## 3.1.0 (2017-11-25)

* Support object encoded input throught the *PoI* input endpoint in addition
  to the already supported JSON encoded strings.
* Support to pass entity lists in addition to individual entities.
* Use entity lists when sending entities throught the output endpoint.
* Parse geo:json data when the attribute configured using the "Coordinates
  attribute" uses such a value.
* Use JSON.stringify to render structured values.


## 3.0.3

* Initial documentation of the operator.
* Support for custom marker icons (added a new setting for this purpose).


## 3.0

* Added support for entities using two attributes for the coordinates instead of the usual pattern of using one attribute for storing both the latitude and longitude.


## 2.99

Initial version
