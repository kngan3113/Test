
TRƯỜNG ĐẠI HỌC KINH TẾ – ĐẠI HỌC ĐÀ NẴNG
KHOA THƯƠNG MẠI ĐIỆN TỬ
**********

ĐỀ ÁN THỰC HÀNH 1
Đề tài

BÁO CÁO TÌNH HÌNH KINH DOANH CỦA
DOANH NGHIỆP ADVENTUREWORKS TỪ 1/1/2011 - 31/12/2013

GVHD: 	ThS. Trương Hồng Tuấn
Lớp học phần: ELC3022_47K29.2 
Thành viên nhóm:
1.	Nguyễn Thị Lệ Quân
2.	Nguyễn Thị Kim Ngân

		Đà Nẵng, ngày 5 tháng 5 năm 2024 

MỤC LỤC
PHẦN A: MỞ ĐẦU	1
I.	Giới thiệu về đề tài	1
1.	Lý do chọn đề tài	1
2.	Đối tượng nghiên cứu	1
3.	Đối tượng sử dụng và mục tiêu của bài báo cáo	2
II.	Mô tả tổng quan về dữ liệu và chuẩn bị dữ liệu	2
1.	Mô tả dữ liệu	2
2.	Công cụ và công việc liên quan đến công cụ	4
3.	Chuẩn bị dữ liệu	5
4.	Cấu trúc nội dung bài báo cáo	6
PHẦN B: BÁO CÁO TÌNH HÌNH KINH DOANH CỦA ADVENTUREWORKS TỪ 2011-2013	7
1.	Overview	7
2.	Products Analytics	15
3.	Sales Market Analytics	29
4.	Sales Customer Analytics	40
5.	Recommendations	43
PHẦN C: TỔNG KẾT	45






PHẦN A: MỞ ĐẦU
I.	Giới thiệu về đề tài
1.	Lý do chọn đề tài

Trong thời đại hiện nay, sự phát triển của công nghệ đã mở ra cánh cửa của Cuộc cách mạng công nghiệp lần thứ tư, mang theo đó những cơ hội và thách thức không ngờ đối với các doanh nghiệp trên toàn cầu. Điều quan trọng nhất trong bối cảnh này là sự xuất hiện và gia tăng không ngừng của dữ liệu, một nguồn tài nguyên quý báu đang là trung tâm của sự chuyển đổi kinh doanh.

Dữ liệu không chỉ là một loại tài sản quan trọng, mà còn là yếu tố then chốt định hình mọi quyết định chiến lược của các doanh nghiệp. Khả năng thu thập, phân tích và sử dụng dữ liệu hiệu quả đã trở thành yếu tố quyết định sự thành công hay thất bại của một tổ chức. Trong bối cảnh này, dữ liệu lớn (Big Data) đã nổi lên như một "mỏ vàng" vô hình, nơi chứa đựng hàng ngàn triệu thông tin quý giá về thị trường, khách hàng, và hoạt động kinh doanh.

Điều quan trọng không chỉ là việc thu thập dữ liệu, mà còn là khả năng khai thác và biến nó thành thông tin có ý nghĩa. Việc phân tích dữ liệu đã trở nên cấp thiết và mạnh mẽ, chính vì thế nên nhóm chọn đề tài “ Phân tích và báo cáo tình hình kinh doanh ”  giúp các nhà quản trị nắm được tình hình kinh doanh giúp các doanh nghiệp hiểu rõ hơn về thị trường, dự đoán xu hướng, và tạo ra những chiến lược kinh doanh hiệu quả.
2.	Đối tượng nghiên cứu

Bài báo cáo sử dụng Bộ dữ liệu AdventureWorks Data Warehouse 2014. AdventureWorksDW2014 là bộ dữ liệu mẫu của Microsoft, đây là một doanh nghiệp sản xuất và kinh doanh đa quốc gia. Sản phẩm chính là Bikes gồm 3 dòng chính là Mountain Bikes, Touring Bikes và Road Bikes, bên cạnh đó cũng kinh doanh các phụ kiện đi kèm là Component, Clothing và Accessories. 

Adventureworks hoạt động trên 6 quốc gia: United States, Australia, United Kingdom, Canada, France và Germany. Có 2 mô hình kinh doanh của Adventureworks là các cửa hàng bán lẻ bán xe đạp và bán hàng trên Internet phục vụ khách hàng cá nhân. Thông thường Adventureworks bán với số lượng lớn cho các cửa hàng bán lẻ, hoạt động làm đại lý cho sản phẩm của mình.

Link tải dataset: [Tại đây](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksDW2014.bak)
3.	Đối tượng sử dụng và mục tiêu của bài báo cáo

Hoạt động kinh doanh của Adventureworks bao gồm một số chức năng như bán hàng, sản xuất, mua hàng, kỹ thuật, tài chính. Bài báo cáo tập trung vào các vấn đề liên quan đến tình hình kinh doanh của AdventureWorks từ 2011 - 2013. Báo cáo này dành cho Giám đốc kinh doanh - người đứng đầu bộ phận kinh doanh của doanh nghiệp,  chịu trách nhiệm quản lý, điều hành, chỉ đạo và định hướng các hoạt động kinh doanh nhằm đạt được các mục tiêu doanh số, lợi nhuận và phát triển của công ty. Bài báo cáo sẽ trình bày các vấn đề liên quan đến hoạt động kinh doanh.

Mục tiêu chính là sử dụng những kỹ thuật phân tích dữ liệu kinh doanh kết hợp với công cụ trực quan hóa và kỹ thuật data storytelling để hỗ trợ giám đốc kinh doanh trong việc nắm bắt tình hình kinh doanh một cách toàn diện để cung cấp một cái nhìn tổng quan về thị trường và dự đoán xu hướng tương lai.

II.	Mô tả tổng quan về dữ liệu và chuẩn bị dữ liệu
1.	Mô tả dữ liệu

Cơ sở dữ liệu này chứa các bảng từ các giao dịch của công ty. Có một số bảng mà được nhóm thành các lĩnh vực khác nhau như bán hàng, nhân sự, con người, mua hàng và sản xuất. Bởi vì đây là báo cáo tình hình kinh doanh nên sử dụng các bảng liên quan như sau: 

●	Fact Reseller Sales: bao gồm các thông tin về giao dịch kinh doanh thông qua kênh bán lẻ. Cụ thể là thông tin về Sản phẩm được bán, Ngày giao dịch, Giá bán, Số lượng, Chi phí liên quan như Thuế, Vận chuyển,...

●	Fact Internet Sales: bao gồm các thông tin về giao dịch bán hàng thông qua kênh Internet. Cụ thể là thông tin về Sản phẩm được bán, Ngày giao dịch, Giá bán, Số lượng, Chi phí liên quan như Thuế, Vận chuyển,...

●	Dim Date: bao gồm thông tin liên quan đến thời gian của các giao dịch như Ngày, Tháng, Năm. 

●	Dim GeoGraphy: bao gồm thông tin liên quan đến vị trí địa lý. Ở đây là thị trường kinh doanh cũng như khu vực sinh sống của khách hàng. 


●	DimProduct: bao gồm thông tin liên quan đến sản phẩm như Mã sản phẩm, Mẫu mã, Dòng sản phẩm cũng như Chi phí liên quan đến sản phẩm, Giá bán,...

●	Dim ProductCategory: bao gồm thông tin liên quan đến các nhóm sản phẩm gồm Mã và Tên của Bikes, Components, Clothing và Accessories.

●	Dim Product SubCategory: bao gồm thông tin liên quan đến sản phẩm của  các nhóm con trong Category. 

●	Dim Customer: bao gồm các thông tin liên quan đến khách hàng của AdventureWorks như Tuổi, Nghề nghiệp, Thu nhập, Trình độ học vấn,...

●	Dim Sales Territory: đây là bảng trung gian giữa bảng “Dim Geography” và các bảng khác.

●	Dim Reseller: bao gồm các thông tin liên quan đến các nhà bán lẻ.

Ngoài ra còn có thêm các bảng được tổng hợp và tính toán thông qua Microsoft SQL Server như Legend, Profitable_Category và Geography để phục vụ cho việc phân tích. Ngoài ra còn các bảng phục vụ cho việc dự đoán như Bikessales_RSL và Final. Mặc dù có thể xử lý trên Python nhưng việc này xử lý trên Microsoft SQL Server dễ dàng hơn.

