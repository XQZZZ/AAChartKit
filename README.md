
![AAChartKit-LOGO](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/AAChartKit-Logo.png)

# AAChartKit
[![Support](https://img.shields.io/badge/support-iOS%206%2B%20-blue.svg?style=flat)](https://www.apple.com/nl/ios/) <br>
[![](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/AAChartModel/AAChartKit/blob/master/LICENSE) <br>
[![](https://img.shields.io/badge/language-OC-green.svg)](https://github.com/AAChartModel/AAChartKit)  <br>
[![](https://img.shields.io/badge/support-Animation-yellow.svg)](https://github.com/AAChartModel/AAChartKit-Swift)  <br>
[![](https://img.shields.io/badge/support-Swift-orange.svg)](https://github.com/AAChartModel/AAChartKit-Swift) <br>
[![](https://jaywcjlove.github.io/sb/lang/chinese.svg)](https://github.com/AAChartModel/AAChartKit/blob/master/CHINESE-README.md) <br>
[![](https://jaywcjlove.github.io/sb/lang/english.svg)](https://github.com/AAChartModel/AAChartKit) <br>
[![](https://img.shields.io/badge/Live-ChartsShow-red.svg)](http://htmlpreview.github.io/?https://github.com/AAChartModel/AAChartKit/blob/master/AAChartKitDemo/ChartsDemo/AAChartKitDocumentLive.html)  <br>
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/AAChartModel/AAChartKit.svg)](http://isitmaintained.com/project/AAChartModel/AAChartKit "Average time to resolve an issue") <br>
[![Percentage of issues still open](http://isitmaintained.com/badge/open/AAChartModel/AAChartKit.svg)](http://isitmaintained.com/project/AAChartModel/AAChartKit "Percentage of issues still open")

## [ **English Document 🇬🇧** ](https://github.com/AAChartModel/AAChartKit)  |  [ **简体中文文档 🇨🇳** ](https://github.com/AAChartModel/AAChartKit/blob/master/CHINESE-README.md)| [ **繁體中文文檔 🇭🇰** ](https://github.com/AAChartModel/AAChartKit/blob/master/TRADITIONAL-CHINESE-README.md)

### The Swift version of AAChartKit can be found here:
#### *https://github.com/AAChartModel/AAChartKit-Swift*

## Preface

AAChartKit is an elegant, friendly and easy to use chart library for iOS, based on the open source `Highcharts` JS libraries. AAChartKit is extremely powerful, easy to configure and a pleasure to use. Currently AAChartKit includes support for the following chart types: column chart, bar chart, area chart, area spline chart, line chart, spline chart, radar chart, polar chart, pie chart, bubble chart, pyramid chart, funnel chart, column range and area range chart. More chart types are planned to be supported. AAChartKit gives you easy and fast access to a wide range of chart types, hassle-free and quick to integrate into your own project.
 
***
## Features

* 🎂  Support up from `iOS 6`, `ARC` support.
* 🚀  Powerful and easy to use. It supports `column chart`, `bar chart`, `area chart`, `areaspline chart`, `line chart`, `spline chart`, `radar chart`, `polar chart`, `pie chart`, `bubble chart`, `pyramid chart`, `funnel chart`, `columnrange chart`, `arearange chart`, `mixed chart` and other graphics. Support for more chart types is planned.
* 🦋  The charts are interactive and animated. The `animation` effect is exquisite, delicate, smooth and beautiful.
* ⛓. Supports `chain programming syntax` like *Masonry* 
* 💑  `AAChartView + AAChartModel = Chart`. The AAChartKit follows a minimalist formula: Chart view + Chart model = The chart you want, just like the powerful and beautiful charts lib [AAInfographics](https://github.com/AAChartModel/AAChartKit-Swift)
***

## Beauty Appreciation

| Column Chart  | Column Range Chart  | Area Chart  |
| :----:  | :----: | :----: |
| ![image1](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/BeautyAppreciation/ColumnChart.png) | ![image1](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/BeautyAppreciation/BarChart.png) | ![image1](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/BeautyAppreciation/AreaChart.png) |

| Line Chart  | Step Area Chart  | Step Line Chart  |
| :----:  | :----: | :----: |
| ![image1](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/BeautyAppreciation/LineChart.png) | ![image1](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/BeautyAppreciation/StepAreaChart.png) | ![image1](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/BeautyAppreciation/StepLineChart.png) |

| Spline Chart | Areaspline Chart  | Stacked Polar Chart  |
| :----:  | :----: | :----: |
| ![image1](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAChartKit/splineChart.png) | ![image1](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAChartKit/areasplineChart.png) | ![image1](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAChartKit/percentStackingAreasplineChart.png) |

| Bubble Chart  | Arearange Average Value Chart  | Column Mixed Line Chart  |
| :----:  | :----: | :----: |
| ![image1](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAInfographics/BubbleChart.png) | ![image1](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAInfographics/ArearangeAverageValueChart.png) | ![image1](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAInfographics/ColumnMixedLineChart.png) |

| Scatter Chart  | Boxplot  Chart  | Mirror Column Chart  |
| :----:  | :----: | :----: |
| ![image1](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAChartKit/scatterChart.png) | ![image1](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAChartKit/boxplotChart.png) | ![image1](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAChartKit/MirrorColumnChart.png) |

## Installation

### CocoaPods (recommend)
1. Add following content
```ruby
pod 'AAChartKit', :git => 'https://github.com/AAChartModel/AAChartKit.git'
```
 to your `Podfile`.
 
2. Run `pod install` or `pod update`.


### Manually (old school way)
1. Drag the `AAChartKitLib` folder into your project.

2. Add the following to your `.pch` file.
```objective-c
#import "AAGlobalMacro.h"
```

### Usage
1. Add the following to your view controller file:
```objective-c
#import "AAChartKit.h"
```

2. Create an instance object of chart view:`AAChartView`
```objective-c
CGFloat chartViewWidth  = self.view.frame.size.width;
CGFloat chartViewHeight = self.view.frame.size.height-250;
_aaChartView = [[AAChartView alloc]init];
_aaChartView.frame = CGRectMake(0, 60, chartViewWidth, chartViewHeight);
//_aaChartView.scrollEnabled = NO;
//// set the content height of aaChartView
// _aaChartView.contentHeight = chartViewHeight;
[self.view addSubview:_aaChartView];
```

3. Configure the chart model properties: `AAChartModel`                                          
```objective-c
AAChartModel *aaChartModel= AAObject(AAChartModel)
.chartTypeSet(AAChartTypeColumn)
.titleSet(@"THE HEAT OF PROGRAMMING LANGUAGE")
.subtitleSet(@"Virtual Data")
.categoriesSet(@[@"Java",@"Swift",@"Python",@"Ruby", @"PHP",@"Go",@"C",@"C#",@"C++"])
.yAxisTitleSet(@"Degrees Celsius")
.seriesSet(@[
        AAObject(AASeriesElement)
        .nameSet(@"2017")
        .dataSet(@[@7.0, @6.9, @9.5, @14.5, @18.2, @21.5, @25.2, @26.5, @23.3, @18.3, @13.9, @9.6]),
        AAObject(AASeriesElement)
        .nameSet(@"2018")
        .dataSet(@[@0.2, @0.8, @5.7, @11.3, @17.0, @22.0, @24.8, @24.1, @20.1, @14.1, @8.6, @2.5]),
        AAObject(AASeriesElement)
        .nameSet(@"2019")
        .dataSet(@[@0.9, @0.6, @3.5, @8.4, @13.5, @17.0, @18.6, @17.9, @14.3, @9.0, @3.9, @1.0]),
        AAObject(AASeriesElement)
        .nameSet(@"2020")
        .dataSet(@[@3.9, @4.2, @5.7, @8.5, @11.9, @15.2, @17.0, @16.6, @14.2, @10.3, @6.6, @4.8]),
                 ])
;
```
4. Draw the chart (this method is only called the first time you create an AAChartView instance object) 
```objective-c
//The chart view object calls the instance object of AAChartModel and draws the final graphic
[_aaChartView aa_drawChartWithChartModel:aaChartModel];
```

🌹🌹🌹Congratulations! Everything was done!!! You will get what you want!!!🌈🌈🌈

### Update chart content 
if you want to refresh chart content,you should do something as follow.According to your actual needs, select the function that fits you.

*  Refresh the chart data (this method is recommended for updating the series data dynamically)
```objective-c
//Refresh the chart dynamically only when the series attribute of the AAChartModel object is updated
[_aaChartView aa_onlyRefreshTheChartDataWithChartModelSeries:aaChartModelSeriesArray];
```

*  Refresh the chart, minus the chart data (this method is recommended for subsequent refreshes after the first drawing of graphics has completed. If you want to update the chart data only, you should use the function `aa_onlyRefreshTheChartDataWithChartModelSeries`)
```objective-c
//Refresh the chart after the AAChartModel content is updated
[_aaChartView aa_refreshChartWithChartModel:aaChartModel];
```

## Samples

-  ### line chart

![IMG_1867.JPG](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/LineChart.png)

-  ### column chart

![IMG_1873.JPG](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/ColumnChart.png)

- ###  bar chart

![IMG_1880.JPG](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/BarChart.png)

- ### special area chart one

![IMG_1869.JPG](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/IMG_1482.JPG)

- ### special area chart two

![IMG_1871.JPG](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAInfographics/AreaChartOne.png)

- ### special area chart three

![IMG_1863.JPG](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/PictureResources/屏幕快照%202017-05-06%20下午6.58.15.png)

- ### radar chart

![IMG_1877.JPG](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/RadarChart.png)

- ### polar chart

![IMG_1879.JPG](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/PolarChart.png)

- ### pie chart

![IMG_1878.JPG](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/PieChart.png)

- ### bubble chart

![IMG_1875.JPG](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAChartKit/BubbleChart.png)

- ### scatter chart

![scatter chart](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAInfographics/ScatterChart.png)

- ### arearange chart

![arearange chart](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAInfographics/ArearangeChart.png)

- ### step area chart

![step area chart](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAInfographics/StepAreaChart.png)

- ### mixed chart

![mixed chart](https://raw.githubusercontent.com/AAChartModel/loadHtmlCssJsDemo-master/master/AAInfographics/MixedChart.png)

## More graphics

>>> * Note: The following `DEMO picture` is a `GIF dynamic picture` which has a size of around *6M*. If you don't see any dynamic preview, then this is because the picture resources were not fully loaded. In such a case please be patient and wait for the contents to finish loading. Maybe you need to reload this page.

![AAChartKit-Live](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAChartKit/AAChartKit-Live.gif)


## Special instructions

### Support user click events and move over events

you can monitor the user touch events message through implementing delegate function for AAChartView instance object


```objc
 //Set AAChartView events delegate
 self.aaChartView.delegate = self;
 
 //set AAChartModel support user touch event
 self.aaChartModel.touchEventEnabledSet(true)

 //implement AAChartView user touch events delegate function
 #pragma mark -- AAChartView delegate
 - (void)aaChartView:(AAChartView *)aaChartView moveOverEventWithMessage:(AAMoveOverEventMessageModel *)message {
 NSLog(@"🚀selected point series element name: %@",message.name);
 }

```

The received touch events message contain following content

```objc
@interface AAMoveOverEventMessageModel : NSObject

@property (nonatomic, copy)   NSString *name; 
@property (nonatomic, strong) NSNumber *x; 
@property (nonatomic, strong) NSNumber *y;
@property (nonatomic, copy)   NSString *category;
@property (nonatomic, strong) NSDictionary *offset;
@property (nonatomic, assign) NSUInteger index;

@end
```


### Support for custom the style of chart `AATooltip` through `JavaScript` function

As we all know, AAInfographics support using `HTML` String.  Most of time, the `headerFormat` 、`pointFormat`、`footerFormat` HTML string is enough for customizing chart tooltip string content, However, sometimes the needs of APP is so weird to satified, in this time, you can even customize the chart tooltip style through `JavaScript` function. 

For example, configuring AATooltip instance object properties as follow:


```objc
 /*Custom Tooltip Style ---*/
    AATooltip *tooltip = aaOptions.tooltip;
    tooltip
    .useHTMLSet(true)
    .formatterSet(@AAJSFunc(function () {
        return ' 🌕 🌖 🌗 🌘 🌑 🌒 🌓 🌔 <br/> '
        + ' Support JavaScript Function Just Right Now !!! <br/> '
        + ' The Gold Price For <b>2020 '
        +  this.x
        + ' </b> Is <b> '
        +  this.y
        + ' </b> Dollars ';
    }))
    .valueDecimalsSet(@2)
    .backgroundColorSet(@"#000000")
    .borderColorSet(@"#000000")
    .styleSet((id)AAStyle.new
              .colorSet(@"#FFD700")
              .fontSizeSet(@"12px"))
    ;
```

you can get the customized tooltip style chart like this👇
![](https://user-images.githubusercontent.com/16357599/56589690-543c5880-6618-11e9-9d18-6bc0fe2fa53f.png)


### Support value range segmentation 


* chart with value range segmentation `bands 🎀`
![plotBandsChart](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAChartKit/plotBandsChart.png)


* chart with value range segmentation `lines 🧶`
![plotLinesChart](https://raw.githubusercontent.com/AAChartModel/Gallery/master/AAChartKit/plotLinesChart.png)

### Supported chart types for now
```objective-c
typedef NSString *AAChartType;

AACHARTKIT_EXTERN AAChartType const AAChartTypeColumn;          //column chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeBar;             //bar chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeArea;            //area chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeAreaspline;      //area spline chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeLine;            //line chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeSpline;          //spline chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeScatter;         //scatter chart
AACHARTKIT_EXTERN AAChartType const AAChartTypePie;             //pie chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeBubble;          //bubble chart
AACHARTKIT_EXTERN AAChartType const AAChartTypePyramid;         //pyramid chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeFunnel;          //funnel chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeColumnrange;     //column range chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeArearange;       //area range chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeAreasplinerange; //area spline range chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeBoxplot;         //box plot chart
AACHARTKIT_EXTERN AAChartType const AAChartTypeWaterfall;       //Waterfall chart
AACHARTKIT_EXTERN AAChartType const AAChartTypePolygon;         //polygon chart
```
### Supported zoom guesture types for now
```Objective-c
typedef NSString *AAChartZoomType;

AACHARTKIT_EXTERN AAChartZoomType const AAChartZoomTypeNone;
AACHARTKIT_EXTERN AAChartZoomType const AAChartZoomTypeX;
AACHARTKIT_EXTERN AAChartZoomType const AAChartZoomTypeY;
AACHARTKIT_EXTERN AAChartZoomType const AAChartZoomTypeXY;
```

### Supported animation types for now
```objective-c
typedef NS_ENUM(NSInteger,AAChartAnimation) {
    AAChartAnimationLinear = 0,
    AAChartAnimationEaseInQuad,
    AAChartAnimationEaseOutQuad,
    AAChartAnimationEaseInOutQuad,
    AAChartAnimationEaseInCubic,
    AAChartAnimationEaseOutCubic,
    AAChartAnimationEaseInOutCubic,
    AAChartAnimationEaseInQuart,
    AAChartAnimationEaseOutQuart,
    AAChartAnimationEaseInOutQuart,
    AAChartAnimationEaseInQuint,
    AAChartAnimationEaseOutQuint,
    AAChartAnimationEaseInOutQuint,
    AAChartAnimationEaseInSine,
    AAChartAnimationEaseOutSine,
    AAChartAnimationEaseInOutSine,
    AAChartAnimationEaseInExpo,
    AAChartAnimationEaseOutExpo,
    AAChartAnimationEaseInOutExpo,
    AAChartAnimationEaseInCirc,
    AAChartAnimationEaseOutCirc,
    AAChartAnimationEaseInOutCirc,
    AAChartAnimationEaseOutBounce,
    AAChartAnimationEaseInBack,
    AAChartAnimationEaseOutBack,
    AAChartAnimationEaseInOutBack,
    AAChartAnimationElastic,
    AAChartAnimationSwingFromTo,
    AAChartAnimationSwingFrom,
    AAChartAnimationSwingTo,
    AAChartAnimationBounce,
    AAChartAnimationBouncePast,
    AAChartAnimationEaseFromTo,
    AAChartAnimationEaseFrom,
    AAChartAnimationEaseTo,
};

```

Here are the ten concrete animation types of AAChartKit

| Back      | Bounce    | Circ      | Cubic     | Elastic   |
|:---------:|:---------:|:---------:|:---------:|:---------:|
| ![][1]    | ![][2]    | ![][3]    | ![][4]    | ![][5]    |


| Expo      | Quad      | Quart     | Quint     | Sine      |
|:---------:|:---------:|:---------:|:---------:|:---------:|
| ![][6]    | ![][7]    | ![][8]    | ![][9]    | ![][10]   |


## AAChartModel:chart attribute list
```objective-c
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, title);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSNumber *, titleFontSize);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, titleFontColor);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, titleFontWeight);

AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, subtitle);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSNumber *, subtitleFontSize);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, subtitleFontColor);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, subtitleFontWeight);

AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSArray  *, series);

AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, AAChartSubtitleAlignType, subtitleAlign);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, AAChartType,              chartType);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, AAChartStackingType,      stacking);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, AAChartSymbolType,        symbol);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, AAChartSymbolStyleType,   symbolStyle);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, AAChartZoomType,          zoomType);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, AAChartAnimation,         animationType);

AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSNumber *, animationDuration);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       inverted);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       xAxisReversed);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       yAxisReversed);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       gradientColorEnabled);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       polar);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       dataLabelEnabled);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, dataLabelFontColor);
AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSNumber *, dataLabelFontSize);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, dataLabelFontWeight);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       xAxisLabelsEnabled);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSNumber *, xAxisLabelsFontSize);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, xAxisLabelsFontColor);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, xAxisLabelsFontWeight);
AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSArray  *, categories);
AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSNumber *, xAxisGridLineWidth);
AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSNumber *, xAxisTickInterval);

AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       xAxisVisible);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       yAxisVisible);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       yAxisLabelsEnabled);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, yAxisTitle);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSNumber *, yAxisLabelsFontSize);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, yAxisLabelsFontColor);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, yAxisLabelsFontWeight);
AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSNumber *, yAxisGridLineWidth);
AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSArray     <NSString *>*, colorsTheme);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, backgroundColor);

AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       tooltipEnabled);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, tooltipValueSuffix);
AAPropStatementAndPropSetFuncStatement(copy  , AAChartModel, NSString *, tooltipValueString);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       tooltipCrosshairs);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       connectNulls);
AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       legendEnabled);

AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSNumber *, borderRadius);
AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSNumber *, markerRadius);

AAPropStatementAndPropSetFuncStatement(assign, AAChartModel, BOOL,       yAxisAllowDecimals);
AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSArray  *, yAxisPlotLines);
AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSNumber *, yAxisMax);
AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSNumber *, yAxisMin);
AAPropStatementAndPropSetFuncStatement(strong, AAChartModel, NSArray  *, yAxisTickPositions);
AAPropStatementAndPropSetFuncStatement(copy,   AAChartModel, NSString *, zoomResetButtonText);

```

## Created By:

![](https://avatars1.githubusercontent.com/u/16357599?s=40&v=4)An An

```java
                         _0_
                       _oo0oo_
                      o8888888o
                      88" . "88
                      (| -_- |)
                      0\  =  /0
                    ___/`---'\___
                  .' \\|     |// '.
                 / \\|||  :  |||// \
                / _||||| -:- |||||- \
               |   | \\\  -  /// |   |
               | \_|  ''\---/''  |_/ |
               \  .-\__  '-'  ___/-. /
             ___'. .'  /--.--\  `. .'___
          ."" '<  `.___\_<|>_/___.' >' "".
         | | :  `- \`.;`\ _ /`;.`/ - ` : | |
         \  \ `_.   \_ __\ /__ _/   .-` /  /
     =====`-.____`.___ \_____/___.-`___.-'=====
                       `=---='
*****************************************************
     ¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥¥
         €€€€€€€€€€€€€€€€€€€€€€€€€€€€€€€€€€
               $$$$$$$$$$$$$$$$$$$$$$$  
                   BUDDHA_BLESS_YOU       
                      AWAY_FROM
                         BUG

```
## Source Code⛓

Language Version | Project Name | Source Code Link |
------------ | ------------- | ------------- |
Objective C | AAChartKit | https://github.com/AAChartModel/AAChartKit |
Swift | AAInfographics | https://github.com/AAChartModel/AAChartKit-Swift |

## LICENSE

![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/License_icon-mit-88x31-2.svg/128px-License_icon-mit-88x31-2.svg.png)
AAChartKit is available under the MIT license. See the [LICENSE](https://github.com/AAChartModel/AAChartKit/blob/master/LICENSE) file for more information.

## Contact

-------------------------------------------------------------------------------
* 🌕 🌖 🌗 🌘   WARM TIPS!!!   🌑 🌒 🌓 🌔
*
* Please contact me on GitHub, if there are any problems encountered in use.
* GitHub Issues : https://github.com/AAChartModel/AAChartKit/issues
-------------------------------------------------------------------------------
* And if you want to contribute for this project, please contact me as well
* GitHub        : https://github.com/AAChartModel
* StackOverflow : https://stackoverflow.com/users/7842508/codeforu
* JianShu       : http://www.jianshu.com/u/f1e6753d4254
* SegmentFault  : https://segmentfault.com/u/huanghunbieguan
-------------------------------------------------------------------------------

## Postscript

If you want to shrink the size of the `AAChartKit` lib, you should do something like this:
1. Delete the `.js` file of `AAJSFiles` folder in `AAChartKit`. The names of the files that need to be deleted are the following:

* AAHighchartsLib.js
* AAHighchartsMore.js
* AAFunnel.js

2. Change the content of `AAChartView.html` file 
``` html
<script src="AAHighchartsLib.js">
</script>
<script src="AAHighchartsMore.js">
</script>
<script src="AAFunnel.js">
</script>
```
to be 

``` html
<script src="https://img.hcharts.cn/highcharts/highcharts.js">
</script>
<script src="https://img.hcharts.cn/highcharts/highcharts-more.js">
</script>
<script src="https://img.hcharts.cn/highcharts/modules/funnel.js">
</script>
```
## To-Do list

 - [x] Support user to add delegate events after the graphics content loading was completed
 - [x] Support graphics to refresh global content dynamically
 - [x] Support graphics to refresh pure data (`series`) content dynamically
 - [x] Support graphics to refresh pure data in real time and scroll dynamically
 - [x] Support color layer gradient effects
 - [x] Support 3D graphics effects, valid only for partial graphics such as `column chart、bar chart、pie charts、scatterplot chart、bubble chart`, etc.
 - [x] Support `CocoaPods`
 - [ ] Support `Carthage`
 - [ ] Support  code coverage test
 - [ ] Support horizontal screen (full screen) effect
 - [ ] Support setting graphics rendering animation freely
 - [ ] Support rendered graphics to generate image files
 - [ ] Support generating image files saved to the system album
 - [x] Support user to configure `AAOptions` model object properties freely
 - [x] Support stacking the graphics 
 - [x] Support reversing the graphics axis 
 - [x] Support rendering scatter chart
 - [x] Support rendering column range map
 - [x] Support rendering area range graph
 - [x] Support rendering the polar chart
 - [x] Support rendering the step line chart
 - [x] Support rendering the step area chart
 - [x] Support rendering the Nightingale rose 🌹chart
 - [x] Support rendering the circular progress bar chart 
 - [x] Support adding clicked event callbacks for graphics

[1]:  https://raw.githubusercontent.com/adad184/MMTweenAnimation/master/Images/1.gif
[2]:  https://raw.githubusercontent.com/adad184/MMTweenAnimation/master/Images/2.gif
[3]:  https://raw.githubusercontent.com/adad184/MMTweenAnimation/master/Images/3.gif
[4]:  https://raw.githubusercontent.com/adad184/MMTweenAnimation/master/Images/4.gif
[5]:  https://raw.githubusercontent.com/adad184/MMTweenAnimation/master/Images/5.gif
[6]:  https://raw.githubusercontent.com/adad184/MMTweenAnimation/master/Images/6.gif
[7]:  https://raw.githubusercontent.com/adad184/MMTweenAnimation/master/Images/7.gif
[8]:  https://raw.githubusercontent.com/adad184/MMTweenAnimation/master/Images/8.gif
[9]:  https://raw.githubusercontent.com/adad184/MMTweenAnimation/master/Images/9.gif
[10]: https://raw.githubusercontent.com/adad184/MMTweenAnimation/master/Images/10.gif
