
#fe_ls.js

localStorage做前端加载性能优化与安全性防护
![process](https://github.com/zzkFE/fe_ls.js/blob/master/img/pic.jpg?raw=true)


##使用指南

```javascript
    var myLS = fe_ls.load({
        regular_map:{
          "LStest/test1.css":{
              "url":"LStest/test1.css",
              "key":"2a060e9622282822b0cefeabd63b739b077a6aa2" 
          },
          "LStest/test2.css":{
              "url":"LStest/test2.css",
              "key":"bd80775b9681b3b47c180b21883a22bd7ae9d734"
          },
          "LStest/test1.js":{
              "url":"LStest/test1.js",
              "key":"72a87eef9e3a768291c57d81fdd0dc94f692f0f4"
          },
          "LStest/test2.js":{
              "url":"LStest/test2.js",
              "key":"9f4baa42910804513c424b43c497c14e686f1f10"
          },
          "LStest/test.json":{
              "url":"LStest/test.json",
              "key":"860dcce54ba99df55f86a72962ee2b5c0dd0db51"
          },
          "LStest/test.str":{
              "url":"LStest/test.str",
              "key":"2cfa674e9c296e1d941bea9ac1da4d2337c158e1"
          }
        },
        loadSuccess:function(key,path,data,type){
          
        }
    });
```

##有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件(zkxupt#gmail.com, 把#换成@)



