# Командный проект №1. Сайт компании по недвижимости **"Realco"**
Компания Realco - агенство недвижимости в Северной Америке, предлагающее свои услуги в городах-миллиониках США (Нью-Йорк, Лос-Анджелес, Лас-Вегас, Сан-Диего и др.)
### Проект выполнен на основе [макета](https://www.figma.com/design/kEVO5l8dmhI80RdChSpAEn/Realco?node-id=0-1) графического редактора Figma
### и реализован на базе технологий `html5`, `css3` и фреймворка `bootstrap5`
![image](https://tajuso.com/wp-content/uploads/2018/03/udemy3-004.png)

### Сайт адаптирован под разные виды устройств (desktop, tablet, mobile):

* Desktop 
![image](./assets/readme/realco_1.png)
![image](./assets/readme/realco_2.png)
![image](./assets/readme/realco_3.png)
![image](./assets/readme/realco_4.png)
![image](./assets/readme/realco_5.png)

* Mobile <br>
  
![image](./assets/readme/realco_adaptive.png)

![image](./assets/readme/realco_adaptive2.png)
![image](./assets/readme/realco_adaptive3.png)


### Команда разработчиков проекта:
* MariaLukyanova
* AlenaGorina
* NadezhdaKov
* Basulka
* Helen1553



#### <u>**Памятка по работе с GIT**</u>
* <i>Клонирование репозитория:</i>
  1. Переходим в нужный репозиторий и нажимаем на кнопку "<>Code"
  2. Копируем ссылку
  3. Создаём папку для проекта на рабочем столе
  4. В этой папке в адресной строке пишем `cmd` - появляется терминал
  5. В терминале набираем команду `git clone "ссылка на репозиторий" .`
  6. Далее работаем с этой папкой уже в vscode
<br>

* <i>Основные команды Git:</i>

  * Команда `git status` - <strong>проверка статуса репозитория</strong> - узнаём, что вообще происходит

  * Проверяем, нет ли изменений в удалённом репозитории:
    * через терминал vscode: пишем: `git fetch origin`
  
  * <strong>Фиксируем изменения (чтобы гит их отслеживал)</strong>:
    * через интерфейс vscode: нажимаем на плюсик;
    * через терминал vscode: пишем: `git add <файл, который вы меняете>`
  
  * **Создаём коммит:**
    * <u>через интерфейс vscode</u>: открываем слева вкладку Source Control --> пишем сообщение коммита ---> далее либо сочетаниями клавиш cntrl+enter (windows)/ command+enter (mac), либо нажимаем на кнопочку Commit
    * <u>через терминал vscode</u>: пишем: `git commit -m "сообщение коммита"`
(коммит можно откатить (если вы еще не запушили изменения): нажимаем на 3 точки --> Commit --> Undo last commit)

  * **Отправляем изменения в удалённый репозиторий** (т.е.гитхаб):
    * <u>через интерфейс vscode</u>: нажимаем на три точки --> Push (либо через кнопочку sync changes - но помните, она пушит и пуллит одновременно);
    * <u>через консоль vscode: пишем</u>: `git push origin main`
  
  * **Получение изменений из удалённого репозитория**
    * <u>через интерфейс vscode</u>: нажимаем на три точки --> Pull
    * <u>через терминал vscode</u>:  `git pull origin main`
