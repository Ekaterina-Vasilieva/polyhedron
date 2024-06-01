# Изображение проекции полиэдра

Построение изображения полиэдра с удалением невидимых линий — пример
классической задачи, для успешного решения которой необходимо знакомство
с основами вычислительной геометрии.

![image](https://github.com/Ekaterina-Vasilieva/polyhedron/assets/165666931/9d9e6440-a1c0-4bd5-9b18-6e05f5e5b0f8)

## Проверка соблюдения соглашений о стиле программного кода

~~~{.sh}
find . -name '*.py' -exec pycodestyle {} \;
~~~

## Проверка покрытия тестами кода программы

~~~{.sh}
python -B -m coverage run -m unittest discover tests && coverage report -m ; rm -f .coverage
~~~
