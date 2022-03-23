
# 2.5 CollectionView

## Правила выполнения домашней работы:

* Присылать на проверку можно каждую задачу по отдельности или все задачи вместе. Во время проверки по частям ваша домашняя работа будет со статусом "На доработке".
* Любые вопросы по решению задач задавайте в чате Slack (ссылку вы найдете в письме на вашей эл. почте).
* **Для выполнения домашнего задания используйте проект из предыдущего домашнего задания**. Это означает, что вы его успешно сдали, а значит, в нем есть все последние изменения.
* **Ваше приложение должно полностью соответствовать макетам.** Не делайте ничего лишнего, это усложнит проверку Вашей работы.

## Оформление результата:

* Ознакомьтесь с [инструкцией по использованию Pull Request для сдачи дз](https://github.com/netology-code/iosui-homeworks/blob/iosui-8/Pull%20requests'%20guideline.md)
* При сдаче работы прикрепите в личный кабинет ссылку на Pull Request с выполненной работой


### Важно! 

## Фотографии:
Скачайте любые 20 фото и добавьте их в папку **Assets.xcassets**

## Макеты:
Макеты для верстки находятся по этой ссылке -> [Макеты](./2.5_Макеты)

## Алгоритм выполнения:

1. Создайте `PhotosTableViewCell.swift` c одноименным классом внутри.

2. Сделайте верстку согласно макету. В ячейке должно отображаться первые 4 фото.

3. Добавьте только что созданную ячейку в таблицу согласно позиции в макете. Рекомендую положить эту ячейку в отдельную секцию, так будет проще.

4. По тапу на ячейку должен быть осуществлен переход на экран "фото галереи". Показать экран нужно при помощи метода `UINavigationController.push(_ :)`

5. Создайте `PhotosViewController.swift` c одноименным классом внутри.

6. Добавьте в него экземпляр класса `UICollectionView` и растяните по краям согласно макету.

7. Добавьте для всей коллекции отступы, используя `UIEdgeInsets`. Размеры оступов берите из макета.

8. Ваша коллекция должна отображать ячейки таким образом, чтобы в одном ряду равнопропорционально разместилось три ячейки с фотографиями.

9. Создайте `PhotosCollectionViewCell.swift` с одноименным классом внутри.

10. Сделайте верстку ячейки согласно макету и добавьте ее в ранее созданную коллекцию.

11. При переходе на экран с коллекцией должен появляться `NavigationBar`. При уходе с экрана он должен исчезать. Используйте правильные методы жизненного цикла `UIViewController` и свойство `isHidden`.

