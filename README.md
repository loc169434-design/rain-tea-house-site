# Tiệm Trà Mưa — trang web (chính sách quyền riêng tư)

Trang tĩnh, không cần build. Đường dẫn cho Google Play Console: `/privacy/`.

Trước khi đưa lên, thay hai chỗ trống email bằng email thật (một lệnh):

```bash
sed -i '' 's/\[EMAIL LIÊN HỆ\]/email-cua-ban@example.com/g; s/\[CONTACT EMAIL\]/email-cua-ban@example.com/g' privacy/index.html
```
