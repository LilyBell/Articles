# How to speed up your development workflow: PhpStorm Edition

One of the most powerful tools available to PHP developers today is PhpStorm, the IDE from JetBrains. PhpStorm is the groundbreaking IDE WebStorm with added support for PHP and DB/SQL.  Not only does it include advanced out of the box features but its extendability coupled with a vast collection of plugins authored by a thriving community give it the ability to be customized for any project scope in the PHP development world.

 All of this means very little if you do not have an optimized workflow.  In this article, we are going to cover ways to optimize your workflow using resources provided to you by PhpStorm, JetBrains, and the JetBrains Community.

 ## Keybindings

 Keybindings are a wonderful and often overlooked tool.  Simply put the more time your hands spend on your keyboard the more productive you can be. Every time you reach for your mouse you are spending time not coding.  With your hands on the keyboard using keybindings you can be exponentially faster than clicking through menus with your mouse. 

 |  |  |
:---|---:
<kbd>Ctrl + Space</kbd> | Invoke Code Completion
<kbd>Alt + Enter</kbd> | Suggest Correction
<kbd>Ctrl + D</kbd> | Duplicate Selection
<kbd>Ctrl + G</kbd> | Navigate to line
<kbd>Ctrl + F</kbd> | Find
<kbd>Ctrl + R</kbd> | Find and replace
<kbd>Ctrl + Tab</kbd> | Navigate open files
<kbd>Ctrl + /</kbd> | Comment or uncomment line

This is only a small section of the keybindings available in PhpStorm but they the ones I get the most use out of. 

You might find it difficult at first to remember to use these; it might also seem cumbersome. Take your time and develop this skill. Make this your goto instead of reaching for your mouse and you will notice an increase in the speed in which you are able to navigate through your code and make changes.

## Plugins

PhpStorm comes packed with a number of plugins out of the box.  Your plugin use should not stop there. With a massive repository of plugins available created by JetBrains and the JetBrains IDE Community plugins are an invaluable way to increase your productivity on any project. 

### [Markdown Navigator](https://plugins.jetbrains.com/plugin/7896-markdown-navigator)

Markdown Navigator is an enhanced markdown language support plugin for PhpStorm. It has a number of robust features such as pasting images into documents, drag and drop files, formatting, HTML to Markdown conversion and error highlighting. This is a powerful and essential plugin for any developer to produce rich and legible markdown files to accompany their project.

### [PHP Annotations](https://plugins.jetbrains.com/plugin/7320-php-annotations)

PHP Annotations is a light and powerful plugin to quickly generate annotations.  PHP Annotations requires no additional configuration and as the official JetBrains Plugin Repository page states, "Just install and be happy"

While PHP Annotations has a few noteworthy features the most important is its ability to automatically generate docblocks with the ability to differentiate between classes, functions, and variables. 

For example, let's assume we have a function called annotationDemo that looks something like this.
```
function annotationDemo ($param1, $param2){
    $response = $param1 + $param2;
    return $response;
}
```

With PHP Annotations you can do the following:

Type /** and press Enter.

The plugin will automatically generate a docblock that should look something like this above the function.

```
/**
 * @param $param1
 * @param $param2
 * @return $response
 */
 ```

It also works on classes and variables as well saving you much needed time in tedious typing. The generated docblock will need some customization because PHP Annotations can't detect variable types or provide descriptions or @author tags but what it does provide are quick and easy barebones docblocks that only need a few blanks filled in.

### [PHP Toolbox](https://plugins.jetbrains.com/plugin/8133-php-toolbox)

PHP Toolbox provides method references and type providers that are included with the Symfony plugin as well as some improved functionality for PhpStorm itself. This plugin adds a variety of type hinting array completion, global string navigation JSON reference and functionality for the Twig templating engine.

While that might not sound like a lot improved hints and completion alone can make a major difference in how smooth your workflow goes.

### Framework and templating plugins

With plugins for every major framework and templating engine, these are easily the most valuable tool in your kit. These plugins are not only time-saving resources but come packed with linting and code hinting specific to the corresponding plugin. 

While there are plugins for Symfony, Laravel, Drupal, WordPress, and Joomla! The available plugins are not specific to PHP Frameworks. You can add additional functionality for Angular, React, Vue, Ember, Handlebars, Blade, and Twig. There are even plugins for database functionality including MySQL, PostgreSQL, and MongoDB.

## Themes and fonts

A common misconception exists that themes and fonts are only for aesthetics. Themes and fonts can and do have an aesthetic value but they also play another very important role in improving your workflow. Your theme and font choices can affect everything from your ability to work for long periods of time to your effectiveness at visual grepping.

### Dark Themes
The importance of a dark theme cannot be overstated. Using a dark theme has a number of important benefits the preeminent being a reduction in eye strain. Reducing eye strain can not only improve your ability to work for longer periods of time but it can reduce dry eyes, long-term eye fatigue and the need for corrective lenses.

### Syntax Highlighting
Syntax highlighting is important when it comes to visual grepping. Having syntactical elements highlighted makes your code easier to read and visually navigate which in turn increases productivity. Most themes already come with their own highlighting but if the defaults don't work for you they can easily be edited in the Color Scheme dialog.

### Monospace Fonts
Monospaced fonts have a variety of benefits to your workflow. The most important benefit is a standardized appearance across your team's devices. Using monospace fonts means that word wraps, indentation and punctuation will look the same on any monitor even if it is a different monospaced font being used by another member of your team. Aside from this other benefits are equal length string literals having the appearance of equality and differentiation between similar characters such as a capital I and a lowercase l.

## You
You are the most important tool in your kit. Making sure that you create a productive environment and routine for yourself it the single most important thing you can do to improve your workflow no matter the IDE you choose.

### Establish a Routine
Establishing a routine will allow you to become more productive because you will never wonder what you should be doing at a given time because your established routine will answer that question for you. This includes a set sleep schedule.

### Minimized Distractions
When distracted it takes the average person between 15-20 minutes to regain their train of thought. Whatever it takes minimized your distractability. This can be done by doing anything from telling people no to rewarding yourself for reaching a set goal. Minimizing distractions effectively depends largely upon your work environment. Identify distractions and eliminate them to make yourself more productive.

### Stop Multitasking
While on the surface multitasking might seem like a great tool to get a lot more accomplished, but it isn't. We learned previously that when distracted it takes 15-20 minutes to recover from the distraction. Multitasking presents you with your own work as distractions. This can lead to drop-offs in quality and productivity. If you have a large task to complete break it down into smaller goals and work on each of them one at a time.

### Reasonable Breaks
Taking breaks sounds like it could disrupt your workflow but there are times when it is the best thing you can possibly do. Plan breaks into your routine so that you can remain alert. Use a break as a reward for accomplishing a goal. Breaks can also be useful if you find yourself stumped with a bug. Get up and walk away from your code for 5-10 minutes and think about anything else but your code. Often you will find that when you return you are able to much more easily focus on troubleshooting.

### Document Everything
Documentation is important no matter the size of your project. It allows other developers and anyone that might work on the same project in the future to quickly be able to ascertain what is going on at a glance. More importantly, it allows you to remain organized and be able to troubleshoot, upgrade and depreciate more efficiently.