# Graph Report - src  (2026-06-16)

## Corpus Check
- 154 files · ~68,806 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 1168 nodes · 3275 edges · 66 communities (36 shown, 30 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS · INFERRED: 2 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `016b28ed`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]
- [[_COMMUNITY_Community 24|Community 24]]
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 26|Community 26]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 28|Community 28]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 31|Community 31]]
- [[_COMMUNITY_Community 32|Community 32]]
- [[_COMMUNITY_Community 33|Community 33]]
- [[_COMMUNITY_Community 34|Community 34]]
- [[_COMMUNITY_Community 35|Community 35]]
- [[_COMMUNITY_Community 36|Community 36]]
- [[_COMMUNITY_Community 37|Community 37]]
- [[_COMMUNITY_Community 38|Community 38]]
- [[_COMMUNITY_Community 39|Community 39]]
- [[_COMMUNITY_Community 40|Community 40]]
- [[_COMMUNITY_Community 41|Community 41]]
- [[_COMMUNITY_Community 42|Community 42]]
- [[_COMMUNITY_Community 43|Community 43]]
- [[_COMMUNITY_Community 44|Community 44]]
- [[_COMMUNITY_Community 45|Community 45]]
- [[_COMMUNITY_Community 46|Community 46]]
- [[_COMMUNITY_Community 47|Community 47]]
- [[_COMMUNITY_Community 48|Community 48]]
- [[_COMMUNITY_Community 49|Community 49]]
- [[_COMMUNITY_Community 50|Community 50]]
- [[_COMMUNITY_Community 51|Community 51]]
- [[_COMMUNITY_Community 52|Community 52]]
- [[_COMMUNITY_Community 53|Community 53]]
- [[_COMMUNITY_Community 54|Community 54]]
- [[_COMMUNITY_Community 55|Community 55]]
- [[_COMMUNITY_Community 59|Community 59]]
- [[_COMMUNITY_Community 60|Community 60]]
- [[_COMMUNITY_Community 61|Community 61]]
- [[_COMMUNITY_Community 62|Community 62]]
- [[_COMMUNITY_Community 64|Community 64]]
- [[_COMMUNITY_Community 65|Community 65]]
- [[_COMMUNITY_Community 67|Community 67]]
- [[_COMMUNITY_Community 68|Community 68]]
- [[_COMMUNITY_Community 72|Community 72]]
- [[_COMMUNITY_Community 73|Community 73]]

## God Nodes (most connected - your core abstractions)
1. `isValid()` - 111 edges
2. `StoreImp` - 106 edges
3. `ChartImp` - 88 edges
4. `MouseTouchEvent` - 46 edges
5. `isString()` - 44 edges
6. `YAxis` - 43 edges
7. `isNumber()` - 41 edges
8. `EventHandlerImp` - 32 edges
9. `Event` - 30 edges
10. `IndicatorTemplate` - 29 edges

## Surprising Connections (you probably didn't know these)
- `EventOverlayInfo` --references--> `OverlayFigure`  [EXTRACTED]
  Store.ts → component/Overlay.ts
- `CreateIndicatorOptions` --references--> `PaneOptions`  [EXTRACTED]
  Chart.ts → pane/types.ts
- `Chart` --references--> `ActionCallback`  [EXTRACTED]
  Chart.ts → common/Action.ts
- `Chart` --references--> `ActionType`  [EXTRACTED]
  Chart.ts → common/Action.ts
- `Chart` --references--> `Indicator`  [EXTRACTED]
  Chart.ts → component/Indicator.ts

