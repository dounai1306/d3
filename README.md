#D3.js

d3.js是操纵基于数据的Js库，数据驱动DOM的库，在https://github-ranking.com/上，排名第五。

D3的学习成本略高，且相对来说，国内关于D3.v4的中文资料还是蛮少的，不像highcharts\echart照着demo就可以撸。尤其对于之前学习v3的童鞋，v4版本还是需要看一些api的，改动可以说还是很大的。在D3.v3版本，被吐槽最多的就是svg数据量支持问题，不过在V4版本中，D3新增了canvas。

与highcharts、echart等大部分库不同，这些库相当于一个函数，只要你的数据格式输入正常，调用函数，就可以绘制出漂亮的图表。而D3是将数据处理为D3的绘图数据，通过数据去绘制对应的图形，从而形成图表。

在工作中，如果highchart可以实现的图表，就不必要去选D3。如果需要定制，那么D3就可以拿来用了。

安利两个学习D3的网站：http://www.ourd3js.com/和https://github.com/tianxuzhang/d3.v4-API-Translation
前者是D3.v3的一个学习资源，尽管v4和v3区别很大，但还是值得一看，顺着v3撸一个v4。

后面的D3 demo都是D3.v4，demo基于http://www.ourd3js.com/