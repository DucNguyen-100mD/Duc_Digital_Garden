![[Pasted image 20250621052210.png]]
# <u>Tiêu chí lựa chọn ban đầu</u>
- **Chi phí ban đầu thấp**
- **Rào cản kỹ thuật không quá cao**: không đòi hỏi kỹ năng lập trình phức tạp hoặc có thể ứng dụng các công cụ no-code/dễ học
- **Qui trình rõ ràng**
- **Tiềm năng doanh thu tốt**

# <u>Case study 1: Bán Clip-art trên Etsy bằng Midjourney (CS5)</u> 
## 1 . **THÔNG TIN TỔNG QUAN**
- **Thời gian triển khai**: Tháng **11/2023** (khởi tạo shop) đến tháng **12/2023** (tháng đầu đạt doanh thu), tăng trưởng đến đầu 2024.
- **Quốc gia triển khai**: Không rõ, hoạt động trên Etsy toàn cầu, nhắm đến người dùng tìm kiếm clip-art theo chủ đề phổ biến (hoa, động vật, lễ hội)

## 2 . **MÔ HÌNH KIẾM TIỀN**
- **Hình thức kiếm tiền chính**: Bán sản phẩm số (clip-art) trên Etsy dưới dạng file PNG với nền trong suốt. 
- **Cách dòng tiền được tạo ra từ AI**:
	- Sử dụng **Midjourney** để tạo **clip-art** chất lượng cao theo các chủ đề phổ biến (Christmas, gnomes, animals), kết hợp với **Canva** để chỉnh sửa và tạo gói sản phẩm. Bán các gói clip-art nhỏ (10–20 hình, giá ~$1–$2) để thu hút traffic và gói lớn (100+ hình, giá $15–$50) để tối ưu lợi nhuận.
	- Doanh thu từ bán clip-art, **chủ yếu là lợi nhuận** do không có chi phí vận chuyển, chỉ trừ phí Etsy (6.5%) và chi phí AI ($10–$20/tháng)
- **Chi tiết doanh thu**: 
	- Tháng đầu (12/2023): $568 (gần như toàn bộ là lợi nhuận sau khi trừ phí Etsy và Midjourney).
	- Sau vài tháng (đầu 2024): $50–$70/ngày (~$1,500–$2,100/tháng).
	- Lợi nhuận cao do chi phí thấp (~$30/tháng cho Midjourney và Etsy fees).

## 3 . **CÔNG CỤ AI VÀ CÔNG NGHỆ SỬ DỤNG**
- **Midjourney**: 
	- Vai trò: Tạo clip-art chất lượng cao với phong cách đa dạng (cartoon, watercolor)
	- Dựa trên prompt như “pink Christmas gnome drinking green tea, watercolor style.”
	- Ưu điểm: Tạo hình ảnh chi tiết, bắt mắt, phù hợp với nhu cầu Etsy (cute designs). Hỗ trợ lệnh /describe để phân tích và tái tạo hình ảnh tương tự.
	- Hạn chế: Không thêm được văn bản vào hình ảnh.
- **DALL·E 3 (qua ChatGPT-4)**:
	- Vai trò: Tạo biến thể hình ảnh hoặc phong cách cụ thể, hỗ trợ thêm văn bản vào hình.
	- Ưu điểm: Chính xác, tích hợp trong ChatGPT-4, phù hợp cho người dùng premium ($20/tháng).
	- Hạn chế: Chỉ dành cho người có tài khoản ChatGPT-4 premium, có danh sách chờ.
- **Canva**: 
	- Vai trò: Xóa nền (BG remover), upscale hình ảnh (~3,000 x 3,000 px), và tạo mockup sản phẩm.
	- Ưu điểm: Miễn phí, dễ sử dụng, phù hợp cho người không biết Photoshop.
	- Hạn chế: Upscale không hoàn hảo, có thể gây mờ nhẹ giữa các pixel.
- **Everb (Chrome extension)**:
	- Vai trò: Phân tích sản phẩm bán chạy trên Etsy (số lượt bán, xu hướng) để chọn chủ đề clip-art (pink Santas, Christmas gnomes).
	- Ưu điểm: Cung cấp dữ liệu chi tiết về hiệu suất sản phẩm, giúp định hướng niche

## 4 . **QUY TRÌNH TRIỂN KHAI**
- **Giai đoạn 1: Nghiên cứu thị trường (Tuần 1–2, 11/2023)**:
	- Sử dụng Everb để phân tích sản phẩm clip-art bán chạy trên Etsy, xác định các chủ đề phổ biến (Christmas, animals, floral, gnomes).
	- Kết hợp xu hướng (ví dụ: pink Santas + gnomes) để tạo sản phẩm độc đáo như “Pink Christmas gnomes.”
	- Xác định clip-art là sản phẩm dễ bán nhất do nhu cầu cao và dễ tạo bằng AI.
- **Giai đoạn 2: Tạo và chỉnh sửa clip-art (Tuần 3–4, 11/2023)**:
	- Tạo hình ảnh: Sử dụng Midjourney với prompt cụ thể (ví dụ: “cute pink Christmas Gnome, watercolor style”). Dùng lệnh /describe để tái tạo phong cách từ hình mẫu bán chạy.
	- Chỉnh sửa: Xóa nền và upscale hình ảnh bằng Canva. Sửa lỗi nhỏ (vùng mờ, chi tiết Thừa) để đảm bảo chất lượng.
	- Tạo gói sản phẩm:
		- Gói nhỏ: 10–20 hình, giá $1–$2, để thu hút traffic.
		- Gói lớn: 100+ hình, giá $15–$50, kết hợp nhiều gói nhỏ để tối ưu lợi nhuận.
	- Mockup: Tạo hình ảnh minh họa (mockup) bằng Canva để sản phẩm hấp dẫn hơn.
