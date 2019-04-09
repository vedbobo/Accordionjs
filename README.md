# Accordionjs
**手风琴幻灯**
需要引入jq
#### HTML 代码 HTML codes
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <link type="text/css" rel="stylesheet" href="Accordionjs.css">
    <title>手风琴幻灯</title>
</head>
<body>
<div class="banner" >
    <div class="mbanner">
        <div data-ac=0>
            <a href="" target="_blank">
                <img class="banner1" src="images/1.jpg"/>
            </a>
            <span>大海</span>
        </div>
        <div data-ac=0>
            <a href="" target="_blank">
                <img class="banner1" src="images/2.jpg"/>
            </a>
            <span>冰山</span>
        </div>
        <div data-ac=1>
            <a href="" target="_blank">
                <img class="banner1" src="images/3.jpg"/>
            </a>
            <span>秋叶</span>
        </div>
    </div>
</div>
<script src="http://apps.bdimg.com/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="Accordionjs.js"></script>
<script>
        $(".mbanner").Accordion({//banner幻灯
            mod: "click",//mouse鼠标移上去模式，click点击切换模式
            dtime: 2500,//延迟
            auto: false//自动切换
        })
</script>
</body>
</html>
```

#### 使用：
``` js
$(".mbanner").Accordion({//banner幻灯
      mod: "click",//mouse鼠标移上去模式，click点击切换模式
      dtime: 2500,//延迟
      auto: false//自动切换
})
```

