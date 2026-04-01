# Project_1_20231_HUST
Tổng hợp code thuật toán (Project 1 - 2023 kỳ 1).  
Repo: `tdvipp/Project_1_20231_HUST`

---

## 1. Nhóm theo chủ đề thuật toán

### A. Quay lui / Backtracking (Brute-force có cắt tỉa)
- **Sinh hoán vị 1..n**  
  `Tuan_2/PERMUTATION_GEN.cpp`
- **Đếm số nghiệm Sudoku** (thử ứng viên + kiểm tra ràng buộc)  
  `Tuan_2/SUDOKU_COUNT.cpp`
- **Hamilton cycle** (quay lui duyệt đường đi qua mỗi đỉnh đúng 1 lần)  
  `Tuan_5/HAM_CYCLE.cpp`

---

### B. BFS (Breadth-First Search)
- **Water Jug (đổ nước 2 bình)** — BFS trên trạng thái `(x, y)`  
  `Tuan_3/WATERJUD.cpp`
- **BFS liệt kê node theo thứ tự tăng dần (lexicographic)** — dùng `set` để giữ thứ tự kề  
  `Tuan_5/BFS_LIST_NODES_LEX.cpp`

---

### C. DFS

---

### D. Quy hoạch động / DP (Dynamic Programming)
- **Tổ hợp C(k, n) mod (1e9+7)** — dùng memoization/bảng nhớ theo công thức Pascal  
  `Tuan_2/C_K_N.cpp`

---

### E. Cây (Tree) + Duyệt cây (Traversal)
- **Xây cây + thao tác MakeRoot/Insert + InOrder/PreOrder/PostOrder**  
  `Tuan_3/TREE_MANIPULATION_TRAVERSAL.cpp`

---

### F. Đồ thị (Graph) / Tham lam (Greedy)
- **Minimum Spanning Tree (MST) — Kruskal** (tham lam + DSU/Union-Find)  
  `Tuan_5/MST_KRUSKAL.cpp`

---

### G. Xử lý dữ liệu / Map / Prefix sum / Thống kê truy vấn
- **Analyze Code Submission** — thống kê submission, lỗi, điểm, prefix-sum theo thời gian  
  `Tuan_8/ANALYZE_CODE_SUBMISSION.cpp`
- **Citizen Data Analyze** — thống kê theo ngày sinh/khoảng ngày (prefix-sum trên map), tính “generation”; phần max independent set ghi chú chưa hoàn thiện  
  `Tuan_8/CITIZEN_DATA_ANALYZE.cpp`
- **Basic Query Array** — min/max/sum và truy vấn max đoạn con (brute-force)  
  `Tuan_1/basic_query_array.cpp`
- **Text Replacement** — thay token trong văn bản theo 2 pattern nhập vào  
  `Tuan_1/text_replacement.cpp`

---

## 2. Build & chạy (C++)
```bash
g++ -std=c++17 -O2 -o main <path_to_cpp_file>
./main
```

Ví dụ:
```bash
g++ -std=c++17 -O2 -o main Tuan_2/SUDOKU_COUNT.cpp
./main
```