## Import Cycles
- 3-file cycle: `component/YAxis.ts -> pane/DrawPane.ts -> widget/YAxisWidget.ts -> component/YAxis.ts`
- 3-file cycle: `pane/XAxisPane.ts -> widget/XAxisWidget.ts -> view/XAxisView.ts -> pane/XAxisPane.ts`
- 3-file cycle: `component/Axis.ts -> pane/DrawPane.ts -> widget/YAxisWidget.ts -> component/Axis.ts`
- 3-file cycle: `Store.ts -> extension/overlay/index.ts -> component/Overlay.ts -> Store.ts`
- 3-file cycle: `Chart.ts -> pane/DrawPane.ts -> pane/Pane.ts -> Chart.ts`
- 3-file cycle: `Chart.ts -> Event.ts -> pane/Pane.ts -> Chart.ts`
- 3-file cycle: `Chart.ts -> pane/SeparatorPane.ts -> pane/Pane.ts -> Chart.ts`
- 4-file cycle: `component/Axis.ts -> pane/DrawPane.ts -> widget/YAxisWidget.ts -> component/YAxis.ts -> component/Axis.ts`
- 4-file cycle: `Chart.ts -> component/YAxis.ts -> pane/DrawPane.ts -> pane/Pane.ts -> Chart.ts`
- 4-file cycle: `component/YAxis.ts -> pane/DrawPane.ts -> widget/YAxisWidget.ts -> view/CandleLastPriceLabelView.ts -> component/YAxis.ts`
- 4-file cycle: `component/YAxis.ts -> pane/DrawPane.ts -> widget/YAxisWidget.ts -> view/OverlayYAxisView.ts -> component/YAxis.ts`
- 4-file cycle: `Store.ts -> extension/overlay/index.ts -> extension/overlay/priceChannelLine.ts -> component/Overlay.ts -> Store.ts`
- 4-file cycle: `Chart.ts -> pane/CandlePane.ts -> pane/DrawPane.ts -> pane/Pane.ts -> Chart.ts`
- 4-file cycle: `Chart.ts -> Event.ts -> widget/Widget.ts -> pane/Pane.ts -> Chart.ts`
- 4-file cycle: `Chart.ts -> Event.ts -> extension/hotkey/index.ts -> common/Hotkey.ts -> Chart.ts`
- 4-file cycle: `Store.ts -> extension/overlay/index.ts -> extension/overlay/straightLine.ts -> component/Overlay.ts -> Store.ts`
- 4-file cycle: `Store.ts -> extension/overlay/index.ts -> extension/overlay/parallelStraightLine.ts -> component/Overlay.ts -> Store.ts`
- 4-file cycle: `Store.ts -> extension/overlay/index.ts -> extension/overlay/verticalSegment.ts -> component/Overlay.ts -> Store.ts`
- 4-file cycle: `Chart.ts -> pane/IndicatorPane.ts -> pane/DrawPane.ts -> pane/Pane.ts -> Chart.ts`
- 4-file cycle: `component/Axis.ts -> pane/DrawPane.ts -> widget/YAxisWidget.ts -> view/OverlayYAxisView.ts -> component/Axis.ts`

## Communities (66 total, 30 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.06
Nodes (49): AxisLineStyle, AxisTickLineStyle, AxisTickTextStyle, CandleAreaPointStyle, CandleAreaStyle, CandleBarColor, CandleLastPriceMarkExtendTextPosition, CandleLastPriceMarkExtendTextStyle (+41 more)

### Community 1 - "Community 1"
Cohesion: 0.08
Nodes (7): EventDispatcher, Eventful, EventName, MouseTouchEvent, FigureImp, Event, SeparatorWidget

### Community 2 - "Community 2"
Cohesion: 0.12
Nodes (10): Delay, EventHandlerImp, EventOptions, ManhattanDistance, MouseEventButton, MouseTouchMoveWithDownInfo, TimerId, isAppleOS() (+2 more)

### Community 3 - "Community 3"
Cohesion: 0.10
Nodes (20): DeepPartial, AxisStyle, Styles, AxisTick, checkCoordinateOnLine(), getLinearYFromSlopeIntercept(), line, LineAttrs (+12 more)

### Community 5 - "Community 5"
Cohesion: 0.17
Nodes (9): enUS, getSupportedLocales(), i18n(), locales, registerLocale(), zhCN, Locales, formatTemplateString() (+1 more)

### Community 6 - "Community 6"
Cohesion: 0.06
Nodes (28): IndicatorConstructor, IndicatorTemplate, Bias, Brar, Cci, commodityChannelIndex, Cr, currentRatio (+20 more)

### Community 7 - "Community 7"
Cohesion: 0.09
Nodes (15): AxisTemplate, YAxisConstructor, YAxisImp, YAxisTemplate, getPrecision(), index10(), log10(), nice() (+7 more)

