# cài đặt web thành exe dùng nwjs

https://nwjs.io/downloads/

## 1. Chuẩn bị sẵn file

- chuẩn bị sẵn toàn bộ src của web
- tạo file package.json với nội dung sau:
```json
{
  "name": "myapp",
  "version": "1.0.0",
  "main": "index.html",
  "window": {
    "title": "My App",
    "width": 800,
    "height": 600
  }
}
```
- nén zip toàn bộ file mã nguồn của web kèm với package.json, sau đó đổi đuôi file .zip thành .nw

### 2. Gộp file

- copy file nén .nw vào thư mục nwjs
- mở cmd trong thư mục nwjs, dùng lệnh sau để gộp file và build thành exe 

```shell script
copy /b nw.exe+my-file.nw webapp.exe
```
