一个简单的 "比应词典"爬虫这个最简单的网页解析,连POST都没用到,不过正则表达式花了我几个小时来调试啊!!!!!

支持 中/英文

中文单词(带拼音):
    格式:
        py 测试
    
英文单词(支持音频):
    格式:
        英音:py test en
        美音:py test us
    
依赖:
1.BeautifulSoup

2.pydub(发音的时候有调试信息啊,烦死了啊有木有)


TODO:
    1.去掉pydub的调试信息(怀疑是ffmpeg的问题, 不过修改pydub的源码加上 -loglevel quiet依然不管用)
    2.貌似只能支持一个单词
    

