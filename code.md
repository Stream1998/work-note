# Catalogue
<!-- vim-markdown-toc GFM -->

- [Catalogue](#catalogue)
- [javascript](#javascript)
  - [获取当前日期和时间](#获取当前日期和时间)
  - [比较时间](#比较时间)
  - [获取文件后缀](#获取文件后缀)
  - [修改文件路径](#修改文件路径)
  - [避免小数丢失精度](#避免小数丢失精度)
  - [浏览器朗读文字](#浏览器朗读文字)
  - [正则匹配](#正则匹配)
    - [替换字符](#替换字符)
    - [检验字符](#检验字符)
  - [匹配url的参数](#匹配url的参数)
  - [创建文件流](#创建文件流)
  - [接收媒体输入](#接收媒体输入)
  - [数组](#数组)
    - [生成数组](#生成数组)
    - [打乱数组](#打乱数组)
    - [过滤假值](#过滤假值)
    - [数组填充](#数组填充)
    - [统计字母个数](#统计字母个数)
  - [随机生成](#随机生成)
    - [11位字符串](#11位字符串)
    - [颜色](#颜色)
  - [拖动元素](#拖动元素)
  - [拖动加载文件](#拖动加载文件)
  - [清空拖动选择](#清空拖动选择)
  - [文档碎片](#文档碎片)
  - [将HTML字符串转换为DOM节点](#将html字符串转换为dom节点)
  - [屏幕共享 & 视频录制](#屏幕共享--视频录制)
  - [动态添加\<input>后自动聚焦](#动态添加input后自动聚焦)
  - [获取\<select>被选中的选项](#获取select被选中的选项)
  - [阻止\<a>默认跳转](#阻止a默认跳转)
  - [设置 input[checkbox] 选中、取消选中、获取被选中的值、判断是否选中](#设置-inputcheckbox-选中取消选中获取被选中的值判断是否选中)
  - [禁用\<select>](#禁用select)
  - [重置\<select>](#重置select)
  - [清空\<input>选中的文件](#清空input选中的文件)
  - [上传图片](#上传图片)
  - [视频截图](#视频截图)
  - [复制内容到粘贴板](#复制内容到粘贴板)
  - [全屏](#全屏)
  - [退出全屏](#退出全屏)
  - [监听全屏、退出全屏](#监听全屏退出全屏)
  - [监听 localStorage、sessionStorage 事件](#监听-localstoragesessionstorage-事件)
  - [下载文件](#下载文件)
  - [读取文件](#读取文件)
  - [触底加载](#触底加载)
  - [控制输入框输入，光标不移动](#控制输入框输入光标不移动)
  - [防抖](#防抖)
  - [节流](#节流)
  - [生成UUID](#生成uuid)
  - [POST 请求上传文件](#post-请求上传文件)
  - [如何实现页面刷新后不定位到之前的滚动位置？](#如何实现页面刷新后不定位到之前的滚动位置)
  - [参数非空检测](#参数非空检测)
  - [jquery模板语法](#jquery模板语法)
  - [将元素滚动到用户可见](#将元素滚动到用户可见)
  - [表单请求](#表单请求)
  - [数字由逗号分隔](#数字由逗号分隔)
  - [对象数组多字段排序](#对象数组多字段排序)
- [CSS](#css)
  - [排除第一个元素](#排除第一个元素)
  - [iconfont的使用](#iconfont的使用)
  - [nth-child](#nth-child)
    - [奇偶匹配](#奇偶匹配)
    - [根据规则给样式](#根据规则给样式)
  - [间隔排布](#间隔排布)
  - [内投影](#内投影)
  - [自定义图形](#自定义图形)
    - [箭头](#箭头)
    - [圆点](#圆点)
  - [禁止用户选择](#禁止用户选择)
  - [渐变色文本](#渐变色文本)
  - [banner](#banner)
  - [去除\<a>默认样式](#去除a默认样式)
  - [去除[input:password]图标](#去除inputpassword图标)
  - [多行文本省略](#多行文本省略)
  - [文本换行显示](#文本换行显示)
  - [文本不换行](#文本不换行)
  - [给文本添加下划线](#给文本添加下划线)
  - [修改表单元素的占位文本样式](#修改表单元素的占位文本样式)
  - [解决背景图片不全问题](#解决背景图片不全问题)
  - [匹配后代获得焦点](#匹配后代获得焦点)
  - [去除 input[number] 默认的按钮](#去除-inputnumber-默认的按钮)
  - [position：fixed 如何水平垂直居中](#positionfixed-如何水平垂直居中)
  - [定义全局变量](#定义全局变量)
  - [引入文件](#引入文件)
  - [进度条](#进度条)
  - [文本选中样式](#文本选中样式)
  - [图片异常处理](#图片异常处理)
  - [重置表单组件的颜色](#重置表单组件的颜色)
  - [修改\<li>默认项目符号或数字](#修改li默认项目符号或数字)
  - [修改插入光标的颜色](#修改插入光标的颜色)
  - [文字排布方式](#文字排布方式)
  - [自定义滚动条样式](#自定义滚动条样式)
- [VUE](#vue)
  - [初始化 data 中的数据](#初始化-data-中的数据)
  - [模拟点击](#模拟点击)
  - [监听路由变化](#监听路由变化)
  - [返回上一个页面](#返回上一个页面)
  - [路由导航](#路由导航)
  - [单选按钮（选中/取消选中）](#单选按钮选中取消选中)
  - [表单验证](#表单验证)
  - [表单重置](#表单重置)
  - [禁止用户选择过去的时间](#禁止用户选择过去的时间)
  - [阻止路由进入页面](#阻止路由进入页面)
  - [跨源数据传输](#跨源数据传输)
- [HTML](#html)
  - [右键菜单](#右键菜单)
  - [iframe 添加设备权限](#iframe-添加设备权限)
  - [转义字符](#转义字符)
    - [中文空格字符](#中文空格字符)
    - [制表符](#制表符)
  - [增加焦点](#增加焦点)
- [uniapp](#uniapp)
  - [如何关闭顶部导航](#如何关闭顶部导航)
  - [获取路由参数](#获取路由参数)
- [git](#git)
  - [设置代理](#设置代理)
  - [取消代理](#取消代理)
- [echarts](#echarts)
  - [格式化文本](#格式化文本)
  - [富文本](#富文本)
  - [默认标签颜色与数据项颜色保持一致](#默认标签颜色与数据项颜色保持一致)
- [other](#other)
  - [实现前后端跨域请求处理以及携带 Cookie](#实现前后端跨域请求处理以及携带-cookie)

<!-- vim-markdown-toc -->

# javascript

## 获取当前日期和时间

Tags: [Date] [toLocaleDateString] [toLocaleTimeString] [toLocaleString]

```javascript {.line-numbers}
const date = new Date();
const cdate = date.toLocaleDateString('zh-CN').split('/').join('-');
const ctime = date.toLocaleTimeString('zh-CN', {hour12: false});
const cdate_ctime = date.toLocaleString('zh-CN', {hour12: false});
console.log(cdate, ctime, cdate_ctime);
```

## 比较时间

tags: [Date] [string] [toISOString] [localeCompare]

```javascript {.line-numbers}
const date1 = new Date('2021-10-21T07:39:21.176Z').toISOString();
console.log(date1);
const date2 = new Date('2021-10-21T07:39:21.170Z').toISOString();
console.log(date2);
// 字符串比较
const result = date1.localeCompare(date2);
console.log(result);
```

## 获取文件后缀

tags: [string] [subString] [lastIndexOf]

```javaScript {.line-numbers}
const filePath = "xxx.png";
console.log(filePath.substring(filePath.lastIndexOf('.') + 1))
```

## 修改文件路径

tags: [string] [lastIndexOf] [subString] [slice]

```javascript {.line-numbers}
const filePath = 'xxx.jpg';
const pos = filePath.lastIndexOf('.');
const res = filePath.substring(0, pos) + '-thumb' + filePath.slice(pos);
console.log(res);
```

## 避免小数丢失精度

tags: [IEEE754]

[来源](https://zhuanlan.zhihu.com/p/100353781)

```javaScript {.line-numbers}
const add = (num1, num2) => {
    const num1Digits = (num1.toString().split('.')[1] || '').length;
    const num2Digits = (num2.toString().split('.')[1] || '').length;
    const baseNum = Math.pow(10, Math.max(num1Digits, num2Digits));
    return (num1 * baseNum + num2 * baseNum) / baseNum;
}
```

## 浏览器朗读文字

tags: [WebAPI] [speechSynthesis]

[来源](https://zhuanlan.zhihu.com/p/141582231)

```javascript {.line-numbers}
function speak(sentence) {
    const utterance = new SpeechSynthesisUtterance(sentence)
    window.speechSynthesis.speak(utterance)
}
// test
speak('hello world');
```

## 正则匹配

tags: [regex]

### 替换字符

```javascript {.line-numbers}
const reg =/[^\u4E00-\u9FA5A-Za-z]/g;
const text = "asldfj123林@@#";
console.log(text.replace(reg, ''));
```

### 检验字符

```javascript {.line-numbers}
const reg =/[^\u4E00-\u9FA5A-Za-z]/g;
const text = "asldfj123林@@#";
console.log(reg.test(e));
```

## 匹配url的参数

tags: [URLSearchParams] [array] [split] [Regex]

使用 [URLSearchParams](https://developer.mozilla.org/zh-CN/docs/Web/API/URLSearchParams)

```javascript {.line-numbers}
const url = "xxx"
// const search = window.location.search;
const search = url.split('?')[1];
const params = new URLSearchParams(search);
// 查询参数对应的值
const appid = params.get('appid');
console.log(params);
// url参数转对象
const obj = Object.fromEntries(params);
console.log(obj);
```

使用正则表达式、split...

```javascript {.line-numbers}
const url = "xxx"
const reg = /([?&][^?&]+)=([^?&]+)/g;
const params = (url.match(reg) || []).reduce((acc, cur) => {
    const [key, value] = cur.slice(1).split('=');
    acc[key] = value;
    return acc; 
},{});
console.log(params.appid);
```

## 创建文件流

tags: [File]

```javascript {.line-numbers}
const file = new File(["foo"], "foo.txt", { type: "text/plain", });
```

## 接收媒体输入

tags: [getUserMedia]

[getUserMedia - mdn](https://developer.mozilla.org/zh-CN/docs/Web/API/MediaDevices/getUserMedia)

```javascript {.line-numbers}
navigator.mediaDevices.getUserMedia(constraints)
    .then(function(stream) {
        /* 使用这个stream stream */
    })
    .catch(function(err) {
        /* 处理error */
    });
```

## 数组

### 生成数组

tags: [array] [from]

```javascript
const arr = Array.from({length: 16}, (v, i) => {return {}});
```

### 打乱数组

tags: [array] [Math] [random]

```javascript {.line-numbers}
// 不完全乱序
const arr = [1, 2, 3, 4, 5]
const result = arr.sort(_ => Math.random() - 0.5)
console.log(result)
// Fisher-Yates shuffle 
for (let i = 1; i < arr.length; i++) {
    const random = Math.floor(Math.random() * (i + 1));
    const temp = arr[i];
    arr[i] = arr[random];
    arr[random] = temp;
}
console.log(arr)
```

### 过滤假值

tags: [array] [filter]

```javascript {.line-numbers}
const arr = [1,2,3];
arr.lenth = 100;
console.log(arr);
const ans = arr.filter(v => Boolean);
console.log(ans);
```

### 数组填充

tags: [array] [fill]

```javascript {.line-numbers}
const array = [1,2,3];
const zeroArray = new Array(3).fill(0);
const newArray = [...array, ...zeroArray];
console.log(newArray);
```

### 统计字母个数

tags: [ES6] [array] [reduce]

```javascript {.line-numbers}
const data = ['a','a','b','a','c','b','d','b','c','b','c'];
const result = data.reduce((acc, v) => (acc[v] = (acc[v] || 0 ) + 1, acc),{});
console.log(result);
```

### 对象数组多字段排序

tags: [array] [sort]

```js
const personList = [
  { name:'Sandra Clark', age:10, id:2001 },
  { name:'George Williams', age:10, id:2010 },
  { name:'Jeffrey Williams', age:24, id:2008 },
  { name:'James Jones', age:10, id:2008 },
  { name:'Linda Martin', age:10, id:2001 },
  { name:'Linda Williams', age:24, id:2000 },
  { name:'Joseph Lee', age:26, id:20015 },
  { name:'Daniel Rodriguez', age:10, id:2001 },
  { name:'James Taylor', age:10, id:2000 },
]
// 先按 age 排序，age 相同再按 id 排序，id 相同则再按 name 排序
personList.sort((m,n) => {
    if (a.age !== b.age) return a.age - b.age
    else if (a.id !== b.id) return a.id - b.id
    else if (a.name !== b.name) return a.name.localeCompare(b.name) 
});
console.log(personList);
```

## 随机生成

tags: [Math] [random]

### 11位字符串

```javascript {.line-numbers}
console.log(Math.random().toString(36).substring(2))
```

### 颜色

```javascript {.line-numbers}
const randomColor = `#${Math.floor(Math.random() * 0xffffff).toString(16).padEnd(6, '0')}`
console.log(randomColor)
```

## 拖动元素

tags: [drag] [drop]

[参考](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API)

```html {.line-numbers}
<div draggable="true" ondragstart="dragElement(data)"></div>
<!-- define drop zone -->
<div ondragover="overElement()" ondrop="dropElement()"></div>
```

```javascript {.line-numbers}
// 开始拖动. 存储信息
function dragElement(data){
    // define drag's data
    event.dataTransfer.setData('data', data);
}
// 悬浮到可放置区域
function overElement(){
    event.preventDefault();
    event.dataTransfer.dropEffect = "move";
}
// 结束拖动，接收信息
function dropElement(){
    event.preventDefault();
    const data = event.dataTransfer.getData("data");
    const target = event.target;
    // do something
}
```

## 拖动加载文件

tags:[event] [drag] [drop] [FileReader]

```javascript {.line-numbers}
dropzone.addEventListener('dragover', (e) => {
    e.dataTransfer.dropEffect = 'copy' ; 
    e.preventDefault();
    e.stopPropagation();
})
dropzone.addEventListener('drop',(e) => {
    e.preventDefault();
    e.stopPropagation();
    const files = e.dataTransfer.files;
    const reader = new FileReader();
    reader.readAsText(files[0], 'utf-8');
    reader.onload = async function(e) {
        const result = e.target.result;
        // do something
    }
})
```

## 清空拖动选择

tags: [getSelection]

```javascript {.line-numbers}
// onmousemove
removeSelection(){
    window.getSelection ? window.getSelection().removeAllRanges() : document.selection.empty();
}
```

## 文档碎片

tags: [createDocumentFragment]

```javascript {.line-numbers}
const ul = document.getElementById("ul");
const fragment = document.createDocumentFragment();
for (let i = 0; i < 20; i++) {
    let li = document.createElement("li");
    li.innerHTML = "index: " + i;
    fragment.appendChild(li);
}
ul.appendChild(fragment);
```

## 将HTML字符串转换为DOM节点

tsgs: [innerHTML] [DOMParser] [createContextualFragment]

[将HTML字符转换为DOM节点并动态添加到文档中](https://www.cnblogs.com/xuanhun/p/9499348.html)

```javascript
// 1. innerHTML
node.innerHTML = template;
// 2. DOMParser
const node = let doc = new DOMParser().parseFromString(template, 'text/html');
// 3. DocumentFragment
const node = document.createRange().createContextualFragment(template);
```

## 屏幕共享 & 视频录制

tags: [WebAPI] [getDisplayMedia] [MediaRecorder]

[来源](https://segmentfault.com/a/1190000040026747)

```javascript {.line-numbers}
const player = document.querySelector('#player');
const start = document.querySelector('#start');
const stop = document.querySelector('#stop');
const download = document.querySelector('#download');

let recorder;
let captureStream;
const displayMediaOptions = {
    video: {
        cursor: "never",
        displaySurface:"window"
    },
    audio: true
}

const startCapture = async () => {
    try {
        captureStream = await navigator.mediaDevices.getDisplayMedia(displayMediaOptions);
    } catch (err) {
        console.log('Error: ' + err);
        return alert('capture is error or cancel!');
    }
    window.URL.revokeObjectURL(player.src);
    player.srcObject = captureStream;
    recorder = new MediaRecorder(captureStream);
    recorder.start();
}
const stopCapture = () => {
    let tracks = player.srcObject.getTracks();
    tracks.forEach(track => {
        track.stop();
    });
    recorder.stop();
    recorder.addEventListener('dataavailable',(event)=>{
        let videoUrl = URL.createObjectURL(event.data,{type:'video/mp4'});
        player.srcObject = null;
        player.src = videoUrl;
    })

}
const downloadVideo = () => {
    const name = new Date().toISOString().slice(0,19).replace('T',' ').replace(' ','_').replace(/:/g,'-');
    const a = document.createElement('a');
    a.href = player.src;
    a.download = `${name}.mp4`;
    document.body.appendChild(a);
    a.click();

}

start.addEventListener('click', (e) => startCapture(), false);
stop.addEventListener('click', (e) => stopCapture(), false);
download.addEventListener('click', (e) => downloadVideo(), false);
```

## 动态添加\<input>后自动聚焦

tags: [jquery] [focus]

```javascript {.line-numbers}
const input = `<input type="text">`
$("#btn").before(input);
$("#btn").prev().focus();
```

## 获取\<select>被选中的选项

tags: [jquery] [select] [option]

```javascript {.line-numbers}
const value = $('#select option:selected').val();
console.log(value);
```

## 阻止\<a>默认跳转

tags: [a] [href]

方法1

```html {.line-numbers}
<a href="javascript:;">jump</a>
```

方法2

```javascript {.line-numbers}
const links = document.querySelectorAll('a');
Array.form(links).map(v => {v.onlink = () => {return false}})
```

## 设置 input[checkbox] 选中、取消选中、获取被选中的值、判断是否选中

tags: [jquery] [checkbox]

[参考](https://blog.csdn.net/chenchunlin526/article/details/77448168)

```javascript {.line-numbers}
// 选中
$("input[type='checkbox']").prop('checked', true);
// 取消选中
$("input[type='checkbox']").prop('checked', false);
// 获取被选中的值
$("input:checkbox:checked").val();
// 判断是否选中
$("input[type='checkbox']").prop('checked');
```

## 禁用\<select>

tags: [select]

方法1

```html
<select style="pointer-events:none;"></select>
```

方法2

```html
<select onfocus="this.defaultIndex=this.selectedIndex" onchange="this.defaultIndex=this.selectedIndex"></select>
```

方法3

```html
<select disabled></select>
```

## 重置\<select>

tags: [jquery] [select]

```javascript
$("#select option:first").prop("selected", 'selected');
```

## 清空\<input>选中的文件

tags: [jquery] [input:file]

```javascript
$('input[type=file]').val('');
```

## 上传图片

tags: [jquery] [input:file] [formData]

```html {.line-numbers}
<div class="micro-image-list"></div>
<div 
    class="micro-upload-image" 
    onclick="uploadImage(this)"
>
    <input 
        type="file"
        accept=".png,.jpg" 
        style="display: none;" 
        multiple 
        onchange="changeImage(this)"
    >
    上传图片
</div>
```

```javascript {.line-numbers}
const uploadImage = (el) => {
    const uploader = el.querySelector("input[type='file']");
    return uploader.click();
}
function changeImage(el){
    const files = el.files;
    // 图片列表
    const imageList = $(el).parent().prev();
    // 上传限制
    // const length = imageList.children().length;
    // if(length > 6){
    //     console.log('图片不能超过6张！');
    //     alert('图片不能超过6张！');
    //     return;
    // }
    // const types = ['image/png', 'image/jpeg'];
    // if(!types.includes(files[0].type)){
    //     console.log('文件类型错误！');
    //     alert('文件类型错误！');
    //     return;
    // }
    // if(files[0].size > 1024){
    //     console.log('图片大小不能超过1M！');
    //     alert('图片大小不能超过1M！');
    //     return;
    // }

    // 添加图片
    const src = window.URL.createObjectURL(files[0]);
    const template = `
        <div class="image-item">
            <img src="${src}" alt="">
        </div>
    `;
    // 提交表单
    const formData = new FormData();
    formData.append('files', files[0]);
    $.ajax({
        url:'/upload/',
        dataType:'json',
        type:'POST',
        async: false,
        data: formData,
        processData : false, // 使数据不做处理
        contentType : false, // 不要设置Content-Type请求头
        success: function(data){
            console.log(data);
        },
        error:function(response){
            console.log(response);
        }
    });
    imageList.append(template);
    // 清空当前选择的文件
    $(el).val('');
}
```

## 视频截图

tags: [canvas] [screenshot]

工具：html2Canvas

```html {.line-numbers}
<video src=""></video>
<!-- 如果视频跨域，导致canvas无法截图，使用crossorigin属性 -->
<video src="" crossorigin="anonymous"></video>
```

```javascript {.line-numbers}
function screenshot(){
    const video = document.querySelector('video');
    const ctx = document.createElement('canvas');
    ctx.width = video.videoWidth;
    ctx.height = video.videoHeight;
    ctx.getContext('2d').drawImage(video, 0, 0, ctx.width, ctx.height);
    ctx.toBlob((blob) => {
        const url = URL.createObjectURL(blob);
        // console.log(url);
        const link = document.createElement('a');
        link.href = url;
        link.download = `视频截图_${new Date().getTime()}`;
        link.click();
        link.remove();
    })
}
```

## 复制内容到粘贴板

tags: [copy]

```html
<input type="text" id="copy-text-store" class="copy-text-store">
```

```css {.line-numbers}
.copy-text-store{
    /* 设置成 hidden 或者是 none 都不能使用 select 方法 */
    opacity: 0;
    height: 1px;
    cursor: default;
}
```

```javascript {.line-numbers}
function copyLink() {
    const input = document.querySelector('#copy-text-store')
    const copyText = `复制的内容`;
    input.value = copyText;
    input.select();
    document.execCommand('copy');
    input.value = '';
}
```

## 全屏

tags: [fullscreen]

```javascript {.line-numbers}
function fullScreen(el) {
    let rfs = el.requestFullScreen || el.webkitRequestFullScreen || el.mozRequestFullScreen || el.msRequestFullScreen,
        wscript;
    if(typeof rfs != "undefined" && rfs) {
        rfs.call(el);
        return;
    }
    if(typeof window.ActiveXObject != "undefined") {
        wscript = new ActiveXObject("WScript.Shell");
        if(wscript) {
            wscript.SendKeys("{F11}");
        }
    }
}
```

## 退出全屏

tags: [cancelFullScreen]

```javascript {.line-numbers}
function exitFullScreen() {
    if (document.cancelFullScreen) {
        document.cancelFullScreen()
    } else if (document.webkitCancelFullScreen) {
        document.webkitCancelFullScreen()
    } else if (document.mozCacelFullScreen) {
        document.mozCacelFullScreen()
    } else if (document.msCanclFullScreen) {
        document.msCanclFullScreen()
    } else if (document.oCancelFullScreen) {
        document.oCancelFullScreen()
    }
    if (typeof window.ActiveXObject != "undefined") {
        let wscript = new ActiveXObject("WScript.Shell");
        if (wscript != null) {
            wscript.SendKeys("{F11}");
        }
    }
}
```

## 监听全屏、退出全屏

tags: [fullscreen]

```javascript {.line-numbers}
function onfullscreenHandle(){
    const target = event.target;
    // do something
}
document.onfullscreenchange = (event) => {
    onfullscreenHandle(event);
}
document.onwebkitfullscreenchange = (event) => {
    onfullscreenHandle(event);
}
document.onmozfullscreenchange = (event) => {
    onfullscreenHandle(event);
}
document.onmsfullscreenchange = (event) => {
    onfullscreenHandle(event);
}
```

## 监听 localStorage、sessionStorage 事件

tags: [event] [storage]

注意：storage 事件有一个很特别的地方，就是它不在导致数据变化的当前页面触发，而是在同一个域名的其他窗口触发。通过这种机制，实现多个窗口之间的通信。

```javaScript
const count = ref(localStorage.getItem('count') || 0);
window.addEventListener('storage', (e) => {
    console.log(e);
    if(e.key === 'count'){
        count.value = Number(e.newValue);
    }
})
```

## 下载文件

tags: [download]

[参考](https://blog.csdn.net/weixin_42981560/article/details/115507234)

```javascript {.line-numbers}
function downloadFile(blob){
    const a = document.createElement('a');
    const url = URL.createObjectURL(blob);
    a.href = url;
    a.download = new Date().getTime() + '.wav'; // filename
    a.click();
    a.remove();
    URL.revokeObjectURL(url);
}
```

## 读取文件

tags: [ajax]

```html
<script>
  const readFile = path => {
    return new Promise((resolve, reject) => {
      const xhr = new XMLHttpRequest();
      xhr.open('get', path);
      xhr.onreadystatechange = () => {
        if(xhr.readyState === 4){
          if(xhr.status === 200){
            resolve(xhr.responseText);
          }
          reject('Request bad!');
        }
      }
      xhr.onerror = () => {
        reject(new Error('An error occured during the transcation'));
      }
      xhr.send();
    })
  }
  readFile('./index.json').then(res => {
    console.log(res);
  }).catch(err => {
    console.error(err);
  })
</script>
```

## 触底加载

tags: [jquery] [scroll]

```javascript {.line-numbers}
$('#id').on('scroll', (e) => {
    const scrollHeight = e.target.scrollHeight;
    const scrollTop = e.target.scrollTop;
    const clientHeight = e.target.clientHeight
    // console.log(scrollHeight, scrollTop, clientHeight);
    const isBottom = scrollHeight - scrollTop <= clientHeight;
    isBottom && loadData();
});
function loadData(){
    alert('加载数据');
}
```

## 控制输入框输入，光标不移动

tags: [input] [setSelectionRange]

[setSelectionRange - mdn](https://developer.mozilla.org/zh-CN/docs/Web/API/HTMLInputElement/setSelectionRange)

```javascript {.line-numbers}
const input = document.querySelector('input');
input.addEventListener('input', (e) => {
    const value = e.target.value;
    const regex = /[^.1-9]/g;
    // 获取第一个不合法的输入位置
    const pos = value.search(regex);
    const res = value.replace(regex, "");
    e.target.value = res;
    // 如果 pos != -1 就将光标定位到该位置
    ~pos && e.target.setSelectionRange(pos,pos);
})
```

## 防抖

tags: [interview] [debounce]

```javascript {.line-numbers}
// 在一段时间结束后, 执行
const debounce = (fn, delay) => {
    let timers = null;
    return () => {
        const context = this;
        const args = arguments;
        if(timers) {
            clearTimeout(timers);
        }
        timers = setTimeout(() => {
            fn.apply(context, args);
        }, delay)
    }
}
```

## 节流

tags: [interview] [throttle]

```javascript {.line-numbers}
// 在一段时间内只执行一次
const throttle = (fn, delay) => {
    let timers = null;
    return () => {
        const context = this;
        const args = arguments;
        timers = setTimeout(() => {
            timers = null;
            fn.apply(context, args);
        })
    } 
}
```

## 生成UUID

tags: [uuid]

```javascript {.line-numbers}
const createUuid = () => {
    return "xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx".replace(/[xy]/g, (c) => {
        const r = (Math.random() * 16) | 0;
        const v = c === "x" ? r : (r & 0x3) | 0x8;
        return v.toString(16);
    });
}
const uuid = createUuid();
console.log(uuid);
```

## POST 请求上传文件

tags: [post] [upload]

multipart/form-data;boundary=xxx
boundary会自动生成，所以不要手动添加 Content-Type, 保留 headers 参数

```javascript
const formData = new FormData();
formData.append('file', files[0])
fetch(url , {
  method:'POST',
  headers:{},
  body: formData,
}).then(res => {
  console.log(res);
})
```

## 如何实现页面刷新后不定位到之前的滚动位置？

tags: [scroll]

```javascript
if (history.scrollRestoration) {
    history.scrollRestoration = 'manual';
} 
```

## 参数非空检测

tags: [function] [params]

```javascript
const isRequired = () => { throw new Error('param is required'); };

const hello = (name = isRequired()) => { console.log(`hello ${name}`) };
// 抛出一个错误，因为参数没有传
hello();
// 没有问题
hello('hello');
```

## jquery模板语法

tags: [jquery] [jquery-tmpl]

[text/x-jquery-tmpl 使用记录](https://blog.csdn.net/weixin_43549578/article/details/103933408)

```code
// 获取值
${}
// 遍历
{{each}}
// 判断
{{if}}, {{else}}
// 输出变量
{{html}}
// 嵌套模板
{{tmpl}} 
```

## 将元素滚动到用户可见

tags: [scroll] [scrollIntoView]

[mdn - scrollIntoView](https://developer.mozilla.org/zh-CN/docs/Web/API/Element/scrollIntoView)
[张鑫旭 - CSS scroll-behavior和JS scrollIntoView让页面滚动平滑](https://www.zhangxinxu.com/wordpress/2018/10/scroll-behavior-scrollintoview-%e5%b9%b3%e6%bb%91%e6%bb%9a%e5%8a%a8/)

scrollIntoView() 方法会滚动元素的父容器，使被调用 scrollIntoView() 的元素对用户可见。

```html
<style>
    div{
        height: 2000px;
        overflow-y: auto;
    }
</style>
</head>
<body>
    <div>
        <button>点我</button>
    </div>
    <p>流汗黄豆 &#x1F605; </p>
    <script>
        const p = document.querySelector('p');
        const btn = document.querySelector('button');
        btn.addEventListener('click', () => {
            p.scrollIntoView({
                behavior: 'smooth'
            })
        })
        p.addEventListener('click', () => {
            btn.scrollIntoView({
                behavior: 'smooth'
            })
        })
    </script>
</body>

```

## 表单请求

tags: [post] [axios]

application/x-www-form-urlencoded

```javascript
// 原生 URLSearchParams
const stringify = (data) => {
    const params = new URLSearchParams();
    for(const [key,value] of Object.entries(data)) {
        params.append(key, value);
    }
    return params;
}

// 或者使用 Qs 模块
import qs from 'Qs'
let data = {"code":"1234","name":"yyyy"};
const formData = qs.stringify(data);
```

## 数字由逗号分隔

tags: [number] [ES5]

```js
const num = 1119.721;
const res = num.toLocaleString();
console.log(res);
```

[Back Top](#catalogue)

---

# CSS

## 排除第一个元素

tags: [pseudo-class] [:first-of-type]

```css {.line-numbers}
.title:not(:first-of-type){
   // some code
}
```

## iconfont的使用

tags: [iconfont]

```html
<i class="iconfont 图标类名"></i>
```

## nth-child

tags: [pseudo-class] [:nth-child]

### 奇偶匹配

[来源](http://www.internetzg.com/view_news.asp?id=578)

```css {.line-numbers}
:nth-child(odd){}
:nth-child(even){}
```

### 根据规则给样式

```css
.className:nth-child(3n+2){
    margin:0 16upx;
}
```

## 间隔排布

tags: [flex] [flex-wrap] [gap]

```css {.line-numbers}
.item-list{
    display: flex;
    width: 320px;
    flex-wrap: wrap;
    gap: 10px;
}
.item{
    width: 100px;
    height: 100px;
}
```

## 内投影

tags: [box-shadow] [inset]

```css
box-shadow: inset 0 10px 7px 0 rgba(72, 97, 123, 0.7);
```

## 自定义图形

tags: [pesudo-element] [::before]

### 箭头

```css {.line-numbers}
.className::before {
    content: "";
    position: absolute;
    border: 2px solid blue;
    border-left: 0;
    border-top: 0;
    width: 10px;
    height: 10px;
    transform: rotate(-45deg);
    left: 5px;
    top: 8px;
}
```

### 圆点

```css {.line-numbers}
.className::before {
    content: "";
    border: 5px solid red;
    border-radius: 50%;
    position: absolute;
    left: 8px;
    top: 13px;
}
```

## 禁止用户选择

tags: [user-select]

```css {.line-numbers}
.remove-select {
    -moz-user-select:none;
    -webkit-user-select:none;
    -ms-user-select:none;
    -khtml-user-select:none;
    user-select:none;
}
```

## 渐变色文本

tags: [linear-gradient] [-webkit-background-clip] [-webkit-text-fill-color]
注意：background必须放在前面

```css {.line-numbers}
background: linear-gradient(0deg, #29e2ee 0%, #29bcee 100%);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
```

## banner

tags: [skew] [background-image] [linear-gradient]

```css {.line-numbers}
.mask-group{
    position: absolute;
    left: 0;
    top: 0;
    height: 530px;
    width: 100%;
    transform: skewY(-5deg);
    background-image: linear-gradient(-20deg, #248EE0 0%, #0A1EAE 100%);
}
.mask {
    position: absolute;
    height: 180px;
}
.mask-0 {
    bottom: 0;
    left: 0;
    width: 30%;
    background-image: linear-gradient(120deg, #3DB4DB 0%, #58A3F6 102%);
}
.mask-1 {
    bottom: 180px;
    right: 0;
    width: 36%;
    background-image: linear-gradient(120deg, #1D59C4 0%, #204EC2 100%);
}
.mask-2 {
    bottom: 500px;
    left: 0;
    width: 100%;
    height: 240px;
    background-image: linear-gradient(120deg, #25B5DF 0%, #267AD4 100%);
}
```

## 去除\<a>默认样式

tags: [text-decoration]

```css {.line-numbers}
a, 
/*正常的未被访问过的链接*/
a:link, 
/*已经访问过的链接*/
a:visited,
/*鼠标划过(停留)的链接*/
a:hover,
/* 正在点击的链接*/
a:active{
    text-decoration: none;
}
```

## 去除[input:password]图标

tags: [input:password] [icon]

```css
input[type="password" i]::-ms-reveal {
    display: none !important;
}
```

## 多行文本省略

tags: [text-overflow] [white-space]

```css {.line-numbers}
.className {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}
```

## 文本换行显示

tags: [word-break]

```css {.line-numbers}
.className{
    word-break: break-all;
}
```

## 文本不换行

tags: [whtie-space]

```css {.line-numbers}
.className{
    white-space: nowrap;
}
```

## 给文本添加下划线

tags: [text-decoration]

```css {.line-numbers}
.className{
    text-decoration: underline;
}
```

## 修改表单元素的占位文本样式

tags: [pesudo-element] [::placeholder]

```css {.line-numbers}
.className::placeholder{
    color: #B8CAE6;
    font-size: 16px;
}
```

## 解决背景图片不全问题

tags: [background] [background-size]

```css {.line-numbers}
.className{
    background: url('xxx.png') no-repeat;
    background-size: 100% 100%;
}
```

## 匹配后代获得焦点

tags: [pesudo-class] [:focus-within]

[mdn - :focus-within](https://developer.mozilla.org/zh-CN/docs/Web/CSS/:focus-within)

```css {.line-numbers}
.father:focus-within{
    border-color: red;
}
.father > input{
    background: blue;
}
```

## 去除 input[number] 默认的按钮

tags: [pesudo-element] [::webkit-inner-spin-button]

```css {.line-numbers}
.input[type="number"]::-webkit-inner-spin-button{
    display:none;
}
```

## position：fixed 如何水平垂直居中

tags: [fixed]

```css {.line-numbers}
/* 宽度确定 */
.className{
    width: 8rem;
    height: 8rem;
    position: fixed;
    left: 0;
    right: 0;
    margin: 0 auto;
}
/* 宽度不确定 */
.className{
    position: fixed;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    z-index: 1000;
}
```

## 定义全局变量

tags:[pseudo-class] [:root]

```css {.line-numbers}
:root {
  --main-color: hotpink;
  --pane-padding: 5px 42px;
}
```

## 引入文件

tags:[import]

```css
import url('./style.css');
/* or */
import "./style.css";
```

## 进度条

tags: [input:range] [pseudo-element] [::webkit-slider-thumb] [::webkit-slider-runnable-track]

```html
<input 
    type="range"
    min="0" 
    max="100" 
    value="50"
    oninput="changeVolume(this)"
>
```

```css
input[type="range"]{
    -webkit-appearance: none; /*去除默认样式*/
    width: 100%;
    height: 2px;
    background: #BDBEC7;
    border-radius: 4px;
    margin: 8px 0;
    cursor: pointer;
}
input[type='range']::-webkit-slider-thumb{
    -webkit-appearance: none;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    margin-top: -3px;
    background: #21AAFF;
}
input[type='range']::-webkit-slider-runnable-track{
    -webkit-appearance: none;
    background: -webkit-linear-gradient(top, #21AAFF, #21AAFF) 
                0% 0% / var(--cur, 0%) 100% 
                no-repeat;
    height: 2px;
}
```

```javascript
function changeVolume(el){
    el.style.setProperty('--cur', el.value + '%');
}
```

## 文本选中样式

tags: [pseudo-element] [::selection]

```css {.line-numbers}
::selection,
::-moz-selection,
::-webkit-selection { 
    color: #c80000;
}
```

## 图片异常处理

tags: [img] [pseudo-element] [::before] [::after] [onerror]

[前端小智-稀土掘金](https://juejin.cn/post/7062860159286149127)

```html
<img src="xxx.jpg" alt='fireworks picture' onerror="this.classList.add('error');">
```

```css
img.error {
    content: '';
    display: inline-block;
    transform: scale(1);
    color: transparent;
}
img.error::before {
    content: '';
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background: #f5f5f5 url('error.png') no-repeat center / 100% 100%;
}
/* 优化使用alt说明图片含义 */
img.error::after {
    content: attr(alt);
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    line-height: 2;
    background-color: rgba(0, 0, 0, .5);
    color: white;
    font-size: 12px;
    text-align: center;
    // 文本省略
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}
```

## 重置表单组件的颜色

tags: [property] [accent-color]

可以在不改变浏览器默认表单组件基本样式的前提下重置表单组件的颜色。

```html
<!-- 目前仅支持以下表单标签 -->
<input type="checkbox">
<input type="radio">
<input type="range">
<progress>
```

## 修改\<li>默认项目符号或数字

tags: [pseudo-element] [::marker]

[mdn - ::marker](https://developer.mozilla.org/zh-CN/docs/Web/CSS/::marker)

它作用在任何设置了display: list-item的元素或伪元素上

```css
ul li::marker {
  color: red;
  font-size: 1.5em;
}
```

## 修改插入光标的颜色

tags: [property] [caret-color]

[mdn - caret-color](https://developer.mozilla.org/zh-CN/docs/Web/CSS/caret-color)

用来定义插入光标（caret）的颜色

## 文字排布方式

tags: [property] [writing-mode]

[layui表格反转的一个简单实现方式](https://www.php.cn/layui/436365.html)
[mdn - writing-mode](https://developer.mozilla.org/zh-CN/docs/Web/CSS/writing-mode)
指定块流动方向，即块级容器堆叠的方向，以及行内内容在块级容器中的流动方向

## 自定义滚动条样式

tags: [pseudo-element] [::-webkit-scrollbar-*]

[关于滚动条样式](https://juejin.cn/post/6997011443967066143)

- ::-webkit-scrollbar：
  - 用于设置滚动条的整体样式
  - 在这里设置宽高，以控制滚动条尺寸，且必须要设置宽高，否则不生效
  - 宽高分别对应 y轴 和 x轴 的滚动条尺寸
  - 若宽高为0，则可隐藏滚动条，但仍可保持滚动
- ::-webkit-scrollbar-track：
  - 滚动条轨道
  - 不设置则不出现轨道
- ::-webkit-scrollbar-track-piece：
  - 没有滑块的滚动条轨道，或者说是内层轨道
  - 同滚动条轨道，
- ::-webkit-scrollbar-thumb：
  - 滚动条滑块，即滚动条滚动的部分
  - 必须要设置，否则不会出现滑块
- ::-webkit-scrollbar-button：
  - 滚动条两端的箭头按钮
  - 不设置则不出现
- ::-webkit-scrollbar-corner：
  - X轴滚动条和Y轴滚动条的交接处
  - 不设置，默认为白色小方块，宽高随X轴和Y轴滚动条尺寸

```css
.container::-webkit-scrollbar{
    width: 10px;
    height: 100%;
    border-radius: 5px;
}
.container::-webkit-scrollbar-track{
    background: transparent;
    border-radius: 5px;
}
.container::-webkit-scrollbar-thumb{
    background: #0E226A;
    border-radius: 5px;
}
```

[Back Top](#catalogue)

---

# VUE

## 初始化 data 中的数据

tags: [vue2]

```javascript {.line-numbers}
Object.assign(this.$data, this.$options.data());
```

## 模拟点击

tags: [vue2]

```vue {.line-numbers}
<template>
    <button ref="initButton" @click="init"></button>
</template>
<script>
export default {
    mounted(){
        this.$refs.initButton.$el.click();
    }
}
</script>
```

## 监听路由变化

tags: [vue2] [vue router]

```vue {.line-numbers}
// some code
<script>
export default {
    watch:{
        $route(to, from){
            console.log(to, from);
        }
    }
}
</script>
// some code
```

## 返回上一个页面

tags: [vue2] [vue router]

```vue {.line-numbers}
// some code
<script>
export default {
    methods:{
        navigateBack(){
            this.$router.go(-1);
        }
    }
}
</script>
// some code
```

## 路由导航

tags: [vue2] [vue router]

[来源](https://router.vuejs.org/zh/api/#router-link-props)

```html {.line-numbers}
// to - 目标路由
// tag - 生成标签
// active-class - 触发后的样式
// exact - 精准模式，只有当前路由与目标路由完全一致才触发。
<ul>
    <router-link to="/realtime" tag="li" active-class="header-nav-active" exact>实时监控</router-link>
    <router-link to="/review" tag="li" active-class="header-nav-active" exact>视频回看</router-link>
    <router-link to="/call" tag="li" active-class="header-nav-active" exact>可视通话</router-link>
</ul>
```

## 单选按钮（选中/取消选中）

tags: [vue2] [elementUI]

```vue {.line-numbers}
<template>
    <!-- some code -->
    <el-radio v-model="radio" label="1" @click.native.prevent="radioChange"></el-radio>
    <!-- some code -->
</template>
<script>
export default {
    data(){
        return {
            radio: '', // 默认未选中
        }
    },
    methods:{
        radioChange(){
            this.radio = this.radio === '1' ? '' : '1';
        }
    }
}
</script>

<style>
// 隐藏label
/deep/ .el-radio__label{
    display: none;
}
</style>
```

## 表单验证

tags: [vue2] [elementUI]

```javascript {.line-numbers}
this.$refs[formName].validate( valid => {
    if(valid){
        // some code
    }
    else return false;
})
```

## 表单重置

tags: [vue2] [elementUI]

```javascript {.line-numbers}
this.$refs[formName].resetFields();
```

## 禁止用户选择过去的时间

tags: [vue2] [elementUI]

```vue
<template>
    <div>
        <el-date-picker
            type="date"
            :picker-options="pickerOptions"
        >
        </el-date-picker>
    </div>
</template>

<script>
    export default {
        data(){
            return {
                pickerOptions:{
                    disabledDate(time) {
                        return time.getTime() < Date.now() - 8.64e7;
                    }
                },
            }
        }
    }
</script>
```

## 阻止路由进入页面

tags: [vue2] [vue router]

```javascript
router.beforeEach((route, redirect, next) => {
    if (route.path === '/login' || localStorage.accessToken) {
        next();
    } else {
        localStorage.clear();
        next('/login')
    }
});
```

## 跨源数据传输

tags: [vue2] [postMessage]

[来源](https://segmentfault.com/a/1190000014882611)
[postMessage](https://developer.mozilla.org/zh-CN/docs/Web/API/Window/postMessage)

```javascript
// 父窗口 http://domain1
created(){
    window.addEventListener('message', (e) => {
        console.log(e.data);
    }, false)
}
methods:{
    send(){
        this.$refs['iframe'].contentWindow.postMessage(message, 'http://domain1')
    }
}
// 子窗口 http://domain2
created(){
    window.addEventListener('message', (e) => {
        console.log(e.data);
        // 注意 webpack 也有数据传输 筛选
    }, false)
}
methods:{
    send(){
        // parent or top, but window don't work.
        top.postMessage(message, 'http://domain1')
    }
}
```

[Back Top](#catalogue)

---

# HTML

## 右键菜单

tags: [event] [contextmenu]

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body, 
        .context-menu ul{
            margin: 0;
            padding: 0;
        }
        .bg{
            width: 300px;
            height: 300px;
            background-color: rgb(95, 230, 220);
            display: inline-flex;
            justify-content: center;
            align-items: center;
            user-select: none;
            cursor: default;
        }
        .context-menu{
            background: rgba(255,255,255);
            border: 1px solid gray;
        }
        .context-menu ul li{
            list-style: none;
            cursor: pointer;
            padding: 6px 10px;
            user-select: none;
        }
        .context-menu ul li + li{
            border-top: 1px solid gray;
        }
    </style>
</head>
<body>
    <div class="bg">
        <span>右键显示自定义菜单</span>
    </div>
    <div class="context-menu" style="display: none;">
        <ul>
            <li data-id="1">menu 1</li>
            <li data-id="2">menu 2</li>
            <li data-id="3">menu 3</li>
        </ul>
    </div>
    <script>
        const bg = document.querySelector('.bg');
        const menu = document.querySelector('.context-menu');
        // 监听右键菜单事件
        bg.addEventListener('contextmenu', (e) => {
            e.preventDefault();
            menu.style = `
                display: block;
                position: fixed;
                left: ${e.pageX}px;
                top: ${e.pageY}px;
                z-index: 20220118;
            `;
            document.addEventListener('click', cancelMenu);
        })
        // 阻止菜单上的默认右键菜单事件
        menu.addEventListener('contextmenu', (e) => {
            e.preventDefault();
            return;
        })
        // 菜单点击事件
        menu.addEventListener('click', (e) => {
            e.stopPropagation();
            console.log(e.target.dataset.id);
            hideMenu();
        })
        // 隐藏菜单
        const hideMenu = () => {
            menu.style = 'display:none;'
        }
        // 取消菜单
        const cancelMenu = () => {
            hideMenu();
            document.removeEventListener('click', cancelMenu);
        };
    </script> 
</body>
</html>
```

## iframe 添加设备权限

tags: [iframe] [allow]

```html
<iframe 
    src="" 
    frameborder="0" 
    width="800" 
    height="600" 
    allow="microphone;camera;midi;encrypted-media;"
></iframe>
```

## 转义字符

tags: [escape]

### 中文空格字符

[参考](https://www.cnblogs.com/chenshihaook/p/6186343.html)

`&emsp;`

### 制表符

`&#9;`, 只能在`<pre></pre>`中使用。

## 增加焦点

tags: [tabindex] [pseudo-class] [:focus]

由于div等元素无法接受键盘或其他用户事件，即不支持:focus伪类，可通过增加tabIndex属性使其支持:focus

```html
<div tabindex="1"></div>
```

```css
div:focus{
  // some code 
}
```

[Back Top](#catalogue)

---

# uniapp

## 如何关闭顶部导航

tags: [titleView]

```json
// 关闭全局顶部导航
"globalStyle": {
    //...
    "app-plus":{
        "titleView":false
    }
}
// 关闭单个页面的顶部导航
"style": {
    //...
    "app-plus":{
        "titleNView":false
    }
}
```

## 获取路由参数

tags: [onLoad] [routes]

1.onLoad

```javascript
    onLoad(options){
        const {xxx} = options;
        console.log(options);
    }
```

2.getCurrentPage

```javascript
    getOptions(){
        let routes = getCurrentPages();
        console.log(routes);
        let options = routes[routes.length - 1].options;
        return options;
    },
```

[Back Top](#catalogue)

---

# git

## 设置代理

tags: [proxy]

```shell
git config --global http.proxy http://127.0.0.1:7890
git config --global https.proxy https://127.0.0.1:7890
```

## 取消代理

tags: [proxy]

```shell
git config --global --unset http.proxy
git config --global --unset https.proxy
```

[Back Top](#catalogue)

---

# echarts

[echarts.apache.org](https://echarts.apache.org/zh/option.html#title)

## 格式化文本

tags: [label] [text]

```js
option:{
    label:{
        formatter: '{a} <br/>{b} : {c} ({d}%)'
    }
}
```

## 富文本

tags: [label] [text] [rich]

```js
option:{
    label:{
        formatter: '{name|{b}}\n{d}%',
        rich: {
            name: {
                color: '#fff',
                fontSize: 20,
                padding: [0, 0, 10, 0]
            }
        }
    }
}
```

## 默认标签颜色与数据项颜色保持一致

tags: [label] [color]

```js
option:{
    label:{ 
        color: 'inherit'
    }
}
```

# other

## 实现前后端跨域请求处理以及携带 Cookie

tags: [cross-domain] [cookie] [cors]

- 前端

```javascript
// ajax
$.ajax({
    //...
    crossDomain: true, 
    xhrFields: {
        withCredentials: true
    }
    //...
})
// axios
axios({
    //...
    withCredentials: true
    //...
})

```

- 后端

```javascript
// koa.js
app.use(cors({
    //...
    credentials: true,
}))
// 或者 配置响应头
Access-Control-Allow-Origin: '*',
Access-Control-Allow-Credentials：true,
```

[Back Top](#catalogue)
