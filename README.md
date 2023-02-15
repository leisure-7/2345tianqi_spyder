# 2345-
爬取2345天气的不同地点不同时间的历史天气
通过https://tianqi.2345.com/Pc/GetHistory?areaInfo[areaId]='+str(value)+'&areaInfo[areaType]=2&date[year]='+str(year)+'&date[month]='+str(month)该格式读取到历史天气
从http://tianqi.2345.com/tqpcimg/tianqiimg/theme4/js/citySelectData2.js获取不同城市的id
最后通过requests爬取天气并存储到.csv文件中
