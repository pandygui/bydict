![](https://github.com/spygg/bydict/blob/master/screenshot/Screenshot%20from%202017-08-22%2022-57-54.png) 
![](https://github.com/spygg/bydict/blob/master/screenshot/Screenshot%20from%202017-08-22%2023-01-37.png) 


####一个简单的 "比应词典"爬虫,带*语音*哦 只是最简单的网页解析,适合初学者,连POST都没用到,不过正则表达式花了我几个小时来调试啊!!!!!

支持 **中/英文**

中文单词(带拼音):
格式:
    
        py 测试
        py test
    
英文单词(支持音频):
格式:
    
        英音:py test -e
        
        美音:py test -u
       
支持双语例句(默认三个例句):

	py word -f 
	
    
依赖:

1.*BeautifulSoup*

2.*pydub*(发音的时候有调试信息啊,烦死了啊有木有)已删除

3.*playsound*

**TODO:**

    1.~~去掉pydub的调试信息~~(怀疑是ffmpeg的问题, 不过修改pydub的源码加上 -loglevel quiet依然不管用)
    
    2.~~貌似只能支持一个单词~~
    
    3.增加数据库支持
    