- **Giai đoạn 3: Mở shop và đăng sản phẩm (Tuần 4, 11/2023)**:
	- Mở shop Etsy, đăng 15–20 gói clip-art, tối ưu tiêu đề và mô tả với từ khóa (ví dụ: “Christmas gnome clipart, pink watercolor”).
	- Đảm bảo hình ảnh có nền trong suốt (PNG) và độ phân giải cao (~3,000 px).
	- Đăng sản phẩm đều đặn (2–3 gói/tuần) để duy trì hoạt động shop.
- **Giai đoạn 4: Quảng bá và mở rộng (12/2023–đầu 2024)**:
	- Quảng bá miễn phí trên Pinterest với hình ảnh clip-art và link đến shop Etsy, tận dụng xu hướng hình ảnh mùa lễ hội (Christmas).
	- Đăng sản phẩm mới hàng tuần, tập trung vào các chủ đề theo mùa (holidays, Seasons).
	- Doanh thu tăng từ ~$10/ngày (giữa 12/2023) lên $50–$70/ngày (cuối 12/2023–đầu 2024).

## 5 . **KẾT QUẢ ĐẠT ĐƯỢC**
- **Doanh thu**:
	- Tháng đầu (12/2023): $568 (gần như toàn bộ là lợi nhuận sau khi trừ ~$10–$20 cho Midjourney và ~6.5% phí Etsy).
	- Sau vài tháng (đầu 2024): $50–$70/ngày (~$1,500–$2,100/tháng)
- **Traffic**: Tăng trưởng đều, đặc biệt vào mùa lễ hội (12/2023), nhờ quảng bá trên Pinterest và xu hướng tìm kiếm trên Etsy.
- **Sản phẩm**: ~15–20 gói clip-art ban đầu, mở rộng lên hàng chục gói với các chủ đề đa dạng (Christmas, animals, floral).
- **Thành quả khác**:
	- Xây dựng shop Etsy thành công từ con số 0 trong 1 tháng với chi phí tối thiểu (~$30).
	- Tạo mô hình kinh doanh sản phẩm số có khả năng mở rộng, đặc biệt vào các mùa cao điểm (holidays).
	- Thử nghiệm thành công chiến lược “small bundles for traffic, large bundles for profit.

## 6 . **BÀI HỌC RÚT RA**
## 7 . **REFERENCES**
- Vd trang Etsy: VD: https://www.etsy.com/listing/1892474057/watercolor-cute-animals-clipart-cute?ls=s&ga_order=most_relevant&ga_search_type=all&ga_view_type=gallery&ga_search_query=clipart&ref=sr_gallery-1-2&sr_prefetch=1&pro=1&bes=1&dd=1&sei=1&content_source=a133f8d487c066e2fd53bb47e88c7492e061ea42%253A1892474057&organic_search_click=1&logging_key=a133f8d487c066e2fd53bb47e88c7492e061ea42%3A1892474057
- Link gốc: journeyaiart.Com - Sell Etsy AI Art


# <u>Case study 2: Bán Prompt ChatGPT (CS13)</u>
## 1 . **THÔNG TIN TỔNG QUAN**
- **Tên nhân vật hoặc thương hiệu cá nhân**: codewithbernard (Redditor, ẩn danh, tự xưng là web developer).
- **Thời gian triển khai**: 6 tháng (từ tháng 7/2023 đến tháng 12/2023, dựa trên bài đăng ngày 7/12/2023).
- **Quốc gia triển khai**: Không rõ, nhưng nhắm đến thị trường toàn cầu qua website Prompt Advance và các kênh như Medium, Reddit.

## 2 . **MÔ HÌNH KIẾM TIỀN**
- **Hình thức kiếm tiền chính**: Bán bộ sưu tập 10,000 prompt ChatGPT (câu lệnh AI) trên website tự xây dựng Prompt Advance (promptadvance.club). 
- **Cách dòng tiền được tạo ra từ AI**:
	- Tạo bộ sưu tập 10,000 prompt chất lượng cao, phục vụ các nhu cầu như marketing, coding, viết nội dung, và sáng tạo (ví dụ: prompt tạo quảng cáo, viết email, hoặc mô phỏng phỏng vấn việc làm).
	- Bán bộ prompt dưới dạng sản phẩm số với mô hình "mua một lần, sở hữu mãi mãi", giá không công khai nhưng ước tính $10–50/bộ dựa trên doanh thu và số lượng khách hàng.
	- Tăng giá trị sản phẩm bằng cách phát triển ChatGPT browser extension, cho phép người dùng truy cập prompt trực tiếp trong giao diện ChatGPT.
	- Đạt doanh thu $14,016 trong 6 tháng từ việc bán bộ prompt, chủ yếu qua lưu lượng truy cập từ Medium (50%), Facebook Ads (25%), Reddit, SEO, và các nguồn khác (25%).
- **Đặc điểm nổi bật**: Mô hình tận dụng kỹ năng lập trình để xây dựng website và extension, kết hợp với nội dung AI để tạo sản phẩm số có giá trị cao, không cần chi phí vận hành lớn.

## 3 . **CÔNG CỤ SỬ DỤNG**
- **ChatGPT**:
	- **Vai trò**: Thử nghiệm và tối ưu hóa các prompt để đảm bảo hiệu quả trước khi đưa vào bộ sưu tập. Ví dụ: prompt tạo quảng cáo Google Ads hoặc mô phỏng phỏng vấn việc làm.
	- **Đặc điểm nổi bật**: Không cần công cụ AI phức tạp, chỉ sử dụng ChatGPT (phiên bản miễn phí hoặc Plus) để kiểm tra chất lượng prompt.
