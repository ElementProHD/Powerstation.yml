info:
  title: 'PowerStation'
  world: 'Power'
  version: '1.0'
  type: 'dtm'
  creators:
  - 'ElementProHD'
  duration: 3600
  spawn: 318,54,-1253,-90,10
  time: 1300
teams:
 red:
  title: 'Red'
  spawn: 405.5,17,-1322.5,0,10
  max: 15
  monuments:
  a:
   name: Monument A
   location: 405,58,-1372
  b:
   name: Monument B
   location: 405,57,-1372
  c:
   name: Monument C
   location: 405,56,-1372
 blue:
  title: Blue
  spawn: 405.5,17,-1179,-180,10
  max: 15
  monuments:
  a:
  name: Monument A
  location: 405,58,-1130
  b:
  name: Monument B
  location: 405,57,-1130
  c:
  name: Monument C
  location: 405,56,-1130
loadout:
 helmet:
  item: leather helmet
 0:
  item: iron sword
 1:
  item: bow
2:
  item: diamond pickaxe
  enchants:
  - dig_speed:3
 3:
  item: golden apple
  amount: 3
 4:
  item: bread
  amount: 32
 5:
  item: stone
  amount: 32
 6:
 item: iron axe
 enchants:
 - dig_speed:3
 7:
  item: glass
  amount: 32
 8:
  item: oak
  amount: 32
 27:
  item: arrow
  amount: 32
 28:
 item: arrow
 remove-drops:
 - iron sword
 - leader helmet
 repair-drops:
 - bow
 - iron axe
 - diamond pickaxe
regions:
 red-spawn:
   type: cuboid
  min: 365,16,-1333
  max: 443,22,-1308
  radius: 4
  height: 4
  flags:
    build:
       who: '*'
       message: '&cYou may not build in the spawn area.'
 blue-spawn:
   type: cuboid
  min: 443,16,-1165
  max: 365,22,-1193
  radius: 4
  height: 4
  flags:
    build:
       who: '*'
       message: '&cYou may not build in the spawn area.'
