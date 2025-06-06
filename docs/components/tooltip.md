# Tooltip

## Overview
The Tooltip component provides contextual information or guidance when users hover over, focus on, or tap an element. It’s perfect for adding helpful hints, explanations, or labels without cluttering the interface.
## Behavior
A tooltip displays on tapping and holding a screen object (on mobile) or hovering over it (desktop). We display the tooltip as long as the press or hovers interaction takes place.
Upon a tap and release the tooltips displays for 1500ms, unless another action is taken by the user prior to end of that time period, in which it would disappear immediately on that new action. On open and close of the tooltip a 250ms grow/shrink fade transiton is used.
**Content:** The information within a Tooltip will wrap to the next line upon reaching the tooltips max width.

![tooltip](https://github.com/user-attachments/assets/c081db6f-105d-4f9b-aee9-b388ef285d97)

## Properties
Note: For each property, the **bolded** value indicates the default setting.

- **TxtSrc** – Tooltip text content  
  Values: **Tooltip copy** (string)

- **Tooltip** – Toggle tooltip visibility  
  Values: **Visible**, Hidden

- **Style** – Tooltip style variant  
  Values: **none** | success | error | warn | info
