<template>
<div>
  <div style="text-align: center">
    <button type="button" @click="downloadPdf" style="margin:20px auto;cursor:pointer;">下载简历</button>
  </div>
  
  <div id="resumeWrap" class="resumeWrap">
    <div class="resumeTitle">个人简历</div>
    <div class="resumeContent">
      <div class="resumeTop">
        <!-- <div class="avatarWrap">
          <div class="avatar">
            <img class="avatarImg" src="../public/img/avator.png" alt="">
          </div>
        </div> -->
        <div class="userInfoWrap" style="margin-top:8px">
          <div class="userInfoItem">
            <div class="rightItem">
              <div class="itemTitle">
                <img class="itemIcon" src="../public/img/gerxinxi.svg" alt="">
                个人资料
              </div>
              <div class="itemContent">
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">姓&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;名：</span>
                  <span class="itemValue">谢顶金</span>
                </div>
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">性&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;别：</span>
                  <span class="itemValue">男</span>
                </div>
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">年&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;龄：</span>
                  <span class="itemValue">27</span>
                </div>
                
                <!-- <div class="itemWrap lineHeight">
                  <span class="itemLabel">出生年月：</span>
                  <span class="itemValue">1993.07</span>
                </div> -->
                <!-- <div class="itemWrap">
                  <span class="itemLabel">工作经验：</span>
                  <span class="itemValue">4年</span>
                </div> -->
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">电&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;话：</span>
                  <span class="itemValue">18576648902</span>
                </div>
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">微&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;信：</span>
                  <span class="itemValue">18378311282</span>
                </div>
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">邮&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;箱：</span>
                  <span class="itemValue">18576648902@163.com</span>
                </div>
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">住&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;址：</span>
                  <span class="itemValue">深圳市南山区</span>
                </div>
              </div>
            </div>
          </div>
          
          
          <div class="userInfoItem" style="margin: 0 16px">
            <div class="rightItem">
              <div class="itemTitle">
                <img class="itemIcon" src="../public/img/qiuzhiyixiang.svg" alt="">
                求职意向
              </div>
              <div class="itemContent">
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">期望职位：</span>
                  <span class="itemValue">高级前端开发工程师</span>
                </div>
                <!-- <div class="itemWrap lineHeight">
                  <span class="itemLabel">期望薪资：</span>
                  <span class="itemValue">20k ~ 30k</span>
                </div> -->
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">期望行业：</span>
                  <span class="itemValue">互联网</span>
                </div>
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">期望城市：</span>
                  <span class="itemValue">深圳市</span>
                </div>
              </div>
            </div>
            <div class="rightItem" style="margin-top: 10px">
              <div class="itemTitle">
                <img class="itemIcon" src="../public/img/xingquaihao.svg" alt="">
                兴趣爱好
              </div>
              <div class="itemContent">
                <span class="favoItem">篮球</span>
                <span class="favoItem">游泳</span>
                <span class="favoItem">爬山</span>
                <span class="favoItem">骑行</span>
                <!-- <span class="favoItem">羽毛球</span> -->
              </div>
            </div>
          </div>

          <div class="userInfoItem">
            <div class="rightItem">
              <div class="itemTitle">
                <img class="itemIcon" src="../public/img/jiaoyubeijing.svg" alt="">
                教育背景
              </div>
              <div class="itemContent">
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">学校名称：</span>
                  <span class="itemValue">桂林航天工业学院</span>
                </div>
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">所学专业：</span>
                  <span class="itemValue">汽车服务工程</span>
                </div>
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">就读时间：</span>
                  <span class="itemValue">2012-09 ~ 2016-06</span>
                </div>
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">学历学位：</span>
                  <span class="itemValue">本科（学士）</span>
                </div>
                <div class="itemWrap lineHeight">
                  <span class="itemLabel">获得证书：</span>
                  <span class="itemValue">英语四级、计算机二级</span>
                </div>
              </div>
            </div>
            
          </div>
          
        </div>
      </div>
      <div class="resumeMiddle">
        <div class="leftItem">
          <div class="itemTitle">
            <img class="itemIcon" src="../public/img/drxx14.svg" alt="">
            个人技能
          </div>
          <div class="itemContent">
            <p class="teachItem">
              1、熟练掌握HTML/HTML5、CSS/CSS3、JS、ES6等编程基础，了解浏览器运行原理及网络基础
            </p>
            <p class="teachItem">
              2、熟练掌握前端工程化打包工具Webpack、Babel的配置及优化，以及Git版本管理的使用
            </p>
            <p class="teachItem">
              3、熟练掌握React、Redux、Router、Vue及其核心原理，熟悉H5、小程序、数据可视化技术
            </p>
            <p class="teachItem">
              4、熟练运用D3、Antv、Echart、地图、动效库、canvas、svg等相关数据可视化技术
            </p>
            <p class="teachItem">
              5、熟悉项目的搭建、开发、部署流程，熟悉nginx的基本配置及Linux日常使用命令
            </p>
            <p class="teachItem">
              6、了解NodeJs、TypeScript、GraphQL开发方式，以及前端性能优化、web安全相关技术
            </p>
            <p class="teachItem">
              7、了解原生移动应用跨平台技术Flutter、React Native，小程序跨平台技术Taro、uni-app
            </p>
          </div>
        </div>
        <div class="leftItem">
          <div class="itemTitle">
            <img class="itemIcon" src="../public/img/pingjia.svg" alt="">
            自我评价
          </div>
          <div class="itemContent">
            <p class="teachItem">
              1、4年以上前端工作经验，具备较丰富的实战经验及良好的编码习惯，熟悉项目开发流程，能快速响应产品迭代及优化升级
            </p>
            <p class="teachItem">
              2、具备良好的分析问题、解决问题及团队协作能力，有较强的抗压能力与工作热情，自驱力及责任心强
            </p>
            <p class="teachItem">
              3、良好的学习能力，关注前端前沿技术，能够快速学习一门新技术并实践，做事重视细节和结果，愿意接受新挑战
            </p>
          </div>
        </div>
        <div class="leftItem">
          <div class="itemTitle">
            <img class="itemIcon" src="../public/img/drxx20.svg" alt="">
            工作经历
          </div>
          <div class="itemContent">
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">公司名称：</span>
                <span class="itemValue">平安国际智慧城市科技股份有限公司</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">所属部门：</span>
                <span class="itemValue">智慧交通及社区事业部畅通管理部产品支持团队</span>
              </p>
            </div>
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">所属职位：</span>
                <span class="itemValue">前端开发工程师</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">在职时间：</span>
                <span class="itemValue">2019-03 ~ 至今</span>
              </p>
            </div>
            <!-- <p class="teachItem">
              <span class="itemLabel">前端团队：</span>
              <span class="itemValue">13人</span>
            </p> -->
            <div class="descItem">
              <div class="descLabel">工作描述：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、作为前端核心成员，主要负责项目的基础建设、框架搭建、核心功能开发、部署上线等工作，勇于承担重、难点的技术攻克
                </p>
                <p class="descValue">
                  2、作为开发组长，主要负责参与需求评审，制定开发计划，合理排期推进项目，code review，确保项目按时高质量完成交付
                </p>
                <p class="descValue">
                  3、参与团队产品核心模块的研发，为团队在开发过程中遇到问题提供解决思路及技术支持，学习新技术并运用到项目上
                </p>
              </div>
            </div>
          </div>
          <hr>
          <div class="itemContent">
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">公司名称：</span>
                <span class="itemValue">深圳市有品网络科技有限公司</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">所属部门：</span>
                <span class="itemValue">产品研发部</span>
              </p>
            </div>
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">所属职位：</span>
                <span class="itemValue">前端开发工程师</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">在职时间：</span>
                <span class="itemValue">2018-08 ~ 2019-03</span>
              </p>
            </div>
            <!-- <p class="teachItem">
              <span class="itemLabel">前端团队：</span>
              <span class="itemValue">1人</span>
            </p> -->
            <div class="descItem">
              <div class="descLabel">工作描述：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、公司前端小组负责人，负责前端新人招聘，带新人及前端技术选型，框架搭建，代码实现，技术难点攻克
                </p>
                <p class="descValue">
                  2、负责前端的日常开发及优化迭代，参与公司官网优化，国外导购平台重构，内部沟通系统开发及数字资产交易所迭代
                </p>
                <p class="descValue">
                  3、负责与产品进行需求对接，与后台、测试沟通协作，合理排期开发任务，确保按时高质量完成交付
                </p>
              </div>
            </div>
          </div>
          <hr>
          <div class="itemContent">
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">公司名称：</span>
                <span class="itemValue">深圳竹云科技有限公司</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">所属部门：</span>
                <span class="itemValue">产品研发部</span>
              </p>
            </div>
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">所属职位：</span>
                <span class="itemValue">软件工程师</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">在职时间：</span>
                <span class="itemValue">2016-07 ~ 2018-08</span>
              </p>
            </div>
            <!-- <p class="teachItem">
              <span class="itemLabel">前端团队：</span>
              <span class="itemValue">1人</span>
            </p> -->
            <div class="descItem">
              <div class="descLabel">工作描述：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、负责公司核心产品的定制化开发，前端涉及ui更新，浏览器兼容，响应式，性能优化，使用java web技术栈（前后端不分离）
                </p>
                <p class="descValue">
                  2、负责前端页面(jsp)的重构，采用新的ui框架，以及新的前端技术来进行重构，专注于提升界面的用户体验
                </p>
                <p class="descValue">
                  3、根据不同项目做针对性的定制开发，前后参与了广发银行、东莞农商银行、中科金证、深圳市公立医院管理中心、华侨城等项目
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="leftItem">
          <div class="itemTitle">
            <img class="itemIcon" src="../public/img/_xiangmujingyan.svg" alt="">
            项目经验
          </div>
           <div class="itemContent">
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">项目名称：</span>
                <span class="itemValue">桐乡交通大脑</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">担任角色：</span>
                <span class="itemValue">业务开发、性能优化</span>
              </p>
            </div>
            <p class="teachItem">
              <span class="itemLabel">开发时间：</span>
              <span class="itemValue">2020-11 ~ 2020-12</span>
            </p>
            <div class="descItem">
              <div class="descLabel">项目简介：</div>
              <div class="itemValue">
                桐乡交通大脑项目主要是城市交通大屏数据中台，以可视化的方式展示城市交通的实时动态，业务主要包括城市交通总览，交通态势，车辆研判，非机动车，信号控制，交通设备，涵盖了交通路况、干道、路口、设备、机动车追踪以及非机动违规等，方便指挥人员掌握实时交通情况，便于数据分析，提升办公效率
              </div>
            </div>
            <div class="descItem">
              <div class="descLabel">工作内容：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、负责信号管控模块、城市总览模块部分的业务开发，以及响应式框架的优化
                </p>
                <p class="descValue">
                  2、项目难点部分攻坚，通过d3技术解决了路口渠化图效果问题，使用css特性实现地图热力效果
                </p>
                <p class="descValue">
                  3、参与性能优化工作，解决了路况数据过大造成的卡顿问题，解决项目编译时间过长等问题
                </p>
                <p class="descValue">
                  4、推崇模块化开发方式，降低模块间的耦合度，功能独立化，方便项目间的复用
                </p>
              </div>
            </div>
            <p class="teachItem">
              <span class="itemLabel">相关技术：</span>
              <span class="itemValue">
                react、mobx、react-router、axios、d3、echart、webpack、less
              </span>
            </p>
          </div>

          <hr>
          <div class="itemContent">
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">项目名称：</span>
                <span class="itemValue">公安网校大数据分析平台</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">担任角色：</span>
                <span class="itemValue">技术选型、框架搭建、开发、部署、优化</span>
              </p>
            </div>
            <p class="teachItem">
              <span class="itemLabel">开发时间：</span>
              <span class="itemValue">2020-08 ~ 2020-09</span>
            </p>
            <div class="descItem">
              <div class="descLabel">项目简介：</div>
              <div class="itemValue">
                公安网校大数据分析平台是公安部门线下、线上课程培训的大数据分析平台，主要对不同年份的课程培训情况做统计分析，线上课程需要实时更新直播状态等数据，线下主要是对各种培训指标做统计展示</div>
            </div>
            <div class="descItem">
              <div class="descLabel">工作内容：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、负责项目的需求评审、技术选型、框架搭建、开发实现、部署上线、调优升级等工作
                </p>
                <p class="descValue">
                  2、负责构建项目上线流程配置，编写脚本实现自动化部署，开发过程中融入新技术graphql进行模拟数据调试
                </p>
                <p class="descValue">
                  3、自定义框架响应式方式，使之兼容不同分辨率的设备，运用动效交互，提升用户体验
                </p>
              </div>
            </div>
            <p class="teachItem">
              <span class="itemLabel">相关技术：</span>
              <span class="itemValue">
                react hook、Ts、react-router、axios、antv、ant-design、webpack、less
              </span>
            </p>
          </div>

          <hr>
          <div class="itemContent">
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">项目名称：</span>
                <span class="itemValue">信号优化等信控子系统</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">担任角色：</span>
                <span class="itemValue">核心功能模块及公共组件开发，技术难点攻克</span>
              </p>
            </div>
            <p class="teachItem">
              <span class="itemLabel">开发时间：</span>
              <span class="itemValue">2019-12 ~ 2020-06</span>
            </p>
            <div class="descItem">
              <div class="descLabel">项目简介：</div>
              <div class="itemValue">
                信控系统是我们畅通业务线的核心产品，主要是给交警部门提供一系列的城市交通拥堵解决方案。而信号优化系统则属于其中一个环节，其主要是对交通路口的时段、信号灯及干道进行优化。干道协调优化是对多个路口进行信号灯协调优化，使多路口之间达到一个最优的可持续通行时间，解决城市道路路口排队拥堵问题，达到一路畅通的效果。通过地图、图表、图形等可视化技术做到直观的展示信号灯控制效果。最终将优化后的方案下发到信号灯中。系统专注于提升交警工作效率
              </div>
            </div>
            <div class="descItem">
              <div class="descLabel">工作内容：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、运用D3可视化技术实现交通绿波优化工具、流量图、动态相位图等重、难点的技术攻克
                </p>
                <p class="descValue">
                  2、负责项目核心模块的开发，能够高度还原ui设计稿，引入动效及图形，达到直观展示交通指标效果
                </p>
                <p class="descValue">
                  3、为团队内部开发路口配置数据录入配置工具，提升团队工作效率，为产品上线与维护提供技术支持
                </p>
              </div>
            </div>
            <p class="teachItem">
              <span class="itemLabel">相关技术：</span>
              <span class="itemValue">
                react、redux、react-router、echart、antv、D3、凯立德地图、websocket、axios、ant-design、less
              </span>
            </p>
          </div>
          <hr>
          <div class="itemContent">
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">项目名称：</span>
                <span class="itemValue">随手拍举报</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">担任角色：</span>
                <span class="itemValue">优化升级及定制开发</span>
              </p>
            </div>
            <p class="teachItem">
              <span class="itemLabel">开发时间：</span>
              <span class="itemValue">2020-04 ~ 2020-08</span>
            </p>
            <div class="descItem">
              <div class="descLabel">项目简介：</div>
              <div class="itemValue">
                随手拍是交通违法举报的一个toC端应用，包含小程序端和H5端以及后台审核系统，用户可以通过应用端对交通的多种违法行为进行举报，举报成功会有相应的奖励。平台旨在提倡治理文明交通，全民参与
              </div>
            </div>
            <div class="descItem">
              <div class="descLabel">工作内容：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、负责优化维护已上线的随手拍举报系统，并且根据不同城市的需求进行定制化开发
                </p>
                <p class="descValue">
                  2、使用原生的微信小程序开发框架，熟悉其开发结构和模式，根据客户反馈，对项目进行体验优化、升级
                </p>
                <p class="descValue">
                  3、掌握小程序开发构建部署完整的流程，提升用户体验交互，能够很好的完成项目交付
                </p>
              </div>
            </div>
            <p class="teachItem">
              <span class="itemLabel">相关技术：</span>
              <span class="itemValue">
                H5、原生微信小程序框架、腾讯地图、刷脸认证
              </span>
            </p>
          </div>

          <hr>
          <div class="itemContent">
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">项目名称：</span>
                <span class="itemValue">backerLand国外导购平台</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">担任角色：</span>
                <span class="itemValue">项目重构、新系统开发</span>
              </p>
            </div>
            <p class="teachItem">
              <span class="itemLabel">开发时间：</span>
              <span class="itemValue">2018-09 ~ 2019-02</span>
            </p>
            <div class="descItem">
              <div class="descLabel">项目简介：</div>
              <div class="itemValue">
                backerLand是国外一个给众筹产品做推广预热的平台。B端客户通过平台购买服务，平台支持信用卡等支付方式，支付成功后，向平台上传产品资料。等管理员审核通过后，平台会基于c端用户等其他渠道来做推广引流。B端客户可通过平台查看项目的进度及推广情况，实现平台一体化服务
              </div>
            </div>
            <div class="descItem">
              <div class="descLabel">工作内容：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、负责和国外团队进行需求收集对接，整理需求文档，制定开发计划，合理排期开发任务
                </p>
                <p class="descValue">
                  2、负责项目的前端技术选型，框架设计及代码实现，与后端同事协作开发，负责项目的跟进、汇报
                </p>
                <p class="descValue">
                  3、负责项目的前端开发，后台管理系统使用vue前后端分离技术，前台B端和C端使用boostrap响应式框架
                </p>
              </div>
            </div>
            <div class="descItem">
              <div class="descLabel">相关技术：</div>
              <div class="itemValue">
                <p class="descValue">
                  vue2.0、webpack、es6、jwt、elementui、bootstrap4、gulp、flyjs、easy_mock
                </p>
              </div>
            </div>
          </div>

          <hr>
          <div class="itemContent">
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">项目名称：</span>
                <span class="itemValue">广发银行集中身份管理系统</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">担任角色：</span>
                <span class="itemValue">项目重构、定制化开发</span>
              </p>
            </div>
            <p class="teachItem">
              <span class="itemLabel">开发时间：</span>
              <span class="itemValue">2016-08 ~ 2018-03</span>
            </p>
            <div class="descItem">
              <div class="descLabel">项目简介：</div>
              <div class="itemValue">
                广发银行集中身份管理系统主要用于身份自动化管理，承接柜面外围系统和其他新系统，行员可通过该系统进行统一认证、应用单点登录、账号申请、权限控制、人员调动、工作流审批等操作
              </div>
            </div>
            <div class="descItem">
              <div class="descLabel">工作内容：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、前后端没有分离，工作内容偏向于全栈开发，主要编写jsp、Java、html、css代码，熟悉后台ssm框架、数据库操作
                </p>
                <p class="descValue">
                  2、参与产品的定制化开发，负责restful风格的接口改造，使用新技术进行项目重构
                </p>
                <p class="descValue">
                  3、参与前端UI框架改造，前端开发涉及浏览器的兼容性、响应式、性能调优等
                </p>
              </div>
            </div>
            <p class="teachItem">
              <span class="itemLabel">相关技术：</span>
              <span class="itemValue">
                java、jsp、ligerui、layerui、js、ajax、jquery、html、css
              </span>
            </p>
          </div>

        </div>

        <!-- <div class="leftItem">
          <div class="itemTitle">
            <img class="itemIcon" src="../public/img/xingquaihao.svg" alt="">
            兴趣爱好
          </div>
          <div class="itemContent">
            <span class="favoItem">篮球</span>
            <span class="favoItem">游泳</span>
            <span class="favoItem">爬山</span>
            <span class="favoItem">骑行</span>
            <span class="favoItem">唱K</span>
            <span class="favoItem">羽毛球</span>
          </div>
        </div> -->
      </div>
      
    </div>
  </div>

  

