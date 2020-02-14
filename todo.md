make a var that tracks the last time a kill was made
  mod - squirrel cage rotor - effect is only active for 10 seconds after killing a mob
    turn this off in game.checks()
  mod - do more damage for 10 seconds after killing a mob
  mod - energy or health regeneration for 10 seconds after killing a mob
    run this effect in game.checks()


mod - mines - fire something instead of needles on activation
  foam?, flak?, vacuum bomb, super balls
  make a different mod for each type of bullet mine can fire

mod - energy recharges faster when not moving

lore - a robot (the player) gains self awareness
  each mod/gun/field is a new tech
    all the technology leads to the singularity
  each game run is actually the mech simulating a possible escape
    this is why the graphics are so bad, its just a simulation
    final mod is "this is just a simulation"
      you get immortality and Infinity damage
      the next level is the final level
  atmosphere levels that explore lore
    give the user a rest, between combat
    low combat more graphics
    large rotating fan that the player has to move through
    nonaggressive mobs one mob attacking the passive mobs
    in the final level you see your self at the starting level, with the wires
      you shoot your self to wake up?

shotgun - even more short range effects

mod: flechettes - each burst fires an extra flechettes
mod: flechettes - stick into mobs and do poison damage, like foam

mod: foam - does extra poison dmg  (to get past shields)

mod: vacuum bomb - does a constant suck

mod: shield harmonics - large field radius

mod: shotgun - fire extra shot
  but also increase spread?

speed up movement for all gameplay
  higher gravity, larger jump force
  faster horizontal acceleration
  only increase top speed a bit

mob: targeting laser, then a high speed, no gravity bullet

add difficulty slider to custom?

add recursive mod counts to pause screen

css transition for pause menu

field that pushes everything back, and can destroy smaller blocks
  converts blocks into ammo power ups

mod: make player invisible when...
  use the flag from phase field
  when health is low?

field: a larger radius that attracted enemies
  still deflected them near the robot
  convert the health of mobs into energy when they are being attracted

mod: chance to not die from fatal damage
  also push mobs and bodies away?
  also heal?

mod: bot that fires minigun bullets
  only fires when your mouse is held down

mod: do extra damage based on your speed
  do more damage when not moving?
  take less damage when not moving?

gun/field: portals
  use the code from mines to get them to stick to walls
    or lasers
  alternate red and blue portals
  
missiles don't explode reliably enough
  they can bounce, which is cool, but they should still explode right after a bounce

weekly random challenge where everyone playing each week gets the same random setup.
  The randomness would be determined by the date so it would sync everyone.
  power ups still drop, but the drops are determined by a preset list that changes each week.

mod: do something at the end of each level
  heal to full
    should still be effected by the heal reduction at higher difficulty
  give ammo to current gun
  give goals/quests for each level
    how to track goals?
    take no damage
    don't shoot

gun:  Spirit Bomb (singularity)
  use charge up like rail gun
  electricity graphics like plasma torch
  suck in nearby mobs, power ups?, blocks?
    sucked in stuff increase size
  uses energy
  hold above the player's head

Boss levels
  sensor that locks you in after you enter the boss room
  boss that eats other mobs and gains stats from them
    chance to spawn on any level (past level 5)

add a key that player picks up and needs to set on the exit door to open it

make power ups keep moving to player if the pickup field is turned off before they get picked up
  not sure how to do this without adding a constant check

animate new level spawn by having the map aspects randomly fly into place

new map with repeating endlessness
  get ideas from Manifold Garden game
  if falling, get teleported above the map
    I tried it, but had trouble getting the camera to adjust to the teleportation
    this can apply to blocks mobs, and power ups as well
    
field power up effects
  field allows player to hold and throw living mobs
    and hack mobs

give mobs more animal-like behaviors
  like rain world
  give mobs something to do when they don't see player
    explore map
    eat power ups
      drop power up (if killed after eating one)
  mobs some times aren't aggressive
    when low on life or after taking a large hit
  mobs can fight each other
    this might be hard to code
  isolated mobs try to group up.
    
game mechanics
  mechanics that support the physics engine
    add rope/constraint
  get ideas from game: limbo / inside
  environmental hazards
    laser
    lava
  button / switch
  door
  fizzler
  moving platform
  map zones
    water
    low friction ground
    bouncy ground