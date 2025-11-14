## Phiếu khảo sát mức độ hài lòng với mua sắm thương mại điện tử

> Khảo sát phục vụ mục đích học tập và nghiên cứu, hoàn toàn ẩn danh.  
> Vui lòng trả lời trung thực theo trải nghiệm thực tế của Anh/Chị.

### Phần A – Thông tin chung

1. **Năm sinh** (chọn một):
   - 1965–1980 (Gen X)  
   - 1981–1996 (Millennials – Gen Y)  
   - 1997–2012 (Gen Z)  

2. **Giới tính**:
   - Nam  
   - Nữ  
   - Khác / Không muốn trả lời  

3. **Tần suất mua hàng trên các sàn TMĐT trong 6 tháng gần đây**:
   - Ít hơn 1 lần/tháng  
   - 1–3 lần/tháng  
   - 4–6 lần/tháng  
   - Hơn 6 lần/tháng  

4. **Nền tảng TMĐT Anh/Chị sử dụng thường xuyên nhất**:
   - Shopee  
   - Lazada  
   - Tiki  
   - Khác (ghi rõ): __________

---

### Phần B – Thang đo mức độ hài lòng

**Hướng dẫn**: Với mỗi phát biểu dưới đây, hãy chọn một mức độ từ **1 đến 5**:

- 1 – Rất không đồng ý  
- 2 – Không đồng ý  
- 3 – Phân vân / Bình thường  
- 4 – Đồng ý  
- 5 – Rất đồng ý  

1. Tôi cảm thấy **hài lòng tổng thể** về trải nghiệm mua sắm trên các sàn TMĐT.  
2. Giao diện và cách sử dụng ứng dụng/sàn TMĐT **dễ hiểu và dễ thao tác**.  
3. Quy trình đặt hàng và thanh toán **diễn ra nhanh chóng, thuận tiện**.  
4. Tôi cảm thấy **an toàn** khi thanh toán online trên sàn TMĐT.  
5. Thời gian giao hàng **phù hợp với kỳ vọng** của tôi.  
6. Chất lượng sản phẩm tôi nhận được **phù hợp với mô tả/quảng cáo** trên sàn TMĐT.  
7. Dịch vụ chăm sóc khách hàng (giải quyết khiếu nại, trả hàng, hoàn tiền) **làm tôi hài lòng**.  
8. Tôi cảm thấy **giá cả và khuyến mãi** trên sàn TMĐT là **hấp dẫn và hợp lý**.  
9. Tôi **sẵn sàng tiếp tục** mua hàng trên các sàn TMĐT trong tương lai.  
10. Tôi **sẵn sàng giới thiệu** việc mua hàng qua TMĐT cho người thân, bạn bè.  

---

### Gợi ý mã hóa dữ liệu (dùng cho dạy học)

- Mỗi câu hỏi Q1–Q10 mã hóa thành cột `Q1` … `Q10` với giá trị từ 1 đến 5.  
- Tạo biến `satisfaction` = trung bình `(Q1 + ... + Q10) / 10`.  
- Từ `year_of_birth` suy ra `generation`:  
  - 1965–1980 → `Gen X`  
  - 1981–1996 → `Millennials`  
  - 1997–2012 → `Gen Z`


