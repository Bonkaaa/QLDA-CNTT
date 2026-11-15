# Tóm Tắt Kiến Thức Trọng Tâm — Bài 2: Quản Lý Dự Án Công Nghệ Thông Tin

Tài liệu hệ thống hóa toàn bộ nội dung cốt lõi của Bài 2 (*Quản lý dự án CNTT*, Khoa Toán - Tin, Đại học Bách khoa Hà Nội) phục vụ ôn tập thi giữa kỳ. Cấu trúc bài học gồm hai mảng lớn: bản chất và các khuynh hướng mới của **dự án CNTT**, cùng hệ thống nhân tố, độ đo, giai đoạn và quy trình tổng thể trong **quản lý dự án CNTT**.

---

## 1. Dự án CNTT: Bản chất, Đặc thù và Các Khuynh hướng Hiện đại

Để quản lý hiệu quả một dự án công nghệ thông tin, trước hết cần nắm vững định nghĩa dự án nói chung và nhận diện những yếu tố khiến dự án CNTT khác biệt so với các loại hình dự án truyền thống.

### 1.1. Khái niệm, Ràng buộc và Tính chất của Dự án

Theo bài giảng Bài 2, **dự án** được định nghĩa là những nỗ lực có thời hạn nhằm tạo ra một sản phẩm hoặc dịch vụ duy nhất. Mọi dự án đều vận hành dưới ba **ràng buộc** cơ bản gồm **mục tiêu**, **thời gian** và **kinh phí**.

Bên cạnh định nghĩa và ba ràng buộc, tài liệu chỉ ra tám tính chất đặc trưng giúp phân biệt dự án với các hoạt động vận hành thường nhật:

- **Khác hoạt động nghiệp vụ**: Dự án không phải là công việc lặp đi lặp lại hằng ngày của tổ chức.
- **Kết quả có tính mới**: Sản phẩm hoặc dịch vụ đầu ra mang tính độc nhất.
- **Kết thúc sau một khoảng thời gian**: Dự án luôn có điểm dừng xác định chứ không kéo dài vô thời hạn.
- **Có độ bất định và rủi ro**: Do tính mới và sự biến động trong quá trình thực hiện, dự án luôn tiềm ẩn yếu tố không chắc chắn.
- **Có mục đích, mục tiêu, kết quả xác định**: Các đích đến của dự án phải được định hình rõ ràng.
- **Có quy trình phát triển riêng**: Mỗi dự án đòi hỏi lộ trình triển khai phù hợp thay vì sao chép nguyên xi quy trình vận hành sẵn có.
- **Có mối quan hệ phức tạp**: Dự án liên quan đến nhiều bên, nhiều bộ phận và yếu tố đan xen.
- **Có môi trường quản lý linh hoạt**: Cách thức điều hành cần khả năng thích ứng trước các biến động thực tế.

Dự án CNTT cũng là một loại dự án, nhưng do những đặc điểm riêng của lĩnh vực CNTT nên bản thân dự án và công tác quản lý dự án CNTT mang nhiều sắc thái đặc thù.

### 1.2. Ba Nguồn gốc Tạo nên Đặc điểm Khác biệt của Dự án CNTT

Ngành CNTT là một ngành công nghệ non trẻ nhưng phát triển nhanh, mang nhiều tính sáng tạo và tác động đến hầu hết mọi khía cạnh của doanh nghiệp cũng như xã hội (từ phần cứng, máy tính, mạng, máy chủ, truyền thông, internet, cơ sở dữ liệu, ứng dụng, thiết kế phần mềm, bảo mật đến hỗ trợ). Việc triển khai và quản lý dự án CNTT chịu ảnh hưởng sâu sắc của quy trình phát triển sản phẩm, chẳng hạn như **mô hình thác nước** (*Waterfall model*: đi tuần tự qua *Analysis* $\rightarrow$ *Design* $\rightarrow$ *Construction* $\rightarrow$ *Testing* $\rightarrow$ *Support*) hoặc **mô hình xoắn ốc** (*Spiral model*: lặp vòng qua các góc phần tư *Analysis*, *Design*, *Implementation*, *Testing*).

Những nét đặc thù của dự án CNTT xuất phát từ ba nhóm nguyên nhân cốt lõi được tổng hợp trong bảng dưới đây.

