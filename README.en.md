[Русский](README.md) | **English**

# MovieQuiz

A film quiz for iPhone. A Yandex Practicum iOS course project.

The player sees a poster and answers whether the film's IMDb rating is higher than a given number. A round is 10 questions. Posters come from the IMDb API.

## Links

- [Figma design](https://www.figma.com/file/l0IMG3Eys35fUrbvArtwsR/YP-Quiz?node-id=34%3A243)
- [IMDb API](https://tv-api.com/api#Top250Movies-header)
- [Fonts](https://code.s3.yandex.net/Mobile/iOS/Fonts/MovieQuizFonts.zip)

## What it does

A splash screen opens first. Then a question, a poster, and two buttons: Yes and No. A correct answer turns the frame green, a wrong one turns it red. The next question appears after one second.

After 10 questions an alert shows the round result, games played, the record, and the average accuracy. The round can be started again. If the data fails to load, the alert offers another request.

Records and statistics stay on the device.

## Stack

UIKit, URLSession, UserDefaults, XCTest. The app targets iPhone on iOS 15, portrait only.

## Run

```bash
git clone https://github.com/dpogonia/MovieQuiz-Yandex.git
cd MovieQuiz-Yandex
open MovieQuiz.xcodeproj
```

Run the **MovieQuiz** scheme on an iPhone simulator.

## Author

[Dmitrii Pogonia](https://github.com/dpogonia)
