---
title: "Tôi có thể truy cập dữ liệu lịch sử bằng cách nào?"
order: 105
lang: en-gb
category: 12-api-data-reuse
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

Hiện tại, chúng tôi chưa cung cấp tính năng sao lưu dữ liệu lịch sử (JSONL, MongoDB, CSV).

Tuy nhiên, đối với từng sản phẩm riêng lẻ, có thể truy cập các phiên bản trước đó của dữ liệu sản phẩm bằng API hoặc trên trang sản phẩm bằng cách sử dụng mục "phiên bản".

Mỗi khi một sản phẩm được cập nhật, một phiên bản mới (số thứ tự tăng dần từ 1) sẽ được tạo ra.

Ví dụ, để có được bản sửa đổi đầu tiên (=phiên bản sản phẩm đầu tiên) của sản phẩm này, hãy sử dụng

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Tương tự, tham số rev có thể được sử dụng với API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
