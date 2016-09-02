# Pixel Perfecter

This is a _very_ simple Sketch plugin that helps you find layers that have float (pixel imperfect) `X`, `Y`, `width` or `height` properties. It will help you keep your documents cleaner, and keep your design specs tight.

There are two functions available in the plugin:

## Select All Pixel Imperfect Layers

This will select all pixel imperfect layers in your current document, and show you a count of them. You can then use `Layer → Round to Nearest Pixel Edge` function in Sketch to deal with them all at once. It's also helpful just to know how many of those pesky layers hide throughout your document.

The keyboard shortcut for this function is `⌥⌘P`

![](readme-all.gif)

## Select One Pixel Imperfect Layer

This will select only one pixel imperfect layer in your current document. It's helpful to quickly go through all the bad layers, dealing with them on an individual basis. Calling up this function repedately will cycle through the bad layers.

The keyboard shortcut for this function is `⌃⌥⌘P`

![](readme-one.gif)
