# Time Series Forecast with Prophet

## I. Tìm hiểu tổng quan về thuật toán Time Series Forecasting

Link: https://insights.magestore.com/posts/giai-thuat-time-series-forecasting

![Phân rã đường cong thời gian thực thành các phần](https://uploads-ssl.webflow.com/5e3a6b6029e8b285ad11a875/5f40cff628575ee1eac75327_4ca22a3a6cdb34b3466499c8e91e94ee2f483166.jpeg)

Với Link 1 kết luận: Đây chính là ý tưởng cơ bản cho lớp các thuật toán Time Series Forecasting. Thực thế thì những thuật toán phổ biến cho dữ liệu chuỗi thời gian như ARIMA, Holt-Winters seasonal method sẽ phức tạp hơn thế này. Việc trích xuất các thành phần con từ dữ liệu gốc không phải là đơn giản, giống như việc pha màu: bạn trộn màu vàng với xanh da trời và thu được màu xanh lá cây, vậy từ màu xanh lá cây đó, hãy tách cho tôi hai màu vàng và xanh da trời ban đầu, có dễ dàng không? Bây giờ thì bạn hiểu vấn đề rồi đó, mix nhiều thứ lại là dễ dàng, nhưng tách chúng ra khỏi hỗn hợp thì là một công việc phức tạp hơn rất rất nhiều!

Link: https://viblo.asia/p/tong-quan-ve-du-bao-chuoi-thoi-gian-y37LdwGYJov

Dự báo chuỗi thời gian (Time Series Forecasting) là một kỹ thuật dự đoán các sự kiện thông qua một chuỗi thời gian. Nó dự đoán các sự kiện trong tương lai bằng cách phân tích các xu hướng trong quá khứ, với giả định rằng các xu hướng trong tương lai sẽ tương tự như vậy.

![](https://images.viblo.asia/full/2e06e642-0d4f-48e9-a5cc-b7166cd79738.png)

File notebook: Overview_Algorithm.ipynb

### Tính dừng và tự tương quan

## II. Paper của thư viện Prophet - Forecasting at Scale (2017)

Link: https://peerj.com/preprints/3190/

### 1. Abstract

Forecasting là một nhiệm vụ phổ biến về khoa học dữ liệu giúp các tổ chức lập kế hoạch với khả năng của minh, thiết lặp mực tiêu và phát hiện sự bất thường. 

## III. Các phương thức và cách hoạt động của Prophet với python nằm trong các file note book.

- Quick Start - (Prophet_1.ipynb)
- Saturating Forecasts include: Forecasting Growth and Saturating Minimum (Prophet_2.ipynb)
- Trend Changepoints include: Automatic changepoint detection in Prophet, Adjusting trend flexibility and Specifying the locations of the changepoints.(Propeht_3.ipynb)
- Seasonality, Holiday Effects, And Regressors include: Modeling Holidays and Special Events, Built-in Country Holidays, Fourier Order for Seasonalities, Specifying Custom Seasonalities, Seasonalities that depend on other factors, Prior scale for holidays and seasonality, Additional regressors and Coefficients of additional regressors (Prophet_4.ipynb)
- Multiolicative Seasonality (Prophet_5.ipynb)
- Uncertainly Intervals include: Uncertainty in the trend and Uncertainty in seasonality (Prophet_6.ipynb)
- 