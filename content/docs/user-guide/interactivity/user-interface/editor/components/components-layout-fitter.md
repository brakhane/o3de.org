---
description: ' Add a layout fitter component to an element in the Open 3D Engine UI Editor
  to make the element fit its content. '
title: LayoutFitter
---

You can use the **LayoutFitter** component to make an element resize itself to fit its content. Use this component with other components that provide cell sizing information, such as the **Text** component, the **Image** component (with **ImageType** set to **Fixed**), or the **Layout** components (**Cell**, **Row**, **Column**, **Grid**).

To see an in-game example of a completed canvas with the **LayoutFitter** component, open the level UiFeatures in the project SamplesProject. Press **Ctrl+G** to play the game, and then choose **Components**, **Layout Components**, **Layout Fitter**. Press **Esc** to exit the game.

To view that same canvas in the **UI Editor**, navigate to the `\Gems\LyShineExamples\Assets\UI\Canvases\LyShineExamples\Comp\Layout` directory and open the `\fitter.uicanvas` file.

![Image NOT FOUND](/images/user-guide/game_ui_editor/ui-editor-component-layout-fitter-canvas.png)

**To edit a layout fitter component**
In the **Properties** pane of the [**UI Editor**](/docs/user-guide/interactivity/user-interface/editor/working), expand **LayoutFitter** and do the following, as appropriate:
****Horizontal Fit****
Select the check box to resize an element's width to fit its content.
****Vertical Fit****
Select the check box to resize an element's height to fit its content.
