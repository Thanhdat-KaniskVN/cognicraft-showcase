# LƯU Ý: Cậu cd vào thư mục cognicraft-showcase nhé
cd D:\projects\cognicraft-showcase

$showcaseReadme = @'
<div align="center">
  <h1>🧠 CogniCraft OS</h1>
  <p><b>A Bio-Inspired Cognitive Operating System (Human-Centric AI)</b></p>
  <p>
    <img src="https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python" alt="Python">
    <img src="https://img.shields.io/badge/LLM-Groq%20%7C%20DeepSeek-orange?style=flat-square" alt="LLM">
    <img src="https://img.shields.io/badge/Status-Enterprise%20Grade-success?style=flat-square" alt="Status">
  </p>
  <p><i>"An AI that doesn't just answer questions, but understands your biology."</i></p>
</div>

---

## 🌟 Tổng quan (Overview)

**CogniCraft OS** là một Hệ điều hành Nhận thức (Cognitive OS) thế hệ mới, được thiết kế để mô phỏng chính xác sinh lý học và tâm lý học của con người. Thay vì chỉ là một Chatbot thông thường, CogniCraft sở hữu một **"Bộ não 32 tầng" (32-Layer Architecture)** giúp nó thực sự "cảm nhận" được trạng thái của người dùng (Stress, Sóng não, Nợ ngủ) để đưa ra các can thiệp y tế và giáo dục phù hợp.

> ⚠️ **Lưu ý:** Đây là Repository **Showcase** (Trưng bày). Mã nguồn lõi (Core Engine) chứa các thuật toán độc quyền đang được bảo mật ở chế độ Private để bảo vệ Tài sản Trí tuệ (IP).

---

## 🚀 Tính năng Đột phá (Core Capabilities)

### 1. Hệ thống Sinh lý Động (Dynamic Biology Engine)
*   **Mô phỏng Stress 2 lớp:** Tính toán thời gian thực nồng độ Adrenaline (Trục SAM) và Cortisol (Trục HPA).
*   **Chu kỳ Giấc ngủ (REM/NREM):** Theo dõi Nợ ngủ và Nợ REM dựa trên mô hình giấc ngủ của Matthew Walker.
*   **Sóng não & Viêm não:** Tự động chuyển đổi Sóng não (Alpha/Beta/Gamma) và mô phỏng tình trạng viêm nhiễm tế bào thần kinh đệm (Microglia).

### 2. Can thiệp Hành vi (Behavioral Intervention)
*   **System Guardian (Kỷ luật thép):** Tự động cưỡng chế tắt thiết bị nếu phát hiện người dùng kiệt sức.
*   **Quyền Trợ khẩn cấp (Emergency Override):** Phân tích ngữ cảnh để bỏ qua lệnh cưỡng chế và tiêm Adrenaline nếu phát hiện tình huống khẩn cấp (tai nạn, hỏa hoạn).
*   **Zen Meditation:** Cung cấp bài tập thiền định tự động để hạ huyết áp và kéo Sóng não về trạng thái thư giãn (Alpha).

### 3. Trợ lý Học tập (Smart Scheduler)
*   Đề xuất thời khóa biểu dựa trên nhịp sinh học (Circadian Rhythm):
    *   *Sáng:* Học Logic (Toán, Code) khi Sóng não Beta.
    *   *Chiều:* Học nhóm/Thực hành để vượt qua Afternoon Dip.
    *   *Tối:* Làm việc sáng tạo khi Sóng não chuyển sang Alpha/Theta.

---

## 📊 Hiệu năng & Kiểm thử (Benchmarks & Test Coverage)

Hệ thống đã được tối ưu hóa ở mức độ Vi xử lý (Micro-optimization) và vượt qua các bài kiểm thử khắt khe nhất.

### ⚡ So sánh Hiệu năng (Performance vs Naive Approach)
| Metric | Naive Approach | **CogniCraft-Masution** | Improvement |
| :--- | :--- | :--- | :--- |
| **Token Usage** | 8,488 tokens | **500 tokens** | 🟢 **94.1% saved** |
| **Latency (avg)** | 96.0s | **4.12s** | 🟢 **95.7% faster** |
| **Concurrent Requests** | ~10 | **100** | 🟢 **10x capacity** |
| **Big Data (10,000 nodes)** | 43s | **1.65s** | 🟢 **26x faster** |
| **RAM usage (10,000 nodes)** | 3,825 MB | **9.9 MB** | 🟢 **386x lighter** |

*(Nhờ áp dụng kỹ thuật Vector hóa Numpy, Threading và Caching thông minh).*

### 🧪 Độ phủ Kiểm thử (Test Coverage)
| Test Suite | Result |
| :--- | :--- |
| Unit Tests (Core Algorithms) | ✅ **7/7 PASS** |
| Stress Test (1000-2000 nodes) | ✅ **PASS** |
| Concurrency Test (100 bots) | ✅ **PASS** |
| Final Score | ⭐⭐⭐⭐⭐ **ENTERPRISE-GRADE** |

---

## 🏗️ Kiến trúc Hệ thống (System Architecture)

```text
                                  [ NGƯỜI DÙNG ]
                                        │
                        (Chat, Bấm nút Thiền, Ngủ, Tạo lịch)
                                        │
                                        ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│                        GIAO DIỆN STREAMLIT (FRONTEND)                       │
│  - Hiển thị Stress, Sóng não, Viêm não, Nợ ngủ                              │
│  - Nút Can thiệp: [Thiền 10p] [Ngủ 8h] [Tạo Lịch Học]                       │
│  - Toggle: [Kỷ luật thép] (Bật/Tắt cưỡng chế ngủ)                           │
└────────────────────────────────────┬────────────────────────────────────────┘
                                     │
                                     ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│                        CPM-16 (COGNITIVE MICROPROCESSOR)                    │
│  - Pipeline: FETCH -> DECODE -> EXEC (4 Clusters) -> MEM -> WB              │
│  - Chạy song song: BIO, CONTEXT, COGNITION, IO                              │
└────────────────────────────────────┬────────────────────────────────────────┘
                                     │
                 ┌───────────────────┼───────────────────┐
                 ▼                   ▼                   ▼
┌───────────────────────┐ ┌───────────────────────┐ ┌───────────────────────┐
│    CORE BIOLOGY       │ │   CORE COGNITION      │ │  INTERVENTION LAYER   │
│  (Các tầng Sinh lý)   │ │ (Các tầng Nhận thức)  │ │  (Lớp Can thiệp)      │
├───────────────────────┤ ├───────────────────────┤ ├───────────────────────┤
│ • Trục HPA/SAM (Stress)│ │ • Working Memory      │ │ • System Guardian     │
│ • Sóng não (Brainwave)│ │ • Predictive Coding   │ │ • Emergency Override  │
│ • Giấc ngủ (REM/SWS)  │ │ • Dual Process        │ │ • Zen Meditation      │
│ • Viêm não (Microglia)│ │ • Flow Tracker        │ │ • Smart Scheduler     │
│ • Nội tiết (Melatonin)│ │ • State Vector        │ │ • Music Therapy (WIP) │
└─────────┬─────────────┘ └─────────┬─────────────┘ └─────────┬─────────────┘
          │                         │                         │
          └─────────────────────────┼─────────────────────────┘
                                    ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│                              LLM / API BANK                                 │
│  - Định tuyến thông minh (Groq, DeepSeek)                                   │
│  - Cầu dao tự ngắt (Circuit Breaker)                                        │
│  - Kho Token (Cache) - Tiết kiệm 90% chi phí                                │
└─────────────────────────────────────────────────────────────────────────────┘
