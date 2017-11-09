<html>
    <head>
        <link rel="stylesheet" href="./bootstrap-3.3.7-dist/css/bootstrap.css">
        <script src="./jquery-3.2.1.js"></script>        
        <script src="./bootstrap-3.3.7-dist/js/bootstrap.js"></script>   
    </head>
    <body>
        <!--标题-->
        <div class="container">
          <h1>统一建模语言理论测试</h1>
          </div>
          <div class="container-fluid">
          <div class="row">
              <div class="col-md-3">考试科目：统一建模语言</div>
              <div class="col-md-3">时间：100分钟</div>
              <div class="col-md-3">得分：100</div>
          </div>
          <div class="row">
                  <div class="col-md-3">
                      <label class for="banji">班级：</label>
                      <input type="text"id="banji" placeholder="01">
                  </div>
              <div class="col-md-3">
                  <label class for="xuehao">学号：</label>
                  <input type="text"id="xuehao" placeholder="001">
              </div>
              <div class="col-md-3">
                  <label class for="xingming">姓名：</label>
                  <input type="text"id="xingming" placeholder="xxx">
              </div>
          </div>
          <h2>一、填空题（每空5分，共20分）</h2>
          <div>
              <div class="form-group">
                  <label class for="banji">1、UML的中文全称是：
                  <input type="text"id="banji" placeholder="统一建模语言考试"></label>
          </div>
              <div>
                  <div class="form-group">
                  <label class for="dierti">2、对象最突出的特征是：
                  <input type="text"id="dierti" placeholder="封装性">
                  <input type="text"id="dierti" placeholder="继承性">
                  <input type="text"id="dierti" placeholder="多态性"></label>
              </div>
              </div>
          </div>
          </div>
          <div class="container-fluid">
          <h2>二、选择题（每题10分，共20分）</h2>
          <ol>
              <li>
                  UML与软件工程的关系是：
          
                  <div class="radio">
                      <label>
                          <input type="radio" name="optionsRadios" id="optionsRadios1" value="option1">
                          (A)UML就是软件工程
                      </label>
                  </div>
                  <div class="radio">
                      <label>
                          <input type="radio" name="optionsRadios" id="optionsRadios2" value="option2" checked>
                          (B)UML参与到软件工程中软件开发过程的几个阶段
                      </label>
                  </div>
                  <div class="radio">
                      <label>
                          <input type="radio" name="optionsRadios" id="optionsRadios3" value="option3">
                          (C)UML与软件工程无关
                      </label>
                  </div>
                  <div class="radio">
                      <label>
                          <input type="radio" name="optionsRadios" id="optionsRadios4" value="option4">
                          (D)UML是软件工程的一部分
                      </label>
                  </div>
              </li>
              <li>
                  Java语言支持：
          
                  <div class="radio">
                      <label>
                          <input type="radio" name="optionsRadios2" id="optionsRadios21" value="option1" checked>
                          (A)单继承
                      </label>
                  </div>
          
                  <div class="radio">
                      <label>
                          <input type="radio" name="optionsRadios2" id="optionsRadios22" value="option2">
                          (B)多继承
                      </label>
                  </div>
          
                  <div class="radio">
                      <label>
                          <input type="radio" name="optionsRadios2" id="optionsRadios23" value="option3">
                          (C)单继承和多继承都支持
                      </label>
                  </div>
          
                  <div class="radio">
                      <label>
                          <input type="radio" name="optionsRadios2" id="optionsRadios24" value="option4">
                          (D)单继承和多继承都不支持
                      </label>
                  </div>
              </li>
          </ol>
          </div>
      <div class="container-fluid">
        <h2>三、多择题（每题10分，共20分）</h2>
      <ol>
        <li>
            用例的粒度分为以下哪三种：
            <div class="checkbox">
              <label>
                <input name="three" type="checkbox" checked>(A)概述级
              </label>
            </div>
            <div class="checkbox">
              <label>
                <input name="three" type="checkbox" checked>(B)需求级
              </label>
            </div>
            <div class="checkbox">
              <label>
                <input name="three" type="checkbox">(C)用户目标级
              </label>
            </div>
            <div class="checkbox">
              <label>
                <input name="three" type="checkbox" checked>(D)子功能级
              </label>
            </div>
        </li>
        <li>
          类图由以下哪三部分组成:
          <div class="checkbox">
              <label>
                <input name="four" type="checkbox" checked>(A)名称（name）
              </label>
            </div>
            <div>
              <label>
                <input name="four" type="checkbox" checked>(B)属性（attribute）
              </label>
            </div>
            <div>
              <label>
                <input name="four" type="checkbox" checked>(C)操作（operation）
              </label>
            </div>
            <div>
              <label>
                <input name="four" type="checkbox">(D)方法（function）
              </label>
            </div>
        </li>
      </ol>
        <h2>四、判断题（每题10分，共20分）</h2>
        <ol>
            <li>
                用例图只是用于在客户交流和沟通的，用于确定需求。
        <label class="checkbox-inline">
            <input type="checkbox" id="inlineCheckbox1" value="option1"> √
        </label>
        <label class="checkbox-inline">
            <input type="checkbox" id="inlineCheckbox2" value="option2"checked> ×
        </label>
            <li>
                在状态图中，终止状态在一个状态图中允许有任意多个。
                <label class="checkbox-inline">
                    <input type="checkbox" id="inlineCheckbox1" value="option1"checked> √
                </label>
                <label class="checkbox-inline">
                    <input type="checkbox" id="inlineCheckbox2" value="option2"> ×
                </label>
        </li>
        </ol>
        <h2>五、简答题（每题20分，共20）</h2>
        <ol>
          <li>
            简述什么是模型以及模型的表现形式？
            <div>
              <textarea  style="width: 500px; height: 200px">模型是对现实世界的简化和抽象，模型是对所研究的系统、过程、税务或概念的一种表达形式，可以是物理实体；可以是某种图形；或者是一种数学表达式。</textarea>
            </div>
        <!-- Button trigger modal -->
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myModal">
  计算分数
</button>

<!-- Modal -->
<div class="modal fade" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Modal title</h4>
      </div>
      <div class="modal-body">
        You're ready to go!
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
    </div>
    </body>
</html>
