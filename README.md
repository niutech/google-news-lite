# Google News Lite

The lightweight version of Google News using Google Web Light and YQL.

Google News is a 2 MB progressive web app full of JavaScript, which takes a lot of time to load on slow networks or slow devices, uses  precious data plan and is not compatible with Opera Mini (extreme mode).

See how Google News front page looks like in Opera Mini on iOS (left) and compare it with Google News Lite (right):

![Google News (left) and Google News Lite (right) in Opera Mini on iOS](https://i.imgur.com/uyZDtCQ.png)

Google News Lite fixes it by loading a YQL-proxified Google News front page using Google Web Light, which makes it only 38 KB! It also fixes CSS `overflow: hidden` and removes unsupported Material Icons, so that it looks fine in Opera Mini.

See Google News Lite in action: [Default language](https://niutech.github.io/google-news-lite/), [English](https://niutech.github.io/google-news-lite/?hl=en-US&gl=US&ceid=US:en), [Spanish](https://niutech.github.io/google-news-lite/?hl=es-419&gl=US&ceid=US:es-419), [Polish](https://niutech.github.io/google-news-lite/?hl=pl&gl=PL&ceid=PL:pl), [German](https://niutech.github.io/google-news-lite/?hl=de&gl=DE&ceid=DE:de), [French](https://niutech.github.io/google-news-lite/?hl=fr&gl=FR&ceid=FR:fr), [Hindi](https://niutech.github.io/google-news-lite/?hl=hi&gl=IN&ceid=IN:hi).

You can change the language by appending your language code to the URL, e.g. https://niutech.github.io/google-news-lite/?hl=pl.

For now, Google News Lite does not support signing in and is not compatible with my web extension [Fixer for Google News](https://github.com/niutech/google-news-fixer/).

## Notice

This service is provided "as is" and it is not affiliated with Google.

Google News is a trademark of Google.

## License

© 2018 Jerzy Głowacki under GNU GPL 3 License.
