# docker-compose
for scillfactory e.4
Для установки docker: curl -fsSL https://get.docker.com/ 
установка docker-compose: sudo apt install docker-compose

1. cкачать проект с git: git clone https://github.com/julia-tolkacheva/docker-compose.git
2. запустить сборку: sudo docker-compose build
3. проверка образов: sudo docker images
4. запуск контейнеров: sudo docker-compose up -d
5. проверка логов: sudo docker-compose logs -f