| Nguồn gốc đặc điểm | Các biểu hiện cụ thể trong dự án CNTT | Hệ quả đối với công tác quản lý |
| :--- | :--- | :--- |
| **Bản chất của dự án CNTT** | Đa dạng về độ lớn, độ phức tạp, sản phẩm, lĩnh vực ứng dụng và yêu cầu nguồn lực (từ triển khai 1 thiết bị với 1 phần mềm cài sẵn đến dự án vài trăm nhân sự kéo dài tới 10 năm); có trong hầu hết ngành nghề và thâm nhập hầu hết nghiệp vụ kinh doanh; làm thay đổi nhiều hoặc toàn bộ quy trình nghiệp vụ doanh nghiệp; yêu cầu phần mềm thường không rõ và hay thay đổi; kết quả còn trừu tượng với nhiều nhà đầu tư; khó xây dựng độ đo. | Khó cố định phạm vi từ đầu; đòi hỏi giao tiếp chặt chẽ với nhà đầu tư và người dùng nghiệp vụ; việc định lượng tiến độ và chất lượng gặp nhiều thách thức. |
| **Đặc điểm thành viên dự án CNTT** | Nền tảng và kỹ năng đa dạng; nhân sự CNTT có sự xáo trộn nhiều; một số dự án chỉ cần kỹ năng chuyên gia đặc biệt trong thời gian ngắn; doanh nghiệp thường kết hợp nhân sự từ các lĩnh vực khác như kinh doanh, toán học hoặc nghệ thuật để có đa góc nhìn. | Sự đa dạng kiến thức và kỹ năng tạo ra cả ưu điểm (sáng tạo, đa chiều) lẫn nhược điểm (khó đồng bộ, biến động nhân sự). |
| **Sự đa dạng về công nghệ** | Sử dụng nhiều công nghệ đa dạng và thay đổi rất nhanh; sự khác biệt tri thức kỹ thuật gây khó khăn trao đổi giữa các chuyên gia; công nghệ mới rút ngắn thời gian phát triển, sản xuất, phân phối nhưng dễ làm xáo trộn dự án; xu hướng mã nguồn mở làm thay đổi nhiều dự án. | Cần liên tục cập nhật công nghệ và thiết lập ngôn ngữ chung giữa các chuyên gia để tránh gián đoạn dự án. |

### 1.3. Bốn Khuynh hướng Gần đây Ảnh hưởng tới Quản lý Dự án CNTT

Thực tiễn quản lý dự án CNTT hiện đại chịu tác động mạnh mẽ từ bốn xu thế lớn: **toàn cầu hóa**, **thuê ngoài**, **nhóm ảo** và **quản lý dự án linh hoạt (Agile)**.

#### Toàn cầu hóa (Globalization)

Toàn cầu hóa giúp các dự án không còn bị giới hạn bởi không gian địa lý, song cũng đặt ra bốn vấn đề lớn về **trao đổi thông tin**, **sự tin cậy**, **các thông lệ làm việc chung** và **các công cụ**. Để phát huy ưu điểm và giải quyết các trở ngại này, bài giảng nêu năm đề xuất hành động:

1. Áp dụng các nguyên tắc dự án tốt hơn.
2. Suy nghĩ toàn cầu, nhưng hành động cục bộ.
3. Xem xét việc cộng tác dựa trên sự tiêu chuẩn hóa.
4. Giữ động lực phát triển cho dự án.
5. Sử dụng các công cụ và công nghệ mới hơn.

#### Thuê ngoài (Outsourcing)

Thuê ngoài là việc thuê và sử dụng các nguồn lực bên ngoài công ty hoặc ngoài quốc gia nhằm duy trì khả năng cạnh tranh và tạo lợi thế, chẳng hạn như tìm cách giảm chi phí. Do hoạt động này có thể chưa phổ biến ở một số quốc gia, nhà quản lý dự án cần làm quen với nhiều vấn đề toàn cầu và mua sắm.

#### Nhóm ảo (Virtual Teams)

Nhóm ảo là hình thức làm việc trên không gian mạng mà các thành viên không cần nắm rõ con người vật lý của nhau. Mô hình này mang lại đồng thời những lợi thế rõ rệt và những rủi ro đặc thù về giao tiếp, được đối chiếu dưới đây.

