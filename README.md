# RNWeatherRevo
RN天气demo应用重构，用于演示UI组件的搭配和抽取，如何让代码层次结构清晰易于维护
## 经过重构之后的代码可读性和维护性都大大增强。 
结构分为4部分：
1. 数据源，手写的mock数据  
2. 抽取出来用于绘制的无状态组件，即一个个拆分出来的小渲染单元 
3. 整个页面本身，其中使用了swiper和scroll搭建了页面框架
4. 抽取出来的styles，也就是样式
## 运行：通过expo, npm install-> npm start 扫码即可在expo宿主环境中运行。

## 原代码链接：https://github.com/fangwei716/30-days-of-react-native
