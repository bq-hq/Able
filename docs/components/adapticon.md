# AdaptIcon

## Overview
The AdaptIcon component is a versatile icon component that supports various sizes, shapes, and visual states.
You can set sizes for display with or without a status badge. Based off of the concept behind [Adaptive Icons](https://developer.android.com/guide/practices/ui\_guidelines/icon\_design\_adaptive) introduced with Android 8.0, AdptIcon's display a simple icon inside a variety of shapes.

## Properties
Note: For each property, the **bolded** value indicates the default setting.

- **Adpt** - Controls visibility of the component
  - Values: **Visible**, Hidden

- **Bdg** - Controls visibility of the badge
  - Values: Visible, **Hidden**

- **Tag** - Controls visibility of the tag
  - Values: Visible, **Hidden**

- **AdptSz** - Sets the size of the icon
  - Values: auto, 3xl (156px × 156px), 2xl (104px × 104px), xl (80px × 80px), l (64px × 64px), **m** (48px × 48px), sm (40px × 40px), s (32px × 32px), xs (24px × 24px)

- **AdptShape** - Sets the shape of the icon
  - Values: c (circle, border-radius: var(--radius--round)), s (soft, border-radius: 2.2vw), **r** (rounded, border-radius: 0.5vw), b (box, border-radius: 0px), in (inherit, border-radius: inherit)

- **AdptBgClr** - Sets the background color of the icon
  - Values: d (var(--color--fd500)), w (var(--color--fw500)), s (var(--color--fs500)), p (var(--color--p500)), **n500** (var(--color--n500))

- **IcnClr** - Sets the icon color
  - Values: **n000**, [any valid color value]

- **IcnSrc** - Source for the icon image or SVG
  - Values: **Default**, [any valid image or SVG source]

- **BdgTxtSrc** - Text content for the badge
  - Values: **3**, [any string]

- **BdgLoc** - Location of the badge
  - Values: **tr** (top-right)

- **TagTxtSrc** - Text content for the tag
  - Values: **3**, [any string]

- **AdptGroup** - Grouping or association for the icon
  - Values: [any string or group identifier]

### Size & Shape

To account for multiple usecases the design system has established a set sizing standard for certain interface objects, with AdaptIcon being one of those. The size and shape of the AdaptIcon is set within the base level feeder of AdaptIcon - Shape.

<figure><img src="../../../.gitbook/assets/Size (5) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/Shape (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/Badge.png" alt=""><figcaption></figcaption></figure>

### Status

Most of the time an adaptIcon is simply shown as a metaphor for something, but it does have the ability to carry a badge as well. There may be situations where a service like email or alerts would be represented on the screen as an AdaptIcon so it will need the capability of sharing additional information in the form of a badge in those situations.

