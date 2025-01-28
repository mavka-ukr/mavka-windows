# Мавка для Windows

```shell
mkdir build
cd build
cmake ..\..\external -G Ninja -DCMAKE_CXX_FLAGS=-fdiagnostics-color=always -DREADLINE_AVAILABLE=0
ninja
cd -

clang++ -municode -o build\mavka .плавлення\мавка\бібліотека\М.ll .плавлення\мавка\бібліотека\мавка.ll .плавлення\мавка\бібліотека\МаМа.ll .плавлення\мавка\бібліотека\читати_юнікод.ll .плавлення\мавка\компілятор.ll .плавлення\мавка\мавка.ll .плавлення\старт.ll .плавлення\МаМа\КД\КД.ll .плавлення\МаМа\біб.ll .плавлення\МаМа\Код.ll .плавлення\МаМа\Машина.ll .плавлення\МаМа\Назва.ll .плавлення\МаМа\Обʼєкт.ll .плавлення\МаМа\ОбʼєктБайтів.ll .плавлення\МаМа\ОбʼєктДії.ll .плавлення\МаМа\ОбʼєктЛогічного.ll .плавлення\МаМа\ОбʼєктМодуля.ll .плавлення\МаМа\ОбʼєктНативноїДії.ll .плавлення\МаМа\ОбʼєктСловника.ll .плавлення\МаМа\ОбʼєктСписку.ll .плавлення\МаМа\ОбʼєктСтруктури.ll .плавлення\МаМа\ОбʼєктТексту.ll .плавлення\МаМа\ОбʼєктЮнікоду.ll .плавлення\МаМа\ОбʼєктЧисла.ll .плавлення\МаМа\Помилка.ll .плавлення\МаМа\Середовище.ll .плавлення\МаМа\СкладенийОбʼєкт.ll .плавлення\МаМа\Утилізатор.ll buildxternal\libmavka_external.a buildxternal\mavka_parser\libmavka_parser.a buildxternal\mavka_parser\syntax\libmavka_syntax.a buildxternal\mavka_parser\syntaxntlr4-cpp-runtime\libantlr4_cpp_runtime.a
```
