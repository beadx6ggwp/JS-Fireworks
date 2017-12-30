# JS-Fireworks

Happy new year!

用JavaScript Canvas寫個簡易粒子特效，來做個跨年煙火。

可以到此連結遊玩，使用滑鼠左鍵施放煙火

連結 : [Click Here](http://davidhsu666.com/downloads/js_Fireworks)

![Alt Text](example/firework3.gif)

## TODO

- 粒子爆炸範圍越大，煙火主體越大顆，且飛行速度慢，希望有集氣的感覺

- 半徑也跟著Alpha變化

- 粒子數與爆炸範圍的比例調整，當前比例有待調整，可使用map區間函數

- 煙火信號彈

- 煙火發射煙霧特效，煙火發射時尾端的火花特效

- 隨機的風，讓煙火與粒子在飛行時看起來比較自然

- 煙火編排

- 文字特效，Math.Sin對Hue的漸變效果，將其用在 this.hue + Math.sin(週期)*30，也許有黃色漸變效果

- 陰影特效，能加在文字上，可達成光暈的效果

- 效能優化，渲染跟粒子的更新效率還有待研究