### Community 8 - "Community 8"
Cohesion: 0.11
Nodes (19): Point, OverlayConstructor, OverlayCreateFiguresCallback, OverlayEventCallback, OverlayInnerConstructor, OverlayPerformEventParams, OverlayTemplate, brush (+11 more)

### Community 10 - "Community 10"
Cohesion: 0.12
Nodes (3): DecimalFold, Formatter, Hotkey

### Community 11 - "Community 11"
Cohesion: 0.05
Nodes (66): ConvertFilter, CreateIndicatorOptions, DomFilter, AnimationDoFrameCallback, AnimationOptions, BarSpace, Bounding, createDefaultBounding() (+58 more)

### Community 12 - "Community 12"
Cohesion: 0.12
Nodes (21): Coordinate, getDistance(), Figure, FigureConstructor, FigureInnerConstructor, FigureTemplate, arc, ArcAttrs (+13 more)

### Community 13 - "Community 13"
Cohesion: 0.18
Nodes (5): MouseTouchEventCallback, checkOverlayFigureEvent(), OverlayFigure, EventOverlayInfoFigureType, OverlayView

### Community 14 - "Community 14"
Cohesion: 0.17
Nodes (9): Crosshair, KLineData, DataLoader, DataLoaderGetBarsParams, DataLoaderSubscribeBarParams, DataLoaderUnsubscribeBarParams, Period, SymbolInfo (+1 more)

### Community 16 - "Community 16"
Cohesion: 0.10
Nodes (20): PickPartial, AxisPosition, ExtendTextType, FormatBigNumber, FormatDateParams, FormatDateType, FormatExtendText, FormatExtendTextParams (+12 more)

### Community 18 - "Community 18"
Cohesion: 0.11
Nodes (5): OverlayImp, simpleTag, formatPrecision(), clone(), isNumber()

### Community 19 - "Community 19"
Cohesion: 0.12
Nodes (18): DomPosition, CandleTooltipRectPosition, FeatureType, PolygonType, TooltipFeaturePosition, TooltipShowRule, TooltipShowType, OverlayDrawingMode (+10 more)

### Community 20 - "Community 20"
Cohesion: 0.10
Nodes (18): Ao, awesomeOscillator, Macd, movingAverageConvergenceDivergence, Sar, stopAndReverse, getVolumeFigure(), Vol (+10 more)

### Community 21 - "Community 21"
Cohesion: 0.14
Nodes (3): LayoutPane, DrawPane, PaneOptions

### Community 22 - "Community 22"
Cohesion: 0.15
Nodes (3): TaskScheduler, isValid(), CandleLastPriceView

### Community 23 - "Community 23"
Cohesion: 0.17
Nodes (14): PolygonStyle, checkCoordinateOnCircle(), circle, drawCircle(), drawLine(), checkCoordinateOnPolygon(), drawPolygon(), polygon (+6 more)

### Community 25 - "Community 25"
Cohesion: 0.13
Nodes (17): NeighborData, IndicatorPolygonStyle, IndicatorStyle, LineType, EachFigureCallback, IndicatorCalcCallback, IndicatorCreateTooltipDataSourceCallback, IndicatorDataState (+9 more)

### Community 26 - "Community 26"
Cohesion: 0.18
Nodes (7): TooltipFeatureStyle, TooltipLegend, TooltipTextStyle, Indicator, IndicatorTooltipData, IndicatorTooltipView, TooltipFeatureInfo

### Community 27 - "Community 27"
Cohesion: 0.24
Nodes (6): CandleColorCompareRule, eachFigures(), IndicatorFigure, IndicatorFigureAttrs, IndicatorFigureStyle, IndicatorLastValueView

### Community 28 - "Community 28"
Cohesion: 0.16
Nodes (5): OverlayStyle, Overlay, OverlayEventCollection, OverlayXAxisView, OverlayYAxisView

### Community 29 - "Community 29"
Cohesion: 0.16
Nodes (6): CrosshairDirectionStyle, CrosshairStyle, StateTextStyle, CrosshairHorizontalLabelView, CrosshairLineView, CrosshairVerticalLabelView

