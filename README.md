打造个人技术雷达

受到ThoughtWorks技术雷达的启发: http://www.thoughtworks.com/radar/.

我非常喜欢ThoughtWorks技术雷达。但是它是针对所有客户，跨产业、跨组织的平均成熟度和风险厌恶。

这是一个强大的话题了，但是我需要它为特定情况定制。

本项目的技术的雷达有着很简单的功能，使用JSON数据源，在HTML内部渲染成SVG。

目前提供的数据按照径向格式提供。我选择这个格式和SVG,是为了尽可能可变。在实践中，一个表格形式结构,在进行自动化布局这些点，将会非常有用。

例如. {name:'Cool Tech', r:50, t:30}，出现在右上象限，"采用"这一节内部。

例如. {name:'Bright Shiny Toy 5', r:390, t:30} 出现在右上象限，在最外层最“保持”的这一节。

Appears in the Lower Left Quadrant, in the second "Trial" Sector.

Where r = radius, and t = theta; the degrees in radians. with 0/360 degrees being the typical right hand x line rotating in an anti-clockwise direction.

See http://en.wikipedia.org/wiki/Polar_coordinates for more details.

<h4>采用</h4>
对于采用环里的技术，我们强烈主张业界采用它们。如果适合我们的项目，我们就尽量毫不犹豫地使用。
<h4>实验</h4>
试验环列出的技术是你（和同事）认为值得去追求的。理解如何建立这种能力十分重要。现在是时候在一个低风险的项目上试点，实践这项技术，这样你就可以真正的了解它。
<h4>评估</h4>
评估环里出现的条目表示的是值得研究一番的技术，以确认它将对你产生何种影响。你应该投入一些精力（例如开发调查、科研项目、参加会议讲座等等）来确定它是否会对你所在的组织产生影响。
<h4>暂缓</h4>
暂缓环逐渐演化成了“别用这项技术启动任何新项目”。在已有项目上使用它没有坏处，但是想在新开发的项目上使用这个技术的话需要三思而行。暂缓是最靠近避免范畴的


![Technology Radar Sample](/techradar_example.png?raw=true)
