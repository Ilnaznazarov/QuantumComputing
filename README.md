Квантовые вычисления
Что такое квантовые вычисления и квантовый компьютер.
Квантовый компьютер – это вычислительное устройство, которое использует явления квантовой механики для передачи и обработки данных. Главное отличие от классических компьютеров, заключается в том, что для решения алгоритмических задач они используют квантовые биты, или как их называют кубиты. При решении задач на привычном компьютере, информация хранится в двоичном коде, поэтому ПК проводит множество последовательных операций с битами. У кубитов есть возможность существовать в нескольких состояниях одновременно, поэтому вычисления делают моментально, а не перебирают последовательно все комбинации. В итоге задачу, которую стандартный компьютер выполняет около недели, квантовый компьютер может выполнить за секунду. Пример отличия бита от кубита представлен на рисунке 1.
 
Рисунок 1 – Биты и кубиты
Такие компьютеры используют для вычислений особые свойства, такие как запутанность и суперпозиция. Квантовые частицы в суперпозиции представляются комбинацией всевозможных состояний, до момента, пока не произошло их измерение и наблюдение. Образуя единую систему, запутанные кубиты влияют друг на друга. Чтобы измерить состояние всех кубитов достаточно измерить состояние одного. Когда увеличивается число запутанных кубитов, способность квантовых компьютеров для обработки информации растет экспоненциально.
При этом, квантовые компьютеры не могут работать со стандартными операционными системами по типу Windows, им необходима своя операционная система и программы. Некоторые крупные компании уже предлагают организациям функцию квантовых вычислений в облаке, как правило такие вычисления предоставляют возможность прямого доступа к эмуляторам, симуляторам и квантовым процессорам. Также у поставщиков имеются личные платформы для разработки, документация для языков программирования и инструменты для вычислений. Одна из крупных компаний IBM опережает многих в данной гонке, и уже смогла представить программную платформу для квантовых вычислений с открытым исходным кодом под названием Qiskit, а компанией Microsoft был выпущен инструмент для программирования вычислительной техники на языке Q# и симулятор квантовых вычислений. При этом многие компании занимаются разработкой программного обеспечения для квантовых компьютеров, такие как: 1QBit, Cambridge Quantum Computing, QSimulate, Rahko и другие. [1]
Обычные алгоритмы, которые основаны на бинарной логике, неприменимы к квантовому компьютеру, использующему квантовые вентили. Для него были созданы новые алгоритмы, из них широко известные: 

− Алгоритм Шора – используется для решения задач методом разложения чисел на простые множители; 

− Алгоритм Гровера – используется для решения задач методом перебора, то есть нахождения решения уравнения F(x) = 1; 

− Алгоритм Дойча – Йожи – основывается на явлении квантовой запутанности и принципе суперпозиции. 

Принцип работы всем привычного компьютера – это цифровой, жестко детерминированный принцип, который основывается на том, что если компьютеру задали начальное состояние, а потом пропустили через него какой-то определенный алгоритм, то в результате получается постоянная переменная, через любое количество запусков. Квантовый компьютер построен на аналоговом, вероятностном принципе и результат работы заданного алгоритма представляет собой выборку из вероятностного распределения конечной реализации алгоритма и плюс возможные ошибки [2].
Квантовые компьютеры не заменят полностью обычные ПК, так как обычный ПК справляется со множеством проблем, но есть такие задачи, которые обычный ПК может решать очень и очень долго.
Задачи для квантового компьютера можно разделить на четыре группы:
1)	Задачи с квантовым преобразованием Фурье, например шифрование и криптография. Алгоритм Шора может позволить взломать bitcoin и RSA, потому что преобразование Фурье очень быстрое и найдя ему правильное применение оно может дать экспоненциальное ускорение;
2)	Задачи оптимизации. Для их решения подходит алгоритм Гровера, который позволяет решать эти задачи быстрее, чем обычным перебором, однако он не даст сильного ускорения как алгоритм Шора. В данную группу входят комбинаторные задачи, решаемые перебором всевозможных вариантов, например, прохождение лабиринта. Чаще всего такие типы задач появляются в сфере логистики, оптимизации и экономики;
3)	Квантовое машинное обучение. Для получения результата чаще всего используют алгоритм HHL, который даст наибольшее ускорение. Представленный алгоритм может решать систему линейных уравнений на много быстрее стандартного алгоритма;
4)	Симуляция квантовой системы. Этот подход был предложен Ричардом Фейнманом. Это самое естественное применение квантовых компьютеров, данные задачи помогают создавать новые сверхпроводники, материалы и лекарства [3].

