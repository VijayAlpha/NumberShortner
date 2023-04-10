# react-number-shortner

`react-number-shortner` is a React package that converts numbers into a formatted string with the appropriate symbol (k, m, b) based on the magnitude of the number.

## Installation

```sh
npm install react-number-shortner
```

## Usage
To use the package in your project, import the `NumberShortener` function from the package:

```javascript
import React from "react";
import NumberShortener  from "react-number-shortner";

function App() {
  return (
    <div>
      <NumberShortener number={12345} /> // Output: 12.3k
    </div>
  );
}

export default App;

```

## API
The `NumberShortener` function takes a single argument - the number to be formatted - and returns a string with the formatted number.

```typescript
numberFormat(number: number): string;
```
