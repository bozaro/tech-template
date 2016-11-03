# tech-template
[Hugo](https://gohugo.io/) тема для презентаций Технопарка

## Пример использования

 - Готовые к просмотру слайды: https://bozaro.github.io/tech-db-lectures/
 - Исходный код: https://github.com/bozaro/tech-db-lectures

## Как создать презентацию?

Простой шаблон презентации можно взять из директории exampleSize.

После этого нужно:

 - Поправить название презентации и контактные данные в `config.yaml`;
 - Заменить `themes/tech-template` на ссылку на данный шаблон.
   
   Например:

   ```
rm themes/tech-template && git submodule add https://github.com/bozaro/tech-template.git themes/tech-template
```

Собрать презентацию можно будет командой `hugo`: презентация появится в каталоге `public`.

Запустить локальный сервер можно командой `hugo server -w -b http://localhost/`: презентация будет доступна по адресу [http://localhost:1313/](http://localhost:1313/).
