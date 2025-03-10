Change log
==========================

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*

- [5.0.0-dev (TBD)](#500-dev-tbd)
- [5.0.0 (2022-01-10)](#500-2022-01-10)
- [4.4.1 (2021-12-24)](#441-2021-12-24)
- [4.4.0 (2021-12-21)](#440-2021-12-21)
- [4.3.1 (2021-10-18)](#431-2021-10-18)
- [4.3.0 (2021-10-15)](#430-2021-10-15)
- [4.2.7 (2021-9-12)](#427-2021-9-12)
- [4.2.6 (2021-7-11)](#426-2021-7-11)
- [4.2.5 (2021-5-31)](#425-2021-5-31)
- [4.2.4 (2021-5-29)](#424-2021-5-29)
- [4.2.3 (2021-5-8)](#423-2021-5-8)
- [4.2.2 (2021-4-23)](#422-2021-4-23)
- [4.2.1 (2021-4-18)](#421-2021-4-18)
- [4.2.0 (2021-4-11)](#420-2021-4-11)
- [4.1.0 (2021-4-7)](#410-2021-4-7)
- [4.0.3 (2021-3-28)](#403-2021-3-28)
- [4.0.2 (2021-3-27)](#402-2021-3-27)
- [4.0.1 (2021-3-20)](#401-2021-3-20)
- [4.0.0 (2021-3-19)](#400-2021-3-19)
- [3.3.0 (2021-2-2)](#330-2021-2-2)
- [3.2.0 (2021-1-25)](#320-2021-1-25)
- [3.1.5 (2021-1-23)](#315-2021-1-23)
- [3.1.4 (2021-1-11)](#314-2021-1-11)
- [3.1.3 (2021-1-2)](#313-2021-1-2)
- [3.1.2 (2020-12-7)](#312-2020-12-7)
- [3.1.0 (2020-12-4)](#310-2020-12-4)
- [3.0.0 (2020-11-29)](#300-2020-11-29)
- [2.2.0 (2020-11-7)](#220-2020-11-7)
- [2.1.0 (2020-10-28)](#210-2020-10-28)
- [2.0.2 (2020-10-05)](#202-2020-10-05)
- [2.0.1 (2020-09-26)](#201-2020-09-26)
- [2.0.0 (2020-09-07)](#200-2020-09-07)
- [1.2.1 (2020-09-04)](#121-2020-09-04)
- [1.2.0 (2020-08-01)](#120-2020-08-01)
- [1.1.2 (2020-05-17)](#112-2020-05-17)
- [1.1.1 (2020-03-17)](#111-2020-03-17)
- [1.1.0 (2020-02-29)](#110-2020-02-29)
- [v1.0.0 (2020-02-23)](#v100-2020-02-23)
- [v0.6.4 (2020-02-17)](#v064-2020-02-17)
- [v0.6.3 (2020-02-05)](#v063-2020-02-05)
- [v0.6.2 (2020-02-03)](#v062-2020-02-03)
- [v0.6.1 (2020-02-02)](#v061-2020-02-02)
- [v0.6.0 (2019-12-24)](#v060-2019-12-24)
- [v0.5.5 (2019-11-27)](#v055-2019-11-27)
- [v0.5.4 (2019-11-26)](#v054-2019-11-26)
- [v0.5.3 (2019-11-20)](#v053-2019-11-20)
- [v0.5.2 (2019-11-13)](#v052-2019-11-13)
- [v0.5.1 (2019-11-07)](#v051-2019-11-07)
- [v0.5.0 (2019-11-06)](#v050-2019-11-06)
- [v0.4.0 (2018-05-11)](#v040-2018-05-11)
- [v0.3.0 (2017-04-21)](#v030-2017-04-21)
- [v0.2.6 (2016-08-17)](#v026-2016-08-17)
- [v0.2.5 (2016-03-02)](#v025-2016-03-02)
- [v0.2.4 (2016-02-15)](#v024-2016-02-15)
- [v0.2.3 (2015-06-23)](#v023-2015-06-23)
- [v0.2.2 (2014-12-23)](#v022-2014-12-23)
- [v0.2.1 (2014-12-09)](#v021-2014-12-09)
- [v0.2.0 (2014-11-30)](#v020-2014-11-30)
- [v0.1.0 (2014-11-18)](#v010-2014-11-18)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## 5.0.0-dev (TBD)
* add `GridStack.registerEngine()` to let user use their own custom layout engine subclass. Thank you [Thomas] for sponsoring it.
* grid option `minWidth` is now `oneColumnSize` to make it clearer, but old field will still work (JS only) for a while

## 5.0.0 (2022-01-10)
* add [#992](https://github.com/gridstack/gridstack.js/issues/992) support dragging into and out of nested grids from parents! Thank you [@arclogos132](https://github.com/arclogos132) for sponsoring it.
* add [#1910](https://github.com/gridstack/gridstack.js/pull/1910) new `column:'auto'` option to size nested grids to their parent grid item column count, keeping items the same size inside and outside. Thank you [@arclogos132](https://github.com/arclogos132) for also sponsoring it.
* fix [#1902](https://github.com/gridstack/gridstack.js/pull/1902) nested.html: dragging between sub-grids show items clipped
* fix [#1558](https://github.com/gridstack/gridstack.js/issues/1558) dragging between vertical grids causes too much growth, not follow mouse.
* fix [#1912](https://github.com/gridstack/gridstack.js/pull/1912) no longer force rows for min-height
* fix [#1888](https://github.com/gridstack/gridstack.js/issues/1888) locks up with nested grid when 'column' is set to 1

## 4.4.1 (2021-12-24)
* fix [#1901](https://github.com/gridstack/gridstack.js/pull/1901) error introduced for #1785 when re-loading with fewer objects

## 4.4.0 (2021-12-21)
* add [#1887](https://github.com/gridstack/gridstack.js/pull/1887) support for IE (new es5 folder) by [@SmileLifeIven](https://github.com/SmileLifeIven)
* fix [#1785](https://github.com/gridstack/gridstack.js/issue/1785) overlapping items when switching column() and making edits. Thank you [@radovanobal](https://github.com/radovanobal) for sponsoring it.
* fix [#1890](https://github.com/gridstack/gridstack.js/issue/1890) unhandled exception when dragging fast between grids.

## 4.3.1 (2021-10-18)
* fix [#1868](https://github.com/gridstack/gridstack.js/issues/1868) prevent swap during resize
* fix [#1849](https://github.com/gridstack/gridstack.js/issues/1849) [#1816](https://github.com/gridstack/gridstack.js/issues/1816) save highest resolution in 1 column mode
* fix [#1855](https://github.com/gridstack/gridstack.js/issues/1855) resize when padding is large vs cellHeight

## 4.3.0 (2021-10-15)
* you can now swap items of different width if they are the same row/height. Thanks to [spektrummedia](http://spektrummedia.com) for sponsoring it.
* fix [#1860](https://github.com/gridstack/gridstack.js/issues/1860) nested grid save inf loop fix
* use latest `dart-sass`, updated comments

## 4.2.7 (2021-9-12)

* fix [#1817](https://github.com/gridstack/gridstack.js/issues/1817) Enable passing of DragEvent to gridstack dropped event. Thanks [@onepartsam](https://github.com/onepartsam)
* fix [#1835](https://github.com/gridstack/gridstack.js/issues/1835) Layout incorrectly restored when node has a minimum width. Thanks [@hssm](https://github.com/hssm)
* fix [#1794](https://github.com/gridstack/gridstack.js/issues/1794) addGrid() does not recognize rem cellHeightUnit

## 4.2.6 (2021-7-11)

* fix [#1784](https://github.com/gridstack/gridstack.js/issues/1784) `removable:true` working by itself (without needing `acceptWidgets:true`)
* fix [#1791](https://github.com/gridstack/gridstack.js/pull/1791) removed drag flicker and scroll issue. Thanks [@nelsieborja](https://github.com/nelsieborja)
* fix [#1795](https://github.com/gridstack/gridstack.js/issues/1795) `save(false)` will no longer have `.content` field (removed existing one if present)
* fix [#1782](https://github.com/gridstack/gridstack.js/issues/1782) `save(false, false)` now correctly saves nested grids
* fix [#1793](https://github.com/gridstack/gridstack.js/issues/1793) `save(false, true)` followed by enable() throws error. we now have new `Utils.cloneDeep()`

## 4.2.5 (2021-5-31)

* fix for website with JQ `droppable('destroy')` giving error

## 4.2.4 (2021-5-29)

* fix [#1760](https://github.com/gridstack/gridstack.js/issues/1760) `removable:true` working again (broke in 4.x)
* fix [#1761](https://github.com/gridstack/gridstack.js/issues/1761) `staticGrid(false)` will now enable drag in behavior (if set)
* fix [#1767](https://github.com/gridstack/gridstack.js/issues/1767) `locked` item can be user moved/resized again, just not pushed by other nodes (broke in 1.1.1)
* fix [#1764](https://github.com/gridstack/gridstack.js/issues/1764) `destroy(false)` can now re-init properly (doesn't force static grid)

## 4.2.3 (2021-5-8)

- `Utils.getScrollParent()` -> `getScrollElement()` rename
- fix [#1745](https://github.com/gridstack/gridstack.js/issues/1745) digression on scrolling in v4.2.1. Thanks [@Manfred-on-github](https://github.com/Manfred-on-github) for fixing your prev change.

## 4.2.2 (2021-4-23)

- fix [#1684](https://github.com/gridstack/gridstack.js/issues/1684) [#1550](https://github.com/gridstack/gridstack.js/issues/1550) mac Safari H5 draggable broken in 4.0.1. Thanks [@wurambo](https://github.com/wurambo)
- fix [#1562](https://github.com/gridstack/gridstack.js/issues/1562) mac Safari page scroll fix

## 4.2.1 (2021-4-18)

- fix [#1700](https://github.com/gridstack/gridstack.js/issues/1700) JQ nested grid drag fix broken in 4.0.3 (but much older underlying issue)
- fix [#1678](https://github.com/gridstack/gridstack.js/issues/1678) item gs-x:0 not animating fix
- fix [#1727](https://github.com/gridstack/gridstack.js/pull/1727) resize-scroll issue when grid is not at top of page. Thanks [@Manfred-on-github](https://github.com/Manfred-on-github)
- fix [#1728](https://github.com/gridstack/gridstack.js/issues/1728) fix sizing from top/left sides

## 4.2.0 (2021-4-11)

- fix [#1704](https://github.com/gridstack/gridstack.js/issues/1704) scrollbar fix broken in 4.x
- fix [#1655](https://github.com/gridstack/gridstack.js/issues/1655) `addWidget()` while in 1 column now remembers original wanted width
- add [#1727](https://github.com/gridstack/gridstack.js/issues/1727) `addWidget()` now supports nested grids like init/addGrid() does.

## 4.1.0 (2021-4-7)

- fix [#219](https://github.com/gridstack/gridstack.js/issues/219) **fixing another 6 years old request** we now automatically insert extra rows
when dragging an item at the bottom below others to make it easier to insert below.
- fix [#1687](https://github.com/gridstack/gridstack.js/issues/1687) more fix for drag between 2 grids with `row / maxRow` broken in 4.x
- fix export symbols .d.ts for `gridstack-h5.js | gridstack-jq.js | gridstack-static.js`
- fix [#1709](https://github.com/gridstack/gridstack.js/issues/1709) correct info for using JQ version and ES6 (tested in Angular app)

## 4.0.3 (2021-3-28)

- fix [#1693](https://github.com/gridstack/gridstack.js/issues/1693) `load` after `init()` broken in 4.x
- fix [#1687](https://github.com/gridstack/gridstack.js/issues/1687) drag between 2 grids with `row / maxRow` broken in 4.x
- fix [#1676](https://github.com/gridstack/gridstack.js/issues/1676) drag edge case in/out single grid without acceptWidgets fix broken in 4.x

## 4.0.2 (2021-3-27)

- fix [#1679](https://github.com/gridstack/gridstack.js/issues/1679) `Resizable: {handles:'w/sw'}` broken in 4.x
- fix [#1658](https://github.com/gridstack/gridstack.js/issues/1658) `enableMove(T/F)` not working correctly
- fix `helper: myFunction` now working for H5 case for `dragInOptions` & `setupDragIn()` broken in 3.x
- fix prevent `addGrid()` from creating nested div grid if container already is a '.grid-stack' div

## 4.0.1 (2021-3-20)

- fix [#1669](https://github.com/gridstack/gridstack.js/issues/1669) JQ resize broken in 4.x
- fix [#1661](https://github.com/gridstack/gridstack.js/issues/1661) serialization of nested grid

## 4.0.0 (2021-3-19)

- fix [#149](https://github.com/gridstack/gridstack.js/issues/149) [#1094](https://github.com/gridstack/gridstack.js/issues/1094) [#1605](https://github.com/gridstack/gridstack.js/issues/1605) [#1534](https://github.com/gridstack/gridstack.js/issues/1534) re-write of the **collision code - fixing 6 years old most requested request**
1. you can now swap items of the same size (vertical/horizontal) when grid is full, and is the default in `float:false` (top gravity) as it feels more natural. Could add Alt key for swap vs push behavior later.
2. Dragging up and down now behave the same (used to require push WAY down past to swap/append). Also much more efficient collision code.
3. handle mid point of dragged over items (>50%) rather than just a new row/column and check for the most covered item when multiple collide.

- fix [#393](https://github.com/gridstack/gridstack.js/issues/393) [#1612](https://github.com/gridstack/gridstack.js/issues/1612) [#1578](https://github.com/gridstack/gridstack.js/issues/1578) re-write of the **drag in/out code - fixing 5 years old bug**
1. we now remove item when cursor leaves (`acceptWidgets` case using `dropout` event) or shape is outside (re-using same method) and re-insert on cursor enter (since we only get `dropover` event). Should **not be possible to have 2 placeholders** which confuses the grids.
2. major re-write and cleanup of the drag in/out. Vars have been renamed and fully documented as I couldn't understand the legacy buggy code.
3. removed any over trash delay feedback as I don't see the point and could introduce race conditions.

- fix [1617](https://github.com/gridstack/gridstack.js/issues/1617) FireFox DOM order issue. Thanks [@marcel-necker](https://github.com/marcel-necker)
- fix changing column # `column(n)` now resizes `cellHeight:'auto'` to keep square
- add [1616](https://github.com/gridstack/gridstack.js/pull/1616) `drag | resize` events while dragging. Thanks [@MrCorba](https://github.com/MrCorba)
- add [1637](https://github.com/gridstack/gridstack.js/issues/1637) `GridStack.setupDragIn()` so user can update external draggable after the grid has been created

## 3.3.0 (2021-2-2)

- big re-write on how `cellHeight()` works. you can now call it at any time (not just grid init options) including switching to 'auto' or other modes on the fly.
- fix `cellHeight:auto` now keeps cell square as window resizes (regressing from 2.x TS conversion). `Utils.throttle()` works better too (guaranteed to be called last event)
- new `cellHeight:initial` which makes the cell squares initially, but doesn't change as windows resizes (better performance)
- new grid option `cellHeightThrottle` (100ms) to control throttle of auto sizing triggers
- fix [1600](https://github.com/gridstack/gridstack.js/issues/1600) height too small with `cellHeight:auto` loading in 1 column. Now detect we load at 1 column and size accordingly (default 'auto' could make big 700x700 cells, so explicit px might still be wanted)
- fix [1538](https://github.com/gridstack/gridstack.js/issues/1538) loading nested into small size and sizing back up
- fix [1604](https://github.com/gridstack/gridstack.js/issues/1604) nested grid resizing fix
- fix [1599](https://github.com/gridstack/gridstack.js/issues/1599) resize from left side can move item right

## 3.2.0 (2021-1-25)

- fix [1413](https://github.com/gridstack/gridstack.js/issues/1413) website & lib works on mobile. We now compile the latest v1.0.8 `jquery.ui.touch-punch`
into the JQ version (only 2k) so mobile devices (android, iphone, ipad, ms surface, etc...) are supported out of the box.
HTML5 version will require re-write to plain `mousemove` & mobile `touchmove` instead of drag events in a future release.
- small optimizations (create placeholder content on the fly, moved more DD code into draggable class)

## 3.1.5 (2021-1-23)

- fix [1572](https://github.com/gridstack/gridstack.js/issues/1572) `column: N` option now sets CSS class
- fix [1571](https://github.com/gridstack/gridstack.js/issues/1571) don't allow drop when grid is full
- fix [1570](https://github.com/gridstack/gridstack.js/issues/1570) easier to drag out/in from below
- fix [1579](https://github.com/gridstack/gridstack.js/issues/1579) `cellHeight()` not updating CSS correctly
- fix [1581](https://github.com/gridstack/gridstack.js/issues/1581) H5 draggable by actual div handle rather than entire item (let content respond to drag as well)

## 3.1.4 (2021-1-11)

- fix [1557](https://github.com/gridstack/gridstack.js/issues/1557) fix no-drop cursor on windows when dragging within a default grid (no external drag in)
- fix [1541](https://github.com/gridstack/gridstack.js/issues/1541) fix Safari H5 delay when dropping items

## 3.1.3 (2021-1-2)

- fix [1540](https://github.com/gridstack/gridstack.js/issues/1540) Safari H5 drag&drop fixed
- fix [1535](https://github.com/gridstack/gridstack.js/issues/1535) use batchUpdate() around grid init to make sure gs-y attributes are respected.
- fix [1545](https://github.com/gridstack/gridstack.js/issues/1545) `disableMove()` correctly prevents drag later (remove events and draggable attribute)
- fix [1546](https://github.com/gridstack/gridstack.js/issues/1546) resize no longer delayed, which caused race conditions errors
- fix [1001](https://github.com/gridstack/gridstack.js/issues/1001) resizing near bottom/top needs to auto-scroll/. thanks [@hbcarlos](https://github.com/hbcarlos)!

## 3.1.2 (2020-12-7)

- fix [1419](https://github.com/gridstack/gridstack.js/issues/1419) dragging into a fixed row grid works better (check if it will fit, else try to append, else won't insert)
-- **possible BREAK** (unlikely you use engine directly)
* engine constructor takes Options struct rather than spelling arguments (easier to extend/use)
* `canBePlacedWithRespectToHeight()` -> `willItFit()` like grid method

- fix [1330](https://github.com/gridstack/gridstack.js/issues/1330) `maxW` does not work as intended with resizable handle `"w"`
- fix [1472](https://github.com/gridstack/gridstack.js/issues/1472) support all options for new dragged in widgets (read all `gs-xyz` attributes)
- fix [1511](https://github.com/gridstack/gridstack.js/issues/1511) dragging any grid item content works
- fix [1438](https://github.com/gridstack/gridstack.js/issues/1438) web-component fixes & grid with 0 size initially.

## 3.1.0 (2020-12-4)

- add new `addGrid(parent, opts)` to create a grid and load children instead of `init() + load()`, which is used by `load()` to supports nested grids creation.
see [nested.html](https://github.com/gridstack/gridstack.js/tree/master/demo/nested.html) demo.
- `save()` will now work on nested grids, recursively saving info. added flag to also allow saving the current grid options + children
(needed for nested grids) so you can now call new `adddGrid()` to re-create everything from JSON.
- fix [1505](https://github.com/gridstack/gridstack.js/issues/1505) don't call `movable()`/`resizable()` on locked items error. thanks [@infime](https://github.com/infime)
- fix [1517](https://github.com/gridstack/gridstack.js/pull/1517) force typescript 3.6 as 3.7 has breaking change

## 3.0.0 (2020-11-29)

- the big news is we finally have a native HTML5 drag&drop plugin (zero jquery)! Huge thanks to [@rhlin](https://github.com/rhlin) for creating this in stealth mode. Read all about it in main doc.
- we now have a React example, in addition to Vue - Angular is next!. thanks [@eloparco](https://github.com/eloparco)
- fix placeholder not having custom `GridStackOptions.itemClass`. thanks [@pablosichert](https://github.com/pablosichert)
- fix [1484](https://github.com/gridstack/gridstack.js/issues/1484) dragging between 2 grids and back (regression in 2.0.1) 
- fix [1471](https://github.com/gridstack/gridstack.js/issues/1471) `load()` into 1 column mode doesn't resize back to 12 correctly
- fix [1235](https://github.com/gridstack/gridstack.js/issues/1235) `update(el, opts)` re-write to take all `GridStackWidget` options (not just x,y,width,height) and do everything efficiently.
Hiding `locked()`, `move()`, `resize()`, `minWidth()`, etc... as they just simply call update() which does all the constrain now as well!
- del `ddPlugin` grid option as we only have one drag&drop plugin at runtime, which is defined by the include you use (HTML5 vs jquery vs none)
- change attribute `data-gs-min-width` is now `gs-min-w`. We removed 'data-' from all attributes, and shorten 'width|height' to just 'w|h' to require less typing and more efficient (2k saved in .js alone!) [1491](https://github.com/gridstack/gridstack.js/pull/1491) [1492](https://github.com/gridstack/gridstack.js/pull/1492)
- also `GridStackWidget` used in most API `width|height|minWidth|minHeight|maxWidth|maxHeight` are now shorter `w|h|minW|minH|maxW|maxH` as well [1493](https://github.com/gridstack/gridstack.js/pull/1493)
- **** see [migrating to v3](https://github.com/gridstack/gridstack.js#migrating-to-v3) ****

## 2.2.0 (2020-11-7)

- add `margin` option now support multi values CSS format `'5px 10px 0 20px'` or `'5em 10em'`
- add `data-gs-static-grid` attribute
- fix [1435](https://github.com/gridstack/gridstack.js/issues/1435) `class="ui-draggable-disabled ui-resizable-disabled"` have been added back to static grid items, so existing CSS rule to style continue working 
- fix [1439](https://github.com/gridstack/gridstack.js/pull/1439) getting DOM element by id with number works (api that uses `GridStackElement` handle more string formats)
- fix [1442](https://github.com/gridstack/gridstack.js/pull/1442) setting `marginTop` (or any 4 sides) to cause resize to break. Thanks [@deadivan](https://github.com/deadivan) for suggested fix.

## 2.1.0 (2020-10-28)

- fix grid `static: true` to no longer add any drag&drop (even disabled) which should speed things up, and `setStatic(T/F)` will now correctly add it back/delete for items that need it only. 
Also fixed JQ draggable warning if not initialized first [858](https://github.com/gridstack/gridstack.js/issues/858)
- add `addWidget(opt)` now handles just passing a `GridStackWidget` which creates the default divs, simplifying your code. Old API still supported.
- add `save(saveContent = true)` now lets you optionally save the HTML content in the node property, with load() restoring it [1418](https://github.com/gridstack/gridstack.js/issues/1418)
- add `GridStackWidget.content` now lets you add any HTML content when calling `load()/save()` or `addWidget()` [1418](https://github.com/gridstack/gridstack.js/issues/1418)
- add `ColumnOptions` to `column(n, options)` for multiple re-layout options, including 'none' that will preserve the x and width, until out of bound/overlap [1338](https://github.com/gridstack/gridstack.js/issues/1338)
including a custom function for you to create the new layout [1332](https://github.com/gridstack/gridstack.js/issues/1332)

## 2.0.2 (2020-10-05)

- fix `animate` to not re-create CSS style each time (should be faster too) and made it default now since so much nicer. pass `{animate: false}` grid options if you want instant again [937](https://github.com/gridstack/gridstack.js/issues/937)
- fix `resizable: { handles: ...}` forcing `alwaysShowResizeHandle` behavior [1373](https://github.com/gridstack/gridstack.js/issues/1373)

## 2.0.1 (2020-09-26)

- fix `minWidth()`, `minHeight()`, `maxHeight()` to set node value as well [1359](https://github.com/gridstack/gridstack.js/issues/1359)
- fix `GridStackOptions` spelling [1359](https://github.com/gridstack/gridstack.js/issues/1359)
- fix remove window resize event when `grid.destroy()` [1369](https://github.com/gridstack/gridstack.js/issues/1369)
- fix nested grid resize [1361](https://github.com/gridstack/gridstack.js/issues/1361)
- fix resize with `cellHeight` '6rem' '6em' not working [1356](https://github.com/gridstack/gridstack.js/issues/1356)
- fix preserve attributes (min/max/id/etc...) when dragging between grids [1367](https://github.com/gridstack/gridstack.js/issues/1367)
- fix 2 drop shadows when dragging between grids [393](https://github.com/gridstack/gridstack.js/issues/393)

## 2.0.0 (2020-09-07)

- re-write to native Typescript, removing all JQuery from main code and API (drag&drop plugin still using jqueryui for now)
- add `getGridItems()` to return list of HTML grid items
- add `{dragIn | dragInOptions}` grid attributes to handle external drag&drop items
- add `save()` and `load()` to serialize grids from JSON, saving all attributes (not just w,h,x,y) [1286](https://github.com/gridstack/gridstack.js/issues/1286)
- add `margin` to replace `verticalMargin` which affects both dimensions in code, rather than one in code the other in CSS.
You can now have perfect square cells (default) [723](https://github.com/gridstack/gridstack.js/issues/723)
- fix [1299](https://github.com/gridstack/gridstack.js/pull/1299) many columns round-off error
- fix [1102](https://github.com/gridstack/gridstack.js/issues/1102) loose functionality when they are moved to a new grid
- add optional params to `removeWidget()` to have quiet mode (no callbacks)
- drop support for IE11 due to more compact ES6 output and newer TS code

## 1.2.1 (2020-09-04)

- fix [1341](https://github.com/gridstack/gridstack.js/pull/1341) Enable the UMD behavior for bundlers compatibility

## 1.2.0 (2020-08-01)

- fix [1311](https://github.com/gridstack/gridstack.js/issues/1311) domAttr is not defined
- adds `styleInHead` option to allow for selecting older behavior (adding STYLE element to HEAD element instead of parentNode)
- update jquery to v3.5.1

## 1.1.2 (2020-05-17)

- fix [1229](https://github.com/gridstack/gridstack.js/issues/1229) `staticGrid` no longer disable oneColumnMode
- fix [1195](https://github.com/gridstack/gridstack.js/issues/1195) options broken with ember hash helper - thanks [@btecu](https://github.com/btecu)
- fix [1250](https://github.com/gridstack/gridstack.js/issues/1250) don't remove item from another grid
- fix [1261](https://github.com/gridstack/gridstack.js/issues/1261) `init()` clones passed options so second doesn't affect first one
- fix [1276](https://github.com/gridstack/gridstack.js/issues/1276) `addWidget()` ignores data attributes

## 1.1.1 (2020-03-17)

- fix [1187](https://github.com/gridstack/gridstack.js/issues/1187) IE support for `CustomEvent` polyfill - thanks [@phil-blais](https://github.com/phil-blais)
- fix [1204](https://github.com/gridstack/gridstack.js/issues/1204) destroy drag&drop when removing node(s) instead of just disabling it.
- fix [1181](https://github.com/gridstack/gridstack.js/issues/1181) Locked widgets are still moveable by other widgets.
- fix [1217](https://github.com/gridstack/gridstack.js/issues/1217) If I set cellHeight to some vh, only first grid will take vh, rest will use px
- include SASS source files to npm package again [1193](https://github.com/gridstack/gridstack.js/pull/1193)

## 1.1.0 (2020-02-29)

- add `minRow` and `row` grid options (which set minRow=maxRow=N) [1172](https://github.com/gridstack/gridstack.js/issues/1172) - thanks [@RadoiAndrei](https://github.com/RadoiAndrei)
- fix [1166](https://github.com/gridstack/gridstack.js/issues/1166) resize not taking margin height into account - thanks [@awjae](https://github.com/awjae)
- fix [1155](https://github.com/gridstack/gridstack.js/issues/1155) `maxRow` now limit initial item placement if out of bound, preventing broken drag behavior
- fix [1171](https://github.com/gridstack/gridstack.js/issues/1171) added event support to call `grid.on('added removed change', callback)` again even with native events.

## v1.0.0 (2020-02-23)

- **breaking**: [(1084)](https://github.com/gridstack/gridstack.js/issues/1084) jquery was removed from the API and dependencies (initialize differently, and methods take/return `GridStack` or `HTMLElement` instead of `JQuery`), so your code will need to change. 
See [Migrating to v1.0.0](https://github.com/gridstack/gridstack.js/tree/master/README.md#migrating-to-v100)
- `setColumn(N)` is now `column(N)` (matches other set/get methods) and `getColumn()` to get current column number
- add `grid.on(eventName, callback)` / `grid.off(eventName)` to hide native JQ events mix
- add `grid.getRow()` to get the current grid row number

## v0.6.4 (2020-02-17)

- fix [#540](https://github.com/gridstack/gridstack.js/issues/540) WebComponent support: CSS file now insert before grid instead of 'head'
- fix [#1143](https://github.com/gridstack/gridstack.js/issues/1143) nested grids with different `acceptWidgets` class
- fix [#1142](https://github.com/gridstack/gridstack.js/issues/1142) add/remove widget will also trigger change events when it should.
- optimized `change` callback to save original x,y,w,h values and only call those that changed [1148](https://github.com/gridstack/gridstack.js/pull/1148)
- delete `bower` since [dead](https://snyk.io/blog/bower-is-dead) for a while now

## v0.6.3 (2020-02-05)

- fix [#1132](https://github.com/gridstack/gridstack.js/issues/1132) oneColumnMode missing CSS to do layout
- del `oneColumnModeClass` / `.grid-stack-one-column-mode` and associated code. If you depended on this, use class `.grid-stack-1` instead since it is 1 column layout anyway [1134](https://github.com/gridstack/gridstack.js/pull/1134)

## v0.6.2 (2020-02-03)

- add `oneColumnModeDomSort` true|false to let you specify a custom layout (use dom order instead of x,y) for oneColumnMode `column(1)` [#713](https://github.com/gridstack/gridstack.js/issues/713)
- fix oneColumnMode to only restore if we auto went to it as window sizes up [#1125](https://github.com/gridstack/gridstack.js/pull/1125)
- editing in 1 column (or few columns) does a better job updating higher layout (track before and after and move items accordingly). 
Tracking item swap would be even better still. [#1127](https://github.com/gridstack/gridstack.js/pull/1127)

## v0.6.1 (2020-02-02)

- fix [#37](https://github.com/gridstack/gridstack.js/issues/37) oneColumnMode (<768px by default) now simply calls `column(1)` and remembers prev columns (so we can restore). This gives
us full resize/re-order of items capabilities rather than a locked CSS only layout (see prev rev changes). [#1120](https://github.com/gridstack/gridstack.js/pull/1120)
- fix [responsive.html](https://gridstackjs.com/demo/responsive.html) demo [#1121](https://github.com/gridstack/gridstack.js/pull/1121)

## v0.6.0 (2019-12-24)

- add `float(val)` to set/get the grid float mode, which will relayout [#1088](https://github.com/gridstack/gridstack.js/pull/1088)
- add `compact()` to reclaim any empty space and relayout grid items [#1101](https://github.com/gridstack/gridstack.js/pull/1101)
- add `options.dragOut` to let user drag nested grid items out of a parent or not (default false)
and jQuery UI `draggable.containment` can now be specified in options. You can now drag&drop between 2 nested grids [#1105](https://github.com/gridstack/gridstack.js/pull/1105)
- add `%` as a valid unit for height [#1093](https://github.com/gridstack/gridstack.js/pull/1093). thank you 
[@trevisanweb](https://github.com/trevisanweb) [@aureality](https://github.com/aureality)
[@ZoolWay](https://github.com/ZoolWay)
- fix callbacks to get either `added, removed, change` or combination if adding a node require also to change its (x,y) for example.
Also you can now call `batchUpdate()` before calling a bunch of `addWidget()` and get a single event callback (more efficient).
[#1096](https://github.com/gridstack/gridstack.js/pull/1096)
- `removeAll()` is now much faster (no relayout) and calls `removed` event just once with a list [#1097](https://github.com/gridstack/gridstack.js/pull/1097)
- `column()` complete re-write and is no longer "Experimental". We now do a reasonable job at sizing/position the widgets (especially 1 column) and
also now cache each column layout so you can go back to say 12 column and not loose original layout. [#1098](https://github.com/gridstack/gridstack.js/pull/1098)
- fix `addWidget(el)` (no data) would not render item at correct location, and overlap item at (0,0) [#1098](https://github.com/gridstack/gridstack.js/pull/1098)
- you can now pre-define size of dragable elements from a sidebar using standard `data-gs-width` and `data-gs-height` - fix 
[#413](https://github.com/gridstack/gridstack.js/issues/413), [#914](https://github.com/gridstack/gridstack.js/issues/914), [#918](https://github.com/gridstack/gridstack.js/issues/918), 
[#922](https://github.com/gridstack/gridstack.js/issues/922), [#933](https://github.com/gridstack/gridstack.js/issues/933) 
thanks [@ermcgrat](https://github.com/ermcgrat) and others for pointing out code issue.

## v0.5.5 (2019-11-27)

- min files include rev number/license [#1075](https://github.com/gridstack/gridstack.js/pull/1075)
- npm package fix to exclude more temporary content [#1078](https://github.com/gridstack/gridstack.js/pull/1078)
- removed `jquery-ui/*` requirements from AMD packing in `gridstack.jQueryUI.js` as it was causing App compile missing errors now that we include a subset of jquery-ui

## v0.5.4 (2019-11-26)

- fix for griditems with x=0 placement wrong order (introduced by [#1017](https://github.com/gridstack/gridstack.js/issues/10510174)) ([#1054](https://github.com/gridstack/gridstack.js/issues/1054)).
- fix `cellHeight(val)` not working due to style change (introduced by [#937](https://github.com/gridstack/gridstack.js/issues/937)) ([#1068](https://github.com/gridstack/gridstack.js/issues/1068)).
- add `gridstack-poly.js` for IE and older browsers, removed `core-js` lib from samples (<1k vs 85k), and all IE8 mentions ([#1061](https://github.com/gridstack/gridstack.js/pull/1061)).
- add `jquery-ui.js` (and min.js) as minimal subset we need (55k vs 248k), which is now part of `gridstack-h5.js`. Include individual parts if you need your own lib instead of all.js
([#1064](https://github.com/gridstack/gridstack.js/pull/1064)).
- changed jquery dependency to lowest we can use (>=1.8) ([#629](https://github.com/gridstack/gridstack.js/issues/629)).
- add advance demo from web site ([#1073](https://github.com/gridstack/gridstack.js/pull/1073)).

## v0.5.3 (2019-11-20)

- grid options `width` is now `column`, `height` now `maxRow`, and `setGridWidth()` now `column()` to match what they are. Old names are still supported (console warnings). Various fixes for custom # of column and re-wrote entire doc section ([#1053](https://github.com/gridstack/gridstack.js/issues/1053)).
- fix widgets not animating when `animate: true` is used. on every move, styles were recreated-fix should slightly improve gridstack.js speed ([#937](https://github.com/gridstack/gridstack.js/issues/937)).
- fix moving widgets when having multiple grids. jquery-ui workaround ([#1043](https://github.com/gridstack/gridstack.js/issues/1043)).
- switch to eslint ([#763](https://github.com/gridstack/gridstack.js/issues/763)) thanks [@rwstoneback](https://github.com/rwstoneback).
- fix null values `addWidget()` options ([#1042](https://github.com/gridstack/gridstack.js/issues/1042)).

## v0.5.2 (2019-11-13)

- fix undefined `x,y` position messes up grid ([#1017](https://github.com/gridstack/gridstack.js/issues/1017)).
- changed code to 2 spaces.
- fix minHeight during `onStartMoving()` ([#999](https://github.com/gridstack/gridstack.js/issues/999)).
- add `gridstack.d.ts` TypeScript definition file now included - no need to include `@types/gridstack`, easier to update ([#1036](https://github.com/gridstack/gridstack.js/pull/1036)).
- add `addWidget(el, options)` to pass object so you don't have to spell 10 params. ([#907](https://github.com/gridstack/gridstack.js/issues/907)).

## v0.5.1 (2019-11-07)

- reduced npm package size from 672k to 324k (drop demo, src and extra files)

## v0.5.0 (2019-11-06)

- emit `dropped` event when a widget is dropped from one grid into another ([#823](https://github.com/gridstack/gridstack.js/issues/823)).
- don't throw error if no bounding scroll element is found ([#891](https://github.com/gridstack/gridstack.js/issues/891)).
- don't push locked widgets even if they are at the top of the grid ([#882](https://github.com/gridstack/gridstack.js/issues/882)).
- RequireJS and CommonJS now export on the `exports` module fix ([#643](https://github.com/gridstack/gridstack.js/issues/643)).
- automatically scroll page when widget is moving beyond viewport ([#827](https://github.com/gridstack/gridstack.js/issues/827)).
- removed lodash dependencies ([#693](https://github.com/gridstack/gridstack.js/issues/693)).
- don't overwrite globals jQuery when in a modular environment ([#974](https://github.com/gridstack/gridstack.js/pull/974)).
- removed z-index from `.grid-stack-item-content` causing child modal dialog clipping ([#984](https://github.com/gridstack/gridstack.js/pull/984)).
- convert project to use yarn ([#983](https://github.com/gridstack/gridstack.js/pull/983)).

## v0.4.0 (2018-05-11)

- widgets can have their own resize handles. Use `data-gs-resize-handles` element attribute to use. For example, `data-gs-resize-handles="e,w"` will make the particular widget only resize west and east. ([#494](https://github.com/gridstack/gridstack.js/issues/494)).
- enable sidebar items to be duplicated properly. Pass `helper: 'clone'` in `draggable` options. ([#661](https://github.com/gridstack/gridstack.js/issues/661), [#396](https://github.com/gridstack/gridstack.js/issues/396), [#499](https://github.com/gridstack/gridstack.js/issues/499)).
- fix `staticGrid` grid option ([#743](https://github.com/gridstack/gridstack.js/issues/743))
- preserve inline styles when moving/cloning items (thanks [@silverwind](https://github.com/silverwind))
- fix bug causing heights not to get set ([#744](https://github.com/gridstack/gridstack.js/issues/744))
- allow grid to have min-height, fixes ([#628](https://github.com/gridstack/gridstack.js/issues/628)) thanks [@adumesny](https://github.com/adumesny)
- widget x and y are now ints (thanks [@DonnchaC](https://github.com/donnchac))
- allow all droppable options (thanks [@vigor-vlad](https://github.com/vigor-vlad))
- properly track mouse position in `getCellFromPixel` (thanks [@aletorrado](https://github.com/aletorrado))
- remove instance of `!important` (thanks [@krilllind](https://github.com/krilllind))
- scroll when moving widget up or down out of viewport ([#827](https://github.com/gridstack/gridstack.js/issues/827))

## v0.3.0 (2017-04-21)

- remove placeholder when dragging widget below grid (already worked when dragging left, above, and to the right of grid).
- prevent extra checks for removing widget when dragging off grid.
- trigger `added` when a widget is added via dropping from one grid to another.
- trigger `removed` when a widget is removed via dropping from one grid to another.
- trigger `removed` when a widget is removed via dropping on a removable zone ([#607](https://github.com/gridstack/gridstack.js/issues/607) and [#550](https://github.com/gridstack/gridstack.js/issues/550)).
- trigger custom event for `resizestop` called `gsresizestop` ([#577](https://github.com/gridstack/gridstack.js/issues/577) and [#398](https://github.com/gridstack/gridstack.js/issues/398)).
- prevent dragging/resizing in `oneColumnMode` ([#593](https://github.com/gridstack/gridstack.js/issues/593)).
- add `oneColumnModeClass` option to grid.
- remove 768px CSS styles, moved to grid-stack-one-column-mode class.
- add max-width override on grid-stck-one-column-mode ([#462](https://github.com/gridstack/gridstack.js/issues/462)).
- add internal function`isNodeChangedPosition`, minor optimization to move/drag.
- drag'n'drop plugin system. Move jQuery UI dependencies to separate plugin file.

## v0.2.6 (2016-08-17)

- update requirements to the latest versions of jQuery (v3.1.0+) and jquery-ui (v1.12.0+).
- fix jQuery `size()` ([#486](https://github.com/gridstack/gridstack.js/issues/486)).
- update `destroy([removeDOM])` call ([#422](https://github.com/gridstack/gridstack.js/issues/422)).
- don't mutate options when calling `draggable` and `resizable`. ([#505](https://github.com/gridstack/gridstack.js/issues/505)).
- update _notify to allow detach ([#411](https://github.com/gridstack/gridstack.js/issues/411)).
- fix code that checks for jquery-ui ([#481](https://github.com/gridstack/gridstack.js/issues/481)).
- fix `cellWidth` calculation on empty grid

## v0.2.5 (2016-03-02)

- update names to respect js naming convention.
- `cellHeight` and `margin` can now be string (e.g. '3em', '20px') (Thanks to @jlowcs).
- add `maxWidth`/`maxHeight` methods.
- add `enableMove`/`enableResize` methods.
- fix window resize issue [#331](https://github.com/gridstack/gridstack.js/issues/331)).
- add options `disableDrag` and `disableResize`.
- fix `batchUpdate`/`commit` (Thank to @radiolips)
- remove dependency of FontAwesome
- RTL support
- `'auto'` value for `cellHeight` option
- fix `setStatic` method
- add `setAnimation` method to API
- add `column` method ([#227](https://github.com/gridstack/gridstack.js/issues/227))
- add `removable`/`removeTimeout` *(experimental)*
- add `removeDOM` parameter to `destroy` method ([#216](https://github.com/gridstack/gridstack.js/issues/216)) (thanks @jhpedemonte)
- add `useOffset` parameter to `getCellFromPixel` method ([#237](https://github.com/gridstack/gridstack.js/issues/237))
- add `minWidth`, `maxWidth`, `minHeight`, `maxHeight`, `id` parameters to `addWidget` ([#188](https://github.com/gridstack/gridstack.js/issues/188))
- add `added` and `removed` events for when a widget is added or removed, respectively. ([#54](https://github.com/gridstack/gridstack.js/issues/54))
- add `acceptWidgets` parameter. Widgets can now be draggable between grids or from outside *(experimental)*

## v0.2.4 (2016-02-15)

- fix closure compiler/linter warnings
- add `staticGrid` option.
- add `minWidth`/`minHeight` methods (Thanks to @cvillemure)
- add `destroy` method (Thanks to @zspitzer)
- add `placeholderText` option (Thanks to @slauyama)
- add `handleClass` option.
- add `makeWidget` method.
- lodash v 4.x support (Thanks to @andrewr88)

## v0.2.3 (2015-06-23)

- gridstack-extra.css
- add support of lodash.js
- add `isAreaEmpty` method
- nested grids
- add `batchUpdate`/`commit` methods
- add `update` method
- allow to override `resizable`/`draggable` options
- add `disable`/`enable` methods
- add `getCellFromPixel` (thanks to @juchi)
- AMD support
- fix nodes sorting
- improved touch devices support
- add `alwaysShowResizeHandle` option
- minor fixes and improvements

## v0.2.2 (2014-12-23)

- fix grid initialization
- add `cellHeight`/`cellWidth` API methods
- fix boolean attributes ([#31](https://github.com/gridstack/gridstack.js/issues/31))

## v0.2.1 (2014-12-09)

- add widgets locking ([#19](https://github.com/gridstack/gridstack.js/issues/19))
- add `willItFit` API method
- fix auto-positioning ([#20](https://github.com/gridstack/gridstack.js/issues/20))
- add animation (thanks to @ishields)
- fix `y` coordinate calculation when dragging ([#18](https://github.com/gridstack/gridstack.js/issues/18))
- fix `removeWidget` ([#16](https://github.com/gridstack/gridstack.js/issues/16))
- minor fixes


## v0.2.0 (2014-11-30)

- add `height` option
- auto-generate css rules (widgets `height` and `top`)
- add `GridStack.Utils.sort` utility function
- add `removeAll` API method
- add `resize` and `move` API methods
- add `resizable` and `movable` API methods
- add `data-gs-no-move` attribute
- add `float` option
- fix default css rule for inner content
- minor fixes

## v0.1.0 (2014-11-18)

Very first version.
