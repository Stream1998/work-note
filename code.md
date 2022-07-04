
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
  - [替换字符](#替换字符)
  - [检验字符](#检验字符)
  - [匹配url的参数](#匹配url的参数)
  - [创建文件流](#创建文件流)
  - [统计字母个数](#统计字母个数)
  - [接收媒体输入](#接收媒体输入)
  - [打乱数组](#打乱数组)
  - [随机生成11位字符串](#随机生成11位字符串)
  - [随机颜色](#随机颜色)
  - [拖动元素](#拖动元素)
  - [拖动加载文件](#拖动加载文件)
  - [清空拖动选择](#清空拖动选择)
  - [过滤假值](#过滤假值)
  - [文档碎片](#文档碎片)
  - [将HTML字符串转换为DOM节点](#将html字符串转换为dom节点)
  - [数组填充](#数组填充)
  - [屏幕共享 & 视频录制](#屏幕共享--视频录制)
  - [动态添加input后自动聚焦](#动态添加input后自动聚焦)
  - [获取 selected option](#获取-selected-option)
  - [阻止a标签默认跳转](#阻止a标签默认跳转)
  - [设置checkbox选中、取消选中、获取被选中的值、判断是否选中等](#设置checkbox选中取消选中获取被选中的值判断是否选中等)
  - [禁用select下拉框](#禁用select下拉框)
  - [重置select](#重置select)
  - [清空input选中的文件](#清空input选中的文件)
  - [上传图片](#上传图片)
  - [视频截图](#视频截图)
  - [复制内容到粘贴板](#复制内容到粘贴板)
  - [全屏](#全屏)
  - [退出全屏](#退出全屏)
  - [监听全屏、退出全屏](#监听全屏退出全屏)
  - [监听 localStorage、sessionStorage 事件](#监听-localstoragesessionstorage-事件)
  - [生成数组](#生成数组)
  - [下载文件](#下载文件)
  - [触底加载](#触底加载)
  - [控制输入框输入，光标不移动](#控制输入框输入光标不移动)
  - [防抖 debounce](#防抖-debounce)
  - [节流 throttle](#节流-throttle)
  - [生成UUID](#生成uuid)
  - [POST 请求上传文件](#post-请求上传文件)
  - [如何实现页面刷新后不定位到之前的滚动位置？](#如何实现页面刷新后不定位到之前的滚动位置)
  - [参数非空检测](#参数非空检测)
  - [text/x-jquery-tmpl 使用记录](#textx-jquery-tmpl-使用记录)
  - [将元素滚动到](#将元素滚动到)
- [CSS](#css)
  - [排除第一个元素](#排除第一个元素)
  - [iconfont的使用](#iconfont的使用)
  - [nth-child奇偶匹配](#nth-child奇偶匹配)
  - [nth-child根据规则给样式](#nth-child根据规则给样式)
  - [间隔排布](#间隔排布)
  - [box-shadow阴影](#box-shadow阴影)
  - [自定义箭头](#自定义箭头)
  - [自定义圆点](#自定义圆点)
  - [阻止鼠标选择文字](#阻止鼠标选择文字)
  - [渐变色](#渐变色)
  - [去除滚动条(不够优雅)](#去除滚动条不够优雅)
  - [banner](#banner)
  - [a标签去除默认样式](#a标签去除默认样式)
  - [多行文本省略](#多行文本省略)
  - [文本换行显示](#文本换行显示)
  - [文本不换行](#文本不换行)
  - [给文本添加下划线](#给文本添加下划线)
  - [::placeholder](#placeholder)
  - [背景图片不全](#背景图片不全)
  - [匹配后代获得焦点](#匹配后代获得焦点)
  - [去除 input-number 默认的按钮](#去除-input-number-默认的按钮)
  - [position：fixed 如何水平垂直居中](#positionfixed-如何水平垂直居中)
  - [定义全局变量](#定义全局变量)
  - [引入文件](#引入文件)
  - [进度条](#进度条)
  - [文本选中样式](#文本选中样式)
  - [图片异常处理](#图片异常处理)
  - [accent-color](#accent-color)
  - [::marker](#marker)
  - [caret-color](#caret-color)
  - [writing-mode](#writing-mode)
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
  - [读取文件](#读取文件)
  - [中文空格字符](#中文空格字符)
  - [制表符的转义字符](#制表符的转义字符)
  - [增加焦点](#增加焦点)
- [uniapp](#uniapp)
  - [如何关闭顶部导航](#如何关闭顶部导航)
  - [获取路由参数](#获取路由参数)
- [git](#git)
  - [设置代理](#设置代理)
  - [取消代理](#取消代理)
- [other](#other)
  - [实现前后端跨域请求处理以及携带 Cookie](#实现前后端跨域请求处理以及携带-cookie)

<!-- vim-markdown-toc -->

# javascript

## 获取当前日期和时间

tags: [ toLocaleDateString ] [ toLocaleTimeString ] [ toLocaleString ]

```javascript {.line-numbers}
const date = new Date();
const cdate = date.toLocaleDateString('zh-CN').split('/').join('-');
const ctime = date.toLocaleTimeString('zh-CN', {hour12: false});
const cdate_ctime = date.toLocaleString('zh-CN', {hour12: false});
console.log(cdate, ctime, cdate_ctime);
```

## 比较时间

tags: [ toISOString ] [ localeCompare ]

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

tags: [ subString ] [ lastIndexOf ]

```javaScript {.line-numbers}
const filePath = "企业微信截图_5225fd8a-ee70-4ed1-b267-c46dcdf637ca.png";
console.log(filePath.substring(filePath.lastIndexOf('.') + 1))
```

## 修改文件路径

tags: [ lastIndexOf ] [ subString ] [ slice ]

```javascript {.line-numbers}
const filePath = '/profile/upload//2021/11/04/90d39148662760c2619c4b741ba6ea7a.jpg';
const pos = filePath.lastIndexOf('.');
const res = filePath.substring(0, pos) + '-thumb' + filePath.slice(pos);
console.log(res);
```

## 避免小数丢失精度

tags: [ IEEE754 ]

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

tags: [ WebAPI ] [ speechSynthesis ]

[来源](https://zhuanlan.zhihu.com/p/141582231)

```javascript {.line-numbers}
function speak(sentence) {
    const utterance = new SpeechSynthesisUtterance(sentence)
    window.speechSynthesis.speak(utterance)
}
// test
speak('hello world');
```

## 替换字符

tags: [ Regex ]

```javascript {.line-numbers}
const reg =/[^\u4E00-\u9FA5A-Za-z]/g;
const text = "asldfj123林@@#";
console.log(text.replace(reg, ''));
```

## 检验字符

tags: [ Regex ]

```javascript {.line-numbers}
const reg =/[^\u4E00-\u9FA5A-Za-z]/g;
const text = "asldfj123林@@#";
console.log(reg.test(e));
```

## 匹配url的参数

tags: [ URLSearchParams ] [ split ] [ Regex ]

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

tags: [ File ]

```javascript {.line-numbers}
const file = new File(["foo"], "foo.txt", { type: "text/plain", });
```

## 统计字母个数

tags: [ ES6 ] [ reduce ]

```javascript {.line-numbers}
const data = ['a','a','b','a','c','b','d','b','c','b','c'];
const result = data.reduce((acc, v) => (acc[v] = (acc[v] || 0 ) + 1, acc),{});
console.log(result);
```

## 接收媒体输入

tags: [ Media ]

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

## 打乱数组

tags: [ Random ]

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

## 随机生成11位字符串

tags: [ Random ]

```javascript {.line-numbers}
console.log(Math.random().toString(36).substring(2))
```

## 随机颜色

tags: [ Random ]

```javascript {.line-numbers}
const randomColor = `#${Math.floor(Math.random() * 0xffffff).toString(16).padEnd(6, '0')}`
console.log(randomColor)
```

## 拖动元素

tags: [ Drag & Drop ]

[参考](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API)

```html {.line-numbers}
<div draggable="true" ondragstart="dragElement(event, data)"></div>
<!-- define drop zone -->
<div ondragover="overElement(event)" ondrop="dropElement(event)"></div>
```

```javascript {.line-numbers}
// 开始拖动. 存储信息
function dragElement(event, data){
    // define drag's data
    event.dataTransfer.setData('data', data);
}
// 悬浮到可放置区域
function overElement(event){
    event.preventDefault();
    event.dataTransfer.dropEffect = "move";
}
// 结束拖动，接收信息
function dropElement(event){
    event.preventDefault();
    const data = event.dataTransfer.getData("data");
    const target = event.target;
    // do something
}
```

## 拖动加载文件

tags: [ Drag & Drop ] [ FileReader ]

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

tags: [ JavaScript ]

```javascript {.line-numbers}
// onmousemove
removeSelection(){
    window.getSelection ? window.getSelection().removeAllRanges() : document.selection.empty();
}
```

## 过滤假值

tags: [ JavaScript ]

```javascript {.line-numbers}
const arr = [1,2,3];
arr.lenth = 100;
console.log(arr);
const ans = arr.filter(v => Boolean);
console.log(ans);
```

## 文档碎片

tags: [ createDocumentFragment ]

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

tsgs: [ HTMLElement ]

[将HTML字符转换为DOM节点并动态添加到文档中](https://www.cnblogs.com/xuanhun/p/9499348.html)

```javascript
// 1. innerHTML
node.innerHTML = template;
// 2. DOMParser
const node = let doc = new DOMParser().parseFromString(template, 'text/html');
// 3. DocumentFragment
const node = document.createRange().createContextualFragment(template);
```

## 数组填充

tags: [ Array ] [ fill ]

```javascript {.line-numbers}
const array = [1,2,3];
const zeroArray = new Array(3).fill(0);
const newArray = [...array, ...zeroArray];
console.log(newArray);
```

## 屏幕共享 & 视频录制

tags: [ WebAPI ] [ getDisplayMedia ] [ MediaRecorder ]

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

## 动态添加input后自动聚焦

tags: [ jquery ] [ focus ]

```javascript {.line-numbers}
const input = `<input type="text">`
$("#btn").before(input);
$("#btn").prev().focus();
```

## 获取 selected option

tags: [ jquery ] [ select ] [ option ]

```javascript {.line-numbers}
const value = $('#select option:selected').val();
console.log(value);
```

## 阻止a标签默认跳转

tags: [ a ] [ href ]

方法1

```html {.line-numbers}
<a href="javascript:;">jump</a>
```

方法2

```javascript {.line-numbers}
const links = document.querySelectorAll('a');
Array.form(links).map(v => {v.onlink = () => {return false}})
```

## 设置checkbox选中、取消选中、获取被选中的值、判断是否选中等

tags: [ jquery ] [ checkbox ]

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

## 禁用select下拉框

tags: [ select ]

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

## 重置select

tags: [ jquery ] [ select ]

```javascript
$("#select option:first").prop("selected", 'selected');
```

## 清空input选中的文件

tags:  [ jquery ] [ input ] [ file ]

```javascript
$('input[type=file]').val('');
```

## 上传图片

tags: [ Javascript ] [ jquery ] [ HTML ]

```html {.line-numbers}
<div class="image-list"></div>
<div 
    class="upload-image" 
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

tags: [ Javascript ] [ canvas ]

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

tags: [ Javascript ]

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

tags: [ Javascript ]

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

tags: [ Javascript ]

```javascript {.line-numbers}
function exitFullScreen() {
    if (document.cancleFullScreen) {
        document.cancleFullScreen()
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

tags: [ Javascript ]

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

tags: [ event ] [ storage ]

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

## 生成数组

tags: [ Javascript ]

```javascript
const arr = Array.from({length: 16}, (v, i) => {return {}});
```

## 下载文件

tags: [ Javascript ]

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

## 触底加载

tags: [ jquery ] [ Scroll ]

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

tags: [Input] [ Javascript ]

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

## 防抖 debounce

tags: [interview]

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

## 节流 throttle

tags: [interview]

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

tags: [javascript]

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

tags: [post] [上传文件]

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

tags: [function]

```javascript
const isRequired = () => { throw new Error('param is required'); };

const hello = (name = isRequired()) => { console.log(`hello ${name}`) };
// 抛出一个错误，因为参数没有传
hello();
// 没有问题
hello('hello');
```

## text/x-jquery-tmpl

tags: [jquery]

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

## 将元素滚动到

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
        <button>滚到底部</button>
    </div>
    <p>回到顶部</p>
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

[Back Top](#catalogue)

---

# CSS

## 排除第一个元素

tags: [ CSS ] [ 伪类 ]

```css {.line-numbers}
.title:not(:first-of-type){
   // some code
}
```

## iconfont的使用

tags: [ CSS ]

```html
<i class="iconfont 图标类名"></i>
```

## nth-child奇偶匹配

tags: [ CSS ]

[来源](http://www.internetzg.com/view_news.asp?id=578)

```css {.line-numbers}
:nth-child(odd){}
:nth-child(even){}
```

## nth-child根据规则给样式

tags: [ CSS ] [ 伪类 ]

```css
.className:nth-child(3n+2){
    margin:0 16upx;
}
```

## 间隔排布

tags: [ CSS ]

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

## box-shadow阴影

tags: [ CSS ]

```css
box-shadow: inset 0 10px 7px 0 rgba(72, 97, 123, 0.7);
```

## 自定义箭头

tags: [ CSS ]

```css {.line-numbers}
.className {
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

## 自定义圆点

tags: [ CSS ]

```css {.line-numbers}
.className {
    content: "";
    border: 5px solid red;
    border-radius: 50%;
    position: absolute;
    left: 8px;
    top: 13px;
}
```

## 阻止鼠标选择文字

tags: [ CSS ]

```css {.line-numbers}
.remove-select {
    -moz-user-select:none;
    -webkit-user-select:none;
    -ms-user-select:none;
    -khtml-user-select:none;
    user-select:none;
}
```

## 渐变色

tags: [ CSS ]

注意：background必须放在前面

```css {.line-numbers}
background: linear-gradient(0deg, #29e2ee 0%, #29bcee 100%);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
```

## 去除滚动条(不够优雅)

tags: [ CSS ]

```css {.line-numbers}
body {
    overflow: hidden;
}
```

## banner

tags: [ CSS ] [skew]

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

## a标签去除默认样式

tags: [ CSS ]

```css {.line-numbers}
 /*包含以下四种的链接*/
a {
    text-decoration: none;
}
/*正常的未被访问过的链接*/
a:link {
    text-decoration: none;
}
/*已经访问过的链接*/
a:visited {
    text-decoration: none;
}
/*鼠标划过(停留)的链接*/
a:hover {
    text-decoration: none;
}
/* 正在点击的链接*/
a:active {
    text-decoration: none;
}
```

## 多行文本省略

tags: [ CSS ]

```css {.line-numbers}
.className {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}
```

## 文本换行显示

tags: [ CSS ]

```css {.line-numbers}
.className{
    word-break: break-all;
}
```

## 文本不换行

tags: [ CSS ]

```css {.line-numbers}
.className{
    white-space: nowrap;
}
```

## 给文本添加下划线

tags: [ CSS ]

```css {.line-numbers}
.className{
    text-decoration: underline;
}
```

## ::placeholder

tags: [ CSS ] [ 伪元素 ]

修改表单元素的占位文本样式

```css {.line-numbers}
.className::placeholder{
    color: #B8CAE6;
    font-size: 16px;
}
```

## 背景图片不全

tags: [ CSS ]

```css {.line-numbers}
.className{
    background: url('../../assets/image/videoCall/card-bg.png') no-repeat;
    background-size: 100% 100%;
}
```

## 匹配后代获得焦点

tags: [ CSS ]

[参考](https://developer.mozilla.org/zh-CN/docs/Web/CSS/:focus-within)

```css {.line-numbers}
.father:focus-within{
    border-color: red;
}
.father > input{
    background: blue;
}
```

## 去除 input-number 默认的按钮

tags: [ CSS ] [ 伪类 ]

```css {.line-numbers}
.input[type="number"]::-webkit-inner-spin-button{
    display:none;
}
```

## position：fixed 如何水平垂直居中

tags: [ CSS ]

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

tags:[ CSS ]

```css {.line-numbers}
:root {
  --main-color: hotpink;
  --pane-padding: 5px 42px;
}
```

## 引入文件

tags:[ CSS ]

```css
import url('./style.css');
/* or */
import "./style.css";
```

## 进度条

tags: [ CSS ] [ input:range ]

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

tags: [ CSS ] [ 伪类 ]

```css {.line-numbers}
::selection,
::-moz-selection,
::-webkit-selection { 
    color: #c80000;
}
```

## 图片异常处理

tags: [ CSS ]

[前端小智-稀土掘金](https://juejin.cn/post/7062860159286149127)

```html
<img src="https://miro.medium.com/xxx.jpg" alt='fireworks picture' onerror="this.classList.add('error');">
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
    background: #f5f5f5 url('https://cdn-images-1.medium.com/max/1600/1*we8wfyztsdo12e2Cww6oVA.jpeg') no-repeat center / 100% 100%;
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

## accent-color

tags: [ CSS ]

可以在不改变浏览器默认表单组件基本样式的前提下重置表单组件的颜色。

```html
<!-- 目前仅支持以下表单标签 -->
<input type=”checkbox”>
<input type=”radio”>
<input type=”range”>
<progress>
```

## ::marker

tags: [ CSS ] [ 伪元素 ]

[mdn - ::marker](https://developer.mozilla.org/zh-CN/docs/Web/CSS/::marker)

它作用在任何设置了display: list-item的元素或伪元素上

```css
ul li::marker {
  color: red;
  font-size: 1.5em;
}
```

## caret-color

tags: [ CSS ]

[mdn - caret-color](https://developer.mozilla.org/zh-CN/docs/Web/CSS/caret-color)

用来定义插入光标（caret）的颜色

## writing-mode

tags: [ CSS ]

[layui表格反转的一个简单实现方式](https://www.php.cn/layui/436365.html)
[mdn - writing-mode](https://developer.mozilla.org/zh-CN/docs/Web/CSS/writing-mode)
指定块流动方向，即块级容器堆叠的方向，以及行内内容在块级容器中的流动方向

[Back Top](#catalogue)

---

# VUE

## 初始化 data 中的数据

tags: [ Vue ]

```javascript {.line-numbers}
Object.assign(this.$data, this.$options.data());
```

## 模拟点击

tags: [ Vue ]

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

tags: [ Vue ] [ Vue Router ]

```vue {.line-numbers}
<script>
export default {
    watch:{
        $route(to, from){
            console.log(to, from);
        }
    }
}
</script>
```

## 返回上一个页面

tags: [ Vue ] [ Vue Router ]

```vue {.line-numbers}
<script>
export default {
    methods:{
        navigateBack(){
            this.$router.go(-1);
        }
    }
}
</script>
```

## 路由导航

tags: [ Vue ] [ Vue Router ]

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

tags: [ Vue ] [ ElementUI ]

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

tags: [ Vue ] [ ElementUI ]

```javascript {.line-numbers}
this.$refs[formName].validate( valid => {
    if(valid){
        // some code
    }
    else return false;
})
```

## 表单重置

tags: [ Vue ] [ ElementUI ]

```javascript {.line-numbers}
this.$refs[formName].resetFields();
```

## 禁止用户选择过去的时间

tags: [ Vue ] [ Element UI ]

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

tags: [ Vue ] [ Vue Router ]

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

tags: [ vue ] [ JavaScript ]

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

tags: [ HTML ] [ Event ]

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

tags: [ HTML ]

```html
<iframe src="" frameborder="0" width="800" height="600" allow="microphone;camera;midi;encrypted-media;"></iframe>
```

## 读取文件

tags: [ HTML ] [ Javascript ] [ AJAX ]

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

## 中文空格字符

tags: [ HTML ] [ 转义字符 ]

[参考](https://www.cnblogs.com/chenshihaook/p/6186343.html)

`&emsp;`

## 制表符的转义字符

tags: [ HTML ] [ 转义字符 ]

`&#9;`, 只能在`<pre></pre>`中使用。

## 增加焦点

tags: [ HTML ] [ :focus ]

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

tags: [ uniapp ]

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

tags: [ uniapp ]

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

tags: [ proxy ]

```shell
git config --global http.proxy http://127.0.0.1:7890
git config --global https.proxy https://127.0.0.1:7890
```

## 取消代理

tags: [ proxy ]

```shell
git config --global --unset http.proxy
git config --global --unset https.proxy
```

[Back Top](#catalogue)

---

# other

## 实现前后端跨域请求处理以及携带 Cookie

tags: [ 跨域 ] [ Cookie ] [  CORS ]

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
