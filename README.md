# poptip

---

气泡提示组件样式，支持各个方向的箭头，带透明边框，黄白蓝三种色调。

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/poptip.css">

<style>
.nico-insert-code {
    overflow: hidden;
    height: 80px;
}
.ui-poptip {
    position: absolute;
}
</style>

### 标准提示框

````html
<div class="ui-poptip">
    <div class="ui-poptip-shadow">
        <div class="ui-poptip-container">
            <div class="ui-poptip-arrow ui-poptip-arrow-10">
                <em></em>
                <span></span>
            </div>
            <a href="javascript:;" class="ui-poptip-close">×</a>
            <div class="ui-poptip-content">
                我是内容我是内容我是内容我是内容我是内容我是内容
            </div>
        </div>
    </div>
</div>
````

### 内容复杂些

````html
<div class="ui-poptip">
    <div class="ui-poptip-shadow">
        <div class="ui-poptip-container">
            <div class="ui-poptip-arrow ui-poptip-arrow-10">
                <em></em>
                <span></span>
            </div>
            <a href="javascript:;" class="ui-poptip-close">×</a>
            <div class="ui-poptip-content">
                <div>我是内容。</div>
                <div>我是内容我是内容我是内容。</div>
                <div>
                    <a href="https://app.alipay.com/xxxx" target="_blank">现在使用</a>
                </div>
            </div>
        </div>
    </div>
</div>
````

### 没有关闭按钮

````html
<div class="ui-poptip">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">
        <div class="ui-poptip-arrow ui-poptip-arrow-10">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">
            我是内容我是内容我是内容我是内容我是内容我是内容
        </div>
    </div>
    </div>
</div>
````

### 两点钟位置箭头

````html
<div class="ui-poptip">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">
        <div class="ui-poptip-arrow ui-poptip-arrow-2">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">
            我是内容我是内容我是内容我是内容我是内容我是内容
        </div>
    </div>
    </div>
</div>
````

### 11点钟位置

````html
<div class="ui-poptip">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">        
        <div class="ui-poptip-arrow ui-poptip-arrow-11">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">
            我是内容我是内容我是内容我是内容我是内容我是内容
        </div>
    </div>
    </div>
</div>
````

### 1点钟位置

````html
<div class="ui-poptip">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">        
        <div class="ui-poptip-arrow ui-poptip-arrow-1">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">
            我是内容我是内容我是内容我是内容我是内容我是内容
        </div>
    </div>
    </div>
</div>
````

### 5点钟位置

````html
<div class="ui-poptip">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">        
        <div class="ui-poptip-arrow ui-poptip-arrow-5">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">
            我是内容我是内容我是内容我是内容我是内容我是内容
        </div>
    </div>
    </div>
</div>
````

### 7点钟位置

````html
<div class="ui-poptip">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">        
        <div class="ui-poptip-arrow ui-poptip-arrow-7">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">
            我是内容我是内容我是内容我是内容我是内容我是内容
        </div>
    </div>
    </div>
</div>
````

### 蓝色提示框

````html
<div class="ui-poptip ui-poptip-blue">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">        
        <div class="ui-poptip-arrow ui-poptip-arrow-10">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">我是内容我是内容我是内容我是内容我是内容我是内容</div>
    </div>
    </div>
</div>
````

### 蓝色框5点钟位置

````html
<div class="ui-poptip ui-poptip-blue">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">        
        <div class="ui-poptip-arrow ui-poptip-arrow-5">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">我是内容我是内容我是内容我是内容我是内容我是内容</div>
    </div>
    </div>
</div>
````

### 白色框

````html
<div class="ui-poptip ui-poptip-white">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">
        <div class="ui-poptip-arrow ui-poptip-arrow-5">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">我是内容我是内容我是内容我是内容我是内容我是内容</div>
    </div>
    </div>
</div>
````

### 9点钟位置

````html
<div class="ui-poptip">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">
        <div class="ui-poptip-arrow ui-poptip-arrow-9">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">我是内容我是内容<br>我是内容我是内容<br>我是内容我是内容</div>
    </div>
    </div>
</div>
````

### 3点钟位置蓝色

````html
<div class="ui-poptip ui-poptip-blue">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">
        <div class="ui-poptip-arrow ui-poptip-arrow-3">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">我是内容我是内容<br>我是内容我是内容<br>我是内容我是内容<br>我是内容我是内容</div>
    </div>
    </div>
</div>
````

### 12点钟位置

````html
<div class="ui-poptip">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">
        <div class="ui-poptip-arrow ui-poptip-arrow-12">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">我是内容我是内容我是内容我是内容</div>
    </div>
    </div>
</div>
````

### 6点钟位置

````html
<div class="ui-poptip">
    <div class="ui-poptip-shadow">
    <div class="ui-poptip-container">
        <div class="ui-poptip-arrow ui-poptip-arrow-6">
            <em></em>
            <span></span>
        </div>
        <div class="ui-poptip-content">我是内容我是内容我是内容我是内容</div>
    </div>
    </div>
</div>
````
