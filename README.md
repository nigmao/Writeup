# Writeup DF-IR

- https://gist.github.com/1259iknowthat/8cb818f0a37566b1fc25151ef074d9af
- https://github.com/MHaggis/sysmon-dfir

```bash
vol -f Windows\ 10\ x64-ff6b1a74.vmem windows.pslist | grep conhost.exe

vol -f Windows\ 10\ x64-ff6b1a74.vmem windows.netscan | grep LISTENING

vol -f Windows\ 10\ x64-ff6b1a74.vmem windows.filescan | grep conhost.exe

vol -f Windows\ 10\ x64-ff6b1a74.vmem windows.dumpfiles --pid 3022
```

HxTsr.exe

ps -ef

https://ctf.shfsec.com/challenges

- https://www.varonis.com/blog/how-to-use-volatility

- https://github.com/volatilityfoundation/volatility/wiki/Command-Reference

https://medium.com/m/global-identity-2?redirectUrl=https%3A%2F%2Finfosecwriteups.com%2Fforensics-memory-analysis-with-volatility-6f2b9e859765

https://infosecwriteups.com/forensics-memory-analysis-with-volatility-6f2b9e859765

https://viblo.asia/p/tailscale-tao-peer-to-peer-vpn-nhu-the-nao-pgjLNdZP432

https://systemweakness.com/the-danger-of-using-unverified-images-from-public-repositories-195db03955bf

tìm thêm lệnh để dump thêm xem được gì không ?

Liệt kê tất cả các tiến trình đang chạy.
Liệt kê các kết nối mạng đang hoạt động và đóng.
Xem lịch sử internet (IE).
Xác định các tập tin trên hệ thống và truy xuất chúng từ kết xuất bộ nhớ.
Đọc nội dung của tài liệu notepad.
Truy xuất các lệnh đã nhập vào Dấu nhắc lệnh của Windows (CMD).
Quét để phát hiện sự hiện diện của phần mềm độc hại bằng quy tắc YARA.
Truy xuất ảnh chụp màn hình và nội dung clipboard.
Truy xuất mật khẩu đã băm.
Truy xuất khóa và chứng chỉ SSL.
