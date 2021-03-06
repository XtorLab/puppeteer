<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Emulation](./puppeteer.protocol.emulation.md) &gt; [SetDeviceMetricsOverrideRequest](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.md)

## Protocol.Emulation.SetDeviceMetricsOverrideRequest interface

<b>Signature:</b>

```typescript
export interface SetDeviceMetricsOverrideRequest 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [deviceScaleFactor](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.devicescalefactor.md) | number | Overriding device scale factor value. 0 disables the override. |
|  [displayFeature](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.displayfeature.md) | [DisplayFeature](./puppeteer.protocol.emulation.displayfeature.md) | If set, the display feature of a multi-segment screen. If not set, multi-segment support is turned-off. |
|  [dontSetVisibleSize](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.dontsetvisiblesize.md) | boolean | Do not set visible view size, rely upon explicit setVisibleSize call. |
|  [height](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.height.md) | [integer](./puppeteer.protocol.integer.md) | Overriding height value in pixels (minimum 0, maximum 10000000). 0 disables the override. |
|  [mobile](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.mobile.md) | boolean | Whether to emulate mobile device. This includes viewport meta tag, overlay scrollbars, text autosizing and more. |
|  [positionX](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.positionx.md) | [integer](./puppeteer.protocol.integer.md) | Overriding view X position on screen in pixels (minimum 0, maximum 10000000). |
|  [positionY](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.positiony.md) | [integer](./puppeteer.protocol.integer.md) | Overriding view Y position on screen in pixels (minimum 0, maximum 10000000). |
|  [scale](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.scale.md) | number | Scale to apply to resulting view image. |
|  [screenHeight](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.screenheight.md) | [integer](./puppeteer.protocol.integer.md) | Overriding screen height value in pixels (minimum 0, maximum 10000000). |
|  [screenOrientation](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.screenorientation.md) | [ScreenOrientation](./puppeteer.protocol.emulation.screenorientation.md) | Screen orientation override. |
|  [screenWidth](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.screenwidth.md) | [integer](./puppeteer.protocol.integer.md) | Overriding screen width value in pixels (minimum 0, maximum 10000000). |
|  [viewport](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.viewport.md) | [Page.Viewport](./puppeteer.protocol.page.viewport.md) | If set, the visible area of the page will be overridden to this viewport. This viewport change is not observed by the page, e.g. viewport-relative elements do not change positions. |
|  [width](./puppeteer.protocol.emulation.setdevicemetricsoverriderequest.width.md) | [integer](./puppeteer.protocol.integer.md) | Overriding width value in pixels (minimum 0, maximum 10000000). 0 disables the override. |

