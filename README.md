# cài đặt web thành exe dùng nwjs

## 1. Chuẩn bị sẵn file

- chuẩn bị sẵn toàn bộ src của web và nén lại, sau đó đổi đuôi .zip thành .nw

### 2. Gộp file

- copy file nén .nw vào thư mục nwjs
- mở cmd trong thư mục nwjs, dùng lệnh sau để gộp file và build thành exe 
<details>
  
```shell script
copy /b nw.exe+my-file.nw webapp.exe
```

</details>
