# 📖 State of HTML 2025 – Reading List

## 📑 Table of Contents
- [Form Controls](#-form-controls)
  - [Datalist](#datalist)
  - [input.showPicker()](#inputshowpicker)
  - [Customizable Select](#customizable-select)
  - [Wide Gamut & Transparency in Color Pickers](#wide-gamut--transparency-in-color-pickers)
- [Content Editing](#-content-editing)
  - [contenteditable="plaintext-only"](#contenteditableplaintext-only)
- [Disclosure & Accordions](#-disclosure--accordions)
  - [<details>](#details)
  - [Exclusive Accordion](#exclusive-accordion)
- [Dialogs & Popovers](#-dialogs--popovers)
  - [<dialog>](#dialog)
  - [dialog.requestClose()](#dialogrequestclose)
  - [Popover API](#popover-api)
- [DOM APIs](#-dom-apis)
  - [Invoker Commands API](#command--commandfor-invoker-commands-api)
  - [Element.before()](#elementbefore)
  - [Element.moveBefore()](#elementmovebefore)
- [Graphics & 3D](#-graphics--3d)
  - [Canvas colorSpace](#canvas-colorspace)
  - [ctx.drawElement()](#ctxdrawelement)
  - [3D & AR/VR](#3d--arvr)
    - [<model>](#model-element)
    - [WebXR](#webxr)
    - [WebGPU](#webgpu)
    - [WebGL](#webgl)
- [Media & Images](#-media--images)
  - [JPEG XL](#jpeg-xl)
- [Math & Maps](#-math--maps)
  - [MathML](#mathml)
  - [MapML](#mapml)
- [Security](#-security)
  - [CSP](#csp)
  - [Sanitizer API](#sanitizer-api)
- [Attributes](#-attributes)
  - [hidden="until-found"](#hiddenuntil-found)
  - [fetchpriority](#fetchpriority)
  - [blocking="render"](#blockingrender)
- [Intl APIs](#-intl-apis)
  - [Intl.Segmenter](#intlsegmenter)
  - [Intl.Locale](#intllocale)
- [HTML Modules & Templates](#-html-modules--templates)
  - [HTML Modules](#html-modules)
  - [<template>](#template)

---

## 📝 Form Controls

### **Datalist**
Method of providing a list of presets for a user to select in a form control, while still allowing custom options.

- [MDN: datalist](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist)  
- [HTML Spec: datalist](https://html.spec.whatwg.org/)

---

### **`input.showPicker()`**
Programmatically open the picker of form controls that have one (color pickers, date inputs etc).

- [MDN: showPicker()](https://developer.mozilla.org/en-US/docs/Web/API/HTMLInputElement/showPicker)  
- [HTML Spec: HTMLInputElement.showPicker](https://html.spec.whatwg.org/)  
- [GitHub: Issue #688 – w3ctag/design-reviews](https://github.com/w3ctag/design-reviews/issues/688)

---

### **Customizable Select**
Stylable, customizable dropdown control. Previously `<selectlist>` and `<selectmenu>`.

- [Customizable Select Element (Explainer) – open-ui.org](https://open-ui.org)  
- [State of CSS 2022 – web.dev](https://web.dev)  
- [The selectmenu HTML Tag – CSS-Tricks](https://css-tricks.com)  
- [Advanced Form Control Styling – Smashing Magazine](https://smashingmagazine.com)  
- [Two levels of customising – hidde.blog](https://hidde.blog)  
- [Open UI selectmenu demos – microsoftedge.github.io](https://microsoftedge.github.io)

---

### **Wide Gamut & Transparency in Color Pickers**
- [Add wide gamut P3 and alpha transparency – WebKit](https://webkit.org)  
- [HTML Spec](https://html.spec.whatwg.org/)

---

## 📝 Content Editing

### **`contenteditable="plaintext-only"`**
Permits editing of raw text but not rich text formatting.

- [MDN: contenteditable](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/contenteditable)  
- [HTML Spec](https://html.spec.whatwg.org/)

---

## 📝 Disclosure & Accordions

### **`<details>`**
A disclosure widget that can be toggled to hide or show content interactively.

- [MDN: details](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details)  
- [HTML Spec](https://html.spec.whatwg.org/)

### **Exclusive Accordion**
Group `<details>` so that only one is open at a time.

- [GitHub PR: Add `name` attribute](https://github.com/whatwg/html/pull/9400)  
- [GitHub Issue #866 – w3ctag/design-reviews](https://github.com/w3ctag/design-reviews/issues/866)  
- [Explainer – Open UI](https://open-ui.org)  
- [Chrome Platform Status](https://chromestatus.com)

---

## 📝 Dialogs & Popovers

### **`<dialog>`**
Dialog that can be dismissed by clicking outside (light dismiss).

- [MDN: dialog](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/dialog)  
- [HTML Spec](https://html.spec.whatwg.org/)

### **`dialog.requestClose()`**
Cancelable close method for dialogs.

- [MDN: requestClose](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDialogElement/requestClose)  
- [HTML Spec](https://html.spec.whatwg.org/)

### **Popover API**
Popover attribute + JS API for overlays, popups, menus etc.

- [MDN: Popover API](https://developer.mozilla.org/en-US/docs/Web/API/Popover_API)  
- [HTML Spec](https://html.spec.whatwg.org/)  
- [GitHub: Issue #743 – w3ctag/design-reviews](https://github.com/w3ctag/design-reviews/issues/743)  
- [Explainer – Open UI](https://open-ui.org)

---

## 📝 DOM APIs

### **Command & Commandfor (Invoker Commands API)**
Declarative way for `<button>` to invoke predefined custom commands.

- [MDN: Invoker Commands API](https://developer.mozilla.org/en-US/docs/Web/API/Invoker_Commands_API)  
- [Explainer – Open UI](https://open-ui.org)  
- [CSS-Tricks: Invoker Commands](https://css-tricks.com)

### **Element.before()**
Insert node before another.

- [MDN: Element.before()](https://developer.mozilla.org/en-US/docs/Web/API/Element/before)

### **Element.moveBefore()**
Move node before another while preserving state.

- [MDN: Element.moveBefore()](https://developer.mozilla.org/en-US/docs/Web/API/Element/moveBefore)  
- [Chrome Dev Blog](https://developer.chrome.com)

---

## 📝 Graphics & 3D

### **Canvas colorSpace**
Set color space for `<canvas>`.

- [MDN: getContext](https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/getContext)  
- [WebKit: Wide Gamut 2D Graphics](https://webkit.org)

### **ctx.drawElement()**
Draw HTML element on canvas.

---

### **3D & AR/VR**

#### **`<model>` Element**
- [Spec – immersive-web](https://immersive-web.github.io)  
- [Test page – keithclark.co.uk](https://keithclark.co.uk)  
- [CSS-Tricks: AR/VR/3D in HTML](https://css-tricks.com)  
- [Safari Tech Preview Notes](https://developer.apple.com)

#### **WebXR**
- [MDN: WebXR Device API](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API)

#### **WebGPU**
- [MDN: WebGPU](https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API)  
- [Chrome Dev Blog](https://developer.chrome.com)  
- [WebKit demos](https://webkit.org)

#### **WebGL**
- [MDN: WebGL Getting Started](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial/Getting_started_with_WebGL)

---

## 📝 Media & Images

### **JPEG XL**
- [JPEG XL – jpeg.org](https://jpeg.org)

---

## 📝 Math & Maps

### **MathML**
- [MDN: MathML](https://developer.mozilla.org/en-US/docs/Web/MathML/Element/math)

### **MapML**
Embed interactive maps in HTML. *(Spec pending)*

---

## 📝 Security

### **CSP**
Content-Security Policy.

- [MDN: CSP](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)

### **Sanitizer API**
`element.setHTML()` and `Document.parseHTML()` for safe DOM updates.

- [MDN: HTML Sanitizer API](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Sanitizer_API)

---

## 📝 Attributes

### **hidden="until-found"**
- [MDN: hidden attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Global_attributes/hidden)  
- [Chrome Dev Blog: until-found](https://developer.chrome.com)

### **fetchpriority**
- [MDN: fetchPriority](https://developer.mozilla.org/en-US/docs/Web/API/HTMLImageElement/fetchPriority)  
- [Chrome Dev Blog](https://web.dev)

### **blocking="render"**
Block rendering until resources load. Applies to `<link>`, `<script>`, `<style>`.

---

## 📝 Intl APIs

### **Intl.Segmenter**
- [MDN: Intl.Segmenter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Segmenter)

### **Intl.Locale**
- [MDN: Intl.Locale](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale)

---

## 📝 HTML Modules & Templates

### **HTML Modules**
Import HTML via JS imports.  

- [Explainer – GitHub](https://github.com)  
- [Chrome Platform Status](https://chromestatus.com)

### **`<template>`**
Hold HTML fragments for later use.

- [MDN: template](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)  
- [HTML Spec](https://html.spec.whatwg.org/)
