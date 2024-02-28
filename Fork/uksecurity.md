---
layout: security.hb
title: Безпека
---

# Безпека 1

## Reporting a new Bug in Node.js

Повідомити про помилки безпеки в Node.js через [HackerOne](https://hackerone.com/nodejs).

Your report will be acknowledged within 24 hours, and you’ll receive a more detailed response to your report within 48 hours indicating the next steps in handling your submission.

After the initial reply to your report, the security team will endeavor to keep you informed of the progress being made towards a fix and full announcement, and may ask for additional information or guidance surrounding the reported issue.

### Програма винагороди Node.js

Проект Node.js використовує офіційну програму винагороди для безпеки дослідників та відповідальні публічні розголоси. Управління програмою здійснюється через платформу HackerOne. Дивіться <https://hackerone.com/nodejs> для отримання додаткової інформації.

## Повідомити про помилку в модулі третьої сторони

Security bugs in third party modules should be reported to their respective maintainers and should also be coordinated through the Node.js Ecosystem Security Team via [HackerOne](https://hackerone.com/nodejs-ecosystem).

Details regarding this process can be found in the [Security Working Group repository](https://github.com/nodejs/security-wg/blob/master/processes/third_party_vuln_process.md).

Дякуємо за поліпшення безпеки Node.js і його екосистеми. Ваші зусилля та відповідальне розкриття значно ціновані і будуть визнані засвідчені.

## Політика розкриття інформації

Ось політика розкриття безпеки для Node.js

* Звіт про безпеку отримано та призначено для первинного обробника. Цей людина координує координацію і процес випуску. Проблему підтверджено і визначено список всіх пов'язаних версій. Код контролюється для пошуку будь-яких потенційних проблем. Виправлення готові до всіх релізів, які все ще знаходяться в стані технічного обслуговування. Ці виправлення не додаються до громадського репозиторію , а скоріше тримаються локально на розгляді оголошення.

* A suggested embargo date for this vulnerability is chosen and a CVE (Common Vulnerabilities and Exposures (CVE®)) is requested for the vulnerability.

* На дату ембарго список розсилки безпеки Node.js надіслав копію оголошень. Зміни розміщуються у публічний репозиторій і нові збірки , розгорнуті до nodejs.org. Протягом 6 годин зі списку розсилки повідомлено, копія дорадника буде опублікована в блозі Node.js.

* Зазвичай дата ембарго буде встановлена 72 години від моменту випуску CVE . Однак це може відрізнятися в залежності від тяжкості помилки або складності в застосуванні виправлень.

* Процес може зайняти деякий час, особливо коли координація потрібна за допомогою супроводжувачів інших проектів. Кожен зусилля буде здійснюватися для обробки помилки як можна вчасно; однак, важливо, щоб ми слідкували за процесом випуску вище, щоб зробити розкриття виконувалося на послідовно.

## Отримання оновлень безпеки

Оповіщення про безпеку будуть поширюватися серед наступних методів.

* <https://groups.google.com/group/nodejs-sec>
* <https://nodejs.org/en/blog/>

## Коментарі до цієї політики

If you have suggestions on how this process could be improved please submit a [pull request](https://github.com/nodejs/nodejs.org) or [file an issue](https://github.com/nodejs/security-wg/issues/new) to discuss.
