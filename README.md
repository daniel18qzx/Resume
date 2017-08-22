## 這框架一個字，潮

雖然 Bootstrap 不是唯一有 RWD Grid 的框架，但衝著他近年這麼潮然後 GitHub 上星星這麼多，我一直都很想學起來然後實做一個網頁

## 履歷用網頁編輯，潮

過往我都用 MS Word 來編輯檔案，但每次改一版本就要重新調整版型，太累。如果用 RWD 網頁來做，修完內容稍微整體放大縮小，整個版面都還是會維持的很好，讚讚 而且，別人看你在打原碼改履歷，**靠，整個潮度跟帥度都被你掌握住惹**

## 項目目標
*   熟悉 Bootstrap 的 Grid 框架
*   熟悉 CSS
*   熟悉開發流程
*   [範例](https://danielrapen3184.github.io/Resume/)

## 使用語言

*   HTML
*   CSS

## 我使用的工具

*   Sublime
    *   Auto Close HTML Tags
    *   ColorPick
    *   HTML-CSS-JS Prettify
    *   HTML Attributes
*   Opera
    *   開發人員工具
*   Git
    *   Tower (Mac only)

## 需要能力/材料
### 強烈建議

*   一點點的美感
*   有個人電子照片
*   記得自己過往做過什麼
*   按這篇文章讚

### 有會更好

*   不怕代碼
*   知道 CSS 架構
*   知道 HTML 架構
*   知道 HTML 基本 Label
*   知道 Semantic HTML 概念

## 建議學習步驟

1.  [Open the GitHub repository](https://github.com/danielrapen3184/Resume)
2.  Fork it
3.  Clone it and create a copy on your computer
4.  Get to know the concept of Bootstrap Grid
5.  Modify the HTML file
6.  Add/Remove the snippets (Default: Profile, Education, Work, Project)
7.  Preview
8.  Modify the CSS file

## Page Attributes

### ISO Language Codes

*   English: en
*   Traditional Chinese: zh-Hant
*   Simplified Chinese: zh-Hans
*   Japanese: ja

```html
<div>

    <html lang="zh-Hant-CN">

</div>
```

### Page Title

```html
<div>

    <title>邱子軒 | Daniel Chiu</title>

</div>
```

## Code Snippets

### Profile section

*   Add the info with <p> label and make sure two columns looked balanced

```html
<div>

    <div class="row" title="">
        <div class="col-sm-5 item">
            <p>年　　龄：24岁</p>
            <p>籍　　贯：台湾台北</p>
            <p>现居城市：台湾台北</p>
        </div>
        <div class="col-sm-5 item">
            <p>就读科系：台湾大学MBA</p>
            <p>学　　历：硕　　士</p>
            <p>服役状况：正在服役 (2018年7月退伍)</p>
        </div>
    </div>

</div>
```

*   Change the email and any websites u want to include

```html
<div>

    <div class="row" title="">
        <div class="col-sm-10 item">
            <p>r04741003@ntu.edu.tw</p>
        </div>
    </div>

    <div class="row" title="">
        <div class="col-sm-10 item">
            <!--WEBSITE1-->
            <!--substitute the icon sn @fontawesome.com-->
            <i class="fa fa-linkedin" aria-hidden="true"></i>
            <!--change the site address and the texts u want to show-->
            <a href="https://www.linkedin.com/in/danielchiu15" class="url"> https://www.linkedin.com/in/danielchiu15</a>
            <!--WEBSITE1 END-->
            <br>
            <!--WEBSITE2-->
            <i class="fa fa-github " aria-hidden="true "></i>
            <a href="https://github.com/danielrapen3184" class="url"> https://github.com/danielrapen3184</a>
            <!--WEBSITE2 END-->
        </div>
    </div>

</div>
```
### Education section

*   The default number of Edu exp are 2, if u only want one of them, change the class of `div` into `col-sm-12`, so does the following EDU1 block.

```html
<div>

    <div class="row " title=" ">
        <!--EDU1-->
        <div class="col-sm-6 item ">
            <h3>国立台湾大学－商学研究所</h3>
            <h4><b>2015 Sep - 2017 Jun</b></h4>
            <p><b>主修：</b>战略管理、供应炼管理&nbsp;</p>
            <p><b>优势：</b>量化分析、质化分析、赛局、量化预测、机器学习、统计分析、最佳化管理、管理科学模式、专案管理、品牌管理、Python语言编程等</p>
            <p>
                <br>
            </p>
        </div>
        <!--EDU1 END-->
        <!--EDU2-->
        <div class="col-sm-6 item ">
            <h3>国立台湾大学－机械工程学系</h3>
            <h4><b>2011 Sep - 2015 Jun</b></h4>
            <p><b>主修：</b>自动控制、力学</p>
            <p><b>优势：</b>系统分析、程式设计、经济学、C++ 语言编程等</p>
        </div>
        <!--EDU2 END-->
    </div>

</div>
```

### Work section

*   The code snippets of work section are independent, feel free to add/remove the following code block.

```html
<div>

    <div class="row " title=" ">
        <div class="col-sm-12 item ">
            <h3>买单侠 Omni prime (上海秦苍信息科技有限公司)</h3>
        </div>
        <div class="col-sm-8 item ">
            <p><b>商业分析师 Growth Hacker</b></p>
            <p><b>使用工具：Python, Tableau, SPSS, JMP, SQL, MS PowerPoint, MS Excel</b></p>
        </div>
        <div class="col-sm-4 item ">
            <p class="text-right "><b>2017 Apr - 2017 May　　</b></p>
        </div>
        <div class="col-sm-12 item ">
            <p>▪ 使用神经网络与机器学习等方法改善坏帐之量化预测，显著降低误差率至 3% 以内，提高公司对资金的掌握度</p>
            <p>▪ 制作实时各产品成本结构仪表版，以利追踪与拓展优化利润空间</p>
            <p>▪ 访查一线销售人员、追踪竞品发展，在部门内部开展新项目关注</p>
        </div>
    </div>

</div>
```

### Project section

*   Same as the work section…

```html
<div>

    <div class="row " title=" ">
        <div class="col-sm-12 item ">
            <h3>远距医疗谘商新创团队 Ether</h3>
        </div>
        <div class="col-sm-8 item ">
            <p><b>共同创办人, 市场调研, 战略拟订, 主视觉师</b></p>
            <p><b>使用工具：Sketch, Flinto, MS PowerPoint</b></p>
        </div>
        <div class="col-sm-4 item ">
            <p class="text-right "><b>2016 Feb - 2016 Jul　　</b></p>
        </div>
        <div class="col-sm-12 item ">
            <p>▪ 偕同台大医院医师、机电整合工程师等人创办网路平台</p>
            <p>▪ 接受鸿海集团旗下的生医领域孵化器</p>
            <p>▪ 成功在台湾获得新创比赛冠军，前往新加坡参展</p>
            <p>▪ 自學 APP 建模，並擔任團隊主視覺師，負責 Pitch 簡報與網頁素材</p>
        </div>
    </div>

</div>
```

* * *

### 推薦文章：

> [https://read01.com/DjmNa.html#.WZqfhlmuRPU](https://read01.com/DjmNa.html#.WZqfhlmuRPU) [http://cythilya.blogspot.tw/2015/04/bootstrap-grid-system.html](http://cythilya.blogspot.tw/2015/04/bootstrap-grid-system.html) [http://kimix.name/bootstrap-rwd-使用方法及原理/](http://kimix.name/bootstrap-rwd-%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95%E5%8F%8A%E5%8E%9F%E7%90%86/) [http://www.thewebpractice.com/w3c/Style/Examples/011/firstcss-tr.html](http://www.thewebpractice.com/w3c/Style/Examples/011/firstcss-tr.html) [http://www.wibibi.com/info.php?tid=CSS_Attribute_Selectors_屬性選擇器](http://www.wibibi.com/info.php?tid=CSS_Attribute_Selectors_%E5%B1%AC%E6%80%A7%E9%81%B8%E6%93%87%E5%99%A8) [http://css-teach.7happy.com.tw/css-div.php](http://css-teach.7happy.com.tw/css-div.php) [http://csscoke.com/2015/01/01/rgb-hsl-hex/](http://csscoke.com/2015/01/01/rgb-hsl-hex/)

<script type="text/javascript">var _self="undefined"!=typeof window?window:"undefined"!=typeof WorkerGlobalScope&&self instanceof WorkerGlobalScope?self:{},Prism=function(){var e=/\blang(?:uage)?-(\w+)\b/i,t=0,n=_self.Prism={util:{encode:function(e){return e instanceof a?new a(e.type,n.util.encode(e.content),e.alias):"Array"===n.util.type(e)?e.map(n.util.encode):e.replace(/&/g,"&amp;").replace(/</g,"&lt;").replace(/\u00a0/g," ")},type:function(e){return Object.prototype.toString.call(e).match(/\[object (\w+)\]/)[1]},objId:function(e){return e.__id||Object.defineProperty(e,"__id",{value:++t}),e.__id},clone:function(e){var t=n.util.type(e);switch(t){case"Object":var a={};for(var r in e)e.hasOwnProperty(r)&&(a[r]=n.util.clone(e[r]));return a;case"Array":return e.map&&e.map(function(e){return n.util.clone(e)})}return e}},languages:{extend:function(e,t){var a=n.util.clone(n.languages[e]);for(var r in t)a[r]=t[r];return a},insertBefore:function(e,t,a,r){r=r||n.languages;var l=r[e];if(2==arguments.length){a=arguments[1];for(var i in a)a.hasOwnProperty(i)&&(l[i]=a[i]);return l}var o={};for(var s in l)if(l.hasOwnProperty(s)){if(s==t)for(var i in a)a.hasOwnProperty(i)&&(o[i]=a[i]);o[s]=l[s]}return n.languages.DFS(n.languages,function(t,n){n===r[e]&&t!=e&&(this[t]=o)}),r[e]=o},DFS:function(e,t,a,r){r=r||{};for(var l in e)e.hasOwnProperty(l)&&(t.call(e,l,e[l],a||l),"Object"!==n.util.type(e[l])||r[n.util.objId(e[l])]?"Array"!==n.util.type(e[l])||r[n.util.objId(e[l])]||(r[n.util.objId(e[l])]=!0,n.languages.DFS(e[l],t,l,r)):(r[n.util.objId(e[l])]=!0,n.languages.DFS(e[l],t,null,r)))}},plugins:{},highlightAll:function(e,t){var a={callback:t,selector:'code[class*="language-"], [class*="language-"] code, code[class*="lang-"], [class*="lang-"] code'};n.hooks.run("before-highlightall",a);for(var r,l=a.elements||document.querySelectorAll(a.selector),i=0;r=l[i++];)n.highlightElement(r,e===!0,a.callback)},highlightElement:function(t,a,r){for(var l,i,o=t;o&&!e.test(o.className);)o=o.parentNode;o&&(l=(o.className.match(e)||[,""])[1],i=n.languages[l]),t.className=t.className.replace(e,"").replace(/\s+/g," ")+" language-"+l,o=t.parentNode,/pre/i.test(o.nodeName)&&(o.className=o.className.replace(e,"").replace(/\s+/g," ")+" language-"+l);var s=t.textContent,u={element:t,language:l,grammar:i,code:s};if(!s||!i)return n.hooks.run("complete",u),void 0;if(n.hooks.run("before-highlight",u),a&&_self.Worker){var c=new Worker(n.filename);c.onmessage=function(e){u.highlightedCode=e.data,n.hooks.run("before-insert",u),u.element.innerHTML=u.highlightedCode,r&&r.call(u.element),n.hooks.run("after-highlight",u),n.hooks.run("complete",u)},c.postMessage(JSON.stringify({language:u.language,code:u.code,immediateClose:!0}))}else u.highlightedCode=n.highlight(u.code,u.grammar,u.language),n.hooks.run("before-insert",u),u.element.innerHTML=u.highlightedCode,r&&r.call(t),n.hooks.run("after-highlight",u),n.hooks.run("complete",u)},highlight:function(e,t,r){var l=n.tokenize(e,t);return a.stringify(n.util.encode(l),r)},tokenize:function(e,t){var a=n.Token,r=[e],l=t.rest;if(l){for(var i in l)t[i]=l[i];delete t.rest}e:for(var i in t)if(t.hasOwnProperty(i)&&t[i]){var o=t[i];o="Array"===n.util.type(o)?o:[o];for(var s=0;s<o.length;++s){var u=o[s],c=u.inside,g=!!u.lookbehind,h=!!u.greedy,f=0,d=u.alias;u=u.pattern||u;for(var p=0;p<r.length;p++){var m=r[p];if(r.length>e.length)break e;if(!(m instanceof a)){u.lastIndex=0;var y=u.exec(m),v=1;if(!y&&h&&p!=r.length-1){var b=r[p+1].matchedStr||r[p+1],k=m+b;if(p<r.length-2&&(k+=r[p+2].matchedStr||r[p+2]),u.lastIndex=0,y=u.exec(k),!y)continue;var w=y.index+(g?y[1].length:0);if(w>=m.length)continue;var _=y.index+y[0].length,P=m.length+b.length;if(v=3,P>=_){if(r[p+1].greedy)continue;v=2,k=k.slice(0,P)}m=k}if(y){g&&(f=y[1].length);var w=y.index+f,y=y[0].slice(f),_=w+y.length,S=m.slice(0,w),O=m.slice(_),j=[p,v];S&&j.push(S);var A=new a(i,c?n.tokenize(y,c):y,d,y,h);j.push(A),O&&j.push(O),Array.prototype.splice.apply(r,j)}}}}}return r},hooks:{all:{},add:function(e,t){var a=n.hooks.all;a[e]=a[e]||[],a[e].push(t)},run:function(e,t){var a=n.hooks.all[e];if(a&&a.length)for(var r,l=0;r=a[l++];)r(t)}}},a=n.Token=function(e,t,n,a,r){this.type=e,this.content=t,this.alias=n,this.matchedStr=a||null,this.greedy=!!r};if(a.stringify=function(e,t,r){if("string"==typeof e)return e;if("Array"===n.util.type(e))return e.map(function(n){return a.stringify(n,t,e)}).join("");var l={type:e.type,content:a.stringify(e.content,t,r),tag:"span",classes:["token",e.type],attributes:{},language:t,parent:r};if("comment"==l.type&&(l.attributes.spellcheck="true"),e.alias){var i="Array"===n.util.type(e.alias)?e.alias:[e.alias];Array.prototype.push.apply(l.classes,i)}n.hooks.run("wrap",l);var o="";for(var s in l.attributes)o+=(o?" ":"")+s+'="'+(l.attributes[s]||"")+'"';return"<"+l.tag+' class="'+l.classes.join(" ")+'" '+o+">"+l.content+"</"+l.tag+">"},!_self.document)return _self.addEventListener?(_self.addEventListener("message",function(e){var t=JSON.parse(e.data),a=t.language,r=t.code,l=t.immediateClose;_self.postMessage(n.highlight(r,n.languages[a],a)),l&&_self.close()},!1),_self.Prism):_self.Prism;var r=document.currentScript||[].slice.call(document.getElementsByTagName("script")).pop();return r&&(n.filename=r.src,document.addEventListener&&!r.hasAttribute("data-manual")&&document.addEventListener("DOMContentLoaded",n.highlightAll)),_self.Prism}();"undefined"!=typeof module&&module.exports&&(module.exports=Prism),"undefined"!=typeof global&&(global.Prism=Prism);</script> <script type="text/javascript">Prism.languages.markup={comment:/<!--[\w\W]*?-->/,prolog:/<\?[\w\W]+?\?>/,doctype:/<!DOCTYPE[\w\W]+?>/,cdata:/<!\[CDATA\[[\w\W]*?]]>/i,tag:{pattern:/<\/?(?!\d)[^\s>\/=.$<]+(?:\s+[^\s>\/=]+(?:=(?:("|')(?:\\\1|\\?(?!\1)[\w\W])*\1|[^\s'">=]+))?)*\s*\/?>/i,inside:{tag:{pattern:/^<\/?[^\s>\/]+/i,inside:{punctuation:/^<\/?/,namespace:/^[^\s>\/:]+:/}},"attr-value":{pattern:/=(?:('|")[\w\W]*?(\1)|[^\s>]+)/i,inside:{punctuation:/[=>"']/}},punctuation:/\/?>/,"attr-name":{pattern:/[^\s>\/]+/,inside:{namespace:/^[^\s>\/:]+:/}}}},entity:/&#?[\da-z]{1,8};/i},Prism.hooks.add("wrap",function(a){"entity"===a.type&&(a.attributes.title=a.content.replace(/&amp;/,"&"))}),Prism.languages.xml=Prism.languages.markup,Prism.languages.html=Prism.languages.markup,Prism.languages.mathml=Prism.languages.markup,Prism.languages.svg=Prism.languages.markup;</script> <script type="text/javascript">!function(){"undefined"!=typeof self&&self.Prism&&self.document&&Prism.hooks.add("complete",function(e){if(e.code){var t=e.element.parentNode,s=/\s*\bline-numbers\b\s*/;if(t&&/pre/i.test(t.nodeName)&&(s.test(t.className)||s.test(e.element.className))&&!e.element.querySelector(".line-numbers-rows")){s.test(e.element.className)&&(e.element.className=e.element.className.replace(s,"")),s.test(t.className)||(t.className+=" line-numbers");var n,a=e.code.match(/\n(?!$)/g),l=a?a.length+1:1,m=new Array(l+1);m=m.join("<span></span>"),n=document.createElement("span"),n.className="line-numbers-rows",n.innerHTML=m,t.hasAttribute("data-start")&&(t.style.counterReset="linenumber "+(parseInt(t.getAttribute("data-start"),10)-1)),e.element.appendChild(n)}}})}();</script> <script type="text/x-mathjax-config;executed=true">(function () { MathJax.Hub.Config({ 'showProcessingMessages': false, 'messageStyle': 'none' }); if (typeof MathJaxListener !== 'undefined') { MathJax.Hub.Register.StartupHook('End', function () { MathJaxListener.invokeCallbackForKey_('End'); }); } })();</script> <script>(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){ (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o), m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m) })(window,document,'script','https://www.google-analytics.com/analytics.js','ga'); ga('set', 'userId', {{USER_ID}}); ga('create', 'UA-105000768-1', 'auto'); ga('send', 'pageview');</script>