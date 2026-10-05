# Báo cáo nộp bài

Link notebook đã chạy:
https://github.com/kentranpr4-crypto/Track04-Day18-2D-perception-detection-segmentation-keypoints/blob/main/lab_2d_perception_student.ipynb

## Trạng thái

- Các mục lõi 1B, 1C, 1D, 2B, 2C, 3B, 3C, 4A và 4B đã có trong `ket_qua.json`.
- Q1-Q12 đã được trả lời trong notebook.
- Bonus 4C đã chạy trên GPU với bảng so sánh: model `flip_idx` giải phẫu đạt mAP 0.457 trên val gốc và 0.439 trên val lật gương; model `flip_idx` đồng nhất đạt 0.417 và 0.298.
- Kết quả cho thấy tập val chỉ quay phải che một phần lỗi trái/phải; val lật gương làm lỗi của `flip_idx` đồng nhất lộ rõ hơn.
