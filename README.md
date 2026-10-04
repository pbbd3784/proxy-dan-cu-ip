# proxy dân cư giá rẻ: chọn gói theo IP hay theo GB, giữ IP cho MMO và thanh toán ngay bằng ví Việt

Người tìm "proxy dân cư giá rẻ" thường không thiếu lựa chọn. Họ thiếu con số thật. Bảng giá niêm yết thì đầy trên mạng, nhưng phần quyết định hóa đơn thực tế lại nằm ở ba chỗ: bạn bị tính theo GB hay theo IP, mỗi IP sống được bao lâu, và phần đã mua mà chưa dùng có bị mất không.

Ba câu hỏi đó quyết định chênh lệch giữa một tháng $24 và một tháng $200 cho cùng một khối lượng công việc. Bài này lấy 9Proxy làm ví dụ cụ thể, vì đây là nhà cung cấp đang bán đúng hai mô hình tính tiền phổ biến nhất, với bảng giá công khai và có mặt trên các diễn đàn Việt như vn-z, voz.

## "Rẻ" trong proxy dân cư thực chất là ba con số khác nhau

Khi so giá proxy dân cư, mọi người hay dán mắt vào một con số duy nhất: giá mỗi GB. Con số đó dễ so, nhưng nó chỉ đúng một nửa.

- **Giá mỗi GB.** Chỉ có ý nghĩa nếu công việc của bạn tiêu thụ băng thông đều và dễ đoán. Tải một trang sản phẩm Shopee mất vài trăm KB, nhưng một trang có nhiều JavaScript, ảnh, video preview có thể ngốn 2–5 MB mỗi lần tải. Cùng số tiền, số request chênh nhau hàng chục lần.
- **Giá mỗi IP.** Nhiều nhà cung cấp bán theo đầu IP kèm băng thông không giới hạn. Bạn tải 100 trang hay 10.000 trang qua cùng một IP thì hóa đơn không đổi. Kiểu này rẻ khi công việc của bạn nặng dữ liệu, nhưng lại phí khi bạn chỉ cần vài chục MB.
- **Tỷ lệ phần đã mua thực sự dùng được.** Đây là con số ít ai nói. Nếu bạn mua 100 GB nhưng hạn dùng 90 ngày, tháng nào làm ít là tháng đó mất tiền. Nếu bạn mua 100 IP nhưng mỗi IP chỉ sống vài giờ, thì "100 IP" không phải là "100 proxy chạy cả tháng".

Nhìn vào ba con số này, cách tính tiền theo IP thường rẻ hơn cho người làm MMO liên tục, còn cách tính theo GB rẻ hơn cho người làm theo đợt.

## 9Proxy bán theo hai mô hình, và khác biệt không chỉ ở giá

9Proxy hiện cung cấp hai dòng proxy dân cư. Theo tài liệu chính thức của họ, sự khác nhau nằm ở chỗ bạn trả tiền cho cái gì và phải cài gì để dùng.

| Tiêu chí | Residential by IPs | Residential by GB |
| --- | --- | --- |
| Cách tính tiền | Theo số lượng IP, không tính dung lượng | Theo tổng GB của gói |
| Thời hạn | Không giới hạn, dùng đến khi hết IP trong ví | Tối thiểu 180 ngày (gói Enterprise: không giới hạn) |
| Vòng đời mỗi IP | Vài giờ đến khoảng 24 giờ, tùy IP | Xoay theo request/session, không có tuổi thọ cố định |
| Cách tạo kết nối | 1 IP = 1 lượt dùng khi forward | Tạo endpoint không giới hạn, chỉ trừ GB |
| Giới hạn băng thông | Không giới hạn trong thời gian IP còn sống | Giới hạn theo GB đã mua |
| Xoay IP | Không tự xoay; phải dùng Auto Rotation Proxy theo cổng | Chế độ rotating hoặc sticky |
| Xác thực | Cần app 9Proxy (forward cổng local) | Username/password hoặc whitelist IP |
| Thiết lập | Bắt buộc app desktop | Làm trực tiếp trên dashboard, không cần app |

