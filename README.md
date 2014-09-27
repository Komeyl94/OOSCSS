# SASS(SCSS) is great, Object Oriented SASS Is AWESOME!
## Start styling from here!
### What's going on in here?
#### Well, everything is clear! 
- I used a version of [normalize](https://github.com/kristerkari/normalize.scss) to stop browsers from doing whatever they want! And there are several files to start with.
- The Mixins file is the first one included. It contains several mixins for REM **font-size** and **line-height** generating, **breakpoints**, **generating arrow** (i love this one!) and some others for generating prefixes automatically. Fill free to edit it.
- Variables file contains some basic information, like default font-size, default colors, defaults page width and so on. If you use a same value for several times, use it the right way, *The Sass Way!*
- And there is the Defaults. Put everything that is going to be styled your way in the theme, like ul or a tags, in this file. It's easier to manage it later.
- I like to use [Lemonade](https://github.com/dope/lemonade) grid system. It's so light and easy to use. Ofcourse if you want to use some other grid system, inform me!

### CSS styling TO-DO list

#### Reset EVERYTHING // Not everything exactly, reset the things that you've used.
- Reset using your own defaults. Most important ones, H1-6, Inputs and container tags, exp. Div or Figure.
- Remember to set padding and margin to zero. You can use them later.

#### Figure out what you want
- You really have to figure out what you are going to do. Like is it going to be responsive? Is it going to be different on mobile devices? Is it going to suck?
- Select a framework, like Foundation, Lemonade, Pure or anything else, if it is NEEDED!
- If it is needed, write your own framework. Even the most popular framework out there may not be good for you

#### Write it Object Oriented
- Use a CSS preprocessor such as SASS or LESS
- Use a framework like Compass or Bourbun
- Add each section of page to different style files. Remember Wordpress hierachy?

#### Write it light
- Ofcourse, if you write your code based on OO rules, you're not going to need this statement. But just for a reminder, use class for same styles.

#### Use version control
- Either you're working with a team or on your own, you ARE going to need to control the difference you made through the time. I like using GIT. You can choose your own, just don't make it complicated!
