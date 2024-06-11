<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 3.24.0611.5 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalAdminexe%2F32406115-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalAdminexe%2F32406115-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalAdminexe%2F32406115-NasDHSolutions.json)
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