# Cubes

## Requirements

##### Необходимо сделать задание про ‘квадратики’ на React.

!["Cubes"](https://serving.photos.photobox.com/60086506f4f24a0b96554aa97484f82841dad4cb2d61a21bbd1082f5c332f3d81cf94984.jpg "Cubes")

1) Задача состоит в разработке пересипользуемого React компонента. Используем React последней версии (сейчас это 16.3).
2) Компонент должен иметь пропсы (в скобках указаны значения по умолчанию):
initialWidth (4) - начальная ширина таблицы (в ячейках)
initialHeight (4) - начальная высота таблицы (в ячейках)
cellSize (50) - размер ячейки в пикселях
3) Тестирование: используя Jest, Enzyme реализовать следующие тесты:
- пропсы initialWidth, initialHeight должны рендерить таблицу соответствующего размера
- кнопки ‘+‘ должны добавлять строку/столбец
- кнопки ‘-’ должны удалять строку/столбец
- кнопки ‘-’ не должны удалять последнюю строку/столбец