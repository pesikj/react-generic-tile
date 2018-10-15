# Generic Tile
`react-generic-tile` is a **KPI tiles** built for React

## Installation
```
npm install react-generic-tile
```
or
```
yarn add react-generic-tile
```

## Example
```
import React from "react";
import ReactDOM from "react-dom";

import GenericTile from "react-generic-tile";

function App() {
  return (
    <div className="App">
      <GenericTile
        header={"Jessica Daniell"}
        subheader={"Senior Consultant, Department Sales & Distribution"}
        loading={false}
        number={"65.5"}
        scale={"MM"}
        color={"Good"}
        indicator={"Up"}
        footer={"This is only example.."}
      />
    </div>
  );
}

const rootElement = document.getElementById("root");
ReactDOM.render(<App />, rootElement);
```

