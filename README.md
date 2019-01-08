# gallery 
[浏览](https://kastrcn.github.io/React-Demo/)
## cfg default.js 文件
```React
  loaders:[
       {
          test:/正则匹配的名称/,  //sass
          load:初始化1!初始化2!outputStyle=输出样式(格式化|单行|压缩|未压缩)
      }
      {
          test:/正则匹配的名称/,
          load:初始化1!初始化2!
      }
  ]
```
## Main.js结构
```React
import React
import React dom
let imagedDatas=json数据
imageDatas() -> 添加URL地址
getRangeRandom=(low,high)={}  ------>获得随机范围值
get30DegRandom=()=>{} ---------->获得随机旋转角度

Component ControllerUnit {
    构造方法{
        绑定事件
    }
    方法
    render(){
        渲染前事件
        return ()
    }
}
Component ImgFigure {
    构造方法{
        绑定事件
    }
    方法
    render(){
        渲染
        return(
        )
    }
}
Component AppComponent{
    构造方法{
        属性初始化
    }
    inverse函数
    rearrange函数
    componentDidMount 界面初始化后
     render(){
        渲染
        return(
        )
    }
}

```
