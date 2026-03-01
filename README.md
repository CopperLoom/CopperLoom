### 👋 Hi, I'm CopperLoom

Currently working on **[biquad-fit](https://github.com/CopperLoom/biquad-fit)** — a JavaScript port of the [AutoEq](https://github.com/jaakkopasanen/AutoEq) optimizer.

Given a measured headphone frequency response and a target curve (e.g. Harman IE 2019), it computes the optimal set of parametric EQ biquad filters — frequency, gain, and Q — to bring the two into alignment. Zero dependencies. Works in Node.js and the browser.
```js
const { pregain, filters } = optimize(measured, target, { maxFilters: 5 });
// → [{ type: 'PK', fc: 4800, gain: -3.2, Q: 1.4 }, ...]
```

**v1.0 stable** · 274 tests passing · MIT license
