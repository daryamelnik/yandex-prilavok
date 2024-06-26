### **Useful links:**

[Тестовый стенд](https://{id}.serverhub.praktikum-services.ru/) ;

[Документация API](https://{id}.serverhub.praktikum-services.ru/docs/).

Разработчики сделали новую функциональность в API Яндекс.Прилавка. Новую версию API передали тебе на тестирование. 

Изучи новую функциональность.

**Работа с наборами:** возможность добавлять продукты в набор — ручка `POST /api/v1/kits/{id}/products`.

**Работа с курьерами:** возможность проверить, есть ли доставка курьерской службой «Привезём быстро» и сколько она стоит. Ручка `POST /fast-delivery/v3.1.1/calculate-delivery.xml`.

**Работа с корзиной:**

- возможность получить список продуктов, которые добавили в корзину. Ручка `GET /api/v1/orders/id`;
- возможность добавлять продукты в корзину. Ручка `PUT /api/v1/orders/:id`;
- возможность удалять корзину. Ручка `DELETE/api/v1/orders/:id`.

### Постановка задачи

1. Проанализируй требования к новой функциональности бэкенда Яндекс.Прилавка. Изучи документацию к API в Apidoc. [Требования](https://code.s3.yandex.net/qa/files/backend_requirements.pdf)
2. Спроектируй тесты в виде чек-листа, чтобы покрыть функциональность, которую тебе передали на тестирование: она описана выше. Авторизацию проверять не нужно.
3. Протестируй API через Postman и заведи баг-репорты в YouTrack, если это понадобится.
