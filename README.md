# LocalizR!

<img align="right" src="https://s18.postimg.cc/tdute22rt/Screen_Shot_2018-04-16_at_12.43.59.png" width="450"/>

Welcome to the repo for our final project at Makers Academy! Our application is an interactive game that takes the user on a language-learning journey.

__DESIGNED BY__:
- Joshua Holloway
- Hannah Lillis
- Kaari Strack
- Magyar-Hunor Tamas
- Jenny Arenas Marin

<hr>


## Approach

### Brainstorming

The main goal for us was to create a web app using React, which most of us haven't used before, but also to produce something presentable as our final project.

After deciding on our product that would be a duolingo clone we fast realized that we don't want a clone. We have to do something more exciting than a clone, after all this is our final project. We then brainstormed our new idea. Let's make a game out of it, let's make a game, where you are given different situations in which you would have to use a different language and let's get you in funny situations if your answers are not correct.

We then thought it would be a great idea to make it full stack JavaScript and this called for the MERN stack.

### Development 

After we agreed on our MVP we decided to spend the rest of the day doing research to get our hands on React. There was a very little i knew about React before so I straight away went to Codecademys React course. I found myself doing very very basic coding and lots of reading about JSX when Josh, the only React experienced in the team gave me a feedback on this. He told me that by doing this I can learn such little by spending a lot of time and yes JSX is important, but not to spend too much time on. Instead we decided to divide up some tasks and I got the tasks to start creating components for our 2nd page where the user would choose the desired language. I had a look on the components Josh created so far and by reading the code I understood how I should test drive creating my components. It was interesting how React has parent and child components and components can be smart or not. In the meantime Hannah - who had some knowledge with Node and Express on backend - paired up with Jenny and they set up our backend environment. Kaari - who loves styling - had a look how she should style React.

The next challenge I've met how are props passed down between components so where the event is met, that can call the function on the smart component, changing the state which then would render the questions page for example. We always kept knowledge sharing sessions where we had the chance to catch up with such challenges.
We were going slower than expected as React showed us that its a harder to deal with such a different paradigm. We did managed to reach our MVP a day later than thought, by TDD ing it, but that was the moment when we had to make a decision. We can TDD onwards and have a not really presentable product or we should try to implement our extra features such as a second language, and a second scenario.

During our 9 days of final projects we've met plenty of big challenges such as styling reused components in React so they look differently on despite they are the same component reused, but Kaari sometimes pairing up with Jenny, sometimes on her own  managed to style it to look great. In the meantime Hannah implemented Auth0 API so our users can log in by using this API just by using their google account or creating a new account. 

Even tho' we decided not the Test Drive our additional features we decided that we should write feature test for our front end. So I installed Cypress and started testing the all the functionality. This, sometimes was a challenge, finding the right class names and ids of the components so I'd be able to click them via Cypress, but I gained lots of useful experience spending time writing these tests. Cypress is a really nice way to test features but also a very slow way of doing it. If I were to create a very simple SPA in JavaScript I would definetely using it because I wouldn't mind a test for running 30 seconds, but if there would be a more sophisticated application I wouldn't go with it again, Mocha and Chai would be much faster. 
We had a good a few smaller merge conflicts but because we divided our tasks well, most of our merges could be done automaticly and I am very proud of it.

After the feature freeze I kept writing/refactoring tests in Cypress as the content of the page was changing, typos were corrected and that was asking for some correction. New ideas and features were coming up on a daily basis from Josh and we did spike a few smaller ones which we thought could 100% implement so we can present a done product on Friday.

### What I would do differently?

I would speak up more and be a better advocate of TDD. I would definetely fully stick to TDD. I would spend much more time planning so we could be more in control and we could come up with a fully tested product. 
I've concentrated more on the front-end and mostly test drive creating components, testing features and I feel like next time I would want to be part of developing the back-end and styling the components as well. Afterall my aspiration is becoming a full stack developer. 


<hr>

<img src="/mvp_daily_workflow_planning.png"  width="500" align="left">

<img src="/MVP_1.png"  width="500" align="left">

<img src="/MVP_2.png"  width="500">

<hr>

## Tech Stack

<img src="https://image.ibb.co/czRdzx/la_reactnpm.png" width="100" alight="left"/>

__Front End__:
- React
- CSS (styled components)

__Back End__:
- Node.js
- Express.js
- Mongodb
- Mongoose

__Testing__:
- Jest
- Enzyme
- Cypress

<hr>

## Set-up & Installation :computer:

Open the Terminal (or iTerm) by pressing ⌘ and spacebar.

<img src="https://image.ibb.co/dXVJXH/la_terminal.png" alt="commandspacebar" width="400" align="right"/>

Click [HERE](https://nodejs.org/en/) to download and install node.js if you do not have it.

Verify your installation by typing:
```
$ node -v
```
Clone this repo onto your computer:
```
$ git clone *copy & paste https or SSH link here*
```
Install the required dependencies:
```
$ npm install
```
Run the server, and begin!
```
$ npm run start-dev
```

<hr>

## User Stories :video_game:

__Minimum Viable Product__:

- As someone who travels often, so I can learn useful phrases, I want to be able to practice a language.

__Features__:

- As a user, so I can decide what to practice, I want to be able to select a language.

- As a traveller, so I can learn a language, I want to be able to choose an answer to a question.

- As a user, so I can play the game, I want to be able to enter my details.

- As a user, so I can keep track of my progress, I want to be able to see my score.

__Extras__

- As a user, so I can play the game, I want to be able to sign up.

- As a user, so I can play the game, I want to able to sign in.

- As a user, so I can enjoy my results, I want to be able to read a comment on how well I did.

- As a user, so I can keep my account secure, I want to be able to sign out.

- As a user, so I can play a random scenario, I want to be able to click a button to randomly choose a quiz for me.

<hr>


## Future Additions

We have two user stories that we were not able to complete in time. Both of which we will look to
integrate into the project after the completion date (12th April)

- As a user, so I can improve my pronunciation, I want to be able to hear example audio.

- As a user, so I can satisfy my competitiveness, I want to see a leaderboard.

- As a user, so I can follow my story, I want to see the outcome of my answer.

## Screenshots of use!

<img align="centre" src="https://s18.postimg.cc/ycibsleah/Screen_Shot_2018-04-16_at_12.44.19.png" width="450"/>
<img align="centre" src="https://s18.postimg.cc/d2uphqik9/Screen_Shot_2018-04-16_at_12.44.37.png" width="450"/>
