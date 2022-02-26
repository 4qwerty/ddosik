1) Встановити докер по силці https://www.docker.com/get-started 
2) Встановити ядро лінукса WLS в четвертому пункті по силці https://docs.microsoft.com/ru-ru/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package 
3) перезапусти комп
5) докер має вигляди наступним чином

![изображение](https://user-images.githubusercontent.com/50421230/155846674-d6c7a529-a2a4-4bf6-9e54-6924c9b5f409.png)

5) Зайдіть в cmd або іншу наявну консоль на пк і пропишіть цю команду ```docker run -ti --rm alpine/bombardier -c 1000 -d 3600s -l``` через пробіл після цієї команди встате силку на один із цих сайтів
 -https://www.gosuslugi.ru/
 -https://epp.genproc.gov.ru
 -https://ach.gov.ru
 -http://www.scrf.gov.ru
