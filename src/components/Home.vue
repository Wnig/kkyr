<template>
  <div class="home">
  	<div class="pc">
      <div class="top"><img src="../assets/pcfhdb@3x.svg" alt=""></div>
      <div class="selection selection-1">
        <div class="con">
          <app-header></app-header>
            <div class="cont">
              <div class="cont_">
                <div class="tit">
                  用工服务，就找<strong>快快用人！</strong><br/>服务<strong>更快、更省、更靠谱</strong>
                </div>
                <div class="down-btn" @click="slideDown">
                  <div class="down"></div>
                </div>
              </div>
            </div>
        </div>
      </div>
      <div class="selection selection-2">
        <div class="con">
          <img class="left-img" src="../assets/pcbeij2.jpg" alt="">
          <div class="cont">
            <h3>关于快快用人</h3>
            <p>快快用人是一个综合性的用工服务平台，集用工信息发布、约单、O2O上门服务功能于一体，提供周边生活服务和专业技能服务，服务无所不有，尽在快快用人。</p>
            <p>基于LBS定位功能，用户发布用工需求后，需求随即推送给周边的服务提供者，从而得到响应。快快用人建立需求者与服务者一对一连接，致力为广大用户建立高效率、高品质、规范化的服务平台。</p>
            <p>打开平台，让您的各种技能有用武之地；足不出户，让您的任何需求能得到满足。</p>
            <p>用工服务，就找快快用人！服务更快、更省、更靠谱。</p>
            <p class="dis"><strong>快快用人</strong>——综合快速用工服务平台！为有技能、有时间的你提供创造价值的平台；为需要帮助的你提供找人的快速通道。</p>
          </div>
        </div>
      </div>
      <div class="selection selection-3">
        <div class="con">
          <div class="cont">
            <div class="tit">平台展示</div>
            <div class="cont_">
              <div class="list_img">
                <div class="list_div">
                  <img src="../assets/img_01.png" alt="">
                  <p>接单</p>
                </div>
                <div class="list_div">
                  <img src="../assets/img_02.png" alt="">
                  <p>消息</p>
                </div>
                <div class="list_div">
                  <img src="../assets/img_03.png" alt="">
                  <p>提现</p>
                </div>
                <div class="list_div">
                  <img src="../assets/img_04.png" alt="">
                  <p>个人信息</p>
                </div>
                <div class="list_div">
                  <img src="../assets/img_05.png" alt="">
                  <p>我的</p>
                </div>
                <div class="list_div">
                  <img src="../assets/img_06.png" alt="">
                  <p>我的余额</p>
                </div>
              </div>
              <div class="bigimg">
                <img src="../assets/img_07.jpg" alt="">
                <p>订单列表</p> 
              </div>
              <div class="video">
                <video src="../assets/video.mp4" autoplay="autoplay" loop="loop"></video>
                <p>视频演示</p>
              </div>
            </div>
          </div>  
        </div>
      </div>
      <div class="selection selection-4">
        <div class="con">
          <div class="con_">
            <div class="tit">平台亮点</div>
            <div class="list_con">
              <div class="list_div list_div_01">
                <div class="list_div_">
                  <i class="icon-pctoum3x"></i>
                  <div class="bor">
                    <div class="yuan"></div>
                  </div>
                  <p>1、低抽佣，价格透明</p>
                </div>
              </div>
              <div class="list_div list_div_02">
                <div class="list_div_">
                  <i class="icon-pcleimu3x"></i>
                  <div class="bor">
                    <div class="yuan"></div>
                  </div>
                  <p>2、多类目，类目齐全</p>
                </div>
              </div>
              <div class="list_div list_div_03">
                <div class="list_div_">
                  <i class="icon-pcjineng3x"></i>
                  <div class="bor">
                    <div class="yuan"></div>
                  </div>
                  <p>3、高标准，技能专业</p>
                </div>
              </div>
              <div class="list_div list_div_04">
                <div class="list_div_">
                  <i class="icon-pcbaoz3x"></i>
                  <div class="bor">
                    <div class="yuan"></div>
                  </div>
                  <p>4、有保障，评价监管</p>
                </div>
              </div>
            </div>
          </div>
          <div class="bg"></div>
        </div>
      </div>
      <div class="selection selection-5">
        <div class="con">
          <div class="cont">
            <h3>行业现状</h3>
            <p>用工行业用工招工难，仍局限于招聘平台、招聘网站，需求方和服务方没有建立起快速有效的对接渠道。平台、中介等薪资递减拖欠问题严重，导致人才劳动力流失，用工困难，严重损害双方的利益。</p>
            <p>而现实中，企业、家庭等对各类专业性需求用工、家政用工、职位招聘等需求日益增加，要求也日益提高，继续一个快速有效的综合服务平台满足各类用工需求。同时，在人才技能日益丰富的当下，许多人才、工人专职于某个单位、公司、平台等，拥有多项技能和拥有富余时间的人无法充分发挥效益，导致资源浪费，急需一个平台充分发挥才能，利用自身技能和富余时间创造更多价值和收益。</p>
          </div>
        </div>
      </div>
      <div class="selection selection-6">
        <div class="con">
          <div class="cont">
            <div class="tit">快快用人解决了什么痛点问题？</div>
            <div class="list_con">
              <div class="bor"></div>
              <div class="list_con_">
                <div class="list_div">
                  <div class="p">
                    <strong>用工招工困难</strong><p>目前大部分用工、应聘局限于招聘平台及各大招聘网站，不能充分的配置人力资源，快快用人服务平台为雇主和工人提供了直接的对接平台，大大提高了招工效率；</p>
                  </div>
                </div>
                <div class="list_div">
                  <div class="p">
                    <strong>薪资递减拖欠</strong><p>随着市场经济的发展，生活成本越来越高，然而薪资增长速度远远赶不上市场经济的高速发展，平台佣金越来越高，薪资结算周期长。快快用人平台无差价，低抽佣，佣金直接进入用户账户，快捷高回报。</p>
                  </div>
                </div>
                <div class="list_div">
                  <div class="p">
                    <strong>人力资源浪费</strong><p>家政公司、中介企业、包工头等常规用工渠道的中间环节，薪资低、抽佣高、结款周期长等，严重损害出工一方的合法权益，快快用人平台没有中间商赚差价，抽佣比例低，用工方和出工方直接对接，需求明确效率高；</p>
                  </div>
                </div>
                <div class="list_div">
                  <div class="p">
                    <strong>中间商赚差价</strong><p>各工种基本为全职岗位，很多人有富足的业余时间和多项技能闲置，而许多需要单项帮助的单位和个人来说，计时计件的服务帮助无处寻找。快快作为用工信息发布平台，解决了资源闲置浪费和需求短缺的双重问题。</p>
                  </div>
                </div>
                <div class="list_div">
                  <div class="p">
                    <strong>用工地域局限</strong><p>家政公司、中介企业均属于当地性服务机构，服务范围有很大的局限性，快快用人用工信息服务平台，面向所有区域用户，只要有需求，都可提供服务。</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- <div class="selection selection-7">
        <div class="con">
          <div class="cont">
            <div class="tit">竞品分析</div>
            <p>快快用人 <strong>vs</strong> 到位 <strong>vs</strong> 好慷在线</p>
            <img src="../assets/pcbiaoge@2x.png" alt="">
          </div>
        </div>
      </div> -->
      <div class="selection selection-8">
        <div class="con">
          <div class="cont">
            <div class="tit">运营拓扑图</div>
            <img src="../assets/pcyyjkkk@2x.png" alt="">
          </div>
        </div>
      </div>
      <div class="selection selection-9">
        <div class="con">
          <img class="img" src="../assets/pcbeij8.jpg" alt="">
          <div class="content">
            <div class="tit">服务支持</div>
            <div class="list_con">
              <div class="list_div">
                <h3>（一）产品使用培训</h3>
                <div class="bor"></div>
                <p>指派专人进行产品的现场使用培训，保障每一位客户都能正常使用</p>
              </div>
              <div class="list_div list_div_right">
                <h3>（二）品牌包装及推广</h3>
                <div class="bor"></div>
                <p>总部通过发布会、交流会、品牌广告曝光等方式进行品牌推广，扩大品牌知名度</p>
              </div>
              <div class="list_div">
                <h3>（三）7*24小时客户服务</h3>
                <div class="bor"></div>
                <p>客服热线全天候解决用户系统和硬件问题，解决客户紧急问题</p>
              </div>
              <div class="list_div list_div_right">
                <h3>（四）后期运维复盘</h3>
                <div class="bor"></div>
                <p>维护人员上门复盘部署系统运维情况，并给出优化建议</p>
              </div>
              <div class="list_div">
                <h3>（五）季度健康检查</h3>
                <div class="bor"></div>
                <p>定期对平台系统全面检查，保障系统稳定运行</p>
              </div>
              <div class="list_div list_div_right">
                <h3>（六）年度系统升级</h3>
                <div class="bor"></div>
                <p>根据运营需要和客户需求，对系统进行定期升级服务</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-10">
        <div class="con">
          <img class="img" src="../assets/pcbeij9.jpg" alt="">
          <div class="content">
            <div class="tit">背景支持</div>
            <p>厦门市佰中晟传媒有限公司成立于2017年，是一家专注于互联网信息服务的企业。公司致力于人力资源共享的服务平台，融合了社交、移动互联网、大数据等主流科技，将为无数的服务提供者与需求者搭建桥梁，促成交易。</p>
            <p>服务需求者一键发布任务，平台快速精准匹配个性化解决方案；服务提供者一键接单，把自己的智力、经验、技能等转化为价值。</p>
            <img src="../assets/pcbeij10.jpg" alt="">
          </div>
        </div>
        <app-footer></app-footer>
      </div>
      <!-- <div class="selection selection-11">
        <div class="con">
          <div class="con_">
            <div class="tit">招商政策</div>
            <p class="p">抽佣方式：代理商抽佣=成交价*0.05*0.6</p>
            <p class="p">代理政策：</p>
            <div class="list_con">
              <div class="list_div list_div_a">
                <div class="list_div_">
                  <div class="img">
                    <img src="../assets/pczy1@3x.svg" alt="">
                  </div>
                  <div class="content">
                    <h3>A级代理</h3>
                    <p>县区人口80-120万，代理费12万元</p>
                  </div>
                </div>
              </div>
              <div class="list_div list_div_b">
                <div class="list_div_">
                  <div class="img">
                    <img src="../assets/pczy2@3x.svg" alt="">
                  </div>
                  <div class="content">
                    <h3>B级代理</h3>
                    <p>县区人口50-80万，代理费8万元</p>
                  </div>
                </div>
              </div>
              <div class="list_div list_div_c">
                <div class="list_div_">
                  <div class="img">
                    <img src="../assets/pczy3@3x.svg" alt="">
                  </div>
                  <div class="content">
                    <h3>C级代理</h3>
                    <p>县区人口10-50万，代理费5万元</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-12">
        <div class="con">
          <div class="con_">
            <div class="tit">收益测算</div>
            <p class="dis">假设人工工价为200元/天，日成交1000单<br/>
            日成交额=1000单*200元=200000元
            </p>
            <div class="list_con">
              <div class="list_div">
                <div class="list_div_">
                  <img src="../assets/pcnian@3x.svg" alt="">
                  <p>日抽佣收益=200000*0.05*0.6=6000元</p>
                </div>
              </div>
              <div class="list_div">
                <div class="list_div_">
                  <img src="../assets/pcyue@3x.svg" alt="">
                  <p>月抽佣收益=6000元*30天=180000元</p>
                </div>
              </div>
              <div class="list_div">
                <div class="list_div_">
                  <img src="../assets/pcri@3x.svg" alt="">
                  <p>年抽佣收益=180000元*12=2160000元</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <app-footer></app-footer>
      </div> -->
	  </div>
  	<div class="mob">
      <div class="selection selection-1">
        <div class="con">
          <app-header></app-header>
            <div class="cont">
              <div class="cont_">
                <div class="tit">
                  用工服务，就找<strong>快快用人！</strong><br/>服务<strong>更快、更省、更靠谱</strong>
                </div>
                <div class="down-btn" @click="slideDown">
                  <div class="down"></div>
                </div>
              </div>
            </div>
        </div>
      </div>
      <div class="selection selection-2">
        <div class="con">
          <div class="con_">
            <img class="left-img" src="../assets/pcbeij2.jpg" alt="">
            <div class="cont">
              <h3>关于快快用人</h3>
              <p>快快用人是一个综合性的用工服务平台，集用工信息发布、约单、O2O上门服务功能于一体，提供周边生活服务和专业技能服务，服务无所不有，尽在快快用人。</p>
              <p>基于LBS定位功能，用户发布用工需求后，需求随即推送给周边的服务提供者，从而得到响应。快快用人建立需求者与服务者一对一连接，致力为广大用户建立高效率、高品质、规范化的服务平台。</p>
              <p>打开平台，让您的各种技能有用武之地；足不出户，让您的任何需求能得到满足。</p>
              <p>用工服务，就找快快用人！服务更快、更省、更靠谱。</p>
              <p class="dis"><strong>快快用人</strong>——综合快速用工服务平台！为有技能、有时间的你提供创造价值的平台；为需要帮助的你提供找人的快速通道。</p>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-3">
        <div class="con">
          <div class="cont">
            <div class="tit">平台展示</div>
            <div id="swiper01" class="swiper-container clearfix">
              <div class="swiper-wrapper">
                <div class="swiper-slide">
                  <img src="../assets/img_01.png" alt="">
                </div>
                <div class="swiper-slide">
                  <img src="../assets/img_02.png" alt="">
                </div>
                <div class="swiper-slide">
                  <img src="../assets/img_03.png" alt="">
                </div>
                <div class="swiper-slide">
                  <img src="../assets/img_04.png" alt="">
                </div>
                <div class="swiper-slide">
                  <img src="../assets/img_05.png" alt="">
                </div>
                <div class="swiper-slide">
                  <img src="../assets/img_06.png" alt="">
                </div>
              </div>
            </div>
          </div>  
        </div>
      </div>
      <div class="selection selection-4">
        <div class="con">
          <div class="con_">
            <div class="tit">平台亮点</div>
            <div class="list_con">
              <div class="list_div list_div_01">
                <i class="icon-pctoum3x"></i>
                <p>1、低抽佣，价格透明</p>
              </div>
              <div class="list_div list_div_02">
                <i class="icon-pcleimu3x"></i>
                <p>2、多类目，类目齐全</p>
              </div>
              <div class="list_div list_div_03">
                <i class="icon-pcjineng3x"></i>
                <p>3、高标准，技能专业</p>
              </div>
              <div class="list_div list_div_04">
                <i class="icon-pcbaoz3x"></i>
                <p>4、有保障，评价监管</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-5">
        <div class="con">
          <div class="cont">
            <h3>行业现状</h3>
            <p>用工行业用工招工难，仍局限于招聘平台、招聘网站，需求方和服务方没有建立起快速有效的对接渠道。平台、中介等薪资递减拖欠问题严重，导致人才劳动力流失，用工困难，严重损害双方的利益。</p>
            <p>而现实中，企业、家庭等对各类专业性需求用工、家政用工、职位招聘等需求日益增加，要求也日益提高，继续一个快速有效的综合服务平台满足各类用工需求。同时，在人才技能日益丰富的当下，许多人才、工人专职于某个单位、公司、平台等，拥有多项技能和拥有富余时间的人无法充分发挥效益，导致资源浪费，急需一个平台充分发挥才能，利用自身技能和富余时间创造更多价值和收益。</p>
          </div>
        </div>
      </div>
      <div class="selection selection-6">
        <div class="con">
          <div class="cont">
            <div class="tit">快快用人解决了什么痛点问题？</div>
            <div class="list_con">
              <div class="list_con_">
                <div class="list_div">
                  <div class="p">
                    <strong>用工招工困难</strong>
                    <div class="line"></div>
                    <p>目前大部分用工、应聘局限于招聘平台及各大招聘网站，不能充分的配置人力资源，快快用人服务平台为雇主和工人提供了直接的对接平台，大大提高了招工效率；</p>
                  </div>
                </div>
                <div class="list_div">
                  <div class="list_div_">
                    <div class="p">
                      <strong>薪资递减拖欠</strong>
                      <div class="line"></div>
                      <p>随着市场经济的发展，生活成本越来越高，然而薪资增长速度远远赶不上市场经济的高速发展，平台佣金越来越高，薪资结算周期长。快快用人平台无差价，低抽佣，佣金直接进入用户账户，快捷高回报。</p>
                    </div>
                  </div>
                </div>
                <div class="list_div">
                  <div class="list_div_">
                    <div class="p">
                      <strong>人力资源浪费</strong>
                      <div class="line"></div>
                      <p>家政公司、中介企业、包工头等常规用工渠道的中间环节，薪资低、抽佣高、结款周期长等，严重损害出工一方的合法权益，快快用人平台没有中间商赚差价，抽佣比例低，用工方和出工方直接对接，需求明确效率高；</p>
                    </div>
                  </div>
                </div>
                <div class="list_div">
                  <div class="list_div_">
                    <div class="p">
                      <strong>人力资源浪费</strong>
                      <div class="line"></div>
                      <p>家政公司、中介企业、包工头等常规用工渠道的中间环节，薪资低、抽佣高、结款周期长等，严重损害出工一方的合法权益，快快用人平台没有中间商赚差价，抽佣比例低，用工方和出工方直接对接，需求明确效率高；</p>
                    </div>
                  </div>
                </div>
                <div class="list_div">
                  <div class="list_div_">
                    <div class="p">
                      <strong>中间商赚差价</strong>
                      <div class="line"></div>
                      <p>各工种基本为全职岗位，很多人有富足的业余时间和多项技能闲置，而许多需要单项帮助的单位和个人来说，计时计件的服务帮助无处寻找。快快作为用工信息发布平台，解决了资源闲置浪费和需求短缺的双重问题。</p>
                    </div>
                  </div>
                </div>
                <div class="list_div">
                  <div class="list_div_">
                    <div class="p">
                      <strong>用工地域局限</strong>
                      <div class="line"></div>
                      <p>家政公司、中介企业均属于当地性服务机构，服务范围有很大的局限性，快快用人用工信息服务平台，面向所有区域用户，只要有需求，都可提供服务。</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- <div class="selection selection-7">
        <div class="con">
          <div class="cont">
            <div class="tit">竞品分析</div>
            <p>快快用人 <strong>vs</strong> 到位 <strong>vs</strong> 好慷在线</p>
            <img src="../assets/Group.png" alt="">
          </div>
        </div>
      </div> -->
      <div class="selection selection-8">
        <div class="con">
          <div class="cont">
            <div class="tit">运营拓扑图</div>
            <img src="../assets/ydyykkk.png" alt="">
          </div>
        </div>
      </div>
      <div class="selection selection-9">
        <div class="con">
          <div class="content">
            <div class="tit">服务支持</div>
            <div class="list_con">
              <div class="list_div">
                <h3>（一）产品使用培训</h3>
                <div class="bor"></div>
                <p>指派专人进行产品的现场使用培训，保障每一位客户都能正常使用</p>
              </div>
              <div class="list_div list_div_right">
                <h3>（二）品牌包装及推广</h3>
                <div class="bor"></div>
                <p>总部通过发布会、交流会、品牌广告曝光等方式进行品牌推广，扩大品牌知名度</p>
              </div>
              <div class="list_div">
                <h3>（三）7*24小时客户服务</h3>
                <div class="bor"></div>
                <p>客服热线全天候解决用户系统和硬件问题，解决客户紧急问题</p>
              </div>
              <div class="list_div list_div_right">
                <h3>（四）后期运维复盘</h3>
                <div class="bor"></div>
                <p>维护人员上门复盘部署系统运维情况，并给出优化建议</p>
              </div>
              <div class="list_div">
                <h3>（五）季度健康检查</h3>
                <div class="bor"></div>
                <p>定期对平台系统全面检查，保障系统稳定运行</p>
              </div>
              <div class="list_div list_div_right">
                <h3>（六）年度系统升级</h3>
                <div class="bor"></div>
                <p>根据运营需要和客户需求，对系统进行定期升级服务</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-10">
        <div class="con">
          <div class="con_">
            <img class="img" src="../assets/ydbeij14.jpg" alt="">
            <div class="content">
              <div class="tit">背景支持</div>
              <p>厦门市佰中晟传媒有限公司成立于2017年，是一家专注于互联网信息服务的企业。公司致力于人力资源共享的服务平台，融合了社交、移动互联网、大数据等主流科技，将为无数的服务提供者与需求者搭建桥梁，促成交易。</p>
              <p>服务需求者一键发布任务，平台快速精准匹配个性化解决方案；服务提供者一键接单，把自己的智力、经验、技能等转化为价值。</p>
            </div>
          </div>
        </div>
        <app-footer></app-footer>
      </div>
      <!-- <div class="selection selection-11">
        <div class="con">
          <div class="con_">
            <div class="tit">招商政策</div>
            <p class="p">抽佣方式：代理商抽佣=成交价*0.05*0.6</p>
            <p class="p">代理政策：</p>
            <div id="swiper02" class="swiper-container clearfix">
              <div class="swiper-wrapper">
                <div class="swiper-slide">
                  <div class="list_div list_div_a">
                    <div class="list_div_">
                      <div class="img">
                        <img src="../assets/pczy1@3x.svg" alt="">
                      </div>
                      <div class="content">
                        <h3>A级代理</h3>
                        <p>县区人口80-120万，代理费12万元</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="swiper-slide">
                  <div class="list_div list_div_b">
                    <div class="list_div_">
                      <div class="img">
                        <img src="../assets/pczy2@3x.svg" alt="">
                      </div>
                      <div class="content">
                        <h3>B级代理</h3>
                        <p>县区人口50-80万，代理费8万元</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="swiper-slide">
                  <div class="list_div list_div_c">
                    <div class="list_div_">
                      <div class="img">
                        <img src="../assets/pczy3@3x.svg" alt="">
                      </div>
                      <div class="content">
                        <h3>C级代理</h3>
                        <p>县区人口10-50万，代理费5万元</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-12">
        <div class="con">
          <div class="con_">
            <div class="tit">收益测算</div>
            <p class="dis">假设人工工价为200元/天，日成交1000单<br/>
            日成交额=1000单*200元=200000元
            </p>
            <div class="list_con">
              <div class="list_div">
                <div class="list_div_">
                  <img src="../assets/pcnian@3x.svg" alt="">
                  <p>日抽佣收益=200000*0.05*0.6=6000元</p>
                </div>
              </div>
              <div class="list_div">
                <div class="list_div_">
                  <img src="../assets/pcyue@3x.svg" alt="">
                  <p>月抽佣收益=6000元*30天=180000元</p>
                </div>
              </div>
              <div class="list_div">
                <div class="list_div_">
                  <img src="../assets/pcri@3x.svg" alt="">
                  <p>年抽佣收益=180000元*12=2160000元</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <app-footer></app-footer>
      </div> -->
    </div>
  </div>
