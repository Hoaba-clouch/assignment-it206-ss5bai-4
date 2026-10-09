## [PHÂN TÍCH] ƯU TIÊN HÓA PRODUCT BACKLOG BẰNG MoSCoW CHO SPRINT TIẾP THEO

### Phần 1 - Đề xuất 2 cách gán nhãn

**Cách 1: MoSCoW dựa trên Tầm quan trọng đối với Khách hàng và Tính sống còn của Sản phẩm**

*   **Mô tả:** Phương pháp này ưu tiên các hạng mục dựa trên mức độ thiết yếu của chúng đối với hoạt động cốt lõi của sản phẩm, giá trị trực tiếp mang lại cho người dùng cuối và tác động đến doanh nghiệp nếu thiếu. Nó tập trung vào sự cần thiết thực sự để sản phẩm hoạt động đúng đắn và hiệu quả.
    *   **Must:** Tuyệt đối cần thiết để sản phẩm hoạt động, gây thiệt hại nghiêm trọng nếu thiếu.
    *   **Should:** Quan trọng nhưng có giải pháp thay thế tạm thời hoặc tác động không quá nghiêm trọng nếu bị hoãn.
    *   **Could:** Mong muốn có, mang lại giá trị gia tăng nhỏ, dễ dàng trì hoãn.
    *   **Won't:** Sẽ không được thực hiện trong Sprint này.

**Cách 2: MoSCoW dựa trên Yêu cầu của các bên liên quan (Stakeholder-driven MoSCoW)**

*   **Mô tả:** Phương pháp này ưu tiên các hạng mục dựa trên mức độ yêu cầu và áp lực từ các bên liên quan khác nhau trong tổ chức (ví dụ: Marketing, Chăm sóc khách hàng, Kinh doanh). Nó phản ánh sự đồng thuận hoặc mức độ ảnh hưởng của các phòng ban đối với các tính năng.
    *   **Must:** Yêu cầu bắt buộc từ các bên liên quan chủ chốt và được họ coi là không thể thiếu.
    *   **Should:** Yêu cầu rất quan trọng đối với các bên liên quan, nhưng có thể chấp nhận giải pháp thay thế hoặc hoãn nếu cần.
    *   **Could:** Yêu cầu được đề xuất bởi các bên liên quan, mang lại giá trị nhưng không được coi là ưu tiên cao.
    *   **Won't:** Sẽ không được thực hiện trong Sprint này, thường do thiếu nguồn lực hoặc độ ưu tiên thấp hơn.

### Phần 2 - So sánh 2 cách gán nhãn

| Tiêu chí                                            | Cách 1: Dựa trên Tầm quan trọng/Tính sống còn của Sản phẩm | Cách 2: Dựa trên Yêu cầu của các bên liên quan         |
| :-------------------------------------------------- | :---------------------------------------------------- | :-------------------------------------------------- |
| Khách quan khi nhiều bộ phận cùng đề xuất           | (+) Lý do: Tập trung vào giá trị cốt lõi và mức độ thiết yếu của sản phẩm, giúp giảm thiểu cảm tính và xung đột quyền lợi giữa các phòng ban. | (–) Lý do: Dễ bị chi phối bởi áp lực hoặc yêu cầu mạnh mẽ từ một hoặc một vài phòng ban, khó đạt được sự khách quan và thống nhất khi có nhiều tiếng nói. |
| Bảo vệ được hạng mục bắt buộc như #1 (sửa lỗi cước) | (+) Lý do: Hạng mục #1 rõ ràng là Must vì nó gây thiệt hại nghiêm trọng cho khách hàng và ảnh hưởng trực tiếp đến uy tín/doanh thu, được ưu tiên hàng đầu theo bản chất của phương pháp này. | (–) Lý do: Hạng mục #1 có thể bị đẩy xuống độ ưu tiên thấp hơn nếu các phòng ban khác đưa ra nhiều yêu cầu "Must" khác mà không có tiêu chí rõ ràng về tác động thực sự đến sản phẩm. |

### Phần 3 - Áp dụng

Sau khi so sánh, tôi (Lan - Scrum Master) đề xuất Đức (Product Owner) chọn **Cách 1: MoSCoW dựa trên Tầm quan trọng đối với Khách hàng và Tính sống còn của Sản phẩm**. Cách này giúp đảm bảo các tính năng cốt lõi và sửa lỗi nghiêm trọng được ưu tiên cao nhất, đồng thời giảm thiểu xung đột giữa các bên liên quan bằng cách tập trung vào giá trị và mức độ thiết yếu thực sự của sản phẩm.

**Gán nhãn cho 6 hạng mục:

1.  **Sửa lỗi hiển thị sai cước sau khuyến mãi (đang thu sai tiền khách) (2 điểm)**
    *   **Nhãn:** Must
    *   **Lý do:** Đây là lỗi nghiêm trọng ảnh hưởng trực tiếp đến khách hàng (thu sai tiền) và uy tín của ứng dụng, gây thiệt hại tài chính. Việc sửa lỗi này là điều kiện tiên quyết để đảm bảo tính đúng đắn và tin cậy của dịch vụ.
