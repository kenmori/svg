# svg

実践1
width 200 height 200 の中にviewBox 0 0 200 200、
x 50 y 100 width 100 height 100 stroke 2 の四角形を描いてください




```
<svg width="200" height="200" viewBox="0 0 200 200">
  <rect x="50" y="100" width="100" height="100" style="stroke:black;fill:none;stroke-width: 2px;" />
  <polyline points="50 100, 100 25, 150 100" style="stroke-width:2;stroke:black; fill: none;" />
  <line x1="50" y1="20" x2="100" y2="25" stroke="red" stroke-width="1" />
  <text font-family="Arial" font-size="100" x="5" y="125" stroke-width="1" stroke="red" fill="none">森田けんじ</text>
</svg>


<svg width="45" height="135" viewBox="0 0 90 90" preserveAspectRatio="xMinYMin meet">
    <text font-family="Arial" font-size="10" x="5" y="12" stroke-width="1" stroke="red" fill="none">森田けんじ</text>

</svg>

<svg width="45" height="135" viewBox="0 0 90 90" preserveAspectRatio="xMidYMid meet">
    <text font-family="Arial" font-size="10" x="5" y="12" stroke-width="1" stroke="red" fill="none">森田けんじ</text>
</svg>


<svg width="45" height="135" viewBox="0 0 90 90" preserveAspectRatio="xMinYMax meet">
    <text font-family="Arial" font-size="10" x="5" y="12" stroke-width="1" stroke="red" fill="none">森田けんじ</text>
</svg>


<svg width="500" height="500">
<path d="M50,50 l100,100 h200 v200" stroke="black" fill="none"></path>
</svg>
```