- **MidJourney (khả năng sử dụng, không xác nhận rõ)**:
	- **Vai trò**: Có thể được dùng để tạo hình ảnh minh họa cho website hoặc bài viết Medium, nhưng không được đề cập trực tiếp trong bài đăng.
- **Prompt Advance (promptadvance. Club)**:
	- **Vai trò**: Website tự xây dựng để bán bộ 10,000 prompt và cung cấp ChatGPT browser extension. Giao diện đơn giản, dễ tìm kiếm và sao chép prompt.
	- **Đặc điểm nổi bật**: Không tốn chi phí phát triển (do chính tác giả lập trình), tích hợp thanh toán (có thể qua Stripe hoặc PayPal, không nêu rõ).
- **Medium.com**:
	- **Vai trò**: Nền tảng viết blog để đăng bài về cách sử dụng ChatGPT và quảng bá bộ prompt, đóng góp 50% khách hàng.
- **Reddit**:
	- Vai trò: Kênh quảng cáo (Reddit Ads) và chia sẻ công cụ miễn phí để thu hút khách hàng, đóng góp ~10–15% khách hàng.
- **Facebook Ads**:
	- **Vai trò**: Chạy quảng cáo để thu hút khách hàng, đóng góp 25% doanh thu, nhưng không mang lại lợi nhuận cao (chi phí ~$3,000). 
- **ChatGPT Browser Extension**:
	- Vai trò: Công cụ tự phát triển, tích hợp bộ prompt vào giao diện ChatGPT, tăng giá trị sản phẩm và trải nghiệm người dùng.
- **SEO Tools (không nêu rõ tên)**:
	- Vai trò: Tối ưu hóa website Prompt Advance để thu hút lưu lượng truy cập organic, đóng góp ~10–15% khách hàng.

## 4 . **QUY TRÌNH TRIỂN KHAI**
- **Giai đoạn 1: Nghiên cứu thị trường và ý tưởng (Tháng 7/2023)**:
	- **Nghiên cứu thị trường**: Quan sát các quảng cáo Facebook về bộ prompt ChatGPT trên Notion, nhận thấy nhu cầu nhưng sản phẩm còn đơn giản. Quyết định xây dựng phiên bản cải tiến.
	- **Xác định niche**: Tập trung vào các prompt hữu ích cho marketing (ví dụ: tạo quảng cáo), coding (ví dụ: viết đoạn code Python), và sáng tạo nội dung (ví dụ: viết truyện ngắn).
	- **Kế hoạch sản phẩm**: Quyết định bán bộ 10,000 prompt qua website tự xây dựng thay vì dùng marketplace như PromptBase hoặc Gumroad.

- **Giai đoạn 2: Xây dựng sản phẩm và website (Tháng 7–Tháng 9/2023)**:
	- **Tạo prompt**: Kết hợp scraping prompt từ các nguồn công khai, xem xét đánh giá khách hàng trên các nền tảng khác, và tự viết prompt mới. Thử nghiệm từng prompt trên ChatGPT để đảm bảo chất lượng.
	- **Xây dựng website**: Sử dụng kỹ năng lập trình để tạo Prompt Advance, một website với giao diện dễ dùng, cho phép tìm kiếm và sao chép prompt. Chi phí phát triển $0 (tự code).
	- **Thử nghiệm ban đầu**: Đăng bán bộ prompt và thu hút 10 khách hàng đầu tiên qua Reddit Ads (hòa vốn).

- **Giai đoạn 3: Marketing và cải tiến sản phẩm (Tháng 10–Tháng 12/2023)**:
	- **Chiến lược marketing**:
		- Đăng bài blog trên Medium.com về cách sử dụng ChatGPT hiệu quả, nhúng liên kết đến Prompt Advance, thu hút 50% khách hàng.
		- Chạy Facebook Ads ($3,000 chi phí), đóng góp 25% doanh thu nhưng không mang lại lợi nhuận cao.
		- Chia sẻ công cụ miễn phí (như công cụ ChatGPT đơn giản) trên Reddit, kết hợp SEO để thu hút lưu lượng organic, đóng góp ~25% khách hàng.
	- **Cải tiến sản phẩm**: Sau 100 khách hàng, phát triển ChatGPT browser extension để tích hợp prompt trực tiếp vào ChatGPT, tăng giá trị và giữ chân người dùng.
	- **Kết quả**: Đạt $14,016 doanh thu từ hàng trăm lượt bán, với lợi nhuận gần như tuyệt đối (trừ $3,000 chi phí quảng cáo).

- **Giai đoạn 4: Kế hoạch mở rộng (Đang tiếp diễn)**:
	- Tiếp tục viết blog trên Medium và tối ưu SEO để tăng lưu lượng organic.
	- Phát triển thêm công cụ miễn phí (như công cụ ChatGPT) để thu hút khách hàng.
	- Cải tiến extension với tính năng quản lý prompt cá nhân hóa.
	- Thử nghiệm lại Facebook Ads và khám phá các kênh như TikTok, Etsy, hoặc affiliate marketing (dựa trên gợi ý từ bình luận).

