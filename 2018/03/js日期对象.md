### new Date()

1. setDate() 用于设置一个月的某一天

            var d = new Date()  //Mon Mar 12 2018 17:09:14 GMT+0800 (中国标准时间)
            d.setDate(31)       // Sat Mar 31 2018 17:06:09 GMT+0800 (中国标准时间)
            d.setDate(31)       // Sun Apr 01 2018 17:07:03 GMT+0800 (中国标准时间)
            
    设置当前日期为N天前
    
            var d = new Date() 
            d.setDate(d.getDate()-N)

### moment 日期处理类库

[中文文档](http://momentjs.cn/)
