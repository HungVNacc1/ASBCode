# ASBCode - Online Compiler & Visual Variable Tracker

ASBCode is an online platform designed to support programming education, source code testing, and visual algorithm analysis. Designed with a minimalist approach to optimize user experience, ASBCode helps programming learners easily verify the accuracy of their algorithms and deeply understand the execution mechanism of each line of code through its dynamic variable tracking feature.

---

## 🌟 Key Features

### 1. Real-Time Source Code Editor (Live Editor)
- Integrates syntax highlighting directly during the typing process following the standard Monokai/VS Code color scheme.
- Supports auto-indentation, proper code tab spacing formatting, and automatically synchronizes session progress to the browser cache (LocalStorage).

### 2. Automated Evaluation System (Mini Code Judge)
- Allows flexible configuration of testcase components, including execution input (`Input`) and expected output (`Expected output`).
- Evaluates the source code execution status and returns standardized feedback responses:
  - **AC (Accepted):** Source code executes completely accurately compared to the sample output.
  - **WA (Wrong Answer):** Actual output deviates from the sample output.
  - **CE (Compilation Error):** Syntax error prevents compilation.
  - **RE (Runtime Error):** Program crashes or throws an unhandled exception during execution.
  - **TLE (Time Limit Exceeded):** Program execution exceeds the predefined maximum time limit (Time Limit).

### 3. Variable Tracker & Execution Analyzer
- **Step-by-Step Simulation (Playback):** Once the system successfully analyzes the source code, users can utilize the **Next ▶** or **◀ Prev** navigation controls to inspect the execution flow.
- **Data Structure Visualization:** Displays detailed value changes of variables, arrays (Lists), and corresponding indexes (Index) aligned with the currently executing line, which is highlighted in real time.

---

## 🛠️ User Manual

* **Step 1: Select Programming Language** Choose the desired language from the dropdown menu at the top left corner of the dashboard (The system currently optimizes and fully supports **Python**).
  
* **Step 2: Draft Source Code** Type or paste the code snippet to be tested into the editor container. Users can click the **Sample** button to automatically load a basic predefined algorithm structure for testing purposes.

* **Step 3: Configure Test Data** Provide testing inputs into the **Input** field and the exact expected result into the **Expected output** field. Adjust the maximum execution time duration (Time Limit) in milliseconds (ms) if required.

* **Step 4: Execute the Program** Click the **Run Code** button. The system will compile, process the evaluation, benchmark the execution, and render detailed logs in the **Verdict Panel**.

* **Step 5: Visual Debugging & Analysis** Observe the **Variable Tracker** panel on the right column, and utilize navigation buttons to witness data mutations across execution steps to identify and resolve logical errors (Bugs).

---

## 📋 System Notes
- The current build is stable for the Python programming language. Language structures for C++, Java, and JavaScript are operating in beta preview versions.
- During the playback simulation process, the active running line is highlighted with an amber accent light to optimize visual tracking capabilities.

================================================================================

# ASBCode - Trình Biên Dịch Trực Tuyến & Theo Dõi Biến Số Trực Quan

ASBCode là một nền tảng web hỗ trợ học lập trình, chạy thử nghiệm mã nguồn và phân tích thuật toán trực quan. Hệ thống được thiết kế tối giản, tối ưu trải nghiệm người dùng, giúp người học lập trình dễ dàng kiểm tra tính chính xác của thuật toán và hiểu sâu sắc cơ chế vận hành của từng dòng lệnh thông qua tính năng theo dõi biến số.

---

## 🌟 Các Tính Năng Chính

### 1. Trình Soạn Thảo Mã Nguồn Thời Gian Thực (Live Editor)
- Tích hợp bộ tô màu cú pháp (Syntax Highlighting) theo chuẩn phối màu Monokai/VS Code trực tiếp ngay trong quá trình gõ phím.
- Hỗ trợ tự động căn lề, định dạng thụt lề chuẩn cú pháp và đồng bộ hóa tiến trình làm việc tự động vào bộ nhớ trình duyệt (LocalStorage).

### 2. Hệ Thống Chấm Bài Tự Động (Mini Code Judge)
- Cho phép thiết lập cấu hình bộ testcase linh hoạt bao gồm dữ liệu đầu vào (`Input`) và kết quả kỳ vọng (`Expected output`).
- Đánh giá trạng thái thực thi của mã nguồn và trả về các phản hồi chuẩn hóa:
  - **AC (Accepted):** Mã nguồn thực thi chính xác hoàn toàn so với đáp án mẫu.
  - **WA (Wrong Answer):** Kết quả thực tế lệch so với đáp án mẫu.
  - **CE (Compilation Error):** Lỗi cú pháp, không thể biên dịch.
  - **RE (Runtime Error):** Mã nguồn sập hoặc văng lỗi trong quá trình vận hành.
  - **TLE (Time Limit Exceeded):** Mã nguồn chạy quá thời gian định sẵn (Time Limit).

### 3. Bộ Theo Dõi Biến Số & Phân Tích Thực Thi (Variable Tracker)
- **Tính năng mô phỏng từng bước (Playback):** Sau khi hệ thống phân tích mã nguồn thành công, người dùng có thể sử dụng bộ điều khiển **Tới** hoặc **Lùi** để kiểm soát tiến trình chạy.
- **Trực quan hóa cấu trúc dữ liệu:** Hiển thị chi tiết sự thay đổi giá trị của các biến số, mảng (List) và chỉ số (Index) tương ứng với dòng lệnh đang thực thi được highlight thời gian thực.

---

## 🛠️ Hướng Dẫn Sử Dụng Dành Cho Người Dùng

* **Bước 1: Lựa chọn ngôn ngữ lập trình** Chọn ngôn ngữ mong muốn tại menu thả xuống ở góc trên bên trái giao diện (Hệ thống hiện tại hỗ trợ và tối ưu mạnh nhất cho ngôn ngữ **Python**).
  
* **Bước 2: Soạn thảo mã nguồn** Nhập hoặc dán đoạn mã cần kiểm tra vào ô soạn thảo. Người dùng có thể bấm nút **Mẫu** để hệ thống tự động nạp một đoạn mã thuật toán cơ bản có sẵn để thử nghiệm.

* **Bước 3: Cấu hình dữ liệu thử nghiệm** Điền dữ liệu kiểm thử vào ô **Input** và kết quả chính xác vào ô **Expected output**. Thiết lập giới hạn thời gian chạy (Time Limit) tối đa bằng đơn vị mili-giây (ms) nếu cần.

* **Bước 4: Thực thi chương trình** Bấm nút **Chạy code**. Hệ thống sẽ tiến hành biên dịch, đối chiếu kết quả chấm bài và hiển thị thông tin chi tiết tại khung **Kết quả Chấm bài**.

* **Bước 5: Phân tích và Debug trực quan** Theo dõi khu vực **Theo dõi biến số (Variable Tracker)** ở cột bên phải, sử dụng các nút điều hướng để xem sự biến đổi dữ liệu của chương trình qua từng dòng lệnh nhằm tìm kiếm và sửa lỗi logic (Bug).

---

## 📋 Ghi Chú Hệ Thống
- Phiên bản hiện tại đang trong giai đoạn phát triển ổn định (Stable) cho ngôn ngữ Python. Giao diện các ngôn ngữ C++, Java, JavaScript hiện đang ở phiên bản thử nghiệm (Beta).
- Trong quá trình điều hướng mô phỏng, dòng lệnh đang chạy thực tế sẽ được làm nổi bật bằng vệt sáng màu vàng hổ phách để tối ưu khả năng quan sát trực quan.
