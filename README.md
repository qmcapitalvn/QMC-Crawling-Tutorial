# HƯỚNG DẪN TỰ BACKTEST CHIẾN LƯỢC GIAO DỊCH DỰA TRÊN PHÂN TÍCH KỸ THUẬT

## 📎 Giới thiệu

Hướng dẫn này cung cấp hướng dẫn về cách tự backtest chiến lược giao dịch cơ bản tại nhà bằng các chỉ báo phân tích kỹ thuật để các bạn có thể tự thử nghiệm.

## 📁 Yêu cầu

1. **Ngôn ngữ lập trình:** Ngôn ngữ lập trình được đề xuất là Python.

2. **Dữ liệu lịch sử:** Thu thập dữ liệu giá và khối lượng từ nguồn tin cậy. Dữ liệu lịch sử là rất quan trọng để xây dựng mô hình backtest chính xác. 

## 📝 Các bước thực hiện
### Bước 1: Chuẩn bị Dữ liệu

- Đảm bảo bạn có dữ liệu lịch sử chính xác và đầy đủ cho thời gian mong muốn backtest.

- Đối với Python, có thể sử dụng các thư viện như Pandas để xử lý dữ liệu.

- Mình recommend một thư viện Python để crawl data chứng khoán Việt Nam từ bạn Thịnh Vũ. Link mình để tại đây: [vn-stock](https://github.com/thinh-vu/vnstock).

### Bước 2: Xây dựng Chiến lược Giao dịch

- Tìm hiểu thêm về các phương pháp phân tích kỹ thuật và lựa chọn chiến lược mà bạn muốn thử nghiệm backtest. Hiện tại mình chưa thấy trang web nào của Việt Nam tổng hợp đầy đủ về tất cả các phương pháp kỹ thuật, blog của QM Capital là trang đầy đủ nhất hiện nay. Bạn có thể đọc về các chiến lược phân tích kỹ thuật cơ bản tại blog của QM Capital [Tại Đây](https://blog.qmcapital.vn/phan-tich-ky-thuat)
- Thư viện Python mà bạn có thể sử dụng để dùng các chỉ báo kỹ thuật là [Pandas-TA](https://github.com/twopirllc/pandas-ta/) với 130+ chỉ báo và chức năng tiện ích.

### Bước 3: Viết Mô-đun Backtest

- Tạo một mô-đun backtest đơn giản, bao gồm hàm để thực hiện giao dịch, tính toán lợi nhuận và vẽ biểu đồ kết quả.

### Bước 4: Thực hiện Backtest

- Sử dụng dữ liệu lịch sử và chiến lược giao dịch để thực hiện backtest.

- Xem xét và ghi chú kết quả của mỗi giao dịch để đánh giá hiệu suất chiến lược.

### Bước 5: Tối ưu hóa và Đánh giá

- Điều chỉnh các tham số của chiến lược để tối ưu hóa hiệu suất.

- Thực hiện đánh giá chiến lược dựa trên các chỉ số như tỷ suất lợi nhuận, drawdown, và sharpe ratio.

Dưới đây mình sẽ để đoạn code sẵn cho chiến lược sử dụng MACD, các bạn có thể tự backtest bằng cách tuỳ chỉnh tham số nhé.

Link code demo một chiến lược cơ bản của mình: [Chiến lược mẫu](https://colab.research.google.com/drive/1iIxJe2ZzP43xLC3--FQbS1pi9T2l1GOY?usp=sharing#scrollTo=8TgIfy-Pt6s1)

Còn rất nhiều chiến lược dùng PTKT khác, hãy tự khám phá và thử nghiệm!


## 🤯 _Khó quá! Liệu có công cụ nào dùng để "nghịch" BACKTEST mà KHÔNG CẦN PHẢI CODE không?_ 🤔
## 💡 Câu trả lời là CÓ 💡
👉 QM Capital cũng sắp release bản demo free của QMC Trading App, giúp bạn có thể tự do tạo chiến lược và backtest chỉ bằng các thao tác kéo thả, không hề yêu cầu kỹ năng lập trình.

👉 Nếu bạn là một nhà đầu tư thích khám phá các chiến lược và thử nghiệm, chắc chắn không nên bỏ qua bản demo free của QMC Trading App.

📣 Dự kiến bản demo sẽ release vào ___18/02/2024___. Để không bỏ lỡ và nhận thông báo khi bản demo release, bạn có thể __điền email vào form dưới đây__ nhé.

__📣📣📣 Nhận thông tin về bản demo QMC Trading App [Tại Đây](https://forms.gle/55hBzx9WKLKQGYSA8) 📣📣📣__
