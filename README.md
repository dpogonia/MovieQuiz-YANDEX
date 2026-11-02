**Русский** | [English](README.en.md)

# MovieQuiz

Викторина о фильмах для iPhone. Учебный проект курса iOS-разработки Яндекс Практикума.

Игрок смотрит постер и отвечает, выше ли рейтинг фильма на IMDb заданного числа. Раунд состоит из 10 вопросов. Постеры приходят из API IMDb.

## Ссылки

- [Макет в Figma](https://www.figma.com/file/l0IMG3Eys35fUrbvArtwsR/YP-Quiz?node-id=34%3A243)
- [API IMDb](https://tv-api.com/api#Top250Movies-header)
- [Шрифты](https://code.s3.yandex.net/Mobile/iOS/Fonts/MovieQuizFonts.zip)

## Что умеет приложение

На запуске показывается сплэш. Дальше вопрос, постер и две кнопки: «Да» и «Нет». Верный ответ подсвечивает рамку зелёным, неверный — красным. Следующий вопрос появляется через секунду.

После 10 вопросов алерт показывает результат раунда, число сыгранных игр, рекорд и среднюю точность. Раунд можно начать заново. Если данные не загрузились, алерт предлагает повторить запрос.

Рекорды и статистика хранятся на устройстве.

## Стек

UIKit, URLSession, UserDefaults, XCTest. Приложение рассчитано на iPhone с iOS 15, только портретная ориентация.

## Запуск

```bash
git clone https://github.com/dpogonia/MovieQuiz.git
cd MovieQuiz
open MovieQuiz.xcodeproj
```

Запустите схему **MovieQuiz** на симуляторе iPhone.

## Автор

[Dmitrii Pogonia](https://github.com/dpogonia)
