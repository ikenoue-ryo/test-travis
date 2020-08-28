## インストール  
pipenv install django gunicorn psycopg2 psycopg2-binary Pillow  
pip install python-dotenv libsass django-compressor django-sass-processor

## ファイル作成  
touch .env  

SECRET_KEY=ここにSECRET_KEY  

DATABASE_ENGINE=  
DATABASE_DB=  
DATABASE_USER=  
DATABASE_PASSWORD=  
DATABASE_HOST=  
DATABASE_PORT=  


## 開発環境起動コマンド
pipenv shell
pipenv install パッケージetc
pythonmanage.py runserver --settings=config.settings.local