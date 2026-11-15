LaviForm 3D - Thư viện theo giấy phép LGPL-2.1

Thư mục này chứa hai thư viện dưới dạng tệp riêng:
- occt/: Open CASCADE Technology (OCCT) bản WebAssembly (gói replicad-opencascadejs 1.2.1, dựa trên opencascade.js,
  OCCT 7.x): replicad_single.js + replicad_single.wasm. Giấy phép LGPL-2.1 kèm OCCT Exception 1.0.
- planegcs/: bộ giải ràng buộc phác thảo PlaneGCS của FreeCAD (gói @salusoft89/planegcs 1.3.0): index.js, sketch/,
  planegcs_dist/planegcs.js + planegcs.wasm. Giấy phép LGPL (tệp LICENSE.txt, văn bản LGPL-2.1).

Bạn có quyền sửa đổi các thư viện này và thay các tệp trên bằng bản bạn tự biên dịch; LaviForm 3D sẽ nạp
bản thay thế khi khởi động. Bản thay thế phải giữ nguyên giao diện (API embind) của bản gốc.

Mã nguồn: https://github.com/sgenoud/replicad (thư mục packages/replicad-opencascadejs, cấu hình build)
          https://github.com/donalffons/opencascade.js
          https://dev.opencascade.org (OCCT)
          https://github.com/Salusoft89/planegcs và https://github.com/FreeCAD/FreeCAD (src/Mod/Sketcher/App/planegcs)
Theo LGPL-2.1 §6(c), LAVIPCO cam kết cung cấp bản sao mã nguồn đầy đủ của thư viện trên (đúng phiên bản
đã đóng gói) trong 3 năm kể từ ngày phát hành, với chi phí không quá chi phí sao chép.
Liên hệ: lamvietphat2022@gmail.com - Công ty TNHH Kỹ Nghệ Lâm Việt Phát.
