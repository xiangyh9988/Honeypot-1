<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
html,body,#app {
  max-width: 1920px;
  max-height: 1080px;
  height: 100%;
  margin:0 auto;
  font-family: 'Microsoft Yahei' !important;
  /* font-family: 'Avenir', Helvetica, Arial, sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  overflow-y:hidden;
  overflow-x:hidden;

}
@font-face {
  font-family: 'iconfont';  /* project id 796633 */
  src: url('//at.alicdn.com/t/font_796633_b3c1isjjwu.eot');
  src: url('//at.alicdn.com/t/font_796633_b3c1isjjwu.eot?#iefix') format('embedded-opentype'),
  url('//at.alicdn.com/t/font_796633_b3c1isjjwu.woff') format('woff'),
  url('//at.alicdn.com/t/font_796633_b3c1isjjwu.ttf') format('truetype'),
  url('//at.alicdn.com/t/font_796633_b3c1isjjwu.svg#iconfont') format('svg');
}


.iconfont{
  font-family:"iconfont" !important;
  font-size:36px;font-style:normal;
  -webkit-font-smoothing: antialiased;
  -webkit-text-stroke-width: 0px;
  color:#5EBF18;
;}
/* *********************************************mian start*****************/
/* 绿色字体 */
.wow{
  position: relative;
  bottom:15px;
}

.p-2{
  position: relative;
  top: 10px;
  font-size: 18pt;
  font-weight: bold;
  left: 20px;
  font-family: '微软雅黑';
  margin: 0;

}
/* 白色条框 */
.header-2{
  margin: 0;
  height:60px;
  width:100%;
  color:black;
  font-weight: 500;
  overflow: hidden;
}
.el-pagination .el-pager .active{
  background-color: #E95513 !important;
}
.el-pagination.is-background .el-pager li:not(.disabled):hover{
  color:#E95513 !important;
}
.p-page{
  padding-top: 15px;
  color:#666666;
  float:left;
  font-size: 12pt;
}
.el-main-2{
  padding: 2px !important;
}
/**tabs的颜色 */
.el-tabs__item.is-active{
  color: #666666 !important;
}
.el-tabs__item:hover{
  color: #E95513 !important;
}
/********************************** 查看详情的颜色 */
.el-button--text{

  color:#E95513 !important;
}
.el-button--text.is-active{
  color: #E95513 !important ;
}
.el-button--text:hover{
  color: #E95513 !important;
}
.tab-1-1{
  margin-left: 30px;
  margin-top:15px;
  margin-bottom: 10px;
}
.tab-2-1{
  margin-left: 30px;
  margin-top:15px;
  margin-bottom: 10px;
}
.button1{
  width: 80px;
  height: 30px;
  font-size: 12.14px;
  line-height:6px;
  border-radius: 0px;
}

