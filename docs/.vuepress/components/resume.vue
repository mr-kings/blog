<template>
<div>
  <div style="text-align: center">
    <button type="button" @click="downloadPdf" style="margin:20px auto;cursor:pointer;">下载简历</button>
  </div>
  
  <div id="resumeWrap" class="resumeWrap">
    <div class="resumeTitle">个人简历</div>
    <div class="resumeContent">
      <div class="resumeTop">
        <div class="avatarWrap">
          <div class="avatar">
            <img class="avatarImg" src="../public/img/avator.png" alt="">
          </div>
        </div>
        <div class="userInfoWrap">
          <div class="userInfoItem">
            <div class="rightItem">
              <div class="itemTitle">
                <img class="itemIcon" src="../public/img/gerxinxi.svg" alt="">
                个人资料
              </div>
              <div class="itemContent">
                <div class="itemWrap">
                  <span class="itemLabel">姓&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;名：</span>
                  <span class="itemValue">谢顶金</span>
                </div>
                <div class="itemWrap">
                  <span class="itemLabel">性&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;别：</span>
                  <span class="itemValue">男</span>
                </div>
                <div class="itemWrap">
                  <span class="itemLabel">名&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;族：</span>
                  <span class="itemValue">仫佬族</span>
                </div>
                <div class="itemWrap">
                  <span class="itemLabel">出生年月：</span>
                  <span class="itemValue">1993.07</span>
                </div>
                <div class="itemWrap">
                  <span class="itemLabel">工作经验：</span>
                  <span class="itemValue">4年</span>
                </div>
                <div class="itemWrap">
                  <span class="itemLabel">电&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;话：</span>
                  <span class="itemValue">18576648902</span>
                </div>
                <div class="itemWrap">
                  <span class="itemLabel">邮&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;箱：</span>
                  <span class="itemValue">18576648902@163.com</span>
                </div>
                <div class="itemWrap">
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
                <div class="itemWrap">
                  <span class="itemLabel">期望职位：</span>
                  <span class="itemValue">高级前端开发工程师</span>
                </div>
                <!-- <div class="itemWrap">
                  <span class="itemLabel">期望薪资：</span>
                  <span class="itemValue">20k ~ 30k</span>
                </div> -->
                <div class="itemWrap">
                  <span class="itemLabel">期望行业：</span>
                  <span class="itemValue">互联网</span>
                </div>
                <div class="itemWrap">
                  <span class="itemLabel">期望城市：</span>
                  <span class="itemValue">深圳市</span>
                </div>
              </div>
            </div>
            <div class="rightItem" style="margin-top: 16px">
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
                <div class="itemWrap">
                  <span class="itemLabel">学校名称：</span>
                  <span class="itemValue">桂林航天工业学院</span>
                </div>
                <div class="itemWrap">
                  <span class="itemLabel">所学专业：</span>
                  <span class="itemValue">汽车服务工程</span>
                </div>
                <div class="itemWrap">
                  <span class="itemLabel">主修课程：</span>
                  <span class="itemValue">汽车销售、维修、保险</span>
                </div>
                <div class="itemWrap">
                  <span class="itemLabel">就读时间：</span>
                  <span class="itemValue">2012-09 ~ 2016-06</span>
                </div>
                <div class="itemWrap">
                  <span class="itemLabel">学历学位：</span>
                  <span class="itemValue">本科（学士）</span>
                </div>
                <div class="itemWrap">
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
              2、熟练掌握工程化打包工具Webpack的配置及优化，以及Git版本管理的使用
            </p>
            <p class="teachItem">
              3、熟练使用React、Vue主流框架并了解其核心原理，熟悉小程序、数据可视化开发技术
            </p>
            <p class="teachItem">
              4、熟悉项目的搭建、部署流程，熟悉nginx的基本配置及Linux日常使用命令
            </p>
            <p class="teachItem">
              5、熟练运用D3、Antv、Echart、地图相关等可视化技术
            </p>
            <p class="teachItem">
              6、了解NodeJs、TS、GraphQL开发方式，以及前端优化、web安全相关知识
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
              1、4年前端开发，具备丰富的实战经验，以及良好的逻辑思维和编码习惯，能独立负责项目的开发及迭代维护
            </p>
            <p class="teachItem">
              2、具备良好的分析问题和解决问题的能力以及沟通、团队协作能力，较强的工作热情与主动性，自驱力及责任心强
            </p>
            <p class="teachItem">
              3、对技术有浓厚兴趣，乐于学习，拥抱新技术，敢于承担项目中重点、难点的技术攻克，愿意接受新挑战
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
            <p class="teachItem">
              <span class="itemLabel">前端团队：</span>
              <span class="itemValue">13人</span>
            </p>
            <div class="descItem">
              <div class="descLabel">工作描述：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、负责团队重点产品核心功能的研发，开发涉及管理后台、大屏数据可视化、小程序，以及历史项目的迭代维护
                </p>
                <p class="descValue">
                  2、作为前端核心成员，负责公共组件的开发，承担项目中重点、难点的技术攻克，以及负责团队技术问题解答
                </p>
                <p class="descValue">
                  3、带小团队进行业务开发，负责框架搭建以及项目优化、上线部署等相关工作，确保项目按时高质量完成交付
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
            <p class="teachItem">
              <span class="itemLabel">前端团队：</span>
              <span class="itemValue">1人</span>
            </p>
            <div class="descItem">
              <div class="descLabel">工作描述：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、负责公司所有前端项目的开发及维护，解决项目上遇到的各种问题，一个人扛下所有前端工作
                </p>
                <p class="descValue">
                  2、负责公司官网的维护与优化，国外导购平台的重构开发，涉及前台展示及后台管理，包含toB、toC业务
                </p>
                <p class="descValue">
                  3、负责研发公司内部的沟通应用系统，以及接手公司数字资产交易所的前端开发及版本迭代
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
            <p class="teachItem">
              <span class="itemLabel">前端团队：</span>
              <span class="itemValue">1人</span>
            </p>
            <div class="descItem">
              <div class="descLabel">工作描述：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、负责公司产品的定制化开发，主要是偏向java web方向（前后端交互方面）
                </p>
                <p class="descValue">
                  2、负责前端页面的重构，提升界面的用户体验。开发涉及页面的响应式、浏览器的兼容性及性能调优方面
                </p>
                <p class="descValue">
                  3、前后参与了广发银行、东莞农商银行、中科金证、深圳市公立医院管理中心、华侨城等项目
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
                <span class="itemValue">公安网校后台统计系统</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">担任角色：</span>
                <span class="itemValue">框架搭建、开发、部署</span>
              </p>
            </div>
            <p class="teachItem">
              <span class="itemLabel">开发时间：</span>
              <span class="itemValue">2020-08 ~ 至今</span>
            </p>
            <div class="descItem">
              <div class="descLabel">工作内容：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、负责项目的搭建、技术选型、开发、部署、优化等工作
                </p>
                <p class="descValue">
                  2、熟练掌握开发到上线的全流程，开发过程中融入新技术，掌握新的开发模式
                </p>
                <p class="descValue">
                  3、项目是大屏数据可视化，掌握大屏可视化技术及响应式布局
                </p>
              </div>
            </div>
            <p class="teachItem">
              <span class="itemLabel">相关技术：</span>
              <span class="itemValue">
                React Hooks、Antv、Ts、Ant-Design、Webpack
              </span>
            </p>
          </div>

          <hr>
          <div class="itemContent">
            <div class="oneline">
              <p class="teachItem onelineItem">
                <span class="itemLabel">项目名称：</span>
                <span class="itemValue">信号优化等信控产品子系统</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">担任角色：</span>
                <span class="itemValue">核心功能模块及公共组件的开发</span>
              </p>
            </div>
            <p class="teachItem">
              <span class="itemLabel">开发时间：</span>
              <span class="itemValue">2019-12 ~ 2020-06</span>
            </p>
            <div class="descItem">
              <div class="descLabel">工作内容：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、负责项目上核心模块，以及复杂组件的开发
                </p>
                <p class="descValue">
                  2、运用D3实现了绿波优化工具、流量图、配时方案图等重点、难点的技术攻克
                </p>
                <p class="descValue">
                  3、开发团队内部使用的数据录入配置工具，提升团队工作效率,为产品上线与维护提供技术支持
                </p>
              </div>
            </div>
            <p class="teachItem">
              <span class="itemLabel">相关技术：</span>
              <span class="itemValue">
                React、Echart、D3、凯立德地图、Ant-Design、Webpack
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
                <span class="itemValue">负责维护及迭代开发</span>
              </p>
            </div>
            <p class="teachItem">
              <span class="itemLabel">开发时间：</span>
              <span class="itemValue">2020-04 ~ 2020-08</span>
            </p>
            <div class="descItem">
              <div class="descLabel">工作内容：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、负责维护已上线的随手拍举报项目，并且根据不同城市的需求进行定制化开发新版本
                </p>
                <p class="descValue">
                  2、使用原生的微信小程序开发框架，熟悉其开发结构和模式
                </p>
                <p class="descValue">
                  3、掌握小程序开发构建部署完整的流程
                </p>
              </div>
            </div>
            <p class="teachItem">
              <span class="itemLabel">相关技术：</span>
              <span class="itemValue">
                原生微信小程序、腾讯地图、刷脸认证
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
                <span class="itemValue">项目的重构、新系统开发</span>
              </p>
            </div>
            <p class="teachItem">
              <span class="itemLabel">开发时间：</span>
              <span class="itemValue">2018-09 ~ 2019-02</span>
            </p>
            <div class="descItem">
              <div class="descLabel">工作内容：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、项目主要是给B端客户的众筹产品做预热推广活动，B端客户提交自己的产品，支付服务后，平台通过邮件，分享，平台展示等方式对众筹产品进行预热推广，B端客户可以登陆平台查看项目的推广情况。平台涉及管理后台及前端展示部分，后台使用vuejs的前后端分离技术，前台使用boostrap响应式框架
                </p>
                <p class="descValue">
                  2、负责项目需求的对接及开发计划安排与跟进
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
                <span class="itemValue">广发银行项目</span>
              </p>
              <p class="teachItem onelineItem">
                <span class="itemLabel">担任角色：</span>
                <span class="itemValue">web重构、二次开发</span>
              </p>
            </div>
            <p class="teachItem">
              <span class="itemLabel">开发时间：</span>
              <span class="itemValue">2016-08 ~ 2018-03</span>
            </p>
            <div class="descItem">
              <div class="descLabel">工作内容：</div>
              <div class="itemValue">
                <p class="descValue">
                  1、广发银行集中身份管理系统主要用于身份自动化管理，承接柜面外围系统和其他新系统，行员可通过该系统进行统一认证、应用单点登录、账号申请、权限控制、人员调动、工作流审批等操作
                </p>
                <p class="descValue">
                  2、参与产品的二次开发，负责restful风格的接口改造，编写jsp、Java、html、css代码，熟悉后台ssm框架的改造流程，参与前端框架的改造，涉及到浏览器的兼容性、响应式、性能调优方面的开发
                </p>
              </div>
            </div>
            <p class="teachItem">
              <span class="itemLabel">相关技术：</span>
              <span class="itemValue">
                Java、jsp、ligerui、layerui、js、ajax、jquery、html、css
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
        pdf.save("谢顶金求职简历.pdf");
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
    padding-top: 6px;
    font-size: 12px;
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
      background-color: #dbe3e5;
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
    padding: 16px;
    margin-bottom: 16px;
    border-radius: 6px;
    background-color: #dbe3e5;
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
    margin: 6px 3px 0 0;
    color: #222831;
  }
  
</style>