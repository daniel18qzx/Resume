
# Resume
A simple resume template built based on bootstrap. 

## Page Attributes
### ISO Language Codes
* English: en
* Traditional Chinese: zh-Hant
* Simplified Chinese: zh-Hans
* Japanese: ja

```html start:2
<html lang="zh-Hant-CN">
```


### Page Title
```html
<title>邱子軒 | Daniel Chiu</title>
```

## Code Snippets
### Profile section
* Add the info with **\<p>** label and make sure two columns looked balanced

```html
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
```
* Change the email and any websites u want to include

```html
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
```
### Education section
* The default number of Edu exp are 2, if u only want one of them, change the class of ````div```` into ````col-sm-12````, so does the following EDU1 block.

````html
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
````

### Work section
* The code snippets of work section are independent, feel free to add/remove the following code block.

````html
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
````

### Project section
* Same as the work section...

````html
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
````