## 5 . **KẾT QUẢ ĐẠT ĐƯỢC**
- **Doanh thu**: $14,016 trong 6 tháng (từ tháng 7–tháng 12/2023, trung bình ~$2,336/tháng).
- **Lợi nhuận**: Gần như toàn bộ doanh thu là lợi nhuận, trừ ~$3,000 chi phí Facebook Ads, do không có chi phí phát triển hoặc vận hành.
- **Thành quả khác**:
	- Chứng minh tiềm năng của thị trường ngách bán prompt, bất chấp ý kiến hoài nghi (như “ai sẽ mua prompt?”).
	- Xây dựng website và extension độc quyền, tạo lợi thế cạnh tranh so với các bộ prompt trên Notion hoặc marketplace.
	- Thu hút hàng trăm khách hàng toàn cầu, với 50% từ Medium, 25% từ Facebook Ads, và 25% từ Reddit, SEO, và các nguồn khác.
	- Tạo mô hình thu nhập thụ động bền vững, với tiềm năng mở rộng sang các kênh như Etsy, TikTok, hoặc YouTube.
## 6 . **BÀI HỌC RÚT RA**
## 7 . **REFERENCES**
- Link gốc: https://www.reddit.com/r/EntrepreneurRideAlong/comments/18bdkbr/14k_selling_chatgpt_prompts/
- Website dự án: https://chromewebstore.google.com/detail/prompt-book/bmjlmnhdmfpkdhjfichjfciedemjaobb
- Blog Medium của nhân vật: https://bernardbad.medium.com/

# <u>Case study 3: Kiếm 2.348 USD/tháng từ Website Ngách và Pinterest (CS22)</u>
## 1 . **THÔNG TIN TỔNG QUAN**
- **Tên nhân vật hoặc thương hiệu cá nhân**: korni (thành viên **BlackHatWorld**, tham gia từ ngày 24/5/2010, có kinh nghiệm xây dựng website ngách từ năm 2010. Trước đây, korni đã thất bại với một website phụ thuộc vào Google SEO do các bản cập nhật thuật toán năm 2023).
- **Thời gian triển khai**: Bắt đầu từ ngày 9/1/2024, với các cập nhật được báo cáo đến ngày 7/6/2024 (khoảng 150 ngày). Các mốc thời gian quan trọng:
	- Tháng 1/2024: Thiết lập website và tài khoản Pinterest.
	- Tháng 2–3/2024: Tăng trưởng traffic và tối ưu hóa pins. 
	- Tháng 4–6/2024: Đột phá traffic và bắt đầu kiếm tiền với Mediavine Journey.
- **Quốc gia triển khai**: Không đề cập cụ thể, nhưng nhắm đến thị trường quốc tế, đặc biệt là Mỹ (84,9% người dùng Pinterest từ Mỹ theo thống kê của korni). Đối tượng mục tiêu là nữ (82,59% người dùng Pinterest là nữ, 3,99% là nam, 13,4% là khác), tập trung vào các chủ đề phù hợp như **lifestyle, home decor, hoặc fashion** (nhưng không quá “nữ tính” như makeup/nails để phù hợp với sở thích cá nhân của korni).
	
## 2 . **MÔ HÌNH KIẾM TIỀN**
- **Hình thức kiếm tiền chính**: 
	- **Quảng cáo hiển thị (Display Ads)**: Sử dụng Mediavine Journey (chương trình quảng cáo cho website nhỏ, yêu cầu tối thiểu 10.000 sessions/tháng) làm nguồn thu chính, chiếm ~90% doanh thu. Từ ngày 7/5 đến 6/6/2024, website kiếm được 2.348,16 USD với RPM ~46,04 USD (ước tính thực tế ~30–35 USD sau điều chỉnh do chênh lệch báo cáo traffic). 
	- **Tiếp thị liên kết (Affiliate Marketing)**: Dự định tham gia các chương trình liên kết trả phí cao hơn Amazon (như ShareASale, CJ Affiliate), nhưng chưa triển khai đáng kể do tập trung vào quảng cáo. 
	- **Bài viết trả phí (Paid Guest Posts)**: Có kế hoạch chấp nhận bài viết trả phí vì không lo bị Google phạt (website không phụ thuộc SEO), nhưng chưa thực hiện trong giai đoạn này.
- **Cách dòng tiền được tạo ra**:
	- **Pinterest Traffic**: Tạo nội dung visual (pins) trên Pinterest, liên kết đến các bài viết trên website. Mỗi bài viết (~1.000–1.500 từ) chứa quảng cáo Mediavine, tạo doanh thu dựa trên impressions và sessions. Tháng 5/2024, website đạt **4,18M impressions**, **73,14k outbound clicks**, **71k sessions**, và **88k pageviews** (theo GA4), mang lại 2.348,16 USD
	- **Chi phí vận hành**:
		- Domain: ~10–15 USD/năm.
		- Hosting: Ước tính ~5–10 USD/tháng (không đề cập cụ thể, nhưng WordPress hosting thường ở mức này).
		- Kadence Theme: ~50 USD/năm (phiên bản premium). 
		- Social Sharing Plugin: ~20 USD/năm.
		- Canva Pro: ~120 USD/năm (~10 USD/tháng). 
		- Midjourney: ~10–30 USD/tháng (tùy gói).
		- Tổng chi phí ban đầu: ~200–300 USD, chủ yếu là chi phí cố định và công cụ. Không sử dụng quảng cáo trả phí, giúp giảm chi phí so với các mô hình khác.
	- **Lợi nhuận tiềm năng**: Với RPM ~30–35 USD, website có thể đạt **10.000 USD/tháng** nếu đạt mục tiêu **10M impressions/tháng** và duy trì CTR ~1,5% (tương đương ~150.000 sessions/tháng). Korni cũng có kế hoạch bán website với giá 6 con số (~100.000–500.000 USD) nếu đạt mục tiêu.
	- **Đặc điểm nổi bật**:
		- Mô hình tận dụng Pinterest để tránh sự phụ thuộc vào Google SEO, phù hợp với các ngách visual và đối tượng nữ.
		- Chi phí thấp, dễ mở rộng, nhưng rủi ro nằm ở sự bất ổn của thuật toán Pinterest (e.g., sụt giảm impressions ngày 31/5/2024) và CTR thấp của image-only pins. 
		- Kết hợp quảng cáo với tiềm năng affiliate và paid guest posts, tạo nhiều nguồn thu nhập trong tương lai.

