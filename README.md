<p align="center">
  <a href="https://github.com/vkbottle/vkbottle">
    <img width="150px" height="150px" alt="VKBottle" src="https://raw.githubusercontent.com/vkbottle/vkbottle/master/docs/logo.svg">
  </a>
</p>
<h1 align="center">
  VKBottle
</h1>
<p align="center">
    <em><b>Кастомизируемый, быстрый и удобный фреймворк для работы с VK API</b></em>
</p>
<p align="center">
  <img alt="GitHub Workflow Status" src="https://img.shields.io/github/actions/workflow/status/vkbottle/vkbottle/push-build.yml">
  <img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dw/vkbottle">
  <img alt="GitHub issues by-label" src="https://img.shields.io/github/issues/vkbottle/vkbottle/bug">
  <img alt="PyPI" src="https://img.shields.io/pypi/v/vkbottle?color=green&label=PyPI">
</p>

## Hello World

```python
from vkbottle.bot import Bot

bot = Bot("GroupToken")

@bot.on.message()
async def handler(_) -> str:
    return "Hello, World!"

bot.run_forever()
```

[Смотреть больше примеров!](https://github.com/vkbottle/vkbottle/tree/master/examples)

## Документация

[Туториал для новичков](https://vkbottle.rtfd.io/ru/latest/tutorial/)\
[Техническая документация](https://vkbottle.rtfd.io/ru/latest)

## Установка

Установить новейшую версию можно командой:

```console
pip install git+https://github.com/lutikk/vkbottle.git
```


