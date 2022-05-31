# Assignment 10. Brute-force Algorithms

[![Build Status](../../actions/workflows/classroom.yml/badge.svg)](../../actions/workflows/classroom.yml)
![Points bar](../../blob/badges/.github/badges/points-bar.svg)

## 1. Информация о студенте

**Номер группы**: 11-109

**Фамилия и Имя**: Юминов Денис

## 2. Описание задания

Используя подходы полного перебора, приведите решение к следующим задачам.

Подходы к реализации полного перебора:

- _bit-masking_ - характеристический вектор или битовая маска, описывающая отсутствие (0) или вхождение (1) элементов в
  рассматриваемое подмножество. Представляет собой итеративный проход по всем возможным решениям.
- _backtracking_ - поиск с возвратом. Используется рекурсия для рассмотрения и отсечения (возврат) непригодных решений.

### A. Subsets

Требуется реализовать генерацию всех возможных подмножеств некого множества.

```text
  Множество S = {1, 3}
  Подмножества: {}, {1}, {3}, {1, 3}
```

**Дополнительно**:

- подумайте, как реализовать наложение дополнительных ограничений к задаче (при _S = {1, 2, 3, 4}_)
  - мощность подмножества не более _3_
  - в подмножестве не должен встречаться элемент _2_
  - вывести только те подмножества, в которых обязательно есть элементы 2 и 4

### B. Subsets Sum

Требуется реализовать поиск всех возможных подмножеств множества, сумма элементов которых равна 
целевой сумме (_T_).

```text
Множество S = {1, 3, 2, 5, 10}
Целевая сумма T = 5

Подмножества: {3, 2}, {5}
```

**Дополнительно**:
- подумайте, как реализовать поиск всех подмножеств, сумма элементов которых наиболее близка к целевой сумме (_T_)

### C. 0/1 Knapsack

Является опциональной задачей на доп. баллы.

С описанием задачи можно ознакомиться по [ссылке](https://ru.wikipedia.org/wiki/%D0%97%D0%B0%D0%B4%D0%B0%D1%87%D0%B0_%D0%BE_%D1%80%D1%8E%D0%BA%D0%B7%D0%B0%D0%BA%D0%B5).

## 3. Инструкции

1. Склонируйте локальную копию репозитория к себе на компьютер.
2. Внесите информацию о себе в раздел "Информация о студенте".
3. Подробно изучите описание задания. При наличии вопросов обратитесь к <strike>врачу</strike> преподавателю.
4. Реализуйте задание в соответствии указанным требованиям.
5. Запустите локальные тесты (при их наличии).
6. Отправьте задание на auto-grading тесты и дождитесь итогового балла.
7. Повторите пункты 4-6 до получения макс. кол-ва баллов.

## 4. Ограничения

- Запрещается вносить изменения в файлы, не указанных в разделе "Описание задания".
- Запуск auto-grading тестов осуществляется:
    - автоматически при внесении изменений в [_src_](src) и/или [_include_](include)
      на ветках _**master**_ или _**main**_;
    - вручную во вкладке _Actions_.

## 5. Примечания

- Результирующие баллы высчитываются при каждом новом push'е (для последнего commit'а).
- По истечении установленных временных сроков сдачи система продолжит высчитывать итоговый балл при внесении изменений.
- Сроки сдачи устанавливаются преподавателем и указываются в индивидуальном порядке для каждой группы.
- Тесты подразделяются на **локальные** и **auto-grading**:
    - локальные тесты запускаются на компьютере через среду разработки (IDE);
    - auto-grading тесты запускаются на GitHub и вычисляют итоговый балл за задание.
- При клонировании репозитория через терминал используйте команду:
  ```shell
    git clone --recurse-submodules <URL>
  ```

---

**Преподаватель**: Рамиль Сафин (Telegram: [_@safin_ramil_](https://t.me/safin_ramil), e-mail: _safin.ramil@it.kfu.ru_).
