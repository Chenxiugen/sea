---
description: 主要是抹平不同浏览器初始样式差异化
---

# CSS初始化

#### 雅虎搜索

点击时的区域标题 \`\`\`bash echo "hello shell" echo "hello python" \`\`\`

```text
<details>
  <summary>点击时的区域标题</summary>
  ```bash
  echo "hello shell"
  echo "hello python"
  ```
</details>
```

&lt;details&gt;

&lt;summary&gt;雅虎搜索的初始化样式&lt;/summary&gt;

```css

body,html {
    background: 0 36px repeat-y url(//img.alicdn.com/imgextra/i3/O1CN01PaQurJ1QgnAICTCgg_!!6000000002006-2-tps-1490-2984.png);
    background-size: cover
}

.cup {
    margin: 0 auto
}

.clearfix {
    *zoom:1}

.clearfix:after,.clearfix:before {
    content: " ";
    display: table
}

.clearfix:after {
    height: 0;
    line-height: 0;
    visibility: hidden;
    clear: both
}

.clearfix:after,.clearfix:before {
    content: " ";
    display: table
}

.clearfix:after {
    height: 0;
    line-height: 0;
    visibility: hidden;
    clear: both
}

body {
    color: #3C3C3C;
    -webkit-font-smoothing: antialiased;
    background-color: #fff
}

body a {
    color: #3C3C3C
}

body a:hover {
    color: #F40;
    text-decoration: none
}

body a:focus {
    outline: 0
}

body.disable-hover {
    pointer-events: none
}

.hotsale-loading {
    display: block;
    height: 120px;
    margin-top: 20px
}

.ml6 {
    margin-left: 6px
}

area {
    outline: 0
}

.J_Module {
    min-height: 0;
    background-color: #FFF
}

.hide,.tb-hide {
    display: none
}

.tb-pass {
    background-color: transparent
}

.loading,.tb-loading {
    background-image: url(//img.alicdn.com/tfs/TB1BlobNFXXXXXyXXXXXXXXXXXX-34-34.gif);
    background-repeat: no-repeat;
    background-position: center;
    min-height: 40px
}

.tb-loading {
    background-color: #FFF
}

.clearfix {
    *zoom:1}

.clearfix:after,.clearfix:before {
    content: " ";
    display: table
}

.clearfix:after {
    height: 0;
    line-height: 0;
    visibility: hidden;
    clear: both
}

.clearfix:after,.clearfix:before {
    content: " ";
    display: table
}

.clearfix:after {
    height: 0;
    line-height: 0;
    visibility: hidden;
    clear: both
}
```

&lt;/details&gt;

```text
html {
    color: #000;
    background: #FFF
}

body,div,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,h5,h6,pre,code,form,fieldset,legend,input,textarea,p,blockquote,th,td {
    margin: 0;
    padding: 0
}

table {
    border-collapse: collapse;
    border-spacing: 0
}

fieldset,img {
    border: 0
}

address,caption,cite,code,dfn,em,strong,th,var {
    font-style: normal;
    font-weight: normal
}

ol,ul {
    list-style: none
}

caption,th {
    text-align: left
}

h1,h2,h3,h4,h5,h6 {
    font-size: 100%;
    font-weight: normal
}

q:before,q:after {
    content: ''
}

abbr,acronym {
    border: 0;
    font-variant: normal
}

sup {
    vertical-align: text-top
}

sub {
    vertical-align: text-bottom
}

input,textarea,select {
    font-family: inherit;
    font-size: inherit;
    font-weight: inherit
}

input,textarea,select {
    *font-size: 100%
}

legend {
    color: #000
}

#yui3-css-stamp.cssreset {
    display: none
}

body {
    font: 13px/1.231 arial,helvetica,clean,sans-serif;
    *font-size: small;
    *font: x-small
}

select,input,button,textarea {
    font: 99% arial,helvetica,clean,sans-serif
}

table {
    font-size: inherit;
    font: 100%
}

pre,code,kbd,samp,tt {
    font-family: monospace;
    *font-size: 108%;
    line-height: 100%
}

html {
    height: 100%
}

select,input,button,textarea,body {
    font: 13px / 1.25 helvetica neue,helvetica,arial,sans-serif;
    color: #000
}

body {
    -webkit-text-size-adjust: 100%;
    height: 100%;
    min-height: 700px;
    max-height: 1080px;
    min-width: 980px;
    position: relative;
    margin: auto
}

.off-left {
    left: -9999px;
    position: absolute
}

a:link,a:visited {
    text-decoration: none
}

a:hover {
    text-decoration: underline
}

input::-ms-clear {
    display: none
}
```

