Create a landing page from your choice (React app )
Integrate google maps into your code.
The bloc of Google maps should be centralized in the middle to be well visualized
Use external libraries for design & good looking of your app

# React Google Maps

Implementing google maps in react using [google-map-react](https://www.npmjs.com/package/google-map-react)

```js
import "./App.css";
import GoogleMapReact from "google-map-react";

function App() {
  return (
    <div className="app">
      <h1>Google Maps</h1>

      <figure className="maps_wrapper">
        <GoogleMapReact
          defaultZoom={1}
          defaultCenter={{ lng: 3.3792, lat: 6.5244 }}
        />
      </figure>
    </div>
  );
}

export default App;
```
