# Nhận Diện Cử Chỉ Chào Xã Giao – Edge Impulse FOMO

## Thông tin sinh viên
| Họ tên | MSSV | Lớp |
|---|---|---|
| Phạm An Dũng | N23DCCI018 | D23CQCI01-N |

**Giảng viên hướng dẫn:** Hồ Nhựt Minh  
**Môn học:** Mạng Cảm Biến   
**Học kỳ 2 – Năm học 2025–2026**

---

## Mô tả đề tài
Xây dựng mô hình học máy nhúng nhận diện 4 cử chỉ tay chào xã giao
sử dụng nền tảng Edge Impulse và kiến trúc MobileNetV2 + FOMO.

| Cử chỉ | Mô tả |
|---|---|
| Xin chào | Đưa ngón tay số 2 |
| Tạm biệt | Đưa tay 5 ngón |
| OK | Ngón cái + ngón trỏ tạo vòng |
| Không | Nắm bàn tay tạo số 0 |

**Kết quả:** Accuracy 87.5% – F1 Score 0.88

---

## Cấu trúc thư mục
mangcambien-cuoiky-N23DCCI018/
├── docs/
│   ├── PhamAnDung_final_cuoiky.docx
│   └── PhamAnDung_slide_cuoiky.pptx
├── dataset/
│   └── dataset_info.md
├── results/
│   └── confusion_matrix.png
└── README.md
## Link project Edge Impulse
https://studio.edgeimpulse.com/studio/1013348

## Hướng dẫn chạy demo
1. Vào link Edge Impulse bên trên
2. Deployment → WebAssembly → Build
3. Launch in browser → cho phép camera
4. Thực hiện cử chỉ trước webcam

## Dependencies
- Edge Impulse Studio (web-based)
- Trình duyệt Chrome mới nhất
- Webcam máy tính