История создание квантового компьютера
Начало теории квантового компьютера положили открытия, за которые их авторы удостоились Нобелевской премии. В 1918 году Макс Планк открыл элементарную частицу - квант, а Альберт Эйнштейн в 1921 году фотон - элементарную частицу света. В 1935 году Эйнштейн вместе с Борисом Подольским и Натаном Розеном написали статью "Можно ли считать квантовомеханическое описание физической реальности полным?", которая в впоследствии была названа парадоксом Эйнштейна - Подольского - Розена (ЭПР) [4]. После появления статьи ЭПР в 1935 году физик Эрвин Шредингер написал свою статью, которая должна была быть продолжением и уточнением выводов, сделанных Эйнштейном, Подольским и Розеном. В переводе название статьи звучит как “Нынешняя ситуация в квантовой механике”. В этой статье Шредингер ввел два понятия: понятие квантовой запутанности и "парадокс кота" Шредингера. "Парадокс кота" Шредингера заключается в том что "кот" находится в двух состояниях одновременно, он жив и мёртв, это состояние называется суперпозицией [5].
В 1960-ых годах американский физик Р. Ландауэр, работавший в корпорации IBM, пытался обратить внимание научного мира на то, что вычисления - это всегда некоторый физический процесс, а значит, невозможно понять пределы наших вычислительных возможностей, не уточнив, какой физической реализации они соответствуют. А в 1980 году Юрий Манин описал теорию о квантовом компьютере, в 1981 году Ричард Фейнман предложил первую модель квантового компьютера. В этом же году Пол Бениофф описал теоретические основы построения квантового компьютера, им было предложено использовать не обычные алгоритмы, а квантовые алгоритмы, использующие квантовомеханические эффекты. Стивен Визнер в 1983 году опубликовал общую концепция квантового компьютера, которую пытался опубликовать на протяжении 10 лет. В 1985 году Дэвид Дойч предложил конкретную математическую модель квантового компьютера. Все вышеперечисленные события определили направление развития квантового компьютера и привели к возникновению споров на тему квантовых алгоритмов и квантовых операций: по причине невозможности физической реализации квантового компьютера, и в виду недостаточной развитости направления транзисторных компьютеров. Поэтому, физическое построение квантового компьютера было отнесено к разряду научной фантастики.
Ситуация меняется в 1994 г. Американский математик Питер Шор предложил для квантового компьютера алгоритм факторизации, а в 1996 году его напарник по работе Л. Гровер предложил квантовый алгоритм быстрого поиска в неупорядоченной базе данных.
Уже в начале 2000-х годов во многих научных лабораториях были созданы однокубитные квантовые процессоры, управляемые двухуровневыми системами, в которых можно было предполагать возможность масштабирования на много кубитов. Также к данному временному отрезку относится появление огромного количества публикаций, связанных с квантовым компьютером и квантовыми алгоритмами. В 2001 году компания IBM создала 7-кубитный квантовый компьютер, на котором был смоделирован алгоритм Питера Шора и были найдены сомножители числа 15 (числа 3 и 5). [6]


1)	Квантовый компьютер: что это, как работает, возможности | РБК Тренды [Электронный ресурс]. – URL: https://trends.rbc.ru/trends/industry/611256109a79470c8b396fbf
2)	Как работают квантовые компьютеры. Собираем паззл / Хабр [Электронный ресурс]. – URL: https://habr.com/ru/post/480480/
3)	Квантовый компьютер - что это такое и каков принцип его работы? [Электронный ресурс]. – URL: https://mining-cryptocurrency.ru/quantumcomputer/
4)	Эйнштейн А., Подольский Б., Розен Н. Можно ли считать квантовомеханическое описание физической реальности полным? Физ. Откр. - Американское Физическое Общество, 1935. - Вып. 47, - 780 стр.
5)	Даулинг Ж. Р., Приложение убийцы Шредингера и гонка построения первого в мире квантового компьютера. 6000 Broken Sound Parkway NW, Suite 300 Boca Raton. Taylor & Francis Group, LLC. 2013г. - 445 стр.
6)	Холево А. С., Квантовая информатика: прошлое, настоящее, будущее // В мире науки : журнал. - 2008. - № 7.

