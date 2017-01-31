# Vue Scroller ![version](https://img.shields.io/badge/version-%20v2.1.0%20beta%20-green.svg) ![vue](https://img.shields.io/badge/vue-%20v2.1%20-green.svg) 
> For vue 1.0, please refer to branch v1.

[Vue Scroller](https://github.com/wangdahoo/vue-scroller) is a foundational component of [Vonic](https://github.com/wangdahoo/vonic) UI.
In purpose of smooth scrolling, pull to refresh and infinite loading.

## [Demo](https://wangdahoo.github.io/vue-scroller/)

## How To Use

```html
<div id="app">
  <scroller 
    :on-refresh="refresh"
    :on-infinite="infinite"
    ref="my_scroller">
    <!-- content goes here -->
  </scroller>
</div>
```

## API

#### Methods of scroller instance:

- resize() :Void
- triggerPullToRefresh() :Void
- finishPullToRefresh() :Void
- finishInfinite(isNoMoreData :Boolean) :Void
- scrollTo(x:Integer, y:Integer, animate:Boolean) :Void
- scrollBy(x:Integer, y:Integer, animate:Boolean) :Void
- getPosition :Object
