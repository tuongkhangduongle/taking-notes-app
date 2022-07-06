# ĐỒ ÁN CUỐI KÌ PHÁT TRIỂN ỨNG DỤNG ĐA PHƯƠNG TIỆN TRÊN THIẾT BỊ DI ĐỘNG
# PHẦN MỀM QUẢN LÝ GHI CHÚ
### SV thực hiện: Dương Lê Tường Khang - 18520882
## Hướng dẫn chi tiết cài đặt ứng dụng
### Sử dụng phần mềm trợ giúp Expo Go
---
1. Download phần mềm expo go
2. Tải xuống mã nguồn github trên
3. Mở command prompt tại mã nguồn và cài đặt các thư viện liên quan  

```
npm install
```

4. Sau khi hoàn tất, nhập dòng tiếp theo
```
yarn start
```

5. Sau đó, mã QR xuất hiện, mở ứng dụng expo và quét mã để sử dụng ứng dụng

### Phát triển ứng dụng trên thiết bị di động riêng
Đảm bảo đủ điều kiện phát triển ứng dụng theo (mô tả)[https://reactnative.dev/docs/environment-setup]
1. Tải xuống mã nguồn (tại đây)[https://drive.google.com/drive/folders/1NbLnStG8H9mmRwN32GE5z1fR8jiEGqOh?usp=sharing]
2. Thực hiện liên kết điện thoại và máy tính phát triển ứng dụng theo hướng dẫn (tại đây)[https://reactnative.dev/docs/running-on-device]
3. Mở command prompt tại mã nguồn của chương trình, nhập lệnh:
```
npm install
```
```
npx react-native start
```
4. Mở một cửa sổ command prompts khác, nhập:
```
npx react-native run-android --no-jetifier
```