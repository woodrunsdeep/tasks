# легенда

Вы вместе с командой заасайнены на проект заказчика. Проект делала команда разработчиков, которая уже не доступна (был другой провайдер сервиса). Вам нужно быстро разобраться в проекте и выполнить пару задач заказчика, чтобы выйграть тендер и получить большой контракт на разработку игры в течении 1 года.

Вы можете задать до 5 вопросов 1 раз за неделю, заказчик отвечает в течении 3 дней. Вопросы можно задавать только на английском. Денис на них тоже будет на них отвечать только на английском )

Если будет ктото из текущей команды разработки игры - можно будет им задавать вопросы )

# суть задачи
- проект без документации
- он на реакте \ редаксе
- надо будет 
  - исправить баг
  - добавить контент
  - сделать фичи
- сделать 3-5 пул реквестов

# какие навыки отрабатываем 
- чтение чужого кода
- фикс багов
- добавление контента
- реализация фичи без подробного ТЗ
- презентация работы
- работа в команде

# доп условия
- нужно трекать время участия каждого человека и какую таску \ что именно он делал
- свой публичный репозиторий

# task content
## feature to implement
* html table with all tasks during game json generation
  * https://github.com/rss-com-lab/learnJs-game-data
  * stats what task on which topic / question type / how many words
* fuzzy answer on open questions (if answer not particular - the answer should be counted)
* script to generate enki cards from current format with react cli tool
  * https://github.com/vadimdemedes/ink
  * https://github.com/enkidevs/curriculum/tree/master/javascript
* add animation
  * for the stars (svg / css animation during adding new star)
  * for cactus on click with lottie animation player - https://github.com/mathworld-games/test-lottie-animation
* stats for learned topics and levels for the player
  * graphics
  * playbook
* create a form to submit the content for each type of question 
  * connect to google forms
  * result should go to google sheet
  * or firebase )
* translate the game to eng / belarussian lang
  * interface (all screens)

## ideas
* desktop view
  * ideas!
  * all screens new markup
  * react + simple html will work )
* create landing page with gatsbyjs
  * screenshots
  * description
  * like in piskel

## tests
* unit tests for simple functions / reducers
* https://www.cypress.io/ implement some easy e2e tests
  * registration
  * answer to question
  * settings
* storybook for internal components
  * stars
  * answer question screen
  * settings
## bugs (markups, logic)
* loading screen
* start stage
* no repeated questions


## refactoring
TBD

## themes for content
* 10 questions for closed question
* 10 questions for open questions
* 10 questions for questions with multiple answers
* themes
  * bind, context, scopes
  * OOP - classes, public, private, methods
  * closures
  * FP methods (pure function, curring, partial application, high order functions )
  * event loop, async / await, promises
  * https://github.com/h5bp/Front-end-Developer-Interview-Questions
  * basic corejs questions - scope, closures, types, event loop, syntax
  
