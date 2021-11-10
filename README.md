自动脚本

## 一家论坛自动签到抽奖脚本 （"oneplus_" 开头的脚本）
## 1、一加论坛web端cookie获取方法
+ 首先使用chrome浏览器，访问[一加论坛官网](https://www.oneplusbbs.com/)， 登陆账号
+ Windows系统可按 `F12` 快捷键打开开发者工具, Mac 快捷键 `option + command + i`
+ 选择开发者工具Network，找到`https://www.oneplusbbs.com/plugin.php?id=dsu_paulsign:sign&operation=qiandao&infloat=1&inajax=1`, 找到`Requests Headers`里的`Cookie`。

## 2、一加论坛web端cookie设置方法
+ 替换 oneolus_cookie.json文件  cookie: XXX" 为自己的Cookie

## 3、注意事项
+ cookie 中包含中文要进行转码地址 https://tool.oschina.net/encode?type=3
+ 格式  "acw_tc=xxxxxx; qKc3_0e8d_saltkey=xxxxxx; qKc3_0e8d_lastvisit=xxxxxx; bbs_avatar=xxxxxx; qKc3_0e8d_sendmail=xxxxxx; opcid=xxxxxx; opcct=xxxxxx; oppt=xxxxxx; opsid=xxxxxx; opsct=xxxxxx; opbct=xxxxxx; UM_distinctid=xxxxxx; CNZZDATA1277373783=xxxxxx; www_clear=xxxxxx; ONEPLUSID=xxxxxx; qKc3_0e8d_sid=xxxxxx; bbs_uid=xxxxxx; bbs_uname=xxxxxx; bbs_grouptitle=xxxxxx; opuserid=xxxxxx; bbs_sign=xxxxxx; bbs_formhash=xxxxxx; qKc3_0e8d_ulastactivity=xxxxxx; opsertime=xxxxxx; qKc3_0e8d_lastact=xxxxxx; qKc3_0e8d_checkpm=xxxxxx; qKc3_0e8d_noticeTitle=xxxxxx; optime_browser=xxxxxx; opnt=xxxxxx; opstep=xxxxxx; opstep_event=xxxxxx; fp=xxxxxx;"

## 免责声明
- 本仓库发布的任何脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断.

- 所有使用者在使用项目的任何部分时，需先遵守法律法规。对于一切使用不当所造成的后果，需自行承担.对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害.

- 如果任何单位或个人认为该项目可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我们将在收到认证文件后删除相关文件.

- 任何以任何方式查看此项目的人或直接或间接使用该项目的任何脚本的使用者都应仔细阅读此声明。本人保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或项目的规则，则视为您已接受此免责声明.

您必须在下载后的24小时内从计算机或手机中完全删除以上内容.

> 您使用或者复制了本仓库且本人制作的任何脚本，则视为`已接受`此声明，请仔细阅读
