<script>
var questions = [ // Сначала вопрос, потом варианты через запятую, потом правильный ответ
["1. Адамзат тарихы дамуының ең алғашқы кезеңі?",
"A) Қола дәуірі",
"В) Темір дәуірі",
"С) Рулық тайпалық кезең",
"D) Андронов кезеңі",
"Е)  Тас дәуірі",
5],
["2. Алғашқы адамдардың бастапқы кезеңдегі топтасу жүйесі?",
"А) Рулық",
"В) Тобыр",
"С) Қауымдастық",
"D) Көшпелілер",
"Е) Тайпалық",
2],
["3. Алағашқы адамдардың тобырдан кейінгі топтасу жүйесі?",
"А) Тайпалық",
"В) Малшылар қауымдастығы",
"С) Рулық", 
"D) Өндірістік ұжым",
"Е) Тері илеушілер мен егіншілер ұйымы",
3],
["4. Алғашқы адамдардың рулық қауымнан кейінгі қалыптасу жүйесі",
"А) тайпа ",
"В) терімшілер",
"С) аналық ру",
"D) аталық ру",
"Е) тобыр",
1],
["5. Қоғамда алғашқы ірі еңбек бөлінісін туғызған жағдай?",
"А) шаруашылықтың егіншілік пен мал шаруашылығы болып бөлінуі", 
"В) аңшылықтың тууы.",
"С) тобырдың қалыптасуы.",
"D) темірді пайдалану",
"Е) терімшіліктің дамуы",
1],
["6. Ғалымдардың ең ежелгі адамды атауы?",
"А) кроманьон.",
"В) синантроп.",
"С) епті адам.",
"D) тік жүретін адам.",
"Е) неандерталь.",
3],
["7. Ең ежелгі <<епті адамның>> мөлшермен өмір сүрген мерзімі.",
"А) 1 млн жыл бұрын",
"В) 500-200 мың жыл бұрын",
"С) 100-35 мың жыл бұрын",
"D) 40-35 жыл бұрын",
"Е) 1 млн. 750 мың жыл бұрын",
5],
["8. Ең ежелгі адамның еңбек құралы",
"А) Үшкір тас",
"В) Бумеранг",
"С) Болас",
"D) Найза",
"Е) Садақ",
1],
["9. Ежелгі <<Тік жүретін адам>> өкілі",
"А) Епті адам",
"В) Неандертальдық",
"С) Синантроп",
"D) Саналы адам",
"Е) Кромонондық",
3],
["10. Жер бетінде бұдан 100-35 мың жыл бұрын өмір сүрді?",
"A) Епті адамдар",
"В) Неандертальдықтар",
"С) Кроманондықтар",
"D) Синантроптар",  
"Е) Саналы адамдар",
4],
["11. Жер бетінде 40-35мың жыл бұрын өмір сүрген адам:",
"A) Епті адамдар",
"В) Неандертальдықтар",
"С) Кроманондықтар",
"D) Синантроптар",  
"Е) Саналы адамдар",
5],
["12. Ежелгі адамдардың ең алғашқы кәсібі",
"А) Терімшілік",
"В) Егіншілік",
"С) Аң аулау мен балық аулап күнелту",
"D) Мал шаруашылығы",
"Е) Терімшілік пен жеміс өсіру",
1],
["13. Тас дәуірін (палеолит) қамтитын кезең",
"А) б.з.д. 12-5 мың жыл",
"В) б.з.д.5-3 мың жыл бұрын",
"С) б.з.д. 100-75 ғасырлар",
"D) б.з.д.75-20 ғасырлар",
"Е) б.з.д. 2 млн 500 мың-12 мың жыл",
5],
["14. Орта тас ғасыры қамтитын кезең",
"А) б.з.б.1 млн. 750 мың жыл бұрын",
"В) б.з.б.12-5 мың жыл", 
"С) б.з.б. 75-12 мың жыл бұрын",
"D) б.з.д.7-5 мың жыл",
"Е) б.з.б. 5-3 мың жыл бұрын",
2],
["15. Жаңа тас ғасыры қамтитын кезең",
"А) б.з.д.12-5 мың жыл",
"В) б.з.д.7-5 мың жыл",
"С) б.з.д. 3-2 мың жыл",
"D) б.з.д.2-1 мың жыл",
"Е) б.з.б.5-3 мың жыл",
5],
["16. Қазақстан аумағында ең ежелгі адамдардың өмір сүрген аймағы",
"А) Солтүстік Қазақстан",
"В) Оңтүстік Қазақстан",
"С) Шығыс Қазақстан",
"D) Орталық Қазақстан",
"Е) Батыс Қазақстан",
2],
["17. Қазақстан аумағында өмір сүрген алғашқы адамдардың  замандасы",
"А) Питекантроп",  
"В) Неондерталь",
"С) Кроманьон",
"D) Саналы адам",
"Е) Епті адам",
1],
["18. Ежелгі адамдардың тұңғыш баспаналары",
"А) Күркелер",
"В) Ағаштан істелген қоршаулар",
"С) Лашықтар",
"D) Үңгірлер", 
"Е) Тұруға қолайлы орман арасы",
4],
["19. Алғашқы адамдардың аулаған аңдары",
"А) Қоян, арқар",
"В) Елік, ешкі",
"С) Қой, жылқы",
"D) Ұсақ аңдар",
"Е) Мамонт мен бизон",
5],
["20. Палеолит дәуіріне жататын еңбек құралдары табылған өңір",
"А) Алтай өңірі",
"В) Жамбыл обылысы", 
"С) Орталық Қазақстан жері",
"D) Алматы обылысы",
"Е) Алатау өңірі",
2],
["21. Жамбыл облысынан табылған палеолит дәуірінің бес мыңдай еңбек құралдарының бәрі:",
"А) Дәнүккіштер мен сыналар",
"В) Келі, балталар",
"С) Қашау мен үшкір заттар", 
"D) Келілер мен чоппингтер",
"Е) Қайла мен чопперлер",
3],
["22. Тас өңдеу биік деңгейге көтерілген кезең",
"А) Орта полеолит",
"В) Кейінгі полеолит",
"С) Мезолит",
"D) Неолит", 
"Е) Ерте полеолит",
4],
["23. Ертедегі адамдардың маймылдар мен жануарлардан басты айырмашылығы.",
"А) Аң аулауы",
"В) Теріп жеуді білуі",
"С) Жұптасып жүруі",
"D) Еңбек құралдарын жасай білуі", 
"Е) Топтасып өмір сүруі",
4],
["24. Жер бетінің күрт суый бастауы басталды?",
"А) 500 мың жыл бұрын",
"В) 100 мың жыл бұрын", 
"С) 300 мың жыл бұрын",
"D) 7 мың жыл бұрын",
"Е) 100 млн жыл бұрын",
2],
["25. Ғалымдырдың есептеуінше мұздықтың ери бастаған уақыты",
"А) 100 мың жыл бұрын",
"В) 53 мың жыл бұрын",
"С) 43 мың жыл бұрын",
"D) 25 мың жыл бұрын",
"Е) 13 мың жыл бұрын",
5],
["26. Ежелгі адамдардың жіп орнына пайдаланған заттары",
"А) Жануарлардың сіңірлері",
"В) Ағаш қабықтары",
"С) Жануарлар жүнін иіру арқылы",
"D) Жануарлар ішектері",
"Е) Шөп тамырлары",
1],
["27. Адамдардың дән үккішті ойлап тапқан кезеңі",
"А) Полеолитте",
"В) Мезолитте",
"С) Қола дәуірінде",
"D) Темір дәуірінде",
"Е) Неолитте",
5],
["28. Ерте тас ғасыры тұрақтарының ең көне ескерткіштерінің табылған жері",
"А) Сексеуіл,Қарасу",
"В) Усть-Нарым",
"С) Шақпақата, Арыстанды", 
"D) Арал, Ботай",
"Е) Атасу, Пеньки",
3],
["29. Екі жағынан да өңделген қарапайым шапқыш тас құрал атауы",
"A) Сына", 
"В) Шапқы",
"С) Қырғыш",
"D) Бифас", 
"Е) Чоппер",
4],
["30. Бір қабат өңделген тас құралдың жүзін ұсақ кертік ойықтар жасау арқылы өткірлеу әдісі",
"A) Егеу әдісі",
"В) Қайрау әдісі",
"С) Кесу әдісі",
"D) Қашау әдісі",
"Е) Ретушь әдісі",
5],

], qQuantity = questions.length, tAnswers = 0, wAnswers = 0;
 
