# daydays


#.gitHub 我的一个gitHub ,记录每日遇到的问题



#  pointer-events属性值详解

可以用于暂时鼠标点击失效，无法点击
pointer-events:  auto | none | visiblePainted | visibleFill | visibleStroke | visible | painted | fill | stroke | all | inherit

auto——效果和没有定义pointer-events属性相同，鼠标不会穿透当前层。在SVG中，该值和visiblePainted的效果相同。
none——元素不再是鼠标事件的目标，鼠标不再监听当前层而去监听下面的层中的元素。但是如果它的子元素设置了pointer-events为其它值，比如auto，鼠标还是会监听这个子元素的。其它属性值为SVG专用

disabled{pointer-events:none}

