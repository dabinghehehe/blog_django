## 数据迁移（Migrations）
通过运行 makemigrations 命令，Django 会检测你对模型文件的修改，并且把修改的部分储存为一次迁移
python manage.py makemigrations

输入python manage.py migrate，应用迁移到数据库中:
python manage.py migrate

pip3 config set global.index-url https://pypi.douban.com/simple/
pip3 config list


## 创建管理员账号（Superuser）
python manage.py createsuperuser

