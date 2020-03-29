# 100 Days Of Code - Log

### Day 0: March 21, 2020

**Today's Progress**: I've started a project before joining this initiative. My intention is to build a simple but complete project, including its SDLC.

**Thoughts:** I want to create a full CI/CD lifecycle for this project, using TDD as much as possible. A lot to fail and a lot to learn, and a tremendous challenge for this Covid-19 quarantine.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/bb1e758323d6b470091f692d3978f280f755350f)

### Day 1: March 22, 2020

**Today's Progress**: I got stucked in problems with unit-testing the new Coordinate model. As the execution didn't raise any exception, I thought it should be a problem with testing framework, but finally I discovered that the culprit was a bad implementation with getters and setters causing a stack overflow situtation.

**Thoughts:** I'm happy cause I've discovered several ways to debug and run unit tests. Although I couldn't advance too much in coding, I have learned a lot today.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/fd63535a6e76332e0fabe9357669a72589c7cc37)

### Day 2: March 23, 2020

**Today's Progress**: Today I could develop all the features that I had in my plans yesterday, and I could finish my Triad implementation

**Thoughts:** I'm realizing all the possibilities and confidence that gives TDD design. I still haven't implemented a user interface or interaction, but I'm sure that all the components will work fine when I need them

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/23ada3236e7c078f93c797441dd1972c9de31ed8)

### Day 3: March 24, 2020

**Today's Progress**: Refactored Grid's winner player check to use Triads. Code is much cleaner now, although the project seems a little more complex in the begining.

**Thoughts:** Proud of all the work I've done until this point. My focus is on designing good code instead of going fast. And I think that all that previous planning and good design is helping me to develop faster than I thought, cause I can early-detect all the errors I'm making.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/29cbd8387bd06b36722a022536326973df9d1f70)

### Day 4: March 25, 2020

**Today's Progress**: Implemented Player model with it's corresponding unit tests and scaffolded the TicTacToe contract + class.

**Thoughts:** Just another ordinary day evolving my code. The end of the TicTacToe game backend is near. I'd like to arrive there soon for preparing SDLC.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/4970cc4599248a403d6c4b409f7b7dcd583de5e6)

### Day 5: March 26, 2020

**Today's Progress**: Just made TicTacToe implementation's unit testing. This is the first step of TDD.

**Thoughts:** Unit testing doubles developing time. If it wasn't so important, I would have avoided it xD I now can see TDD like a time investment: developing is slower and tedious, but it saves future time

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/e12e23dcf2eacd593cb8969d0d279a6ed2bb4b58)

### Day 6: March 27, 2020

**Today's Progress**: I have decided to begin developing my SDLC, so I have formatted my VPS to install Sonarqube. This is very important in this momment, because I need to measure my code's quality before I begin to add features to it. I've installed all pre-requisites to configure it.

**Thoughts:** I can't show much progress because I've only been configuring VPS' security, installing and configuring MariaDb and setting up users. Tomorrow will be very similar...

### Day 7: March 28, 2020

**Today's Progress**: I have finished installing SonarQube. The first tutorial I've found used MySQL, but currently SonarQube doesn't support that database, so I had to uninstall MySQL, install MS SQL Server Express, and reconfigure everything

**Thoughts:** It's a little disappointing to re-do certain boring and annoying steps... but at least, I have SonarQube perfectly installed and working!

### Day 8: March 29, 2020

**Today's Progress**: I've implemented TicTacToeImpl and improved unit tests. The game's backend is near to finish at least.

**Thoughts:** These coding days are a little "rutinary", but I'm near of my next sub-challenge: improving my SDLC by implementing Gitlab and... a new Front-End using Ionic! It's very exciting!!

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/bf37592f1d86759534dd3101dbaebf067e8e225d)
