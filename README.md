# Web-Panel
## Định nghĩa 
Web panel (hoặc web hosting control panel) là một giao diện quản lý dựa trên web giúp người dùng quản lý các dịch vụ và tài nguyên của máy chủ hoặc dịch vụ lưu trữ web. Các tính năng chính của một web panel thường bao gồm:
- Quản lý Tài khoản và Tên miền: Cho phép người dùng tạo, xóa, và quản lý các tài khoản người dùng, tên miền, và tên miền con.
- Quản lý Email: Cung cấp công cụ để tạo và quản lý các tài khoản email, thiết lập chuyển tiếp email, và lọc spam.
- Quản lý Cơ sở dữ liệu: Cho phép người dùng tạo, xóa, và quản lý cơ sở dữ liệu, thường bao gồm công cụ như phpMyAdmin để quản lý cơ sở dữ liệu MySQL.
- Quản lý Tệp: Cung cấp công cụ quản lý tệp trên máy chủ qua giao diện web, cho phép tải lên, tải xuống, và chỉnh sửa các tệp.
- Quản lý DNS: Cho phép người dùng cấu hình và quản lý các bản ghi DNS cho các tên miền.
- Bảo mật: Cung cấp các công cụ bảo mật như tường lửa, chứng chỉ SSL, và cài đặt bảo mật khác.
- Sao lưu và Phục hồi: Cung cấp khả năng sao lưu dữ liệu và phục hồi khi cần thiết.
- Giám sát và Logs: Cung cấp công cụ để theo dõi hiệu suất máy chủ và xem các bản ghi hoạt động.
- Hỗ trợ PHP và Các Công nghệ Web khác: Cho phép cấu hình các phiên bản PHP, công nghệ web khác, và cài đặt ứng dụng.

## DirectAdmin      

| Tiêu đề Cột 1          | Tiêu đề Cột 2     |
| ---------------------- | ----------------  |
| Giới hạn user/domain   | Giới hạn theo gói |
| Webserver mặc định     | Apache            |
| File Manager - FTP     | Có                |
| Multi PHP              | Có                |
| DNS                    | Có                |
| Email                  | Có                |
| Free SSL               | Có                |
| My SQL + PHPAdmin      | Có                |
| Backup - Restore       | Set up thủ công   |
| Monitor - Logs         |                   |
| Security               |                   |
| More Plugins Support   |                   |

## aaPanel 
| Tiêu đề Cột 1          | Tiêu đề Cột 2     |
| ---------------------- | ----------------  |
| Giới hạn user/domain   | Giới hạn theo gói |
| Webserver mặc định     | Apache            |
| File Manager - FTP     | Có                |
| Multi PHP              |                   |
| DNS                    |                   |
| Email                  |                   |
| Free SSL               |                   |
| My SQL + PHPAdmin      |                   |
| Backup - Restore       |                   |
| Monitor - Logs         |                   |
| Security               |                   |
| More Plugins Support   |                   |

## CyperPanel
| Tiêu đề Cột 1          | Tiêu đề Cột 2     |
| ---------------------- | ----------------  |
| Giới hạn user/domain   | Giới hạn theo gói |
| Webserver mặc định     | Apache            |
| File Manager - FTP     | Có                |
| Multi PHP              |                   |
| DNS                    |                   |
| Email                  |                   |
| Free SSL               |                   |
| My SQL + PHPAdmin      |                   |
| Backup - Restore       |                   |
| Monitor - Logs         |                   |
| Security               |                   |
| More Plugins Support   |                   |

## VestaCP
| Tiêu đề Cột 1          | Tiêu đề Cột 2     |
| ---------------------- | ----------------  |
| Giới hạn user/domain   | Giới hạn theo gói |
| Webserver mặc định     | Apache            |
| File Manager - FTP     | Có                |
| Multi PHP              |                   |
| DNS                    |                   |
| Email                  |                   |
| Free SSL               |                   |
| My SQL + PHPAdmin      |                   |
| Backup - Restore       |                   |
| Monitor - Logs         |                   |
| Security               |                   |
| More Plugins Support   |                   |

## So sánh chung 
| STT | Tiêu Chí                            | DirectAdmin        | aaPanel                      | CyberPanel              | VestaCP                         |
|-----|-------------------------------------|--------------------|-----------------------------|-------------------------|---------------------------------|
| 1   | Miễn Phí/ Có Phí                    | Có Phí             | Miễn Phí/ Có Phí            | Miễn Phí/ Có Phí        | Miễn Phí                        |
| 2   | Giới hạn users/ domains             | Giới hạn theo gói  | 1 user                      | Nhiều users/ domains    | Nhiều users/ domains           |
| 3   | WebPanel Mặc Định                   | Apache             | Apache/Nginx                | OpenLiteSpeed           | Apache/Nginx                    |
| 4   | Hỗ trợ SSL                          | Có                 | Có                          | Có                      | Có - Không ổn định              |
| 5   | File Manager                        | Có                 | Có                          | Có                      | Không - phải active thủ công    |
| 6   | Hỗ trợ FTP                          | Có                 | Có                          | Có                      | Có                              |
| 7   | Hỗ trợ PHPMyAdmin                   | Có                 | Có                          | Có                      | Có                              |
| 8   | DNS Server                          | Có                 | Có                          | Có                      | Có                              |
| 9   | Email Server                        | Có                 | Không                       | Có                      | Có                              |
| 10  | Backup - Restore                    | Setup thủ công     | Setup thủ công              | Setup thủ công          | Đã có predefined - có thể custom |
| 11  | Hỗ trợ Docker                       | Không              | Có                          | Có                      | Không                           |
| 12  | Hỗ trợ Multi PHP                    | Có - phải build thêm | Có - phải build thêm        | Có - Mặc định           | Có - phải build thêm thủ công   |
| 13  | Reseller                            | Có                 | Không                       | Có                      | Không                           |
| 14  | Hỗ trợ NodeJS/ Python               | ONLY in PRO pack   | Có                          | Không                   | Không                           |
| 15  | Thao tác cài đặt, sửa đổi           | Dễ                 | Dễ                          | Khó                     | Khó                             |
| 16  | Firewall CSF/LFD                    | Có + GUI           | FW cơ bản                   | Có                      | Có                              |
| 17  | Terminal in GUI                     | Không              | Có                          | Không                   | Không                           |
| 18  | Hỗ trợ Packages - Chia gói Hosting  | Có                 | Không                       | Có                      | Có                              |
| 19  | Hỗ trợ chuyển qua sử dụng Litespeed | Có                 | Không - chỉ có OpenLiteSpeed | Có                      | Không                           |
| 20  | Các chức năng trả phí nâng cao      | Mua theo từng plugins | Chỉ mua theo gói plugins  | Mua theo từng plugins   | Mua theo từng plugins           |
| 21  | Hỗ trợ cấu hình qua API             | Có                 | Có                          | Không - chỉ có GitHub   | Không                           |

