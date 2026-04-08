# ОСНОВНОЙ НАБОР ПРАВИЛ

## [**RU**](/ru/rulesets/DEFAULT.md) | [EN](/en/rulesets/DEFAULT.md)

<details>
  <summary>
    <b> Основной набор </b>
  </summary>

## Основной набор

**Набор предметов**

* Ресурсы
  * Дерево ![Дерево](/img/blocks/x16/oak_log.png)
  * Камень ![Камень](/img/blocks/x16/stone.png)
* Ресурсы с Аттрибутами
  * Сырое мясо ![Сырое мясо](/img/items/x16/beef.png)
  * Пшеница ![Пшеница](/img/items/x16/wheat.png)
  * Стрела ![Стрела](/img/items/x16/arrow.png)
* Функциональные предметы
  * Верстак ![Верстак](/img/blocks/x16/crafting_table_side.png)
  * Бочка ![Бочка](/img/blocks/x16/barrel_side.png)
  * Сундук ![Сундук](/img/blocks/x16/chest_front.png)
  * Печка ![Печка](/img/blocks/x16/furnace_front.png)
* Инструменты
  * Мотыга ![Мотыга](/img/items/x16/wooden_hoe.png)
  * Меч ![Меч](/img/items/x16/wooden_sword.png)
  * Топор ![Топор](/img/items/x16/wooden_axe.png)
  * Кирка ![Кирка](/img/items/x16/wooden_pickaxe.png)
  * Щит ![Щит](/img/items/x16/shield_front.png)
* Оружие
  * Меч ![Меч](/img/items/x16/wooden_sword.png)
  * Топор ![Топор](/img/items/x16/wooden_axe.png)
  * Лук ![Лук](/img/items/x16/bow.png)
  * Арбалет ![Арбалет](/img/items/x16/crossbow_standby.png)
* Еда
  * Сырое мясо ![Сырое мясо](/img/items/x16/beef.png)
  * Жаренное мясо ![Жаренное мясо](/img/items/x16/cooked_beef.png)
  * Хлеб ![Хлеб](/img/items/x16/bread.png)

---

**Набор механик**

**Стартовые условия**

* 3 слота инвентаря
* 3 действия в первый ход
* 3 ХП в инвентаре
* Размер поля:
  * 4x4 для 2 игроков
  * 6x6 для 3 игроков
  * 8x8 для 4 игроков
* Ограничение количества действий до 3

**Действия**

* **Крафт** - производится с ресурсами и требуемыми предметами на поле
  * Ресурсы должны соприкосаться друг с другом (включая диагональ)

* **Атака** - является Перемещением Оружия, разрушающим блоки в области, привязанной к оружию
  * требует расходование предметов из инвентаря

* **Разрушение** - разрушение любого предмета кроме Еды дает 1 ХП
  * Один ХП с разрушения можно сразу установить

**Предметы**

* **Ресурсы** - предметы, расходуемые для каких-либо действий
  * Стрела ![Стрела](/img/items/x16/arrow.png) - расходуется при атаке дальним оружием

* **Ресурсы с Аттрибутами** - ресурсы, наличие которых в инвентаре на конец хода, дает бонусы в начале следующего хода
  * Аттрибуты - бонусы к существующим параметрам
    * ![Лечение](/img/items/x16/lime_dye.png) Лечение ![Сырое мясо](/img/items/x16/beef.png) (Количество получаемых ХП с разрушения)
    * ![Действие](/img/items/x16/light_blue_dye.png) Действие ![Пшеница](/img/items/x16/wheat.png) (Дополнительное действие, игнорирующее текущее ограничение)
    * ![Урон](/img/items/x16/red_dye.png) Урон ![Стрела](/img/items/x16/arrow.png) (Количество разрушаемых блоков)
  * Не больше 3 Аттрибутов одновременно

