# nhyai
南海云　AI 开放平台

数据库割接：

python backend/manage.py makemigrations

python backend/manage.py migrate

后台运行：
screen python backend/manage.py runserver 0.0.0.0:8000 --noreload

运行任务:
screen python backend/manage.py process_tasks

如遇到mysql安装错误，在ubuntu下执行如下命令：
sudo apt-get install libmysqlclient-dev