</div>
  
</template>

<script>
import html2canvas from 'html2canvas';
import { jsPDF } from "jspdf";
export default {
  mounted(){
    // console.log('挂载成功')
    // this.downloadPdf();
  },
  methods: {
    downloadPdf: () => {
      html2canvas(document.querySelector('#resumeWrap'),{
        width: document.querySelector('#resumeWrap').clientWidth,
        x: (window.innerWidth - document.querySelector('#resumeWrap').clientWidth)/2,
        backgroundColor: '#dfe2e5'
      }).then(function(canvas) {
        // console.log('options',canvas)
        // document.body.appendChild(canvas);
        
        var contentWidth = canvas.width;
        var contentHeight = canvas.height;

        //一页pdf显示html页面生成的canvas高度;
        var pageHeight = contentWidth / 592.28 * 841.89;

        //未生成pdf的html页面高度
        var leftHeight = contentHeight;

        //页面偏移
        var position = 0;

        //a4纸的尺寸[595.28,841.89]，html页面生成的canvas在pdf中图片的宽高
        var imgWidth = 595.28;
        var imgHeight = 592.28/contentWidth * contentHeight + 45;

        var pageData = canvas.toDataURL('image/jpeg', 1.0);

        var pdf = new jsPDF('', 'pt', 'a4');
        console.log('pdf', pdf)

        //有两个高度需要区分，一个是html页面的实际高度，和生成pdf的页面高度(841.89)
        //当内容未超过pdf一页显示的范围，无需分页
        if (leftHeight < pageHeight) {
          pdf.addImage(pageData, 'JPEG', 0, 0, imgWidth, imgHeight );
        } else {
          // pdf.addImage(pageData, 'JPEG', 0, 0, imgWidth, imgHeight + 20);
          while(leftHeight > 0) {
            pdf.addImage(pageData, 'JPEG', 0, position, imgWidth, imgHeight)
            leftHeight -= pageHeight;
            position -= 841.89;
            //避免添加空白页
            if(leftHeight > 0) {
              pdf.addPage();
            }
          }
        }
        pdf.save("谢顶金 - 前端求职简历.pdf");
      });
    }
  }
}
</script>
<style lang="less" scoped>
  .resumeWrap{
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 860px;
    height: 100%;
    margin: 0 auto;
    background-color: #fff; //#dfe2e5; //#02c59d;
  }
  .resumeTitle{
    width: 100%;
    height: 60px;
    line-height: 60px;
    font-family: PingFang SC;
    font-weight: 600;
    font-size: 24px;
    color: #393e46;
    text-align: center;
  }
  .resumeContent{
    overflow: hidden;
    flex: 1;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
  }
  .resumeTop{
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .oneline{
    display: flex;
    justify-content: flex-start;
    align-items: center;
    .onelineItem{
      width: 50%;
    }
  }
  .avatar{
    overflow: hidden;
    width: 100px;
    height: 100px;
    border-radius: 50%;
  }
  .avatarImg{
    width: 100%;
    height: 100%;
  }
  .itemName{
    font-size: 16px;
    color: #333;
    font-weight: 600;
    text-align: center;
    margin-top: 8px;
  }
  .userInfoWrap{
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin-top: 16px;
    padding: 0 24px;
  }
  .itemTitle{
    display: flex;
    justify-content: flex-start;
    align-items: center;
    color: #333;
    font-weight: 600;
    margin-bottom: 6px;
  }
  .itemIcon{
    width: 18px;
    height: 18px;
    margin-right: 4px;
  }
  
  .itemWrap{
    font-size: 12px;
  }
  .lineHeight{
    line-height: 26px;
  }
  .itemLabel{
    color: #1e2022;
    font-weight: 600;
  }
  .itemValue{
    flex: 1;
    color: #52616b;
  }

  .resumeMiddle{
    height: 100%; 
    display: flex;
    flex-direction: column;
    padding: 16px 24px;
    .itemContent{
      padding-left: 24px;
    }
  }
  .userInfoItem{
    height: 232px;
    width: 260px;
    .rightItem{
      padding: 16px;
      border-radius: 6px;
      background-color: #f4f4f4;
      // box-sizing: border-box;
      // width: 100%;
      // height: 100%;
    }
  }
  
  .userInfoItem:not(:nth-child(2)){
    .rightItem{
      height: calc(~"100% - 32px");
    }
  }
  .leftItem{
    padding: 14px;
    margin-bottom: 12px;
    border-radius: 6px;
    background-color: #f4f4f4;
  }
  .leftItem:last-child{
    margin-bottom: 0;
  }
  .itemLabel{
    color: #1e2022;
    font-weight: 600;
  }
  .itemValue{
    flex: 1;
    color: #52616b;
  }
  .teachItem{
    margin: 0;
    padding-top: 6px;
    font-size: 12px;
    color: #222831;
  }
  .descItem{
    display: flex;
    justify-content: flex-start;
    align-items: flex-start;
    margin: 0;
    padding-top: 6px;
    font-size: 12px;
    color: #222831;
  }
  .descLabel{
    color: #1e2022;
    font-weight: 600;
  }
  .descValue{
    flex: 1;
    margin-top: 0;
    margin-bottom: 4px;
    color: #52616b;
  }
  .favoItem{
    display: inline-block;
    font-size: 12px;
    padding: 4px 8px;
    background: #ebecf1;
    border-radius: 16px;
    margin: 2px 3px 0 0;
    color: #222831;
  }
  
</style>