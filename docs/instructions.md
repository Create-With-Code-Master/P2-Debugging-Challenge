---
layout: tabbed-assignment
---

# Instructions

{% include time-estimate.html %}

By the time you get here you should have:

* Successfully installed and tested **GitHub Desktop** on your computer.
* Made a *fork* of the **Prototype 2 Debugging Challenge** repository to your GitHub account. Choose the appropriate repository for your block:
  - **1st Block:** [Prototype-2-Debugging-Challenge-S2A1](https://github.com/SKHS-GDP2-S2A1-2019-2020/Prototype-2-Debugging-Challenge-S2A1)
  - **7th Block:** [Prototype-2-Debugging-Challenge-S2B7](https://github.com/SKHS-GDP2-S2B7-2019-2020/Prototype-2-Debugging-Challenge-S2B7)
* *Cloned* the repository to your Desktop.
* Opened the **Prototype 2** debugging challenge in Unity on your computer.
* Set the external script editor in Unity's preferences (Edit > Preferences) to **Visual Studio Code**.

With that accomplished, we're going to spend a few minutes tuning the complete version of Prototype 3 to make it more playable. Then we are going to track down bugs in the game, document them using GitHub Issues, and work on fixing them:

1. Make a copy of the [submission template][template].
1. Start by switching to the **origin/start-here** branch of your clone of the **Prototype 2 Debugging Challenge** repository (this should be the branch that you are already on).
1. Play the game and make any changes in the Inspector pane that you need to make the game more playable. At this point the game is not intentionally buggy, but there are probably changes that will make it more interesting to play. **Record those changes on your submission template.**
1. Switch to the **origin/runtime-bugs-unity** branch and go bug hunting. **As you find bugs, create issues for them on the master repository (the one you forked) for your section.** The bugs you find will all be in the Unity Editor - on this branch there are no *intentional* bugs in the scripts.
   - Add *at least* one issue.
   - Comment on *at least* one issue.
1. Switch to the **origin/runtime-bugs-code** branch and go bug hunting. **As you find bugs, create issues for them on the master repository (the one you forked) for your section.** The bugs you find will all be in the C# scripts - on this branch there are no *intentional* bugs in the Unity Editor.
   - Add *at least* one issue.
   - Comment on *at least* one issue.

<!-- Don't edit links here, change them in _data/assignment.yml instead. -->

{% if site.data.assignment.lesson   %}[lesson]: <{{site.data.assignment.lesson}}>     {% endif %}
{% if site.data.assignment.slides   %}[slides]:   <{{site.data.assignment.slides}}>   {% endif %}
{% if site.data.assignment.template %}[template]: <{{site.data.assignment.template}}> {% endif %}
