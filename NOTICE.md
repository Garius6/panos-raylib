# NOTICE

Этот пакет — FFI-биндинги (`внешний`/`ff_структура`) к
[raylib](https://www.raylib.com/) для языка panos. Не порт OneScript-
библиотеки (в отличие от gitrunner/v8runner/v8storage/tempfiles/
скобки/cli/configor/cli-selector в этой же организации) — оригинальный
код, написанный с нуля против C API raylib.

Сам raylib НЕ распространяется вместе с этим пакетом и не копируется в
исходники — только объявления вызовов динамической библиотеки
(`внешний`), которую пользователь ставит отдельно (`brew install
raylib`). raylib лицензирован под [zlib license](https://github.com/raysan5/raylib/blob/master/LICENSE)
(Ramon Santamaria).

Собственный код этого пакета (биндинги + demo `pong.ps`) лицензирован по
MIT — см. `LICENSE`.
