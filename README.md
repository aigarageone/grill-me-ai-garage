# Grill Me AI Garage

Grill Me допомагає перевірити план перед реалізацією або скласти робочий портрет людини. Агент ставить запитання раундами й пропонує відповідь або варіанти до кожного.

## Встановлення

Запустіть команду в корені свого проєкту.

```sh
npx skills add aigarageone/grill-me-ai-garage --skill grill-me --skill grilling --skill grill-me-portrait
```

Щоб явно вказати агента, додайте `--agent claude-code` або `--agent codex`.

## Запуск

- **Перевірка плану.** Додайте план, рішення чи ідею до `/grill-me` у Claude Code або `$grilling` у Codex.
- **Портрет.** Введіть `/grill-me-portrait` у Claude Code або `$grill-me-portrait` у Codex. За три раунди агент збере відомості про роботу, джерела доходу, цілі й блокери та запише їх у `portrait.md`. Скажіть «глибше», щоб додати раунд за обраною темою.

`/grill-me` також запускає портрет, якщо запит стосується самої людини.

## Авторство

Режим перевірки плану базується на скілах `grill-me` і `grilling` Matt Pocock. [Вихідні файли](https://github.com/mattpocock/skills/tree/7739eaed7f8f3915437a8def198a6d0d7206dbc7/skills/productivity) · [Ліцензія MIT](LICENSE)