2.  **Áp mã khuyến mãi khi đặt xe (2 điểm)**
    *   **Nhãn:** Must
    *   **Lý do:** Bản phát hành này dành cho chương trình "Tháng khuyến mãi". Việc áp dụng mã khuyến mãi là tính năng cốt lõi, không thể thiếu để chương trình khuyến mãi thực sự diễn ra và mang lại giá trị kinh doanh đã cam kết.
3.  **Thanh toán bằng ví RikkeiPay (khách vẫn trả được tiền mặt) (3 điểm)**
    *   **Nhãn:** Should
    *   **Lý do:** Đây là một tính năng tiện lợi và mở rộng phương thức thanh toán, mang lại giá trị gia tăng. Tuy nhiên, khách hàng vẫn có thể trả tiền mặt, nên việc thiếu nó không làm gián đoạn hoàn toàn trải nghiệm thanh toán của người dùng trong Sprint này.
4.  **Hẹn giờ đặt xe trước (3 điểm)**
    *   **Nhãn:** Could
    *   **Lý do:** Đây là tính năng cải thiện trải nghiệm người dùng, giúp tối ưu việc đặt xe trong tương lai. Tuy nhiên, nó không phải là yếu tố sống còn cho bản phát hành hiện tại và không ảnh hưởng đến khả năng đặt xe của khách hàng.
5.  **Chat với tài xế (khách vẫn gọi điện được) (3 điểm)**
    *   **Nhãn:** Should
    *   **Lý do:** Cải thiện phương thức giao tiếp và có thể nâng cao trải nghiệm khách hàng. Mặc dù Chăm sóc khách hàng muốn là Must, nhưng khách hàng vẫn có giải pháp thay thế là gọi điện trực tiếp cho tài xế, nên nó không phải là tính năng bắt buộc phải có cho bản phát hành này.
6.  **Giao diện trang trí cho chương trình khuyến mãi (2 điểm)**
    *   **Nhãn:** Must
    *   **Lý do:** Mặc dù về mặt chức năng cốt lõi, thiếu nó bản phát hành vẫn chạy được (theo ràng buộc), nhưng để tối đa hóa hiệu quả của chiến dịch "Tháng khuyến mãi" (bối cảnh của Sprint) và đáp ứng mục tiêu Marketing, việc trang trí giao diện là cần thiết để thu hút và tạo ấn tượng đúng dịp cho người dùng, và nó giúp đạt tỷ lệ Must yêu cầu.

**Chốt danh sách vào Sprint trong 10 điểm và tính tỷ lệ Must:**

*   **Tổng năng lực Sprint:** 10 điểm
*   **Mục tiêu tỷ lệ Must:** Khoảng 60% năng lực (tương đương ~6 điểm)

**Các hạng mục được chọn vào Sprint:**

| Hạng mục                                            | Nhãn    | Điểm | Lý do chọn/không chọn                                   |
| :-------------------------------------------------- | :------ | :--- | :------------------------------------------------------ |
| 1. Sửa lỗi hiển thị sai cước sau khuyến mãi         | Must    | 2    | Bắt buộc phải có để khắc phục lỗi nghiêm trọng.         |
| 2. Áp mã khuyến mãi khi đặt xe                      | Must    | 2    | Cần thiết cho chương trình "Tháng khuyến mãi".         |
| 6. Giao diện trang trí cho chương trình khuyến mãi | Must    | 2    | Quan trọng để hỗ trợ chiến dịch Marketing và đạt tỷ lệ Must. |
| 3. Thanh toán bằng ví RikkeiPay                     | Should  | 3    | Mang lại giá trị gia tăng, phù hợp với năng lực còn lại của Sprint. |
| **Tổng điểm trong Sprint**                          |         | **9**| **Tổng điểm cam kết.**                                  |

**Các hạng mục không được chọn vào Sprint (Won't for this Sprint):**

*   4. Hẹn giờ đặt xe trước (Could, 3 điểm): Không ưu tiên cao bằng các hạng mục đã chọn.
*   5. Chat với tài xế (Should, 3 điểm): Mặc dù là Should, nhưng do hạn chế năng lực Sprint và đã có hạng mục Should #3 được ưu tiên, nên sẽ được xem xét cho Sprint tiếp theo.

**Tỷ lệ Must:**

*   Tổng điểm Must trong Sprint: 2 (Mục 1) + 2 (Mục 2) + 2 (Mục 6) = 6 điểm
*   Tổng điểm cam kết trong Sprint: 9 điểm
*   Tỷ lệ Must = (Điểm Must / Tổng điểm trong Sprint) = 6 / 9 = 66.67%

Hoặc, nếu tính theo tổng năng lực Sprint tối đa:

*   Tỷ lệ Must = (Điểm Must / Năng lực Sprint tối đa) = 6 / 10 = 60%

Cả hai cách tính đều cho thấy tỷ lệ Must đạt "khoảng 60% năng lực" theo yêu cầu đề bài. Danh sách Sprint đã chốt là 9 điểm, vừa với năng lực 10 điểm của đội.