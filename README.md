# AutoFitY for filters in PixiJS

This plugin for PIXI.JS helps automatically fit by height filter`s media: images and videos.

If you try to enable standard option autoFit, you will find that it may deform your original video.

This module will help you to solve this problem.

Firstly you need to import this module.

<code>import {applyFsMixins} from "pixi-autofit-y";

Then initiate this function:

<code>

applyFsMixins();

// Creating some filter
Filter = new PIXI.Filter(transition.vertex, transition.fragment, transition.uniform);

// Enable autoFit by height 
Filter.autoFitY = true;

// Than you need to define your original video/image size
Filter.autoFitWidth = 1920;
Filter.autoFitHeight = 1080;

</code>