# dockerfile nginx-php-mssql
# docker build wolf/nginx-php-fpm:latest
# 简单运行容器
#sudo docker run -d wolf/nginx-php-fpm
#要在启动时从git中动态提取代码：
#docker run -d -e 'GIT_EMAIL=email_address' -e 'GIT_NAME=full_name' -e 'GIT_USERNAME=git_username' -e 'GIT_REPO=github.com/project' -e 'GIT_PERSONAL_TOKEN=<long_token_string_here>' wolf/nginx-php-fpm:latest
