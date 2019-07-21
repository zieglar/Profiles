使用本方法就不需要导入传统的 [Pro](https://github.com/ConnersHua/Profiles/raw/master/Quantumult/X/Pro.conf)，在文本模式编辑在「[filter_remote]」内添加

```
[filter_remote]
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Advertising.list, tag=去广告, enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Hijacking.list, tag=反劫持, enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/ForeignMedia.list, tag=国际流媒体, enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/DomesticMedia.list, tag=国内流媒体, enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Global.list, tag=全球加速, enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Apple.list, tag=Apple 服务, enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/China.list, tag=中国直连, enabled=true
```

另外 [Rewrite](https://github.com/ConnersHua/Profiles/raw/master/Quantumult/X/Rewrite.conf) 依然需要导入