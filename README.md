# DonutChart
An animatable donut chart view written in swift 3.

# Features

* Fully customizable through interface builder

![alt tag](https://raw.githubusercontent.com/zbamstudio/DonutChart/master/ReadmeAssets/donutChartInterfaceDesign.gif)

* Progress of the chart can be animated with CABasicAnimation
```Swift
        let animation = CABasicAnimation(keyPath: "progress")
        animation.fromValue = 0.2
        animation.toValue = 1.0
        animation.duration = 2
        animation.fillMode = kCAFillModeForwards
        chart.layer.add(animation, forKey: "progress")
```
* Can achieve large variety of look & feel

![alt tag](https://raw.githubusercontent.com/zbamstudio/DonutChart/master/ReadmeAssets/example.png)
