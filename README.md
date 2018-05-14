# game development / Unity3D / Prepare a Machine learning platform for myself
1. A Unity3D game development project - to practice game development, game AI, machine learning.
2. Here is a [prototype](game_prototype_balance_your_forces.jpg) of the game.
3. Intention is to learn the following :
    * Technology wise :
       > Unity3D.(Maybe Unreal engine for C++ too - very far in future.)
       > Android development and Android NDK for game physics and graphics with future expansion.
    * Concept wise : 
      > Game Development, Game physics and Computer graphics.
      > Game adaptivity, AI and Machine learning : Computer simulation and computer games are nice 
        platform to learn and implement AI and machine learning.
      > Procedural Content generation in game development.
      > Little bit learn about mathematics behind sound and music.

# Game Proposal :
 ## Technical considerations :
    * Platform : 
       > 2D on Unity3D game engine. 
       > Future considerations (priority ascending) :
           > Android port of stable 2D version.
           > 3D game - which is port of the best version of the stable 2D (Use Unity3D).
           > Android port of stable 3D.          
       
    * Technologies : 
       > Unity3D
    * Game engine : Unity3D.
    
  ## Game Mechanics :
     * Main idea : is to learn about concept of force.
     * World : 
        > Levels can be multiple with different environment features.
        > OR, later expanded to 
     * Genre : 
       > As a prototype build as a single frame game where enemey come from right and player is at left.
       > Later can be expanded to endless runner with the same feature (will be fun).
     * Player :
       > Will have a gun or power(like sorcerer do!) or throwing axe etc. whose 
         recoil will make the player push back.
       > Player has to avoid or kill enemies by jumping or killing with weapon.
       > Player also has to avoid _back wall_ or _monster which continiously 
         pursues the enemy running at its back_ i.e., player should consider the recoil from 
         the weapon so that it is not much pushed to the monster. Player cannot avoid it with jump.
       > Goes from left to right.
       > Has health as buffer to death !!! simply saying - has a health bar which 
         goes up for some powerups, down on touching enemies, or goes slow on having some powerUps.
     * Enemy :
       > Type 1 (Tailing Monster) : follows the player from left i.e., back, should avoid touching it. Is bigger
         than player so that it cannot be avoided with jump.
       > Type 2 (Facing Monsters) : Comes from right of game viewport. May or may not have weapon of own. 
         Player can avoid them by by jumping. If avoided by player and caught by enemy type 1, they get eaten too.
     * Game Features :
       > Different forces can be considered like wind, less or more friction on ground,
         gravity to increase player difficulty. This can also bring variance in game environment.
       > Power ups can be given to player which can decrease effect of friction or wind or gravity etc.
     * Game Adaptivity :
       > Game can be adapted with :
         ~ increasing or decreasing player difficulty by for example increasing enemy - type 1 or 2 - speed, 
         more powerful enemies or by increasing power of wind, gravity or friction.
         ~ give powerUps to decrease those difficulty.
         ~ Use Machine learning algorithms for adaptation strategies.
     * Game AI :
        > Use machine learning for game adaptivity e.g., evolutionary algorithms, reinforcement learning,
          Q-learning, neural networks etc. specially unsupervised learning methods.
        > Behaviour AI of enemy and environment to give more variety to game.
        > Enemy AI gets more adaptive by evolving through observation of player's gameplay (elements that 
          define gameplay has to be choosen), using evolutionary+reinforcement learning algorithm. Each 
          generation of new enemy will evolve by learning, i.e. one enemey dies but the learning gets 
          transferred to the upcoming enemy.
        > Environment and its features - gravity, storm, wind, objects etc get evolved 
          according to the player gameplay improvement.
       
