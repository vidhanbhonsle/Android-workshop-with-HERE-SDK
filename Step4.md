## Step 4 : Add an icon to the Map

### In MainActivity.java file, between handleAndroidPermissions(); and } add following code:

```java

    MapImage mapImage = MapImageFactory.fromResource(getApplicationContext().getResources(), R.drawable.home);
    MapMarker mapMarker = new MapMarker((new GeoCoordinates(52.530932, 13.384915)), mapImage);

    mapView.getMapScene().addMapMarker(mapMarker);

```

[![Foo](/img/s5.png)](https://github.com/vidhanbhonsle/Android-workshop-with-HERE-SDK/blob/master/Step5.md) 

