# AutoFitY for filters in PixiJS

This plugin for PIXI.JS helps automatically fit by height filter`s media: images and videos.

If you try to enable standard option autoFit, you will find that it may deform your original video.

This module will help you to solve this problem.

Firstly you need to import this module.

<code>import {applyFsMixins} from "pixi-autofit-y";</code>

Then initiate this function:

<code>applyFsMixins();</code>

Creating some filter:

<code>Filter = new PIXI.Filter(transition.vertex, transition.fragment, transition.uniform);</code>

Enable autoFit by height:

<code>Filter.autoFitY = true;</code>

Then you need to define your original video/image size:

<code>Filter.autoFitWidth = 1920;</code>
<code>Filter.autoFitHeight = 1080;</code>