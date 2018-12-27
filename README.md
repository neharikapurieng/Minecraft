# Minecraft
//This is a JavaScript code for a version of Minecraft game !!
turnLeft();
moveForward();
moveForward();
destroyBlock();
moveForward();
turnRight();
moveForward();
moveForward();
moveForward();
turnLeft();
destroyBlock();
moveForward();
turnLeft();
moveForward();
destroyBlock();
turnLeft();
moveForward();
for (var count = 0; count < 9; count++) {
  moveForward();
}
placeBlock("glass");
for (var count2 = 0; count2 < 4; count2++) {
  placeBlock("glass");
  moveForward();
}
turnRight();
for (var count3 = 0; count3 < 3; count3++) {
  placeBlockAhead("glass");
  moveForward();
}
placeBlock("glass");
turnRight();
