<template>
  <div class="recruiting">
    <div class="top-menu">
      <div class="top-menu-location">
        <span>您现在的位置：<router-link to="/" >首页</router-link>>招贤纳士>{{activeName}}</span>
      </div>
    </div>
    <div class="tabs">
      <el-tabs v-model="activeName">
        <el-tab-pane label="人才理念" name="人才理念">
          <label slot="label">&nbsp;&nbsp;&nbsp;人才理念</label>
          <div class="detailInner">
            <div class="talent-concept">
              <h4 class="title-ch">人才战略</h4>
              <h5 class="title-en">Talent Strategy</h5>
              <li><span class="orange">人才理念：人尽其才，才尽其用。</span></li>
              <li>充分发挥每个员工的长处，在合适的位置发挥最大的能量</li>
              <li><span class="orange">职业平台：相互提升，共享成就。</span></li>
              <li>优秀的员工是项目成功的关键，成功的项目是优秀人才的积淀</li>
              <li><span class="orange">薪酬福利：效率优先，兼顾公平。</span></li>
              <li>科学合理的薪酬体系和福利保障体系</li>
              <li><span class="orange">培训发展：打造学习型组织，多层级培训体系。</span></li>
              <li>多维度、多层级的培训体系，塑造复合型人才，让员工提供快速成长平台</li>
            </div>
            <div class="talent-concept">
              <h4 class="title-ch">发展平台</h4>
              <h5 class="title-en">Development Platform</h5>
              <li>与大师同行，跟随传奇，挑战传奇，成就传奇。</li>
              <li>成为行业顶尖团队一员，全方位体现个人能力。</li>
              <li>参与最前沿、最具影响力的项目，创造属于个人及团队的优秀产品。</li>
              <li>极具竞争力的企业环境，加速职业能力提升。</li>
            </div>
            <div class="talent-concept">
              <h4 class="title-ch">人才发展通道</h4>
              <h5 class="title-en">Talent Development Channel</h5>
              <div class="img-manager">
                <img src="./test.jpg"/>
              </div>
            </div>
          </div>
        </el-tab-pane>
        <el-tab-pane label="社会招聘" name="社会招聘">
          <label slot="label">社会招聘</label>
          <div class="detailInner">
            <!--<div class="list-items">-->
            <!--<h4 class="h4title">技术主管</h4>-->
            <!--<p class="time">岗位职责</p>-->
            <!--<li>1、熟悉国家相关设计规范及技术要求，负责项目设计进度及设计质量的协调、审查，参与项目各专业及施工图会审，参与各项目的技术交底</li>-->
            <!--<li>2、负责与设计单位协调沟通，技术交流工作</li>-->
            <!--<li>3、负责新技术、新产品、新材料、新工艺的运用推广</li>-->
            <!--<li>4、负责项目施工方案的技术审查</li>-->
            <!--<li>5、负责与政府相关部门的技术协调沟通工作</li>-->
            <!--<li>6、负责项目各专业技术衔接、分析及会审工作。</li>-->
            <!--<p class="time">任职要求</p>-->
            <!--<li>1、本科以上学历，结构、土木工程、建筑等相关专业</li>-->
            <!--<li>2、8年以上施工技术管理经验</li>-->
            <!--<li>3、具有中级以上职称</li>-->
            <!--<li>4、持有一级建造师、注册监理工程师、注册造价工程师等优先</li>-->
            <!--<li>5、具有结构设计经验，具备审查结构图纸的能力</li>-->
            <!--<li>6、熟悉房建、市政工程现行施工技术措施及施工方案的编审，熟悉现行施工相关技术规范、规程。</li>-->
            <!--</div>-->
            <div class="list-items">
              <h4 class="h4title">BIM项目经理</h4>
              <li class="list-first"><span class="to-bold">学历要求：</span>硕士学历以上</li>
              <li><span class="to-bold">工作经验：</span>5年以上</li>
              <p class="time">能力要求</p>
              <li>1、熟练掌握BIM相关设计与模拟软件；熟悉工程建设基本流程；</li>
              <li>2、建筑、结构、土木、机电、项目管理、计算机等相关专业；</li>
              <li>3、有实际大型项目BIM应用经验；有一年以上设计院建筑、结构等专业设计或工地现场工作经历者优先；</li>
              <li>4、有国外留学经历或国外工作经验者优先；</li>
              <li>5、持有工信部或图学会认证的BIM证书。</li>
            </div>
            <div class="list-items">
              <h4 class="h4title">BIM高级工程师（机电、结构、建筑、造价）</h4>
              <li class="list-first"><span class="to-bold">学历要求：</span>统招本科以上学历，硕士学历优先</li>
              <li><span class="to-bold">工作经验：</span>1年以上</li>
              <p class="time">能力要求</p>
              <li>1、熟练掌握BIM相关设计与模拟软件；</li>
              <li>2、建筑、结构、土木、机电、项目管理、计算机等相关专业；</li>
              <li>3、有实际大型项目BIM应用经验；有一年以上设计院建筑、结构等专业设计或工地现场工作经历者优先；</li>
              <li>4、有国外留学经历或国外工作经验者优先；</li>
              <li>5、乐于在BIM领域做前瞻性研究与推广工作，持有工信部或图学会认证的BIM证书者优先。</li>
            </div>
            <div class="list-items">
              <h4 class="h4title">BIM大数据工程师</h4>
              <li class="list-first"><span class="to-bold">学历要求：</span>统招本科以上学历，硕士学历优先</li>
              <li><span class="to-bold">工作经验：</span>1年以上</li>
              <p class="time">能力要求</p>
              <li>1、熟悉C/C++编程，有UI前端开发经验和大型系统开发背景；熟悉数据库原理和常用性能优化技术，以及NoSQL原理、使用场景以及限制；熟悉Pylons、CherryPy等框架；熟悉爬虫、搜索引擎技术；</li>
              <li>2、计算机及软件类相关专业；</li>
              <li>3、有国外留学经历或国外工作经验者优先；</li>
              <li>4、持有工信部、图学会认证的BIM证书且具备BIM技术技能者优先。</li>
            </div>
            <div class="list-items">
              <h4 class="h4title">平台开发工程师</h4>
              <li class="list-first"><span class="to-bold">学历要求：</span>统招本科以上学历，硕士学历优先</li>
              <li><span class="to-bold">工作经验：</span>3年以上</li>
              <p class="time">能力要求</p>
              <li>1、熟悉java数据库编程，精通主流的软件框架(Spring、hibernate、Struts)，熟悉OSGi；</li>
              <li>2、计算机及软件类相关专业；</li>
              <li>3、有平台开发工作经验；</li>
              <li>4、持有工信部、图学会认证的BIM证书且具备BIM技术技能者优先。</li>
            </div>
            <div class="list-items">
              <h4 class="h4title">项目经理</h4>
              <li class="list-first"><span class="to-bold">学历要求：</span>统招本科以上学历，硕士学历优先</li>
              <li><span class="to-bold">工作经验：</span>8年以上</li>
              <p class="time">能力要求</p>
              <li>1、熟悉工程建设基本流程；</li>
              <li>2、建筑、土木工程、工程管理及相关专业；</li>
              <li>3、中级工程师以上职称，一级建造师或其他工程行业注册类证书者优先；</li>
              <li>4、担任过类似项目的项目经理或副经理；</li>
              <li>5、持有工信部、图学会认证的BIM证书且具备BIM技术技能者优先。</li>
            </div>
            <div class="list-items">
              <h4 class="h4title">项目管理工程师</h4>
              <li class="list-first"><span class="to-bold">学历要求：</span>统招本科以上学历，硕士学历优先</li>
              <li><span class="to-bold">工作经验：</span>5年以上</li>
              <p class="time">能力要求</p>
              <li>1、熟悉工程建设基本流程；</li>
              <li>2、建筑、土木工程、工程管理及相关专业；</li>
              <li>3、担任过类似项目的项目管理工程师；</li>
              <li>4、持有工信部、图学会认证的BIM证书且具备BIM技术技能者优先。</li>
            </div>
            <div class="list-items">
              <h4 class="h4title">总监理工程师</h4>
              <li class="list-first"><span class="to-bold">学历要求：</span>统招本科以上学历，硕士学历优先</li>
              <li><span class="to-bold">工作经验：</span>8年以上</li>
              <p class="time">能力要求</p>
              <li>1、较强的适应能力、沟通能力和综合协调组织能力；</li>
              <li>2、理工科专业毕业，特别优秀者可放宽至大专以上学历；</li>
              <li>3、有建筑、市政相关业务经验，具备中级、高级职称优先；</li>
              <li>4、持有国家注册监理工程师证书；</li>
              <li>5、持有工信部、图学会认证的BIM证书且具备BIM技术技能者优先。</li>
            </div>
            <div class="list-items">
              <h4 class="h4title">总监代表/专业监理工程师</h4>
              <li class="list-first"><span class="to-bold">学历要求：</span>统招本科以上学历，硕士学历优先</li>
              <li><span class="to-bold">工作经验：</span>5年以上</li>
              <p class="time">能力要求</p>
              <li>1、较强的适应能力、沟通能力和综合协调组织能力；</li>
              <li>2、理工科专业毕业，特别优秀者可放宽至大专以上学历；</li>
              <li>3、有建筑、市政相关业务经验，具备中级以上职称，高级以上职称优先；</li>
              <li>4、持有重庆市监理工程师证书，持有国家注册监理工程师证书者优先；</li>
              <li>5、持有工信部、图学会认证的BIM证书且具备BIM技术技能者优先。</li>
            </div>
            <div class="list-items">
              <h4 class="h4title">监理员</h4>
              <li class="list-first"><span class="to-bold">学历要求：</span>大专及以上</li>
              <li><span class="to-bold">工作经验：</span>1年以上</li>
              <p class="time">能力要求</p>
              <li>1、较强的适应能力、沟通能力和综合协调组织能力；</li>
              <li>2、工程相关专业；</li>
              <li>3、有超过2年相关工作经验者优先；</li>
              <li>4、有助理工程师或监理员证为佳； </li>
              <li>5、持有工信部、图学会认证的BIM证书且具备BIM技术技能者优先。</li>
            </div>
            <p>应聘者请将个人简历发邮件至招聘邮箱
              <a href="mailto:lijiakrystal@tylin.com.cn">lijiakrystal@tylin.com.cn</a>
              ，为确保应聘资料的准确收集，请在邮件标题中标注"姓名+应聘职位"；当我们收到您的资料后，会在1-2周内与您联系，
              如未与您联系，证明您的资料已进入我们的人才储备库，当我们的岗位需要时，会再与您取得联系。
            </p>
          </div>
        </el-tab-pane>
        <el-tab-pane label="校园招聘" name="校园招聘">
          <label slot="label">校园招聘&nbsp;&nbsp;&nbsp;&nbsp;</label>
          <div class="detailInner list-two">
            <!--<div class="list-items">-->
              <!--<div class="detail-title">实现自我价值与能力提升的新领地</div>-->
              <!--<li>1、与大师同行，跟随传奇，挑战传奇，成就传奇</li>-->
              <!--<li>2、成为行业顶尖团队一员，全方位体现个人能力</li>-->
              <!--<li>3、参与最前沿、最具影响力的项目，创造属于个人及团队的优秀产品</li>-->
              <!--<li>4、极具竞争力的企业环境，加速职业能力提升</li>-->
            <!--</div>-->
            <div class="list-items items-jobs">
              <p class="h4title">招聘岗位</p>
              <li>1、项目管理工程师</li>
              <li>2、研发工程师</li>
              <li>3、BIM工程师</li>
              <li>4、模型工程师</li>
              <li>5、图形工程师</li>
              <li>6、平台开发工程师</li>
              <li>7、BIM大数据软件工程师</li>
              <li>8、市场助理</li>
            </div>
            <div class="list-items">
              <p class="h4title">招聘需求</p>
              <li>建筑、 结构、土木、机电、 环境工程、项目管理、工程力学、 机械工程、信息工程、智能科学、 软件工程、计算机</li>
            </div>
            <div class="list-items">
              <p class="h4title">个人素质</p>
              <li>1、具有良好的学习能力、沟通协调能力（担任社团领导的人员优先）;</li>
              <li>2、 硕士研究生毕业（优秀毕业生可放宽至本科学历），博士更佳，英语熟练掌握运用，具有留学背景或国内外相关BIM学习经历的优先考虑；</li>
              <li>3、所有岗位同时接受实习生，2020届、2021届毕业的硕士、博士（可长期实习者优先）。</li>
            </div>
            <p>应聘者请将个人简历发邮件至招聘邮箱
              <a href="mailto:lijiakrystal@tylin.com.cn">lijiakrystal@tylin.com.cn</a>
              ，为确保应聘资料的准确收集，请在邮件标题中标注"姓名+应聘职位"；当我们收到您的资料后，会在1-2周内与您联系，
              如未与您联系，证明您的资料已进入我们的人才储备库，当我们的岗位需要时，会再与您取得联系。
            </p>
          </div>
        </el-tab-pane>
      </el-tabs>
    </div>
  </div>
