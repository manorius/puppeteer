<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Input](./puppeteer.protocol.input.md) &gt; [SynthesizeTapGestureRequest](./puppeteer.protocol.input.synthesizetapgesturerequest.md)

## Protocol.Input.SynthesizeTapGestureRequest interface

<b>Signature:</b>

```typescript
export interface SynthesizeTapGestureRequest 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [duration](./puppeteer.protocol.input.synthesizetapgesturerequest.duration.md) | [integer](./puppeteer.protocol.integer.md) | Duration between touchdown and touchup events in ms (default: 50). |
|  [gestureSourceType](./puppeteer.protocol.input.synthesizetapgesturerequest.gesturesourcetype.md) | [GestureSourceType](./puppeteer.protocol.input.gesturesourcetype.md) | Which type of input events to be generated (default: 'default', which queries the platform for the preferred input type). |
|  [tapCount](./puppeteer.protocol.input.synthesizetapgesturerequest.tapcount.md) | [integer](./puppeteer.protocol.integer.md) | Number of times to perform the tap (e.g. 2 for double tap, default: 1). |
|  [x](./puppeteer.protocol.input.synthesizetapgesturerequest.x.md) | number | X coordinate of the start of the gesture in CSS pixels. |
|  [y](./puppeteer.protocol.input.synthesizetapgesturerequest.y.md) | number | Y coordinate of the start of the gesture in CSS pixels. |

