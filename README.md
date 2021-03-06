# RTUPlane
Название проекта: Mountain Plane

Описание: Геймплей игры представлен в виде достижения игроком, взявшимся за штурвал самолёта, базирующегося в горах, "контрольных точек" - абстрактных жёлтых прямоугольников. Самолёт может разгоняться, увеличивать/уменьшать скорость в зависимости от направления полёта, совершать тангаж, крен и рысканье. При разбитии об горы или вылете за границы уровня самолёт появляется на начальной точке. Проект создавался в одиночку (Соколовский Игорь Икбо-01-19). https://github.com/DJSwitchCase/RTUITLab1.

Скриншоты: https://disk.yandex.ru/i/WnWN-JpOqwc4Zw https://disk.yandex.ru/i/wMqv1zelyu4Twg

Инструкция по запуску: Для успешного запуска требуется устройство на операционной системе Windows, Unity SDK, Visual Studio C++ Redistributable, а так же файлы билда (ассеты, скрипты, exe. и тд.) 

Из-за проблем с Git LFS (ограниченный размер хранилища) не получилось вести историю commit'ов проекта и мною было принято решение сосредоточиться на разработке, а потом загрузить проект целиком, чтобы уложиться во временные рамки. Прошу прощения, снизу документирую примерную историю разработки:
1. Importing the plane's prefab, creating a script for basic plane controls. 
2. Creating the basic terrain form of the terrain.
3. Scripting the collision, respawn system and creating "invisible walls" around the borders of the map.
4. Improving the terrain, changing the skybox.
5. Adding the game's goal "checkpoints" - abstract yellow rectangles needed for the player to pass through to win the game.
6. Scripting the rectangles' collision.
7. Scripting the UI.
