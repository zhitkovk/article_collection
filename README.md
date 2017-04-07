# Article collection

#### Articles/textbooks/SO answers I find interesting and worth reading

## Data visualization and design


http://www.webascender.com/Blog/ID/597/2014-Web-Map-Design-Examples-Inspiration — map collection

http://www.nytimes.com/interactive/2013/10/09/us/yellen-fed-chart.html — инфляция и безработица в США со времен великой депрессии

http://www.nytimes.com/interactive/2012/07/20/us/drought-footprint.html?_r=0 — карта засухи во времени

https://www.jasondavies.com/maps/ — разные проекции карт

http://www.nytimes.com/2014/08/16/upshot/mapping-migration-in-the-united-states-since-1900.html — миграция в штатах

http://www.cs.ubc.ca/%7Etmm/vadbook/ — book about dataviz (from Bostock AMA)

http://queue.acm.org/detail.cfm?id=1805128 — basic reading about data viz (Mike Bostock and others)

http://courses.cs.washington.edu/courses/cse512/14wi/ — example dataviz course program

http://hci.stanford.edu/courses/cs448b/f11/lectures/CS448B-20111117-Text.pdf — stanford HCI about text visualization

http://projects.propublica.org/graphics/workers-comp-reform-by-state?state=New_York — инфографика про компенсации и вычеты для заработных плат по Штатам. В целом на этом сайте есть много хороших визуализаций.

http://www.ericson.net/content/2011/10/when-maps-shouldnt-be-maps/ — Когда не стоит пользоваться картами. Основная идея: нужно пользоваться картами, если различия между двумя местами действительно обусловлены географией, а не другими факторами, характеризующими две географические точки. Допустим штаты, на которых концентрируется один из кандидатов: он заинтересован в продвижении в них __не__ потому, что они расположены в определенном месте, а потому, что люди, которые там живут скорее всего проголосуют за него из-за своих демографических характеристик. Поэтому лучше отображать это изменение не на карте. Второй случай, когда карта может быть __не__ очень хороша: показать изменение по сравнению с прошлым годом.

http://www.informationisbeautifulawards.com/news/188-2016-the-winners — номинация по визуализации данных и инфографике

https://public.tableau.com/en-us/s/gallery/surviving-titanic — лучшая визуализация титаника

http://www.colorcombos.com/ — подборка палитр цветов

http://www.color-blindness.com/coblis-color-blindness-simulator/ -- color blindens simulator. From colorbrewer2.org «Red-green color blindness affects approximately 8 percent of men and 0.4 percent of women, although its severity varies»

http://junkcharts.typepad.com/junk_charts/ — МНОГО хороших историй про то как, сделать плохие графики хорошими.

http://www.jstor.org/stable/27643902?seq=1#page_scan_tab_contents — examples of counterintuitive in pictures datasets. Like Anscombe’s quartet. Not so understandable article because of genetic algorithms

https://www.r-bloggers.com/the-ramones-punk-is-data-too/ -- Analysis of Ramones career and basic text mining

http://algorithms-tour.stitchfix.com/ -- one of the __coolest storytelling__ examples I've ever seen. Story about data mining at the clothing company.

#### Design (general ideas)

https://gomockingbird.com/mockingbird/# -- vector prototyping in web. Haven't tried yet, seems intuitive and rather simple. Good thing for going away from Shiny's pre-defined layouts.

https://www.invisionapp.com/ -- another solution for prototyping (not vector). FREE.

http://www.designkit.org/methods/ --introduction to design thinking with examples. In short how I understand it: define your design around user needs. Make deep research to understand problems, then prototype, test and then deliver the solution. Don't start design before knowing the problem. Designer is problem solver

http://artgorbunov.ru/bb/soviet/20170104/ -- Делая дизайн сайта, сначала нужно думать о целях этого сайта («зачем огромный раздел новостей стоматологической клинике?»). Какие он задачи решает? Again idea of design = problem solving.

https://m.signalvnoise.com/the-unnecessary-fragmentation-of-design-jobs-d5b9c8621082 -- Аргументы в пользу того, что дизайнер это человек, который умеет создавать разные вещи. Дробление работы дизайнера на мелкие обязанности создаёт хаос: компании не нужны отдельные UI дизайнеры, отдельные фронтэндеры и т.д. Пример Raymond Loewy, человек который делал дизайн машин, логотипов (shell, exxon).

https://signalvnoise.com/posts/2106-you-can-always-do-less -- Ruby founder about developing projects without infinite list of features. TLDR: Set yourself a constraint and do only things that are essential

http://lenagroeger.com/design/ — книжки о дизайне


## R and JS


http://stackoverflow.com/questions/11076567/plot-a-legend-and-well-spaced-universal-y-axis-and-main-titles-in-grid-arrange — extract legend from plot and use it in arranged ggplots

https://medium.com/javascript-scene/top-javascript-frameworks-topics-to-learn-in-2017-700a397b711#.p23ga373z — javascript tech stack in 2017