Thông tin của các cột tính toán để phục vụ cho việc phân tích: 

●	Extended Amount: Tổng doanh thu của doanh nghiệp khi chưa trừ bất cứ chi phí gì.

●	Sales Amount: tổng doanh thu của doanh nghiệp khi trừ đi Discount Amount - Chiết khấu thương mại cho kênh Reseller.

●	Total Product Cost: tổng tất cả các chi phí bao gồm Chi phí sản xuất, Thuế, Chiết khấu, Vận chuyển. 

●	Profit: đây là lợi nhuận ròng về tay doanh nghiệp khi đã trừ tất cả các chi phí. Cột này được tính bằng cách lấy Extended Amount - Total Product Cost. 


●	Net Profit Margin: đây là biên lợi nhuận ròng, đánh giá khả năng sinh lời của doanh nghiệp. Được tính bằng cách lấy Profit/Sales Amount. 

●	Tuổi của khách hàng: bằng cách lấy năm mua trừ đi năm sinh của khách.

2.	Công cụ và công việc liên quan đến công cụ

Import  file bak của bộ dữ liệu AdventureWorksDW2014 vào Microsoft SQL Server, thực hiện các truy vấn để lấy thông tin cần thiết.
 
SQL Server là một hệ quản trị cơ sở dữ liệu quan hệ (RDBMS) được phát triển bởi Microsoft. Nó cung cấp một nền tảng mạnh mẽ để quản lý và lưu trữ dữ liệu cho các ứng dụng doanh nghiệp. SQL Server cho phép người dùng lưu trữ dữ liệu trong các bảng được tổ chức theo cấu trúc và thực hiện các thao tác truy vấn dữ liệu phức tạp bằng ngôn ngữ truy vấn SQL.

Power BI: đây là một công cụ phân tích dữ liệu và trực quan hóa thông tin được phát triển bởi Microsoft. Với Power BI, người dùng có thể kết nối đến nhiều nguồn dữ liệu khác nhau, từ các cơ sở dữ liệu cục bộ đến các dịch vụ đám mây như Azure và SQL Server,... để thu thập dữ liệu và tạo ra các báo cáo, biểu đồ và bảng điều khiển đa dạng.

Với Power BI: nhóm thực hiện việc chuyển đổi và tính toán các cột cần thiết cho việc phân tích như Lợi nhuận, Tỷ suất lợi nhuận ròng. Đặc biệt là trực quan hóa dữ liệu, vẽ các biểu đồ để có thể trình bày được việc phân tích một cách dễ hiểu cho đối phương cũng như có một cái nhìn trực quan, tổng quát về tình hình kinh doanh, thực hiện việc làm sạch và chuyển đổi dữ liệu, cụ thể là đổi tên cột, đổi kiểu dữ liệu để chúng phù hợp với mục tiêu của báo cáo. 

Ngoài ra Power BI còn có Slicer - một bộ lọc phục vụ mạnh mẽ trong quá trình phân tích, tính năng này cung cấp khả năng kiểm tra chi tiết và chi tiết hơn về các chỉ số quan trọng, đặc biệt là lọc các giá trị không cần thiết cũng như các Blank, điều chỉnh thông tin chi tiết cho các lĩnh vực quan tâm cụ thể trong bối cảnh hiệu quả hoạt động của công ty.

Những bảng được kết nối vào Power BI không phục vụ hết những mục tiêu cần thiết nên chúng ta sẽ kiểm tra Diagram, xem xét các mối quan hệ giữa các bảng bằng khóa chính và khóa ngoại, sau đó truy vấn những thông tin cần thiết, xuất thành file Excel và đưa vào Power BI để tiếp tục việc trực quan hóa.

3.	Chuẩn bị dữ liệu

Các bảng khi Import vào Microsoft SQL Server đã được thiết lập mối quan hệ với nhau thông qua các khóa nối và được sắp xếp rõ ràng. Điều này đảm bảo tính nhất quán của bộ dữ liệu. Mỗi bảng đều có Khóa chính và các Khóa ngoại để tham chiếu đến các bảng liên quan. 

