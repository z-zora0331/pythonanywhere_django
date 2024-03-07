# pythonanywhere_django

modify: 2024-03-07

Step 1. 建立/啟動虛擬環境

```
<!-- 僅第一次執行即可 -->
$ C:/Users/JingYa.Zeng/Anaconda3/envs/work/python.exe -m venv myvenv

<!-- 啟動環境 -->
$ myvenv\Scripts\activate
```

Step 2. 安裝環境/套件

```
$ pip install django
$ pip install djangorestframework

<!-- 或一次安裝 -->
$ pip install -r requirements.txt
```

Step 3. 設定SQLite資料庫

```
$ python manage.py migrate
```

Step 4. 建立超級使用者

```
$ python .\manage.py createsuperuser
```

Step 5. 運行專案，啟動WebServer

```
$ python manage.py runserver

<example>
- Username: zora
- Email address: (可空白)
- Password: 123
```

備註 . 其他
```
<!-- 查詢已安裝套件 -->
$ pip list

<!-- 管理套件 -->
$ pip freeze > requirements.txt
```