http://usabilityetc.com/2016/06/how-to-create-leaflet-plugins/ — создание function factory для leaflet контролов (по сути вводная статья про плагины для leaflet’a)

https://www.datacamp.com/courses/object-oriented-programming-in-r-s3-and-r6?tap_a=5644-dce66f&tap_s=10907-287229 — data camp курс про S3 и R6 классы в R

https://www.interviewcake.com/concept/python/memoization — memoization. Suppose you need to make multiple calls to a function. Sometimes (especially in recursive functions) you don’t need to recalculate the result, but just fetch it from previous calculations. Writing a class solves this problem.

https://danmartensen.svbtle.com/javascripts-map-reduce-and-filter — map, reduce, filter for arrays in JS with examples.

https://www.r-bloggers.com/scheduling-r-scripts-and-processes-on-windows-and-unixlinux/ - Easy scheduling in R

https://www.is.uni-freiburg.de/ressourcen/algorithm-design-and-software-engineering-oeffentlicher-zugriff/11_softwaretesting.pdf -- Writing tests in R

http://cooldatasets.com/#Entertainment-Datasets -- коллекция наборов данных

http://stackoverflow.com/questions/30470293/how-to-underline-text-in-a-plot-title-or-label-ggplot2 -- how to add underlined text to ggplot title. Also contains a link to elegant hack for underlining facet titles with annotation.

https://www.sitepoint.com/dom-manipulation-vanilla-javascript-no-jquery/ -- DOM manipulation with Vanilla JS. Many useful examples

#### Colour analysis in R

https://www.r-bloggers.com/color-quantization-in-r/ -- выделение каналов цвета, PCA и kmeans для похожих точек.

http://blog.martinbellander.com/post/115411125748/the-colors-of-paintings-blue-is-the-new-orange -- большой анализ картин художников на по цветам


## Experiment design

http://www.stat.yale.edu/Courses/1997-98/101/expdes.htm -- easy introduction to basic concepts of experimental design.

http://www.tandfonline.com/doi/abs/10.1080/00220485.2014.889538#aHR0cDovL3d3dy50YW5kZm9ubGluZS5jb20vZG9pL3BkZi8xMC4xMDgwLzAwMjIwNDg1LjIwMTQuODg5NTM4P25lZWRBY2Nlc3M9dHJ1ZUBAQDA= — статья про полевые эксперименты в экономике.

http://www.nber.org/papers/w19666.pdf — field experiments article by List.

http://faculty.haas.berkeley.edu/rjmorgan/ebay.pdf — field experiments on eBay

http://www.ingentaconnect.com/content/aea/jep/2011/00000025/00000003/art00001 — guide on field experiments


## Probability theory and math


http://kaharris.org/teaching/425/index.html — mid level probability

http://www.evanmiller.org/how-not-to-run-an-ab-test.html — про то как корректно делать A/B тесты. Нельзя останавливать тест как только результат стал значимым. Правильно контролировать размер выборки заранее. Снизу ссылки на то как выбрать размер выборки. How to run A/B tests correctly

http://xcelab.net/rm/statistical-rethinking/ — McElreath’s Statistical Rethinking: A Bayesian Course with Examples in R and Stan — хорошая книга про байесовскую эконометрику в R. Начинается с супер простых примеров. Интересна первая глава с обсуждением того как сегодня работает статистическая наука (нормально ли применять дерево решений для решения о том какой статистический тест выбрать)

http://www.stat.columbia.edu/~madigan/W2025/notes/survival.pdf — хорошее введение в survival с примерами из R. 

http://andrewgelman.com/2011/09/10/the-statistical-significance-filter/ — Andrew Gelman про постоянное завышение оценок эффектов для значимых результатов. http://dcscience.net/ioannidis-associations-2008.pdf — более подробная статья про это же.

http://www.nibcode.com/en/blog/6/10-recommended-books-on-linear-algebra — подборка книжек по линалу. Обратить внимание на стрэнга

https://petolau.github.io/Analyzing-double-seasonal-time-series-with-GAM-in-R/ — Хороший пост про Generalized additive models

https://nsaunders.wordpress.com/2017/02/03/the-real-meaning-of-spurious-correlations/ — Почему корреляции не работают для пропорциональных данных (дроби и т д). Кратко: берём некоррелированные X и Y. Делим их на Z. X/Z и Y/Z будут коррелированы. Нужно считать proportinality. Пакет для расчета: https://github.com/tpq/propr

https://www.le.ac.uk/users/dsgp1/COURSES/THIRDMET/MYLECTURES/1REGRESS.pdf — Differences between estimating regression with LS, MM and ML. Assumptions and results of each method.


### Markov Chain explanations


http://stats.stackexchange.com/questions/165/how-would-you-explain-markov-chain-monte-carlo-mcmc-to-a-layperson — basic question from stack. Easy explanations with math.

http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.13.7133&rep=rep1&type=pdf — Introduction to MCMC from machine learning perspective.


## Misc


http://ogoloda.li/search#q=&home=false&i= — сервис по подбору блюда из еды которая есть