function goNext(N) { // N = номер вопроса
document.getElementById('qBlock').innerHTML = ""; // Очищаем блок вопросов
var qElem = questions[N].length-2, i=1; // Кол-во в массиве минус вопрос и счетчик
var e = document.getElementById('qBlock');
var addQ = document.createElement('h3'); // заголовок, id из номера вопроса
addQ.id = 'head' + N;
e.appendChild(addQ);
document.getElementById('head' + N).innerHTML = questions[N][i-1]; // вписываем вопрос
while (qElem >= i) {
var addP = document.createElement('p'); // абзацы
addP.id = 'p' + i;
e.appendChild(addP);
    var addInput = document.createElement('input'); // инпуты
   addInput.type = 'radio';
    addInput.name = 'a';
    addInput.value = i;
   document.getElementById('p' + i).appendChild(addInput);
    document.getElementById('p' + i).insertAdjacentHTML("BeforeEnd", ' '+questions[N][i]); // вопросы
    i++;
    }
    document.getElementById('btn').innerHTML = "<input type='button' value='Тексеру' onclick='submit("+N+")' />";
}
 
function submit(N) { // Проверяем ответы
var varQuantity = (document.getElementsByName('a').length), oneVar = 0;
while (oneVar <= varQuantity) {
if (document.getElementsByName('a')[oneVar].checked == false) {
oneVar++;
}
else {
var all = questions[N].length-1;
var t = questions[N][all]; // правильный ответ
if (document.getElementsByName('a')[oneVar].value == t) {
document.getElementById('p' + t).className = 'tt';
tAnswers++;
} else {
var ff = oneVar+1;
document.getElementById('p' + t).className = 'tt';
document.getElementById('p' + ff).className = 'ff';
wAnswers++;
}
break;
}
}
N++;
if (N == qQuantity) {
document.getElementById('btn').innerHTML = "<input type='button' id='next' value='Перейти к результатам' onclick='toResults()' />";
} else {
document.getElementById('btn').innerHTML = "<input type='button' id='next' value='Келесі сұрақ' onclick='goNext("+N+")' />";
}
}
 
function toResults() {
document.getElementById('qBlock').innerHTML = "<h3>Сынақ аяқталды!</h3>";
document.getElementById('btn').innerHTML = "<h4>Нәтиже:</h4>Дұрыс жауаптар: "+tAnswers+"<br>Қате жауаптар: "+wAnswers+"<p>Желаете пройти тест еще?</p><input type='button' value='Бастау!' onclick='goNext(0)' />";
tAnswers = 0, wAnswers = 0;
}
</script>




## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ibarafla/2020.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ibarafla/2020.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
