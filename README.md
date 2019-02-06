### Mo.js
---
https://github.com/legomushroom/mojs

```js
const circle = new mojs.Shape({
  shape: 'circle',
  scale: { 0 : 1 },
  left: '25%',
  fill: {},
  radius: 25,
  duration: 2000,
  repeat: 999,
}).play();

const rect = new mojs.Shape({
  shape: "rect",
  left: "50%",
  fill: "none",
  radius: 20,
  stroke: { "rgba(0,255,255,1)": "megenta" },
  strokeWidth: { 10: 0 },
  strokeDasharray: "100%",
  strokeDahsoffset: { "-100%": "100%" },
  angle: { 0: 180 },
  duration: 2000,
  repeat: 999
}).play();

const polygon = new mojs.polygon({
  shape: "polygon",
  points: 5,
  left: "75%",
  fill: { deeppink: "#00F87F" },
  x: { "rand(-100%, -200%)": 0 },
  angle: { 0: "rand(0, 360)" },
  radius: 25,
  duration: 2000,
  repeat: 999
}).play();
```

```css
body, html {
  padding: 0;
}

body {
  background: rgba(241, 226, 215, 0.2);
}
```

```
```

