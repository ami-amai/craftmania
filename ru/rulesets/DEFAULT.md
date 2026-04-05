# НАБОР ПРАВИЛ ПО УМОЛЧАНИЮ

## [**RU**](/ru/rulesets/DEFAULT.md) | [EN](/en/rulesets/DEFAULT.md)

<details>
  <summary>
    <b> Основной набор </b>
  </summary>

## Основной набор

**Набор предметов**

* Ресурсы
  * Дерево ![Дерево](/img/icons/blocks/x16/oak_log.png)
  * Камень ![Камень](/img/icons/blocks/x16/stone.png)
  * Сырое мясо ![Сырое мясо](/img/icons/items/x16/beef.png)
  * Стрела ![Стрела](/img/icons/items/x16/arrow.png)
  * Мотыга ![Мотыга](/img/icons/items/x16/wooden_hoe.png)
* Функциональные предметы
  * Верстак ![Верстак](/img/icons/blocks/x16/crafting_table_side.png)
  * Бочка ![Бочка](/img/icons/blocks/x16/barrel_side.png)
  * Печка ![Печка](/img/icons/blocks/x16/furnace_front.png)
* Инструменты
  * Меч ![Меч](/img/icons/items/x16/wooden_sword.png)
  * Топор ![Топор](/img/icons/items/x16/wooden_axe.png)
  * Кирка ![Кирка](/img/icons/items/x16/wooden_pickaxe.png)
* Атакующие предметы
  * Меч ![Меч](/img/icons/items/x16/wooden_sword.png)
  * Топор ![Топор](/img/icons/items/x16/wooden_axe.png)
  * Лук ![Лук](/img/icons/items/x16/bow.png)
  * Щит ![Щит](/img/icons/items/x16/shield_front.png)
* Еда
  * Сырое мясо ![Сырое мясо](/img/icons/items/x16/beef.png)
  * Жаренное мясо ![Жаренное мясо](/img/icons/items/x16/cooked_beef.png)
  * Хлеб ![Хлеб](/img/icons/items/x16/bread.png)

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

* **Атака** - может быть выполнена одновременно с Перемещением по полю, атакующего предмета
  * требует некоторое количество ХП в инвентаре, перед атакой удаляет их

* **Разрушение** - разрушение любого предмета кроме Еды дает 1 ХП

**Предметы**

* **Ресурсы** - предметы, расходуемые для каких-либо действий

* **Функциональный предмет** - предметы, расширяющие возможности игры
  * Верстак ![Верстак](/img/icons/blocks/x16/crafting_table_side.png) - дает расширенные крафты, пока находится на поле
  * Печка ![Печка](/img/icons/blocks/x16/furnace_front.png) - дает расширенные крафты, пока находится на поле
  * Бочка ![Бочка](/img/icons/blocks/x16/barrel_side.png) - дает 2 слота инвентаря, пока находится на поле
    * При уменьшении количества слотов, владелец инвентаря может выбрать предметы, которые останутся

* **Инструменты** - предметы, упрощающие игру
  * Меч ![Меч](/img/icons/items/x16/wooden_sword.png) - позволяет брать Сырое мясо
  * Топор ![Топор](/img/icons/items/x16/wooden_axe.png) - уменьшает количетсво необходимого Дерева в крафтах на 1
  * Кирка ![Кирка](/img/icons/items/x16/wooden_pickaxe.png) - позволяет брать Камень

* **Атакующие предметы** - предметы, имеющие действие атаки, и имеющие собственные параметры атаки
  * Меч ![Меч](/img/icons/items/x16/wooden_sword.png)
    * Область 3х3 вокруг меча в конечной точке перемещения
    * Типы атаки:
      * Основная
        * Стоимость **5**
        * Разрушает 2 ХП
      * Дополнительная
        * Стоимость **3**
        * Разрушает 1 ХП

  * Топор ![Топор](/img/icons/items/x16/wooden_axe.png)
    * Область 3х3 вокруг меча в конечной точке перемещения
    * Типы атаки:
      * Основная
        * Стоимость **6**
        * Разрушает 8 ХП

  * Лук ![Лук](/img/icons/items/x16/bow.png)
    * Область неограниченная
    * Типы атаки:
      * Основная
        * Стоимость **4**
        * Разрушает 1 ХП
        * Требует 1 стрелу на поле, удаляется после атаки

  * Щит ![Щит](/img/icons/items/x16/shield_front.png)
    * Область чужой производимой атаки
    * Поглощает весь урон атаки, удаляется вместе со своим ХП при срабатывании

* **Еда** - дает большее количество ХП при разрушении, чем другие предметы
  * Сырое мясо ![Сырое мясо](/img/icons/items/x16/beef.png) - **2**
  * Жаренное мясо ![Жаренное мясо](/img/icons/items/x16/cooked_beef.png) - **5**
  * Хлеб ![Хлеб](/img/icons/items/x16/bread.png) - **3**

**Механики**

* **Одно оружие** - в моменте, можно иметь только один тип Атакующего предмета
  * При получении другого типа, все Атакующие предметы предыдущего типа должны быть удалены

* **Поднятие предметов** - возможность атакующему, после атаки, взять любые предметы с разрушенных ХП себе в инвентарь
  * Не поднятые предметы будут удалены

---

**Крафты**

Требования | Ресурсы | Результат
-|-|-
[]()| ![Дерево](/img/icons/blocks/x32/oak_log.png) ![Дерево](/img/icons/blocks/x32/oak_log.png) | ![Верстак](/img/icons/blocks/x32/crafting_table_front.png) ИЛИ ![Бочка](/img/icons/blocks/x32/barrel_side.png)
![Верстак](/img/icons/blocks/x32/crafting_table_front.png)| ![Дерево](/img/icons/blocks/x32/oak_log.png) | ![Верстак](/img/icons/blocks/x32/crafting_table_front.png) ИЛИ ![Бочка](/img/icons/blocks/x32/barrel_side.png) ИЛИ ![Меч](/img/icons/items/x32/wooden_sword.png) ИЛИ ![Топор](/img/icons/items/x32/wooden_axe.png) ИЛИ ![Кирка](/img/icons/items/x32/wooden_pickaxe.png) ИЛИ ![Мотыга](/img/icons/items/x32/wooden_hoe.png) ИЛИ ![Лук](/img/icons/items/x32/bow.png) ИЛИ ![Стрела](/img/icons/items/x32/arrow.png)
![Верстак](/img/icons/blocks/x32/crafting_table_front.png)| ![Мотыга](/img/icons/items/x32/wooden_hoe.png) | ![Хлеб](/img/icons/items/x32/bread.png)
![Верстак](/img/icons/blocks/x32/crafting_table_front.png)| ![Камень](/img/icons/blocks/x32/stone.png) | ![Печка](/img/icons/blocks/x32/furnace_front.png)
![Печка](/img/icons/blocks/x32/furnace_front.png)| ![Дерево](/img/icons/blocks/x32/oak_log.png) ![Камень](/img/icons/blocks/x32/stone.png) | ![Щит](/img/icons/items/x32/shield_front.png)
![Печка](/img/icons/blocks/x32/furnace_front.png)| ![Дерево](/img/icons/blocks/x32/oak_log.png) ![Сырое мясо](/img/icons/items/x32/beef.png) | ![Жаренное мясо](/img/icons/items/x32/cooked_beef.png)
