# youtubeBuzzer
userscript to add buzzers via the browsers gamepad api to youtube videos for playing quiz-games.
The script automatically finds and registers Playstation 2 Buzz Controllers and Xbox One Controllers connected to the PC.
When you press a buzzer or the (A) button on the Xbox Controller the video gets paused and the Name+Color of the player who pressed first, is shown.

It's tested in google chrome only so far.

## Installation

You need the tampermonkey browser extension, you can download here: https://www.tampermonkey.net/
When the extension is installed you can open the link to the script to install it: https://github.com/DGZeule/youtubeBuzzer/raw/main/youtubeBuzzer.user.js

## How to use

The script is started on any youtube video URL.
When the Buzzer or controller button is pressed the color and name of the person who pressed it first is displayed and the video gets paused.
A settings button is displayed next to the YT logo. You can set up the usernames, the time that players have for answering and whether an animation should be displayed when the timer is running or not.

## ToDo

* add/test more types of gamepads
* integrate more buttons on the controllers in order to play multiple choice quizzes
* The script could be modified to run on twitch or any other video platform.

