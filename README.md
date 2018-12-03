# DecodePolyline Android

An Android application to draw polyline on maps using encoded string.

```
@Override
public void onMapReady(GoogleMap googleMap) {
    mMap = googleMap;

    PolyUtils polyUtils = new PolyUtils(this, mMap, "{punAgqyhNIgAWAeE[iBKLh@VdA\\z@t@rALr@SrDdC@BHj@lDPvB?t@Ax@DRBf@Df@f@lFdHcBp@QnDy@jBi@bCiA|E_CrDaBhAu@BIWQ_BmCQF_C~@");
    polyUtils.start();
}
```
