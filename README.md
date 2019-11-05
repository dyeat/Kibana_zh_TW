# kibana 中文化

# 測試環境 版本7.3.2

步驟:
---

### 1. 至kibana.yml 更改語系

```sh
$ vim /etc/kibana/kibana.yml

尋找 i18n.locale: "zh-TW" 更改語系

```
### 2. 複製 zh-TW.json 至資料夾 指定路徑
```sh
$ cp zh-TW.json /usr/share/kibana/node_modules/x-pack/plugins/translations/translations/zh-TW.json

or

$ cp zh-TW.json /usr/share/kibana/x-pack/plugins/translations/translations/zh-TW.json
```
### 3. 重新啟動kibana
```sh
$ systemctl restart kibana.service
```
### 4. done


---

#### ※對於顯示的文字不正確 可自行修改 zh-TW.json 
已更改 文字

| **更改前** | **更改後** |
| ------ |:------:|
| 數據   |  資料  |
| 搜索   |  搜尋  |
| 信息   |  訊息  |
| 這里   |  這裡  |
| 存儲   |  儲存  |
| 新建   |  創建  |
| 保存   |  儲存  |
| 打開   |  開啟  |
| 共享   |  分享  |
| 日誌   |  Log   |
| 註意   |  注意  |
| 鏈接   |  連結  |
| 標簽   |  標籤  |
| 添加   |  新增  |
| 全屏   | 全螢幕 |
| 次命中   | 條符合 |
| 磁盤   | 磁碟 |
| 內存   | 記憶體 |
| 網絡   | 網路 |
| 恢複   | 恢復 |
| 策略   | 規則 |
| 複製   | 複製 |
| 剪貼板   | 剪貼簿 |
| 合並   | 合併 |
| 示例   | 範例 |
| 布爾   | 布林 |
| 日歷   | 日歷 |
| 服務器   | 伺服器 |
| 打印   | 列印 |
| 撤消   | 撤銷 |

