---
layout: arbital
title: Винджевская неопределенность
author: "Элиезер Юдковский"
original_title: Vingean uncertainty
original_date: 2015.07.02
original: https://arbital.com/p/Vingean_uncertainty/
original2: https://arbital.greaterwrong.com/p/Vingean_uncertainty
translated_by: К. Кирдан
translated_when: 2024.05.17
license:
  - CC BY 3.0
  - https://creativecommons.org/licenses/by/3.0/deed.ru
excerpt: "«Винджевская неопределенность» — это специфическое эпистемическое состояние, в которое мы входим, когда рассматриваем достаточно умные программы; в частности, в этом состоянии мы становимся менее уверенными в том, что можем предсказать их точные действия, и более уверенными в том, каким будет итоговый результат этих действий."
math: true
---
>Конечно, я так и не написал «важную» историю, продолжение истории о первом усиленном человеке. Однажды я попробовал сделать нечто подобное. Письмо Джона Кэмпбелла с отказом начиналось так: «Извините, но вы не можете написать эту историю. И никто другой не может». <...> Рассказ «Беги, книжный червь!» и его урок были важны для меня. В нем я попробовал прямую экстраполяцию технологии и обнаружил, что падаю в пропасть. С этой проблемой писатели сталкиваются каждый раз, когда задумываются о создании форм разума, превосходящих наш собственный. Когда это произойдет, человеческая история достигнет своего рода сингулярности — места, где экстраполяция перестает работать и приходится применять новые модели — и мир выходит за пределы нашего понимания. — [Вернон Виндж](https://books.google.com/books?id=tEMQpbiboH0C&pg=PA44&lpg=PA44&dq=vinge+%22pass+beyond+our+understanding%22+%22john+campbell%22&source=bl&ots=UTTxJ7Pndr&sig=88zngfy45_he2nJePP5dd0CTuR4&hl=en&sa=X&ved=0ahUKEwjD34_wrubJAhUHzWMKHVXYAocQ6AEIHTAA#v=onepage&q=vinge%20%22pass%20beyond%20our%20understanding%22%20%22john%20campbell%22&f=false), «Истинные имена и другие опасности» (True Names and other Dangers, p. 47).

Винджевская непредсказуемость — это ключевая часть того, как мы размышляем о (по нашему мнению) более умном в той или иной области [консеквенциалистском интеллекте](https://arbital.com/p/consequentialist/). В частности, обычно мы думаем, что не сможем точно предсказать, что сделает агент, который умнее нас, потому что если бы мы могли это сделать, то и сами (согласно [принципу Винджа](vinge-principle.html)) были бы столь же умными.

Если бы вы могли точно предсказывать, какой ход [Deep Blue](https://arbital.com/p/deep_blue/) сделает на шахматной доске, то вы могли бы играть так же хорошо, как и Deep Blue, если бы ходили так, как по вашему прогнозу ходил бы Deep Blue. Это значит, что программисты Deep Blue неизбежно пожертвовали своей способностью заранее предвидеть точные ходы Deep Blue в ходе создания этого превосходящего людей шахматиста.

Но это не значит, что программисты Deep Blue не знали, по каким критериям Deep Blue выбирает, что ему делать. Программисты Deep Blue все еще заранее знали, что Deep Blue постарается _выиграть_, а не проиграть в шахматных партиях. Они знали, что Deep Blue попытается направить будущее шахматной доски в конкретный регион, который занимает высокое место в его рейтинге предпочтений между шахматными позициями. Мы можем предсказать _последствия_ ходов Deep Blue лучше, чем сами ходы.

«Винджевская неопределенность» — это специфическое эпистемическое состояние, в которое мы входим, когда рассматриваем достаточно умные программы; в частности, в этом состоянии мы становимся менее уверенными в том, что можем предсказать их точные действия, и более уверенными в том, каким будет итоговый результат этих действий.

(Обратите внимание, что это противоречит утверждению о том, что мы эпистемически беспомощны и ничего не можем знать о существах, которые умнее нас самих.)

Более того, наша способность думать об агентах, которые умнее нас, не ограничивается знанием конкретной цели и прогнозированием ее достижения. Если бы мы нашли гигантскую инопланетную машину, которая выглядит очень хорошо спроектированной, мы могли бы сделать вывод о том, что инопланетяне были сверхчеловечески умны, даже если бы не знали их конечных целей. Если бы мы увидели металлические трубы, мы могли бы догадаться, что трубы представляют собой некое устойчивое, оптимальное механическое решение, изготовленное из твердого металла, чтобы сохранять свою форму. Если бы мы увидели сверхпроводящие кабели, мы могли бы догадаться, что это способ эффективной транспортировки электричества из одного места в другое, даже если бы не знали, для какой конечной цели оно было нужно. В этой идее — основа [инструментальной конвергенции](https://arbital.com/p/instrumental_convergence/): если мы можем распознать, что инопланетная машина эффективно добывает и распределяет энергию, мы можем признать ее разумно спроектированным артефактом, который служит какой-то цели, даже если мы не знаем какой именно.

## Невместимость убеждений внутри вероятностей действий

Из-за отсутствия у нас логического всезнания при рассуждениях в условиях винджевской неопределенности наши убеждения о последствиях действий агента не полностью содержатся в нашем распределении вероятностей действий этого агента.

Предположим, что на каждом ходу шахматной партии против Deep Blue я прошу вас определить распределение вероятностей возможных шахматных ходов Deep Blue. Если вы рациональный агент, вы должны быть в состоянии определить [хорошо откалиброванное](https://arbital.com/p/calibrated_probabilities/) распределение вероятностей для этих ходов. В самом тривиальном случае — назначив каждому допустимому ходу одну и ту же вероятность (если всего у Deep Blue 20 допустимых ходов, и вы назначаете каждому ходу 5% вероятность, это гарантирует хорошую калибровку).

Теперь представьте себе рандомизированного игрока RandomBlue, который на каждом раунде случайным образом выбирает ход согласно распределению вероятностей, которое вы назначили для возможных ходов Deep Blue в соответсвующей шахматной позиции. На каждом этапе ваша уверенность в том, что RandomBlue сходит тем или иным образом, эквивалентна вашей уверенности в том, что так сходил бы Deep Blue. Но ваше убеждение о том, чем, вероятно, закончится игра — совсем другое. (Это возможно только из-за отсутствия у вас логического всезнания — вам не хватает вычислительных ресурсов, чтобы, исходя из ваших убеждений о каждой позиции, наметить полную последовательность ожидаемых ходов.)

В частности, можно провести следующий контраст между вашими рассуждениями о Deep Blue и о RandomBlue:

- Когда вы видите, что Deep Blue делает ход, которому вы назначили низкую вероятность, вы делаете вывод, что дальше игра пойдет для вас хуже, чем вы ожидали (то есть Deep Blue справится лучше, чем вы ожидали ранее).
- Когда вы видите, что RandomBlue делает ход, которому вы назначили низкую вероятность (т. е. низкую вероятность того, что и Deep Blue сделал бы тот же ход в той же позиции), вы ожидаете, что победите RandomBlue быстрее, чем ожидали ранее (у RandomBlue дела пойдут хуже по сравнению с вашим прежним средним ожиданием).

Это отражает нашу веру во что-то вроде [инструментальной эффективности](https://arbital.com/p/efficiency/) решений Deep Blue. Когда мы оцениваем вероятность того, что Deep Blue сделает ход $x$, мы оцениваем вероятность того, что, исходя из оценки ожидаемой вероятности $EU[y]$ победы для каждого хода $y$, Deep Blue обнаружит, что $\forall y \neq x : EU[x]>EU[y]$ (не учитывая возможности точных совпадений — они маловероятны при глубоком поиске и оценках значимости позиций числами с плавающей запятой). Если Deep Blue выберет $z$ вместо $x$, мы будем знать, что Deep Blue сделал оценку $\forall y \neq z : EU[z]>EU[y]$ и, в частности, обнаружил что $EU[z]>EU[x]$. Это могло быть обусловлено тем, что ожидаемая польза хода $x$ для Deep Blue была меньше, чем нами ожидалось. Но то, что ход $z$ с низкой вероятностью оказался лучше всех прочих, также подразумевает, что он имел неожиданно высокую ценность по сравнению с нашими собственными оценками. Таким образом, когда Deep Blue делает весьма неожиданный для нас ход, мы в основном ожидаем, что он нашел неожиданно хороший ход, — лучше того хода, который мы ранее считали лучшим из доступных.

Напротив, когда RandomBlue делает неожиданный ход, мы думаем, что это просто генератор случайных чисел выдал ход, которому мы справедливо присвоили низкую полезность. Поэтому в итоге мы ожидаем победить RandomBlue быстрее, чем в ином случае.

## Особенности винджевских рассуждений

Некоторые интересные особенности рассуждений в условиях винджевской неопределенности:

- Мы можем оказаться более уверенными в предсказанных последствиях действия, чем в предсказанном действии.
- Мы можем быть более уверенными в инструментальных стратегиях агента, чем в его целях.
- Из-за отсутствия у нас логического всезнания наши убеждения об опосредованных действиями агента отношениях с окружающей средой не отсекаются нашим распределением вероятностей возможных следующих действий системы.
  - Мы обновляем вероятные последствия того или иного действия агента и вероятные последствия других (не предпринятых) им действий после того, как увидим, что в реальности агент выдает это действие.
- Если есть компактный способ описания прежних последствий прежних действий агента, мы могли бы попытаться сделать вывод, что эти последствия являются _целью_ агента. Тогда мы могли бы предсказать схожие последствия в будущем, даже не имея возможности предсказывать точные будущие действия агента.

Наше ожидание винджевской непредсказуемости в той или иной области может не оправдаться, если [область чрезвычайно проста и достаточно хорошо исследована](https://arbital.com/p/rich_domain/). В этом случае может существовать уже известная нам оптимальная стратегия игры, делающая сверхчеловеческую (непредсказуемую) игру невозможной.

## Когнитивная невместимость

Винджевская непредсказуемость — одна из основных причин ожидать [когнитивной невместимости](https://arbital.com/p/uncontainability/) [достаточно умных агентов](https://arbital.com/p/advanced_agent/).

## Винджевская рефлексия

[Винджевская рефлексия](vingean-reflection.html) — это рассуждения о когнитивных системах, особенно очень похожих на вас самих (включая ваше реальное «я»), при условии, что вы не можете точно предсказывать их будущие выводы. Программисты Deep Blue, рассуждая о том, как Deep Blue осуществляет поиск в деревьях игры, могут прийти к хорошо обоснованному, но абстрактному убеждению, что Deep Blue «пытается выиграть» (а не проиграть) и эффективно рассуждает для достижения этой цели.

В [винджевской рефлексии](vingean-reflection.html) нам нужно каким-то образом делать прогнозы о последствиях действий агента в окружающей среде, не зная точных будущих действий агента — по-видимому, посредством рассуждений на каком-то более абстрактном уровне. В [теории тайлинговых агентов](https://arbital.com/p/tiling_agents/) [принцип Винджа](vinge-principle.html) проявляется в правиле, согласно которому мы должны говорить о конкретных действиях нашего агента-преемника только внутри кванторов.

«Винджевская рефлексия» может оказаться гораздо более общей проблемой в разработке продвинутых когнитивных систем, чем может показаться на первый взгляд. Агента, рассуждающего о последствиях выполнения _своего текущего кода_ или обдумывающего, что произойдет, если он _потратит на размышления еще одну минуту_, можно рассматривать как выполняющего винджевскую рефлексию. Винджевскую рефлексию можно также рассматривать как исследование того, какое мышление в когнитивных вычислениях агент _хочет_ иметь, — что может существенно отличаться от его _текущего_ мышления. (Если эти два варианта мышления совпадают, то мы говорим, что агент [рефлексивно устойчив](reflective-stability.html).)

[Теория тайлинговых агентов](https://arbital.com/p/tiling_agents/) в настоящее время является основным направлением исследований, (медленно) пытающихся приступить к формализации винджевской рефлексии и рефлексивной устойчивости.