Hai chi tiết đáng lưu ý trước khi so giá. Thứ nhất, dòng theo IP cần app desktop (hiện có bản Windows, macOS và Linux), nên nếu bạn muốn chạy trên VPS hoặc server không giao diện thì dòng GB thuận hơn. Thứ hai, dòng GB không cần cài gì, chỉ cần user/pass hoặc whitelist IP là dùng được với anti-detect browser, tool scrape hay script Python.

Cả hai dòng đều hỗ trợ HTTP/HTTPS và SOCKS5, nhắm mục tiêu theo quốc gia, bang/tỉnh, thành phố, mã ZIP và cả ISP.

## Bảng giá 9Proxy hiện hành

9Proxy đã điều chỉnh giá gói theo IP và gói bundle từ ngày 1/6/2026; giá gói theo GB giữ nguyên. Các bảng dưới đây theo mức giá đang áp dụng sau đợt điều chỉnh đó.

### Gói theo IP (băng thông không giới hạn mỗi IP)

| Gói | Giá mỗi IP | Tổng tiền | Mua gói |
| --- | --- | --- | --- |
| 100 IP | $0.24 | $24 | [Đặt gói 100 IP](https://bit.ly/9-Proxy) |
| 500 IP | $0.144 | $72 | [Đặt gói 500 IP](https://bit.ly/9-Proxy) |
| 1.000 IP (+500 IP tặng) | $0.084 | $126 | [Đặt gói 1.000 IP kèm 500 IP tặng](https://bit.ly/9-Proxy) |
| 2.500 IP | $0.084 | $210 | [Đặt gói 2.500 IP](https://bit.ly/9-Proxy) |
| 5.000 IP | $0.072 | $360 | [Đặt gói 5.000 IP](https://bit.ly/9-Proxy) |
| 15.000 IP | $0.048 | $720 | [Đặt gói 15.000 IP](https://bit.ly/9-Proxy) |
| 25.000 IP | $0.035 | $863 | [Đặt gói 25.000 IP](https://bit.ly/9-Proxy) |
| 50.000 IP | $0.029 | $1.438 | [Đặt gói 50.000 IP](https://bit.ly/9-Proxy) |
| 100.000 IP (Business) | $0.023 | $2.300 | [Đặt gói 100.000 IP](https://bit.ly/9-Proxy) |
| 200.000 IP (Business) | $0.021 | $4.140 | [Đặt gói 200.000 IP](https://bit.ly/9-Proxy) |
| 500.000 IP (Business) | $0.018 | $8.625 | [Đặt gói 500.000 IP](https://bit.ly/9-Proxy) |

### Gói theo GB

| Gói | Giá mỗi GB | Tổng tiền | Hiệu lực | Mua gói |
| --- | --- | --- | --- | --- |
| 5 GB | $3.00 | $15 | 180 ngày | [Đặt gói 5 GB](https://bit.ly/9-Proxy) |
| 50 GB (+5 GB tặng) | $2.10 | $105 | 180 ngày | [Đặt gói 50 GB](https://bit.ly/9-Proxy) |
| 100 GB | $1.50 | $150 | 180 ngày | [Đặt gói 100 GB](https://bit.ly/9-Proxy) |
| 200 GB | $1.00 | $200 | 180 ngày | [Đặt gói 200 GB](https://bit.ly/9-Proxy) |
| 1.000 GB | $0.80 | $800 | 180 ngày | [Đặt gói 1.000 GB](https://bit.ly/9-Proxy) |
| 2.000 GB | $0.75 | $1.500 | 180 ngày | [Đặt gói 2.000 GB](https://bit.ly/9-Proxy) |
| 3.000 GB (Enterprise) | $0.72 | $2.160 | Không giới hạn | [Đặt gói 3.000 GB](https://bit.ly/9-Proxy) |
| 6.000 GB (Enterprise) | $0.70 | $4.200 | Không giới hạn | [Đặt gói 6.000 GB](https://bit.ly/9-Proxy) |
| 10.000 GB (Enterprise) | $0.68 | $6.800 | Không giới hạn | [Đặt gói 10.000 GB](https://bit.ly/9-Proxy) |

### Gói bundle (IP + GB trong cùng một gói)

| Gói | Thành phần | Giá | Mua gói |
| --- | --- | --- | --- |
| Starter | 100 IP + 5 GB | $30 | [Đặt gói Starter](https://bit.ly/9-Proxy) |
| Popular | 1.500 IP + 50 GB | $180 | [Đặt gói Popular](https://bit.ly/9-Proxy) |
| Pro | 5.000 IP + 500 GB | $720 | [Đặt gói Pro](https://bit.ly/9-Proxy) |

Gói Pro đáng chú ý ở chỗ giá niêm yết là $860 và được giảm còn $720, tức khoảng 16% – mức giảm này hiển thị ngay ở bước thanh toán. Cả ba gói bundle đều dùng băng thông trong 180 ngày.

## Gói nào rẻ cho trường hợp cụ thể của bạn?

Đây là phần mà bảng giá không tự trả lời. Một vài tình huống thường gặp:

**Nuôi tài khoản Facebook/TikTok, làm MMO.** Bạn cần IP ổn định theo từng profile, không cần nhiều băng thông. Gói theo IP hợp hơn. Nhưng đừng đọc "100 IP" thành "100 proxy chạy cả tháng": theo thông số chính thức, mỗi IP trong ví sống từ vài giờ đến khoảng 24 giờ, và mỗi IP tính là một lượt khi bạn forward. Nếu mỗi IP trung bình sống 12 giờ, 100 IP tương đương khoảng 50 "ngày-thiết bị" — đủ để giữ chừng một đến hai tài khoản online liên tục trong một tháng, hoặc 20 tài khoản online khoảng hai ngày rưỡi. Muốn giữ 20 tài khoản chạy suốt 30 ngày với giả định đó, bạn cần khoảng 1.200 IP mỗi tháng, tương đương hai gói 500 IP cộng thêm phần lẻ. Con số này sẽ lệch tùy tỷ lệ IP sống lâu, nhưng hướng tính thì rõ: hãy ước lượng theo giờ sống, không theo số IP trong ví.

**Cào dữ liệu, theo dõi giá Shopee/Lazada, check SERP.** Công việc theo đợt, khối lượng GB đo được. Gói GB là lựa chọn hợp lý, và gói 5 GB ($15) đủ để bạn đo mức tiêu thụ thực tế trước khi mua gói lớn. Nếu chạy vài chục GB mỗi tháng, gói 50 GB ở mức $2.10/GB hoặc 100 GB ở $1.50/GB rẻ hơn đáng kể so với trả theo đầu IP.

**Vừa nuôi tài khoản vừa scrape.** Gói bundle sinh ra cho đúng kiểu việc này. Starter ($30) là mức thử hợp lý, còn Popular ($180 cho 1.500 IP + 50 GB) dành cho team có vài khách hàng chạy song song.

**Đại lý bán lại.** Mức giá theo IP rơi xuống $0.018/IP ở gói 500.000 IP, và ở Việt Nam có các đơn vị bán lại theo dạng CDkey.

## Những chỗ dễ biến "giá rẻ" thành đắt

Có mấy điểm mà nếu bỏ qua, bạn sẽ thấy hóa đơn không khớp với kỳ vọng.

> Gói theo GB có hiệu lực 180 ngày. Mua 2.000 GB rồi làm được 300 GB trong nửa năm thì phần còn lại mất trắng. Chỉ nên mua theo đúng tốc độ tiêu thụ của bạn.

Tính năng tái sử dụng IP trong 24 giờ trước đó (Today List) cho phép dùng lại IP đã bỏ ra mà không tính thêm, theo mô tả từ phía đối tác tích hợp thì tiết kiệm được khoảng 20–30% chi phí. Với người làm MMO, đây là khoản tiết kiệm thật, không phải chiêu marketing.

Cơ chế đổi IP khi IP chết ngay sau khi kết nối chỉ khoảng 60 giây. Hiểu đúng con số này rất quan trọng: IP dân cư là máy thật của người thật, chủ máy tắt modem thì IP biến mất. Một số phản hồi trên Trustpilot (điểm tổng khá thấp, khoảng 2/5 ở thời điểm kiểm tra) phàn nàn IP ngắt sau chừng một giờ và gây khóa tài khoản. Phía 9Proxy trả lời rằng đây là bản chất của proxy dân cư xoay, và khuyến nghị người cần IP cố định dài hạn nên chuyển sang dòng khác. Nếu công việc của bạn phụ thuộc vào một IP không đổi trong nhiều ngày, proxy dân cư nói chung không phải công cụ phù hợp — kể cả bản rẻ nhất.

Vài điểm khác nên biết trước khi trả tiền:

- Dòng theo IP cần app desktop. Không có app thì không dùng được, kể cả khi bạn chỉ muốn gắn proxy vào một trình duyệt.
- Không phù hợp để xem nội dung streaming. Các tổng hợp đánh giá đều ghi nhận 9Proxy bị phát hiện trên các dịch vụ như Netflix, và chính sách sử dụng của họ cũng không hướng tới mục đích này.
- Yêu cầu hoàn tiền khá hẹp, gần như chỉ áp dụng cho IP chết ngay sau khi kết nối. Không có bản dùng thử miễn phí công khai; bản thử nghiệm số lượng giới hạn phải hỏi trực tiếp hỗ trợ.
- Pool IP được công bố là hơn 20 triệu IP tại 90+ quốc gia. Việt Nam nằm trong danh sách quốc gia có IP, nhưng bạn không nên kỳ vọng nguồn IP Việt dồi dào như IP Mỹ hay châu Âu — nếu công việc bắt buộc IP Việt, hãy kiểm tra khả năng thực tế trước khi mua gói lớn.

## So nhanh mức giá khởi điểm với các nhà cung cấp khác

| Nhà cung cấp | Mức giá khởi điểm công bố |
| --- | --- |
| 9Proxy | $3.00/GB (gói 5 GB), $0.24/IP (gói 100 IP) |
| PSB-Proxy | $2.00/GB |
| CatProxies | $2.50/GB |
| LunaProxy | $3.30/GB |
| Scrapeless | $1.80/GB |
| Webshare | Từ $3.50/tháng (gói rotating residential) |
| Smartproxy | Khoảng $7.00/GB |
| Oxylabs | Khoảng $8.00/GB |
| Bright Data | Khoảng $8.40/GB |

Cách đọc bảng này: mức giá khởi điểm chỉ so được khi cùng mô hình tính tiền. PSB-Proxy rẻ hơn 9Proxy ở bậc 5 GB, nhưng nếu công việc của bạn nặng dữ liệu thì gói theo IP với băng thông không giới hạn của 9Proxy lại rẻ hơn hẳn — bạn không phải nhìn đồng hồ GB nữa. Ngược lại, nếu bạn tiêu thụ hàng trăm GB mỗi tháng, hãy so kỹ phần giảm giá theo bậc, vì đó là lúc chênh lệch vài chục phần trăm xuất hiện.

## Thanh toán từ Việt Nam và mức giảm cho người được giới thiệu

Khâu thanh toán thường là lý do khiến người dùng Việt bỏ qua một nhà cung cấp nước ngoài. 9Proxy xử lý phần này bằng Local Payment: chọn gói, bấm Order Now, chọn Local Payment ở trang thanh toán, hệ thống tự hiện các phương thức khả dụng theo khu vực. Ngoài ra còn thẻ tín dụng (kèm Google Pay, Alipay), crypto (USDT, BTC, ETH, LTC, DOGE…) và ví nội bộ có auto top-up.

Với người ở Việt Nam, Local Payment từng được bổ sung thêm chuyển khoản ngân hàng nội địa và ví điện tử quét QR, theo thông tin do đội ngũ 9Proxy công bố trên các diễn đàn proxy Việt. Danh sách cụ thể hiển thị trên trang thanh toán có thể thay đổi theo thời điểm, nên nếu bạn cần một phương thức nhất định, hãy kiểm tra ngay ở bước checkout.

Một điểm liên quan trực tiếp đến giá: người mua qua mã hoặc link giới thiệu được giảm 5%. Nếu bạn đang chuẩn bị mua gói lớn, đây là 5% không cần làm gì thêm.

👉 [Mở tài khoản 9Proxy và nhận ưu đãi cho người được giới thiệu](https://bit.ly/9-Proxy)

## Các bước bắt đầu trong khoảng mười phút

1. Tạo tài khoản qua link giới thiệu để nhận mức giảm cho người được mời.
2. Vào trang giá, chọn đúng dòng sản phẩm: Residential Proxy by IP, by GB, hoặc Bundle.
3. Chọn gói nhỏ nhất phù hợp để kiểm tra IP trên chính mục tiêu của bạn trước khi nâng gói.
4. Thanh toán bằng Local Payment, thẻ hoặc crypto.
5. Nếu dùng dòng theo IP: tải app cho Windows/macOS/Linux, forward cổng local, bật Auto Rotation Proxy cho các cổng cần thiết. Nếu dùng dòng GB: lấy user/pass hoặc thêm IP vào whitelist và gắn thẳng vào tool.
6. Gắn proxy vào anti-detect browser, script hoặc tool đang dùng; cả hai dòng đều chạy HTTP/HTTPS và SOCKS5.

Với người cần kiểm tra nhanh mà không muốn cài gì, Proxy2Web cho phép đăng nhập bằng user/pass từ trình duyệt. Với người chạy nhiều thiết bị di động, có ProxyHub. Với pipeline tự động, có Public API để quản lý session và xem thống kê.

## Câu hỏi thường gặp

**Có IP Việt Nam không?**
Việt Nam thuộc danh sách quốc gia có IP, và bạn có thể nhắm theo quốc gia, thành phố, mã ZIP và ISP. Nguồn IP Việt không lớn như các thị trường Mỹ hay châu Âu, nên hãy thử ở gói nhỏ trước nếu đây là yêu cầu bắt buộc.

**Mua 100 IP thì dùng được trong bao lâu?**
Không có mốc thời gian cố định. IP chưa dùng thì nằm nguyên trong ví, không hết hạn; IP đã forward thì sống vài giờ đến khoảng 24 giờ. Thời gian dùng gói phụ thuộc vào tốc độ bạn đốt IP, không phụ thuộc vào ngày mua.

**Mua gói GB rồi không dùng hết thì sao?**
Gói GB có hiệu lực 180 ngày, riêng nhóm Enterprise thì không giới hạn. Đây là lý do nên chọn dung lượng theo mức tiêu thụ thực tế thay vì mua thật nhiều để lấy giá rẻ.

**Không muốn cài app thì dùng được không?**
Được, nếu bạn chọn dòng theo GB hoặc gói bundle và dùng phần băng thông. Dòng theo IP bắt buộc phải có app desktop.

**Bao lâu thì nhận được IP sau khi thanh toán?**
Theo mô tả quy trình thanh toán của 9Proxy, gói được kích hoạt ngay sau khi thanh toán xác nhận. Với chuyển khoản nội địa, thời gian phụ thuộc vào ngân hàng hoặc ví.

**Có hỗ trợ khi cấu hình sai không?**
Có ba kênh: Live Chat trên website, Telegram @Official9Proxy và email. Cộng đồng proxy Việt trên vn-z và voz cũng khá active, thường có người của 9Proxy trả lời trực tiếp trong thread.

## Tóm lại

Nếu bạn đang tìm proxy dân cư giá rẻ để nuôi tài khoản, làm MMO hoặc cào dữ liệu, thứ cần so không phải là con số $/GB trên trang chủ. Hãy so ba thứ: bạn bị tính theo GB hay theo IP, một IP sống được bao lâu trong đúng loại việc của bạn, và phần chưa dùng có hết hạn hay không.

Với 9Proxy, gói theo IP đáng cân nhắc khi công việc nặng băng thông, cần giữ phiên ổn định và bạn chấp nhận việc phải cài app. Gói theo GB đáng cân nhắc khi công việc theo đợt, cần xoay IP liên tục và bạn muốn gắn proxy thẳng vào tool mà không cài gì. Và nếu bạn không chắc mình thuộc nhóm nào, hãy bắt đầu ở gói nhỏ nhất — 100 IP với $24 hoặc 5 GB với $15 rẻ hơn nhiều so với việc mua gói lớn rồi phát hiện mô hình tính tiền không khớp với cách bạn làm việc.