## 3 . **CÔNG CỤ SỬ DỤNG**
- **ChatGPT/GPT-4 API**:
	- Vai trò:
		- Viết bài (~1.000–1.500 từ/bài) với nội dung dạng listicles (e.g., “60 Spring Dinner Ideas”) để thu hút click từ Pinterest.
		- Tạo tiêu đề và mô tả pin với từ khóa chính, tối ưu hóa cho Pinterest SERPs.
		- Tạo prompt chi tiết cho Midjourney để sinh hình ảnh độc đáo.
	- Đặc điểm nổi bật:
		- Sử dụng prompt cụ thể để đạt Flesch reading score >80, sử dụng ngôn ngữ rõ ràng, giọng chủ động, tránh từ ngữ quảng cáo hoặc buzzwords. Ví dụ prompt:
			![[image-71.png]]
		- Cần chỉnh sửa thủ công để tránh nội dung AI-sounding, đảm bảo tự nhiên và phù hợp với đối tượng.

- **Midjourney**: ^53d898
	- Vai trò:
		- Tạo ~95% hình ảnh cho pins và bài viết, với prompt riêng cho mỗi tiêu đề/item trong bài (e.g., không lặp lại “cozy living room decor” mà tạo prompt độc đáo cho từng ý tưởng trang trí).
		- Hỗ trợ tạo logo (kết hợp với Canva).
	- Đặc điểm nổi bật:
		- Tiết kiệm chi phí so với stock images (~0,1–0,5 USD/hình ảnh so với 1–5 USD/hình trên Shutterstock).
		- Yêu cầu kỹ năng tạo prompt và thời gian hậu kỳ (nén, định dạng, upload lên WordPress).
		- Hình ảnh độc đáo giúp tăng khả năng viral và cạnh tranh với đối thủ.

- **Canva**: ^08efee
	- Vai trò:
		- Thiết kế text overlay và collage pins với template tùy chỉnh, đảm bảo CTR cao (~3–4%).
		- Tạo logo và các yếu tố visual khác cho website.
	- Đặc điểm nổi bật:
		- Dễ sử dụng, hỗ trợ tạo pins chất lượng cao, nhưng tốn thời gian khi tạo 20–30 pins/bài (~45–60 phút cho 30 pins).
		- Template tái sử dụng giúp tiết kiệm thời gian sau giai đoạn đầu.

- **Kadence Theme (WordPress)**: ^bcf603
	- Vai trò: Giao diện website, tùy chỉnh CSS để tối ưu tốc độ và trải nghiệm người dùng.
	- Đặc điểm nổi bật: Nhẹ, nhanh, giá hợp lý (~50 USD/năm), phù hợp cho website ngách với traffic từ mạng xã hội.

- **Social Sharing Plugin**:
	- Vai trò: Hiển thị nút “Pin It” trên mọi hình ảnh trong bài viết, khuyến khích repins tự nhiên từ người dùng.
	- Đặc điểm nổi bật: Tăng khả năng viral, đặc biệt với các bài viết có nhiều hình ảnh chất lượng cao.

- **Google Analytics (GA4) và Google Search Console (GSC)**:
	- Vai trò:
		- GA4: Theo dõi sessions, pageviews, users, và thời gian tương tác trung bình.
		- GSC: Theo dõi hiệu suất tìm kiếm (dù không tập trung SEO).
	- Đặc điểm nổi bật:
		- GA4 ghi nhận traffic cao hơn Mediavine Journey (~12–13k sessions chênh lệch), cho thấy vấn đề báo cáo từ Mediavine.
		- Hỗ trợ phân tích hành vi người dùng để tối ưu hóa nội dung.

- **Buffer (dự kiến)**:
	- Vai trò: Lên lịch đăng pins tự động.
	- Đặc điểm nổi bật: Giá rẻ (~6 USD/tháng), giới hạn 2.000 pins, nhưng korni chưa sử dụng do tự đăng pins để kiểm soát chất lượng.

- **Keywords Everywhere**: ^4bcfa3
	- Vai trò: Nghiên cứu từ khóa trên Pinterest, xác định các từ khóa có lượng tìm kiếm cao.
	- Đặc điểm nổi bật: Dữ liệu không hoàn toàn chính xác, nhưng hữu ích để định hướng từ khóa ban đầu.

- **Pinterest Trends**: ^7899c8
	- Vai trò: Phân tích xu hướng tìm kiếm trên Pinterest, nhắm vào các chủ đề phổ biến (e.g., “spring dinner ideas”).
	- Đặc điểm nổi bật: Miễn phí, cung cấp dữ liệu theo mùa và khu vực, nhưng cần kết hợp với Keywords Everywhere để tối ưu.

