# Hands on Lab 0 - 準備工作 #

操作時間: **30 分鐘**


# 1. 申請 Azure 訂閱 #

## 一般免費試用 ##

在操作本教材前，必須先確認是否擁有 Microsoft Azure 的訂閱帳戶，若尚未申請，請參考 [Azure 食譜 - 1.1 建立 Microsoft Azure 訂閱帳戶](http://book.azure-recipes.tw/chapter01/01_signup.html) 上的文章申請免費試用 30 天（含新台幣 6,300 元額度）。

## 使用特殊訂閱服務開始 ##

若您欲採用其它方式購買 Microsoft Azure 的訂閱帳戶（如：**Azure in Open**），請使用 https://account.windowsazure.com/signup?showCatalog=True 這個連結，登入 Microsoft 帳號（以前稱作 MSN 帳號或 Windows Live ID）後選擇對應的服務購買。

![購買 Microsoft Azure 訂閱](images/0-signup-microsoft-azure-subscription.png)

# 2. 建立 Azure 儲存體帳戶 #

因為在操作 Azure IoT Suite 的相關 labs 中經常會用到 Azure Blob 儲存體，所以為了之後的操作方式便，可以先建立一個儲存體帳戶以便後續使用。

建立方式請參考 [Azure 食譜 - 4.1 建立儲存體帳號](http://book.azure-recipes.tw/chapter04/01_create_storage_account.html)。


# 3. 安裝軟體 #

操作過程中可能會使用到下列軟體：

  1. Visual Studio 2013 以上（**Community**, Professional, Premium, Ultimate 版本都可以）。
  2. Excel 2013 ProPlus 以上。
  3. [AzCopy](http://aka.ms/downloadazcopy) - 用來上傳檔案至 Azure 儲存體，詳見[使用說明](http://aka.ms/azcopy)。


# 4. 善用論壇 #

請多多利用 [MSDN 論壇 - Microsoft Azure PaaS 服務](https://social.msdn.microsoft.com/Forums/zh-TW/home?forum=2199) 的論壇來發問及交流。

# 5. Azure 帳號建立失敗或其他設定問題的處理方式 #

當您在建立 Azure 帳號過程中，遭遇一些問題 (例如：無法建立帳號、無法接收到驗證簡訊或是驗證後仍失敗等) 導致無法完成帳號建立時，請參考以下步驟，開立支援票證，以便讓微軟客戶支援服務團隊協助您。

  1. 請登入此網址：http://bit.ly/1IeFUu1
  2. 在 "Problem type:" 的下拉式選單內，選擇 "I cannot sign up for a new account" (若您遭遇其他的問題，可以選擇更符合您狀況的描述)。
  3. 點選 "Start request" 按鈕。
  4. 在 "Create an incident" 頁面中，確認您的聯絡資訊。所有欄位都正確填寫完成後，點選 "Continue" 按鈕。
  5. 在 "Create an incident - describe the issue" 頁面中，描述您所遭遇的問題 (可使用中文)。所有欄位都填寫完成後，勾選下方的 "I accept the Agreement for Microsoft Services."，並點選 "Continue" 按鈕。
  6. 完成後，您會收到微軟客戶技術服務團隊的來信或來電，以便協助您處理所遭遇的問題。
