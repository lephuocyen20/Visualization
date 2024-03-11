## Bộ dữ liệu Thu nhập điều tra dân số của người dân Mỹ
Bộ dữ liệu được sử dụng để khảo sát các yếu tố ảnh hưởng đến mức thu nhập cá nhân hàng năm của người dân Mỹ, đặc biệt là khả năng kiếm được thu nhập trên 50.000 USD. Đây là mức thu nhập cao, nằm trong top quartile thu nhập của người dân Mỹ. Việc xác định các yếu tố ảnh hưởng giúp đưa ra khuyến nghị phát triển bản thân và nâng cao khả năng thu nhập.
# 1. Các câu hỏi nghiên cứu :
- Những yếu tố nào ảnh hưởng đến việc một cá nhân có thu nhập hơn 50.000 USD mỗi năm?
- Giới tính có ảnh hưởng đến mức thu nhập không?
- Người trẻ tuổi dễ kiếm hơn 50.000 USD so với người trung niên không?
- Làm việc nhiều giờ/tuần trực tiếp tương quan với thu nhập cao hơn không?
- Chúng ta có thể dự đoán thu nhập dựa trên các thuộc tính đã phân tích chưa?
# 2. Dữ liệu
Dữ liệu được lấy từ Cục Điều tra Dân số Mỹ năm 1994 trên Kaggle: https://www.kaggle.com/datasets/uciml/adult-census-income. Bao gồm 15 thuộc tính với hơn 45,000 mẫu gồm:
- Tuổi
- Giới tính
- Nghề nghiệp
- Trình độ học vấn
- Tình trạng hôn nhân
- Sắc tộc
- Số giờ làm việc/tuần
- Quốc tịch
- Mức thu nhập (dưới/trên 50,000 USD)
# 3. Trực quan hóa dữ liệu
- Sử dụng các biểu đồ khác nhau để trực quan hóa phân bố dữ liệu và mối quan hệ, bao gồm:
- Sơ đồ hình lịch cho các thuộc tính số
- Biểu đồ cột so sánh thu nhập theo giới tính, tình trạng hôn nhân, nghề nghiệp...
- Biểu đồ tán xạ giữa Tuổi và Số giờ làm việc
# 4. Mô hình hóa
Sử dụng mô hình Hồi quy Logic để dự đoán mức thu nhập dựa trên các thuộc tính khác. Mô hình đạt 84% độ chính xác cho dự đoán dưới 50,000 USD và 74% cho trên 50,000 USD.
# 5. Kết quả và kết luận
Những phát hiện chính:
- Tuổi trung bình kiếm được trên 50,000 USD là 44 tuổi.
- Nam giới có khả năng kiếm trên 50,000 USD hơn.
- Nghề nghiệp như Quản lý, Chuyên gia có thu nhập cao hơn.
- Làm việc trên 45 giờ/tuần tương quan với thu nhập cao hơn.
- Mặc dù còn hạn chế nhưng phân tích cung cấp những gợi ý về các yếu tố ảnh hưởng đến mức thu nhập cá nhân ở Mỹ. Khai thác thêm các thuộc tính có thể nâng cao độ chính xác dự đoán.
