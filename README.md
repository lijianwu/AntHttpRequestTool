# AntHttpRequestTool

### 1.用Swift封装的网络请求工具类方法，直接复制可以使用 

### 2.用的是Swift原生底层的api方法实现 

### 3.可以加我微信：lixiaowu1129

### 4.[参考链接]:https://www.it610.com/article/1295349644250914816.htm

### 使用方法：

```
// MARK:- 请求Message数据
@objc fileprivate func loadData() {

  let path = "\(totalAddress)flzxbg_service_vmessage/vmessage/getbyuserid"
  
  let dict = ["userid":1]
  
  HCTool.share.getWithPath(path: path, paras: dict, success: { (result) in
  
     print(result)
     
  }) { (error) in
  
  print(error)
  
 }
 
}
```

![image](https://user-images.githubusercontent.com/17900500/155686187-2d8d1ada-ef89-4e61-b23e-02e2876678ce.png)

