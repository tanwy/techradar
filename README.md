打造个人技术雷达

受到ThoughtWorks技术雷达的启发: http://www.thoughtworks.com/radar/.

我非常喜欢ThoughtWorks技术雷达。但是它是针对所有客户，跨产业、跨组织的平均成熟度和风险厌恶。

![Technology Radar Sample](/techradar_example.png?raw=true)

这是一个强大的话题了，但是我需要它为特定情况定制。

本项目的技术的雷达有着很简单的功能，使用JSON数据源，在HTML内部渲染成SVG。

目前提供的数据按照径向格式提供。我选择这个格式和SVG,是为了尽可能可变。在实践中，一个表格形式结构,在进行自动化布局这些点，将会非常有用。

例如. {name:'Cool Tech', r:50, t:30}，出现在右上象限，"采用"这一节内部。

例如. {name:'Bright Shiny Toy 5', r:390, t:30} 出现在右上象限，在最外层最“保持”的这一节。

Appears in the Lower Left Quadrant, in the second "Trial" Sector.

Where r = radius, and t = theta; the degrees in radians. with 0/360 degrees being the typical right hand x line rotating in an anti-clockwise direction.

See http://en.wikipedia.org/wiki/Polar_coordinates for more details.