| Khía cạnh | Nội dung chi tiết trong tài liệu |
| :--- | :--- |
| **Ưu điểm** | Giảm chi phí (không đòi hỏi không gian văn phòng hay các hỗ trợ khác); cung cấp thêm kiến thức chuyên môn và tính linh hoạt, tăng khả năng cạnh tranh và khả năng đáp ứng bằng cách dùng thành viên khắp nơi trên thế giới làm việc trong tất cả khung thời gian ngày hay đêm; tăng cân bằng giữa công việc và cuộc sống nhờ giảm giờ văn phòng cố định và thời gian đi lại. |
| **Nhược điểm** | Cô lập các thành viên; gia tăng tiềm năng về lỗi do trao đổi thông tin; giảm khả năng kết nối mạng và trao đổi thông tin không chính thức giữa các thành viên; tăng sự phụ thuộc vào công nghệ. |
| **Nhân tố thành công** | Quy trình của nhóm; lòng tin và mối quan hệ; phong cách lãnh đạo; lựa chọn thành viên nhóm. |

#### Quản lý dự án linh hoạt (Agile), Scrum và Kanban

Trước đây, dự án phần mềm thường áp dụng tiếp cận **thác nước** (*Waterfall*). Tuy nhiên, khi công nghệ và nghiệp vụ trở nên phức tạp, yêu cầu chưa xác định rõ hoặc thay đổi liên tục, cách tiếp cận thác nước trở nên khó sử dụng. Mặc dù *Agile* mang nghĩa có thể nhanh và dễ, nhiều người cảm thấy việc quản lý dự án như vậy không cho phép thực hiện công việc nhanh và dễ; bản chất của Agile ngày nay là tiếp cận trong đó **yêu cầu và giải pháp được hình thành thông qua sự cộng tác**.

Tháng **2/2001**, nhóm **17 người** gọi là liên minh Agile (*Agile Alliance*) đã phát triển và đồng ý **Tuyên ngôn về phát triển linh hoạt** (*Agile Manifesto*). Tuyên ngôn khẳng định bốn cặp giá trị (đánh giá cao các mục bên trái hơn bên phải, mặc dù các điều bên phải vẫn còn giá trị):

- **Cá nhân và tương tác** hơn là *quy trình và công cụ*.
- **Phần mềm chạy tốt** hơn là *tài liệu đầy đủ*.
- **Cộng tác với khách hàng** hơn là *đàm phán hợp đồng*.
- **Phản hồi với thay đổi** hơn là *bám sát kế hoạch*.

Trong hệ sinh thái Agile, hai phương pháp/kỹ thuật tiêu biểu được trình bày là **Scrum** và **Kanban**:

- **Scrum**: Theo liên minh Scrum, đây là phương pháp phát triển phần mềm linh hoạt hàng đầu cho các dự án có phạm vi phức tạp và sáng tạo. Thuật ngữ này được đặt ra năm **1986** trong nghiên cứu trên tạp chí *Harvard Business Review*, ở đó so sánh hiệu năng cao của các nhóm đa chức năng với đội hình *Scrum* được sử dụng bởi các đội **bóng bầu dục**. Chu trình Scrum gồm bốn bước lặp lại cho đến khi hoàn thành dự án:
  1. **Product Owner** tạo danh sách mong muốn ưu tiên gọi là **Product Backlog**.
  2. **Nhóm dự án** (*Project Team*) tạo **Sprint Backlog**.
  3. Các nhóm họp **Daily Scrum** hằng ngày trong suốt mỗi **Sprint kéo dài 2–4 tuần**.
  4. Sprint tạo ra phần gia tăng sản phẩm hữu ích có khả năng bàn giao (*Potentially shippable product increment*) và thực hiện **Sprint Review**.
- **Kanban**: Là kỹ thuật có thể được sử dụng cùng với Scrum, được phát triển bởi công ty **Toyota ở Nhật**. Kanban sử dụng các dấu hiệu trực quan để hướng dẫn quy trình, với thẻ Kanban thể hiện công việc mới (**Cần làm**), công việc đang thực hiện (**Đang làm**) và công việc đã hoàn thành (**Hoàn thành**).

Về mối quan hệ với chuẩn mực quản lý dự án: sách **PMBOK® Guide** mô tả các phương pháp hay nhất về *những việc nên làm* để quản lý dự án, còn **Agile** là phương pháp luận mô tả *cách* quản lý dự án. Viện Quản lý Dự án (**PMI**) đã ghi nhận sự quan tâm gia tăng đối với Agile và đưa ra chứng chỉ mới từ năm **2011** là **Chứng nhận thực hành Agile** (*Agile Certified Practitioner* — **ACP**). Các nhà quản lý dự án dày dạn kinh nghiệm hiểu rằng họ luôn có lựa chọn tùy biến cách quản lý dự án, nhưng việc quản lý dự án là không đơn giản, thậm chí đã sử dụng Agile.

