--------------------------------------------------------------------------------------------------------------------------------------
RU
--------------------------------------------------------------------------------------------------------------------------------------

Файлы, необходимые для полноценной работы мода.
Автомобили и запчасти к ним будут спавниться в мире вместе с ванильными.
Обратите внимание - чать автомобилей использует стандартные точки спавна.
Также включены дополнительные точки спавна (взяты из файлов, в обсуждениях к моду в стиме).
Не включает в себя прайсинг для торговца.
Также присутствует экселька для облегчения работы со списком.

--------------------------------------------------------------------------------------------------------------------------------------
Для тех, кто не знает как это работает. 

Для корректной работы необходимо добавить модельки в четыре файла - types и events в папке mpmissions\dayzOffline.chernarusplus\db, и 
cfgspawnabletypes и cfgeventspawns в папке mpmissions\dayzOffline.chernarusplus. (для других карт - другая директория соответственно).

Файл types - содержит параметры предмета на сервере - время жизни, флаги, теги для спавна и т.п.

С ним тесно связан файл cfgspawnabletypes, который содержит параметры спавна предмета - какие  части с каким шансом должны быть 
установлены, что может находиться в созданном контейнере и т.п.

Файл events, по аналогии, содержит в себе параметры событий - минимальное и максимальное количество (это важно!), какой дочерний 
элемент оно создаёт и т.п. 

И связанный с ним файл cfgeventspawns - содержит в себе координаты, где это событие будет вызываться.

Для корректной работы мода необходимо добавить содержимое этих четырёх файлов в одноимённые файлы в папке с игрой 
(расположение как в описании).

--------------------------------------------------------------------------------------------------------------------------------------

Прим. Делал по большому счёту для себя. Как я понял мод недавно разделился на два разных самостоятельных мода, из-за чего все ранее 
написанные файлы потеряли актуальность. И хотя разработчик предоставил types, их пришлось исправлять в соответствии с текущим списком 
авто (убран опель блиц - он ушел в другой мод, убраны несколько уазов - предполагаю что там ошибка в имени, из-за чего игра не может 
их найти) Я не тестировал ВСЁ, но получилось вполне играбельно и без ошибок в консоли.

--------------------------------------------------------------------------------------------------------------------------------------
EN
--------------------------------------------------------------------------------------------------------------------------------------

The files necessary for the mod to work properly.
Cars and their spare parts will spawn in the world along with vanilla ones. 
Additional spawn points are also included (taken from files in discussions on steam).
It does not include the pricing for the merchant.
There is also an excel card to make it easier to work with the list.

--------------------------------------------------------------------------------------------------------------------------------------
For those who don't know how it works. 

For correct operation, four files are needed - types and events in the folder 
mpmissions\dayzOffline.chernarusplus\db and cfgspawnabletypes and cfgeventspawns in the folder mpmissions\dayzOffline.chernarusplus. 
(for other maps - a different directory, respectively).

The types file contains the parameters of the item on the server - lifetime, flags, tags for spawn, etc.

Closely related to it is the cfgspawnabletypes file, which contains the spawn parameters of the item - which parts should be 
installed with what chance, what can be in the created container, etc. 

The events file, by analogy, contains the event parameters - the minimum and maximum number (this is important!), which child element 
it creates, etc. 

Associated cfgeventspawns file contains the coordinates where this event will be triggered.

For the mod to work correctly, you need to add the contents of these four files to same in the game folder. 
(the location is as described).

--------------------------------------------------------------------------------------------------------------------------------------

Note. I did it mostly for myself. As I understand it, the mod has recently split into two different independent mods, which is why all 
previously written files have lost their relevance. And although the developer provided the types, they had to be fixed in accordance 
with the current list of cars (Opel blitz was removed - it went to another mod, several uazs were removed - I assume that there is an 
error in the name, which is why the game cannot find them) I haven't tested EVERYTHING, but it turned out to be quite playable and 
error-free in the console.
