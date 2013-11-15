# icon

---

通用网站图标
---

## 图标列表

图标来自阿里www.iconfont.cn
<link rel="stylesheet" href="src/icon.css">
<style>
    .nico-insert-code{overflow:hidden;clear:both;}
    .icon_lists{clear:both;}
    .icon_lists li {text-align:center;float:left;list-style:none;padding:10px;}
</style>
````html
<ul class="icon_lists clear">
    <li>
        <i class="x-icon">&#13539</i>
        <div class="name">正确</div>
        <div class="code">13539/0x34e3</div>
    </li>

    <li>
        <i class="x-icon">&#13540</i>
        <div class="name">错误</div>
        <div class="code">13540/0x34e4</div>
    </li>

    <li>
        <i class="x-icon">&#13541</i>
        <div class="name">禁止</div>
        <div class="code">13541/0x34e5</div>
    </li>

    <li>
        <i class="x-icon">&#13542</i>
        <div class="name">提醒</div>
        <div class="code">13542/0x34e6</div>
    </li>

    <li>
        <i class="x-icon">&#13543</i>
        <div class="name">提示</div>
        <div class="code">13543/0x34e7</div>
    </li>

    <li>
        <i class="x-icon">&#13544</i>
        <div class="name">警告</div>
        <div class="code">13544/0x34e8</div>
    </li>

    <li>
        <i class="x-icon">&#13545</i>
        <div class="name">帮助</div>
        <div class="code">13545/0x34e9</div>
    </li>

    <li>
        <i class="x-icon">&#13557</i>
        <div class="name">等待</div>
        <div class="code">13557/0x34f5</div>
    </li>

    <li>
        <i class="x-icon">&#13677</i>
        <div class="name">赞扬</div>
        <div class="code">13677/0x356d</div>
    </li>

    <li>
        <i class="x-icon">&#13678</i>
        <div class="name">批评</div>
        <div class="code">13678/0x356e</div>
    </li>

    <li>
        <i class="x-icon">&#13679</i>
        <div class="name">设置</div>
        <div class="code">13679/0x356f</div>
    </li>

    <li>
        <i class="x-icon">&#13680</i>
        <div class="name">删除</div>
        <div class="code">13680/0x3570</div>
    </li>

    <li>
        <i class="x-icon">&#13683</i>
        <div class="name">信息</div>
        <div class="code">13683/0x3573</div>
    </li>

    <li>
        <i class="x-icon">&#13684</i>
        <div class="name">帮助</div>
        <div class="code">13684/0x3574</div>
    </li>

    <li>
        <i class="x-icon">&#13685</i>
        <div class="name">收藏</div>
        <div class="code">13685/0x3575</div>
    </li>

    <li>
        <i class="x-icon">&#13686</i>
        <div class="name">喜爱</div>
        <div class="code">13686/0x3576</div>
    </li>

    <li>
        <i class="x-icon">&#13696</i>
        <div class="name">编辑</div>
        <div class="code">13696/0x3580</div>
    </li>

    <li>
        <i class="x-icon">&#13700</i>
        <div class="name">减</div>
        <div class="code">13700/0x3584</div>
    </li>

    <li>
        <i class="x-icon">&#13701</i>
        <div class="name">加</div>
        <div class="code">13701/0x3585</div>
    </li>

    <li>
        <i class="x-icon">&#13702</i>
        <div class="name">错误</div>
        <div class="code">13702/0x3586</div>
    </li>

    <li>
        <i class="x-icon">&#13703</i>
        <div class="name">正确</div>
        <div class="code">13703/0x3587</div>
    </li>

    <li>
        <i class="x-icon">&#13726</i>
        <div class="name">向右</div>
        <div class="code">13726/0x359e</div>
    </li>

    <li>
        <i class="x-icon">&#13727</i>
        <div class="name">向左</div>
        <div class="code">13727/0x359f</div>
    </li>

    <li>
        <i class="x-icon">&#13728</i>
        <div class="name">向上</div>
        <div class="code">13728/0x35a0</div>
    </li>

    <li>
        <i class="x-icon">&#13729</i>
        <div class="name">向下</div>
        <div class="code">13729/0x35a1</div>
    </li>

    <li>
        <i class="x-icon">&#13734</i>
        <div class="name">加</div>
        <div class="code">13734/0x35a6</div>
    </li>

    <li>
        <i class="x-icon">&#13735</i>
        <div class="name">减</div>
        <div class="code">13735/0x35a7</div>
    </li>

    <li>
        <i class="x-icon">&#13757</i>
        <div class="name">禁止</div>
        <div class="code">13757/0x35bd</div>
    </li>

    <li>
        <i class="x-icon">&#13867</i>
        <div class="name">下拉</div>
        <div class="code">13867/0x362b</div>
    </li>
    
    <li style="clear:both;"></li>      
</ul>
````
<div style="clear:both;"></div>


## 代码
 
一定要添加x-icon: "x", asiicode: 120 ,不然在window xp下用safari会出现蓝屏。

```css
    @font-face {font-family: 'x-icon';
        src: url('x-icon.eot'); /* IE9*/
        src: url('x-icon.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
        url('x-icon.woff') format('woff'), /* chrome、firefox */
        url('x-icon.ttf') format('truetype'), /* chrome、firefox、opera、Safari, Android, iOS 4.2+*/
        url('x-icon.svg#uxx-icon') format('svg'); /* iOS 4.1- */
    }
```

定义使用x-icon的样式
```css
    .x-icon{font-family:"x-icon";font-size:16px;font-style:normal;}
```
挑选相应图标并获取字体编码，应用于页面

```html
<i class="x-icon">&#33</i>;
```