</template>

<script>
import Header from './Header'
import Footer from './Footer'
export default {
  name: 'Home',
  data () {
    return {
    	selShow: false,
    }
  },
  created() {

  },
  methods: {
    slideDown() {
      let downHeight = document.documentElement.clientHeight || document.body.clientHeight;
      window.scrollTo(0, downHeight);
      this.slideShow = true;
    },
  },
  components: {
    'app-header': Header,
    'app-footer': Footer
  },
  mounted() {

  	$('.img-con img').on('click', function() {
  		var ind = $(this).index() + 1;
  		var src = $(this).siblings().attr('src');
  		$('.main-img').attr('src', src);
  	});

  	// 返回顶部
    $('.top').on('click', function() {
    	$('html, body').animate({scrollTop: '0px'}, 800);
    });

  	$(window).scroll(function() {
	　　 var scrollTop = $(this).scrollTop();
	　　 var scrollHeight = $(document).height();
	　　 var windowHeight = $(this).height();

  		if(scrollTop < scrollHeight / 9) {
  			$('.top').css({
  				'display': 'none'
  			});
  		} else {
  			$('.top').css({
  				'display': 'block'
  			});
  		}
  	});

    let swiper = new Swiper('#swiper01', {
      loop: 1,
      autoplay: 3000,
      autoplayDisableOnInteraction : false,
      slidesPerView: 1,
      spaceBetween: 0,
      speed: 3000,
      releaseOnEdges: true,
      paginationClickable: true,
    });

    let swiper02 = new Swiper('#swiper02', {
      loop: 1,
      autoplay: 3000,
      autoplayDisableOnInteraction : false,
      slidesPerView: 1,
      spaceBetween: 0,
      speed: 3000,
      releaseOnEdges: true,
      paginationClickable: true,
    });


  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  
  /*selection-1*/
	.selection-1 {
    background: url('../assets/PCbeijing1.jpg') center center no-repeat;
    background-size: cover;
  }
  .selection-1 .con {

  }
  .selection-1 .cont {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 50vh;
  }
  
  .selection-1 .tit {
    font-family: PingFangSC-Semibold;
    font-size: 3.13vw;
    color: #FFFFFF;
    text-align: center;
    line-height: 5.89vw;
  }
  .selection-1 .tit strong {
    font-family: PingFangSC-Semibold;
    font-size: 4.17vw;
    color: #FF972C;
    text-align: center;
    line-height: 5.89vw;
  }
  
  /*selection-2*/
  .selection-2 {

  }
  .selection-2 .con {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
  .selection-2 .left-img {
    width: 46.46vw;
    height: 49.38vw;
    margin-right: 6.56vw;
  }
  .selection-2 .cont {
    width: 34.58vw;
  }
  .selection-2 .cont h3 {
    margin-bottom: 6.67vh;
    font-family: PingFangSC-Medium;
    font-size: 2.08vw;
    color: #000000;
  }
  .selection-2 .cont p {
    margin-bottom: 2.41vh;
    opacity: 0.5;
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #000000;
    line-height: 2.34vw;
  }
  .selection-2 .cont .dis {
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #000000;
    line-height: 2.34vw;
    opacity: 1;
  }
  .selection-2 .cont .dis strong {
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #FD9618;
    line-height: 2.34vw; 
  }
  
  /*selection-3*/
  .selection-3 {
    background: url('../assets/pcbeiji3.jpg') center center no-repeat;
    background-size: cover;
  }
  .selection-3 .tit {
    margin-bottom: 5.28vh;
    font-family: PingFangSC-Medium;
    font-size: 2.08vw;
    color: #FFFFFF;
    text-align: left;
  }
  .selection-3 .con {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
  .selection-3 .cont {
    width: 80%;
  }
  .selection-3 .cont_ {
    display: flex;
  }
  .selection-3 .list_img {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    width: 56vw;
  }
  .selection-3 .list_div {
    width: 9.84vw;
    margin-right: 4.01vw;
    margin-bottom: 3.7vh;
  }
  .selection-3 .list_div img {
    display: block;
    width: 100%;
    height: 17.5vw;
    margin-bottom: 2.13vh;
  }
  .selection-3 p {
    font-family: PingFangSC-Regular;
    font-size: 0.99vw;
    color: #FFFFFF;
    text-align: center;
  }
  .selection-3 .bigimg {
    width: 13.84vw;
    margin-right: 7.14vw;
  }
  .selection-3 .bigimg img {
    display: block;
    width: 100%;
    margin-bottom: 2.5vh;
  }

  .selection-3 .video video {
    width: 18.75vw;
    margin-bottom: 2.59vh;
  }

  /*selection-4*/
  .selection-4 {

  }
  .selection-4 .con {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  } 
  .selection-4 .bg {
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100vw;
    height: 50vh;
    background: #121212;
    z-index: -1;
  }
  .selection-4 .tit {
    margin-bottom: 11.48vh;
    font-family: PingFangSC-Medium;
    font-size: 2.08vw;
    color: #FF972C;
    text-align: center; 
  }
  .selection-4 .list_con {
    display: flex;
    justify-content: center;
    align-items: center;

  }
  .selection-4 .list_div {
    margin: 0 3.21vw;
    text-align: center;
    cursor: pointer;
    -webkit-transition: all 0.8s;
    transition: all 0.8s;
  }
  .selection-4 .list_div p {
    font-family: PingFangSC-Regular;
    font-size: 1.56vw;
    color: #FFFFFF;
    text-align: center;
    line-height: 3.13vw;  
  }
  
  .selection-4 .list_div i {
    color: #BEBEBE;
    font-size: 7.81vw;
  }

  .selection-4 .list_div .bor {
    position: relative;
    display: block;
    width: 1px;
    height: 20.16vw;
    margin: auto;
    background: #979797;
  }
  .selection-4 .list_div .yuan {
    position: absolute;
    left: -1.04vw;
    bottom: 6.09vw;
    margin: auto;
    width: 2.08vw;
    height: 2.08vw;
    border-radius: 50%;
  }
  .selection-4 .list_div_01 .yuan {
    background: #FF972C;
  }
  .selection-4 .list_div_02 .yuan {
    background: #FF682C;
  }
  .selection-4 .list_div_03 .yuan {
    background: #2CD1FF;
  }
  .selection-4 .list_div_04 .yuan {
    background: #672CFF;
  }

  .selection-4 .list_div_01:hover i {
    -webkit-transition: all 0.8s;
    transition: all 0.8s;
    color: #FF972C;
  }
  .selection-4 .list_div_02:hover i {
    -webkit-transition: all 0.8s;
    transition: all 0.8s;
    color: #FF682C;
  }
  .selection-4 .list_div_03:hover i {
    -webkit-transition: all 0.8s;
    transition: all 0.8s;
    color: #2CD1FF;
  }
  .selection-4 .list_div_04:hover i {
    -webkit-transition: all 0.8s;
    transition: all 0.8s;
    color: #672CFF;
  }
  


  /*selection-5*/
  .selection-5 {
    background: url('../assets/pcbeij4.jpg') center center no-repeat;
    background-size: cover;
  }
  .selection-5 .con {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 8.02vw;
    margin: auto;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 61.2vw;
    height: 40.89vw;
    background: #FFFFFF;
  }
  .selection-5 .cont {
    width: 80%;
  }
  .selection-5 h3 {
    font-family: PingFangSC-Medium;
    font-size: 2.08vw;
    color: #FF972C;
  }
  .selection-5 p {
    margin-top: 5.83vh;
    opacity: 0.6;
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #000000;
    line-height: 2.6vw;
  }

  /*selection-6*/
  .selection-6 {
    background: url('../assets/pcbeiji5.jpg') center center no-repeat;
    background-size: cover;
  }
  .selection-6 .con {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
  .selection-6 .tit {
    margin-bottom: 7.69vh;
    font-family: PingFangSC-Medium;
    font-size: 2.08vw;
    color: #000000;
    text-align: center;
  }
  .selection-6 .list_con {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .selection-6 .list_con_ {
    position: relative;
    z-index: 10;
  }
  .selection-6 .bor {
    position: absolute;
    left: 13.2vw;
    top: 0;
    width: 2px;
    height: 46vw;
    background: #B9B9B9;
    z-index: 1;
  }
  .selection-6 .list_div {
    height: 5.21vw;
    margin-bottom: 4.63vh;
    -webkit-transition: all 0.8s;
    transition: all 0.8s;
    cursor: pointer;
  }
  .selection-6 .list_div .p {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .selection-6 .list_div .p strong {
    width: 13.02vw;
    height: 5.21vw;
    border-right: 0.52vw solid transparent;
    line-height: 5.21vw;
    margin-right: 2.6vw;
    font-family: PingFangSC-Medium;
    font-size: 1.56vw;
    color: #000;
    -webkit-transition: all 0.8s;
      transition: all 0.8s;
  }
  .selection-6 .list_div .p:hover strong {
    border-right: 0.52vw solid #FF972C;
    color: #FF972C;
    -webkit-transition: all 0.8s;
      transition: all 0.8s;
  }
  .selection-6 .list_div .p p {
    width: 66.67vw;
    opacity: 0.4;
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #000000;
    -webkit-transition: all 0.8s;
      transition: all 0.8s;
  }
  .selection-6 .list_div .p:hover p {
    opacity: 1;
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #000000;
    -webkit-transition: all 0.8s;
      transition: all 0.8s;
  }
  
  

  /*selection-7*/
  .selection-7 {
    background: url('../assets/pcbeij6.jpg') center center no-repeat;
    background-size: cover;
  }
  .selection-7 .con {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
  .selection-7 .tit {
    margin-bottom: 7.31vh;
    font-family: PingFangSC-Semibold;
    font-size: 2.08vw;
    color: #FF972C;
    text-align: center;
  }
  .selection-7 p {
    margin-bottom: 4.81vh;
    text-align: center;
    font-family: PingFangSC-Regular;
    font-size: 1.56vw;
    color: #FFFFFF;
  }
  .selection-7 p strong {
    margin: 0 1.82vw;
    font-family: PingFangSC-Medium;
    font-size: 1.56vw;
    color: #FF972C; 
  }
  .selection-7 img {
    width: 75.73vw;
  }
  

  /*selection-8*/
  .selection-8 {
    background: url('../assets/pcyykpt.jpg') center center no-repeat;
    background-size: cover;
  }
  .selection-8 .con {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
  .selection-8 .tit {
    margin-bottom: 2.78vh;
    font-family: PingFangSC-Medium;
    font-size: 2.08vw;
    color: #FFFFFF;
  }
  .selection-8 img {
    width: 79.06vw;
  }
  
  /*selection-9*/
  .selection-9 {
    
  }
  .selection-9 .con {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 85%;
    height: 100%;
    margin: auto;
  }
  .selection-9 img {
    width: 27.92vw;
    margin-right: 5vw;
  }
  .selection-9 .content {

  }
  .selection-9 .list_con {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
  }
  .selection-9 .content .tit {
    margin-bottom: 7.31vh;
    font-family: PingFangSC-Semibold;
    font-size: 2.08vw;
    color: #FF972C;
  }
  .selection-9 .list_div {
    width: 24.67vw;
    margin-right: 2.73vw;
    margin-bottom: 9.26vh;
  }
  .selection-9 .list_div h3 {
    margin-bottom: 3.06vh;
    font-family: PingFangSC-Medium;
    font-size: 1.46vw;
    color: #000000;
  }
  .selection-9 .list_div .bor {
    margin-bottom: 1.48vh;
    width: 21.67vw;
    height: 1px;
    background: #D8D8D8;
  }
  .selection-9 .list_div p {
    opacity: 0.7;
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #000000;
  }
  .selection-9 .list_div_right {
    margin-right: 0;
  }

  /*selection-10*/
  .selection-10 {
    height: auto;
  }
  .selection-10 .con {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh; 
  }
  .selection-10 .img {
    width: 32.24vw;
    margin-right: 3.8vw;
  } 
  .selection-10 .content {
    width: 41.35vw;
  }
  .selection-10 .tit {
    margin-bottom: 4.63vh;
    font-family: PingFangSC-Medium;
    font-size: 2.08vw;
    color: #000000;
  }
  .selection-10 p {
    margin-bottom: 3.8vh;
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #000000;
    line-height: 2.6vw;
  }
  .selection-10 .content img {
    display: block;
    width: 100%;
  } 
  
  /*selection-11*/
  .selection-11 {
    background: url('../assets/pcbeij11.jpg') center center no-repeat;
    background-size: cover;
  }
  .selection-11 .con {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%; 
  }
  .selection-11 .tit {
    margin-bottom: 5.83vh;
    font-family: PingFangSC-Semibold;
    font-size: 2.08vw;
    color: #FFFFFF;
  }
  .selection-11 .p {
    margin-bottom: 3.98vh;
    font-family: PingFangSC-Regular;
    font-size: 1.56vw;
    color: #FFFFFF;
  }
  .selection-11 .list_con {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .selection-11 .list_con .img {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 18.33vw;
    height: 17.08vw;
    margin: 0 auto 3.52vh;
  }
  .selection-11 .list_con .img img {
    width: 8.33vw;
    height: 10.36vw;
  }
  
  .selection-11 .list_div {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 22.97vw;
    height: 30.31vw;
    margin-right: 6.41vw;
    background: #FFFFFF;
  }
  .selection-11 .list_div_a .img {
    background: #F5C269;
  }
  .selection-11 .list_div_b .img {
    background: #8CE2F7;
  }
  .selection-11 .list_div_c .img {
    background: #C36BF0;
  } 
  .selection-11 .content h3 {
    margin-bottom: 3.52vh;
    font-family: PingFangSC-Medium;
    font-size: 1.56vw;
    color: #000000;
  }
  .selection-11 .content p {
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #000000;
  }

  /*selection-12*/
  .selection-12 {

  }
  .selection-12 .con {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 72.04vh;
  }
  .selection-12 .tit {
    margin-bottom: 1.48vh;
    font-family: PingFangSC-Semibold;
    font-size: 2.08vw;
    color: #000000;
    text-align: center;  
  }
  .selection-12 .dis {
    margin-bottom: 7.87vh;
    font-family: PingFangSC-Regular;
    font-size: 1.25vw;
    color: #000000;
    text-align: center;
    line-height: 2.08vw;
  }
  .selection-12 .list_con {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .selection-12 .list_div {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 3vw;
  }
  .selection-12 .list_div img {
    display: block;
    width: 9.11vw;
    margin: 0 auto 6.94vh;
  }
  
  .selection-12 .list_div p {
    font-family: PingFangSC-Regular;
    font-size: 1.35vw;
    color: #000000;
    text-align: center;
  }
  
    

	@media screen and (max-width: 750px) {
		.mob {
			display: block;
		}

    /*selection-1*/
    .selection-1 {
      background: url('../assets/PCbeijing1.jpg') center center no-repeat;
      background-size: cover;
    }
    .selection-1 .con {

    }
    .selection-1 .cont {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 50vh;
    }
    
    .selection-1 .tit {
      font-family: PingFangSC-Semibold;
      font-size: 5.33vw;
      color: #FFFFFF;
      text-align: center;
      line-height: 5.89vw;
    }
    .selection-1 .tit strong {
      font-family: PingFangSC-Semibold;
      font-size: 6.4vw;
      color: #FF972C;
      text-align: center;
      line-height: 10.93vw;
    }
    
    /*selection-2*/
    .selection-2 {

    }
    .selection-2 .con {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
    }
    .selection-2 .left-img {
      width: 85.87vw;
      height: 52.53vw;
      margin-right: 0vw;
      margin-bottom: 3vh;
    }
    .selection-2 .cont {
      width: 85.87vw;
    }
    .selection-2 .cont h3 {
      margin-bottom: 1.95vh;
      font-family: PingFangSC-Medium;
      font-size: 5.33vw;
      color: #000000;
      text-align: center;
    }
    .selection-2 .cont p {
      margin-bottom: 1.65vh;
      opacity: 0.5;
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #000000;
      line-height: 6.4vw;
    }
    .selection-2 .cont .dis {
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #000000;
      line-height: 6.4vw;
      opacity: 1;
    }
    .selection-2 .cont .dis strong {
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #FD9618;
      line-height: 6.4vw; 
    }
    
    /*selection-3*/
    .selection-3 {
      background: url('../assets/pcbeiji3.jpg') center center no-repeat;
      background-size: cover;
    }
    .selection-3 .tit {
      margin-bottom: 5.28vh;
      font-family: PingFangSC-Medium;
      font-size: 5.33vw;
      color: #FFFFFF;
      text-align: center;
    }
    .selection-3 .con {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
    }
    .selection-3 .cont {
      width: 100%;
    }

    .selection-3 img {
      display: block;
      width: 61.87vw;
      height: 109.6vw;
      margin: auto;
      margin-bottom: 0vh;
    }

    #swiper01 {
      width: 100vw;
      height: 109.6vw;
    }


    /*selection-4*/
    .selection-4 {

    }
    .selection-4 .con {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
    } 
    .selection-4 .tit {
      margin-bottom: 6.75vh;
      font-family: PingFangSC-Medium;
      font-size: 5.33vw;
      color: #FF972C;
      text-align: center; 
    }
    .selection-4 .list_con {
      display: block;
    }
    .selection-4 .list_div {
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 0 auto 3vh;
      width: 77.07vw;
      height: 26.13vw;
      text-align: center;
      cursor: pointer;
      -webkit-transition: all 0.8s;
      transition: all 0.8s;
    }
    .selection-4 .list_div p {
      font-family: PingFangSC-Regular;
      font-size: 3.56vw;
      color: #000;
      text-align: center;
      line-height: 3.13vw;  
    }

    .selection-4 .list_div_01 {
      border: 0.27vw solid #FF972C;
    }
    .selection-4 .list_div_02 {
      border: 0.27vw solid #FF682C;
    }
    .selection-4 .list_div_03 {
      border: 0.27vw solid #2CD1FF;
    }
    .selection-4 .list_div_04 {
      border: 0.27vw solid #672CFF;
    }
    
    .selection-4 .list_div_01 i {
      margin-right: 12vw;
      font-size: 15vw;
      color: #FF972C;
    }
    .selection-4 .list_div_02 i {
      margin-right: 12vw;
      font-size: 15vw;
      color: #FF682C;
    }
    .selection-4 .list_div_03 i {
      margin-right: 12vw;
      font-size: 15vw;
      color: #2CD1FF;
    }
    .selection-4 .list_div_04 i {
      margin-right: 12vw;
      font-size: 15vw;
      color: #672CFF;
    }


    /*selection-5*/
    .selection-5 {
      display: flex;
      justify-content: center;
      align-items: center;
      background: url('../assets/ydbeiji5.jpg') center center no-repeat;
      background-size: cover;
    }
    .selection-5 .con {
      position: static;
      margin: auto;
      display: flex;
      justify-content: center;
      align-items: center;
      width: 84.27vw;
      height: 143.2vw;
      background: #FFFFFF;
    }
    .selection-5 .cont {
      width: 80%;
    }
    .selection-5 h3 {
      font-family: PingFangSC-Medium;
      font-size: 5.33vw;
      color: #FF972C;
      text-align: center;
    }
    .selection-5 p {
      margin-top: 5.83vh;
      opacity: 0.6;
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #000000;
      line-height: 7.73vw;
    }

    /*selection-6*/
    .selection-6 {
      background: url('../assets/pcbeiji5.jpg') center center no-repeat;
      background-size: cover;
    }
    .selection-6 .con {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
    }
    .selection-6 .tit {
      margin-bottom: 5.4vh;
      font-family: PingFangSC-Medium;
      font-size: 5.33vw;
      color: #000000;
      text-align: center;
    }
    .selection-6 .list_con {
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .selection-6 .list_con_ {
      position: relative;
      z-index: 10;
    }
    .selection-6 .bor {
      position: absolute;
      left: 13.2vw;
      top: 0;
      width: 2px;
      height: 46vw;
      background: #B9B9B9;
      z-index: 1;
    }
    .selection-6 .list_div {
      display: flex;
      justify-content: center;
      align-items: center;
      height: auto;
      margin-bottom: 2.1vh;
      -webkit-transition: all 0.8s;
      transition: all 0.8s;
      cursor: pointer;
    }
    .selection-6 .list_div .p {
      display: block;
    }
    .selection-6 .list_div .p strong {
      display: block;
      width: 100%;
      height: 5.21vw;
      border-right: none;
      line-height: 5.21vw;
      margin-right: 0;
      margin-bottom: 0.9vh;
      font-family: PingFangSC-Medium;
      font-size: 4.27vw;
      color: #000;
      -webkit-transition: all 0.8s;
        transition: all 0.8s;
    }
    .selection-6 .list_div .line {
      width: 40.27vw;
      height: 1px;
      margin-bottom: 1.05vh;
      opacity: 0.3;
      background: #000000;
    }
    .selection-6 .list_div .p:hover strong {
      border-right: none;
      color: #FF972C;
      -webkit-transition: all 0.8s;
        transition: all 0.8s;
    }
    .selection-6 .list_div .p p {
      width: 90vw;
      opacity: 0.4;
      font-family: PingFangSC-Regular;
      font-size: 2.93vw;
      color: #000000;
      -webkit-transition: all 0.8s;
        transition: all 0.8s;
    }
    .selection-6 .list_div .p:hover p {
      opacity: 1;
      font-family: PingFangSC-Regular;
      font-size: 2.93vw;
      color: #000000;
      -webkit-transition: all 0.8s;
        transition: all 0.8s;
    }
    
    

    /*selection-7*/
    .selection-7 {
      background: url('../assets/pcbeij6.jpg') center center no-repeat;
      background-size: cover;
    }
    .selection-7 .con {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
    }
    .selection-7 .tit {
      margin-bottom: 4.95vh;
      font-family: PingFangSC-Semibold;
      font-size: 5.33vw;
      color: #FF972C;
      text-align: center;
    }
    .selection-7 p {
      margin-bottom: 7.65vh;
      text-align: center;
      font-family: PingFangSC-Regular;
      font-size: 3.73vw;
      color: #FFFFFF;
    }
    .selection-7 p strong {
      margin: 0 1.82vw;
      font-family: PingFangSC-Medium;
      font-size: 3.73vw;
      color: #FF972C; 
    }
    .selection-7 img {
      width: 78.13vw;
    }
    

    /*selection-8*/
    .selection-8 {
      background: url('../assets/ydbeij10.jpg') center center no-repeat;
      background-size: cover;
    }
    .selection-8 .con {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
    }
    .selection-8 .tit {
      margin-bottom: 7.35vh;
      font-family: PingFangSC-Medium;
      font-size: 5.33vw;
      color: #FFFFFF;
      text-align: center;
    }
    .selection-8 img {
      width: 84.8vw;
    }
    
    /*selection-9*/
    .selection-9 {
      
    }
    .selection-9 .con {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 85%;
      height: 100%;
      margin: auto;
    }
    .selection-9 img {
      width: 27.92vw;
      margin-right: 5vw;
    }
    .selection-9 .content {

    }
    .selection-9 .list_con {
      display: flex;
      align-items: center;
      flex-wrap: wrap;
    }
    .selection-9 .content .tit {
      margin-bottom: 7.31vh;
      text-align: center;
      font-family: PingFangSC-Semibold;
      font-size: 5.33vw;
      color: #FF972C;
    }
    .selection-9 .list_div {
      width: 87.73vw;
      margin: 0 auto 3.6vh;
    }
    .selection-9 .list_div h3 {
      margin-bottom: 1.05vh;
      font-family: PingFangSC-Medium;
      font-size: 3.73vw;
      color: #000000;
    }
    .selection-9 .list_div .bor {
      margin-bottom: 1.05vh;
      width: 53.33vw;
      height: 1px;
      background: #D8D8D8;
    }
    .selection-9 .list_div p {
      opacity: 0.7;
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #000000;
    }
    .selection-9 .list_div_right {
      margin-right: 0;
    }

    /*selection-10*/
    .selection-10 {
      height: auto;
    }
    .selection-10 .con {
      display: block;
      height: 100vh; 
    }
    .selection-10 .img {
      width: 100vw;
      height: 89.07vw;
      margin: 0 0 5.4vh 0;
    } 
    .selection-10 .content {
      width: 90%;
      margin: auto;
    }
    .selection-10 .tit {
      margin-bottom: 1.63vh;
      font-family: PingFangSC-Medium;
      font-size: 5.33vw;
      color: #000000;
    }
    .selection-10 p {
      margin-bottom: 3.8vh;
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #000000;
      line-height: 6.67vw;
    }
    .selection-10 .content img {
      display: block;
      width: 100%;
    } 
    
    /*selection-11*/
    .selection-11 {
      background: url('../assets/ydbeiji16.jpg') center center no-repeat;
      background-size: cover;
    }
    .selection-11 .con {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%; 
    }
    .selection-11 .tit {
      width: 85%;
      margin: 0 auto 4.65vh;
      font-family: PingFangSC-Semibold;
      font-size: 5.33vw;
      color: #FFFFFF;
    }
    .selection-11 .p {
      width: 85%;
      margin: 0 auto 6.75vh;
      font-family: PingFangSC-Regular;
      font-size: 4vw;
      color: #FFFFFF;
    }
    /*.selection-11 .list_con {
      display: flex;
      justify-content: center;
      align-items: center;
    }*/
    
    .selection-11 .list_div .img {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 57.87vw;
      height: 53.87vw;
      margin: 0 auto 3.52vh;
    }
    .selection-11 .list_div .img img {
      width: 33.33vw;
      height: 33.36vw;
    }
    
    .selection-11 .list_div {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 72.53vw;
      height: 95.73vw;
      margin: auto;
      background: #FFFFFF;
    }
    .selection-11 .list_div_a .img {
      background: #F5C269;
    }
    .selection-11 .list_div_b .img {
      background: #8CE2F7;
    }
    .selection-11 .list_div_c .img {
      background: #C36BF0;
    } 
    .selection-11 .content h3 {
      margin-bottom: 2.1vh;
      font-family: PingFangSC-Medium;
      font-size: 4vw;
      color: #000000;
    }
    .selection-11 .content p {
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #000000;
    }
    
    #swiper02 {
      width: 100vw;
      height: 95.73vw; 
    }
    

    /*selection-12*/
    .selection-12 {

    }
    .selection-12 .con {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 72.04vh;
    }
    .selection-12 .tit {
      margin-bottom: 1.48vh;
      font-family: PingFangSC-Semibold;
      font-size: 5.33vw;
      color: #000000;
      text-align: center;  
    }
    .selection-12 .dis {
      margin-bottom: 7.87vh;
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #000000;
      text-align: center;
      line-height: 5.33vw;
    }
    .selection-12 .list_con {
      display: block;
    }
    .selection-12 .list_div {
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 0 auto 2.55vh;
    }
    .selection-12 .list_div img {
      display: block;
      width: 14.13vw;
      margin: 0 auto 2.55vh;
    }
  
    .selection-12 .list_div p {
      font-family: PingFangSC-Regular;
      font-size: 3.2vw;
      color: #000000;
      text-align: center;
    }
		
	}

	@media screen and (min-width: 751px) {
    
	}
</style>
