# stage_5_developer_roadmap
Препроцессор Sass/SCSS

* Установка через npm (npm install -g sass).
* Переменные ($primary-color), вложенность (&, &__element, &--modifier по БЭМ).
* Миксины (@mixin, @include) — для переиспользования наборов свойств.
* Функции (lighten, darken, rgba).
* Импорт/использование (@use, @forward).
* Циклы (@for, @each map-get($arr, key)).
* @extend — наследование стилей
* % — "молчаливый" класс
* Условные конструкции (@if, @else, @return)
* @at-root — выход из вложенности
* @debug, @warn, @error — отладка
* @use 'theme' with (
  $primary: red,
  $secondary: white
);
* $rand: random(100); // 0-100
* $slice: str-slice($text, 1, 5);
* Компиляция sass styles.scss output.css
* sass --watch src/styles:dist/css       |||||    sass --watch style.scss:style.css
