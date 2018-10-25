# 中国区划代码

中华人民共和国县以上省市地区行政区划数据, 提供 JSON 数据格式.

本数据来自中华人民共和国民政部, 港澳台地区数据来自百度百科及第三方数据库.

最后更新于 2018-08. ([源网页](http://www.mca.gov.cn/article/sj/xzqh/2018/201804-12/20180810101641.html)、
[港澳台地区数据](http://www.zxinc.org/gb2260-latest.htm))

## Intro

The People's Republic of China regions data, provide JSON data format.

The data that is from Ministry of Civil Affairs of the People's Republic of China,
 Hong Kong, Macao and Taiwan region data from Baidu Encyclopedia and third-party database.

Latest upated at 2018-08. ([Source](http://www.mca.gov.cn/article/sj/xzqh/2018/201804-12/20180810101641.html)、
[Hong Kong, Macao and Taiwan Source](http://www.zxinc.org/gb2260-latest.htm))

## 目录结构

```
data
├── csv
│   ├── cities.csv
│   ├── districts.csv
│   └── provinces.csv
├── js
│   ├── regions.js          # 省市区全部数据
│   └── regions.object.js   # 省市区全部数据 (对象)
├── json
│   ├── cities.json
│   ├── cities.object.json
│   ├── districts.json
│   ├── districts.object.json
│   ├── provinces.json
│   ├── provinces.object.json
│   ├── regions.json            # 省市区全部数据
│   └── regions.object.json 		    # 省市区全部数据 (对象)
│   └── regions.object.flat.json 	    # 省市区全部数据 (扁平对象)
│   └── regions.object.flat.full.json 	    # 省市区全部数据 (扁平对象含父级)
└── sql
    ├── cities.sql
    ├── districts.sql
    ├── provinces.sql
    └── regions.sql 		# 省市区全部数据
```

## 引用资料

* [中华人民共和国行政区划代码](http://www.mca.gov.cn/article/sj/xzqh/2018/)
* [Administrative divisions of China](https://en.wikipedia.org/wiki/Administrative_divisions_of_China)
* [最新县及县以上行政区划代码](http://www.zxinc.org/gb2260-latest.htm)