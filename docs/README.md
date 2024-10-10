<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 3.24.1010.0 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalAdminexe%2F32410100-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalAdminexe%2F32410100-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalAdminexe%2F32410100-NasDHSolutions.json)
- 🐛: **💼**: **_Lỗi - BA TRẢ VỀ ĐIỀU TRỊ KẾT THÚC TẠI THÁNG MỚI GHI NHẬN SAI THÔNG TIN TRÊN 4750_**
- 🐛: Kiểm soát hồ sơ XML trường hợp trả về điều trị, cho xuất viện, thay đổi tháng ra viện ![](https://i.imgur.com/gGSup0k.png) ![](https://i.imgur.com/pqBY5NR.png) ![](https://i.imgur.com/4tT8wcp.png)
- ☑: https://github.com/dh-hos/dhg.hosptaltreatment/issues/276
## [v.3.24.1009.2]()
- 🐛: **💼**: **_Lỗi - BANT ĐỢT KẾT THÚC KHÔNG CÓ HỒ SƠ KHI XUẤT 4750 _**
- 🐛: ***Chỉnh lỗi lấy thiếu hồ sơ trên so với báo cáo QĐ130*** ![](https://i.imgur.com/Hwdlwxq.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/349
## [v.3.24.1009.1]()
- ✨: **💼**: **_💼 Admin - Thực hiện - Mô tả ICD10 theo QĐ 4469 - BYT -⏳Dự kiến :  2024-10-09_**
- ✨: ***Thêm chức năng chỉnh ICD loại trừ theo QDD4469 BYT*** ![](https://i.imgur.com/YecaNVk.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/676
## [v.3.24.1009.0]()
- ✨: **💼**: **_Mô tả và thực hiện hỗ trợ gởi bệnh nhân BANT thanh toán ngày XML1.ma_loai_kcb_**
- ✨: Thực hiện theo mô tả tham số ***`ma_loai_kcb.ba_ngoai_ngay`*** ![](https://i.imgur.com/FuxGUHO.png) ![](https://i.imgur.com/24t6x0q.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/84
## [v.3.24.1008.0]()
- 🐛: **💼**: **_Lỗi - Admin, Report XM3 4750 không lấy được mã DỊCH VỤ khi cho Vật tư kèm theo**
- 🐛: ***Chỉnh lỗi: XML03.MA_DICH_VU, XML03.TEN_DICH_VU thiếu đối với những VTYT đánh theo CLS,DV*** ![](https://i.imgur.com/SkH5ZCH.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/103
## [v.3.24.1004.4]()
- 🐛: **💼**: **_Lỗi - Report XML130 bảng 2 double số lượng thuốc_**
- 🐛: Chỉnh lỗi XML4750.bang2,3 bị tăng số lượng thuốc. ![](https://i.imgur.com/QgoL17P.png)
- ✨: ***Bổ sung chức năng xóa Hồ sơ XML4750 thừa (không nằm trong danh sách của 4210, chỉ áp dụng khi chọn Combo `Tất cả`, và không tìm theo Mã bệnh nhân, và chọn tất cả đối tượng )***
- ✨: ***Bổ sung cảnh báo khi có xóa hồ sơ thừa*** ![](https://i.imgur.com/Ba106vn.png)
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/135
## [v.3.24.1004.3]()
- 🐛: **💼**: **_Lỗi - Report XML130 bảng 2 double số lượng thuốc_**
- 🐛: Chỉnh lỗi XML4750.bang3 bị tăng số lượng CLS và VTYT. ![](https://i.imgur.com/X06MDoL.png)
- Lưu ý: nếu cập nhật bản mới vẫn còn, thì vào chức năng ***`Kiểm tra chi chí lại`***
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/135
## [v.3.24.1004.2]()
- 🐛: **💼**: **_Lỗi - Report XML130 bảng 2 double số lượng thuốc_**
- 🐛: Chỉnh lỗi XML4750.bang2 bị tăng số lượng thuốc. ![](https://i.imgur.com/QgoL17P.png)
- Lưu ý: nếu cập nhật bản mới vẫn còn, thì vào chức năng ***`Kiểm tra chi chí lại`***
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/135
## [v.3.24.1004.1]()
- 🐛: **💼**: **_Lỗi - Bệnh nội trú không có nhập thông tin con vẫn có XML9 4750 (bv Ô môn)_**
- 🐛: Thêm điều kiện lấy chính xác thông tin con, dữ liệu giấy chứng sinh XML09 ![](https://i.imgur.com/unyCqh6.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/102
## [v.3.24.1004.0]()
- ✨: **💼**: **_Lỗi - BANT theo ngày khi kết thúc bệnh án thì tạo thêm XML130 có mã bệnh án làm tăng số lượng XML Reports (trùng dữ liệu XML)_**
- ✨: ***Bổ sung chức năng xóa hồ sơ thừa so với danh sách hồ sơ 4210 trên chức năng kiểm tra chi phí***
- ![](https://i.imgur.com/diz3Crb.png) ![](https://i.imgur.com/Jvc3xOV.png) ![](https://i.imgur.com/yBv8fyT.png) ![](https://i.imgur.com/dV92tXP.png) ![](https://i.imgur.com/NM5DcTh.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/341
## [v.3.24.1003.0]()
- 🐛: **💼**: **_Lỗi - XML130 không cấn trừ được thuốc trả_**
- 🐛: Chỉnh lỗi cấn trừ sai thuốc trả trên XML03 ![](https://i.imgur.com/YQG3XVy.png)
- ***Lưu ý, phải thực hiện công cụ sai chi phí lại trên Reports thì XML4750 mới tính lại đúng.***
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/132
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/101
## [v.3.24.1002.0]()
- 🐛: **💼**: **_Lỗi - CLS thuộc loại thủ thuật vẫn load vào xml4 4750(bv Ung Bướu)_**
- 🐛: Loại bỏ những CLS thuộc kho TT, PT ra ngoài danh sách XML04 ![](https://i.imgur.com/yrSEyJW.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/100
## [v.3.24.0930.1]()
- ✨: **💼**: **_Yêu cầu - Bổ sung nội dung diễn biến vào XML5.dien_bien_ls đối với xml4750 (BV Châu Thành Đồng Tháp) _**
- ✨: Thay đổi DIEN_BIEN_LS theo mô tả ![](https://i.imgur.com/e1MAHv7.png)
- ![](https://i.imgur.com/J4qyYT1.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/658
## [v.3.24.0930.0]()
- 🐛: **💼**: **_Lỗi - XML4 4750 không lấy được MA_BS_DOC_KQ cls thủ thuật (BV Ung Bướu)_**
- 🐛: Chỉnh lỗi không lấy được MA_BS_DOC_KQ đối với các dịch vụ có thực hiện PT, TT ![](https://i.imgur.com/aVRnMUl.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/99
## [v.3.24.0921.1]()
- 🐛: **💼**: **_Admin thống kê XML bệnh nhân tháng cũ khi chọn ngày thống kê có ngày của tháng cũ (ngày cuối tháng cũ trùng ngày đầu tháng mới)_**
- 🐛: Lấy danh sách hồ theo theo THANG_QT, NAM_QT trên Form quản lý hồ sơ 4750 ![](https://i.imgur.com/hN7DGwT.png)
- 🐛: Chỉnh lỗi không tạo được ngày giờ kết thúc của tháng cũ, và ngày giờ bắt đầu của tháng mới ![](https://i.imgur.com/ulTI8Ok.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/133
## [v.3.24.0921.0]()
- ✨: **💼**: **_Hỗ trợ khách hàng - Yêu cầu có chức năng chỉ xuất XML hồ sơ_**
- ✨: Bổ sung chức năng chỉ xuất XML4750 (không xuất XML check in), sử dụng khi đã sử dụng Services để gửi checkin 
- ![](https://i.imgur.com/58udEc1.png) ![](https://i.imgur.com/HZumWEN.png) ![](https://i.imgur.com/sczh8gL.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/101
## [v.3.24.0919.1]()
- ✨: **💼**: **_Yêu cầu hỗ trợ trường hợp 1 bệnh nhân có dữ liệu XML trong 2 tháng gây lệch số hồ sơ Admin_**
- ✨:***Chỉnh lỗi trùng hồ sơ khi lấy dữ liệu trên Form xuất 4750 (chức năng kiểm tra thiếu hồ sơ nội trú)*** ![](https://i.imgur.com/Ip8ejcB.gif)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/131
## [v.3.24.0919.0]()
- ✨: **💼**: **_Yêu cầu hỗ trợ trường hợp 1 bệnh nhân có dữ liệu XML trong 2 tháng gây lệch số hồ sơ Admin_**
- ✨:***Chỉnh lỗi trùng hồ sơ khi lấy dữ liệu trên Form xuất 4750 (chức năng kiểm tra thiếu hồ sơ nội trú)*** ![](https://i.imgur.com/Aeg0Cku.gif)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/131
## [v.3.24.0918.2]()
- 🐛: **💼**: **_CHỨC NĂNG: KIỂM TRA CHI PHÍ GIỮA 4210 VAD QĐ 130 LỖI_**
- 🐛:![](https://i.imgur.com/BK7ZoSw.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/132
## [v.3.24.0918.1]()
- ✨: **💼**: **_Yêu cầu hỗ trợ trường hợp 1 bệnh nhân có dữ liệu XML trong 2 tháng gây lệch số hồ sơ Admin_**
- ✨: ***Xử lý trùng ma_lk trong current.psxml*** _Thực hiện loại bỏ các hồ sơ bị trùng, **Đồng thời** cập nhật lại giá trị ma_lk, ngay_ttoan, thang_qt, nam_qt trường hợp trùng (các giá trị này được lấy chi tiết từ psdangky và bnnoitru dựa vào loaihosokcb)_ 
- ✨: Việc kiểm tra trùng này trong chức năng ***[Lấy dữ liệu]*** trên form ![](https://i.imgur.com/vXVq6SD.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/131
## [v.3.24.0918.0]()
- 🐛: **💼**: **_Hỗ trợ khách hàng - Không cập nhật được XML4750_**
- 🐛: Chỉnh năng lưu lại XML4750 mới, không xóa được thông tin các XML cũ trước đó.
- ![](https://i.imgur.com/80JsJBI.png) ![](https://i.imgur.com/RH0z4TX.png) ![](https://i.imgur.com/0Hfyv5R.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/100
## [v.3.24.0916.0]()
- ✨: **💼**: **_Yêu cầu - Thực hiện gửi bảng Check in tự động._**
- ✨: ***Chức năng cấu hình gửi tự động theo loại checkin hoặc hồ sơ*** ![](https://i.imgur.com/cAuOKkF.png)
- ✨: ***Bỏ các chức năng gửi hồ sơ theo 4210, thay bằng chức năng gửi CheckIn và Hồ sơ 4750***![](https://i.imgur.com/if3yoev.png)
- ✨: ***Video kiểm thử việc gửi dữ liệu lên cổng đào tạo*** [Video](https://www.youtube.com/watch?v=KBXGYXtGaG0)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/587
## [v.3.24.0914.0]()
- 🐛: **💼**: **_XML 4750 Bệnh nhân lao (BANT ngày) lấy sai mã đối tượng (BV Quảng ngãi)_**
- 🐛: Thực hiện: Mo-ta-he-thong/XML130/QD4570/ma_doituong_kcb.md ![](https://i.imgur.com/YyOLxCN.png)
- 🐛: **XML01.MA_DOITUONG_KCB** ![](https://i.imgur.com/MNeWvLS.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/127
## [v.3.24.0913.0]()
- ✨: **💼**: **_Thực hiện lưu lại XML4750 khi thực hiện thay đổi tháng ra viện ⏳Dự kiến : 2024-09-11_**
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/634
## [v.3.24.0912.2]()
- ✨: **💼**: **_Yêu cầu - Hỗ trợ admin loại bỏ hồ sơ trùng_**
- ✨: Thêm chức năng kiểm tra trùng lặp khi bắt đầu lấy dữ liệu. Nếu có trùng MA_LK sẽ hỏi có xử lý xóa trùng hay không?
- ✨: **Xử lý xóa trùng lặp theo nguyên tắt sau: ưu tiên giữ lại dòng có trường daguibhxh lớn hơn, rồi đến ngay_ttoan lớn hơn**
- ![](https://i.imgur.com/FkeiMDa.png)![](https://i.imgur.com/AIGNQJC.png)![](https://i.imgur.com/po3VM8B.png)![](https://i.imgur.com/cFxyZ0A.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/644
## [v.3.24.0912.1]()
- ✨: Thực hiện Mo-ta-he-thong/XML130/QD4570/ma_loai_kcb.md ![](https://i.imgur.com/tqOYdLS.png)
- ✨: **XML01.MA_LOAI_KCB** = 07 khi psdangky.trangthaichuyentuyen IN (5,6)
- ✨: Thực hiện Mo-ta-he-thong/XML130/QD4570/ma_doituong_kcb.md ![](https://i.imgur.com/1Rzz1jh.png)
- ✨: **XML01.MA_DOITUONG_KCB**
- ✨: ![](https://i.imgur.com/eVvUwns.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/127
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/130
## [v.3.24.0912.0]()
- ✨: **💼**: **_💼 Admin - Thực hiện xóa hồ sơ XML4750 khi thực hiện trả về điều trị BA Nội trú⏳Dự kiến : 2024-09-12_**
- ✨: Xóa hồ sơ XML4750 khi trả về điều trị BA Nội trú ![](https://i.imgur.com/bzNTtj7.png)![](https://i.imgur.com/X1BO3hk.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/645
## [v.3.24.0911.6]()
- 🐛: Lỗi - XML13 thông tin TEN_THUOC bị trùng tên thuốc (1 thuốc bị lập lại nhiều lần) ![](https://i.imgur.com/oj9W0ZL.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/95
## [v.3.24.0911.5]()
- 🐛: **💼**: **_Bệnh nhân nội trú có thanh toán chi phí ngoại trú XML4750 admin không load được hs ngoại trú_**
- 🐛:Fix lỗi load thiếu hồ sơ ngoại trú (khi có bệnh án nội trú ) ![](https://i.imgur.com/ILGskmX.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/126
## [v.3.24.0911.4]()
- ✨: **💼**: **_Lỗi - XML9 cột NGAY_SINH_NND nếu để năm sinh +0000 khi bệnh nhân chỉ có năm sinh gởi cổng báo lỗi_**
- ✨: **XML09.NGAYSINH_NND** xử lý nếu **0000**, thì thay đổi thành **0101** ![](https://i.imgur.com/hdxiWLE.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/96
## [v.3.24.0911.3]()
- 🐛: **💼**: **_Lỗi - VTYT lấy sai DON_GIA_BV trên XML03 Trường hợp sử dụng chức năng (option) DON_GIA_BV là DON_GIA_BH_**
- 🐛: Xử lý DON_GIA_BV theo cấu hình trên Admin ![](https://i.imgur.com/wca7ckz.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/94
## [v.3.24.0911.2]()
- ✨: XML03.GOI_VTYT theo mô tả ![](https://i.imgur.com/BuCQJie.png)
## [v.3.24.0911.1]()

- 🐛: **💼**: **_Yêu cầu - Admin và Report thống nhất cách lấy XML để đơn vị đối chiếu số lượng hồ sơ_**
- 🐛: Thống nhất lấy THANG_QT, NAM_QT giống 4210 (nội trú, bệnh án ngoại trú theo đợt lấy theo thangrv, namrv trong bnnoitru)
- 🐛: Chức năng kiểm tra hồ sơ sai giữa 4210 và 4750 theo THANG_QT và NAM_QT. ![](https://i.imgur.com/5FrT7sv.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/627
## [v.3.24.0911.0]()
- ✨: Thêm chức năng kiểm tra sai chi chi phí đối với tất cả hồ sơ 4210 theo danh sách đã lấy lên ![](https://i.imgur.com/0Catr61.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/642
## [v.3.24.0909.0]()
- ✨: Đổi màu tab XML đang chọn ![](https://i.imgur.com/xI6Iny8.png)
- ✨: **💼**: **_💼 DLL - Thực hiện không lưu hồ sơ XML130 khi chi phí bằng 0 ⏳Dự kiến :  2024-09-13_**
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/124
## [v.3.24.0904.2]()
- 🐛: **💼**: **_Yêu cầu - Cập nhật mô tả cột pp_dieutri của XML13 theo cấu hình trên Admin_**
- 🐛: XML07.PP_DIEU_TRI lấy theo XML01 ![](https://i.imgur.com/iPQdv5s.png)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/279
## [v.3.24.0904.1]()
- 🐛: **💼**: **_Yêu cầu - Cập nhật mô tả cột pp_dieutri của XML13 theo cấu hình trên Admin_**
- 🐛: XML01.PP_DIEU_TRI, PP_DIEUTRI lấy theo XML01 ![](https://i.imgur.com/rlz2Pa0.png)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/279
## [v.3.24.0904.0]()
- 🐛: **💼**: **_Hỗ trợ khách hàng - XML03 sai TY_LE_DV_**
- 🐛: XML03.TY_LE_DV, TY_LE_BH bị sai khi có pshdxn_giabhyt > 0 ![](https://i.imgur.com/hL1Ikrq.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/88
## [v.3.24.0903.0]()
- 🐛: **💼**: **_XML13: TOMTAT_KQ không load dữ liệu_**
- 🐛:XML13.TOMTAT_KQ không lấy được dữ liệu ![](https://i.imgur.com/tDtuPN9.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/120
## [v.3.24.0830.4]()
- ✨: **💼**: **_Yêu cầu - Hỗ trợ XML1 mã loại KCB = 02_**
- ✨: Thêm cấu hình để lựa chọn NGAY_RA theo QĐ4750 hoặc theo ngày in phiếu ![](https://i.imgur.com/8WzOVwC.png)![](https://i.imgur.com/kmTDmJp.png)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/277
## [v.3.24.0830.3]()
- ✨: **💼**: **_Yêu cầu - Module Reports bổ sung form xuất XML130 (theo Quyết định 4750) và Mẫu C79 (được lấy từ dữ liệu XML4750)._**
- ✨: Bổ sung chức năng kiểm tra thiếu hồ sơ, sai chi phí XML4750 và XML4210
- ✨: Xem XML4750 giống phân hệ Reports
- ![](https://i.imgur.com/5bkiE5w.png)![](https://i.imgur.com/eS7uh4L.png) ![](https://www.youtube.com/watch?v=UREWiotZZZw)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0830.2]()
- ✨: **💼**: **_Yêu cầu - Module Reports bổ sung form xuất XML130 (theo Quyết định 4750) và Mẫu C79 (được lấy từ dữ liệu XML4750)._**
- ✨: Bổ sung chức năng kiểm tra thiếu hồ sơ, sai chi phí XML4750 và XML4210
- ✨: Xem XML4750 giống phân hệ Reports
- ![](https://i.imgur.com/5bkiE5w.png)![](https://i.imgur.com/eS7uh4L.png) ![](https://www.youtube.com/watch?v=UREWiotZZZw)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0830.1]()
- ✨: **💼**: **_Yêu cầu - Module Reports bổ sung form xuất XML130 (theo Quyết định 4750) và Mẫu C79 (được lấy từ dữ liệu XML4750)._**
- ✨: Bổ sung chức năng kiểm tra thiếu hồ sơ, sai chi phí XML4750 và XML4210
- ✨: Xem XML4750 giống phân hệ Reports
- ![](https://i.imgur.com/5bkiE5w.png)![](https://i.imgur.com/eS7uh4L.png) ![](https://www.youtube.com/watch?v=UREWiotZZZw)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0830.0]()
- ✨: **💼**: **_Yêu cầu - Module Reports bổ sung form xuất XML130 (theo Quyết định 4750) và Mẫu C79 (được lấy từ dữ liệu XML4750)._**
- ✨: Bổ sung chức năng kiểm tra thiếu hồ sơ, sai chi phí XML4750 và XML4210
- ✨: Xem XML4750 giống phân hệ Reports
- ![](https://i.imgur.com/5bkiE5w.png)![](https://i.imgur.com/eS7uh4L.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0829.4]()
- ✨: **💼**: **_Yêu cầu - Hỗ trợ trường hợp lỗi báo từ cổng BHXH Ngày Thực hiện y lệnh không hợp lệ_**
- Thêm chức năng cấu hình ![](https://i.imgur.com/98ifU0F.png) ![](https://i.imgur.com/o3teEcA.png)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/275
## [v.3.24.0829.3]()
- 🐛: **💼**: **_Module admin không hoạt động được khi thực hiện gửi xml 4750_**
- 🐛: Bỏ thông báo lỗi khi gửi nhiều hồ sơ
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/116
## [v.3.24.0829.2]()
- ✨: **💼**: **_Yêu cầu - Module Reports bổ sung form xuất XML130 (theo Quyết định 4750) và Mẫu C79 (được lấy từ dữ liệu XML4750)._**
- ✨: Bổ sung chức năng kiểm tra thiếu hồ sơ so với C79-HD![](https://i.imgur.com/GBIaQMZ.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0829.1]()
- ✨: **💼**: **_Yêu cầu - Module Reports bổ sung form xuất XML130 (theo Quyết định 4750) và Mẫu C79 (được lấy từ dữ liệu XML4750)._**
- ✨: Bổ sung chức năng kiểm tra thiếu hồ sơ so với C79-HD![](https://i.imgur.com/GBIaQMZ.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0829.0]()
- 🐛: **💼**: **_Lỗi - XML2 LẤY SỐ LƯỢNG CẤN TRỪ THUỐC TRẢ SAI THEO MÃ THẺ_**
- 🐛: XML02,03 cấn trừ thuốc sai số lượng theo mức hưởng ![](https://i.imgur.com/Sa7ypak.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/92
## [v.3.24.0827.4]()
- ✨: **💼**: **_Hỗ trợ khách hàng - Chức năng chọn nhiều mã liên kết từ Cổng GĐBHYT trả về_**
- ✨: Thêm chức năng cho phép load danh sách bệnh nhân từ tập tin Excel (từ cổng GĐ trả về). Điều kiện là trong tệp Excel phải có cột `ma_lk` hoặc `Mã liên kết` hoặc `malk`
- ![](https://i.imgur.com/zLL6uMI.png) ![](https://i.imgur.com/iKyBWo9.png) ![](https://i.imgur.com/oicGBLN.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/81
## [v.3.24.0827.3]()
- ✨: **💼**: **_Hỗ trợ khách hàng - Chức năng chọn nhiều mã liên kết từ Cổng GĐBHYT trả về_**
- ✨: Thêm chức năng cho phép load danh sách bệnh nhân từ tập tin Excel (từ cổng GĐ trả về). Điều kiện là trong tệp Excel phải có cột `ma_lk` hoặc `Mã liên kết` hoặc `malk`
- ![](https://i.imgur.com/zLL6uMI.png) ![](https://i.imgur.com/iKyBWo9.png) ![](https://i.imgur.com/oicGBLN.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/81
## [v.3.24.0827.2]()
- 🐛: **💼**: **_Hỗ trợ - Lỗi XML4750 - Lệch tiền thuốc giữa XML01 và XML02_**
- 🐛: **XML01.T_THUOC** lệch với SUM(**XML02.THANH_TIEN_BV**) ![](https://i.imgur.com/0gNSfZl.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/80
## [v.3.24.0827.1]()
- ✨: **💼**: **_Yêu cầu - BỔ SUNG OPTION ĐƠN VỊ TUỲ CHỌN GIỜ PHÚT MẶC ĐỊNH THEO MÔ TẢ CHO XML1.NGAY_RA_**
- ✨: Thực hiện XML01.NGAY_RA theo mô tả [xml130.bang01](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang01%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md) ![](https://i.imgur.com/N78HDJM.png)
- ![](https://i.imgur.com/ou10K57.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/618
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/620
## [v.3.24.0827.0]()
- 🐛: **💼**: **_Lỗi - Admin XML3 không lấy được người thực hiện Siêu âm_**
- 🐛:Không xử trí trường hợp XML03.NGAY_YL lớn hơn XML01.NGAY_RA ![](https://i.imgur.com/S3Cf2CZ.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/91
## [v.3.24.0826.0]()
- ✨: **💼**: **_Yêu cầu - Bổ sung thêm chức năng lưu Loại bênh nhân 4750_**
- ✨:XML06.MA_LOAI_BN lấy theo loaibenhnhan4750 trong fhi_dieutriarv nếu khác rỗng, ngược lại lấy theo cách hiện tại
- ![](https://i.imgur.com/AspaKbC.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/595
## [v.3.24.0823.1]()
- ✨: **💼**: **_Yêu cầu - BỆNH NHÂN ĐIỀU TRỊ OPC CHƯA LẤY ĐÚNG XML1.MA_DOITUONG_KCB_**
- ✨: Thực hiện XML01.MA_DOITUONG_KCB: theo mô tả [Table xml130.bang01](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang01%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md) ![](https://i.imgur.com/TK2eONV.png) 
- ![](https://i.imgur.com/TinUOhF.png)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/266
## [v.3.24.0823.0]()
- ✨: **Thực hiện**: **_Yêu cầu - Bổ sung tham số cho phép người dùng tự cập nhật nội dung XML1.pp_dieu_tri đối với bệnh nhân khám ngoại trú/toa xuất viện_**
- ✨: Hỗ trợ cấu trúc thêm option chọn XML01.PP_DIEU_TRI đối với Ngoại trú, Toa xuất viện ![](https://i.imgur.com/YKtd4K4.png) ![](https://i.imgur.com/NjTbBOi.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/621
## [v.3.24.0822.2]()
- ✨: **Thực hiện**: **_Yêu cầu - ĐIỀU CHỈNH CÁCH LẤY XML13.TEN_DV_**
- ✨: XML13.TEN_DICH_VU: Xử lý loại bỏ trùng ![](https://i.imgur.com/ZzKJTPO.png)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/267
## [v.3.24.0822.1]()
- ✨: **Thực hiện**: **_Yêu cầu - Bổ sung tham số cho phép người dùng tự cập nhật nội dung XML1.pp_dieu_tri đối với bệnh nhân khám ngoại trú/toa xuất viện_**
- ✨: Hỗ trợ cấu trúc thêm option chọn XML01.PP_DIEU_TRI đối với Ngoại trú, Toa xuất viện
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/621
## [v.3.24.0822.0]()
- 🐛: **Chỉnh lỗi**: **_XML3 lấy sai NGAY_TH_YL không đúng với mô tả_**
- 🐛: XML03.NGAY_TH_YL: Lấy sai không theo mô tả ![](https://i.imgur.com/UTn9D9A.png)
- ![](https://i.imgur.com/PzBVwa3.png) ![](https://i.imgur.com/sDIGlrU.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/617
## [v.3.24.0821.6]()
- 🐛: **Chỉnh lỗi**: **_XML3 lấy sai NGAY_TH_YL không đúng với mô tả_**
- 🐛: XML03.NGAY_TH_YL: Lấy sai không theo mô tả ![](https://i.imgur.com/UTn9D9A.png)
- ![](https://i.imgur.com/PzBVwa3.png) ![](https://i.imgur.com/sDIGlrU.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/617
## [v.3.24.0821.2]()
- 🐛: **Chỉnh lỗi**: **_XML3 lấy sai NGAY_TH_YL không đúng với mô tả_**
- 🐛: XML03.NGAY_TH_YL: Lấy sai không theo mô tả ![](https://i.imgur.com/UTn9D9A.png)
- ![](https://i.imgur.com/PzBVwa3.png) ![](https://i.imgur.com/sDIGlrU.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/617
## [v.3.24.0821.1]()
- 🐛: **Chỉnh lỗi**: **_Lỗi - XUẤT XML 4750 THIẾU T_BNTT CỦA VTYT_**
- ✨: Đối với VTYT (không thuộc stent): TYLE_TT_DV=100, TYLE_TT_BH =100
- XML03.DON_GIA_BH = nếu pshdxn.giabhyt > 0 lấy pshdxn.giabhyt ngược lại pshdxn.dongia
- XML03.DON_GIA_BV = pshdxn.dongia, 
- Trường hợp sử dụng chức năng (option) DON_GIA_BV là DON_GIA_BH (XML03.DON_GIA_BV = XML03.DON_GIA_BH)
- ✨: Đối với THUỐC (không thuộc stent): TYLE_TT_DV=100, TYLE_TT_BH =100
- XML02.DON_GIA = nếu pshdxn.giabhyt > 0 lấy pshdxn.giabhyt ngược lại pshdxn.dongia, 
- ![](https://i.imgur.com/Rc8shLM.png) ![](https://i.imgur.com/wVMqN63.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/90
## [v.3.24.0821.0]()
- 🐛: **Chỉnh lỗi**: **_Yêu cầu hỗ trợ thay đổi cách ghi nhận dữ liệu bệnh nhân nhận thuốc lao theo hẹn khi đăng ký KCB và điều kiện lấy mã đối tượng KCB 7.1 (Lĩnh thuốc không khám bệnh)_**
- 🐛: XML01.MA_DOITUONG_KCB lấy sai điều kiện 7.1 ![](https://i.imgur.com/hHMPD3g.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/105
## [v.3.24.0819.1]()
- 🐛: **Chỉnh lỗi**: **_XML3 MA_BAC_SI lấy thông tin sai mô tả (đang lấy bác sĩ chỉ định + bác sĩ trả kết quả)_**
- 🐛: XML03.MA_BAC_SI: sai khi các dịch vụ có thực hiện PT,TT ![](https://i.imgur.com/yUFHB8P.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/609
## [v.3.24.0819.0]()
- 🐛: **Chỉnh lỗi**: **_Lỗi XML3 không lấy được NGAY_TH_YL khi mã nhóm CLS CĐHA = 18 (thủ thuật)_**
- 🐛: XML03.NGAY_TH_YL: lấy sai khi nhóm 8,18 ![](https://i.imgur.com/eRP7uXy.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/607
## [v.3.24.0816.1]()
- 🐛: **Chỉnh lỗi**: **_LỖI KHI GỬI XML4750 LÊN CỔNG VÀ XUẤT XML4750_** ![](https://i.imgur.com/EnsOczn.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/110
## [v.3.24.0816.0]()
- 🐛: **Chỉnh lỗi**: **_LỖI KHI GỬI XML4750 LÊN CỔNG VÀ XUẤT XML4750_** ![](https://i.imgur.com/EnsOczn.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/110
## [v.3.24.0814.2]()
- ✨: **Thực hiện**: **_💼 Thực hiện Xuất XML4750 theo Mô tả XML130 - Bổ sung QĐ 4750 ⏳Dự kiến :  2024-08-19_**
- ✨: **XML01.MA_DOITUONG_KCB** theo mô tả
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/109
## [v.3.24.0814.1]()
- ✨: **Thực hiện**: **_Yêu cầu - BỔ SUNG MÔ TẢ XML3.NGAY_YL_**
- ✨: Xử lý lại **XML03.NGAY_YL** đối với PT,TT (lấy theo thông tin chỉ định ngaykcb, nguyên nhân là theo mô tả cũ không còn phù hợp với 4750 **Vinh - Mo ta cot [dien_bien] [hoi_chan] va [phau_thuat] XML5 - 20220602.3.pdf**)
- ![](https://i.imgur.com/eYE022S.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/599

## [v.3.24.0814.0]()
- ✨: **Thực hiện**: **_Kiểm tra XML4.ma_bs_doc_kq với mô tả_**
- ✨: XML03.MA_BAC_SI theo mô tả [xml130.bang3](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang03%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md):  ![](https://i.imgur.com/JG02sol.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/92
## [v.3.24.0812.0]()
- ✨: **Thực hiện**: **_Kiểm tra XML4.ma_bs_doc_kq với mô tả_**
- ✨:Mô tả [Table xml130.bang04](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang04%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md)
![](https://i.imgur.com/2WxiokN.png)![](https://i.imgur.com/ImBp80Q.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/591
## [v.3.24.0811.2]()
- 🐛: **Chỉnh lỗi**: **_Lỗi - NHẬP GIÁ TRỊ TÌM KIẾM NHÂN VIÊN PHÁT SINH LỖI_**![](https://i.imgur.com/BNh3KHy.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/86

## [v.3.24.0811.1]()
- ☑: **Chỉnh lỗi**: **_Chức năng xuất xml 4750 bệnh nhân có 1 đợt điều trị hiển thị nhiều lần trong danh sách xuất xml_** ![](https://i.imgur.com/OYiBhXF.png)
- 🐛: https://github.com/dh-hos/To_Lap_Trinh/issues/582

## [v.3.24.0811.0]()
- ✨: Yêu cầu - Hỗ trợ hàm kiểm tra thông tuyến theo Công văn 1923/BHXH-CNTT ngày 20/06/2024
- ✨: Mô tả thực hiện [Ham API tra cuu TT - theo CV 1923-BHXHVN.md
](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Ham%20API%20tra%20cuu%20TT%20-%20theo%20CV%201923-BHXHVN.md)
- ✨:  + Chuyển hàm sử dụng thông tuyến KQNhanLichSuKCB2024 (Không theo cấu hình trên Admin)
- ✨:  + Sử dụng tài khoản kiểm tra theo tài khoản đăng nhập, điều kiện cụ thể để tài khoản có thể sử dụng tra cứu là có tài khoản BHXH cung cấp khác rỗng, có họ lót và Số CCCD
- ✨:  + Trường hợp tài khoản đăng nhập không hợp lệ, sẽ tìm theo tài khoản được cấu hình theo khoa, và theo bệnh viện trên Danh mục Nhân viên
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/565
## [v.3.24.0810.2]()
- 🐛: Lỗi - Cấn trừ thuốc trả sai khi xuất 4750 ![](https://i.imgur.com/lKwPbZQ.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/87
## [v.3.24.0810.1]()
- 🐛: Yêu cầu - Cập nhật kết quả XN cho ngày cũ tại form khám HIV ![](https://i.imgur.com/hi4V2AF.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/547
## [v.3.24.0810.0]()
- ✨: **XML01.LY_DO_VNT** (Chưa lấy theo [Mô tả XML130 - Bổ sung QĐ 4750](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750.md))  ![](https://i.imgur.com/upcYGv2.png)
- 🐛: **XML4750 tính sai tiền VTYT** ![](https://i.imgur.com/ijvw0o4.png)
- 🐛: **Lỗi - Cấn trừ thuốc trả bị sai khi xuất XML 4750** ![](https://i.imgur.com/7SqaBx3.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/589
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/88
## [v.3.24.0806.0]()
- 🐛: Lỗi - Admin hiển thị thông báo cập nhật nhiều lần
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/85
## [v.3.24.0805.3]()
- ✨: XML03 sai tỉ lệ thanh toán đối với nhóm MÁU
- ✨: XML4570 tính sai tiền BHTT đối với bệnh có nhập chứng nhận miễn.
![](https://i.imgur.com/nnESRUF.png) ![](https://i.imgur.com/A5NdfZb.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/572
## [v.3.24.0805.2]()
![](https://i.imgur.com/qjQ6yIZ.png) ![](https://i.imgur.com/3QI9yH0.png)![](https://i.imgur.com/ALs17dj.png)
- ✨: Thêm chức năng hỗ trợ XML03_DON_GIA_BV_IS_DON_GIA_BH
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/574
## [v.3.24.0805.1]()
![](https://i.imgur.com/qjQ6yIZ.png) ![](https://i.imgur.com/3QI9yH0.png)![](https://i.imgur.com/ALs17dj.png)
- ✨: Thêm chức năng hỗ trợ XML03_DON_GIA_BV_IS_DON_GIA_BH
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/238
## [v.3.24.0805.0]()
![](https://i.imgur.com/qjQ6yIZ.png) ![](https://i.imgur.com/3QI9yH0.png)![](https://i.imgur.com/ALs17dj.png)
- ✨: Thêm chức năng hỗ trợ XML03_DON_GIA_BV_IS_DON_GIA_BH
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/238
## [v.3.24.0803.3]()
- ✨: Yêu cầu - Gửi HIV không theo cấu hình các bảng tại module Admin
- ✨: Khi gửi HIV sẽ không theo cấu hình các bảng XML trên Admin
- ![](https://i.imgur.com/PKoQquT.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/556
## [v.3.24.0803.2]()
- 🐛: Xử lý mất trạng thái form khi thông báo gửi hồ sơ thành công
## [v.3.24.0803.1]()
- ✨: Thực hiện theo Mô tả Kiểm tra thời gian kết quả HA/CN/TT/PT
- ![](https://i.imgur.com/VeIVeHQ.png)
![](https://i.imgur.com/JnFa8mo.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/63
## [v.3.24.0803.0]()
- ✨: XML03.ngay_th_yl thực hiện theo mô tả 
- ![](https://i.imgur.com/0wf6uwP.png)
- 🐛: XML4570 tính sai tiền BHTT đối với bệnh có nhập chứng nhận miễn (Thiếu điều kiện cùng ngày miễn chi trả), => Lớn hơn hoặc bằng NGAY_MIEN_CT sẽ tính MUC_HUONG = 100_
- ![](https://i.imgur.com/2i6gwnJ.png) https://i.imgur.com/96n4aGP.png
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/365
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/572
## [v.3.24.0802.1]()
- ✨: Yêu cầu - Gủi thông tin XML11.MAU_SO![](https://i.imgur.com/9XcL3Lg.png)
- ![](https://i.imgur.com/KBSKGbL.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/564
## [v.3.24.0802.0]()
- ✨: XML01.PP_DIEU_TRI
![](https://i.imgur.com/Cmw0zVb.png)
- ✨: XML13.TOMTAT_KQ,PP_DIEUTRI,PP_DIEU_TRI
![](https://i.imgur.com/y71CGOa.png)![](https://i.imgur.com/MQPZNzG.png)![](https://i.imgur.com/FUO7JOn.png)
- 🐛: XML03.DON_GIA_BV (trường hợp XML03.DON_GIA_BV < XML03.DON_GIA_BH, xử lý XML03.DON_GIA_BV = XML03.DON_GIA_BH) để phù hợp với công thức T_BNTT = THANH_TIEN_BV - THANH_TIEN_BH
- 🐛: Tiền T_BNTT < 0 trường hợp CLS có giá BH lớn hơn giá Dịch vụ, dân
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/365
## [v.3.24.0801.1]()
- 🐛: XML01.PP_DIEU_TRI (trường hợp không thuộc Bệnh án sẽ lấy [`Ngoại khoa`])
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/82
## [v.3.24.0801.0]()
- 🐛: Fix Lỗi - Admin Khi thêm nhân viên mới ![](https://i.imgur.com/YTOP4MY.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/83
## [v.3.24.0731.1]()
- ✨: 💼 Thực hiện - Admin Thêm chức năng cấu hình thời gian đối với Loại CLS, CLS
- ![](https://i.imgur.com/7jwGMJE.png)
- ![](https://i.imgur.com/cCeOriM.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/529
## [v.3.24.0731.0]()
- ✨: 💼 Thực hiện - Admin Thêm chức năng cấu hình thời gian đối với Loại CLS, CLS
- ![](https://i.imgur.com/7jwGMJE.png)
- ![](https://i.imgur.com/cCeOriM.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/529
## [v.3.24.0730.1]()
- ✨: Mặc định mở rộng độ dài các tiêu đề của Grid XML (để header không bị khuất chữ)
- 🐛: Fix: XML0 trống MA_DICH_VU/TEN_THUOC/MA_VAT_TU
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/554
## [v.3.24.0730.0]()
- 🐛: XML4750 không load được bệnh nhân bệnh án ngoại trú thanh toán ngày ![](https://i.imgur.com/5bZ030c.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/553
## [v.3.24.0729.1]()
- 🐛: Fix XML01.MA_DKBD thiếu thông tin thẻ 2 (trường hợp 2 thẻ) ![](https://i.imgur.com/r2qv7Hp.png)
## [v.3.24.0729.0]()
- 🐛: Fix XML 4750 tính sai tiền BHTT và BNCCT
- ![](https://i.imgur.com/MID08ug.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/549
## [v.3.24.0726.5]()
- 🐛: Fix: Admin - Chức năng xuất xml 4750 vẫn xuất bệnh nhân chưa ra viện (loại bệnh án lấy hồ sơ ra viện `ravien!=0`, ngoại trú lấy hồ sơ đã in 01`dain!=0`) 
- ![](https://i.imgur.com/nivASCj.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/535
## [v.3.24.0726.4]()
- 🐛: Fix: Lỗi - Mô tả sai mã đối tượng KCB với trường hợp bệnh nhân tuyến xã nhập viện BV tuyến tỉnh không có giấy chuyển tuyến
- ![](https://i.imgur.com/oieNqHi.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/80
## [v.3.24.0726.3]()
- ✨: Thực hiện mô tả, thực hiện bổ sung chức năng chọn nhân viên thực hiện cho XN, HA, cập nhật hỗ trợ gởi XML4750
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/522
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/541
## [v.3.24.0726.2]()
- ✨: Bổ sung XML10 theo mô tả [Table xml130.bang10 - [Phụ lục - Mô tả XML130 - Bổ sung QĐ 4750].md](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang10%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md)
## [v.3.24.0726.1]()
- 🐛: Lỗi - XML13 lấy thông tin phiếu chuyển viện đã xóa ![](https://i.imgur.com/kUZKHAU.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/543
## [v.3.24.0726.0]()
- ✨: Bổ sung checkbox [Được thực hiện CLS], ghi nhận những nhân viên được phép thực hiện CLS
- ![](https://i.imgur.com/UU9IDd3.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/538
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/522
## [v.3.24.0725.6]()
- 🐛: Fix: XML3 tính sai tiền VTYT có trần thanh toán 
- ![](https://i.imgur.com/GPtjfds.png)
- 🐛: Fix: XML11.PP_DIEUTRI (ngoại trú lấy sai)
- ![](https://i.imgur.com/JYVkFhi.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/542
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/199
## [v.3.24.0725.5]()
- 🐛: XML11.MA_BS: lấy thông tin số BHXH trưởng khoa
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/199
## [v.3.24.0725.4]()
- 🐛: Fix: Lỗi - Không lấy được Người Thực Hiện XML3 khi đã có kết quả Siêu âm ![](https://i.imgur.com/nvtMSpW.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/81
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0725.3]()
- 🐛: Fix: Admin - Chức năng xuất xml 4750 vẫn xuất bệnh nhân chưa ra viện (loại bệnh án lấy hồ sơ ra viện `ravien!=0`, ngoại trú lấy hồ sơ đã in 01`dain!=0`)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/535
## [v.3.24.0725.2]()
- ✨: Yêu cầu - Bổ sung bảng XML 11 (GIẤY CHỨNG NHẬN NGHỈ HƯỞNG BHXH)
- 🐛: Fix lỗi XML11.MA_BS (lấy thiếu thông tin) ![](https://i.imgur.com/fu0LPdU.png)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/199
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0725.1]()

- 🐛: Fix lỗi mở form xuất XML4750
## [v.3.24.0725.0]()
- ✨: Yêu cầu - Hỗ trợ chuyển ngày bắt đầu/kết thúc xử trí ![](https://i.imgur.com/xm7Ytzf.png) ![](https://i.imgur.com/2ux7f8s.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/532
## [v.3.24.0724.4]()
- 🐛: XML2 4750 tính sai tiền BNTT đối với thuốc thanh toán theo tỷ lệ
![](https://i.imgur.com/YIyxoTO.png) ![](https://i.imgur.com/T3b3oIx.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/530
## [v.3.24.0724.3]()
- ✨: Yêu cầu - Hỗ trợ xuất XML6 đối với 4750 ![](https://i.imgur.com/2jzHlO9.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/531
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0724.2]()
- ✨: Yêu cầu - Hoàn thiện XML9 ![](https://i.imgur.com/44d0lsC.png)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/198
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0724.1]()
- ✨: Yêu cầu - Bổ sung bảng XML 11 (GIẤY CHỨNG NHẬN NGHỈ HƯỞNG BHXH) ![](https://i.imgur.com/1pHSAuu.png)
- ✨: Yêu cầu - Mô tả và thực hiện hỗ trợ gởi bệnh nhân BANT thanh toán ngày XML1.ma_loai_kcb ![](https://i.imgur.com/HMSzYM7.png)
- 🐛: Fix lỗi: XML3 chưa lấy Nguoi_thuc_hien cho Mã Nhóm 2 ![](https://i.imgur.com/IeSaP0d.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/83
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/199
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/519
## [v.3.24.0724.0]()
- ✨: Yêu cầu - Bổ sung bảng XML 11 (GIẤY CHỨNG NHẬN NGHỈ HƯỞNG BHXH) ![](https://i.imgur.com/1pHSAuu.png)
- ✨: Yêu cầu - Mô tả và thực hiện hỗ trợ gởi bệnh nhân BANT thanh toán ngày XML1.ma_loai_kcb ![](https://i.imgur.com/HMSzYM7.png)
- 🐛: Fix lỗi: XML3 chưa lấy Nguoi_thuc_hien cho Mã Nhóm 2 ![](https://i.imgur.com/IeSaP0d.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/83
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/199
## [v.3.24.0723.0]()
- ✨: CheckIn lấy thẻ theo mô tả
- ![](https://i.imgur.com/HbhbDM2.png)
- ✨: Thực hiện: Yêu cầu - Hoàn thiện XML9 (đang chờ mô tả thêm)
- ![](https://i.imgur.com/jaMoqtP.png)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/198
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/514
## [v.3.24.0722.2]()
- 🐛: xml.LOAI_DTRI_LAO
## [v.3.24.0722.1]()
- 🐛: Fix lỗi xml.LOAI_DTRI_LAO
## [v.3.24.0722.0]()
- ✨: Bổ sung chức năng xem XML4750 đối với các bệnh viện triển khai HIV
- 🐛: Fix lỗi HIV 
## [v.3.24.0721.1]()
- ✨: Xuất XML HIV
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/511
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/512
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/497
## [v.3.24.0721.0]()
- ✨: Xử lý XML01.MA_NOI_DI theo [Table xml130.bang01](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang01%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/509
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0719.1]()
- 🐛: Fix thiếu XML01.CAN_NANG: trường hợp BANT
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0719.0]()
- 🐛: 
Lỗi - Lấy sai mã đối tượng khám chữa bệnh XML1 (MA_DOITUONG_KCB) với bệnh nhân nhập viện trái tuyến tại BV tuyến tỉnh
![](https://i.imgur.com/QyFqKHB.png)
- 🐛: Xử lý đơn giá thuốc (DON_GIA, DON_GIA_BV, DON_GIA_BH), vtyt lấy giabhyt khi giabhyt>0 (không thuộc thanh toán Stent)
- ![](https://i.imgur.com/kKOpa7P.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/78
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0718.0]()
- ✨: Bổ sung chức năng cấu hình sử dụng chức năng thông tuyến theo 1923/BHXH-CNTT
- ![](https://i.imgur.com/4WUjZHp.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/450
## [v.3.24.0716.2]()
﻿- ✨: Bổ sung form Danh mục chứng thư số
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/446
![](https://i.imgur.com/hrBhKo2.png)
## [v.3.24.0716.1]()
﻿- ✨: Bổ sung form Danh mục chứng thư số
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/446
![](https://i.imgur.com/hrBhKo2.png)
<<<<<<< HEAD
## [v.3.24.0716.0]()
﻿- ✨: Bổ sung form Danh mục chứng thư số
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/446
![](https://i.imgur.com/hrBhKo2.png)
=======
## [v.3.24.0716.1]()
- 🐛: FIX Lỗi xuất, gửi XML4750 khi bệnh nhân có sử dụng CLS có phương pháp vô cảm
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/491
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0716.0]()
- ✨: Bổ sung XML13
- ![](https://i.imgur.com/d57JB4C.png)
- 🐛: XML01.CHAN_DOAN_VAO (không lấy được khi phòng đầu tiên chưa khám)
- ![](https://i.imgur.com/eLOaYJu.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/494
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/77
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/489
>>>>>>> 12353681bff8ff606193e7ef15c9c8eda9abe9dd
## [v.3.24.0714.2]()
- ✨: Test cập nhật
## [v.3.24.0714.0]()
- 🐛: Fix: Admin xuất xml tính sai tiền BHTT 
- ![](https://i.imgur.com/E349XGv.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/484
## [v.3.24.0713.4]()
- ✨: Test cập nhật
## [v.3.24.0713.3]()
- ✨: Test cập nhật
- ✨: XML01.MA_BENH_KT theo tham số ma_benh_kt.soluong [Mô tả XML130 - Bổ sung QĐ 4750](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750.md)
- ✨: XML01 và Checkin: MA_DOITUONG_KCB [Table xml130.bang01](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang01%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md#user-content-fnref-2024-07-12-02-1ec9d201cbe3c6fd4b2a050757091faf)
- 🐛: XML01.NGUOI_THUC_HIEN, NGAY_TH_YL đối với Loại CLS (TL: Test tâm lý)
![](https://i.imgur.com/CfraF7I.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/479
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/62
## [v.3.24.0711.2]()
- ✨: Thực hiện gởi tối đa 12 ICD, XML01.MA_BENH_KT giới hạn 12 mã bệnh (cách nhau bằng dấu ;)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/476
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0711.1]()
- ✨: XML4750: tự động thêm CDDATA đối với những trường dữ liệu có ký tự đặc biệt
- 🐛: Fix: XML4750 bảng 2 tính sai số tiền T_BHTT ![](https://i.imgur.com/OBWJla8.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/477
## [v.3.24.0711.0]()
- ✨: XML08.TOMTAT_KQ, QT_BENHLY:  theo mô tả [Table xml130.bang08 - [Phụ lục - Mô tả XML130 - Bổ sung QĐ 4750].md](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang08%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md#user-content-fnref-2024-07-11-01-42b2e71eadf2a2eaa04e5b87f8fa0048)
- ✨: Yêu cầu - BANT ĐỢT LƯU THÔNG TIN THEO MÔ TẢ 130 CHO XML8.QT_BENHLY VÀ XML8.TOMTAT_KQ
- 🐛: Lỗi XML7 CHAN_DOAN_RV khi chẩn đoán có ký tự đặc biệt ![](https://i.imgur.com/7BUJG1l.png)
- ☑: `https://github.com/dh-hos/To_Lap_Trinh/issues/472
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/471
## [v.3.24.0710.3]()
- ✨: XML01.CHAN_DOAN_VAO, KET_QUA_DTRI theo mô tả [xml130.bang1](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang00checkin%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md)
- ✨: Thực hiện Yêu cầu bỏ mặc định CAN_NANG = 0.01
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/469
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0710.2]()
- 🐛: Fix - DANH MỤC ĐỊA PHƯƠNG 4750 TÊN VIẾT TẮT BỊ SAI #54 
- Trường hợp viettat lấy sai tenhuyen
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/54
## [v.3.24.0710.1]()
- 🐛: Fix lỗi - DANH MỤC ĐỊA PHƯƠNG 4750 TÊN VIẾT TẮT BỊ SAI
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/54
![](https://i.imgur.com/yzMsYaF.png)
## [v.3.24.0710.0]()
- 🐛: Fix: Lỗi - XML 4750 không cấn trừ thuốc đã trả
![](https://i.imgur.com/o4W2XtA.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/75
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0709.4]()
- ✨: THỰC HIỆN CHỦ ĐỀ: MÔ TẢ THỰC CẬN LÂM SÀNG THĂM DÒ CHỨC NĂNG (KHO = 'CN')
- Xử lý thêm Không được xóa các loại CLS mặc định như sau (bổ sung thêm): 
![](https://i.imgur.com/UpIdIem.png)
- Cho phép thêm loại thuộc kho CN
![](https://i.imgur.com/M61PKfh.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/460
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/309
## [v.3.24.0709.3]()
- 🐛: Fix Lỗi - Bị mất mã giường khi thêm mã giường thủ công
- ![](https://i.imgur.com/rP5mxvw.png)
- 🐛: XML01.NGAY_RA, NGAY_TTOAN, khi null (tránh lỗi xml)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/74
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0709.2]()
- 🐛: Fix Lỗi - Bị mất mã giường khi thêm mã giường thủ công
- ![](https://i.imgur.com/rP5mxvw.png)
- 🐛: XML01.NGAY_RA, NGAY_TTOAN = '', khi null (tránh lỗi xml)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0709.1]()
- 🐛: Fix Lỗi - Bị mất mã giường khi thêm mã giường thủ công
- ![](https://i.imgur.com/rP5mxvw.png)
- 🐛: XML01.NGAY_RA, NGAY_TTOAN, khi null (tránh lỗi xml)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/74
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0709.0]()
- ✨: XML08.NGAY_VAO, CHAN_DOAN_VAO theo mô tả [Mô tả XML130 - Bổ sung QĐ 4750.md](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750.md)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0708.2]()
- ✨: Thực hiện: Yêu cầu thực hiện 4750 - Bổ sung dử liệu XML8
- 🐛: XML08.CHAN_DOAN_VAO, XML08.TOMTAT_KQ , XML08.QT_BENHLY
- ![](https://i.imgur.com/vWcHAaY.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/451
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0708.1]()
- ✨: Form Xuất 4750 định dạng số các cột thành tiền
- 🐛: XML03.NGAY_KQ, XML04.NGAY_KQ (các xét nghiệm sinh thiết không lấy được)
- 🐛: Fix Lỗi - Thông tin của danh mục nhân viên bị khuất.
- ![](https://i.imgur.com/2xRPvpo.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/72
## [v.3.24.0708.0]()
- ✨: Kiểm tra Định dạng CCCD phải có 9,12 ký tự số hoặc hộ chiếu 8 ký tự bắt đầu là chữ in hoa và 7 ký tự số ở sau, khi lưu (kiểm tra khi số CCCD khác rỗng)
- ![](https://i.imgur.com/raV9QXV.png)
- ✨: Thực hiện theo mô tả [Ham API tra cuu TT - theo CV 1923-BHXHVN.md](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Ham%20API%20tra%20cuu%20TT%20-%20theo%20CV%201923-BHXHVN.md)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/450
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0707.1]()
- ✨: Thêm form xuất và xem XML4750
- ![](https://i.imgur.com/r5vq1m1.png)
- 🐛: XML03.NGAY_TH_YL (lấy sai thông tin so với chidinhcls.giolaymau)
- 🐛: XML04 loại bỏ những dịch vụ không nằm trong XML03 (trường hợp thực hiện đối với các chi phí không thuộc BHYT)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0707.0]()
- ✨: XML14.NGAY_HEN_KL xử lý Giờ phút mặc định (08:00) khi dữ liệu không ghi nhận giờ phút hẹn tái khám
- ![](https://i.imgur.com/ZU2cE6N.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/48
## [v.3.24.0706.1]()
- ✨: Bổ sung các thông tin trên XML14
![](https://i.imgur.com/ArYFIEb.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0706.0]()
- ✨: Bổ sung các thông tin trên XML14
![](https://i.imgur.com/ArYFIEb.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0705.2]()
- ✨: Thực hiện Yêu cầu hỗ trợ kiểm tra thông tuyến theo công văn 1923/BHXH-CNTT
- ✨: Bổ sung chức năng nhập Thông tin API - BHXH (tài khoản, mật khẩu, số cccd, ngày sinh) trên danh mục nhân viên
- Check Theo đơn vị: Tất cả tài khoản trong cùng đơn vị (madv) sẽ được phép sử dụng tài khoản này khi thực hiện kiểm tra thông tuyến, khi chưa được cấu hình tài khoản và mật khẩu trên cổng giám định.
- Check Cả bệnh viện: Tất cả tài khoản trong danh mục nhân viên sẽ được phép sử dụng tài khoản này khi thực hiện kiểm tra thông tuyến, khi chưa được cấu hình tài khoản và mật khẩu trên cổng giám định.
- ![](https://i.imgur.com/i7MRcj1.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/450
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0705.1]()
- 🐛: Fix Lỗi - Lấy sai mã loại Đối tượng Khám chưa bệnh XML01.MA_DOITUONG_KCB
- ![](https://i.imgur.com/laQIFQx.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/71
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0705.0]()

- 🐛: XML03.NGUOI_THUC_HIEN (Nguyên nhân không lấy được do tham số congdulieuBHXH.guitudongxml45=0, xử lý không quan tâm tới tham số này đối với 4750)
- ![](https://i.imgur.com/2U7Do7e.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/448
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0704.2]()
- ✨: Thực hiện Xuất XML cấn trừ thuốc trả Theo mô tả - [MÔ TẢ QUY TRÌNH TRẢ THUỐC/VTYT NGƯỜI BỆNH ĐIỀU TRỊ NỘI TRÚ](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/M%C3%B4%20t%E1%BA%A3%20Quy%20tr%C3%ACnh%20tr%E1%BA%A3%20thu%E1%BB%91c-VTYT%20b%E1%BB%87nh%20%C3%A1n%20n%E1%BB%99i%20tr%C3%BA.md) 
- Dựa vào sohdx để cấn trừ thuốc trả, nếu không có sohdx việc cấn trừ vẫn giữ trước không thay đổi.
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/42
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0704.1]()
- ✨: Bổ sung XML03.MA_XANG_DAU (ưu tiên theo thứ tự mã xăng dầu ở dmcls => tham số hệ thống ma_xang_dau)
![](https://i.imgur.com/JA1YD9D.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/445
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0704.0]()
- ✨: Bổ sung chức năng nhập mã xăng dầu theo danh mục cận lâm sàng (theo kho CV, CV2)
![](https://i.imgur.com/HLLCltb.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/445
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- 📗: ma_xang_dau trên current.dmcls
## [v.3.24.0703.3]()
- 🐛: XML06.LOAI_DTRI_LAO: Lấy fhi_dgxutri.maxutri join qua bảng fhi_dmxutri để lấy giá trị cột ma4750 để gửi.
- ![](https://i.imgur.com/Np7bfnQ.png) ![](https://i.imgur.com/bHw9r5M.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/70
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/70#issuecomment-2206058751
## [v.3.24.0703.2]()
- ✨: Bổ sung XML7.MA_DINH_CHI_THAI giá trị mặc định "0"
- ![](https://i.imgur.com/qAtp6oL.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/441
## [v.3.24.0703.1]()
- 🐛: XML06.LOAI_DTRI_LAO (lấy maxutri để link dmchon lấy giá trị 4750)
- ![](https://i.imgur.com/rj6jaP3.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/70
## [v.3.24.0703.0]()
- ✨: Bổ sung XML06.MA_BENH_KT, NGAY_TAI_KHAM 
- ![](https://i.imgur.com/OrQHdbw.png)
- ![](https://i.imgur.com/KQgls8j.png)
![](https://i.imgur.com/oWX4uHQ.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/442
## [v.3.24.0702.2]()
- ✨: Bổ sung điều kiện để xuất các XML, theo thứ tự ưu tiên theo option Cấu hình gửi tự động => Điều kiện xuất theo mô tả [Mô tả QĐ 4750](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750.md)
- XML06: Dữ liệu phải có trong fhi.qtdieutri (phải có khám ARV)
- XML09, XML10, XML11, XML12, XML13, XML14, XML15
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/37
## [v.3.24.0702.1]()
- ✨: Thực hiện Yêu cầu - Thực hiện xuất xml lấy thông tin mã máy theo mô tả Table xml130.bang03
- 🐛: XML03.MA_MAY theo phiếu PT, TT
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/36
## [v.3.24.0702.0]()
- ✨: Bổ sung Tại form quản lý [Danh mục mã máy thực hiện CLS], bổ sung thêm giá trị cho [Kho CLS] là TT (thủ thuật) và PT (phẫu thuật)
![](https://i.imgur.com/TA70SNR.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/33
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0701.4]()
- ✨: XML03.PP_VO_CAM lấy mặc định 4, khi rỗng
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/439
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0701.3]()
- 🐛: XML07.TEN_BS ưu tiên lấy họ lót không chức danh trước, nếu rỗng thì mới lấy họ lót bình thường
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/30
## [v.3.24.0701.2]()
- ✨: Bổ sung chức năng nhập họ lót không chức danh trên danh mục nhân viên
![](https://i.imgur.com/MtRm1eS.png) 
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/30
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0701.1]()
- 🐛: Fix thiếu XML04.MA_BS_DOC_KQ
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0701.0]()
- 🐛: Sai MA_DOITUONG_KCB bệnh nhân thông tuyến, trái tuyến được hưởng cùng tuyến
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/438
## [v.3.24.0630.1]()
- ✨: Bổ sung theo mô tả [Table xml130.bang07 - [Phụ lục - Mô tả XML130 - Bổ sung QĐ 4750].md](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang07%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md#user-content-fnref-2024-06-30-02-662b588869adb0bca8862f41127d9b1a)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0630.0]()

- 🐛: Lỗi tính sai số tiền T_VTYT XML1: phần mềm tính tiền CLS xét nghiệm vào tiền vật tư
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/433#issuecomment-2198239795
## [v.3.24.0629.3]()
- 🐛: XML03.NGAY_YL theo mô tả [Table xml130.bang03 - [Phụ lục - Mô tả XML130 - Bổ sung QĐ 4750].md](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang03%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0629.2]()
- 🐛: Fix stent2 (dmthuoc.stent=2): 
- xml03.DON_GIA_BH = dmthuoc_t_trantt.toRound(3);
- xml03.TYLE_TT_DV = 100.toVString();
- xml03.TYLE_TT_BH = xml4210.dmthuoc_tyle_tt.toVString();
- xml01.T_VTYT
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/425
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0629.1]()
- 🐛: Fix stent2 (dmthuoc.stent=2): 
- xml4750.DON_GIA_BH = dmthuoc_t_trantt.toRound(3);
- xml4750.TYLE_TT_DV = 100.toVString();
- xml4750.TYLE_TT_BH = xml4210.dmthuoc_tyle_tt.toVString();
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/425
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0629.0]()
- 🐛: Fix lỗi CLS con không load được dữ liệu đơn vị đo lên phần mềm
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/427
## [v.3.24.0628.9]()
- ✨: Hỗ trợ chức năng Import ICD 9 từ excel  COD thực hiện.
- ✨: Hỗ trợ script áp mã ICD 9 cho danh mục cận lâm sàng theo mã tương đương 
COD thực hiện.
![](https://i.imgur.com/3dMDbUf.png)
![](https://i.imgur.com/pnX7oj1.png)
![](https://i.imgur.com/yJQnkFQ.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/16
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0628.8]()
- 🐛: Sai số tỷ lệ thanh toán dịch vụ phải là số nguyên dương, 
- 🐛: SO_LUONG, DON_GIA_BV, DON_GIA_BH => toRound(3);
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/426
## [v.3.24.0628.7]()
- 🐛: XML1 và XML3 sai số tiền bệnh nhân có công khám lần 2. số tiền bị nhân lên nhiều lần
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/426
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0628.6]()
- 🐛: Lỗi sai số tiền T_BNTT XML1 và XML3 khi bệnh nhân có chỉ định CLS DV có chênh lệch giá DVKT (hiện tại phần mềm chưa tính tiền chênh lệch vào T_BNTT )
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/424
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0628.5]()
- ✨: Một số thông tin mặc định có thể sử dụng khi dữ liệu trống:
        Mã quốc tịch: 000 <MA_QUOCTICH>000</MA_QUOCTICH> -> Việt Nam
        Mã dân tộc: 56 <MA_DANTOC>56</MA_DANTOC> -> Không xác định
        Mã nghề nghiệp: 00000 <MA_NGHE_NGHIEP>00000</MA_NGHE_NGHIEP> -> Không xác định
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/423
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0628.4]()
- 🐛: XML02.TYLE_TT_BH, TYLE_TT_DV, DON_GIA_BV,DON_GIA_BH,THANH_TIEN_BV,THANH_TIEN_BH
- 🐛: Công khám lần 2
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0628.3]()
- 🐛: XML02.TT_THAU (trường hợp vật tư chưa lấy theo 4750)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0628.2]()
- 🐛: XML01.ma_loai_kcb, so_ngay_dtri theo mô tả mới [Table xml130.bang01.md](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang01%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md#user-content-fn-2024-06-28-01-8d3a94d0508a2e3ff81e19212fc59a54)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0628.1]()
- ✨: Test NASs
## [v.3.24.0628.0]()
- 🐛: XML01.SO_NGAY_DTRI (MA_LOAI_KCB=05, lấy MAX ngayuong trong current.chungtu)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0627.6]()
- 🐛: Fix lỗi phải chọn lại thư mục khi xuất nhiều hồ sơ
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0627.5]()
- 🐛: Fix: XML01.MA_LOAI_KCB, XML01.SO_NGAY_DTRI
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0627.4]()
- 🐛: XML1: Trùng mã icd9 MA_PTTT_QT -> Cần phải lọc trùng ICD9
- 🐛: XML3: Không lấy được mã ICD9 MA_PTTT_QT
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20#issuecomment-2193919323
## [v.3.24.0627.3]()
- 🐛: Fix lỗi ma_giuong_bak_ trong bảng chidinhcls
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/403
## [v.3.24.0627.2]()
- 🐛: Fix lỗi phát sinh khi add danh mục địa phương 4750 bằng excel - phiên bản postgres 9.4
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
<<<<<<< HEAD
## [v.3.24.0627.1]()
- 🐛: Fix lỗi phát sinh khi add danh mục địa phương 4750 bằng excel - phiên bản postgres 9.4
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0627.0]()
- 🐛: Fix lỗi phát sinh khi add danh mục địa phương 4750 bằng excel - phiên bản postgres 9.4
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
<<<<<<< HEAD
## [v.3.24.0613.1]()
- 🐛: Fix lỗi mất cột 4750 ở các danh mục (dân tộc, nghề nghiệp, tai nạn, phương pháp vô cảm)
=======
=======
## [v.3.24.0627.0]()
- ✨: Thử NAS
## [v.3.24.0626.3]()
- ✨: Test KS
## [v.3.24.0626.2]()

- 🐛: Fix lỗi xuất XML4750 ![](https://i.imgur.com/IR465Cc.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
>>>>>>> dc4c06299ac0ee184352431b6ca8d58e59db3c61
## [v.3.24.0626.1]()
- 🐛: Fix lỗi xuất XML4750 ![](https://i.imgur.com/IR465Cc.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0626.0]()
- ✨: Hỗ trợ Thao tác danh mục thuốc xuất ra file Excle bổ sung thêm cột Dạng bào chế, Mã phương pháp chế biến, Thông tin thầu 130, Mã cơ sở KCB để người dùng có thể làm ngoài file Excel để cập nhật nhanh.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/415
## [v.3.24.0625.1]()
- 🐛: Kiểm tra qui tắc số BHXH khi lưu
- Định dạng: Số BHXH gồm 10 ký tự, tất cả đều là chữ số từ 0 đến 9.
- Không có ký tự chữ: Số BHXH không bao gồm bất kỳ ký tự chữ nào, chỉ có các con số.
- Độ dài cố định: Số BHXH luôn có độ dài cố định là 10 chữ số.
- ![](https://i.imgur.com/jlqCSe6.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/29
## [v.3.24.0625.0]()
- ✨: XML02.tt_thau lấy theo danh mục 4750
- 🐛: XML05.DIEN_BIEN_LS: Bệnh nhân ngoại trú chưa lấy được <DIEN_BIEN_LS /> dù có nhập chỉ số sinh hiệu
- 🐛: XML01.NGAY_VAO_NOI_TRU: Bệnh nhân ngoại trú không lập bệnh án lấy dư ngày vào nội trú
- 🐛: XML05.NGUOI_THUC_HIEN
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0622.0]()
- ✨: Bỏ hiển thị 2 cột Cấp và Tên tiếng anh
- ✨: Thêm groups Trong tỉnh và ngoài tỉnh
- 🐛: Fix lỗi lấy sai tên viết tắt khi add
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/61
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0621.1]()
- ✨: Yêu cầu thực hiện 4750 - Bổ sung danh mục Địa phương theo 4750 
- ![](https://i.imgur.com/YdVGqUR.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/399
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0621.0]()
- ✨: Yêu cầu thực hiện 4750 - Bổ sung danh mục Địa phương theo 4750 
- ![](https://i.imgur.com/YdVGqUR.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/399
## [v.3.24.0617.4]()
- 🐛: Thêm chức năng cấu hình chọn xuất XML (02->15) 
- ![](https://i.imgur.com/38Jfh0I.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0617.3]()
- 🐛: Fix lỗi stent2 trên 4210
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20#issuecomment-2165074926
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0617.2]()
- 🐛: Fix lỗi stent2 trên 4210
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20#issuecomment-2165074926
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0617.1]()
- 🐛: Fix lỗi stent2
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20#issuecomment-2165074926
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0617.0]()
- 🐛: Fix lỗi stent2
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20#issuecomment-2165074926
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
>>>>>>> c3162f775d68b60918a1d21dcd8976b4d78c527d
## [v.3.24.0613.0]()
- 🐛: XML05.DIEN_BIEN_LS (Thêm CDData)
- 🐛: Fix lỗi chưa có Mã 4750 trên danh mục quốc gia
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0612.5]()
- 🐛: XML1.MA_NOI_DEN - BN có phiếu chuyển viện nhưng khi xuất XML1 lại chưa có thông tin
- 🐛: XML6.LOAI_DTRI_LAO, NGAYBD_DTRI_LAO, NGAYKT_DTRI_LAO - Sau khi triển khai ở 2 đơn vị thì thống nhất lại chổ lấy hợp lý hơn là Xử trí phác đồ, khi fhi_dgxutri.maxutri = 2 hoặc 3, gửi khi điều kiện sẽ là tungay=< ngaykham <= denngay, hoặc tungay=< ngaykham, denngay is null
- ☑: https://github.com/dh-hos/92010-send4750/issues/1
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0612.4]()
- 🐛: XML1.MA_NOI_DEN - BN có phiếu chuyển viện nhưng khi xuất XML1 lại chưa có thông tin
- 🐛: XML6.LOAI_DTRI_LAO, NGAYBD_DTRI_LAO, NGAYKT_DTRI_LAO - Sau khi triển khai ở 2 đơn vị thì thống nhất lại chổ lấy hợp lý hơn là Xử trí phác đồ, khi fhi_dgxutri.maxutri = 2 hoặc 3, gửi khi điều kiện sẽ là tungay=< ngaykham <= denngay, hoặc tungay=< ngaykham, denngay is null
- ☑: https://github.com/dh-hos/92010-send4750/issues/1
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0612.3]()
- ✨: XML01.NHOM_MAU 
- ✨: XML03.PP_VO_CAM
- ✨: XML05.DIEN_BIEN_LS
- ✨: XML01,06,09,12.MAXA_CU_TRU, MAHUYEN_CU_TRU, MATINH_CU_TRU => Xử lý ưu tiên theo [Địa phương (theo QĐ 4750)](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750.md#user-content-fn-2024-06-12-02-4e793f573b226b50144acb4151da95a9), sau đó đến dmxa,dmhuyen,dmtinh (như cũ)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0612.2]()
- ✨: Yêu cầu thực hiện 4750 - Bổ sung nhập sobhxh trên danh mục nhân viên (sử dụng trong XML07.MA_BS)![](https://i.imgur.com/8qmBPJK.png)
- 🐛: https://github.com/dh-hos/To_Lap_Trinh/issues/398 
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0612.1]()
- ✨: Yêu cầu thực hiện 4750 - Bổ sung nhập sobhxh trên danh mục nhân viên (sử dụng trong XML07.MA_BS)![](https://i.imgur.com/8qmBPJK.png)
- 🐛: https://github.com/dh-hos/To_Lap_Trinh/issues/398
## [v.3.24.0612.0]()

- 🐛: XML7: MA_BS sai định dạng mã số BHXH , phần mềm đang lấy chứng chỉ hành nghề-> Mã bác sĩ lấy mã BHXH trưởng khoa. hiện tại chưa có chức năng nhập mã BHXH cho nhân viên -> thêm chức năng nhập mã BHXH trưởng khoa
![](https://i.imgur.com/J2zWtnF.png) 
- 🐛: XML1, 2, 3 sai số tiền khi bệnh nhân có chứng nhận miễn (XML không tính được chi phí được hưởng chứng nhận miễn), thẻ 1 và thẻ 2 đều bị sai ![](https://i.imgur.com/E1kZxvR.png) 
- 🐛: Fix Yêu cầu - Xác định mã lý do vào viện trên bảng kê 6556 và XML 4210 ( trường hợp bệnh nhân có giấy xác nhận cư trú) ![](https://i.imgur.com/lJrTENa.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0611.5]()
- ✨: xml06.KQ_DTRI_LAO = ""
## [v.3.24.0611.4]()
- ✨: XML06.NGAYBD_DTRI_LAO - Ngày bắt đầu phác đồ đầu tiên điều trị Lao, khi fhi_gdxutri.maxutri=2 liên kết fhi_dmxutri.maxutri, khi lần khám nào có phát sinh phác đồ Lao thì từ đó trờ về sau khám lần nào thì đẩy lần đó
- ✨: XML06.NGAYKT_DTRI_LAO - Ngày kết thúc phác đồ đầu tiên điều trị Lao, khi fhi_gdxutri.maxutri=2 liên kết fhi_dmxutri.maxutri, khi ngày khám = ngày kết thúc(người dùng nhập) thì mới đẩy
- ✨: XML06.LOAI_DTRI_LAO - Thống nhất lấy tại fhi_gdxutri.malydo liên kết fhi_dmchon.loai=16(gửi cột 4750), khi fhi_gdxutri.maxutri=2, khi lần khám nào có phát sinh phác đồ Lao thì từ đó trờ về sau khám lần nào thì đẩy lần đó
- ✨: XML06.MA_LYDO_XNTL_VR - Trường này thì chỉ đẩy lên dữ liệu khi có cấu hình XN đó thuộc fhi_dmxetnghiem.loai=2 và fhi_dmchon.loai=14(gửi cột 4750)
- ✨: XML06.NGAY_CHUYEN_PHAC_DO
- ✨: XML06.MA_PHAC_DO_DIEU_TRI 
## [v.3.24.0611.3]()
- ✨: Cập nhật xml HIV
## [v.3.24.0611.2]()
- ✨: Thực hiện [CHỦ ĐỀ: CÁCH GHI NHẬN GIÁ TRỊ CỘT XML1.MA_LYDO_VVIEN (cột 16, bảng 1 - XML4210)](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML4210/Vinh%20-%20Mo%20ta%20XML4210%20-%20XML1.MA_LYDO_VVIEN.md)
![](https://i.imgur.com/sDpfvF4.png)
![](https://i.imgur.com/eNNVLHF.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389
## [v.3.24.0611.1]()
- ✨: Thực hiện [CHỦ ĐỀ: CÁCH GHI NHẬN GIÁ TRỊ CỘT XML1.MA_LYDO_VVIEN (cột 16, bảng 1 - XML4210)](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML4210/Vinh%20-%20Mo%20ta%20XML4210%20-%20XML1.MA_LYDO_VVIEN.md)
![](https://i.imgur.com/BlhPztm.png)
![](https://i.imgur.com/dVtIYn3.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389
## [v.3.24.0611.0]()
- 🐛: Fix Lỗi - Cập nhật tự động bị mất phiên bản, không cập nhật được version của phiên bản cài đặt
- ![](https://i.imgur.com/O2Chxhk.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/67
## [v.3.24.0609.1]()
- ✨: Cập nhật XML06
- 🐛: Thêm ma4750 trong fhi_dmnoikhangdinhhiv: <NOI_XN_KD>00</NOI_XN_KD> <--Sử dụng mã dùng chung của cơ sở KBCB nơi BN được khẳng định HIV, fhi_dieutriarv.manoikhangdinhhiv liên kết bảng fhi_dmnoikhangdinhhiv(chưa có cột mã dùng chung) ![](https://i.imgur.com/Y5eHEYP.png)
- 🐛: <MA_LYDO_XNTL_VR />
- 🐛: <NGAY_XN_TLVR />
- 🐛: <KQ_XNTL_VR /> 
- 🐛: <NGAY_KQ_XN_TLVR /> Lấy ngày trên form HIV, được nhập và lưu/load từ fhi_xetnghiem
- 🐛: <MA_TINH_TRANG_DK /> Có thể check chọn nhiều tình trạng, liên kết bảng fhi_dmchon.loai=4
- 🐛: <LAN_XN_PCR /> Phần mềm hiện tại chỉ có 2 lần, 4750 thì quy định 3 lần, sẽ yc Pre bổ sung sau, dl từ bảng fhi_dieutriarv.
- 🐛: <NGAY_XN_PCR /> và <NGAY_KQ_XN_PCR /> Lấy chung 1 ô Ngày PCR.
- 🐛: <MA_KQ_XN_PCR /> Kết quả - Mã "0": Âm tính; Mã "1": Dương tính.
- 🐛: <MA_BAC_PHAC_DO /> fhi_gdxutri.maphacdo liên hết fhi.phacdo để lấy bậc
- 🐛: <NGAY_CHUYEN_PHAC_DO /> và <LY_DO_CHUYEN_PHAC_DO /> Hình 6
- ☑: https://github.com/dh-hos/92010-send4750/issues/1
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/387
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/388
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0607.0]()
- 🐛: Lỗi - Chỉnh thông tin bệnh nhân nội trú nút Lưu không lưu được
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/65#issuecomment-2153690364
## [v.3.24.0605.2]()
- ✨: Bổ sung XML04, XML05 theo mô tả mới [Mô tả XML QĐ 130 - Bổ sung QĐ 4750 [version 4]](https://github.com/dh-hos/Mo-ta-he-thong/blob/3d8dc81f63b3bb144848fd0643de2250aee28efb/XML130/QD4570/Vinh%20-%20Mo%20ta%20XML%20Quyet%20Dinh%20130%20-%2025-05-2024%20-%20Bo%20sung%20QD%204750%20-%20V4.docx)
- 🐛: Fix: <GIOI_TINH>: Mã hóa sai giới tính bệnh nhân ngược giữa Nam và Nữ ( theo 130 (1: Nam; 2: Nữ; 3: Chưa xác định) hiện tại bệnh nhân nữ phần mềm mã hóa 1 , nam mã hóa 2
- 🐛: Fix: <CAN_NANG>: chưa lấy được thông tin
- 🐛: Fix: <MA_MAY />: chưa lấy được dữ liệu
- 🐛: Fix: <MA_DOITUONG_KCB>: đang lấy sai. bệnh nhân ngoại trú có giấy chuyển nhưng mã hóa thành 2 (cấp cứu)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0605.1]()
- ✨: Bổ sung XML04, XML05 theo mô tả mới [Mô tả XML QĐ 130 - Bổ sung QĐ 4750 [version 4]](https://github.com/dh-hos/Mo-ta-he-thong/blob/3d8dc81f63b3bb144848fd0643de2250aee28efb/XML130/QD4570/Vinh%20-%20Mo%20ta%20XML%20Quyet%20Dinh%20130%20-%2025-05-2024%20-%20Bo%20sung%20QD%204750%20-%20V4.docx)
- 🐛: Fix: <GIOI_TINH>: Mã hóa sai giới tính bệnh nhân ngược giữa Nam và Nữ ( theo 130 (1: Nam; 2: Nữ; 3: Chưa xác định) hiện tại bệnh nhân nữ phần mềm mã hóa 1 , nam mã hóa 2
- 🐛: Fix: <CAN_NANG>: chưa lấy được thông tin
- 🐛: Fix: <MA_MAY />: chưa lấy được dữ liệu
- 🐛: Fix: <MA_DOITUONG_KCB>: đang lấy sai. bệnh nhân ngoại trú có giấy chuyển nhưng mã hóa thành 2 (cấp cứu)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0605.0]()
- ✨: Thêm chức năng nhập liệu đơn vị đo (DON_VI_DO trên XML04) trên danh mục CLS
- ![](https://i.imgur.com/2VNcw1u.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/383
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0604.2]()
- 🐛: Sai định dạng chổ này nha anh utf-8 mới đúng (Bỏ dòng này luôn)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0604.1]()
- 🐛: Fix: <CAN_NANG_CON>3300.00;2800.00</CAN_NANG_CON>: bỏ phần thập phân  .00 
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0604.0]()
- 🐛: Lấy sai: xml1.MA_NOI_DEN = this.TONG_HOP.psdangky_manoigt; -> theo mô tả thì MA_NOI_DEN là là mã BV mà BV đang khám sẽ chuyển bệnh nhân đi (chuyenvien.mabv)
- 🐛: <NGAY_TAI_KHAM /> chỉ lấy ngoại trú thôi ->hiện tại có thể chỉ lấy của ngoại trú (sau này nên bổ sung thêm vì nếu chỉ lấy ở ngoại trú thì sẽ thiếu do bệnh nhân nội trú vẫn có giấy hẹn, và ngoại trú cần bổ sung trường hợp bệnh nhân có giấy hẹn theo từng chuyên khoa.), => Lấy bnnoitru.ngaytaikham
- 🐛: <CAN_NANG_CON /> -> chưa lấy được số cân nặng con (ttcon.cannang)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0603.0]()
- ✨: Xuất XML theo thứ tự 1 -> 15 
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0531.1]()
- 🐛: xml1.MA_NOI_DEN = this.TONG_HOP.psdangky_manoigt;
- 🐛: XML1: không lấy được <T_TONGCHI_BV>0</T_TONGCHI_BV>
- 🐛: XML1: không lấy được <T_TONGCHI_BH>0</T_TONGCHI_BH>
- 🐛: XML1: <GIOI_TINH>2</GIOI_TINH> -> Yêu cầu bổ sung trường hợp giới tính = 3 : Không xác định
- 🐛: XML1: Chưa lấy được <NGAY_TAI_KHAM /> chỉ lấy ngoại trú thôi
- 🐛: XML1: Chưa lấy được <CAN_NANG_CON />
- 🐛: XML1: Chưa lấy được <MA_TAI_NAN />
- 🐛: XML2: Chưa lấy được <DANG_BAO_CHE />
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0531.0]()
- 🐛: Xử lý toa trả ngày YL giống với ngày YL toa nhận
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/61
## [v.3.24.0529.0]()
- 🐛: Fix lỗi column "mabn" does not exist
- 🐛: Fix XML4750_CHAN_DOAN_VAO => CDDATA nếu cần thiết
- 🐛: Fix XML4750_LY_DO_VV => CDDATA nếu cần thiết
- 🐛: Fix XML4750_MA_TAI_NAN lấy dữ liệu ma4750 từ bảng tainan và dmnntn thông qua mann
- 🐛: Fix XML2: DANG_BAO_CHE (dmtoathuoc.dangbc)
- 🐛: Fix XML2: THANH_TIEN_BV, THANH_TIEN_BH theo công thức
- 🐛: Fix XML3: THANH_TIEN_BV, THANH_TIEN_BH theo công thức, (DON_GIA_BH: lấy theo DON_GIA của XML4210, DON_GIA_BV: dongiabv theo bảng kê 6556, )
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0528.1]()
- 🐛: Fix lỗi sai MA_NGHE_NGHIEP trên XML1
- 🐛: Fix lỗi sai MA_DANTOC,MA_QUOCTICH trên XML1
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0528.0]()
- 🐛: Fix lỗi không lấy được SO_CCCD trong checkIn
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0526.2]()
- ✨: Hỗ trợ xuất XML4750.xml8 (hoàn thiện)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0526.1]()
- ✨: Hỗ trợ xuất XML4750.xml7 (hoàn thiện)
![](https://i.imgur.com/ZmwuliO.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0526.0]()
- ✨: Hỗ trợ xuất XML4750.xml3 (hoàn thiện)
![](https://i.imgur.com/LVwXRY8.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0525.1]()
- ✨: Hỗ trợ xuất XML4750.xml2 (hoàn thiện)
![](https://i.imgur.com/WzIwyPR.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0525.0]()
- ✨: Chuẩn hóa XML4750.xml1 (hoàn thiện)
![](https://i.imgur.com/gn6AijX.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0524.2]()
- ✨: Hỗ trợ xuất XML4750, chọn thư mục 1 lần khi chọn nhiều hồ sơ
- ✨: Chuẩn hóa XML1 (có thể xuất hiện lỗi do thiếu dữ liệu thì phải cập nhật các giá trị lại, chủ yếu các danh mục dùng chung)
![](https://i.imgur.com/XpiXzli.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20

## [v.3.24.0524.1]()
- ✨: Hỗ trợ xuất XML4750, chọn thư mục 1 lần khi chọn nhiều hồ sơ
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0524.0]()
- ✨: Bổ sung control để chỉnh sửa mã 4750
![](https://i.imgur.com/8lWx8OR.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/366

## [v.3.24.0523.4]()
- ✨: Chuẩn hóa xml.checkin
![](https://i.imgur.com/rg2i7fN.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20"
## [v.3.24.0523.3]()
- ✨: Thay đổi URL gửi xml lên cổng giám định theo QĐ4750: /api/qd130/checkInKcbQd4750 và /api/qd130/guiHoSoXmlQD4750
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0523.2]()
- ✨: Fix XML4750_MA_DOITUONG_KCB trong bảng checkin (HOÀN THÀNH CHECKIN)
- PS: (nhờ KT, HT kiểm thử các giá trị trong trường này có theo đúng qui định của 4750 và 130 chưa)
![](https://i.imgur.com/7RNGz4c.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57- 
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20"
## [v.3.24.0523.0]()
- ✨: Bổ sung chức năng xuất XML 4750 để test VAS
![](https://i.imgur.com/lQd6Ola.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57- 
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0522.1]()
- 🐛: Fix lỗi thiếu cấu trúc FHI (schema)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20#issuecomment-2123814211
## [v.3.24.0522.0]()
- ✨: Hoàn thiện xml4750.checkin để gửi cổng đào tạo
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0517.1]()
- ✨: Bổ sung control để chỉnh sửa mã liên thông
![](https://i.imgur.com/XAVMzeT.png) ![](https://i.imgur.com/dxi4bey.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/58
## [v.3.24.0517.0]()
- 🐛: Fix lỗi sai ngày lại sau khi đăng xuất
- 🐛: Fix sai ngày làm việc trên form Nhật ký hệ thống
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/59
- 📕: Gom tất cả code đăng xuất trở về lúc đăng nhập lúc đầu