## 4 . **QUY TRÌNH TRIỂN KHAI**
- <u>Giai đoạn 1: Thiết lập và khởi động (1/2024)</u>
	- **Hành động**
		- **Đăng ký domain**: chọn domain ngắn, dễ nhớ (10-15 USD)
		- **Cài đặt Website**: Sử dụng WordPress với Kadence theme ([[#^bcf603]]), tùy chỉnh CSS, cài plugin chia sẻ mạng xã hội (~20 USD/năm).
		- **Tạo logo**: Kết hợp Canva ([[#^08efee]]) và Midjourney ([[#^53d898]]) để thiết kế logo đơn giản nhưng chuyên nghiệp. 
		- **Thiết lập Pinterest**: Tạo tài khoản, xác định ngách nhắm đến phụ nữ (lifestyle, home decor, fashion) nhưng không quá “nữ tính” để phù hợp với sở thích cá nhân.
		- **Nghiên cứu từ khóa**: Sử dụng Pinterest Trends ([[#^7899c8]]) và Keywords Everywhere ([[#^4bcfa3]]), xác định từ khóa có lượng tìm kiếm cao nhưng cạnh tranh vừa phải.
		- **Tạo nội dung ban đầu**: Viết ~10 bài viết (~1.000–1.500 từ) với ChatGPT, tạo 50+ pins (5–10 pins/bài) bằng Canva, đăng ~10–15 pins/ngày.
	
	- **Chi tiết**
		- Tập trung vào nội dung visual (pins) thay vì SEO. Mỗi pin chứa từ khóa chính trong tiêu đề và mô tả, liên kết đến bài viết trên website.
		- Gặp vấn đề “sandbox” của Pinterest (pins không được đẩy lên home feed), tương tự Google, nhưng vẫn duy trì đăng pins đều đặn.
		- Hình ảnh chủ yếu từ Midjourney (~95%), một số từ Instagram (~5%, có rủi ro bản quyền).
	
	- **Kết quả**
		- Website hoàn thiện với cấu trúc silo (4 danh mục chính, nhiều danh mục phụ). 
		- Tài khoản Pinterest đạt **1,96k impressions**, **117 engagements**, **37 outbound clicks**, **10 saves** (26–27/1/2024).
		- Traffic website gần như bằng 0, nhưng đặt nền tảng cho tăng trưởng.

- <u>Giai đoạn 2: Tăng trưởng và tối ưu hóa (2 - 3/2024)</u>
	- **Hành động**
		- **Tăng tần suất đăng pins**: Từ ~10–15 pins/ngày lên ~20–30 pins/ngày, tập trung vào text overlay/collage pins sau khi nhận thấy image-only pins có CTR thấp (~0,4–0,5% so với ~3–4% của text overlay).
		- **Tạo nội dung mới**: Viết ~10–15 bài viết mới, mỗi bài có 5–10 pins, sử dụng Midjourney để tạo hình ảnh độc đáo.
		- **Thử nghiệm tài khoản thứ hai**: Tạo tài khoản Pinterest thứ hai trong ngách khác, nhưng thất bại (chỉ đạt 10–30 impressions/ngày) do thiếu từ khóa cụ thể và nghi ngờ bị shadow ban.
		- **Nghiên cứu đối thủ cạnh tranh**: Phân tích tài khoản thành công trên X (e.g., tài khoản 4,4M views với <1.000 pins) và Pinterest, học cách thiết kế pins và chọn từ khóa.
		- [ ] **Áp dụng Mediavine Journey**: Nộp đơn cho Mediavine Journey, chờ domain đủ 4 tháng tuổi (yêu cầu từ tháng 5/2024).
	
	- **Chi tiết**
		- **Gặp vấn đề với thuật toán Pinterest**, đặc biệt là giai đoạn đầu khi pins không được đẩy lên home feed. Korni kiên trì đăng pins đều đặn và thử nghiệm các loại pin khác nhau.
		- **Tối ưu hóa** mô tả pin với từ khóa chính, sử dụng ChatGPT để viết tự nhiên hơn (e.g., “Spring dinner ideas for family” thay vì “Dinner ideas”).
		- **Nhận thấy cuối tuần** (thứ Bảy, Chủ Nhật) có traffic cao hơn, tập trung đăng pins vào các khung giờ sáng sớm và tối.
	
	- **Kết quả**
		- **Tháng 2/2024**: 184,52k impressions, 9,84k engagements, 2,15k outbound clicks, 910 saves, 75,25k total audience (Pinterest). Website đạt 3,2k pageviews, 2,3k sessions, 2,1k users (GA4).
		- **Tháng 3/2024**: Đạt đỉnh 25,22k impressions/ngày (24/3), 268 outbound clicks,150 saves. Traffic tăng mạnh, nhưng CTR giảm còn ~0,75% do ảnh hưởng của image-only pins.
		- **Tài khoản thứ hai** không hiệu quả, bị bỏ rơi.

- <u>Giai đoạn 3: Đột phá và kiếm tiền (4 - 6/2024)</u>
	- **Hành động**
		- **Đẩy mạnh đăng pins**: Duy trì ~30 pins/ngày, tập trung vào text overlay/collage pins với thiết kế Canva có CTR cao (~1–1,5%). Giảm sử dụng image-only pins do CTR thấp.
		- **Được chấp nhận vào Mediavine Journey**: Bắt đầu kiếm tiền từ quảng cáo (tháng 5/2024), với 2.348,16 USD từ 7/5 đến 6/6/2024.
		- **Tối ưu hóa nội dung**: Tập trung vào listicles (e.g., “60 Spring Dinner Ideas” Hoặc “20 Things To Do in Amsterdam”) để tăng CTR và traffic. Mỗi bài viết được tối ưu với hình ảnh từ Midjourney và nút “Pin It” để khuyến khích repins.
		- **Đối mặt với thuật toán Pinterest**: Ngày 31/5/2024, nhiều pins giảm về 0 impressions, nghi ngờ bị “partial shadow ban”. Một số pins phục hồi nhưng impressions giảm đáng kể.
		- **Lên kế hoạch đa dạng hóa**: Xem xét các nguồn traffic khác (Facebook, Reddit, Flipboard) để giảm rủi ro từ Pinterest.
	
	- **Chi tiết**
		- **Đạt các cột mốc ấn tượng**: 50,76k impressions, 699 outbound clicks (14/4/2024); 100,61k impressions, 1,53k outbound clicks (28/4/2024); 3.114 pageviews/ngày (18/5/2024).
		- **Tháng 5/2024** ghi nhận 4,18M impressions, 73,14k outbound clicks, 9,54k saves, 71k sessions, 88k pageviews (GA4).
		- **Vấn đề báo cáo traffic**: GA4 ghi nhận ~12–13k sessions cao hơn Mediavine Journey, ảnh hưởng đến RPM thực tế (~30–35 USD thay vì ~46,04 USD).
		- **Tài khoản thứ hai bị bỏ rơi hoàn toàn**, tập trung toàn bộ vào tài khoản chính.
	
	- **Kết quả**
		- **Doanh thu**: 2.348,16 USD (tháng 5/2024) từ Mediavine Journey.
		- **Traffic**: 4,18M impressions, 73,14k outbound clicks, 71k sessions, 88k pageviews (tháng 5/2024).
		- **Tổng cộng** ~550 pins trên tài khoản chính, đạt 3.114 pageviews/ngày (18/5/2024).
		- **Chưa đạt mục tiêu** 10M impressions/tháng, nhưng tiến gần với 4,18M impressions trong tháng 5.

## 5 . **KẾT QUẢ ĐẠT ĐƯỢC**
- <u>DOANH THU</u>
	- **2.348,16 USD** từ **Mediavine Journey** (7/5–6/6/2024), với RPM ~46,04 USD (ước tính thực tế ~30–35 USD do chênh lệch báo cáo).
	- **Chưa có doanh thu** từ *affiliate* hoặc *paid guest posts*, nhưng có tiềm năng trong tương lai.

- <u>KHỐI LƯỢNG HOẠT ĐỘNG</u>
	- **Pinterest** (tháng 5/2024):
		- **Impressions**: 4,18M (tăng 137% so với tháng trước).
		- **Engagements**: 259,97k (tăng 150%).
		- **Outbound clicks**: 73,14k (tăng 218%).
		- **Saves**: 9,54k (tăng 49%).
		- **Total audience**: 1,75M (tăng 111%).
		- **Engaged audience**: 150,05k (tăng 134%).
	- **Website** (GA4, tháng 5/2024):
		- **Pageviews**: 88k (tăng 210,8%).
		- **Sessions**: 71k (tăng 181,2%).
		- **Users**: 67k (tăng 187,1%).
		- **Thời gian tương tác trung bình**: 43 giây (giảm 16,8%).
		- **Đỉnh cao**: 3.114 pageviews/ngày (18/5/2024).
	- **Số lượng pins**: ~550 pins trên tài khoản chính, ~200 pins trên tài khoản thứ hai (bị bỏ rơi).

- <u>THÀNH QUẢ KHÁC</u>
	- **Xây dựng website ngách** thành công, nhắm đúng đối tượng nữ trên Pinterest (82,59% người dùng là nữ).
	- **Được chấp nhận** vào Mediavine Journey, tạo dòng tiền ổn định từ quảng cáo.
	- **Phát triển kỹ năng** tối ưu hóa pins (text overlay/collage pins có CTR cao), nghiên cứu đối thủ cạnh tranh, và sử dụng AI hiệu quả (ChatGPT, Midjourney).
	- **Xây dựng hệ thống** nội dung bền vững với template Canva và prompt ChatGPT, giảm thời gian sản xuất.

- <u>THÁCH THỨC</u>
	- **Thuật toán Pinterest bất ổn**: Sụt giảm impressions ngày 31/5/2024 (nhiều pins về 0 impressions), nghi ngờ “partial shadow ban”.
	- **CTR thấp** của image-only pins: ~0,4–0,5% so với ~3–4% của text overlay pins, làm tăng số impressions cần thiết để đạt 50k sessions.
	- **Thời gian tạo nội dung**: ~5–6 giờ/ngày cho việc viết bài, tạo pins, và quản lý website.
	- **Chênh lệch báo cáo traffic**: GA4 ghi nhận ~12–13k sessions cao hơn Mediavine Journey, ảnh hưởng đến ước tính doanh thu.

## 6. **BÀI HỌC RÚT RA**
- <u>Điều làm nên thành công chính</u>
	- **Tập trung vào Pinterest**: Bỏ qua Google SEO, tận dụng đặc điểm visual và đối tượng nữ của Pinterest để thu hút traffic nhanh chóng (4,18M impressions trong tháng 5/2024).
	- **Text overlay/collage pins**: Có CTR cao (~3–4%) so với image-only pins (~0,4–0,5%), giúp tối ưu hóa traffic với số lượng pins ít hơn. Ví dụ: Một pin text overlay với 1.000 impressions có thể tạo 30–40 clicks, trong khi image-only pin chỉ tạo 4–5 clicks.
	- **Nghiên cứu đối thủ cạnh tranh**: Phân tích tài khoản thành công trên X (e.g., tài khoản 4,4M views với <1.000 pins) và Pinterest, học cách thiết kế pins, chọn từ khóa, và tối ưu hóa nội dung. Korni sử dụng kỹ năng “reverse engineering” để tìm tài khoản đối thủ và phân tích chiến lược của họ.
	- **Nội dung listicles**: Các bài viết dạng “60 Spring Dinner Ideas” hoặc “20 Things To Do in Amsterdam” thu hút click mạnh mẽ, phù hợp với hành vi người dùng Pinterest.

- <u>Có gì sáng tạo khác biệt</u>
	- **Sử dụng Midjourney hiệu quả**: Tạo ~95% hình ảnh độc đáo, giảm chi phí và tăng tính cạnh tranh so với stock images. Prompt riêng cho mỗi tiêu đề/item giúp hình ảnh đa dạng và phù hợp nội dung.
	- **Tối ưu hóa repins**: Cài nút “Pin It” trên mọi hình ảnh trong bài viết, khuyến khích repins tự nhiên, tăng khả năng viral mà không cần thêm chi phí.
	- **Kết hợp AI và công cụ truyền thống**: Sử dụng ChatGPT để viết bài và tạo prompt, Canva để thiết kế pins, và Midjourney để sinh hình ảnh, tạo quy trình sản xuất nội dung hiệu quả.
	- **Chiến lược “Build in Public” nhẹ**: Dù không công khai ngách, korni chia sẻ chi tiết tiến độ trên BlackHatWorld, thu hút sự chú ý và nhận phản hồi từ cộng đồng.

- <u>Thách thức và cách vượt qua</u>
	- **Thách thức**: Thuật toán Pinterest bất ổn, gây sụt giảm impressions (31/5/2024). 
		- **Giải pháp**: Tiếp tục đăng pins đều đặn (~30 pins/ngày), tập trung vào text overlay pins, và lên kế hoạch đa dạng hóa traffic (Facebook, Reddit, Flipboard).
	- **Thách thức**: Tốn thời gian tạo pins và nội dung (~5–6 giờ/ngày). 
		- **Giải pháp**: Sử dụng template Canva, prompt ChatGPT hiệu quả, và cân nhắc công cụ tự động như Pingenerator hoặc BlogToPin (dù chưa triển khai).
	- **Thách thức**: CTR thấp của image-only pins. 
		- **Giải pháp**: Chuyển hoàn toàn sang text overlay/collage pins, ưu tiên nội dung listicles và thiết kế “inspire action” (theo Tony Hill).
	- **Thách thức**: Chênh lệch báo cáo traffic giữa GA4 và Mediavine Journey. 
		- **Giải pháp**: Chấp nhận sai số, tập trung tăng traffic để bù đắp và cải thiện RPM

- <u>Gợi ý áp dụng cho người mới</u>
	- Bắt đầu nhỏ:
		- **Đăng ký domain** (~10 USD) và **hosting** (~5 USD/tháng), sử dụng WordPress với Kadence theme miễn phí.
		- **Tạo tài khoản Pinterest**, chọn ngách visual nhắm đến phụ nữ (e.g., home decor, recipes, fashion).
		- **Viết 5–10 bài** (~1.000 từ) với ChatGPT, tạo 5 pins/bài bằng Canva (dùng tài khoản miễn phí).
	
	- Xây dựng hệ thống:
		- **Đăng ~10–15 pins/ngày** trong tháng đầu để “làm nóng” tài khoản, tăng lên ~20–30 pins/ngày sau 2 tháng.
		- **Sử dụng Midjourney** (~10 USD/tháng) để tạo hình ảnh, tập trung vào text overlay/collage pins.
		- **Cài plugin chia sẻ mạng xã hội** (~20 USD/năm) để thêm nút “Pin It” trên hình ảnh. Sử dụng Pinterest Trends và Keywords Everywhere để tìm từ khóa (e.g., “spring dinner ideas”)
	
	- Tiếp thị:
		- **Đăng pins vào khung giờ** đông người dùng (sáng sớm, tối, đặc biệt cuối tuần).
		- **Tạo nội dung listicles** (e.g., “20 Summer Outfit Ideas” hoặc “60 Spring Dinner Ideas”) để thu hút click.
		- **Nghiên cứu đối thủ bằng** cách tìm tài khoản thành công trên Pinterest hoặc X, phân tích thiết kế pins và từ khóa
	
	- Chi phí ban đầu: 
		- ~50–100 USD (domain, hosting, Canva Pro, Midjourney). Có thể dùng Canva miễn phí và Midjourney trial để giảm chi phí.
	
	- Học kỹ năng:
		- Xem hướng dẫn Canva/Midjourney trên YouTube.
		- Đọc tài liệu **Pinterest for Business** và **Mediavine Journey**.
		- Tham gia **BlackHatWorld** để học mẹo tối ưu hóa pins và nghiên cứu đối thủ.
	
	- Lưu ý: 
		- Tránh image-only pins để đảm bảo CTR cao.
		- Đăng nội dung độc đáo, tránh sao chép để giảm rủi ro **shadow ban**.
		- Kiên nhẫn trong 3–6 tháng, vì Pinterest cần thời gian để đẩy pins lên home feed

## 7. REFERENCES
Link gốc: https://www.blackhatworld.com/seo/journey-growing-a-niche-website-from-scratch-with-pinterest-as-a-main-traffic-source-goal-10m-monthly-pinterest-views.1561227/

# <u>Case study 4: Faceless YouTube Crypto – Lãi 2.000 USD/Tháng (CS26)</u>
## 1 . THÔNG TIN TỔNG QUAN
- **Thành tựu hiện tại (tính đến 5/2025)**:
	- YouTube: 21,355 subscriber (người đăng ký), 16,800 views/28 ngày, 1,200 giờ xem, +217 sub mới.
	- Doanh thu: ~$2,000/tháng (~$800 từ tài trợ Sniperoo, $800+ từ affiliate, $150 từ quảng cáo YouTube).
	- Khán giả: 99.2% nam, 64% từ 25–44 tuổi, chủ yếu ở Mỹ.
	- Chi phí: ~$50/tháng (tool chỉnh sửa, proxy, internet).
	- Lợi nhuận: ~$1,950/tháng (tỷ suất 97.5%).
- **Mục tiêu**: $10,000/tháng (~230 triệu VND) trong 1–2 năm tới, ra mắt platform phân tích memecoin (đồng tiền mã hóa vui nhộn, như Dogecoin) vào 6/2025.








































