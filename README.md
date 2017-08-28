# django 學習筆記

step 1 : 安裝python 3.5

step 2 : 安裝完畢後，找到python.exe的所在路徑，將此路徑加入 控制台\所有控制台項目\系統\進階系統設定\環境變數的PATH中 讓 CMD可以直接執行PYTHON程式

step 3 :建立django 虛擬環境 (Windows 環境下)

		1.切換到專案目錄 : cd /d D:\git\django

		2.python -m venv django_first
		
step 4 :切換到虛擬環境  django_first\Scripts\activate => (如果看到前面多了 (虛擬資料夾名稱)，表示成功切換到虛擬環境)

step 5 :開始安裝django => pip install "django<1.9" => 如何確定 django 已安裝成功，在虛擬環境中輸入 python 進入python環境 =>輸入 >>> import django >>> django.VERSION 輸出結果(1, 8, 6, 'final, 0')=>代表安裝成功(ctrl+z退出python命令列環境)

---------------- 

建立 Django 專案

在虛擬環境中執行 => django-admin.py startproject mySite

啟動開發環境 => 切換到mySite => python manage.py runserver