* **Функциональный предмет** - предметы, расширяющие возможности игры
  * Верстак ![Верстак](/img/blocks/x16/crafting_table_side.png) - дает расширенные крафты, пока находится на поле
  * Печка ![Печка](/img/blocks/x16/furnace_front.png) - дает расширенные крафты, пока находится на поле
  * Бочка ![Бочка](/img/blocks/x16/barrel_side.png) - дает 1 слот инвентаря, пока находится на поле
    * При уменьшении количества слотов, владелец инвентаря может выбрать предметы, которые останутся
  * Сундук ![Сундук](/img/blocks/x16/chest_front.png) - дает 3 слота инвентаря, пока находится на поле
    * При уменьшении количества слотов, владелец инвентаря может выбрать предметы, которые останутся

* **Инструменты** - предметы, упрощающие игру
  * Меч ![Меч](/img/items/x16/wooden_sword.png) - позволяет брать Сырое мясо ![Сырое мясо](/img/items/x16/beef.png)
  * Топор ![Топор](/img/items/x16/wooden_axe.png) - позволяет брать дополнительное Дерево ![Дерево](/img/blocks/x16/oak_log.png)
  * Кирка ![Кирка](/img/items/x16/wooden_pickaxe.png) - позволяет брать Камень ![Камень](/img/blocks/x16/stone.png)
  * Мотыга ![Мотыга](/img/items/x16/wooden_hoe.png) - позволяет брать Пшеницу ![Пшеница](/img/items/x16/wheat.png)
  * Щит ![Щит](/img/items/x16/shield_front.png) - поглощает одну атаку, принимая урон на себя
    * Срабатывает, если может быть разрушен во время текущей атаки
    * При срабатывании удаляется вместе с ХП, отменяя действие атаки
    * Может быть только один на игрока

* **Оружие** - предметы, имеющие действие атаки, и имеющие собственные параметры атаки
  * Меч ![Меч](/img/items/x16/wooden_sword.png)
    * Основная атака
      * Область 3х3 воркуг
      * Стоимость 1 Хлеб ![Хлеб](/img/items/x16/bread.png)
      * Разрушает 1 ХП
    * Критическая атака
      * Область 3х3 вокруг
      * Стоимость Жаренное мясо ![Жаренное мясо](/img/items/x16/cooked_beef.png)
      * Разрушает 4 ХП

  * Топор ![Топор](/img/items/x16/wooden_axe.png)
    * Основная атака
      * Область 3х3 вокруг
      * Стоимость 2 Хлеба ![Хлеб](/img/items/x16/bread.png) ![Хлеб](/img/items/x16/bread.png)
      * Разрушает 1 ХП
    * Критическая атака
      * Область 3х3 вокруг
      * Стоимость Жаренное мясо ![Жаренное мясо](/img/items/x16/cooked_beef.png)
      * Разрушает 8 ХП

  * Лук ![Лук](/img/items/x16/bow.png)
    * Основная атака
      * Неограниченная область
      * Стоимость Хлеб ![Хлеб](/img/items/x16/bread.png) за каждую Стрелу ![Стрела](/img/items/x16/arrow.png) И Стрелы ![Стрела](/img/items/x16/arrow.png)
      * Разрушает количество ХП, равное количеству израсходованных Стрел ![Стрела](/img/items/x16/arrow.png)
  * Арбалет ![Арбалет](/img/items/x16/crossbow_standby.png)
    * Основная атака
      * Неограниченная область
      * Стоимость Жаренное мясо ![Жаренное мясо](/img/items/x16/cooked_beef.png) И Стрела ![Стрела](/img/items/x16/arrow.png)
      * Разрушает линию ХП в любую сторону от Арбалета (45 градусов) ![Арбалет](/img/items/x16/crossbow_standby.png)

* **Еда** - дает большее количество ХП при разрушении, чем другие предметы
  * Сырое мясо ![Сырое мясо](/img/items/x16/beef.png) - **2**
  * Жаренное мясо ![Жаренное мясо](/img/items/x16/cooked_beef.png) - **5**
  * Хлеб ![Хлеб](/img/items/x16/bread.png) - **3**

