Стъпка 1: Създайте папка
mkdir your-project
cd your-project

Стъпка 2: Създайте package.json:
(който ще съхранява вашите зависимости).

Ако искате сами да попълните стойностите, стартирайте в npm initпротивен случай run npm init -y, което ще отговори на всички основни въпроси от ваше име.

Това ще създаде package.jsonфайл във вашия проект.

Стъпка 3: Инсталирайте пакет локално
npm install

Стъпка 4: Създайте index.html index.js
touch index.html index.js

<body>
  <script (defer ако е в header)src="./index.js"></script>
</body>

Стъпка 5: Стартирайте сървъра

npx пакет index.html

можете да отворите http://localhost:123

=========================

Когато инсталирате пакети локално, те ще бъдат инсталирани във вашата папка в нова папка, наречена node_modules.

- Папката node_modulesтрябва да бъде игнорирана от git, защото не трябва да проследявате файловете вътре node_modules.
  (node_modules/)
- можете безопасно да я изтриете и след това

package-lock.json -> съдържа точните версии на пакетите, които са инсталирани.

- имайте предвид, че никога не трябва да променяте ръчно този файл, тъй като той се генерира автоматично.