---

## 2. Quản lý Dự án CNTT: Nhân tố Ảnh hưởng, Độ đo và Quy trình Tổng thể

Phần thứ hai của bài học đi sâu vào các yếu tố tác động tới điều hành dự án, hệ thống độ đo định lượng phần mềm và các mô hình giai đoạn triển khai từ ý tưởng đến kết thúc.

### 2.1. Tám Nhóm Nhân tố Ảnh hưởng tới Quản lý Dự án CNTT

Công tác quản lý dự án CNTT chịu sự chi phối đồng thời của tám nhóm nhân tố sau đây:

1. **Lĩnh vực nghiệp vụ**: Phức tạp hay đơn giản, phạm vi, yêu cầu xử lý, tính ổn định của các yêu cầu.
2. **Môi trường làm việc**: Thuận lợi hay không thuận lợi, tính pháp lý liên quan, tính quốc tế, công cụ sử dụng hiện đại hay truyền thống.
3. **Độ phức tạp của phần mềm**: Phần mềm lớn có thuật toán xử lý phức tạp, nhiều mô đun, nhiều dòng lệnh, nhiều giao diện; CSDL quan hệ hay khác; CSDL tập trung hay phân tán.
4. **Năng lực nhân viên**: Lòng yêu nghề, tính cần cù, sáng tạo, phong cách làm việc, khả năng nắm bắt vấn đề, trình độ chuyên môn có được đào tạo bài bản hay không, khả năng diễn đạt vấn đề có bị hạn chế hay không, khả năng làm việc nhóm, từng tham gia dự án trước đó, có ý thức về việc bảo hành và bảo trì phần mềm.
5. **Thời gian**: Dài hay ngắn; thời gian ngắn phải làm gấp dễ dẫn đến nhiều lỗi.
6. **Công nghệ**: Cũ hay mới, đơn giản hay phức tạp, có sẵn hay không có sẵn, nhân viên thành thạo hay không thành thạo, công nghệ client/server hay công nghệ web.
7. **Kỹ năng quản lý**: Trình độ quản lý, được đào tạo bài bản, đội ngũ hùng hậu, có chuyên gia giỏi làm cùng không, được huấn luyện đầy đủ.
8. **Tính rủi ro**: Các khả năng, tình huống xảy ra được đo lường trước đến đâu.

### 2.2. Hệ thống Độ đo Phần mềm (Software Metrics)

**Độ đo phần mềm** dùng để định lượng hóa nhằm đánh giá tiến độ, độ ổn định và chất lượng của việc phát triển phần mềm, qua đó giúp các nhà quản lý hiểu rõ hơn về sản phẩm được tạo ra. Tài liệu phân loại độ đo thành ba nhóm chính: **độ đo theo quy mô**, **độ đo theo chức năng** và **độ đo chất lượng**.

#### Độ đo theo quy mô / kích cỡ (Đo trực tiếp)

Đây là cách đo **trực tiếp** cho phần mềm và tiến trình phát triển phần mềm dựa trên đơn vị **KSLOC** (*Kilo Source Lines Of Code* — nghìn dòng lệnh nguồn). Bốn công thức chuẩn theo quy mô gồm:

$$\text{Hiệu năng} = \frac{\text{KSLOC}}{\text{Công sức}}, \qquad \text{Chất lượng} = \frac{\text{Lỗi}}{\text{KSLOC}}$$

$$\text{Chi phí} = \frac{\$}{\text{KSLOC}}, \qquad \text{Tư liệu} = \frac{\text{Số trang tư liệu}}{\text{KSLOC}}$$

Áp dụng với bảng số liệu mẫu **Dự án ABC** trong bài giảng (Công sức = $12$ người-tháng, Chi phí = $84$ nghìn USD, Quy mô = $12{,}1$ KSLOC, Trang tư liệu = $365$, Lỗi = $29$, Người = $3$), các chỉ số thu được lần lượt là: hiệu năng $\approx 1{,}01$ KSLOC/người-tháng, chất lượng $\approx 2{,}40$ lỗi/KSLOC, chi phí $\approx 6{,}94$ nghìn USD/KSLOC và mật độ tư liệu $\approx 30{,}17$ trang/KSLOC.

#### Độ đo theo chức năng (Đo gián tiếp)

