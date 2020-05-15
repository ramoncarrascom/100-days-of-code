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

### Day 9: April 2, 2020

**Today's Progress**: Implemented main game, this is the first usable version, and all pieces are working perfectly fine! 

**Thoughts:** I've had a couple of very hard work days, and obviously I couldn't make progress with this challenge. But in these complicated quarantine days, my mental health is more important than anything else. So I've made the decission to not code on those so hard work days. But I'm so happy because everything is working fine... just without almost doing anything!! I've detected some minor fixes to do, but I already have a working version of my TicTacToe game!!

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/2c98f133bde38a8aa18e6c19c35f9b5170aa292e)

### Day 10: April 3, 2020

**Today's Progress**: Did some minor fixing with components integration.  Added game's Id as Guid. Next step is the web service!! 

**Thoughts:** Today has been a functional testing day, which required some minor fixing. Text mode game's only mission is to test components functionality. As I've already checked that everything is working OK, tomorrow will be the first web service approach.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/077dc1676a24544441e50d4c593a5f5ed2f6c11a)

### Day 11: April 4, 2020

**Today's Progress**: Designed & created web api service & repository scaffold.

**Thoughts:** It seems that I haven't advanced too much today, but I've been thinking about player's service & repository design so it can be scalable in upcoming games.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/a91d82b3605e2e43da187092b303ec019f6c4fad)

### Day 12: April 5, 2020

**Today's Progress**: Coded player repository unit tests

**Thoughts:**: Coding unit tests makes me design a better project structure and adopt best practices. It helps me to think about all my needs and all the exceptions that I must consider and handle.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/fd8ce3af1e3718faba596b6e240f28048bbbdb25)

### Day 13: April 9, 2020

**Today's Progress**: Added SetBaseRepository and assured that all unit tests pass OK

**Thoughts:**: I've designed a base repository based on a Set. This will help me mock a database and begin a fast start-up implementation of the application. It is generic, which will allow me to reuse it for other entities.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/897dcd2c83711edea870522c23b0498ab89c2089)

### Day 14 - 15 - 16 - 17: April 10 - 11 - 12 - 13, 2020

**Progress:** They have been 4 hard days dedicated to refactoring and improving unit tests. SonarQube and code coverage has revealed several bugs and misconceptions from my part.

**Thoughts:** Not only I've learned to design more "testable" classes, but also I've learned a lot of new concepts on code coverage and code analysis. This lead me to discover a bug in Coverlet (the library I'm using to analyse code coverage)

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/5390fb0cacfe6cf574695d3e71792329e07dc2b9)

### Day 18: April 14, 2020

**Progress:** Implemented Player and TicTacToeImpl SetBaseRepository

**Thoughts:** Just another normal day coding.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/6a271b7b747f79d59ba78a5b2b550db734a3c08d)

### Day 19: April 16, 2020

**Progress:** Designed main game services contracts.

**Thoughts:** I'm a little tired because of my "official" work. Today I couldn't progress a lot, but I had to think about the next steps. I have a clearer image in my mind of how am I going to design the service and controller layers.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/49a355e0733c60da0dfccdc2040b29c4d40c8f2b)

### Day 20: April 17, 2020

**Progress:** Refactoring and unit testing, fixed Coverlet's problems

**Thoughts:** After fixing Coverlet's problems, I'm having a more reliable vision of the real code coverage in my project.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/tree/0c8186daa5d9f1f904d1278d4fbe6a6f1622db84)

### Day 21: April 18, 2020

**Progress:** Refactoring and unit testing, I already have the green light on SonarQube, so I'll continue with my backend development.

**Thoughts:** I've realized how important is to follow SOLID principles. This makes code more testable and more reliable. From this point on, I'm going to finish the development of my backend.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/7d6b7710962c717ba193b2b2984be075327530af)

### Day 22: April 19, 2020

**Progress:** Begun developing unit tests for the necessary services for the controller.

**Thoughts:** It's time for the final sprint. These unit tests are a little more difficult because of the ammount of mocks and special conditions to simulate. Perhaps I'll get it on 2-3 days to have all the necessary things to finish my backend.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/a0878d57fd129ebdef78a8414d304d9499db2bd1)

### Day 23: April 21, 2020

**Progress:** Finished developing unit tests for backend's services, and started services implementation

**Thoughts:** Everything is working fine. The best thing of developing consistent, well structured and deeply tested internal layers, is that on external layers you only have to "join the pieces" and everything just works

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/d8546a13e588d2d22bb3f98c1491a9fffcf3d736)

### Day 24: April 23, 2020

**Progress:** Finished BoringToeService implementation and unit tests

**Thoughts:** I've finished all the service's implementation. There's only one component remaining to finish all the backend. In a couple of days, I'll be able to see my new endpoints working.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/1eebce68e77d684b8a4e2b9053e09eb8ead2b56c)

### Day 25: April 24, 2020

**Progress:** Implemented controller layer and unit tests, plus some refactor in controller and service layer models

**Thoughts:** Development stage is finished. Tomorrow I'll do some functional testing and I'll mark my backend as complete. After 25 days of working, I'm very proud of all my evolution as a developer.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/1f266ce36d14a774f43d393c93a3b6f789364ac7)

### Day 26: April 25, 2020

