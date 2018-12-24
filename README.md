<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en">
<head>
    <meta http-equiv="Content-Type" content="text/html;charset=UTF-8" />
    <title>管理员登陆</title>
</head>
<body>
     <style>
    .soubg{
        width: 100%;
        min-width: 1200px;
        height:35px;
        background-color:#f6f6f6;
        font-family:"宋体";
    }
    div,table{
        margin:0 auto;
    }
    div{
        display:block;
    }
    body{
        margin:0;
        padding:0;
        font-size:12px;
        font-family:"Microsoft YaHei";
        line-height:25px;
        background-color:#B0C4DE;
    }
    .sou{
        width: 1200px;
        height: 35px;
        line-height:35px;
    }
    .log_bg{
        width: 100%;
        min-width:1200px;
        height: 840px;
        overflow:hidden;
        background-color:#fff4ef;
    }
    .top{
        width: 1200px;
        height: 140px;
    }
    .login{
        width: 1200px;
        overflow:hidden;
        margin-top:45px;
    }
    .log_img{
        width: 611px;
        height: 425px;
        overflow:hidden;
        float:left;
        margin-top:40px;
    }
    .log_c{
        width: 455px;
        height: 385px;
        overflow:hidden;
        background-color:#FFF;
        display:inline;
        maegin-top:40px;
        margin-right:10px;
        margin-bottom:10px;
        box-shadow:0 0 5px #e0e0e0;
        border-radius:5px;
    }
    form{
        margin: 0;
        padding: 0;
    }
    tbody{
        display:table-row-group;
        vertical-align:middle;
        border-color:inherit;
    }
    table{
        display:table;
        border-collapse:separate;
        border-spacing:2px;
        border-color:grey;
    }
    tr{
        display:table-row;
        vertical-align:inherit;
        border-color:inherit;
    }
    td ,th{
      display:table-cell;
      vertical-align:inherit;
    }
    .l_user {
    width: 267px;
    height: 38px;
    line-height: 38px\9;
    overflow: hidden;
    background: url(images/i_u.png) no-repeat 285px center;
    background-color: #FFF;
    color: #888888;
    font-size: 14px;
    font-family: "Microsoft YaHei";
    padding: 0 40px 0 10px;
    border: 1px solid #cccccc;
   }
   .l_pwd {
    width: 267px;
    height: 38px;
    line-height: 38px\9;
    overflow: hidden;
    background: url(images/i_pwd.png) no-repeat 285px center;
    background-color: #FFF;
    color: #888888;
    font-size: 14px;
    font-family: "Microsoft YaHei";
    padding: 0 40px 0 10px;
    border: 1px solid #cccccc;
}

.r_rad {
    float: left;
    padding-top: 1px;
    margin-right: 2px;
}
.r_txt {
    float: left;
    line-height: 22px;
    margin-right: 15px;
}

.log_btn {
    width: 318px;
    height: 42px;
    line-height: 42px\9;
    overflow: hidden;
    background: url(images/btn_log.gif) repeat-x center top;
    color: #FFF;
    font-size: 16px;
    font-family: "Microsoft YaHei";
    text-align: center;
    padding: 0;
    border: 0;
    cursor: pointer;
    -webkit-border-radius: 2px;
    -moz-border-radius: 2px;
    border-radius: 2px;
}
    .fr{
        float:right;
    }
    .f1{
        float:left;
    }
    .s_sh{
        width: 55px;
        height: 35px;
        overflow:hidden;
        float:left;
    }
    a{
        color:#555555;
        text-decoration:none;
        cursor:pointer;
    }
    .s_sh a{
        width: 20px;
        height: 35px;
        line-height:35px;
        overflow:hidden;
        float:left;
        display:inline;
        margin: 0 3px;
        text-indent:-9999em;

    }
    .s_sh a.sh1{
        background:url('images/sh1.png') no-repeat center 8px;
    }
    .s_sh a.sh2{
        background:url('images/sh2.png') no-repeat center center;
    }
    </style>
</head>
<body>
    <div class="soubg">
     <div class="sou">
            <span class="fr">
                <span class="f1">
                    你好，请
                    <a href="Login1.html">登陆</a>
                    &nbsp;
                    <a href="Regist1.html" style="color:#ff4e00;">免费注册</a>
                    &nbsp;
                </span>
                <span class="f1">|&nbsp;关注我们：</span>
                <span class="s_sh">
                    <a href="#" class="sh1">新浪</a>
                    <a href="#" class="sh2">微信</a>
                </span>
                <span class="fr">
                    |&nbsp;
                    <a href="#">
                        手机版&nbsp;
                        <img src="images/s_tel.png" align="absmiddle">
                    </a>
                </span>

            </span>
        </div>
    </div>
    <div class="Log_bg">
        <div class="top">

        </div>
        <div class="login">
            <div class="log_img">
               <img src="images/l_img.jpg" width="611" height="425">
            </div>
            <div class="log_c">
                <form>
                   <table border="0" style="width: 370px; font-size:14px; margin-top:30px;" cellspadding="0">
                       <table>
                          <tr height="50" valign="top">
                              <td width="55">&nbsp;</td>
                              <td>
                                  <span class="f1" style="font-size:24px">登录</span>
                                  <span class="fr">
                                      还没有账号，
                                      <a href="Regist1.html" style="color:#ff4e00;">立即注册</a>
                                  </span>
                              </td>
                          </tr>
                          <tr height="70">
                              <td>用户名</td>
                              <td>
                                  <input type="text" value class="l_user">
                              </td>
                          </tr>
                          <tr height="70">
                              <td>密&nbsp; &nbsp;码</td>
                              <td>
                                  <input type="password" value class="l_pwd">
                              </td>
                          </tr>
                          <tr>
                              <td>&nbsp;</td>
                              <td style="font-size:12px; padding-top:20px;">
                                  <span style="font-family:"宋体"; class="f1">
                                      <label class="r_rad">
                                         <input type="checkbox" name="">
                                      </label>
                                      <label class="r_txt">请保存我这次的登录信息</label>
                                  </span>
                                  <span class="fr">
                                      <a href="#" style="color: #ff4e00;">忘记密码</a>
                                  </span>
                              </td>
                          </tr>
                          <tr height="60">
                              <td>&nbsp;</td>
                              <td>
                                  <input type="submit" value="登录" class="log_btn">
                              </td>
                          </tr>
                       </table>
                   </table>
                </form>
            </div>
        </div>
    </div>
    <div>

    </div>
</body>
</html>
</body>
</html>
