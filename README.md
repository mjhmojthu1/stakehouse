# stakehouse
Run node stakehouse
- Guide
1. Deposit 32e: https://lsd.joinstakehouse.com/
2. Setup node, import key: https://eth-docker.net/Usage/QuickStart
3. Stake val: https://lsd.joinstakehouse.com/manage

sudo adduser mjhmojthu
usermod -aG sudo mjhmojthu
sudo usermod -aG docker mjhmojthu
./ethd install  //lệnh này k ra gì, run luôn lệnh tiếp theo, nếu lỗi thêm sudo
./ethd keys import

Xóa mọi dấu vết của 
Dự án này sử dụng khối lượng docker để lưu trữ cơ sở dữ liệu Ethereum PoW và PoS, cũng như các khóa trình xác thực cho ứng dụng khách trình xác thực. 
./ethd terminate  //sẽ loại bỏ tất cả các tập.

./ethd keys import //để nhập khóa và dữ liệu bảo vệ chống chém của chúng. Điều này tìm kiếm .eth/validator_keyscác keystore*.jsontệp và slashing_protection*.jsoncác tệp tùy chọn

./ethd keys list  //để liệt kê tất cả các khóa đã nhập