**Механики**

* **Одно оружие** - можно иметь только один тип оружия на поле
  * При появлении другого типа оружия на поле, предыдущий тип должен быть удален
  * Перемещение "Поле <-> Инвентарь" между двумя типами оружия, удаляет оружие которое было перемещено с поля в инвентарь

* **Выпадение предметов** - после разрушения ХП, предмет внутр остается в той же ячейке на поле
  * Предмет может быть Добыт установкой на него ХП

---

**Крафты**

Требования | Ресурсы | Результат
-|-|-
[]()| ![Дерево](/img/blocks/x32/oak_log.png) | ![Верстак](/img/blocks/x32/crafting_table_front.png)
![Верстак](/img/blocks/x32/crafting_table_front.png)| ![Дерево](/img/blocks/x32/oak_log.png) | ![Бочка](/img/blocks/x32/barrel_side.png) ИЛИ ![Кирка](/img/items/x32/wooden_pickaxe.png) ИЛИ ![Мотыга](/img/items/x32/wooden_hoe.png) ИЛИ ![Стрела](/img/items/x32/arrow.png)
![Верстак](/img/blocks/x32/crafting_table_front.png)| ![Дерево](/img/blocks/x32/oak_log.png) ![Дерево](/img/blocks/x32/oak_log.png) | ![Сундук](/img/blocks/x32/chest_front.png) ИЛИ ![Меч](/img/items/x32/wooden_sword.png) ИЛИ ![Топор](/img/items/x32/wooden_axe.png) ИЛИ ![Лук](/img/items/x32/bow.png) ИЛИ ![Арбалет](/img/items/x32/crossbow_standby.png)
![Верстак](/img/blocks/x32/crafting_table_front.png)| ![Меч](/img/items/x32/wooden_sword.png) | ![Топор](/img/items/x32/wooden_axe.png) ИЛИ ![Лук](/img/items/x32/bow.png) ИЛИ ![Арбалет](/img/items/x32/crossbow_standby.png)
![Верстак](/img/blocks/x32/crafting_table_front.png)| ![Топор](/img/items/x32/wooden_axe.png) | ![Меч](/img/items/x32/wooden_sword.png) ИЛИ ![Лук](/img/items/x32/bow.png) ИЛИ ![Арбалет](/img/items/x32/crossbow_standby.png)
![Верстак](/img/blocks/x32/crafting_table_front.png)| ![Лук](/img/items/x32/bow.png) | ![Меч](/img/items/x32/wooden_sword.png) ИЛИ ![Топор](/img/items/x32/wooden_axe.png) ИЛИ ![Арбалет](/img/items/x32/crossbow_standby.png)
![Верстак](/img/blocks/x32/crafting_table_front.png)| ![Арбалет](/img/items/x32/crossbow_standby.png) | ![Меч](/img/items/x32/wooden_sword.png) ИЛИ ![Топор](/img/items/x32/wooden_axe.png) ИЛИ ![Лук](/img/items/x32/bow.png)
![Верстак](/img/blocks/x32/crafting_table_front.png)| ![Пшеница](/img/items/x32/wheat.png) | ![Хлеб](/img/items/x32/bread.png)
![Верстак](/img/blocks/x32/crafting_table_front.png)| ![Камень](/img/blocks/x32/stone.png) | ![Печка](/img/blocks/x32/furnace_front.png)
![Печка](/img/blocks/x32/furnace_front.png)| ![Дерево](/img/blocks/x32/oak_log.png) ![Камень](/img/blocks/x32/stone.png) | ![Щит](/img/items/x32/shield_front.png)
![Печка](/img/blocks/x32/furnace_front.png)| ![Дерево](/img/blocks/x32/oak_log.png) ![Сырое мясо](/img/items/x32/beef.png) | ![Жаренное мясо](/img/items/x32/cooked_beef.png)
</details>