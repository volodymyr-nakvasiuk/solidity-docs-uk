`Про відповідність основній документації. <https://github.com/volodymyr-nakvasiuk/solidity-docs-uk/blob/master/README.md>`_

Solidity
========

.. image:: logo.svg
    :width: 120px
    :alt: Solidity logo
    :align: center

Solidity - це, так звана, контрактно-орієнтована, високорівнева мова програмування для написання смарт контрактів (smart contracts).
Натхнена такими мовами програмування як C++, Python та JavaScript
і розроблена спеціально під віртуальну машину Ethereum (Ethereum Virtual Machine, або EVM).

Solidity статично типізована мова і серед інших функцій, підтримує успадкування (inheritance), бібліотеки та складні,
визначені користувачем, типи даних.

Як ви зможете переконатися, Solidity дозволяє створити контракти для голосування,
краудфандінгу, чесного аукціону, гаманці з мульти-підписом та багато чого іншого.

.. note::
    Напростіший спосіб спробувати Solidity прямо зараз, це скористатися
    `Remix <https://remix.ethereum.org/>`_
    (може довго завантажуватися, будьте терплячі). Remix - це online
    IDE, що дозволяє писати, деплоїти та запускати смарт контракти мовою Solidity.

.. warning::
    Програмне забезпечення пишеться людьми, тому не захищене від помилок. Тому,
    смарт контракти ви повинні писати з використанням добре відомих найкращих практик
    написання програмного забезпечення. Це code review, тестування, аудит та, так званий, доказ корректності (correctness proofs).
    Також зауважте, що користувачі програмного забезпечення часто більш впевнені в програмному коді, ніж в його авторі.
    І останнє, але не меньш важливе, blockchain має власні особливості за якими потрібно уважно стежити при написанні коду,
    тож прохання звернути увагу на розділ :ref:`security_considerations`.

Документація іншими мовами
--------------------------

Solidity документація перекладена кількома мовами волонтерами DAPP спільноти. Англійська версія найбільш актуальна, та виступає джерелом для перекладу.

* `Англійська <http://solidity.readthedocs.io>`_ (**основна документація**)
* `Українська <https://solidity-uk.readthedocs.io>`_ (`Бажаєте допомогти з перекладом? <https://github.com/volodymyr-nakvasiuk/solidity-docs-uk/blob/master/CONTRIBUTING.md>`_)
* `Китайська <http://solidity-cn.readthedocs.io>`_ (перекладається)
* `Іспанська <https://solidity-es.readthedocs.io>`_
* `Російська <https://github.com/ethereum/wiki/wiki/%5BRussian%5D-%D0%A0%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%BF%D0%BE-Solidity>`_ (неактуальна версія)
* `Корейська <http://solidity-kr.readthedocs.io>`_ (перекладається)



Корисні лінки
-------------

* `Ethereum <https://ethereum.org>`_

* `Список останніх змін Solidity <https://github.com/ethereum/solidity/blob/develop/Changelog.md>`_

* `Backlog Solidity <https://www.pivotaltracker.com/n/projects/1189488>`_

* `Програмний код Solidity <https://github.com/ethereum/solidity/>`_

* `Ethereum Stackexchange (Q&A) <https://ethereum.stackexchange.com/>`_

* `Gitter чат <https://gitter.im/ethereum/solidity/>`_

Існуючі способи розробки мовою Solidity
---------------------------------------

* `Remix <https://remix.ethereum.org/>`_
    Online IDE з інтегрованим компілятором та Solidity runtime середовищем, що не потребує серверної частини (працює в браузері).

* `Плагін для IntelliJ IDEA <https://plugins.jetbrains.com/plugin/9475-intellij-solidity>`_
    Плагін Solidity для IntelliJ IDEA (і всіх похідних IDE від JetBrains)

* `Розширення для Visual Studio <https://visualstudiogallery.msdn.microsoft.com/96221853-33c4-4531-bdd5-d2ea5acc4799/>`_
    Плагін Solidity для Microsoft Visual Studio, що включає компілятор Solidity.

* `Пакет для SublimeText <https://packagecontrol.io/packages/Ethereum/>`_
    Пакет Ethereum Solidity language syntax для редактора SublimeText, що дозволяє робити підсвітку синтаксису програмного коду на Solidity.

* `Etheratom <https://github.com/0mkara/etheratom>`_
    Плагін для редактора Atom, що дозволяє робити підсвітку синтаксису, компілятор та runtime серидовище.

* `Atom Solidity Linter <https://atom.io/packages/linter-solidity>`_
    Плагін для редактора Atom, що перевіряє ваш Solidity код на відповідність стилю та стандартам.