</template>

<script>
    export default {
        name: "recruiting",
      data() {
        return {
          activeName: '人才理念'
        };
      },
      mounted() {

      },
    }
</script>

<style  lang="less">
  .recruiting .top-menu {
    margin-top: 65px;
    background: url("./recruiting.jpg") center;
    height: 330px;
  }
  .recruiting .top-menu .top-menu-location {
    color: #fff;
    border-radius: 5px;
    width: 1280px;
    text-align: right;
    margin: 0 auto;
    padding-top: 230px;
    span {
      background-color: #6a6b6da6;
      padding: 5px;
      border-radius: 3px;
    }
    a {
      color: #fff;
    }
  }
  .recruiting .el-tabs__nav {
    margin: 16px 0;
    text-align: center;
    width: 1280px;
  }
  .recruiting .el-tabs__nav-wrap::after {
    background-color: #fff;
  }
  .recruiting .el-tabs__item.is-active {
    color: #fff;
    background-color: #D86614;
    border-radius: 7px;
  }
  .recruiting .el-tabs__item:hover {
    cursor: pointer;
    color: #D86614;
  }
  .recruiting .el-tabs__active-bar {
    background-color:#fff;
  }
  .recruiting .el-tabs__item.is-active:hover {
    color: #fff;
  }
  .recruiting .el-tabs__item {
    padding: 0 15px;
    margin: 5px 20px;
    font-size: 16px;
  }
  .recruiting .tabs {
    width: 1280px;
    margin: 0px auto;
  }
  .recruiting {
    .detail-title {
      font-size: 16px;
      text-align: center;
      margin-bottom: 20px;
      font-weight: bold;
    }
    .detailInner {
      background-color: #F2F2F2;
      padding: 60px 67px;
    }
    .h4title {
      padding-left: 10px;
      border-left: 3px solid #FF9955;
      color: #3f3f40;
      font-size: 15px;
      line-height: 18px;
      display: block;
      font-weight: bold;
    }
    .time {
      font-size: 14px;
      color: #3F3F40;
      line-height: 50px;
      margin-left: 25px;
    }
    li {
      font-size: 14px;
      color: rgb(140, 141, 144);
      line-height: 30px;
      text-align: justify;
      white-space: normal;
      list-style: none;
      margin-left: 25px;
    }
    .list-items {
      overflow: hidden;
      margin-bottom: 20px;
      border-bottom: 1px dotted #cccdd1;
      padding-bottom: 20px;
    }
    .list-two {
      .h4title {
        margin-bottom: 14px;
      }

    }
    .talent-concept {
      margin-bottom: 50px;
     .title-ch {
       color: #000;
        font-size: 23px;
       line-height: 28px;
       margin-left: -10px;
       padding-left: 10px;
       border-left: 6px #FF9955 solid;
     }
      .title-en {
        font-size: 12px;
        line-height: 30px;
      }
      li {
        line-height: 45px;
        font-size: 14px;
        .orange {
          display: inline-block;
          font-weight: bold;
          color: #666;
          /*color: #000;*/
          /*margin-right: 30px;*/
        }
      }
      .img-manager {
        margin-top: -10px;
        img {
          width: 800px;
          margin-top: 60px;
        }
      }
    }
    .list-first {
      margin-top: 15px;
    }
    .to-bold {
      color: #3F3F40;
    }
  }
</style>
