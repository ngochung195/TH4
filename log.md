Prompt 1: Kiểm tra giúp tôi đoạn code này đã chuẩn Semantic chưa
<header
        style="background: #2c3e50; color: white; padding: 15px 30px; display: flex; justify-content: space-between; align-items: center;">
        <div class="logo">
            <div class="logo-text" style="font-size: 24px; font-weight: bold;">TechFuture JSC</div>
        </div>
        <nav>
            <div class="nav-list">
                <ul>
                    <li style="display: inline-block; margin-right: 20px; cursor: pointer;">Trang Chủ</li>
                    <li style="display: inline-block; margin-right: 20px; cursor: pointer;">Dịch Vụ</li>
                    <li style="display: inline-block; margin-right: 20px; cursor: pointer;">Dự Án</li>
                    <li style="display: inline-block; cursor: pointer;">Liên Hệ</li>
                </ul>
            </div>
        </nav>
    </header>

Prompt 2: giải thích sự khác biệt giữa các thẻ (Ví dụ: <b> vs <strong>)
<b> vs <strong> (Chữ đậm)Dù cả hai đều làm chữ hiển thị đậm hơn trên màn hình, nhưng mục đích sử dụng lại hoàn toàn khác nhau:
<b> (Bold): Chỉ mang tính chất trình bày. Nó làm chữ đậm lên để gây chú ý về mặt thị giác nhưng không mang thêm ý nghĩa quan trọng nào về nội dung.
<strong> (Strong Importance): Mang ý nghĩa ngữ nghĩa. Nó báo hiệu rằng đoạn văn bản này cực kỳ quan trọng, nghiêm trọng hoặc khẩn cấp.
Các trình đọc màn hình (cho người khiếm thị) sẽ nhấn mạnh hơn khi đọc thẻ này.


Prompt 3: Tư vấn về tác động của Semantic tags lên SEO
1. Tăng khả năng "Hiểu" của Google (Indexing & Context)
Google Bot là một chương trình máy tính, nó không "nhìn" thấy giao diện đẹp hay xấu như con người, nó đọc cấu trúc mã.

Xác định trọng tâm: Khi bạn dùng <article> thay vì <div>, Google biết chính xác đâu là nội dung chính. Khi dùng <nav>, nó biết đây là các liên kết điều hướng.

Phân cấp thông tin: Các thẻ tiêu đề <h1> đến <h6> tạo ra một mục lục logic. Nếu thiếu cấu trúc này, Google sẽ gặp khó khăn trong việc xác định chủ đề cốt lõi của trang.

2. Cải thiện tỷ lệ nhấp chuột (CTR) thông qua Rich Snippets
Sử dụng các thẻ ngữ nghĩa (kết hợp với Schema Markup) giúp website có cơ hội hiển thị các "đoạn trích giàu thông tin" trên kết quả tìm kiếm.

Ví dụ: Các thẻ như <footer>, <time>, hoặc các thẻ mô tả sản phẩm giúp Google hiển thị ngày đăng bài, giá cả, hoặc đánh giá sao ngay trên trang tìm kiếm. Điều này làm nổi bật website của bạn so với đối thủ và kéo người dùng click vào.

3. Ưu tiên trải nghiệm người dùng (UX) và Trợ năng (Accessibility)
Google cực kỳ ưu ái các trang web hỗ trợ tốt cho người khuyết tật.

Các trình đọc màn hình (Screen Readers) dựa hoàn toàn vào Semantic tags để đọc nội dung cho người khiếm thị.

Một website có cấu trúc tốt thường có tỉ lệ thoát trang (Bounce Rate) thấp hơn vì người dùng dễ dàng tìm thấy thông tin họ cần qua các vùng được phân chia rõ ràng.
