# 使用するイメージを設定
FROM nginx

# ローカルの default.conf をコンテナ内の /etc/nginx/conf.d/ にコピーする
COPY ./default.conf /etc/nginx/conf.d/

# ローカルの　htmlファイル をコンテナ内の /var/www/html/ にコピーする
COPY ./*.html /var/www/html/