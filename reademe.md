> # 1.聊天框内容超出滚动条自动到底部
[div滚动条自动滚到底部]:(div滚动条自动滚到底部.html)
查看[div滚动条自动滚到底部]案例

聊天框设置`固定高,over-flow:auto,` js设置 `元素.scrollTop = div.scrollHeight;`

> # 2.flexible.js & rem
[flexiblejs&rem]:(flexiblejs&rem.html)
查看[flexiblejs&rem]案例

添加flexible.js,页面将根据已有的meta标签来设置缩放比例,将设计稿宽均分100份(每份为a),`1rem = 10a` 字体建议仍用px,例如当前宽为`375px` , `1a = 3.75px,1rem = 37.5px`

> # 3.rem适应布局
[rem适应布局]:(rem适应布局.html)
查看[rem适应布局]案例

html设置`<meta name="viewport" content="width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1,user-scalable=no" />`

css设置`html,body{font-size:625%}`

html设置625%,设置100倍,谷歌火狐均无误差,即 `1rem = 100px || 1px = 0.01rem`