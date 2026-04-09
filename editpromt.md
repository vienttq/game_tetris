# 🎮 Prompt: Build a Tetris Game (Vietnamese, Sound, Light Theme, Pause Feature)

## Objective
Create a complete, playable Tetris game running in a web browser using HTML, CSS, and JavaScript.

---

## Core Requirements

### 1. Game Mechanics
- Classic Tetris gameplay:
  - 7 tetromino shapes (I, O, T, S, Z, J, L)
  - Random generation using bag system
  - Rotation (clockwise at minimum)
  - Collision detection (wall, floor, stacked blocks)
  - Line clearing
  - Gravity (auto falling)
  - Game over when new piece cannot spawn

---

### 2. Controls
- Keyboard:
  - ← → : Di chuyển trái/phải
  - ↓ : Rơi nhanh (soft drop)
  - ↑ hoặc X : Xoay khối
  - Space : Rơi ngay (hard drop)
  - P : Tạm dừng / Tiếp tục

---

### 3. Pause Feature (Quan trọng)
- Khi nhấn phím **P**:
  - Game phải dừng hoàn toàn (không rơi block, không update)
  - Hiển thị overlay "TẠM DỪNG"
  - Nhấn lại P để tiếp tục
- Không làm reset game khi pause

---

### 4. UI / Layout (Light Theme)
- Thiết kế nền sáng (light theme):
  - Background sáng (trắng hoặc pastel)
  - Block màu rõ ràng, dễ nhìn
- Hiển thị:
  - Điểm số (Điểm)
  - Cấp độ (Cấp độ)
  - Số dòng (Số dòng)
  - Khối tiếp theo (Khối tiếp theo)
- Toàn bộ text hiển thị bằng **TIẾNG VIỆT**

---

### 5. Vietnamese Language (Bắt buộc)
Tất cả UI phải dùng tiếng Việt:
- "Điểm"
- "Cấp độ"
- "Số dòng"
- "Tạm dừng"
- "Kết thúc"
- "Chơi lại"

---

### 6. Sound Effects (Quan trọng)
- Thêm âm thanh cho:
  - Di chuyển khối
  - Xoay khối
  - Xóa dòng
  - Game over
- Yêu cầu:
  - Dùng Web Audio API hoặc file âm thanh nhẹ
  - Có thể bật/tắt âm thanh (phím M hoặc nút UI)
  - Âm thanh không bị delay

---

### 7. Scoring System
- 1 dòng = 100 điểm
- 2 dòng = 300 điểm
- 3 dòng = 500 điểm
- 4 dòng = 800 điểm
- Tăng cấp mỗi 10 dòng
- Tốc độ rơi tăng theo cấp

---

### 8. Code Structure
- Tổ chức rõ ràng:
  - Game state
  - Rendering
  - Input handling
  - Game loop
- Dùng requestAnimationFrame
- Code dễ đọc, có comment

---

### 9. Output Format
- Trả về 1 file HTML duy nhất
- Bao gồm CSS + JavaScript bên trong
- Chạy được ngay khi mở trình duyệt

---

### 10. Bonus (Khuyến khích)
- Nút "Chơi lại"
- Lưu điểm cao (localStorage)
- Hiệu ứng xóa dòng đẹp
- Responsive (chạy tốt trên mobile)

---

## Quality Expectations
- Gameplay mượt
- Không lỗi collision
- Pause hoạt động chính xác
- Âm thanh ổn định
- Giao diện sáng, dễ nhìn
- Toàn bộ UI bằng tiếng Việt
