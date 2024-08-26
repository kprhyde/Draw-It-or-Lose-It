# Draw-It-or-Lose-It

Who is The Gaming Room, and what software did they need?
	The Gaming Room (TGR) is a fictional client of the fictional developer company Creative Technology Solutions (CTS), for which I have been assigned to work as a Technology Consultant. 
  TGR currently has a game, Draw It or Lose It, available only on Android. They have partnered with CTS to streamline the game's development so that it can be played across multiple 
  platforms. They are unfamiliar with setting up the environment but can manage it after being given the final product. 
  
	The game will allow players to use authentication when signing up or logging in, allow them to create or find a team to play for, and play the game, which consists of four rounds, 
  each one minute long, where a team will have a high-definition image fully render in after 30 seconds and must provide its phrase, title, or what it is. If they cannot do so, then the 
  other team is given 15 seconds to offer one guess as to what it might be. To facilitate this request, the program will need to allow only one instance of a player or team to exist at 
  a time, pull images from a library of stocked images, allow for multiple players to play worldwide simultaneously, be able to account for time with the one-minute turns and a possible 
  15 second added turn, a way to keep score to decide winners and losers, and a way to keep player stats for possible tournaments or leader boards.
  
	A game server that players can access over the Internet must be established to enable play across multiple platforms. An auth server may also want to be established so that if TGR has 
  various games, players only require one sign-on instead of making numerous to play all of them. This would require a database to store all the credentials where a player’s information 
  would be saved. Finally, security would need to be a top priority, so establishing stateless solid code, a RESTful API for caching memory, and having a form of firewall as players come 
  and go or some form of encryption would ensure player safety.  

What did you do particularly well in developing this documentation?
	Above all, I would say finding and applying research helped throughout this document. The first example of this had to be using a better form of the singleton pattern than what I had 
  been initially exposed to in the provided material. While the provided material gave the basics of the code, further research revealed additional lines of code added to guarantee only 
  one instance can go through and be saved when the same login is being done simultaneously. Researching also gave me a better understanding of how concepts are applied in real-world 
  scenarios and how these can lead to more informed decisions in a client-developer relationship. Since this was the theme over the course, understanding what the client was asking for 
  and applying it effectively, finding and applying research had to be the most substantial part of developing this document.

What about the process of working through a design document did you find helpful when developing the code?
	I found this helpful in a couple of ways. The first came from earlier in the course when it was stated that different teams could oversee various program parts. This map breaks down 
  each team’s role and how their segment interacts with the rest of the program, like puzzle pieces. From an individual perspective, this course gave me perspective on how each part or 
  class of the code gave me the overall program, such as how some classes can be associated with or inherited from others. Also, within each class, I found “FIX ME” statements that I 
  needed to correct to make each class operate effectively and fulfill its intended purpose by working with the other classes. Ultimately, this directs anyone or group to stay focused 
  on what needs to be done, and blocks can be checked off on the map as they are completed.

What would you pick if you could choose one part of your work on these documents to revise? How would you improve it?
	There was only one part where I got dinged: ensuring I included all aspects of the code, mainly when importing lists and having a return type. I understand that researching and 
  applying what I learned are substantial aspects, but I need more practice developing code. I am not afforded many opportunities to practice coding, and I acknowledge that this is where 
  my fault lies and that I need to work on it. Another part I would like to revise possible recommendations for The Gaming Room. I do not believe I was wrong in assessing what was 
  required to fit their needs. However, I was going off the current knowledge, and maybe further research will open more possibilities that I had not previously considered.

How did you interpret and implement the user’s needs into your software design? Why is it so important to consider the user’s needs when designing?
	I reread the entire dialogue about them a few times and noted who they were, what they had, and where they wanted to go. Once I had all this information, I applied what I knew to solve 
  their issues. If the answer seemed unclear, I researched ways to give them what they needed. I currently work in retail, and the most important thing to know is that a customer’s needs 
  always come first. It is crucial to listen for essential information like the initial want and budget, then provide what they are requesting or offer other solutions or upgrades to 
  what they are asking for. It is always important to consider these needs because the client knows precisely what they have and what is needed. As a developer, it is essential to 
  understand these needs and find the best course of action for them to take.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
	I approached it with an open mind. Initially, I did not have all the answers, so I began taking in as much information as possible to be better prepared as the assignments came in. 
  This involved a lot of reading and video explanations to better understand the techniques and strategies involved in approaching software design. There was also a need to record 
  specific patterns for future use to accommodate better business practices held by companies today. While I would say that I still do not have all the answers, this approach made me 
  better informed and opened new possibilities to what I had not previously considered. With technology constantly changing and fresh minds expanding the possibilities of program 
  execution, having an open mind and always being willing to learn and adapt will help me in the future to analyze and design software. 
