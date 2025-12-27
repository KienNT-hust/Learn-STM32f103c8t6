## 1. 🛠 TỔNG QUAN PHẦN CỨNG (HARDWARE)

* **Số lượng:** 2 bộ ADC độc lập (ADC1, ADC2).
* **Độ phân giải:** 12-bit (Giá trị từ `0` đến `4095`).
* **Điện áp tham chiếu ($V_{REF+}$):** Nối cứng với nguồn 3.3V ($V_{DDA}$) trên chip Blue Pill.
* **Điện áp đầu vào ($V_{IN}$):** $0V \le V_{IN} \le 3.3V$.
* **Thời gian chuyển đổi:** ~1 $\mu s$ (tại xung ADC 14MHz).

### Bảng chân ADC thông dụng (Blue Pill LQFP48)
| Kênh (Channel) | Chân GPIO | Ghi chú |
| :--- | :--- | :--- |
| **IN0** | **PA0** | Thường dùng nhất |
| **IN1** | **PA1** | |
| **IN2** | **PA2** | |
| **IN3** | **PA3** | |
| **IN4** | **PA4** | |
| **IN5** | **PA5** | |
| **IN6** | **PA6** | |
| **IN7** | **PA7** | |
| **IN8** | **PB0** | |
| **IN9** | **PB1** | |
| **IN16** | *Internal* | Cảm biến nhiệt độ chip |
| **IN17** | *Internal* | VREFINT (1.2V chuẩn) |

---
