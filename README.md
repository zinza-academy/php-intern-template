# 🎯 Template Project - Auto Issue Creation

Chào mừng đến với template! Khi bạn tạo một project từ repo này, pipeline đầu tiên sẽ tự động tạo 1 issue mẫu để hướng dẫn các bước tiếp theo.

## ✅ Tính năng:
- Tự động tạo issue sau khi clone
- Hướng dẫn checklist đầu việc cần làm
- Dễ dàng mở rộng để tạo nhiều issue hơn

## 🔧 Hướng dẫn cài đặt:
1. Vào `Settings → CI/CD → Variables`
2. Thêm biến môi trường:
   - `GITLAB_API_TOKEN`: Personal Access Token của bạn với quyền `api`

## 🧪 Test local:
Bạn có thể chạy file `init.sh` để test tạo issue thủ công.
