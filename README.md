# Hướng dẫn download videos từ coursera

Mục đích của việc download videos dành cho việc lưu trữ offline những videos bài giảng, phục vụ cho việc review bài giảng thường xuyên nhanh chóng. 

Tool  
* https://github.com/coursera-dl/coursera-dl
* Python 
* Annaconda


## Cài đặt tool coursera-downloader 
```bash
pip install coursera-dl
```

## Download course
```bash
coursera-dl -u <user> -p <pass> <ten_khoa_hoc> -sl en --cauth <CAUTH_Token>
```

Trong đó:
* user: Địa chỉ email 
* pass: Mật khẩu
* sl: ngôn ngữ cho phụ đề, ở đây mình chọn en (english)
* cauth: tìm trong Application của trang web (F12 -> Application)
  
Để download được course, mình cần phải có CAUTH_Token. Làm theo hướng dẫn này để lấy CAUTH_Token
  
https://insights.janardhan.page/coursera-dl-httperror-400 
  
