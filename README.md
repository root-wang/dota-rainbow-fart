<h1 align="center">
+++++++
dota2 英雄人物语音
</h1>

<p align="center">
<strong>「 哪个男孩能拒绝一个傲娇萝莉纸片人老婆在一旁鞭写鞭骂呢？   dota2才是永远的神，最爱的游戏」</strong>
</p>


---

这是一个 ~~vscode~~     clion   彩虹屁🌈插件 [vscode-rainbow-fart](https://github.com/SaekiRaku/vscode-rainbow-fart) 的语音扩展包，灵感来源 [#40](https://github.com/SaekiRaku/vscode-rainbow-fart/issues/40) (支持 `JS` `TS` `python` `golang`)

但这并不彩虹屁，因为钉宫没有夸你，**相反是在骂你**；  ~~你再骂？！(恳求)~~

来自jugg和骨弓的督促，还有JJ8脸来自未来时空的嘲讽，让人兴奋不已

但是从作用上说又并没有区别，彩虹屁原理是让人听着舒服、心情愉悦有动力写代码，

而钉宫傲娇的声音同样听得眯眼而且非常激动、~~血压飙升~~码力十足。


## Preview

![](F:\code\C++\kugimiya-voice-1.0.3\avatars\louise.png)

![shana](F:\code\C++\kugimiya-voice-1.0.3\avatars\shana.png)

语音文件: [voices/](./voices/)

语音台词对照: [resource.csv](./resource.csv)

关键词语音列表: [keywords-voices.yml](./keywords-voices.yml)


## Install

在clion的设置插件里直接搜索Rainbow Fart

~~在 vscode-rainbow-fart(v1.2.3) 中引入语音包是需要打包成 zip 然后引用的，~~

**本项目已经提供了打包好的文件，可以直接在 [Releases](https://github.com/zthxxx/kugimiya-rainbow-fart/releases) 中下载最新版 zip；**

(或者作为开发者从[本仓库](https://github.com/zthxxx/kugimiya-rainbow-fart) clone 后自己手动把相关资源打包成 zip (`npm run build`)。)

~~然后在本地 vscode 启动的 rainbow-fart 配置页面中 `Settings` -> `Voice Packages` -> `Import` 中导入 zip，导入后需要点 enable 开关开启使用；~~

在其他设置中找到Rainbow Fart将解压后地址复制到Custom voice package path(最好不要用中文路径)

勾选Enable rainbow fart


## Customize

导入后可以在页面上打开音频文件夹然后编辑 'contributes.json` 来简单自定义**修改触发关键词和语音**，

------

对于clion来说，contributes.json里的对象数目要控制在23（从0开始计数）及之内否则会报错，我加入插件原版的女生语音，还行，日语的这个我听不懂，然后我又加入了游戏dota2的人物的触发语音，感觉有还挺有意思的，可以根据自己的爱好加入短暂的.mp3的音频文件，然后写出对应的关键词触发，也可以对于日常写错的词语进行提醒，原作者本意是希望可以加入对自己有很大意义的音频文件，这样就会脱离这个插件而独立存在的意义，也就是说这个插件的可能会发展的一些技术问题不会是发展趋势，而个性化自定义的音频则是使用的人的最大的兴趣。



------

~~语音台词对照已整理了列表清单，参见 [resource.csv](./resource.csv)，方便在自定义时选择让自己-兴奋-喜欢的语音；~~

~~如果觉得触发太频繁可以手动删掉一些关键词，或者**把某些关键词改成错误拼写** (目前内置了一些常见 typo)，**立即享受在打错单词的时候被钉宫狠狠的骂一顿吧～**~~

不知道钉宫是谁哈




## Dev & Contribute

~~目前[关键词和语音](./keywords-voices.yml)意思不太对应，希望众钉宫病患者厨力放出，完善一下语音和对应关键词，让钉宫骂得更爽一点。~~

## 喜欢dota2的语音的同学可以告我，我再去弄一些回来，一时半会想不起来了

切分的语音全都放在 [voices/](./voices/) 目录下了，语音和**对应台词及翻译**有对照清单 [resource.csv](./resource.csv)，方便各位自由发挥。

## Ref

- [vscode-rainbow-fart](https://github.com/SaekiRaku/vscode-rainbow-fart)

- [语音合集来源](https://music.163.com/song?id=426850381)

- [钉宫理惠 - 萌娘百科 万物皆可萌的百科全书](https://zh.moegirl.org/zh-hans/%E9%92%89%E5%AE%AB%E7%90%86%E6%83%A0)

- [dota2英雄人物台词](https://dota2.fandom.com/wiki/Kunkka/Responses)

  

## Author

**kugimiya-rainbow-fart** © [Root_Wang](https://github.com/w276211640), Released under the **[MIT](./LICENSE)** License.<br>

> Blog [@Root_Wang](https://github.com/w276211640) · GitHub [@Root_Wang](https://github.com/w276211640)