### Community 30 - "Community 30"
Cohesion: 0.17
Nodes (6): RectStyle, FigureCreate, getInnerFigureClass(), RectAttrs, CandleBarView, View

### Community 31 - "Community 31"
Cohesion: 0.20
Nodes (9): Chart, HotkeyActionParams, AxisCreateRangeParams, IndicatorCreateTooltipDataSourceParams, IndicatorDrawParams, OverlayCreateFiguresCallbackParams, OverlayEvent, XAxis (+1 more)

### Community 32 - "Community 32"
Cohesion: 0.17
Nodes (5): IndicatorCreate, getIndicatorClass(), Layout, LayoutPaneContentChild, Options

### Community 33 - "Community 33"
Cohesion: 0.13
Nodes (4): DataLoadMore, DataLoadType, IndicatorOnDataStateChangeParams, isBoolean()

### Community 34 - "Community 34"
Cohesion: 0.22
Nodes (9): HotkeyTemplate, getHotkey(), getSupportedHotkeys(), hotkeys, registerHotkey(), scrollLeft, scrollRight, zoomIn (+1 more)

### Community 35 - "Community 35"
Cohesion: 0.15
Nodes (3): OverlayCreate, OverlayFilter, OverlayOverride

### Community 36 - "Community 36"
Cohesion: 0.31
Nodes (7): PathStyle, computeEllipticalArcParameters(), drawEllipticalArc(), ellipticalArcToBezier(), ellipticalArcToBeziers(), path, PathAttrs

### Community 39 - "Community 39"
Cohesion: 0.29
Nodes (3): lineTo(), isArray(), CandleAreaView

### Community 40 - "Community 40"
Cohesion: 0.27
Nodes (7): getLinearSlopeIntercept(), getLinearYFromCoordinates(), getParallelLines(), parallelStraightLine, priceChannelLine, getRayLine(), rayLine

### Community 47 - "Community 47"
Cohesion: 0.14
Nodes (6): YAxis, CandlePane, IndicatorPane, CrosshairFeatureView, YAxisWidget, getYAxisClass()

### Community 51 - "Community 51"
Cohesion: 0.29
Nodes (5): Kdj, stoch, williamsR, Wr, getMaxMin()

## Knowledge Gaps
- **179 isolated node(s):** `ConvertFilter`, `DomFilter`, `EventTriggerWidgetInfo`, `hotkeyModifierAlias`, `hotkeyAlias` (+174 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **30 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `isValid()` connect `Community 22` to `Community 1`, `Community 2`, `Community 4`, `Community 5`, `Community 7`, `Community 8`, `Community 10`, `Community 11`, `Community 13`, `Community 14`, `Community 16`, `Community 18`, `Community 19`, `Community 20`, `Community 21`, `Community 23`, `Community 24`, `Community 25`, `Community 26`, `Community 27`, `Community 29`, `Community 30`, `Community 31`, `Community 32`, `Community 33`, `Community 35`, `Community 36`, `Community 38`, `Community 39`, `Community 41`, `Community 44`, `Community 45`, `Community 47`, `Community 48`?**
  _High betweenness centrality (0.184) - this node is a cross-community bridge._
- **Why does `StoreImp` connect `Community 4` to `Community 33`, `Community 35`, `Community 38`, `Community 10`, `Community 42`, `Community 44`, `Community 14`, `Community 16`, `Community 48`, `Community 52`, `Community 22`?**
  _High betweenness centrality (0.098) - this node is a cross-community bridge._
- **Why does `ChartImp` connect `Community 9` to `Community 32`, `Community 35`, `Community 38`, `Community 39`, `Community 10`, `Community 11`, `Community 42`, `Community 14`, `Community 48`, `Community 16`, `Community 22`, `Community 24`, `Community 26`, `Community 31`?**
  _High betweenness centrality (0.060) - this node is a cross-community bridge._
- **What connects `ConvertFilter`, `DomFilter`, `EventTriggerWidgetInfo` to the rest of the system?**
  _179 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.060408163265306125 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.07868852459016394 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.12181616832779624 - nodes in this community are weakly interconnected._