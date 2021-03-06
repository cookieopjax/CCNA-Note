# CCNA Unit 1

##  (Open System Interconnection ,OSI)網路七層架構


| Layer 名稱         | 中文       | 功能與說明                                                                                              |
| ------------------ | ---------- | ------------------------------------------------------------------------------------------------------- |
| Application Layer  | 應用層     | 應用程式                                                                                                |
| Presentation Layer | 出席層     | 資料的壓縮還原、網路安全、檔案傳送。                                                                    |
| Session Layer      | 會談層     | 網路管理、密碼辨識、簽到簽退、網路監控。                                                                |
| Transport Layer    | 傳輸層     | 資料傳輸錯誤的偵測和復原，資料封包的重行排列。                                                          |
| Network Layer      | 網路層     | 定義虛擬電路的建立、維持和終止，封包交換的路由選擇、擁塞控制等。                                        |
| Data Link Layer    | 資料連結層 | 定義把傳輸資料分裝成資料封包的規範， 檢查資料傳輸中是否有錯誤發生，執行資料傳送中的流量控制及鏈路管理。 |
| Physical Layer     | 實體層     | 定義實際傳輸資料的硬體設備的規範，像是纜線規格、接頭尺寸、信號電壓、資料傳輸時序等等。                  |

----

中介網路裝置包括：
* 網路存取（交換器和無線存取點）
* 網路互連（路由器）
* 安全（防火牆）

網路基礎建設:
* 區域網路 (LAN) - 通常由一個組織或個人管理。
* 廣域網路 (WAN) - 通常由服務供應商 (SP) 或 Internet 服務供應商 (ISP) 管理。
* 都會網路 (MAN)
* 無線 LAN (WLAN)
* 儲存區域網路 (SAN)

----

### 一般使用者連線到Internet之方法:
* **有線電視網路** - 通常由有線電視服務供應商提供，Internet 資料訊號在輸送有線電視訊號的同軸纜線上進行傳輸。它能提供高頻寬、不斷線網路和 Internet 連線。特殊的纜線數據機將 Internet 資料訊號與該纜線承載的其他訊號分離，並提供與主機電腦或 LAN 的乙太網路連線。
* **DSL** - 高頻寬、不斷線網路和 Internet 連線。它使用一種特殊的高速數據機，該裝置將 DSL 訊號從**電話訊號**中分離出來，並提供與主機電腦或 LAN 的乙太網路連線。DSL 透過電話線執行，線路分為三種通道。一個通道用於語音電話通話。這個通道允許人們在不中斷 Internet 的情況下接聽電話。第二個通道是快速下載通道，用於接收來自 Internet 的資訊。第三個通道用於發送或上傳資訊。這個通道通常比下載通道略慢。DSL 連線的品質和速度主要取決於電話線路的品質以及跟電話公司局端的距離。離局端越遠，連線速度越慢。
* **蜂巢式網路** - 又稱行動網路（mobile network）。
* **衛星** - 就是衛星。
* **撥號電話** - 使用電話線和數據機，費用相對較低。使用者透過撥打 ISP 接取電話號碼來連線 ISP。撥號數據機連線提供的低頻寬通常不足用於大型資料傳輸，但對旅行中的行動存取非常有用。僅當沒有更高速的連線選項時，應考慮數據機撥號連線。

### 企業連線到Internet之方法:
* **專用租用線路** - 這是從服務供應商到客戶建築的專用連線。租用線路實際上是連接地理位置分散的辦公室的保留電路，以提供私用語音和或資料網路。
* **都會乙太網路** - 都會乙太網路通常是從供應商到客戶建築，透過專用銅纜或光纖連線提供 10 Mb/s 到 10 Gb/s 的頻寬速度。
* **DSL** - 數位用戶迴路 (SDSL)->上下載對稱 ; 非對稱數位用戶迴路 (ADSL)->上下載不對稱。
* **衛星** - 就是衛星。

----

可靠網路
* 容錯能力(Fault tolerance)
* 可延伸性(Scalavility)
* 服務品質(Quality of Service)
* 安全性(Security)