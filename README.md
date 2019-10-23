## <center>mtui.css</center>
####  一、文件概述
    将传统臃肿的css样式搬到布局中，借助class或className等类名，快速生成样式，将臃肿转移至布局
####  二、文件缘由
    着手整合这个css,主要的原因有两个: 
    一是在原先的研发中，html和css两个文件切换较为频繁，在不使用鼠标的前提下，开发着实麻烦;
    二是研发后期，在css文件中寻找需要修改的类名，步骤大概需要，html复制类名->切换到css文件->ctrl+f5 搜索->修改,步骤太多，着实麻烦。 
####  三、文件思想
    复用类名、简写样式
####  四、文件举例
```
.w-100-px{
    width:100px;
}
.dis-f{
    display:flex;
}
.m-r-10-px{
    margin-right:10px;
}
.bg-f{
    background:#ffffff;
}
.cur-p:hover{
    cursor: pointer;
    color: #58ADFA;
}
```
#### 五、使用方式
    <link rel="stylesheet" type="text/css" href="./stylesheet/mtui.css">
    或
    import './stylesheet/mtui.css'
    等...
