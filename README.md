# Wind

Wind is a compact framework for applying CSS properties using classes.
The framework needs CSS variables to function correctly.
You can supply your own CSS variables or use the default file `_variables.css`, which can be found in the `source` folder.

## Usage

Just apply the classes you want to your HTML using the class attributes.
If for instance you want to add `text-align: center` and add a large `margin-bottom` below an `h1`:

```html
<div class="text-align-center">
    <h1 class="margin-bottom-large">I'm centered now</h1>
</div>
```

As you can see, each CSS class represents one CSS property.
There are some exceptions:
* `display-*-mobile` classes are using a media query
* `margin-x-`, `margin-y-`, `padding-x-` and `padding-y-` classes are setting two paddings and margins at the same time

## Supported Properties

|CSS property|Wind classes|
|---|---|
|[align-content](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)|align-content-center<br>align-content-flex-end<br>align-content-space-around<br>align-content-space-between<br>align-content-start<br>align-content-stretch|
|[align-items](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)|align-items-baseline<br>align-items-center<br>align-items-flex-end<br>align-items-flex-start<br>align-items-stretch<br>|
|[align-self](https://developer.mozilla.org/en-US/docs/Web/CSS/align-self)|align-self-baseline<br>align-self-center<br>align-self-flex-end<br>align-self-flex-start<br>align-self-stretch<br>|
|[background-color](https://developer.mozilla.org/en-US/docs/Web/CSS/background-color)|background-color-danger<br>background-color-info<br>background-color-success<br>background-color-transparent<br>background-color-warning|
|[border-radius](https://developer.mozilla.org/en-US/docs/Web/CSS/border-radius)|border-radius-small<br>border-radius-medium<br>border-radius-large|
|[border-style](https://developer.mozilla.org/en-US/docs/Web/CSS/border-style)|border-style-none<br>border-bottom-style-none<br>border-left-style-none<br>border-right-style-none<br>border-top-style-none<br>border-style-solid<br>border-bottom-style-solid<br>border-left-style-solid<br>border-right-style-solid<br>border-top-style-solid|
|[border-width](https://developer.mozilla.org/en-US/docs/Web/CSS/border-width)|border-width-none<br>border-width-small<br>border-width-medium<br>border-width-large<br>border-bottom-width-none<br>border-bottom-width-small<br>border-bottom-width-medium<br>border-bottom-width-large<br>border-left-width-none<br>border-left-width-small<br>border-left-width-medium<br>border-left-width-large<br>border-right-width-none<br>border-right-width-small<br>border-right-width-medium<br>border-right-width-large<br>border-top-width-none<br>border-top-width-small<br>border-top-width-medium<br>border-top-width-large|
|[color](https://developer.mozilla.org/en-US/docs/Web/CSS/color)|color-inherit|
|[column-gap](https://developer.mozilla.org/en-US/docs/Web/CSS/column-gap)|column-gap-xsmall<br>column-gap-small<br>column-gap-medium<br>column-gap-large<br>column-gap-xlarge<br>column-gap-xxlarge|
|[cursor](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor)|cursor-all-scroll<br>cursor-cell<br>cursor-col-resize<br>cursor-crosshair<br>cursor-ew-resize<br>cursor-grab<br>cursor-grabbing<br>cursor-help<br>cursor-not-allowed<br>cursor-move<br>cursor-nesw-resize<br>cursor-ns-resize<br>cursor-nwse-resize<br>cursor-pointer<br>cursor-progress<br>cursor-row-resize<br>cursor-text<br>cursor-wait<br>cursor-zoom-in<br>cursor-zoom-out|
|[display](https://developer.mozilla.org/en-US/docs/Web/CSS/display)|display-block<br>display-flex<br>display-inline<br>display-inline-block<br>display-inline-flex<br>display-none<br>display-block-mobile<br>display-inline-mobile<br>display-inline-block-mobile<br>display-none-mobile|
|[flex-direction](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)|flex-direction-column<br>flex-direction-column-reverse<br>flex-direction-row<br>flex-direction-row-reverse|
|[flex-grow](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-grow)|flex-grow-0<br>flex-grow-1|
|[flex-shrink](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-shrink)|flex-shrink-0<br>flex-shrink-1|
|[flex-wrap](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-wrap)|flex-wrap-nowrap<br>flex-wrap-wrap|
|[font-family](https://developer.mozilla.org/en-US/docs/Web/CSS/font-family)|font-family-monospace|
|[font-size](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size)|font-size-xsmall<br>font-size-small<br>font-size-medium<br>font-size-large<br>font-size-xlarge<br>font-size-xxlarge|
|[font-style](https://developer.mozilla.org/en-US/docs/Web/CSS/font-style)|font-style-italic<br>font-style-normal|
|[font-weight](https://developer.mozilla.org/en-US/docs/Web/CSS/font-weight)|font-weight-100<br>font-weight-200<br>font-weight-300<br>font-weight-400<br>font-weight-500<br>font-weight-600<br>font-weight-700<br>font-weight-800<br>font-weight-900|
|[height](https://developer.mozilla.org/en-US/docs/Web/CSS/height)|height-25<br>height-33<br>height-50<br>height-66<br>height-75<br>height-100<br>height-100px<br>height-200px<br>height-300px<br>height-100vh|
|[justify-content](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)|justify-content-center<br>justify-content-flex-end<br>justify-content-flex-start<br>justify-content-space-around<br>justify-content-space-between<br>justify-content-space-evenly|
|[line-height](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height)|line-height-xsmall<br>line-height-small<br>line-height-medium<br>line-height-large<br>line-height-xlarge|
|[margin](https://developer.mozilla.org/en-US/docs/Web/CSS/margin)|margin-bottom-xsmall<br>margin-bottom-small<br>margin-bottom-medium<br>margin-bottom-large<br>margin-left-xsmall<br>margin-left-small<br>margin-left-medium<br>margin-left-large<br>margin-right-xsmall<br>margin-right-small<br>margin-right-medium<br>margin-right-large<br>margin-top-xsmall<br>margin-top-small<br>margin-top-medium<br>margin-top-large<br>margin-x-auto<br>margin-x-xsmall<br>margin-x-small<br>margin-x-medium<br>margin-x-large<br>margin-y-xsmall<br>margin-y-small<br>margin-y-medium<br>margin-y-large<br>|
|[overflow](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow)|overflow-x-auto<br>overflow-x-hidden<br>overflow-x-scroll<br>overflow-x-visible<br>overflow-y-auto<br>overflow-y-hidden<br>overflow-y-scroll<br>overflow-y-visible|
|[padding](https://developer.mozilla.org/en-US/docs/Web/CSS/padding)|padding-bottom-xsmall<br>padding-bottom-small<br>padding-bottom-medium<br>padding-bottom-large<br>padding-left-xsmall<br>padding-left-small<br>padding-left-medium<br>padding-left-large<br>padding-right-xsmall<br>padding-right-small<br>padding-right-medium<br>padding-right-large<br>padding-top-xsmall<br>padding-top-small<br>padding-top-medium<br>padding-top-large<br>padding-x-xsmall<br>padding-x-small<br>padding-x-medium<br>padding-x-large<br>padding-y-xsmall<br>padding-y-small<br>padding-y-medium<br>padding-y-large<br>|
|[text-align](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align)|text-align-center<br>text-align-left<br>text-align-right|
|[text-decoration](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration)|text-decoration-line-through<br>text-decoration-none<br>text-decoration-underline|
|[text-transform](https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform)|text-transform-capitalize<br>text-transform-lowercase<br>text-transform-uppercase|
|[vertical-align](https://developer.mozilla.org/en-US/docs/Web/CSS/vertical-align)|vertical-align-baseline<br>vertical-align-bottom<br>vertical-align-middle<br>vertical-align-sub<br>vertical-align-super<br>vertical-align-text-bottom<br>vertical-align-text-top<br>vertical-align-top|
|[visibility](https://developer.mozilla.org/en-US/docs/Web/CSS/visibility)|visibility-hidden<br>visibility-visible|
|[width](https://developer.mozilla.org/en-US/docs/Web/CSS/width)|width-25<br>width-33<br>width-50<br>width-66<br>width-75<br>width-100<br>width-100px<br>width-200px<br>width-300px<br>width-100vh|