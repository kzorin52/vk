---
layout: default
title: Метод Video.PutTag
permalink: video/putTag/
comments: true
---
# Метод Video.PutTag
Добавляет отметку на видеозапись.

Страница документации ВКонтакте [video.putTag](https://vk.com/dev/video.putTag).
## Синтаксис
``` csharp
public long PutTag(long videoId, long userId, long? ownerId, string taggedName)
```

## Параметры
+ **userId** - Идентификатор пользователя, которого нужно отметить. положительное число, обязательный параметр
+ **ownerId** - Идентификатор владельца видеозаписи (пользователь или сообщество). По умолчанию — идентификатор текущего пользователя. целое число, положительное число, по умолчанию идентификатор текущего пользователя
+ **videoId** - Идентификатор видеозаписи. положительное число, обязательный параметр
+ **taggedName** - Текст отметки. строка

## Результат
После успешного выполнения возвращает идентификатор созданной отметки (tag id).

## Пример
``` csharp
// Пример кода
```

## Версия Вконтакте API v.5.44
Дата обновления: 26.01.2016 14:50:41