# Курс &#8212; [Python: основы и применение](https://stepik.org/course/512)

**Оглавление:**
- [XML, библиотека ElementTree, библиотека lxml](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#xml-%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0-elementtree-%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0-lxml)
- [API сайта artsy.net](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#api-%D1%81%D0%B0%D0%B9%D1%82%D0%B0-artsynet)
- [API сайта numbersapi.com](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#api-%D1%81%D0%B0%D0%B9%D1%82%D0%B0-numbersapicom)
- [Введение в API для Python](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#%D0%B2%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2-api-%D0%B4%D0%BB%D1%8F-python)
- [Пример обработки CSV файлов](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80-%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B8-csv-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2)
- [Описание наследования классов в формате JSON](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BD%D0%B0%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%BE%D0%B2-%D0%B2-%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B5-json)
- [Пример использования стороннего модуля](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D1%81%D1%82%D0%BE%D1%80%D0%BE%D0%BD%D0%BD%D0%B5%D0%B3%D0%BE-%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D1%8F)
- [Собственные исключения](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#%D1%81%D0%BE%D0%B1%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5-%D0%B8%D1%81%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D0%B8%D1%8F)
- [Эмулятор отлова исключений](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#%D1%8D%D0%BC%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80-%D0%BE%D1%82%D0%BB%D0%BE%D0%B2%D0%B0-%D0%B8%D1%81%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D0%B8%D0%B9)
- [Пример множественного наследования](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80-%D0%BC%D0%BD%D0%BE%D0%B6%D0%B5%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D0%BE%D0%B3%D0%BE-%D0%BD%D0%B0%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)
- [Расширенный стек](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#%D1%80%D0%B0%D1%81%D1%88%D0%B8%D1%80%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9-%D1%81%D1%82%D0%B5%D0%BA)
- [Эмулятор наследования классов](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#%D1%8D%D0%BC%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80-%D0%BD%D0%B0%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%BE%D0%B2)
- [Реализация класса `Buffer`](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F-%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%B0-buffer)
- [Реализация класса `MoneyBox`](https://github.com/BotSaibot/pract_python_basics_and_applications/blob/main/README.md#%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F-%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%B0-moneybox)
- [Эмулятор пространства имен](#%D1%8D%D0%BC%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80-%D0%BF%D1%80%D0%BE%D1%81%D1%82%D1%80%D0%B0%D0%BD%D1%81%D1%82%D0%B2%D0%B0-%D0%B8%D0%BC%D0%B5%D0%BD)

## [XML, библиотека ElementTree, библиотека lxml]()
Вам дано описание пирамиды из кубиков в формате XML.
Кубики могут быть трех цветов: красный (**red**), зеленый (**green**) и синий (**blue**).
Для каждого кубика известны его цвет, и известны кубики, расположенные прямо под ним.

**Пример**:
```xml
<cube color="blue">
  <cube color="red">
    <cube color="green">
    </cube>
  </cube>
  <cube color="red">
  </cube>
</cube>
```
Введем понятие ценности для кубиков. Самый верхний кубик, соответствующий корню XML документа имеет ценность **1**. Кубики, расположенные прямо под ним, имеют ценность **2**. Кубики, расположенные прямо под нижележащими кубиками, имеют ценность **3**. И т. д.

Ценность цвета равна сумме ценностей всех кубиков этого цвета.

Выведите через пробел три числа: ценности красного, зеленого и синего цветов.

Sample Input:
```
\<cube color="blue">\<cube color="red">\<cube color="green">\</cube>\</cube>\<cube color="red">\</cube>\</cube>
```
Sample Output:
```
4 3 1
```

### Решение
```python
from lxml import etree


def el_value(tree, out):
    for el in tree.iter('cube'):
        val = 1
        par = el.getparent()
        while par is not None:
            par = par.getparent()
            val += 1
        out[el.get('color')] += val
    return out


def main():
    data = '''
    <cube color="blue">
        <cube color="red">
            <cube color="green">
            </cube>
        </cube>
        <cube color="red">
        </cube>
    </cube>
    '''

    out = el_value(etree.fromstring(data, etree.XMLParser()),
                   {'red': 0, 'green': 0, 'blue': 0})

    print(*out.values())


if __name__ == '__main__':
    main()

```

## [API сайта artsy.net]()
API проекта Artsy предоставляет информацию о некоторых деятелях искусства, их работах, выставках.

В рамках данной задачи вам понадобятся сведения о деятелях искусства (назовем их, условно, художники).

Вам даны идентификаторы художников в базе Artsy.
Для каждого идентификатора получите информацию о имени художника и годе рождения.
Выведите имена художников в порядке неубывания года рождения. В случае если у художников одинаковый год рождения, выведите их имена в лексикографическом порядке.

**Работа с API Artsy**

Полностью открытое и свободное API предоставляют совсем немногие проекты. В большинстве случаев, для получения доступа к API необходимо зарегистрироваться в проекте, создать свое приложение, и получить уникальный ключ (или токен), и в дальнейшем все запросы к API осуществляются при помощи этого ключа.

Чтобы начать работу с API проекта Artsy, вам необходимо пройти на стартовую страницу документации к API https://developers.artsy.net/v2/start и выполнить необходимые шаги, а именно зарегистрироваться, создать приложение, и получить пару идентификаторов **Client Id** и **Client Secret**. Не публикуйте эти идентификаторы.

После этого необходимо получить токен доступа к API. На стартовой странице документации есть примеры того, как можно выполнить запрос и как выглядит ответ сервера. Мы приведем пример запроса на Python.
```python
import requests
import json

client_id = '...'
client_secret = '...'

# инициируем запрос на получение токена
r = requests.post("https://api.artsy.net/api/tokens/xapp_token",
                  data={
                      "client_id": client_id,
                      "client_secret": client_secret
                  })

# разбираем ответ сервера
j = json.loads(r.text)

# достаем токен
token = j["token"]
```
Теперь все готово для получения информации о художниках. На стартовой странице документации есть пример того, как осуществляется запрос и как выглядит ответ сервера. Пример запроса на Python.
```python
# создаем заголовок, содержащий наш токен
headers = {"X-Xapp-Token" : token}
# инициируем запрос с заголовком
r = requests.get("https://api.artsy.net/api/artists/4d8b92b34eb68a1b2c0003f4", headers=headers)

# разбираем ответ сервера
j = json.loads(r.text)
```

**Примечание**:

В качестве имени художника используется параметр **sortable_name** в кодировке **UTF-8**.

**Примечание для пользователей Windows**

При открытии файла для записи на Windows по умолчанию используется кодировка CP1251, в то время как для записи имен на сайте используется кодировка UTF-8, что может привести к ошибке при попытке записать в файл имя с необычными символами. Вы можете использовать **print**, или аргумент encoding функции **open**.

Пример входных данных:
```
4d8b92b34eb68a1b2c0003f4
537def3c139b21353f0006a6
4e2ed576477cc70001006f99
```
Пример выходных данных:
```
Abbott Mary
Warhol Andy
Abbas Hamra
```

### Решение
```python
import requests
from time import perf_counter, sleep


def it_per(max_i, time):
    t_start = perf_counter()
    i_count = 0
    while True:
        time_delta = perf_counter() - t_start
        if time_delta > time or i_count == max_i:
            if not time_delta > time:
                sleep(time - time_delta)
            t_start = perf_counter()
            i_count = 1
        else:
            i_count += 1
        yield


def main():
    client_id = '5c77a508fffc947ef338'
    client_secret = '60ce486175f865c0b532d3db8fe2b806'
    r = requests.post("https://api.artsy.net/api/tokens/xapp_token",
                      data={
                          "client_id": client_id,
                          "client_secret": client_secret
                      })
    j = r.json()
    token = j["token"]

    with open('/content/artists_id.txt') as inf:
        artists_id = inf.read().strip().split()

    artists_data = []
    headers = {'X-Xapp-Token': token}
    limiter = it_per(4, 1)

    for id in artists_id:
        next(limiter)
        r = requests.get(f'https://api.artsy.net/api/artists/{id}',
                         headers=headers)
        j = r.json()
        artists_data.append([j['sortable_name'], j['birthday']])

    artists_data.sort(key=lambda x: x[1] + x[0])
    print(*[name for name, birthday in artists_data], sep='\n')


if __name__ == '__main__':
    main()

```

## [API сайта numbersapi.com]()
Вам дается набор чисел. Для каждого из чисел необходимо узнать, существует ли интересный математический факт об этом числе.

Для каждого числа выведите **Interesting**, если для числа существует интересный факт, и **Boring** иначе.
Выводите информацию об интересности чисел в таком же порядке, в каком следуют числа во входном файле.

Пример запроса к интересному числу:<br>
http://numbersapi.com/31/math?json=true

Пример запроса к скучному числу:<br>
http://numbersapi.com/999/math?json=true

Пример входного файла:
```
31
999
1024
502
```
Пример выходного файла:
```
Interesting
Boring
Interesting
Boring
```

### Решение
```python
import requests


def main():
    with open('/content/dataset_nums.txt', 'r') as inf:
        str_in = inf.read().strip()

    nums = str_in.replace('\n', ',')
    params = {'json': True, 'default': 'Boring'}
    res = requests.get(f'http://numbersapi.com/{nums}/math', params)
    data = res.json()

    for num in str_in.split():
        data_line = data[num]
        if data_line != 'Boring':
            print('Interesting')
        else:
            print(data_line)

if __name__ == '__main__':
    main()

```

## [Введение в API для Python]()
Данный вводный пример использования API демонстрирует реализацию мониторинга погоды в любом городе мира.

### Решение
```python
import requests


def main():
    c_name = 'Voronezh'
    api_url = 'https://api.openweathermap.org/data/2.5/weather'
    param = {
        'q': c_name,
        'appid': '11c0d3dc6093f7442898ee49d2430d20',
        'units': 'metric'
    }
    res = requests.get(api_url, param)
    print(res.status_code)
    data = res.json()
    print(data['main']['temp'])
    print(
        f'''Current temperature in {c_name} is {data['main']['temp']}\u00B0C '''
        f'''feels like {data['main']['feels_like']}\u00B0C''')


if __name__ == '__main__':
    main()

```

## [Пример обработки CSV файлов]()
Вам дана частичная выборка из датасета зафиксированных преступлений, совершенных в городе Чикаго с 2001 года по настоящее время.

Одним из атрибутов преступления является его тип – **Primary Type**.

Вам необходимо узнать тип преступления, которое было зафиксировано максимальное число раз в 2015 году.

### Решение
```python
import csv


with open('/content/Crimes.csv', 'r') as inf:
    arr = []
    for i in csv.reader(inf):
        if '2015' in i[2]:
            f = True
            for el in arr:
                if el[0] == i[5]:
                    arr[arr.index(el)] = [el[0], el[1] + 1]
                    f = False
                    break
            if f:
                arr.append([i[5], 1])


if __name__ == '__main__':
    print(*sorted(arr, key=lambda el: el[1], reverse=True), sep='\n')

```

## [Описание наследования классов в формате JSON]()
Описание представляет из себя массив JSON-объектов, которые соответствуют классам. У каждого JSON-объекта есть поле **name**, которое содержит имя класса, и поле **parents**, которое содержит список имен прямых предков.

**Пример**:

[{"name": "A", "parents": []}, {"name": "B", "parents": ["A", "C"]}, {"name": "C", "parents": ["A"]}]

Эквивалент на Python:
```python
class A:
    pass

class B(A, C):
    pass

class C(A):
    pass
```
Гарантируется, что никакой класс не наследуется от себя явно или косвенно, и что никакой класс не наследуется явно от одного класса более одного раза.

Для каждого класса вычислите предком скольких классов он является и выведите эту информацию в следующем формате.

**<имя класса> : <количество потомков>**

Выводить классы следует в лексикографическом порядке.

Sample Input:
```
[{"name": "A", "parents": []}, {"name": "B", "parents": ["A", "C"]}, {"name": "C", "parents": ["A"]}]
```
Sample Output:
```
A : 3
B : 1
C : 2
```

### Решение
```python
import json


def find_el(name, tree) -> dict or None:
    '''Найти елемент в дереве'''
    res = [el for el in tree if el['name'] == name]
    if res:
        return res[0]
    return None


def parents_list(name, tree) -> list:
    '''Лист родителей `name`'''
    r = [name]
    i = 0
    while i < len(r):
        [r.append(el) for el in find_el(r[i], tree)['parents'] if el not in r]
        i += 1
    return r


def main():
    jsonin = json.loads('[{"name": "B", "parents": ["A", "C"]}, '
                        '{"name": "C", "parents": ["A"]}, '
                        '{"name": "A", "parents": []}, '
                        '{"name": "D", "parents":["C", "F"]}, '
                        '{"name": "E", "parents":["D"]}, '
                        '{"name": "F", "parents":[]}]')
    arr_out = []
    [arr_out.extend(parents_list(el['name'], jsonin)) for el in jsonin]
    for el in sorted(jsonin, key=lambda x: x['name']):
        print(el['name'], ':', arr_out.count(el['name']))


if __name__ == '__main__':
    main()

```

## [Пример использования стороннего модуля]()
В первой строке дано три числа, соответствующие некоторой дате **date** -- год, месяц и день.
Во второй строке дано одно число **days** -- число дней.

Вычислите и выведите год, месяц и день даты, которая наступит, когда с момента исходной даты **date** пройдет число дней, равное **days**.

**Примечание**:

Для решения этой задачи используйте стандартный модуль **datetime**.
Вам будут полезны класс **datetime.date** для хранения даты и класс **datetime.timedelta** для прибавления дней к дате.

Sample Input 1:
```
2016 4 20
14
Sample Output 1:
2016 5 4
```
Sample Input 2:
```
2016 2 20
9
Sample Output 2:
2016 2 29
```
Sample Input 3:
```
2015 12 31
1
Sample Output 3:
2016 1 1
```

### Решение
```python
import datetime

[
    print(int(y), int(m), int(d)) for y, m, d in [
        (
            datetime.date(
                *[int(i) for i in input().split()]
            ) + datetime.timedelta(int(input()))
        ).isoformat().split('-')
    ]
]

```

## [Собственные исключения]()
Реализуйте класс **PositiveList**, отнаследовав его от класса **list**, для хранения положительных целых чисел.
Также реализуйте новое исключение **NonPositiveError**.

В классе **PositiveList** переопределите метод **append(self, x)** таким образом, чтобы при попытке добавить неположительное целое число бросалось исключение **NonPositiveError** и число не добавлялось, а при попытке добавить положительное целое число, число добавлялось бы как в стандартный **list**.

В данной задаче гарантируется, что в качестве аргумента **x** метода **append** всегда будет передаваться целое число.

**Примечание**:

Положительными считаются числа, **строго большие** нуля.

### Решение
```python
class NonPositiveError(Exception):
    pass

class PositiveList(list):
    def append(self, added_object) -> None:
        if added_object > 0:
            return super().append(added_object)
        else:
            raise NonPositiveError(f'{added_object} is not positive')

```

## [Эмулятор отлова исключений]()
Вам дано описание наследования классов исключений в следующем формате.
**<имя исключения 1> : <имя исключения 2> <имя исключения 3> ... <имя исключения k>**<br>
Это означает, что **исключение 1** наследуется от **исключения 2**, **исключения 3**, и т. д.

Или эквивалентно записи:
```python
class Error1(Error2, Error3 ... ErrorK):
    pass
```
Антон написал код, который выглядит следующим образом.
```python
try:
   foo()
except <имя 1>:
   print("<имя 1>")
except <имя 2>:
   print("<имя 2>")
...
```
Костя посмотрел на этот код и указал Антону на то, что некоторые исключения можно не ловить, так как ранее в коде будет пойман их предок. Но Антон не помнит какие исключения наследуются от каких. Помогите ему выйти из неловкого положения и напишите программу, которая будет определять обработку каких исключений можно удалить из кода.

**Важное примечание**:

В отличие от предыдущей задачи, типы исключений не созданы.
Создавать классы исключений также не требуется
Мы просим вас промоделировать этот процесс, и понять какие из исключений можно и не ловить, потому что мы уже ранее где-то поймали их предка.

**Формат входных данных**

В первой строке входных данных содержится целое число **n** - число классов **исключений**.

В следующих **n** строках содержится описание наследования классов. В **i**-й строке указано от каких классов наследуется **i**-й класс. Обратите внимание, что класс может ни от кого не наследоваться. Гарантируется, что класс не наследуется сам от себя (прямо или косвенно), что класс не наследуется явно от одного класса более одного раза.

В следующей строке содержится число **m** - количество обрабатываемых исключений.
Следующие **m** строк содержат имена исключений в том порядке, в каком они были написаны у Антона в коде.
Гарантируется, что никакое исключение не обрабатывается дважды.

**Формат выходных данных**

Выведите в отдельной строке имя каждого исключения, обработку которого можно удалить из кода, не изменив при этом поведение программы. Имена следует выводить в том же порядке, в котором они идут во входных данных.

**Пример теста 1**

Рассмотрим код
```python
try:
   foo()
except ZeroDivision :
   print("ZeroDivision")
except OSError:
   print("OSError")
except ArithmeticError:
   print("ArithmeticError")
except FileNotFoundError:
   print("FileNotFoundError")


...
```

По условию этого теста, Костя посмотрел на этот код, и сказал Антону, что исключение FileNotFoundError можно не ловить, ведь мы уже ловим OSError -- предок FileNotFoundError

### Решение
```python
def is_parent(child, parent):
    return child == parent or any(map(
        lambda p: is_parent(p, parent),parents[child]))


def main():
    n = int(input())

    parents = {}
    for _ in range(n):
        a = input().split()
        parents[a[0]] = [] if len(a) == 1 else a[2:]

    q = int(input())
    log = []
    for _ in range(q):
        a = input()
        if any(is_parent(a, i) for i in log):
            print(a)
        log.append(a)


if __name__ == '__main__':
    main()

```

## [Пример множественного наследования]()
Одно из применений множественного наследование – расширение функциональности класса каким-то заранее определенным способом. Например, если нам понадобится логировать какую-то информацию при обращении к методам класса.

Рассмотрим класс **Loggable**:
```python
import time

class Loggable:
    def log(self, msg):
        print(str(time.ctime()) + ": " + str(msg))
```
У него есть ровно один метод **log**, который позволяет выводить в лог (в данном случае в stdout) какое-то сообщение, добавляя при этом текущее время.
Реализуйте класс **LoggableList**, отнаследовав его от классов **list** и **Loggable** таким образом, чтобы при добавлении элемента в список посредством метода **append** в лог отправлялось сообщение, состоящее из только что добавленного элемента.

**Примечание**

Ваша программа не должна содержать класс Loggable. При проверке вашей программе будет доступен этот класс, и он будет содержать метод log, описанный выше.

### Решение
```python
class LoggableList(list, Loggable):
    def append(self, __object) -> None:
        self.log(__object)
        return super().append(__object)

```

## [Расширенный стек]()
Реализуйте структуру данных, представляющую собой расширенную структуру стек. Необходимо поддерживать добавление элемента на вершину стека, удаление с вершины стека, и необходимо поддерживать операции сложения, вычитания, умножения и целочисленного деления.

Операция сложения на стеке определяется следующим образом. Со стека снимается верхний элемент (**top1**), затем снимается следующий верхний элемент (**top2**), и затем как результат операции сложения на вершину стека кладется элемент, равный **top1** + **top2**.

Аналогичным образом определяются операции вычитания (**top1** - **top2**), умножения (**top1** $\times$ **top2**) и целочисленного деления (**top1** // **top2**).

Реализуйте эту структуру данных как класс **ExtendedStack**, отнаследовав его от стандартного класса **list**.
Требуемая структура класса:
```python
class ExtendedStack(list):
    def sum(self):
        # операция сложения

    def sub(self):
        # операция вычитания

    def mul(self):
        # операция умножения

    def div(self):
        # операция целочисленного деления

```

**Примечание**

Для добавления элемента на стек используется метод **append**, а для снятия со стека – метод **pop**.<br>
Гарантируется, что операции будут совершаться только когда в стеке есть хотя бы два элемента.

### Решение
```python
class ExtendedStack(list):
    def check(self) -> bool:
        '''Проверка для бинарных операций'''
        return len(self) > 1

    def sum(self):
        '''Операция сложения'''
        if self.check():
            self.append(self.pop() + self.pop())

    def sub(self):
        '''Операция вычитания'''
        if self.check():
            self.append(self.pop() - self.pop())

    def mul(self):
        '''Операция умножения'''
        if self.check():
            self.append(self.pop() * self.pop())

    def div(self):
        '''Операция целочисленного деления'''
        if self.check():
            self.append(self.pop() // self.pop())

```

## [Эмулятор наследования классов]()
Вам дано описание наследования классов в следующем формате.
**<имя класса 1> : <имя класса 2> <имя класса 3> ... <имя класса k>**
Это означает, что **класс 1** отнаследован от **класса 2**, **класса 3**, и т. д.

Или эквивалентно записи:
```python
class Class1(Class2, Class3 ... ClassK):
    pass
```
Класс **A** является **прямым предком** класса **B**, если **B** отнаследован от **A**:
```python
class B(A):
    pass
```
Класс **A** является **предком** класса **B**, если
**A** = **B**;
**A** - прямой предок **B**
существует такой класс **C**, что **C** - прямой предок **B** и **A** - предок **C**

Например:
```python
class B(A):
    pass

class C(B):
    pass

# A -- предок С

```

Вам необходимо отвечать на запросы, является ли один класс предком другого класса

**Важное примечание**:<br>
Создавать классы не требуется.<br>
Мы просим вас промоделировать этот процесс, и понять существует ли путь от одного класса до другого.

**Формат входных данных**

В первой строке входных данных содержится целое число **n** - число классов.

В следующих **n** строках содержится описание наследования классов. В **i**-й строке указано от каких классов наследуется **i**-й класс. Обратите внимание, что класс может ни от кого не наследоваться. Гарантируется, что класс не наследуется сам от себя (прямо или косвенно), что класс не наследуется явно от одного класса более одного раза.

В следующей строке содержится число **q** - количество запросов.

В следующих **q** строках содержится описание запросов в формате **<имя класса 1> <имя класса 2>**.
Имя класса – строка, состоящая из символов латинского алфавита, длины не более 50.

**Формат выходных данных**

Для каждого запроса выведите в отдельной строке слово `"Yes"`, если **класс 1** является предком **класса 2**, и `"No"`, если не является.

Sample Input:
```
4
A
B : A
C : A
D : B C
4
A B
B D
C D
D A
```

Sample Output:
```
Yes
Yes
Yes
No
```

### Решение
```python
def find_class(class_name: str, classes: list) -> list:
    '''Найти класс'''
    for el in classes:
        if class_name in el:
            return el
    return list()


def create_classes() -> list:
    '''Создать класс'''
    classes = list()
    for _ in range(int(input())):
        str_in = input().split()
        if ':' in str_in:
            str_in.remove(':')
            cur_class = find_class(str_in[0], classes)
            if cur_class:
                classes[classes.index(cur_class)][1] = str_in[1:]
            else:
                classes.append([str_in[0], str_in[1:]])
            for el in str_in[1:]:
                if not find_class(el, classes):
                    classes.append([el, list()])
        else:
            classes.append([str_in[0], list()])
    return classes


def isancestor(class_name1: str, class_name2: str, classes: list) -> str:
    '''Является ли `class_name1` предком `class_name2`'''
    ancestors = [class_name2]
    cur_index = 0
    while cur_index < len(ancestors):
        for el in find_class(ancestors[cur_index], classes)[1]:
            if el not in ancestors:
                ancestors.append(el)
        cur_index += 1
    if class_name1 in ancestors:
        return 'Yes'
    return 'No'


def testing_isancestor(classes: list):
    '''Тестирование `isancestor()`'''
    for _ in range(int(input())):
        str_in = input().split()
        print(isancestor(str_in[0], str_in[1], classes))


if __name__ == '__main__':
    lst_classes = create_classes()
    testing_isancestor(lst_classes)

```

## [Реализация класса `Buffer`]()
Реализуйте класс `Buffer`, который будет накапливать в себе элементы последовательности и выводить сумму пятерок последовательных элементов по мере их накопления.

Вам дается последовательность целых чисел и вам нужно ее обработать и вывести на экран сумму первой пятерки чисел из этой последовательности, затем сумму второй пятерки, и т. д.

Но последовательность не дается вам сразу целиком. С течением времени к вам поступают её последовательные части. Например, сначала первые три элемента, потом следующие шесть, потом следующие два и т. д.

Одним из требований к классу является то, что он не должен хранить в себе больше элементов, чем ему действительно необходимо, т. е. он не должен хранить элементы, которые уже вошли в пятерку, для которой была выведена сумма.

Класс должен иметь следующий вид
```python
class Buffer:
    def __init__(self):
        # конструктор без аргументов

    def add(self, *a):
        # добавить следующую часть последовательности

    def get_current_part(self):
        # вернуть сохраненные в текущий момент элементы последовательности в порядке, в котором они были
        # добавлены

```

Пример работы с классом
```python
buf = Buffer()
buf.add(1, 2, 3)
buf.get_current_part() # вернуть [1, 2, 3]
buf.add(4, 5, 6) # print(15) – вывод суммы первой пятерки элементов
buf.get_current_part() # вернуть [6]
buf.add(7, 8, 9, 10) # print(40) – вывод суммы второй пятерки элементов
buf.get_current_part() # вернуть []
buf.add(1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1) # print(5), print(5) – вывод сумм третьей и четвертой пятерки
buf.get_current_part() # вернуть [1]
```

Обратите внимание, что во время выполнения метода `add` выводить сумму пятерок может потребоваться несколько раз до тех пор, пока в буфере не останется менее пяти элементов.

### Решение
```python
class Buffer:
    def __init__(self):
        '''конструктор без аргументов'''
        self.storage = list()

    def add(self, *a):
        '''добавить следующую часть последовательности'''
        for i in a:
            self.storage.append(i)
            if len(self.storage) == 5:
                print(sum(self.storage))
                self.__init__()

    def get_current_part(self) -> list:
        '''вернуть сохраненные в текущий момент элементы последовательности в
         порядке, в котором они были добавлены'''
        return self.storage

```

## [Реализация класса `MoneyBox`]()
Каждая копилка имеет ограниченную вместимость, которая выражается целым числом – количеством монет, которые можно положить в копилку. Класс должен поддерживать информацию о количестве монет в копилке, предоставлять возможность добавлять монеты в копилку и узнавать, можно ли добавить в копилку ещё какое-то количество монет, не превышая ее вместимость.

Класс должен иметь следующий вид
```python
class MoneyBox:
    def __init__(self, capacity):
        # конструктор с аргументом – вместимость копилки

    def can_add(self, v):
        # True, если можно добавить v монет, False иначе

    def add(self, v):
        # положить v монет в копилку

```
При создании копилки, число монет в ней равно 0.

**Примечание**:

Гарантируется, что метод `add(self, v)` будет вызываться только если `can_add(self, v)` – `True`.

### Решение
```python
class MoneyBox:
    def __init__(self, capacity, value=0):
        '''Конструктор с аргументом – вместимость копилки'''
        self.capacity = capacity
        self.value = 0
        if value:
            self.add(value)

    def can_add(self, v) -> bool:
        '''`True`, если можно добавить `v` монет, `False` иначе'''
        return self.value + v <= self.capacity

    def add(self, v):
        '''Положить v монет в копилку'''
        if self.can_add(v):
            self.value += v

```

## [Эмулятор пространства имен]()
Вашей программе на вход подаются следующие запросы:

* **create \<namespace\> \<parent\>** –  создать новое пространство имен с именем **\<namespace\>** внутри пространства **\<parent\>**
* **add \<namespace\> \<var\>** – добавить в пространство **\<namespace\>** переменную **\<var\>**
* **get \<namespace\> \<var\>** – получить имя пространства, из которого будет взята переменная **\<var\>** при запросе из пространства **\<namespace\>**, или **None**, если такого пространства не существует

Sample Input:
```
9
add global a
create foo global
add foo b
get foo a
get foo c
create bar foo
add bar a
get bar a
get bar b
```

Sample Output:
```
global
None
bar
foo
```

### Решение
```python
def namespaces_create(name, parent, namespace) -> list:
    '''Создать новое пространство имен с именем `namespace` внутри
    пространства `parent`
    `namespaces_create('global', '', [])`
    создает глобальное пространство имен'''
    namespace.append([name, [], parent])
    return namespace

def namespaces_add(name, var, namespace):
    '''Добавить в пространство `namespace` переменную `var`'''
    for space in namespace:
        if name in space:
            space[1].append(var)
            break

def namespaces_find(name, namespace) -> list:
    '''Найти и вернуть первое вхождение `name` из `namespace`'''
    for space in reversed(namespace):
        if space[0] == name:
            return space
    return []

def namespaces_get(name, var, namespace) -> str:
    '''Получить имя пространства, из которого будет взята переменная `var`
    при запросе из пространства `namespace`, или None, если такого
    пространства не существует'''
    cur_ns = namespaces_find(name, namespace)
    if var in cur_ns[1]:
        return cur_ns[0]
    elif cur_ns[2] == '':
        return 'None'
    return namespaces_get(cur_ns[2], var, namespace)

def main():
    namespaces = namespaces_create('global', '', [])
    for cmd in inputs:
        if cmd[0] == 'add':
            namespaces_add(cmd[1], cmd[2], namespaces)
        elif cmd[0] == 'create':
            namespaces_create(cmd[1], cmd[2], namespaces)
        else:
            print(namespaces_get(cmd[1], cmd[2], namespaces))


if __name__ == '__main__':
    main()

```