# Арина Сиротинкина - "?????"

### Группа: 10 - МИ - 3
### Электронная почта: akuptsov.hse@gmail.com
### VK: www.vk.com/alekscooper


**[ НАЗВАНИЕ ПРОЕКТА ]**

“Универсальный калькулятор УК – 1”

**[ ПРОБЛЕМНОЕ ПОЛЕ ]**

Объём научных расчётов, выполняемых в настоящее время в разных областях промышленности, инженерии и дизайна возрастает, что приводит к необходимости развития и совершенствования программных продуктов, осуществляющих эти расчёты. К сервисам и приложениям, осуществляющим подобные расчёты, предъявляются следующие требования: 1) охват большого числа разделов математики, 2) возможность производить стандартизированные расчёты по тем или иным общепринятым в различных областях науки формулам и алгоритмам в различных областях, 3) возможность запускать на разных операционных системах. Однако, во всех имеющихся программных продуктах **отсутствует**, по нашим данным: 1) интегрированность математических расчётов с другими науками, использующими математический аппарат: физикой, химией, теорией информаций и т. п. 2) возможность исполнения скриптов, 3) возможность интеграции с известными облачными сервисами для сохранения промежуточных расчётов, 4) возможность экспорта результатов в различные популярные форматы типа pdf, csv, xls. Заявляемый программный продукт позволит решить эти проблемы и обеспечит пользователям широкий функционал, интуитивно понятный интерфейс, кроссплатформенность и адаптивную систему настроек тарифного плана. 

**[ ЗАКАЗЧИК / ПОТЕНЦИАЛЬНАЯ АУДИТОРИЯ ]**

Программный продукт может заинтересовать широкую аудиторию, поскольку рассчитан на проведение универсальных расчётов, однако необходимо выделить несколько групп пользователей, для которых существует свой тип настроек (профилей). Эти настройки будут влиять на функционал и интерфейс(внешний вид), тарифный план и возможность экспортировать результаты вычислений. К выделяемым группам относятся:

* Учащиеся средней и старшей школы
* Учащиеся вузов по специальности “Программная инженерия”
* Инженеры-строители
* Инженеры космической отрасли

**[ АППАРАТНЫЕ ТРЕБОВАНИЯ ]** 

Продукт разрабатывается под все известные операционные системы в данный момент и к моменту сдачи должен существовать в виде версий для следующих конфигураций:

* OS – версия 11 и выше, 10 Гб свободного места на гаджете
* Android – версия Nougat (Android 7) и выше, 12 Гб свободного места, 3 Гб оперативной памяти
* Облачная версия: браузеры Chrome, Firefox
* Mac OS X: версия El Capitan и выше, 4 Гб оперативной памяти и 10 Гб свободного дискового пространства
* Windows 10 – 4 Гб оперативной памяти и 12 Гб свободного дискового пространства 

**[ ФУНКЦИОНАЛЬНЫЕ ТРЕБОВАНИЯ ]**

Программный продукт будет предоставлять следующие возможности:
* Выполнение большинства известных в науке и промышленности расчётов 
* Выбор профилей: учащийся школы, учащийся вузов, инженер-строитель, инженер космической отрасли
* Создание собственных профилей 
* Распознавание рукописных формул
* Распознавание формул в виде голосового сообщения
* Визуализация полученных данных
* Исполнение расчётных скриптов, экспорт и импорт скриптов из популярных облачных сервисов 
  (Яндекс.Диск, Google Drive, Dropbox)
* Экспорт результатов в различные форматы (как минимум – pdf, xls, csv)
* Выбор тарифных планов и способов оплаты 

**[ ПОХОЖИЕ / АНАЛОГИЧНЫЕ ПРОДУКТЫ ]**

Анализ 3 программных продуктов, которые максимально приближены к заданному функционалу, показал, что:

* Калькулятор – 1: не обладает возможностью сохранять экспортируемые данные в известных “облаках“ (доступна только пересылка по электронной почте) 
*	Калькулятор – 2: высокая стоимость ($700 – премиум-план) и отсутствие поддержки мобильных устройств с диагональю меньше 6 дюймов существенно ограничивают целевую аудиторию
* Калькулятор – 3:  не позволяет распознавать формулы в рукописном виде и в виде аудиосообщений; также этот продукт не позволяет создавать собственные профили

**[ ИНСТРУМЕНТЫ РАЗРАБОТКИ ]**

*	Java / Android Studio – для разработки Android-версии
*	Swift / XCode – для разработки iOS-версии
*	HTML / CSS / JS / Django / jQuery – для разработки веб-версии

**[ ЭТАПЫ РАЗРАБОТКИ ]**

*	Разработка пользовательских сценариев
*	Проектирование интерфейса
*	Создание библиотеки для работы с вычислениями
*	Написание модуля для визуализации данных
*	Интеграция с облачными сервисами
*	Создание веб-версии продукта
*	Запуск Android- и iOS версий продукта
*	Тестирование, отладка
*	Подготовка проекта к защите

**[ ВОЗМОЖНЫЕ РИСКИ ]**

*	Невозможность наладить оплату различных пользовательских планов, интеграцию с платёжными системами
*	Трудности с интеграцией с облачными сервисами
*	Невозможность спроектировать удобный пользовательский интерфейс 
*	Неправильная оценка стека технологий, которые мне необходимо изучить, как следствие – нехватка времени на изучение    необходимых языков программирования, фреймворков и т. п.

# !!!Внимание!!!
В этой заявке проект искусственно раздут с целью показать, как должна быть оформлена та или иная задача. Категорически не рекомендуется заявлять версии продукта для разных операционных систем. Сосредоточьтесь на чём-то одном (Web, Android, iOS, Win, Mac OS X, Linux), а все идеи и усилия направьте на развитие функционала.
