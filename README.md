### Khung 1: Bài làm

**1. User Flow "Đặt lại đơn"**

<img width="1012" height="370" alt="image" src="https://github.com/user-attachments/assets/d8c8737b-d997-4500-a4fc-fa22e2ec69ee" />


## 2. Wireframe màn hình "Xem lại giỏ" (đen - trắng - xám)

* **Đầu trang:** Tiêu đề **Xem lại giỏ**, góc phải có nút **? Trợ giúp** (Heuristic #10).
* **Thông báo (Heuristic #1):** Trà đá đã hết hàng và được gỡ khỏi giỏ.
* **Danh sách món:**
* **2x Cơm gà:** Giá cũ gạch ngang ~~45.000đ~~ $\rightarrow$ Giá mới **48.000đ** (Tạm tính: **96.000đ**).
* **1x Nước cam:** **20.000đ**.


* **Chi tiết tiền:**
* Tiền món: **116.000đ**
* Phí giao hàng: **22.000đ**
* Giảm phí giao hàng: **-15.000đ**
* Tổng thanh toán: **123.000đ**


* **Đáy màn hình:** Nút bấm **Đặt đơn • 123.000đ** (cao $\ge 48\text{ dp}$).

---

## Khung 2: Ghi chú (Phép tính)

* **Tiền món:** $2 \times 48.000\text{đ} + 20.000\text{đ} = 116.000\text{đ}$ (đã bỏ Trà đá hết hàng).
* **Giảm phí ship:** Tiền món $116.000\text{đ} \ge 100.000\text{đ}$ nên được giảm $15.000\text{đ}$ phí giao.
* **Tổng thanh toán:** $116.000\text{đ} + 22.000\text{đ} - 15.000\text{đ} = 123.000\text{đ}$.
