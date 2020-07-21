# 移动端使用sass + rem + flexible 适配方案

## 安装
`
 cnpm install || yarn install 
`

## 运行
`
npm run serve
`

## 说明
- 设计稿要求750px;
- 宽度高度设置直接使用 `height: pxToRem(100px)`; // 100px 为750px实际尺寸
- 字体使用方式为: `@include font-dpr(18px);` // 18px为750设计稿量取的字体大小的一半
- 想要增加sass函数可以在公用文件夹进行增加 `@/assets/css/flexible`
- base.scss 和 flexible.scss 为配置引入,无需再次引入