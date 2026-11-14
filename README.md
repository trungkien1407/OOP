# BTL Phân tích thiết kế hướng đối tượng – Đề tài 8: Hệ thống quản lý cửa hàng điện thoại

Nhóm 3 · Lớp CNTT1 · GVHD: Nguyễn Hiếu Cường
Thành viên: Nguyễn Trung Kiên (nhóm trưởng), Lương Công Hoan, Nguyễn Việt Hưng

## Nội dung

| File | Nội dung |
|---|---|
| `BaoCao_PTTK_CuaHangDienThoai.docx` / `.pdf` | Báo cáo chính (4 chương, 16 hình, Phụ lục A phân công) – toàn bộ khổ dọc A4, có logo trường; sơ đồ vẽ dáng dọc để thẳng, riêng DCD-C và ERD xoay ngang chiếm trọn trang |
| `Slide_ThuyetTrinh_15phut.pptx` | 15 slide chính (~15 phút, Kiên trình bày); lời thoại trong phần **Notes** |
| `Slide_DuPhong.pptx` | Slide dự phòng DP1–DP8: các sơ đồ còn lại, chỉ mở khi thầy hỏi; trang bìa ghi số hình và người trả lời |
| `OnTap_Kien.docx` | Ôn tập riêng cho Kiên: Chương 3, sơ đồ tuần tự, DCD, GRASP/SOLID |
| `OnTap_Hoan.docx` | Ôn tập riêng cho Hoan: UC, hoạt động, mô hình khái niệm, SSD, trạng thái, ERD |
| `OnTap_Hung.docx` | Ôn tập riêng cho Hưng: bài toán, phạm vi, giả định, quy tắc, NFR, test case |
| `SoDo/*.drawio` | 16 sơ đồ dạng file nguồn chỉnh sửa được (mở bằng [app.diagrams.net](https://app.diagrams.net)) |
| `SoDo/*.png` | Ảnh sơ đồ đã chèn vào báo cáo và slide |

## Phân công

| Thành viên | Phần báo cáo | Thầy hỏi về (nội dung slide) | Đóng góp |
|---|---|---|---|
| Nguyễn Trung Kiên | Chương 3: kiến trúc, 5 sơ đồ tuần tự, 3 DCD, GRASP/SOLID, truy vết; tổng hợp báo cáo; **thuyết trình toàn bộ** | 10–15 + bổ sung mọi phần | 40% |
| Lương Công Hoan | UC + đặc tả, sơ đồ hoạt động; Chương 2; sơ đồ trạng thái; ERD | 5–9 | 35% |
| Nguyễn Việt Hưng | Bài toán, phạm vi, giả định, quy tắc nghiệp vụ, tác nhân; NFR; test case; kết luận | 1–4 | 25% |

Kiên thuyết trình cả 15 slide. Khi thầy hỏi, ai phụ trách phần nào trả lời phần đó (xem file `OnTap_<tên>.docx`).

## Hình – file nguồn

| Hình | File | Hình | File |
|---|---|---|---|
| 1.1 | `01_UseCase` | 3.5 | `07_SD_DoiSanPham` |
| 1.2 | `02_Activity_DoiSanPham` | 3.6 | `08_SD_TiepNhanBaoHanh` |
| 2.1 | `03_ConceptualModel` | 3.7 | `09_DCD_BanHang_SanPham` |
| 2.2 | `04_SSD_BanHang` | 3.8 | `10_DCD_NhapHang_SauBan` |
| 3.1 | `14_KienTruc` | 3.9 | `11_DCD_BCE` |
| 3.2 | `05_SD_BanHang_ThemSanPham` | 3.10 | `12_State_MayDienThoai` |
| 3.3 | `05b_SD_GhiNhanKhachHang` | 3.11 | `13_State_PhieuBaoHanh` |
| 3.4 | `06_SD_BanHang_ThanhToan` | 3.12 | `15_ERD` |

Sửa sơ đồ: mở `.drawio` → File → Export as → PNG → trong Word chuột phải vào hình → Change Picture.
