# Эссе `F#`

---

`Мельников Владимир Владимирович`

`367390`

`P3310`

---
## Мотивация

Я долго думал, что же я хочу сделать. Делать ничего не хотелось, пришлось думать. Я подумал и решил что будет неплохой идеей попробывать написать простой аудиокодек, особенно учитывая что я уже работал с аудиоданными из WAV файлов, а так же (не очень глубоко) разбирался с устройством MP3.

Так как мест на Haskell и Erlang/Elixir не осталось, а Clojure мне не нравится, среди возможных языков оставались F#, OCaml, Coq и лиспы. 
По совету проверенных камрадов я сузил свой взор до Ocaml и F# и остановился на F#. Хотя OCaml также рассматривался как альтернатива, я выбрал F# из-за его интеграции с .NET. Это предоставляет доступ к обширной экосистеме библиотек и инструментов, что значительно упрощает разработку. .NET предлагает множество полезных функций, которые могут ускорить процесс создания аудиокодека.

## Инструменты

[Ionide ecosystem](https://ionide.io/):

- Linter - [FSharpLint](https://github.com/fsprojects/FSharpLint)
- Formatter - [Fantomas](https://fsprojects.github.io/fantomas/docs/index.html)

Compiler, runtime: .NET Core SDK, .NET Core Runtime and etc.

Tests: [FsUnit](https://fsprojects.github.io/FsUnit/) + NUnit + (maybe [FsCheck](https://fscheck.github.io/FsCheck/))

## Книги

[F# Microsoft documentation](https://learn.microsoft.com/en-us/dotnet/fsharp/)

[Essential F# Ian Russell 2021-2022](https://drive.google.com/file/d/1KQ8MRE8Ntl28t8qOA7qfswXHh-HgyQkl/view)



