# Pong

Pong is a two-dimensional sports game which simulates table tennis. This implementation is built with Löve

## CS50's Introduction to Game Development

Learn about the development of 2D and 3D interactive games in this hands-on course, as you explore the design of games such as Pong.

[Course Link](https://www.edx.org/course/cs50s-introduction-to-game-development)

### Setup Details:

1. To Build this game we used lua language similar to javascript [manual](http://www.lua.org/manual/5.4/manual.html#2.1)
2. Framework used is named LÖVE
   > LÖVE is an _awesome_ framework you can use to make 2D games in Lua. It's free, open-source, and works on Windows, Mac OS X, Linux, Android and iOS. [Link to Download](https://love2d.org/)
   > [Docs](https://love2d.org/wiki/love)

### step-by-step guide will help to build pong game

0. Display Text: Starting of game building with displaying a text in center of screen.
1. Low resolution: Display text in low resolution using push library.
2. Adding Rectangles: For pong game adding rectangle paddles on screen.
3. Moving Paddles: Using dt - the most common shorthand for delta-time.
4. Add Velocity to Ball: Using - math.randomseed(), os.time(), etc. And Starting game on keyPressed.
5. Updating Code with OOPS!
6. FPS Update: Frames Per Second, using love.window.setTitle(), love.timer.getFPS()
7. Collision Detection: based on "axis-aligned bounding boxes"
8. Adding Scoring
9. Assigning Service to player after scoring
10. Victory Updates for a player
11. Adding Audio for scoring, ball hitting paddle or wall, using [bfxr.net](https://www.bfxr.net/).
12. Reszing Game window with push library, love.resize(width, height), push:resize

#### Few operands differnt in lua:

1. concatenation (..) operation
2. status == nil, kid of null
3. a == b and 1 or 2 (kind of ternary a==b ? true : false )