* `Atom Solium Linter <https://atom.io/packages/linter-solium>`_
    Плагін для редактора Atom, що перевіряє ваш Solidity код на відповідність стилю та стандартам на базі Solium. Дозволяє зробити гнучку настройку своєї роботи.

* `Solium <https://github.com/duaraghav8/Solium/>`_
    Linter для знаходження та виправлення помилок та зауважень пов'язаних з безпекою та стилем програмного коду в Solidity.
    
* `Solhint <https://github.com/protofire/solhint>`_
    Linter для Solidity, що підсвічує помилки пов'язані з безпекою, стилем коду та допомагає у використанні найкращих практик написання смарт контрактів.

* `Розшрення для Visual Studio Code <http://juan.blanco.ws/solidity-contracts-in-visual-studio-code/>`_
    Плагін Solidity для Microsoft Visual Studio Code, що включає в себе підсвітку синтаксису та компілятор Solidity.

* `Emacs Solidity <https://github.com/ethereum/emacs-solidity/>`_
    Плагін для редактора Emacs, що надає підсвітку синтаксису та перевірку помилок компіляції.

* `Vim Solidity <https://github.com/tomlion/vim-solidity/>`_
    Плагін для редактора Vim, що надає підсвітку синтаксису.

* `Vim Syntastic <https://github.com/scrooloose/syntastic>`_
    Плагін для редактора Vim, що перевіряє код на помилки компіляції.

Більше не підтримується:

* `Mix IDE <https://github.com/ethereum/mix/>`_
    IDE на базі Qt для розробки, дебагінгу та тестування смарт контрактів на Solidity.

* `Ethereum Studio <https://live.ether.camp/>`_
    Спеціалізований онлайн IDE, що надає shell доступ до повного середовища Ethereum.

Інструменти для Solidity
------------------------

* `Dapp <https://dapp.readthedocs.io>`_
    Build інструмент, пакетний менеджер та deployment помічник для Solidity.

* `Solidity REPL <https://github.com/raineorshine/solidity-repl>`_
    Спробуйне Solidity прямо зараз з командного рядка.

* `solgraph <https://github.com/raineorshine/solgraph>`_
    Візуалізує роботу коду Solidity та підсвічує потенційні вразливості пов'язані з безпекою.

* `evmdis <https://github.com/Arachnid/evmdis>`_
    Дизасемблер віртуальної машини Ethereum (EVM), що виконує статичний аналіз, щоб забезпечити більш високий рівень абстракції, ніж сирі операції EVM.

* `Doxity <https://github.com/DigixGlobal/doxity>`_
    Генератор документації для Solidity.

Інші парсери Solidity
---------------------

* `solidity-parser <https://github.com/ConsenSys/solidity-parser>`_
    Парсер Solidity для JavaScript

* `Solidity Grammar for ANTLR 4 <https://github.com/federicobond/solidity-antlr4>`_
    Граматика Solidity для парсера ANTLR 4-го покоління

Документація
------------

На наступній сторінці ви спочатку побачите :ref:`простий смарт контракт <simple-smart-contract>` написаний
мовою Solidity, далі основи технології :ref:`blockchains <blockchain-basics>`
та трохи про :ref:`віртуальну машину Ethereum (EVM) <the-ethereum-virtual-machine>`.

Наступний розділ пояснить кілька *можливостей* мови Solidity на
корисних :ref:`прикладах смарт контрактів <voting>`.
Пам'ятайте, що ви завжди можете спробувати/перевірити смарт контракти
запустивши їх `прямо у браузері <https://remix.ethereum.org>`_!

Останній і найширший розділ глибоко охоплює всі аспекти Solidity.

Якщо після прочитання документації у вас все ще залишаться запитання,
ви можете пошукати відповідь, або задати власне запитання на сайті
`Ethereum Stackexchange <https://ethereum.stackexchange.com/>`_,
або ласкаво просимо в наш `gitter канал <https://gitter.im/ethereum/solidity/>`_.
Ми завжди вітаємо будь-які ідеї що до покращення мови Solidity, або цієї документації!

Зміст
=====

:ref:`Ключові слова в алфавітному порядку <genindex>`, :ref:`Пошук <search>`

.. toctree::
   :maxdepth: 2

   introduction-to-smart-contracts.rst
   installing-solidity.rst
   solidity-by-example.rst
   solidity-in-depth.rst
   security-considerations.rst
   using-the-compiler.rst
   metadata.rst
   abi-spec.rst
   julia.rst
   style-guide.rst
   common-patterns.rst
   bugs.rst
   contributing.rst
   frequently-asked-questions.rst
