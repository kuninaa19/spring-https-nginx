## Spring-HTTPS-nginx
스프링 컨테이너 생성, Certbot이미지로 letsencrypt 인증받은 후  nginx HTTPS 적용

### 사용방법
nginx/conf.d/app.conf, init-letsencrypt.sh 도메인 및 기타내용 작성   
###
init-letsencrypt.sh 실행권한 부여

    chmod +x init-letsencrypt.sh
##
docker-compose를 사용하는 대신 아래의 쉘스크립트를 실행

    sudo ./init-letsencrypt.sh