# goit-markup-hw-05
Оформлення
[OK]«C1» Для всіх ефектів ховер і фокуса (колір, фон, тінь) зроблені переходи. Час - 250ms, функція розподілу часу - cubic-bezier(0.4, 0, 0.2, 1).
[OK]«C2» У переходах та анімаціях явно зазначені анімовані властивості. Ніде немає значення all.
[OK]«C3» В секції Чим ми займаємось текст з фоном спозиційований поверх зображення.
[OK]«C4» В головній навігації, за допомогою псевдоелемента ::after, зроблено підкреслення посилання поточної сторінки (на якій зараз знаходиться користувач).
«C5» Синій оверлей з текстом на картках сторінки Портфоліо з'являється при ховері в будь-якому місці картки.
«C6» Синій оверлей в картках сторінки Портфоліо виїжджає знизу, як показано на відео.
[OK]«C7» У псевдоелементів відсутній текстовий контент у властивості content. Вони використані виключно для декоративного оформлення.

Модальне вікно
[OK]«D1» Виконана розмітка і оформлення «бекдропа» (темного напівпрозорого фону) модального вікна.
[OK]«D2» «Бекдроп» заповнює 100% висоти і ширини в'юпорту браузера і фіксований в ньому.
[OK]«D3» Виконана розмітка і оформлення модального вікна.
[OK]«D4» Модальне вікно вертикально і горизонтально спозиційоване посередині бекдропа.
[OK]«D5» Виконана розмітка і оформлення кнопки закриття модального вікна у верхньому правому куті.
[OK]«D6» Спочатку модальне вікно і бекдроп приховані за допомогою класу is-hidden на бекдропі, в селекторі якого використовуються властивості visibility, opacity і pointer-events.
[OK]«D7» Якщо прибрати з бекдропа клас is-hidden - з'являється бекдроп і модальне вікно.
[OK]«D8» Поява і приховування модального вікна анімовано за допомогою переходу з довільним ефектом, наприклад scale або translate, і opacity.

transition: cubic-bezier(0.4, 0, 0.2, 1) 250ms;