---
order: 2
title: "Epic: Gitlab Enterprise Server"
---

-  Для Enterprise:

   -  У нас будет Gitlab Enterprise Server на домене [ics-it.app.gram.ax](https://ics-it.app.gram.ax)

   -  В gitlab будет специальный пользователь для review. У этого пользователя будут хранится review репозитории

   -  В gitlab будет специальный пользователь с ролью как минимум Maintainer, у которого будет доступ для того, чтобы добавлять вебхуки в репозитории

   -  При формировании ссылки для ревью, будет создаваться в гитлабе review репозиторий

   -  Если ревьювер перейдёт по этой ссылки, он залогиниться под review пользователем и будет иметь только его права

-  Для не Enterprise:

   -  Пока что ничего трогать не будем, пусть будет пока так-же как сейчас работает

   -  Пока не придумали безопасного решения без использования сервера

   -  После того, как появится [ics-it.app.gram.ax](https://ics-it.app.gram.ax), уберём возможность создавать review ссылки в [app.gram.ax](https://gram.ax)