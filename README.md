<h1>myQuestions</h1>
<h2>There is no such thing as a dumb question</h2>

<h3>2018/4/7</h3>
<p>
    Q: 在vue文件中想使用嵌套的语法来写css样式，在美团实习的时候项目用的postcss，所以自己考虑是不是要加上postcss-loader?
</p>
<p>
    A: vue-cli生成的项目中默认使用了....只需要在vue组件中的样式标签加上lang="postcss"，之前使用想使用嵌套语法没用是因为没加对应的插件...项目使用了postcss-loader，在.postcssrc.js里用加上想用的加上要用的插件就好了。比如postcss-nested插件提供嵌套语法
</p>

<h3>2018/4/8</h3>
<p>
    Q:executed context, lexical enviroment,this in JavaScript
</p>
<p>
    //TODO:
    A: executed context是规范中定义的一种服务(device)，用来追踪和评估代码的执行
</p>

<p>
    Q:async & await 已及他们和generator有什么关系？
</p>
<p>
    A: async function定义一个函数，返回值是一个Promise，如果函数正常返回，状态为resolved，报错的话为rejected。在async funtion中可以使用await关键字，这个关键字可以暂停当前函数的执行，交出控制权，去执行其他代码，等待一个异步操作（Promise）。当异步操作完成时，继续执行函数。
//TODO:
</p>

<h3>2018/4/9</h3>
<p>Q: HTML5 drag and drop</p>
//TODO:

<h3>2018/04/11</h3>
<p>Q: vue SSR是什么?为了解决什么问题出现的?</p>
//TODO:

<h3>2018/4/13</h3>
<p>Q: png图片和jpg图片不同之处在哪里?</p>
//TODO:

<h3>2018/4/23</h3>
<p>Q: 什么是generator,为什么会出现？</p>
//TODO:

<h3>2018/4/24</h3>
<p>Q：innerHTML vs appChild</p>
//TODO:


<h3>2018/6/12</h3>
<p>Q: vue组件中的scope属性是干什么的?如何理解?</p>
//TODO:

<h3>2018/6/26</h3>
<p>Q: less vs sass vs postcss</p>
//TODO:

<h3>2018/6/29</h3>
<p>Q: 什么是gulp?</p>
//TODO:

<h3>2018/7/8</h3>
<p>Q: yarn vs npm</p>
//TODO:

<h3>2018/7/9</h3>
<p>Q: 自执行函数</p>
//TODO:

<p>Q: "="操作的返回值</p>
//TODO:

<h3>2018/7/11</h3>
<p>Q: new操作返回值</p>
A: 构造函数 return语句返回值作为这个new表达式的返回值，没有手动声明return语句的话，new操作中新建的对象将作为返回值

<p>Q: ||操作返回值</p>
<p>
    A:
    expr1 || expr2
    Returns expr1 if it can be converted to true; otherwise, returns expr2. Thus, when used with Boolean values, || returns true if either operand is true.
</p>

<h3>2018/7/12</h3>
<p>
    Q:使用es6 class关键字继承时，如果要重写constructor，为什么一定要调用super(super到底是啥)
</p>
//TODO:


<h3>2018/7/15</h3>
<p>Q: XSS(cross site script) cross site含义</p>
//TODO:

<h3>2018/7/17</h3>
<p>Q: npx</p>
//TODO::

<p>Q: webpack-dev-server</p>
//TODO:

<h3>2018/7/18</h3>
<p>Q: Web Api</p>
// TODO:

<p>Q:`\u001b[1m\u001b[31mBoston Celtics\u001b[39m\u001b[22m`为毛红色?</p>
// TODO:


<p>Q: websocket</p>
//TODO:

<h3>2018/08/19</h3>
<p>Q: js中[]的具体用法，比如以下这种是什么操作?</p>
<code>
//conn是connection的回调传过来的参数<br>
this.sockWrite([conn], 'error', 'Invalid Host header');
</code>

<h3>2018/09/01</h3>
<p>为啥npm i @vue/cli -g后，会有一个可执行的命令，换句话说，怎么样才能构建自己的类似vue-cli的脚手架工具?</p>
// TODO:

<h3>2018/09/02</h3> 
<p>Q: webpack  assetsPublicPath</p>

<h3>2018/10/30</h3>
<p>宏任务和微任务?</p>
<p>A:目前的理解是js里面有两个任务队列,eventloop在取执行的任务时,微任务队列的优先级高于宏任务,会往微任务队列里面添加事件的有promise, jsdom事件.往宏任务队列里添加事件的有setTimeout, setInterval等</p>
