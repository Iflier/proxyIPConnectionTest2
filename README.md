# 代理 IP 连通性测试
这是一个`Go`语言版本的代理`ip`连通性测试脚本。`Python`语言版的，由于使用了本地的公共类，拆分出来便不知所云了，就不贴了。</br>
`Python`语言版本的，除了开多线程测试代理ip外，也尝试过使用异步方式测试代理连通性，但是哪一种方式都不够快，所以拿`Go`语言来试一下，看看效果怎么样吧。</br>
好久没有更新过`GitHub`了，不是懒了，而是有些信息不方便放出来 :-)。爬虫这个东西，在抓取信息过程中使用的代理网站也就那么几家能用，放出来吧，都去抓代理，对人家的服务器会产生一些压力，这个不太好。所以在哪抓的代理`ip`我就不贴出来了。</br>
至于爬虫抓的内容，有的是直接抓网页，有的是研究的网页使用的api来抓的，api这个东西自己用着没问题，很方便。放出来后，万一人家发现了，更改api调用的链接之后，又得再研究一番，有些小麻烦。记得`脉脉`好像在去年11月份更改过一次api调用，然后我的爬虫就`end of life`了 :-(</br>