
  

# Phone Horizone

  

## Mô tả

- Ứng dụng di động bán điện thoại Phone Horizone

- Công nghệ sử dụng:

- Frontend: React Native build trên nền tảng Expo

- Backend: Nodejs với thư viện Express

- Database: MongoDb

  

## Hướng dẫn cài đặt

- Cài đặt Mobile App:

	- Cài đặt nodejs (Phiên bản của ứng dụng: 20.11.0) - <a  href="https://nodejs.org/en/download/current">Cài đặt</a>

	- Cài đặt các gói package: ``npm install``
- Cài đặt Server:
	-  Cài đặt nodejs (Phiên bản của ứng dụng: 20.11.0) - <a  href="https://nodejs.org/en/download/current">Cài đặt</a>
	- Cài đặt các gói package: ``npm install ``

- Cài đặt MongoDb
	- Tải MongoDb Compact: <a  href="https://www.mongodb.com/try/download/community">Cài đặt</a>

## Hướng dẫn chạy ứng dụng
- Chạy Mobile App: 
	- Mở terminal và chạy lệnh: ``npx expo start``
	- Chọn run android
- Chạy Server:
	- Mở terminal và chạy lệnh: ``npm start``

## Tài khoản
- Tạo tài khoản mới bằng cách mở ứng dụng lên và đăng kí
- Hoặc có thể sử dụng api sau để đăng kí sản phẩm:
	- POST /api/users/register
	- body:
	``{ "username":  "username", "email":  "email", "password":  "password" }``