.table-p1{
  font-family: 'Microsoft YaHei';
  font-size: 12pt;
  color:#BFBFBF;
}
/* ******原始日志查询-左侧菜单栏 start*/
.tab-aside{
  height: 100%;
  overflow: hidden;
}
/****************************************** main  end */
.button1{
  background-color: #E95513 !important;
  color: #ffff !important;

}
.el-checkbox__input.is-checked .el-checkbox__inner, .el-checkbox__input.is-indeterminate .el-checkbox__inner {
  background-color: #E95513 !important;
  border-color:#E95513 !important;
}
.el-button--primary {
  color: #fff;
  background-color: #E95513 !important;
  border-color:#E95513 !important;
}
.td-1 td{
  padding-left: 15px;
  color: #909399;
}
.el-tabs__active-bar {
  display: none;
}
/*刚修改的分页背景颜色问题*/
.el-tabs--card>.el-tabs__header .el-tabs__item.is-active {
  border-bottom: 2px solid #E95513;
  background: #fff;
}
.el-tabs--card>.el-tabs__header .el-tabs__item.is-active{
  border-bottom: 2px solid #E95513;}


.el-tabs--card>.el-tabs__header .el-tabs__item.is-active{
  border-bottom: 2px solid #E95513;

}
.el-tabs--left .el-tabs__item.is-left, .el-tabs--left .el-tabs__item.is-left.is-active{
  text-align: left;
  width: 250px;
  height: 30px;
  line-height: 30px;
}


/*侧面导航栏布局*/
.tab-2-1 {
  margin-left: 0px;
}


/*导航栏背景颜色*/
.el-tabs__nav-wrap.is-left {
  background: #F2F2F2;
}
.el-tabs__nav-wrap::after {
  background: #F2F2F2;
}
.el-tabs--card>.el-tabs__header .el-tabs__nav {
  background: #F2F2F2;
}
/*导航栏间隔*/
.el-tabs__header {
  padding: 0;
  position: relative;
  margin: 0 0 10px;
}
.el-tabs__item:active {
  color: #E95513 !important;
  background: #fff;
}
.el-tabs__item:focus, .el-tabs__item:active {
  color: #E95513 !important;
  outline: 0;
  background: #fff;
}
.el-tabs--left .el-tabs__active-bar.is-left, .el-tabs--left .el-tabs__nav-wrap.is-left::after {

}
/*导航栏样式*/
.el-tabs__item.is-left.is-active{
  color: #E95513 !important;
  background: #fff;
}
/*侧面导航栏间距问题*/
.tab-2-1 {
  margin-top: 0px;
}

/*输入框样式*/
.inputType1 .el-input__inner{
  height: 30px;
  border-right: 0px;
  border-radius: 0px;
  margin-right: 0px;
}
.el-table th>.cell {
  background: #e95513;
  color: #fff;

  font-weight: bold;
  font-size: 12px;


  /*border-right: 1px solid #fff;*/

  font-size: 12px;



  font-size: 12px;

  vertical-align: center;
  padding-left: 20px;
  margin-bottom: 0px;
  /* line-height: initial; */
}
.el-table th{
  height: 29px;
  border-right: 1px solid #fff;
}
.el-table__body, .el-table__footer, .el-table__header{
  font-weight: bold;
  font-size: 12px;
}

.el-pagination .el-select .el-input .el-input__inner{
  float:left;
}
/*分页*/
.el-pagination .el-select .el-input {
  position: absolute;
  left: -640px;
  top:-15px;
  font-size: 12px;
  border-radius: 0px;
}


.button2{
  background-color: #E95513 !important;
  color: #ffff !important;
  width: 60px;
  height: 30px;
  border-radius: 0px;
  vertical-align: center;
  padding: 2px;
  font-size: 12px;
  margin-left:10px ;
}


.el-pagination__jump{
  position: relative;
  left: -1140px;
  top:9px;
}
el-pagination__sizes .el-input .el-input__inner:hover {
  border-color: #fff;
}
.el-select-dropdown__item.selected {
  color: #fff;
  font-weight: 700;
  background: #e95513;
}
.el-select .el-input .el-select__caret{
  font-size: 12px;
}
.el-select.el-input__icon{
  line-height: 30px;
}
.el-input{
  font-size: 12px;
}
.el-select-dropdown__item.hover, .el-select-dropdown__item:hover:active{
  background: #e95513;
}
/*.el-select.el-input*/ .el-input--suffix{
                          height: 30px;
                        }
.el-select .el-input.is-focus .el-input__inner{
  border-color:#c0c4cc;
}
.el-select.el-input.el-input__inner {
  color: #606266;
  height: 30px;
  line-height: 30px;
}
.el-select.el-input__icon{
  line-height: 30px;
  height: 30px;
}
.el-select>.el-input--suffix{
  line-height: 30px;
  height: 30px;
}
.el-input__suffix{
  height: 30px;
}
.el-input__inner{
  line-height: 30px;
  height: 30px;
}

.el-icon-arrow-up{
  line-height: 10px;
  height: 30px;
}
.is-reverse{
  line-height: 30px;
  height: 30px;
}

/*********************确定 跳转 按钮样式*********************/
.button2{
  background-color: #E95513 !important;
  color: #ffff !important;
  width: 60px;
  height: 30px;
  border-radius: 0px;
  vertical-align: center;
  padding: 2px;
  font-size: 12px;
  margin-left:10px ;
}
/*********************取消按钮样式*********************/
.button3{
  background-color: #ffffff !important;
  color: black !important;
  width: 60px;
  height: 30px;
  border-radius: 0px;
  vertical-align: center;
  padding: 2px;
  font-size: 12px;
  margin-left:10px ;
}
/*********************普通按钮样式*********************/
.button4{
  background-color: #E95513 !important;
  color: #ffff !important;
  width: 80px;
  height: 30px;
  border-radius: 0px;
  vertical-align: center;
  padding: 2px;
  font-size: 12px;
  margin-left:10px ;

}
.left-nav{
  margin-left: 0px!important;
}
.el-tabs--left .el-tabs__item.is-left, .el-tabs--left .el-tabs__item.is-left.is-active {
  text-align: left;
  width: 250px;
  height: 30px;
  line-height: 56px;
  font-size: 14px;
  text-align: left;
  height: 56px;
  padding-left: 40px !important;
}
.el-tabs--left .el-tabs__item.is-left, .el-tabs--left .el-tabs__item.is-left {
  text-align: left;
  width: 250px;
  height: 30px;
  line-height: 56px;
  font-size: 14px;
  text-align: left;
  height: 56px;
  padding-left: 40px;
}
.el-tabs__nav>.is-left{
  text-align: left;
  width: 250px;
  height: 30px;
  line-height: 56px;
  font-size: 14px;
  text-align: left;
  height: 56px;
  padding-left: 40px !important;
}




</style>