**Progress:** Finished functional testing and applied some fixing

**Thoughts:** I've already finished the first functional version of my project's backend, and I have the first master version, although I have a lot of things pending: error control, authentification, etc. At least I have "something" to get called from my frontend.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/ffa30e9c38ae545838c04110d862a9ad96a7e019)

### Day 27: April 26, 2020

**Progress:** Started Ionic frontend

**Thoughts:** I've installed all the necessary software for developing my frontend: NodeJS, Ionic and Visual Studio Code. I've also started a new frontend and begun investigating how Ionic works. It's a totally new framework for me and It's gonna be funny!!

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/ef8372c82e50a2cbfbcab6ad3bee719f5be6a415)

### Day 28: April 29, 2020

**Progress:** Scaffolded project's components

**Thoughts:** Although I've been working on several projects using Angular, I've never started a frontend from the beginning. It's been a little hard to understand Angular's lazy loading and modules routing, but at the end I could make all routes work correctly.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/1563d49789e7a77159f736ba445a2cb45adece78)

### Day 29: April 30, 2020

**Progress:** Installed and configured Jenkins in my RasPi

**Thoughts:** I've recovered a RasPi and I've installed Jenkins for using it as CI/CD manager. This is a completely new world to me, and my steps are going slowly. There's a lot of documentation to read and a lot to learn.

### Day 30: May 1, 2020

**Progress:** Started grid + cell frontend implementation

**Thoughts:** In the begining I'm not using TDD for my developments, because I don't have all the necessary framework knowledge to know exactly how can I make things. I've been reading a lot of documentation and I'm going little by little in this stage.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/87104e11516f9359300d50c07479163e568edfc4)

### Day 31: May 2, 2020

**Progress:** I began developing my DevOps, with the building and testing part of the pipeline for the backend

**Thoughts:** I'm going a little slow because I'm reading a lot of documentation about Jenkins, and I want to do things right. I didn't have all the necessary SDKs in my RasPi, and Arm64 versions don't have an automated install. But now everything's working perfectly fine. It builds and tests my backend. The next step is deploying the generated artifact.

### Day 32: May 6, 2020

**Progress:** Fixed CSS issues

**Thoughts:** It's been several days having issues with CSS layout. I want my grid to be responsive and full CSS. After reading documentation and forums, I did the trick!! Now it's working fine. I'll have to make a CSS course, cause it is one of my weak points.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/f26d7a7428aa9db3b0acad84fc5a8b95af3b24bf)

### Day 33: May 8, 2020

**Progress:** I've been developing my frontend deployment. I already have a very basic but operational web deployed in https://www.boringames.com

**Thoughts:** I'm very happy cause I already could deploy my frontend by using Jenkins... I am beginning to understand the pipelines' structure and function. The only pending point is the deployment of the backend, but this will have to wait some days, cause I must configure correctly the vps that I'm going to use.

### Day 34: May 9, 2020

**Progress:** Developed Player's display and Scoreboard. In this moment it's only the scaffold and a little more.

**Thoughts:** Developing frontend components seems a little difficult to me, because graphical components always have been my weak point. But little by little, I am evolving.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/6d3c6c49e6d9d9bd65bd87b20a424d6f9c33eb45)

### Day 35: May 10, 2020

**Progress:** Solved some CSS issues with Player Display

**Thoughts:** It's a little bit disappointing to deal with CSS. But now, my PlayerDisplay component is working fine. I must take a look to responsiveness, but I think that I'm doing it.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/f82492262a28e5a21a50c5c8c5c6f2abbc55189a)

### Day 36: May 11, 2020

**Progress:** Service and components logic

**Thoughts:** I've evolved my apps logic. I've started the new service for backend communications. In the begining I'm going to mock all the calls.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/a0cce6288b9e0b7c9146c80b1a6195218fad33a1)

### Day 37: May 12, 2020

**Progress:** Refactor and improved models

**Thoughts:** I've refactored my scoreboard component to allow N number of players. I've also refactored players models to improve data linking between components. The game now shows a User Name input on initializing.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/64aa59c9cdbdef08fd3a92f5ff1d900db36a59ab)

### Day 38: May 13, 2020

**Progress:** Added HttpClient and developed error interceptor

**Thoughts:** I've begun implementing the infraestructure needed for communicating with the backend. I want to make it as solid as possible, and using best practices as much as I can. I've read all Angular documentation to reach this purpose, and I've started its implementation.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/6e31adb065d51d61741273006c7a05fddaedb479)

### DAY 39: May 14, 2020

**Progress:** Solved CORS problems in the backend

**Thoughts:** It's been a horrible day, dealing with CORS problems. Reading CORS for .NET Core documentation, it seems to be as simple as adding a couple of lines of code. But the order in which these lines are added is so important, and that was my main problem. .NET Core's middleware must follow a right order, or everything just stops working.

### DAY 40: May 15, 2020

**Progress:** Implemented player's initialization with backend

**Thoughts:** Still implementing things. I could already connect with the backend and players are beeing initialized correctly. I've had some problems with async/await workflow combined with Angular's components lifecycle.

**Link to work:** [Boring Games App](https://github.com/ramoncarrascom/BoringGames/commit/eb02de690cb476c7f2c87c613d8f1e1aee69cbba)