Bên cạnh những bảng đã có sẵn, để phục vụ cho việc phân tích thì cần tạo thêm một số bảng khác thông qua việc truy xuất dữ liệu trên Microsoft SQL Server, ví dụ như bảng tổng hợp dữ liệu kinh doanh của 2 kênh Reseller và Internet theo Địa lý.
![image](https://github.com/user-attachments/assets/a1d2e5e7-ddd2-4b36-8f7a-fcd7ace28135)
 
Hình 1.1: Ví dụ về việc tạo view lấy dữ liệu từ Microsoft SQL Server

Mối liên hệ giữa các bảng được thể hiện thông qua Diagram dưới đây: 

 ![image](https://github.com/user-attachments/assets/85bd94e4-20a0-410e-8790-57607c12c149)
Hình 1.2: Diagram của các bảng được sử dụng

Bộ dữ liệu không có bất kỳ vấn đề nghiêm trọng nào về dữ liệu ngoại lai, dữ liệu trùng lặp, các giá trị bị thiếu sẽ được lọc bằng Slicer của Power BI. Bên cạnh đó định dạng của dữ liệu đa số đã đúng, nhóm chỉ chuyển định dạng một vài cột liên quan đến tiền tệ về dạng fix decimal number.

Tính toán thêm những cột cần thiết cho việc phân tích:

●	Profit: đây là lợi nhuận ròng về tay doanh nghiệp khi đã trừ tất cả các chi phí. Cột này được tính bằng cách lấy Extended Amount - Total Product Cost. 
●	Net Profit Margin: đây là biên lợi nhuận ròng, đánh giá khả năng sinh lời của doanh nghiệp. Được tính bằng cách lấy Profit/Sales Amount.
●	Tuổi: đây là một thông tin cần thiết cho việc phân tích nhưng lại không có sẵn, được tính toán dự vào việc lấy năm khách hàng thực hiện giao dịch trừ cho năm sinh của khách đó.

4.	Cấu trúc nội dung bài báo cáo

4.1 Overview
Phần này cung cấp một cái nhìn tổng quan về tình hình kinh doanh, hiệu suất tổng thể của của doanh nghiệp qua 3 năm, từ Doanh thu, Chi phí và Lợi nhuận. Những chỉ số này ở hai kênh bán hàng là Reseller và Internet cũng được thể hiện trong phần Overview.

4.2 Sales Product Analytics
Phần này tập trung vào việc phân tích tình hình kinh doanh của các Nhóm sản phẩm cũng như từng mặt hàng cụ thể. So sánh hiệu suất kinh doanh, tỷ suất sinh lời của các sản phẩm ở mỗi kênh bán hàng.

4.3 Sales Market Analytics
Phần này tập trung vào việc phân tích tình hình kinh doanh của các thị trường trên thế giới, bao gồm các châu lục và các quốc gia. Xem xét tình hình biến động tại mỗi quốc gia.

4.4 Sales Customer Analytics
Phần  này tập trung vào việc phân tích tình hình kinh doanh của khách hàng theo các đặc điểm của khách hàng như về độ tuổi, bậc đại học và các yếu tố như tình trạng hôn nhân và giới tính.

4.5 Recommendations
Dựa vào quá trình phân tích tổng quan và phân tích từng yếu tố như trên, cũng như việc tương quan và dự đoán doanh thu ở nhóm hàng,  nhóm sẽ đưa ra các đề xuất, giải pháp phù hợp cho doanh nghiệp trong năm 2014 đưa ra được những quyết định đúng đắn, tốt cho doanh nghiệp.
PHẦN B: BÁO CÁO TÌNH HÌNH KINH DOANH CỦA ADVENTUREWORKS TỪ 2011-2013

1.	Overview
 ![image](https://github.com/user-attachments/assets/b26bfeaf-6121-441c-b04a-f40e994be40e)
 			Hình 1.1: Tổng quan về tình hình kinh doanh từ 2011-2013

a.	Những chỉ số chung của Adventureworks từ năm 1/1/2011 - 31/12/2013
Dashboard Overview cung cấp sự cái nhìn tổng quát về hiệu suất tổng thể của công ty. Tổng doanh thu doanh nghiệp đạt được là 110,34 triệu USD. Trong đó Tổng chi phí lên đến 97,26 triệu USD, một con số cao so với Tổng doanh thu. 

Trong 3 năm thì doanh nghiệp đang có lời với mức lợi nhuận là 12,55 triệu USD.

b.	Biến động tổng doanh thu từ 1/1/2011 - 31/12/2013
 ![image](https://github.com/user-attachments/assets/5e839a2e-59cd-4570-9902-9851993f5b81)
Hình 1.2: Biến động doanh thu ở 2 kênh qua các năm
Doanh thu từ kênh Reseller mang về luôn cao hơn kênh Internet rất nhiều ở cả 3 năm. Doanh thu từ kênh Internet có sự giảm nhẹ vài năm 2012 nhưng nhìn chung vẫn có xu hướng tăng lên và không có sự biến động đột biến gì. Doanh thu từ kênh Reseller có tăng qua 3 năm nhưng biến động rất lớn, luôn tăng giảm thất thường với biên độ thay đổi rất lớn.

c.	Biến động doanh thu theo từng quý ở 2 kênh
 ![image](https://github.com/user-attachments/assets/9642286c-0d6c-494c-af2d-c62c3175d7ce)
 ![image](https://github.com/user-attachments/assets/e75a7936-4d3b-4df3-aebc-dd26b224bd09)
Hình 1.3: Biến động doanh thu ở hai kênh theo tháng
 ![image](https://github.com/user-attachments/assets/dc039f75-1b14-460d-ac14-d4a2b2fd60e0)
Hình 1.4: Số lượng chiến dịch tiếp thị theo tháng

Đối với kênh Internet thì doanh thu không có sự biến động gì quá lớn qua các tháng và có xu hướng tăng nhẹ từ khi dần về cuối năm. Nhưng kênh Reseller thì doanh thu có điều đặc biệt là đều có xu hướng chung là giảm ở tháng 4, tháng 7, tháng 10 và tháng 12, tăng lên ở những tháng còn lại trong cả 3 năm.  Nguyên nhân chính là vì ở những tháng này số lượng các chương trình tiếp thị thấp hơn, dẫn đến doanh thu bán hàng thấp ở tất cả các Category.
![image](https://github.com/user-attachments/assets/eff72947-3318-4957-9cac-51ba1a579d3b)
 
Hình 1.5: Tương quan giữa số lượng chiến dịch tiếp thị và doanh thu

Điều này cho thấy các chiến dịch tiếp thị của doanh nghiệp đang có sự ảnh hưởng lớn đến hoạt động kinh doanh, nhu cầu của khách hàng được kích thích và họ mua sắm nhiều hơn khi có những chương trình tiếp thị này. Cụ thể hơn ở đây có sự tương quan thuận giữa 2 biến số này, nếu số lượng chiến dịch tiếp thị nhiều thì sẽ dẫn đến doanh thu cao. Doanh nghiệp đang triển khai khá tốt những chiến dịch tiếp thị của họ.

d.	Tỷ lệ doanh thu và lợi nhuận của 2 kênh

![image](https://github.com/user-attachments/assets/436747a1-797a-4359-9b0d-c25245d350ad)
 
Hình 1.6: Tỷ lệ doanh thu và lợi nhuận ở 2 kênh bán hàng

 ![image](https://github.com/user-attachments/assets/b074dc36-b83e-4fe7-a62d-a7a20ffd2d9e)
Hình 1.7: Giá bán ra trung bình của mỗi Nhóm hàng

Nhìn vào hai biểu đồ về doanh thu và chi phí của 2 kênh bán hàng ở Hình 1.6,  ta có thể thấy Kênh Reseller mang lại doanh thu chính cho cửa hàng, chiếm gần 73.81% doanh thu trong 3 năm, gần ¾  doanh thu, còn Internet chỉ mang lại 26,19% doanh thu. 

Điều này có thể bởi vì doanh thu chính của cửa hàng đến từ Category là Bikes, đây là mặt hàng chủ lực cũng như giá thành nó sẽ cao hơn so với các Category còn lại với đơn giá trung bình một sản phẩm của Bikes là 883 USD, còn Component là 251 USD và Clothing, Accessories lần lượt là 28 USD và 23 USD như hình 1.7. 

Bên cạnh đó đối với mặt hàng Bikes thì khách hàng đa số có xu hướng mua trực tiếp tại cửa hàng hơn để dễ dàng lựa chọn mẫu mã và chất lượng. Chính vì thế mà doanh thu chủ yếu đến từ Reseller

Tuy nhiên, điều doanh nghiệp thực sự quan tâm ở đây là lợi nhuận. Một vấn đề đã được nhận thấy ở đây là tuy Reseller có tỷ lệ doanh thu rất lớn nhưng lợi nhuận đem về lại không nhiều như thế, chỉ chiếm 1,79%. Kênh Internet tuy không mang lại nhiều doanh thu nhưng mức lợi nhuận lại rất lớn - 92,21% lợi nhuận như Hình 1.6.
![image](https://github.com/user-attachments/assets/bf751b8c-ed60-46f3-82a2-1c259068883e)
 
Hình 1.8: Trung bình những chi phí khác(trừ chi phí vận chuyển) của 2 kênh

Nguyên nhân có lẽ vì các nhà bán lẻ tốn quá nhiều chi phí cho một sản phẩm bán ra, nhiều hơn hẳn so với kênh Internet như Hình 1.8. Chi phí trên là chi phí trung bình cho một sản phẩm bán ra ở hai kênh, bao gồm thuế, phí vận chuyển và chiết khấu thương mại, không bao gồm chi phí sản xuất trực tiếp bởi vì chi phí sản xuất trực tiếp của sản phẩm nào cũng giống nhau, không bị ảnh hưởng bởi kênh bán hàng. Cụ thể như sau:   
     
●	Đối với một sản phẩm được bán ra, chi phí trung bình ở kênh Reseller cao hơn so với kênh Internet gần gấp 3 lần ( 51,04 USD so với 147,48 USD).
 
●	Đầu tiên là do chi phí cho khoản chiết khấu thương mại. Đối với Reseller, doanh nghiệp có các chính sách giá cả và chiết khấu nhằm kích thích doanh số bán hàng, Internet không tốn chi phí cho khoản này như hình 1.8.

●	Chi phí vận chuyển ở kênh Reseller cũng cao hơn so với Internet, đặc biệt là đối với Thuế. Thuế ở Reseller cao hơn hẳn - 39 USD so với 106 USD.

●	Ngoài ra việc quản lý độ lớn của đơn đặt hàng từ reseller có thể tạo ra các khó khăn về quản lý tồn kho, sản xuất, và dịch vụ khách hàng. Nếu không được quản lý hiệu quả, điều này có thể dẫn đến các chi phí không mong muốn và làm giảm lợi nhuận. Chi phí hàng tồn kho là một chi phí rất quan trọng cần được kiểm soát chặt chẽ và thường xuyên. Đây cũng có thể là một trong những nguyên nhân dẫn đến việc lợi nhuận ở kênh Reseller bị giảm trừ đáng kể.
![image](https://github.com/user-attachments/assets/75402008-7323-4dfe-91ce-3d964c231f2b)
  ![image](https://github.com/user-attachments/assets/530b0c7d-f174-430e-a08a-52d698603eea)
                    Hình 1.10: Doanh thu và chi phí ở 2 kênh bán hàng

Trong khi đó ở kênh Internet luôn có lời qua các năm và tăng trưởng mạnh mẽ vào năm 2013 với 16 triệu USD, hơn 10 triệu USD so với 2012 như Hình 1.10.  Và đối với Reseller thì đúng là Adventureworks đang tốn rất nhiều chi phí so với doanh thu (bao gồm tất cả chi phí bao gồm chi phí sản xuất, chiết khấu, thuế, vận chuyển). 

Đây là một dấu hiệu đáng báo động. Doanh nghiệp nên xem xét lại khâu sản xuất cũng như các chi phí liên quan đến nhà bán lẻ như chiết khấu, thuế, vận chuyển. Đặc biệt phải có chính sách điều chỉnh lập tức để tránh tình trạng tổng chi phí lại cao hơn so với doanh thu như thế này.

e.	Lợi nhuận và Biên lợi nhuận ròng ở 2 kênh
 ![image](https://github.com/user-attachments/assets/2dec11ae-1f37-4e80-8c15-621f396fb422)
 Hình 1.11: Lợi nhuận và biên lợi nhuận ròng ở kênh bán lẻ

Tuy là kênh mang đến phần lớn doanh thu cho cửa hàng những về mặt lợi nhuận của kênh Reseller thì không khả quan lắm. Cụ thể là biên lợi nhuận luôn thấp và bị âm ở Quý 4 năm 2011 và Quý 1 năm 2013. Doanh nghiệp cần phải khắc phục được những nguyên nhân đã được nêu ra ở trên (2c).
![image](https://github.com/user-attachments/assets/7c007806-b102-4a35-8724-03be265716a3)
 
           Hình 1.12: Lợi nhuận và biên lợi nhuận ròng ở kênh trực tuyến
![image](https://github.com/user-attachments/assets/2f383b0a-3e74-4eea-b072-bce7801eb1e6)
 
Hình 1.13: Doanh thu và số lượng bán ở kênh Internet

Đối với kênh Internet: Lợi nhuận luôn dương qua các năm, biên lợi nhuận ròng cũng dương nhưng trong 2 năm 2011 - 2012 thì chưa có sự tăng trưởng nào cho đến năm 2013 mới tăng lên hơn 10%, từ 41% ở cuối năm 2012 lên 54%  ở cuối 2013 ở Hình 1.12

Nguyên nhân của sự tăng trưởng về biên lợi nhuận ròng ở năm 2013 này là trong 2 năm 2011 - 2012 thì chỉ bán một Category là Bikes và đến 2013 thì mới có thêm Accessories và Clothing ở Hình 1.13. Tuy năm 2013 Bikes cũng tăng trưởng về mặt doanh thu, nhiều hơn so với 2 năm trước nhưng ta có thể thấy được rằng hai Category là Accessories và Clothing mới là nguyên nhân chính làm biên lợi nhuận ròng của doanh nghiệp tăng. Điều đặc biệt ở đây là doanh thu của 2 Category này rất nhỏ so với Bikes nhưng tiềm năng sinh lợi của nó lại rất lớn, lớn hơn Bikes rất nhiều. Doanh nghiệp nên tập trung phát triển nhiều hơn vào những Category này để có được mức sinh lời nhiều hơn.

2.	Products Analytics
a.	Tổng quan về Products

Adventureworks kinh doanh các mặt hàng về xe đạp, phụ kiện và quần áo xe đạp. Cụ thể từ 2011-2013, doanh nghiệp có 4 Category là: Bikes - sản phẩm chủ lực, Clothing, Accessories và Component với 37 Subcategory, 606 sản phẩm thuộc 4 dòng.

b.	Tỷ trọng doanh thu và lợi nhuận theo Category
 ![image](https://github.com/user-attachments/assets/fab9f507-ec10-4773-917b-6a609821eae3)
Hình 2.1: Doanh thu và lợi nhuận theo Nhóm sản phẩm

 ![image](https://github.com/user-attachments/assets/bbb0e4c2-fbde-48d3-93d0-8a8a9963dc92)
Hình 2.2: Giá bán trung bình ở mỗi Nhóm hàng

Nhìn chung thì Bikes là sản phẩm mang lại doanh thu chính cũng như lợi nhuận cho doanh nghiệp, chiếm 86,2% doanh thu và 84,18% lợi nhuận. Tiếp đến là Components, đây tuy là sản phẩm chỉ được bày bán tại Reseller nhưng có đóng góp khá đáng kể so với Clothing và Accessories.  

Nguyên nhân bởi vì Bikes là sản phẩm chính của Adventureworks cũng như giá bán trung bình của mỗi sản phẩm ở Category Bikes là 853 USD, cao hơn hẳn so với Components là 179 USD, Clothing là 27 USD và Accessories là 23 USD như hình 2.2

c.	Tình hình kinh doanh theo Category ở kênh Internet
 ![image](https://github.com/user-attachments/assets/19c600be-92c5-42f8-88d6-ad0465b3892c)
Hình 2.3: Số lượng bán ra đơn hàng bán ra ở kênh Internet

 ![image](https://github.com/user-attachments/assets/f82857b0-0e92-4ca4-9da2-aa521afd1be8)
Hình 2.4: Doanh thu và lợi nhuận của mỗi Nhóm hàng ở kênh Internet

Ở kênh Internet, Accessories tuy bán chạy nhất với 36 nghìn lượt bán nhưng doanh thu và lợi nhuận của Category này không đáng kể, chỉ chiếm tầm 2,39% doanh thu và 3,63% lợi nhuận. 
Doanh thu và lợi nhuận chính của kênh Internet vẫn đến từ Bikes là chính, tuy số lượng bán không nhiều bằng Accessories 15 nghìn lượt bán.

Tình hình kinh doanh theo Category ở kênh Reseller
   ![image](https://github.com/user-attachments/assets/9af82fbe-1cfa-43bf-ab83-b7ccd53f6c5f)
Hình 2.5: Doanh thu và lợi nhuận của mỗi Nhóm hàng ở kênh bán lẻ
![image](https://github.com/user-attachments/assets/d75bf092-b4f1-457d-9f2a-cede5f4ca6a2)
 
                 Hình 2.6: Chi phí của mỗi nhóm hàng ở 2 kênh bán hàng

Đối với kênh Internet thì doanh thu của Bikes vẫn chiếm phần lớn - 82,49% và
có thêm sản phẩm về Components - cũng có doanh thu khá cao là 14,58%. Tuy Bikes mang lại doanh thu cao như thế nhưng về mặt lợi nhuận thì lại bị thua lỗ ở Reseller - âm 0,5 triệu USD trong vòng 3 năm như hình 2.5 trong khi Bikes ở kênh Internet vẫn đang lời với mức lợi nhuận chiếm đến 95,24% như Hình 2.4.

Nguyên nhân của tình trạng này có lẽ đến từ vấn đề chi phí dành cho Bikes ở kênh Reseller. Tất cả 4 Category thì Tổng chi phí ở Reseller đều cao hơn Internet. 
Những chi phí khác (chưa bao gồm chi phí sản xuất) của Bikes rất cao, hơn rất nhiều lần so với các Category còn lại.Trong 3 loại chi phí thì Thuế chiếm nhiều nhất - chiếm 70% so với tổng chi phí ở kênh Reseller, bên cạnh đó phí vận chuyển cũng khá đáng kể nhưng nhìn chung thì trung bình mỗi một sản phẩm của Bikes bán ra phải chi trả nhiều chi phí hơn so (không tính chi phí sản xuất) với sản phẩm của các Category còn lại. 

Những nguyên nhân trên cũng lý giải được vì sao doanh thu của Bikes rất lớn nhưng lợi nhuận lại đang bị âm ở kênh Reseller.

d.	Số lượng đơn đặt hàng ở 2 kênh
![image](https://github.com/user-attachments/assets/b6554d69-80be-43a5-ab84-1a5aa900d7f1)
 
Hình 2.5: Số lượng đơn đặt hàng ở 2 kênh bán hàng
   ![image](https://github.com/user-attachments/assets/ee0f764d-7275-4277-9f29-526e797b8ca2)               
![image](https://github.com/user-attachments/assets/d352bf4d-db42-49e2-8480-5fe933d71059)
![image](https://github.com/user-attachments/assets/f1def2b1-8e7b-4604-82cf-7afbad8470d1)
   
Hình 2.6: Giá bán ra của mỗi Nhóm hàng ở 2 kênh

Ở kênh Reseller thì Bikes được bán nhiều nhất với 75 nghìn đơn đặt hàng như hình 2.5. Bởi vì đây là sản phẩm chủ lực của Adventureworks cũng như có thể vì đối với những sản phẩm có giá bán cao thì khách hàng sẽ có xu hướng đến trực tiếp tại cửa hàng để có thể lựa chọn kỹ lưỡng hơn về chất lượng cũng như mẫu mã thay vì đặt hàng qua Internet thì chỉ được xem hình ảnh thôi. Một nguyên nhân ảnh hưởng đến việc Bikes được mua nhiều tại kênh Reseller nữa là vì ở hình 2.6 ta có thấy nếu mua Bikes ở Reseller, ta sẽ được mua với giá ưu đãi hơn rất nhiều là 882 USD thay vì phải mất 1.862 USD khi mua trên Internet. 

Ở kênh Internet thì Accessories bán chạy nhất với 36 nghìn đơn hàng, hơn gấp đôi Bikes với 15 nghìn đơn hàng và cuối cùng là Clothing. 

Ở Hình 2.6 ta có thể thấy giá ở 2 kênh bán hàng của các Category, ở kênh Internet thì chỉ có giá bán của Accessories là thấp hơn so với kênh Reseller - 19,4 USD so với 21.67 USD. Tất cả các mặt hàng còn lại đều có giá cao hơn ở kênh Internet, đặc biệt là Bikes với mức chênh lệch lên đến 1 nghìn USD. Điều này có thể lý giải vì sao Accessories lại là Category được bán chạy nhất ở kênh Internet trong khi Bikes mới chính là sản phẩm chính của doanh nghiệp, cũng như việc Clothing và Bikes được mua với số lượng nhiều hơn ở Reseller. 

Đối với Clothing thì khách hàng sẽ có xu hướng muốn đến lựa chọn trực tiếp tại cửa hàng để tránh tình trạng không mua nhầm size sản phẩm không phù hợp với bản thân. Đây cũng có thể là một nguyên nhân dẫn đến Clothing được mua tại cửa hàng trực tiếp nhiều hơn bên cạnh nguyên nhân là giá ở cửa hàng sẽ thấp hơn.

e.	Sự tăng trưởng doanh thu của các dòng xe đạp từ 2011-2013

 ![image](https://github.com/user-attachments/assets/ede864c7-0983-4501-a1bf-181cabe439ac)
Hình 2.7: Sự tăng trưởng doanh thu của các dòng xe đạp qua 3 năm

Nhìn chung ở cả 2 kênh thì doanh thu của xe đạp có sự tăng trưởng, năm 2013 có thêm dòng sản phẩm mới là Touring Bikes - xe đạp đi du lịch đường dài. Có thể doanh nghiệp đã nhận thấy xu hướng của thị trường đối với dòng xe đạp du lịch này nên chỉ mới năm đầu tiên ra mắt, dòng xe đạp này đã mang lại doanh thu rất lớn cho doanh nghiệp - 15,7 triệu USD.

Tuy mới ra mắt được 1 năm nhưng dòng xe này đem lại doanh thu khá lớn, đặc biệt ở kênh Reseller với 12 triệu USD trong năm 2013. Có vẻ đây là một dòng xe có tiềm năng phát triển, được thị trường ưa chuộng khá nhiều. Doanh nghiệp nên tập trung phát triển và mở rộng nhiều sản phẩm của dòng Touring Bikes này để đem lại doanh số cao.

Đối với kênh Internet thì doanh thu năm 2012 giảm nhẹ so với 2011, đặc biệt là Road Bikes, từ 5,6 triệu USD giảm còn 3,7 triệu USD. Nhưng đến năm 2013 thì phục hồi lại 5,2 triệu USD. Đối với Mountain Bikes thì tăng trưởng đều qua các năm, tăng mạnh vào năm 2013, gấp 3 lần so với 2012 - từ 2,2 triệu USD tăng lên 6,5 triệu USD. 

Đối với kênh Reseller thì doanh thu lại tăng trưởng mạnh vào năm 2012, đặc biệt là Road Bikes, trái ngược với kênh Internet. Road Bikes phát triển mạnh mẽ, mang về lên đến 16 triệu USD doanh thu cho Adventureworks vào băm này. Doanh thu của xe đạp leo núi có xu hướng giảm vào năm 2013, doanh nghiệp nên có những chính sách kích thích nhu cầu mua dòng xe đạp này vào năm 2014 để doanh thu có sự tăng trưởng hơn.

f.	Tỷ suất sinh lời của Category Product
![image](https://github.com/user-attachments/assets/22399ea0-1d81-412a-918a-e07615147633)
 
Hình 2.8: Tỷ suất lợi nhuận của các Category

Tuy Bikes là sản phẩm chủ đạo của AdventureWorks, mang lại doanh thu cao nhất nhưng Accessories mới là Nhóm sản phẩm có khả năng sinh lời nhiều nhất.

g.	Top 5 sản phẩm có doanh thu cao nhất
 ![image](https://github.com/user-attachments/assets/ea02b0b1-47bc-483d-bbcd-a35397a5427d)
Hình 2.10: Top 5 sản phẩm mang lại doanh thu cao nhất ở Nhóm hàng Clothing

Mục tiêu của mọi tổ chức là tạo ra lợi nhuận, để tạo ra lợi nhuận tổ chức cần biết rõ sản phẩm khách hàng đang mua. Hình trên cho biết top 5 sản phẩm mang lại doanh thu cao nhất cho doanh nghiệp ở các Category. Bộ phận liên quan nên ưu tiên nỗ lực trong việc sản xuất và phát triển.

h.	Correlation
![image](https://github.com/user-attachments/assets/e57c43e5-00be-48c5-9322-98b8375933eb)
 
 ![image](https://github.com/user-attachments/assets/3f2e0a7f-be9f-4646-8806-da46baf937e5)
Hình 2.11: Biểu đồ tương quan giữa các biến với biến SalesAmount (Doanh thu)

Nhìn vào Hình 2.11 ta có thể thấy Feight, ExtendedAmount, TaxAmt là các biến có tương quan mạnh mẽ với SalesAmount nhất vì các điểm dữ liệu có xu hướng đi lên theo một đường thẳng và đồng nhất với nhau. Các biến như OrderQuantity, ProductStandardCost và UnitPrice có tương quan nhưng không mạnh mẽ bằng. Cuối cùng các biến hầu như không thể hiện mối tương quan với biến SalesAmount là Profit và DiscountAmount. Từ đó ta có thể rút ra được rằng các biến có tương quan càng cao thì sẽ có sự ảnh hưởng đến SalesAmount càng cao.

i.	Dự đoán doanh thu của Bikes ở kênh Reseller

Bikes là một trong những sản phẩm chủ chốt trong danh mục của AdventureWorks. Trong một cửa hàng đa dạng như vậy, Bikes thường là một phần quan trọng trong doanh số bán hàng và doanh thu, đặc biệt là kênh Reseller. Việc dự đoán doanh thu của Bikes sẽ cung cấp thông tin chi tiết và quan trọng về xu hướng tiêu thụ và hiệu suất kinh doanh của một phần lớn trong tổng doanh thu của cửa hàng. Điều này giúp tập trung phân tích và tối ưu hóa các chiến lược kinh doanh cho nhóm hàng quan trọng nhất này

Dự đoán bằng chuỗi thời gian (time series) là một kỹ thuật mạnh mẽ trong lĩnh vực dự đoán và phân tích dữ liệu. Phương pháp này tập trung vào việc phân tích và dự đoán các xu hướng và biến động trong dữ liệu theo thời gian. Trong trường hợp của chúng ta, chúng ta sử dụng phương pháp này để dự đoán doanh thu của Bikes trong cơ sở dữ liệu AdventureWorks ở kênh Reseller.

Phương pháp dự đoán chuỗi thời gian thường bắt đầu bằng việc phân tích các mẫu và xu hướng trong dữ liệu lịch sử. Các phương pháp phổ biến là Average Moving, Smoothing Moving, Linear Regression và ARIMA. Mỗi phương pháp phù hợp với đặc điểm của dữ liệu khác nhau. Cụ thể nếu giá trị dãy số thời gian biến động ngẫu nhiên nhỏ thì phù hợp với phương pháp Average Moving và Smoothing Moving. Giá trị dãy số thời gian biến động ngẫu nhiên lớn, có xu hướng thì phù hợp với phương pháp Linear Regression. Cuối cùng nếu giá trị dãy số thời gian biến động ngẫu nhiên lớn nhưng không có xu hướng thì sẽ sử dụng phương pháp ARIMA.
     ![image](https://github.com/user-attachments/assets/c62c394d-d3f3-4901-8131-190501ab0414)
Hình 2.12: Biến động doanh thu của Bikes ở kênh Reseller qua thời gian

Qua hình 2.12, ta có thể thấy doanh thu của Bikes biến động rất lớn qua các tháng, đặc biệt là không có xu hướng nào cả. Như đã nói ở trên, với đặc điểm như thế thì sẽ sử dụng ARIMA cho việc dự đoán doanh thu của Bikes.

Việc dự đoán và đề xuất thực hiện qua các bước như sau: 

1.	Truy xuất dữ liệu cần từ Microsoft SQL Server về file Excel 
![image](https://github.com/user-attachments/assets/a5aa0d90-15af-4253-bc8d-89d78f131cfc)
 
Hình 2.12: Tạo View về thông tin doanh thu của xe đạp ở kênh bán lẻ


0.	Add xử lý và dự đoán bằng Python

Thêm dataset được xuất về file Excel ở bước trên vào để xử lý
 ![image](https://github.com/user-attachments/assets/b1761f64-d946-48b9-9dc5-eb9c01acaef4)

Xóa cột không cần thiết và chuyển đổi dữ liệu cho phù hợp
 ![image](https://github.com/user-attachments/assets/d273c78f-d2ab-422f-b0ea-744cd791a93b)

Xây dựng và lựa chọn mô hình tối ưu nhất
 ![image](https://github.com/user-attachments/assets/4be9b937-7889-45cc-ba8b-4c460c95b12e)
 	![image](https://github.com/user-attachments/assets/5bd44162-d416-4e45-bcc4-69ebe3df61e7)

Kết quả dự đoán doanh thu của Bikes tại Reseller cho 12 tháng tiếp theo
 ![image](https://github.com/user-attachments/assets/38526cec-1d48-4311-acea-c8b7028602a0)
Hình 3.13: Doanh thu từ 2011-2014

 ![image](https://github.com/user-attachments/assets/2220029a-dca7-4504-8b8d-aa6cb6efbc40)
Hình 2.14: Doanh thu của các tháng năm 2014 được dự đoán

    Quá trình cụ thể được thực hiện tại đây: (https://colab.research.google.com/drive/1OfX5fhx1sPWRaYiv8HDLa0Pm-gD1kR7z?usp=sharing).

*.	Đề xuất

Theo hình 2.14, doanh thu có sự dao động mạnh mẽ theo mùa, ta nên tăng cường chiến dịch tiếp thị vào các mùa cao điểm là cuối mỗi quý để thu hút khách hàng. Đảm bảo hàng luôn đầy đủ trong kho để tránh tình trạng thiếu hụt khi nhu cầu tăng cao. 

Để làm dịu bớt sự sụt giảm doanh thu trong các mùa doanh thu thấp, cửa hàng nên cân nhắc đưa ra các chương trình khuyến mãi, giảm giá dưới dạng tri ân khách hàng chẳng hạn.

3.	Sales Market Analytics
a.	Tổng quan về tình hình bán hàng của từng quốc gia
 ![image](https://github.com/user-attachments/assets/ece5249f-eca5-4859-8887-50dc482295e4)
Hình 3.1: Phần trăm doanh thu của từng quốc gia

 ![image](https://github.com/user-attachments/assets/77a63343-d729-4549-8cba-cb92bd4d54a6)
  Hình 3.2: Phần trăm lợi nhuận của từng quốc gia 

Nhìn chung qua hai biểu đồ trên thì United States là quốc gia có đóng góp cao về cả doanh thu (57.37%) lẫn lợi nhuận (35.41%)Điều đặc biệt ở trên là Canada mặc dù là nước có tỷ lệ doanh thu cao thứ hai (14.89%) nhưng lại có tỷ lệ lợi nhuận thấp nhất trong các quốc gia chỉ 8.03%, có thể giải thích ở Hình 3.3 mặc dù số đơn đặt hàng lên đến 50.000 đơn (ở cả 2 kênh) nhưng sản phẩm chính của cửa hàng là Bikes thì số đơn hàng rất thấp (chưa đến 14.000 đơn)

Ngược lại với Canada thì Australia mặc dù đóng góp doanh thu nhỏ hơn Canada nhưng lợi nhuận mà quốc gia này mang lại lại tất cao (28.5%) chỉ sau United States, tương tự chúng ta có Hình 3.4 để giải thích cho nguyên nhân trên là mặc dù Australia có Canada số lượng đơn đặt hàng thấp hơn chỉ 18.000 đơn nhưng Bikes lại chiếm số đơn đặt hàng nhiều hơn Canada nên vì vậy doanh thu của nó đã cao vượt trội.

 ![image](https://github.com/user-attachments/assets/1a0957da-653e-4ed7-a894-9779e2824671)
          Hình 3.3: Số lượng đơn đặt hàng của quốc gia Canada

 ![image](https://github.com/user-attachments/assets/3ae6885c-61f1-48d3-abb4-22c9e9396f3d)
Hình 3.4: Số lượng đơn đặt hàng của quốc gia Australia

b.	Tổng quan về thị trường kinh doanh
 ![image](https://github.com/user-attachments/assets/8ef42a02-4d05-4191-85f4-3ef28e06fc25)
 ![image](https://github.com/user-attachments/assets/bc512ebb-b588-4d16-8b1a-bfc329b4d893)
Hình 3.5: Các quốc gia có các kênh bán hàng trực tuyến và các cửa hàng của Adventureworks trong năm 2011-2013

Trong 3 năm từ 2011 đến 2013 thì doanh nghiệp đã bán hàng thông qua hai kênh là Internet và Reseller. Đối với kênh Internet thì rất dễ kinh doanh trên đó và tốn rất ít chi phí để vận hành nên từ những năm đầu Adventureworks đã bán hàng trên các quốc gia như United States, Australia, United Kingdom, Canada, France và Germany

Đối với kênh Reseller thì không dễ dàng bắt đầu với nhiều cửa hàng trên nhiều quốc gia như thế vì chi phí vận hành rất cao nên trong năm 2011 thì Adventureworks chỉ có cửa hàng tại hai quốc gia đó là United States và Australia và kể từ 2012 trở đi Adventureworks đã quyết định mở rộng thị trường bán hàng như với kênh Internet

c.	Số lượng đặt hàng qua cả 2 kênh bán hàng theo từng quốc gia
 ![image](https://github.com/user-attachments/assets/28142915-a55f-4409-8de2-a4b964b55052)
Hình 3.6: Số lượng đặt hàng qua cả 2 kênh bán hàng theo từng quốc gia
                                              
Biểu đồ trên biểu diễn số lượng đơn đặt hàng từ 2 kênh trên từng quốc gia. Nhìn chung thì số lượng đơn đặt hàng của Reseller luôn nhiều hơn Internet vì mặt hàng chủ yếu là Bikes vì để lựa chọn mẫu mã và chất lượng của sản phẩm nên khách hàng sẽ ưu tiên mua tại cửa hàng hơn
United States là thị trường lớn cho cả 2 kênh bán. Điều này có thể do một số yếu tố, chẳng hạn như dân số của United States lớn, có nền kinh tế phát triển mạnh mẽ và đôi khi yếu tố văn hóa của người dân ở đây cũng ảnh hưởng ít nhiều vì người dân ở đây đa số sẽ đi bộ và đi xe đạp rất nhiều tạo điều thuận lợi cho công ty xâm nhập vào thị trường này.

Bên cạnh đó có Canada có số lượng đơn đặt hàng chỉ xếp sau United States (-104.000 đơn) vì Canada cũng là một quốc gia có nền kinh tế tương đối phát triển, Chính phủ ở đây luôn có các chính sách hỗ trợ doanh nghiệp phát triển và cạnh tranh hiệu quả hơn trên thị trường. Ngoài ra còn có một yếu tố nhỏ đó là Canada là quốc gia tiếp giáp với United States nên đôi khi cũng có ảnh hưởng tích cực từ nó

Các quốc gia như Australia, United Kingdom, Germany, France thì không có chênh lệch nhiều và quốc gia có số lượng đơn đặt hàng thấp nhất là Germany (13.000 đơn) vì Germany là một quốc gia có nền kinh tế sản xuất công nghiệp và xuất khẩu điều này có thể ảnh hưởng nhu cầu mua các mặt hàng của Adventurework cung cấp. Doanh nghiệp có thể nghiên cứu thêm về thị trường để hiểu rõ thêm về nhu cầu, sở thích và hành vi mua sắm của người tiêu dùng. Bên cạnh đó có thể mở rộng các cửa hàng bán lẻ và phát triển các chiến lược tiếp thị để tăng tính nhận diện của doanh nghiệp đối với khách hàng.
![image](https://github.com/user-attachments/assets/15d8dfc8-aa4e-4b87-ad13-9203da0d3ee7)
 
Hình 3.7: Doanh thu qua từ 2011-2013

Với số lượng đơn đặt hàng như trên thì ta thu được doanh thu qua các năm như biểu đồ 3.7. Với doanh thu cao của United States thì dễ dàng giải thích quốc gia này cũng là quốc gia có số lượng đơn đặt hàng cao nhất.

Tiếp đến là Australia, có doanh thu năm 2011 và năm 2012 dẫn đầu nhưng đến 2013 thì chỉ thấp hơn mỗi United States, Australia là quốc gia có số lượng đơn đặt hàng khá thấp (chỉ 18.000 đơn) nhưng về doanh số lại cao có thể giải thích rằng đa số khách hàng ở quốc gia này đã mua mặt hàng là Bikes vì đây là mặt hàng chính của doanh nghiệp và có doanh thu cao nhất trong số các mặt hàng còn lại.

Ngược lại với Australia thì Canada là quốc gia có số lượng đơn đặt hàng khá cao (50.000 đơn) nhưng về doanh thu thấp nhất trong tất cả các nước còn lại. Còn lại France, Germany, United Kingdom đều có doanh thu là tương đương nhau.

Nhìn tổng quan thì vào năm 2012 thì doanh thu đa số đều giảm có tăng thì chỉ tăng nhẹ và tăng trưởng vượt trội trở lại vào năm 2013. Như đã phân tích ở Hình 3.5 thì Adventureworks đã quyết định mở rộng thị trường bán lẻ ở nhiều quốc gia đi kèm là phần chi phí rất lớn nên đã dẫn đến doanh thu có phần sụt giảm.

Có thể doanh nghiệp đã có thay đổi về các chiến dịch quảng cáo, marketing, nâng cao chất lượng sản phẩm, đa dạng các mặt hàng cũng có thể có các chương trình giảm giá để kích thích khách hàng lựa chọn của hàng của Adventureworks để mua sắm, nên doanh thu vào năm 2013 đã có sự tăng trưởng rõ rệt.

d.	Chi phí và lợi nhuận của từng quốc gia
![image](https://github.com/user-attachments/assets/ec9dfb28-ea17-4a18-87a0-15623d6c696f)
 
Hình 3.8: Chi phí của từng quốc gia

Biểu đồ trên biểu diễn chi phí của từng quốc gia qua 2 kênh bán hàng, nhìn chung thì kênh Internet là kênh bán hàng ít tốn chi phí hơn kênh Reseller đều đó có thể dễ dàng giải thích rằng vì khi bán lẻ doanh nghiệp sẽ tốn chi phí cho mặt bằng và nhân viên nên chi phí sẽ nhiều hơn so với bán online
![image](https://github.com/user-attachments/assets/4621b851-e402-4adb-9b78-f03eebc23220)
 
Hình 3.9: Lợi nhuận của từng quốc gia
 
Sau khi trừ đi hết chi phí thì ta sẽ thu được lợi nhuận, biểu đồ trên cho ta thấy được lợi nhuận của từng quốc gia qua 2 kênh bán với sự chênh lệch không đồng đều của các quốc gia.

Dẫn đầu lợi nhuận từ cả hai kênh đó là United States (4.8M) điều này có thể dễ dàng giải thích vì đây là một trong những quốc gia có lãnh thổ lớn nhất thế giới và đi kèm là số dân đông nên đây là yếu tố rất lớn để mang về lợi nhuận cao cho doanh nghiệp.

Bên cạnh đó Australia cũng là quốc gia có lợi nhuận khá cao (kênh Internet: 3.7M) nhưng điều đặc biệt ở đây là về lợi nhuận ở kênh Reseller lại âm nhưng con số rất nhỏ (0.1M) đôi khi vì một số lý do như sửa chữa và nâng cấp về cửa hàng nên dẫn đến lợi nhuận âm như vậy. Và quốc gia có đặc điểm chung về lợi nhuận kênh Reseller âm (0.1M) đó là Germany.

Đối với United Kingdom và France thì lợi nhuận của kênh Reseller lại bằng 0 có thể là do chính sách bán hàng những năm đầu chưa được ổn định bên cạnh đó các chi phí vận hành cửa hàng hay là chi phí nhân viên chưa được tối ưu hóa.

Canada là một quốc gia có tổng lợi nhuận nhỏ nhất nhưng lại ổn định về lợi nhuận của cả hai kênh bán hàng (Reseller: 0.3M, Internet: 0.8).

Để xem xét tình trạng lợi nhuận ở kênh Reseller chưa được cao hay thậm chí âm và bằng 0 thì doanh nghiệp nên cần tối ưu hóa các chi phí để điều hành các cửa hàng bán lẻ này, bên cạnh đó cần có những chính sách thu hút khách hàng nhằm để tăng doanh thu và tăng tính cạnh tranh cho doanh nghiệp.

e.	Số lượng đơn đặt hàng SubCategory của từng quốc gia

 ![image](https://github.com/user-attachments/assets/7788fa74-1d68-4fe6-8ada-6620530841ac)
Hình 3.10: Số lượng đơn đặt hàng SubCategory của Bikes
 ![image](https://github.com/user-attachments/assets/c925174c-b759-494e-9c5c-75f69242ad26)
Hình 3.11: Số lượng đơn đặt hàng SubCategory của Clothing
![image](https://github.com/user-attachments/assets/cc3543e8-2420-427c-ae57-8b5ad639f761)
 
Hình 3.12: Số lượng đơn đặt hàng SubCategory của Accessories
 ![image](https://github.com/user-attachments/assets/10f7546d-19ff-4e01-a906-f5161e493e77)
Hình 3.13: Số lượng đơn đặt hàng SubCategory của Component

Sau khi xem xét kỹ, nhận thấy rằng các sản phẩm phổ biến khác nhau giữa các khu vực khác nhau, nhưng đặc biệt là ở United States luôn là quốc gia có số lượng đơn đặt hàng cao nhất 

Đối với Hình 3.10 SubCategory của Bikes thì sản phẩm có lượt bán cao nhất là Road Bikes (hơn 40.000 đơn hàng) vì đây là loại xe phổ biến dễ sử dụng và phù hợp với nhu cầu của đa số khách hàng. Vì nhu cầu chính của mọi người là đi lại, lưu thông trên đường nên Road Bike là một trong những phương tiện giao thông mà họ sử dụng

Tiếp theo với Hình 3.11 ta có Jerseys (áo thi đấu) là sản phẩm có lượt bán ra cao nhất (hơn 18.000 đơn), có thể vì lợi ích của doanh nghiệp như để quảng bá cửa hàng thông qua in ấn thông tin trên sản phẩm Jerseys nên đã có các chiến dịch để bán được nhiều Jerseys hơn. Bên cạnh đó khách hàng có yêu cầu mua áo để tham gia các cuộc thi cũng như các hoạt động đạp xe tập thể, vì sản phẩm Jerseys cũng là một vật để thể hiện tinh thần đồng đội cao nên được mọi người ưa chuộng nhiều
	
Với SubCategory của Accessories (Hình 3.12) thì Helmets (mũ bảo hiểm) là sản phẩm có số lượng đơn hàng cao nhất trong số các sản phẩm còn lại (xấp xỉ 13.000 đơn) có lẽ vì đây là sản phẩm bắt buộc phải có khi sử dụng phương tiện giao thông kể cả xe đạp để đảm bảo an toàn giao thông, nên có lượt mua cao là điều hiển nhiên

Cuối cùng về sản phẩm của Component (Hình 3.13) thì 2 SubCategory có số lượng bán tương đương nhau đó là Mountain Frames và Road Frames. Vì mục đích dùng xe đạp để leo núi và để lưu thông đi lại nên Mountain Frames và Road Frames là những vật dụng không thể thiếu. Và vì khách hàng mua chúng sẵn để trừ khi hư hỏng nên chúng có lượt mua cao đáng kể

4.	Sales Customer Analytics
a.	Tổng quan
 ![image](https://github.com/user-attachments/assets/fdea7662-80e9-40c2-8c78-0f57ee7d14ad)
 ![image](https://github.com/user-attachments/assets/abd73ef0-308e-432b-996d-084723e7a9d0)
Hình 4.1: Tổng quan về Khách hàng

Với tổng số khách hàng là 18.48K, giữa giới tính thì số lượng nam và nữ tương đương nhau, về tình trạng kết hôn cũng không chênh lệch nhiều và độ tuổi trung bình của khách hàng xấp xỉ 44 tuổi.

 ![image](https://github.com/user-attachments/assets/24fb432f-7fc9-422d-97cd-960a738926b2)
Hình 4.2: Biểu đồ phân bổ độ tuổi của Khách hàng

Khách hàng của doanh nghiệp đa số có độ tuổi từ 30 đến 50 tuổi vì đây là độ tuổi đã có thu nhập ổn định nên chiếm tổng số khách hàng lớn cũng không có gì là bất thường. Doanh nghiệp cũng nên tập trung vào tệp khách hàng này nhiều hơn vì đây là khách hàng tiềm năng của doanh nghiệp. Đồng thời cũng sẽ có các chương trình tiếp thị phù hợp và có thể mở rộng các mặt hàng để kích thích sự mua hàng các khách hàng dưới 30 tuổi và trên 50 tuổi.
![image](https://github.com/user-attachments/assets/4c099d7c-97b9-4088-9840-49682e51bac5)
 
Hình 4.3: Biểu đồ phần trăm mức lương của Khách hàng ở ba phân khúc

Mức thu nhập của khách hàng được chia thành 3 mức: Cao (High), Trung bình (Medium) và Thấp (Low). Ta có thể thấy từ biểu đồ trên số khách hàng có mức thu nhập Trung bình chiếm tỉ lệ rất cao (63.02%) tiếp đến là mức Thấp (28.18%)

b.	Ảnh hưởng của nghề nghiệp đến đơn đặt hàng
![image](https://github.com/user-attachments/assets/ec15a13c-4eaa-44bd-93bc-e93f996c6da7)
 
Hình 4.4: Tổng số lượng Khách hàng của mỗi ngành nghề

Biểu đồ trên cho ta thấy được nghề nghiệp của khách hàng và mỗi nghề sẽ có sự khác nhau về số lượng đơn đặt hàng. với Professional là ngành nghề có số lượng đơn đặt hàng nhiều nhất (19K) và nghề có số lượng đơn đặt hàng ít nhất là Manual (6.9K).

Mỗi ngành nghề có các nhu cầu mua hàng khác nhau và các mức thu nhập khác nhau nên dẫn đến sự khác biệt trên. Từ đó doanh nghiệp cần tìm hiểu nhu cầu của từng tệp khách hàng để có thể cung cấp các sản phẩm phù hợp hơn, có các chương trình tiếp thị để giúp khách hàng biết đến doanh nghiệp nhiều hơn.

Ảnh hưởng của học vấn đến doanh thu
 ![image](https://github.com/user-attachments/assets/d5a7432c-c069-40fe-bd11-a16e22f9aecb)
Hình 4.5: Tổng phần trăm Khách hàng ở mỗi mức trình độ học vấn

 Biểu đồ trên thể hiện trình độ học vấn của khách hàng tương đương với doanh thu mà họ mang lại cho doanh nghiệp, ở đây nhóm đóng góp doanh thu nhiều nhất là Bachelors với 33.72%.

Tiếp đến là Partial College (26.31%), Graduate Degree (18.6%) và High School với doanh thu là 15.8%.  Partial High School là nhóm mà doanh nghiệp thu được ít doanh thu nhất ở họ chỉ bằng ⅙ doanh thu của Bachelors (5.57%)

Nguyên nhân vì sao có sự khác biệt về doanh thu của từng trình độ học vấn như vậy nhìn chung thì học vấn càng cao thì mức doanh thu thu được từ họ càng lớn ta có thể giải thích như sau: đối với tệp khách hàng có trình độ học vấn cao như Bachelors thì đa số họ sẽ có mức thu nhập cao hoặc ổn định để có thể tiêu dùng mà mua sắm nên việc họ là nhóm khách hàng có đóng góp doanh thu lớn nhất là điều dễ hiểu. Ngược lại với nhóm Partial High School thì đây là nhóm còn nằm trong độ tuổi đi học và đa số không thể kiếm ra thu nhập cá nhân nên lượng mua hàng của doanh nghiệp đương nhiên sẽ ít hơn so với các nhóm còn lại từ đó doanh thu thu được từ tệp khách hàng này là ít nhất.

5.	Recommendations
a.	Về sản phẩm
Accessories là Nhóm sản phẩm có tiềm năng sinh lời tốt nhất. Chính vì thế, doanh nghiệp nên nâng cao chất lượng và đa dạng hóa dòng sản phẩm accessories của bạn để đáp ứng nhu cầu của các khách hàng trên toàn cầu. Tạo ra các sản phẩm độc đáo và hấp dẫn để thu hút sự chú ý của người tiêu dùng. Bên cạnh đó nên xây dựng hệ thống phân phối toàn cầu, hợp tác với các đối tác phân phối và nhà bán lẻ trên khắp thế giới để mở rộng mạng lưới phân phối và đưa sản phẩm của bạn đến tay người tiêu dùng trên các thị trường quốc tế.

b.	Về thị trường
Có tiềm năng lớn cho doanh số bán hàng ở Australia. Để phát triển thị trường này, cần triển khai các chiến lược tiếp thị hiệu quả và sáng tạo. Đặc biệt, cần tập trung vào việc mở rộng đa dạng sản phẩm và áp dụng các ý tưởng mới vào lĩnh vực quần áo, phụ kiện, và xe đạp. Điều này là cần thiết vì khu vực này hiện đang gặp thách thức với giá trị đặt hàng và doanh số trung bình thấp nhất.
Theo Nghiên cứu, Netherlands có 27% tổng số chuyến đi và 25% số chuyến đi làm được thực hiện bằng xe đạp. Nó có 400 km làn đường dành cho xe đạp và gần 40% việc đi lại ở Amsterdam được thực hiện bằng xe đạp. Điều kỳ lạ là hầu hết người đi xe đạp đều không đội mũ bảo hiểm. Và trộm cắp xe đạp là một vấn đề lớn, với khoảng một trong năm (20%) chiếc xe đạp bị đánh cắp mỗi năm. Hiện này, AdventureWorks đã hoạt động tốt trên thị trường Châu Âu,  nên thực hiện các bước cần thiết để tiếp cận sang thị trường Netherlands nhằm cải thiện đáng kể doanh thu và lợi nhuận.

c.	Về khách hàng
Nên trao các ưu đãi và phần thưởng cho những khách hàng có hiệu suất cao nhất để khuyến khích bán hàng nhiều hơn. Họ cũng có thể tiến hành các buổi nâng cao năng lực để tư vấn cho những khách hàng có hiệu suất thấp về các chiến lược hiệu quả nhằm cải thiện doanh số bán hàng.

PHẦN C: TỔNG KẾT

Từ việc phân tích sâu và đánh giá kỹ lưỡng bộ dữ liệu của Công ty kinh doanh xe đạp và các phụ kiện leo núi Adventureworks trong khoảng thời gian từ tháng 2011 đến tháng 2013, nhóm đã có khả năng hỗ trợ Giám đốc kinh doanh cùng các phòng ban liên quan khác nhau để hiểu rõ hơn về tình hình hoạt động cụ thể trong thời gian này. Nhờ vào các phân tích chi tiết về xu hướng bán hàng, biến động trong ngành, và các yếu tố thị trường khác, chúng tôi đã có thể cung cấp cái nhìn toàn diện và chính xác về hiệu suất kinh doanh của Công ty.
Từ những thông tin này, chúng tôi đã đề xuất một loạt các phương án phát triển, bao gồm cải thiện sản phẩm hiện tại, phát triển sản phẩm mới phù hợp với nhu cầu thị trường, tối ưu hóa chiến lược giá cả, và tăng cường chiến lược tiếp thị và quảng bá. Điều này sẽ giúp Công ty tối ưu hóa doanh số bán hàng và tăng cường vị thế cạnh tranh trong giai đoạn tiếp theo của hoạt động kinh doanh.
Đồng thời, thông qua bài báo cáo với công cụ Power BI, nhóm đã hiểu rõ hơn về các kiến thức như phân tích dữ liệu, trực quan hóa dữ liệu qua các biểu đồ (Pie, Line, Bar Chart,...), bên cạnh đó nhóm còn tìm hiểu được chức năng Swap để giúp làm Dashboard một cách gọn gàng và dễ hiểu hơn
Tuy nhiên, trong quá trình thực hiện bài báo cáo này thì nhóm cũng gặp một số vấn đề gây trở ngại như bộ dữ liệu có quá nhiều bảng gặp rắc rồi trong lúc lựa chọn bảng để phù hợp với chủ đề của nhóm. Từ khó khăn đó, nhóm đã có thêm thời gian để hiểu về bộ dữ liệu hơn.
