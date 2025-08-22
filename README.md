This is a very simple UI library for Roblox that allows you to easily style your UI elements using predefined classes.
The inspiration is obviously a framework like Tailwind CSS.

Feel free to use and modify this code as you see fit. If you have any questions or suggestions, please feel free to reach out to me on Discord: lakenzi

In case you actually use this, you do not need to credit me, but it would be appreciated.
Adding new classes is fairly simple, and styling your UI is as easy as calling the :style() method.
It's also recommended to use UIAspectRatio for better responsiveness, especially when using rounded-full.

Available classes (37):

Color / Transparency / Font:
- bg-(color)-(shade) -> sets BackgroundColor3 (e.g., "bgcolor-blue-500")
- textcolor-(color)-(shade) ->sets TextColor3 (e.g., "textcolor-red-300")
- placeholder-(color)-(shade) -> sets PlaceholderColor3 for TextBox (e.g., "placeholder-gray-400")
- border-(color)-(shade) →-> sets UIStroke color (e.g., "border-black-500")
- bg-(0-100) -> sets BackgroundTransparency (0 = opaque, 100 = invisible)
- text-(0-100) -> sets TextTransparency (0 = visible, 100 = invisible)
- textstroke-(0-100) -> sets TextStrokeTransparency
- transparency-(0-100) -> sets all transparencies at once (background, text, textstroke)
- font-(FontName)-(Size) -> sets font family and text size (e.g., "font-Arial-18")
- textscaled -> enables TextScaled on text objects
- bold -> makes the text bold (<b>Rich Text</b>)
- italic -> makes the text italic (<i>Rich Text</i>)

Positions / Alignment / Shape:
- align-center -> anchors to center of parent
- align-left -> anchors to left of parent
- align-right -> anchors to right of parent
- rounded-sm -> small corner radius
- rounded-md -> medium corner radius
- rounded-lg -> large corner radius
- rounded-full -> full circle corner radius
- responsive -> converts offsets to scale relative to parent (auto-resize) ---> (IN CASE THIS DOES NOT WORK, USE A RESCALE PLUGIN INSTEAD PLS, IT'S BETTER!)

Effects / Shadows:
- shadow ->  adds UIStroke
- hover-shadow ->  adds UIStroke shadow on hover only
- blur -> enables BlurEffect when object is visible

Animations:
- heartbeat -> heartbeat animation continuously
- spin -> spins continuously
- bounce-(number) -> bounces up and down (number = strength)

Hover Effects:
- hover-grow -> slightly enlarges on hover
- hover-spin-left -> rotates counter-clockwise while hovering
- hover-spin-right -> rotates clockwise while hovering
- hover-grow-spin -> combines hover-grow + hover-spin-right
- hover-beat -> heartbeat animation while hovering

Interactions:
- follow-mouse -> object follows mouse while hovered
- grab -> allows dragging with mouse click

Other:
- icon-(name) -> sets image to predefined icon (e.g., "icon-menu")
- activated -> triggers on .Activated
- dropdown-menu -> enables dropdown menu functionality
- autotype -> types out text one character at a time (for text objects only)
