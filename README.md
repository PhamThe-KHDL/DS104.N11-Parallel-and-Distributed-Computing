# DS104.N11 - Parallel and Distributed Computing


DS200.M21 - Tính Toán Song Song & Phân Tán

Học kỳ 1 Năm 4 Năm học 2022-2023 

## Final Project - A Practical Real-Time Energy Consumption Prediction System using Big Data Technology


**Giảng Viên:** 
- TS Đỗ Trọng Hợp


**Nhóm SVTH:**
- Phạm Đức Thể
- Trần Thành Luân
- Mai Đức Thuận


### Bộ dữ liệu

- [Kaggle - Smart Home Dataset with weather Information](https://www.kaggle.com/datasets/taranvee/smart-home-dataset-with-weather-information)


![image](https://user-images.githubusercontent.com/62134515/219851137-7fd96909-2990-4632-9d86-8494a2c67ccc.png)


### Nội dung đồ án

- Tiền xử lý và phân tích bộ dữ liệu.
- Hướng tiếp cận: Để tạo ra mô hình dự đoán năng lượng sử dụng trong thời gian thực, chúng tôi sử dụng các phương pháp Univariate Time Series Forecasting và Multivariate Time Series Forecasting thực nghiệm trên các mô hình như: BigDL (TCNForecaster, Seq2SeqForecaster, LSTMForecaster), CNN, GRU, LSTM. Để đánh giá mô hình chúng tôi sử dụng độ đo RMSE.


- Kết quả: Kết quả cao nhất mà chúng tôi đạt được là **RMSE = 0.489** sử dụng LSTMForecaster với phương pháp chuỗi thời gian đa biến sử dụng thuộc tính nhiệt độ và độ ẩm (temperature+humidity).


![image](https://user-images.githubusercontent.com/62134515/219851077-4f378df2-e819-4539-868e-1121b6e3eb0c.png)


![image](https://user-images.githubusercontent.com/62134515/219851094-73e51964-4ea6-4d2f-9021-c09ac27888a7.png)






### Kiến trúc hệ thống

![image](https://user-images.githubusercontent.com/62134515/219851020-70cd28a2-bd4d-49bb-9e62-f503607da4cc.png)




## Thực hiện

```
Phạm Đức Thể

Thể ~/~
```
