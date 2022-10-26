<div align="center">

  <h1>my own version React Splide using @gwroger/splidejs</h1>
  <p>added wheelLtR option for horizontal detection</p>

## Quick Start

Get the latest version from NPM:

```
$ npm install @gwroger/react-splide
```

Import CSS and components:

```jsx
import { Splide, SplideSlide } from "@gwroger/react-splide";
import "@gwroger/react-splide/css";

export function Slider() {
  return (
    <Splide
      options={{ rewind: true, wheel: true, wheelLtR: true }}
      aria-label="Example"
    >
      <SplideSlide>
        <img src="image1.jpg" alt="Image 1" />
      </SplideSlide>
      <SplideSlide>
        <img src="image2.jpg" alt="Image 2" />
      </SplideSlide>
    </Splide>
  );
}
```
