# IME Training
Natural language training data LiveG OS Input Method Editor/typing suggestions.

Licensed by the [LiveG Open-Source Licence](LICENCE.md), except where otherwise noted (such as with training corpuses that are externally sourced).

## What is this repo for?
[gShell](https://github.com/LiveGTech/gShell), the desktop environment for LiveG OS, is designed to work with a range of device platforms and is designed to be used in many languages. One of the requirements for meeting those two goals is to implement an _input method editor_ (IME) which can display typing suggestions/predictive text results to mobile and touchscreen users, and can allow users to enter text in their own language using a standard ISO or ANSI keyboard. Both of these functions are interoperable, meaning that users on mobile devices can also enter text in their own language.

You can learn more about the LiveG OS Input Method Editor on [our Docs page](https://docs.liveg.tech/?product=gshell&page=input.md).

The Input Method Editor displays typing suggestions and other natural-language-based information, and so therefore, we need a vast amount of training data that can be consumed by the Input Method Editor to display the most relevant typing suggestions. This repo serves to collate this training data in a clean format, in addition to housing relevant scripts for processing this data into an intermediate format (a `.gime` file) that can be used efficiently by the LiveG OS IME.