Đây là cách đo **gián tiếp** cho phần mềm và tiến trình phát triển phần mềm, tập trung vào chức năng hay tiện ích của chương trình thông qua **"điểm chức năng"** (*Function Point* — **FP**). Điểm chức năng được tính dựa trên kinh nghiệm và số đo các thành phần: **số lượng đầu vào, đầu ra, yêu cầu, số file trao đổi, số giao diện và độ phức tạp thuật toán**. Bốn công thức theo chức năng tương ứng gồm:

$$\text{Hiệu năng} = \frac{\text{FP}}{\text{người-tháng}}, \qquad \text{Chất lượng} = \frac{\text{Khiếm khuyết}}{\text{FP}}$$

$$\text{Chi phí} = \frac{\$}{\text{FP}}, \qquad \text{Tư liệu} = \frac{\text{Số trang tư liệu}}{\text{FP}}$$

#### Độ đo chất lượng

Nhóm độ đo này đánh giá bốn thuộc tính chất lượng cốt lõi của phần mềm với cách xác định riêng biệt như sau:

| Thuộc tính chất lượng | Ý nghĩa và phạm vi đánh giá | Cách xác định / Đo lường |
| :--- | :--- | :--- |
| **Tính đúng đắn** | Mức độ chính xác của phần mềm so với yêu cầu. | Đo bằng số khiếm khuyết trên KSLOC. |
| **Tính bảo trì** | Mức độ chương trình có thể sửa được nếu gặp lỗi, thích nghi nếu môi trường thay đổi và nâng cao nếu khách hàng muốn đổi yêu cầu. | **Không đo được trực tiếp**, phải đo **gián tiếp** qua thời gian hay chi phí. |
| **Tính toàn vẹn** | Khả năng trụ được của hệ thống trước sự tấn công. | Xác định qua ước lượng bằng chứng kinh nghiệm của sự đe dọa và độ an toàn. |
| **Tính sử dụng được** | Mức độ thân thiện đối với người dùng. | Xác định qua thời gian học và hiệu năng của người dùng trung bình. |

### 2.3. Năm Giai đoạn của một Dự án CNTT

Xét theo vòng đời quản lý, một dự án CNTT trải qua năm giai đoạn tuần tự với các nhiệm vụ trọng tâm được tổng hợp dưới đây.

1. **Giai đoạn hình thành ý tưởng**: Xác định bức tranh toàn cảnh về mục tiêu, kết quả cuối cùng và phương pháp thực hiện kết quả đó; tập hợp số liệu, xác định nhu cầu, đánh giá độ rủi ro, ước lượng nguồn lực, so sánh lựa chọn dự án.
2. **Giai đoạn lập kế hoạch**: Thành lập nhóm dự án, xác định cấu trúc tổ chức dự án; lập kế hoạch tổng thể; phân tích công việc của dự án; lập kế hoạch tiến độ về thời gian; lập kế hoạch ngân sách; thiết kế và quy trình sản xuất phần mềm; lập kế hoạch nguồn lực cần thiết; lập kế hoạch chi phí và công sức; đề xuất phê chuẩn thực hiện.
3. **Giai đoạn tổ chức dự án**: Tài liệu dự án; phê duyệt ngân sách, bổ nhiệm, tuyển dụng, thành lập các bộ phận, chuẩn bị cơ sở vật chất, thực hiện các bảo đảm pháp lý. Các tổ dự án được thành lập dựa trên quyết định thành lập dự án, còn việc phân bổ tài nguyên dựa trên kế hoạch ngân sách được duyệt.
4. **Giai đoạn thực hiện và kiểm soát**: Quản lý các lĩnh vực hoạt động thực hiện, giám sát và kiểm soát tiến độ thực hiện công việc theo kế hoạch; kiểm soát tài liệu, giám sát các hoạt động điều chỉnh, kiểm soát thay đổi, chỉnh sửa kế hoạch, quản lý các hoạt động hợp đồng thuê khoán ngoài.
5. **Giai đoạn kết thúc và nghiệm thu dự án**: Hoàn thành sản phẩm, bàn giao sản phẩm và những tài liệu liên quan; đánh giá dự án, tổ chức nghiệm thu; giải phóng nguồn lực.

### 2.4. Quy trình Triển khai Dự án Ứng dụng CNTT và Ma trận Tham gia của Các Bên

