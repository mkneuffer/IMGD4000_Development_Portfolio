# IMGD4000 Development Portfolio
## IMGD4000 D23
### Matthew Neuffer


## My role in the project

When we initially started, my role was planned to be primarily heading the UI of the game and tackling extra tasks and jobs that the others didn't have time to complete or thought I would be better at completing. As development continued this shifted. I worked closely with the art team on the level design, worked with Jiangwen to get the water how we wanted it, created the boat driving mechanics, and worked on barriers for the game.

During the inception of our game development project, my designated responsibility was mainly centered around overseeing the User Interface (UI) design of the game. However, as the project progressed, my role gradually evolved to encompass additional tasks and responsibilities that required my expertise and skill set.

In particular, I collaborated closely with the art team to conceptualize and execute level designs that would enhance the gameplay experience. Additionally, I worked alongside Jiangwen to perfect the water mechanics, ensuring that they aligned with our vision for the game. I also developed the boat driving mechanics, which required a thorough understanding of game physics and player movement.

Another area where I contributed significantly was in the creation of barriers within the game. These barriers are an essential element of the game's design and help to establish its unique gameplay mechanics. My involvement in these aspects of the game allowed me to showcase my versatility and ability to adapt to evolving project needs.

In conclusion, as a member of the development team, I was able to leverage my skills and experience to contribute meaningfully to the success of the project. Through my diverse contributions, I was able to play a pivotal role in shaping the game and delivering a high-quality product to our audience.

## The challenges you faced and How you overcame those challenges, including specific APIs used and code fragments (both Blueprints and C++)

Throughout the project there were many obstacles that both the team and I ran into. The first challenge was getting the idea of the game to a place where we could begin work. We had an idea in mind, but the scope would have been too large and it did not align well with the course requirements set for the game. We talked as a team, both art and tech, and settled on a direction that we all thought would work well. Instead of just being an open world sailing game, we pivoted to a puzzle based game that would have a combination of sailing and on-land puzzles.
![map](https://user-images.githubusercontent.com/126025888/235823248-8265be1a-d842-4bb6-8c70-efbbcfa59746.PNG)

The next challenge was having multiple team members developing multiple parts of the game at the same time. This will be covered again in a later section of the development portfolio, but our use of github was a struggle and led to many issues that would delay development. For example, there was one day where I lost 4 hours of work. Another challenge was creating a boat and sailing mechanic that would work well for our game. We wanted a stylized look, so we could not just use the default water and buoyancy. I began by creating two planes, one for the water texture, and one as a ground plane. Then, I created the boat system which is a hover vehicle. The boat is hovering above the ground plane at a level that makes it appear to float. 
![Boat](https://user-images.githubusercontent.com/126025888/235823204-5da7a8b6-7d93-409a-8e7f-aba92fb88603.PNG)
![BoatHover](https://user-images.githubusercontent.com/126025888/235823210-016afa7f-f1db-49df-965b-b5f1c134bafc.PNG)
![bp0](https://user-images.githubusercontent.com/126025888/235823216-8d059e48-4c95-459b-84fd-0e7e9fcd74e7.PNG)
![BP1](https://user-images.githubusercontent.com/126025888/235823221-a913d667-e3cb-4558-aee1-7013dc4da651.PNG)

This worked well, but would introduce another problem which I would have to solve. Since the boat was hovering off of the ground plane, it could also hover above the land, so we had to add barriers that prevent the boat from going on land.
![Barriers](https://user-images.githubusercontent.com/126025888/235823252-9cfd17f5-1bf3-46bd-829b-8c7937195465.PNG)

 
Outside of the development, one of the challenges that our team faced was communication at the start of the term. Our entire team had busy schedules and found it hard to meet and work on the project together, so we were not sure what eachother were doing. To solve this, we found a time to meet to address the issue. We laid out a road map, made assignments, and talked about how we could further improve our communication. This resolved most of the issues and our development quickly advanced.

## An architectural diagram(s) that roughly portrays the architecture of your final project and then shows the design of your specific parts in more detail.
![UML](https://user-images.githubusercontent.com/126025888/235823176-beb2dbdc-f914-4679-aeae-351dade2d95a.png)

## Lessons learned: how should students facing similar challenges in the future tackle the problems you faced?

I learned many important lessons throughout this project and course. First, I learned the importance of communication. When working with a team, it is necessary to stay on top of what each other are working on, so you can be as efficient as possible and dont work on the same thing as someone else.
 
The second lesson I learned is the importance of using your team. This means asking questions, reaching out for help, and taking advantage of the different skill sets that each person on the team has. If you run into a roadblock, you should ask your team to see if anyone has a solution. This came into play multiple times throughout the project.

## Describe your version control choice, and your experience with it

The version control method we went with was GitHub. It started off working well, with no issues, but as our project grew we ran into issues with size. We eventually got these sorted by upgrading our plan. We also had issues with merging projects, but we would continue to slowly get better at this as the project developed and we got more experience. A big help was the one file per actor. Overall, despite having some issues and hiccups along the way, I think that Github was sufficient for what we needed.
