<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 3.24.0708.0 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalAdminexe%2F32407080-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalAdminexe%2F32407080-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalAdminexe%2F32407080-NasDHSolutions.json)
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