Đối với một **dự án ứng dụng CNTT trong doanh nghiệp**, bài giảng mô tả quy trình gồm **6 giai đoạn** có luồng phản hồi quay vòng từ bước 6 trở lại bước 2. Ma trận sau tổng hợp sự tham gia của bốn đối tượng (**Doanh nghiệp**, **Nhà tư vấn**, **Nhà cung cấp**, **Người sử dụng**) cùng kết quả đầu ra ở từng bước:

| Giai đoạn triển khai | Doanh nghiệp | Nhà tư vấn | Nhà cung cấp | Người sử dụng | Kết quả |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **1. Hoạch định chiến lược CNTT** | Có | — | — | — | Chiến lược CNTT |
| **2. Xây dựng mô hình và quy trình nghiệp vụ** | Có | — | — | — | Mô hình và quy trình nghiệp vụ |
| **3a. Lựa chọn, đàm phán, ký hợp đồng với nhà tư vấn mô hình ứng dụng CNTT** | Có | Có | — | — | Hợp đồng với nhà tư vấn |
| **3b. Tiến hành thiết kế mô hình ứng dụng CNTT** | Có | Có | — | — | Mô hình ứng dụng CNTT |
| **4a. Lựa chọn, đàm phán, ký kết hợp đồng với nhà cung cấp giải pháp ứng dụng CNTT** | Có | Có | Có | — | Hợp đồng với nhà cung cấp |
| **4b. Tiến hành xây dựng giải pháp ứng dụng CNTT** | Có | Có | Có | Có | Giải pháp ứng dụng CNTT |
| **5. Kiểm thử và cài đặt hệ thống, đào tạo người sử dụng, vận hành và khai thác hệ thống** | Có | — | Có | Có | Hệ thống hoạt động ổn định |
| **6. Đánh giá hiệu quả, xem xét nhu cầu mới để đưa ra yêu cầu điều chỉnh đối với hệ thống** | Có | — | Có | Có | Hệ thống được nâng cấp |

Điểm cần đặc biệt lưu ý khi ôn thi là **Doanh nghiệp** tham gia xuyên suốt cả 6 giai đoạn; **Nhà tư vấn** tham gia từ bước 3a đến 4b nhưng không còn tham gia ở giai đoạn 5 và 6; **Nhà cung cấp** bắt đầu tham gia từ bước 4a đến hết bước 6; **Người sử dụng** tham gia từ bước 4b đến hết bước 6; và bước **4b** là bước duy nhất có mặt đầy đủ cả bốn đối tượng.

### 2.5. Sơ đồ Tổng thể Quản lý Dự án CNTT và Công cụ Hỗ trợ

Nhìn trên bình diện tổng thể, quy trình quản lý dự án CNTT liên kết bốn khối công việc lớn thành một vòng khép kín có cơ chế kiểm soát sai lệch:

1. **Xác định dự án**: Xây dựng ý tưởng và phác thảo công việc $\rightarrow$ Công bố dự án.
2. **Lập kế hoạch dự án**: Viết phác thảo dự án và danh sách công việc $\rightarrow$ Ước lượng công việc, thời gian, tài nguyên, chi phí, chất lượng, rủi ro dự án $\rightarrow$ Lập lịch biểu tiến độ $\rightarrow$ Dự toán ngân sách.
3. **Tổ chức dự án**: Lập tài liệu dự án và tổ chức triển khai quản lý dự án $\rightarrow$ Xác định tổ, thủ tục và độ đo đánh giá dự án $\rightarrow$ Phân bổ tài nguyên.
4. **Thực hiện và kiểm soát dự án**: Tiến hành quản lý thực hiện và kiểm soát dự án, sau đó kiểm tra điều kiện **Kết thúc dự án?**:
   - Nếu **thỏa mãn điều kiện kết thúc**: Chuyển sang **Kết thúc dự án**.
   - Nếu **chưa thỏa mãn điều kiện kết thúc**: Thực hiện **Phân tích độ lệch giữa thực tế và kế hoạch**, rồi xét câu hỏi **Sửa đổi kế hoạch?**:
     - Nếu **Không**: **Xác định công việc còn lại** $\rightarrow$ quay lại *Quản lý thực hiện và kiểm soát dự án*.
     - Nếu **Có**: **Xác định sửa đổi cần thiết** $\rightarrow$ **Thực hiện sửa đổi** $\rightarrow$ quay lại *Quản lý thực hiện và kiểm soát dự án*.

Cuối bài giảng, phần bài tập định hướng sinh viên thảo luận về một số dự án CNTT và làm quen với các công cụ quản lý dự án phổ biến gồm **Jira\***, **Trello** và **Zoho**.
