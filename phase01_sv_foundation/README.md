Phase 01 — Nền tảng SystemVerilog
Mục tiêu
Xây dựng nền tảng SystemVerilog trước khi làm dự án APB Timer Verification.
Trọng tâm của phase này là hiểu:
•	Module
•	Testbench
•	Self-checking testbench
•	Expected vs actual
•	PASS/FAIL summary
•	Cách verify cơ bản bằng simulation
________________________________________
Nội dung học
•	SystemVerilog cơ bản
•	Combinational logic
•	Sequential logic
•	Reset behavior
•	Self-checking testbench
•	Expected vs actual comparison
•	PASS/FAIL summary
•	QuestaSim / ModelSim simulation flow
________________________________________
Các lab
•	lab01_basic_tb: and_gate, mux2 và self-checking testbench cơ bản
•	lab02_alu: ALU 8-bit
•	lab03_counter: Counter có reset, load, enable
________________________________________
Cấu trúc thư mục
phase01_sv_foundation/
├── README.md
├── lab01_basic_tb/
│   ├── rtl/
│   ├── tb/
│   ├── sim/
│   └── sample_logs/
├── lab02_alu/
│   ├── rtl/
│   ├── tb/
│   ├── sim/
│   └── sample_logs/
└── lab03_counter/
    ├── rtl/
    ├── tb/
    ├── sim/
    └── sample_logs/
________________________________________
Tiêu chí PASS
Một lab chỉ được xem là PASS khi có đủ:
•	Compile pass
•	Simulation pass
•	Có self-checking testbench
•	Có so sánh expected vs actual
•	Có PASS/FAIL summary
•	fail_count = 0
•	Có simulation log
Nếu chạy được nhưng chưa có checker hoặc chưa có log thì chỉ là PARTIAL.
Nếu thiếu bằng chứng để kết luận thì là MISSING EVIDENCE.
________________________________________
Kết quả cần đạt sau Phase 01
Sau phase này, tôi cần giải thích được:
•	Self-checking testbench là gì
•	Expected và actual khác nhau thế nào
•	Vì sao cần fail_count
•	Cách test mạch tổ hợp
•	Cách test mạch tuần tự
•	Cách kiểm tra reset
•	Cách chạy simulation cơ bản trong QuestaSim / ModelSim
________________________________________
Trạng thái hiện tại
Status : In Progress
Branch : phase/01-sv-foundation
Focus  : lab01_basic_tb

