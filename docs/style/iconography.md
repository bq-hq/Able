# Iconograhy

Used as a visual language to represent type, level, status, content, or adding context to supporting material. Icons are meant to be a simple, immediately recognizable, visual representations of an object or activity. Icons are visual cues that provide clues about how the user should use the app using metaphorical associations. Iconography is treated in the same way as an element with color, size, and spacing properties that are set outside of the library itself.

With any application there will be the need for some level of visual iconography. To provide a scalable, consistent, and easy way to move between different icon families we use an Icon Library. This ties a **metaphor**, the intent/idea behind an icon to a design token which can have one or more words associated with it. As an example, let's take the idea "metaphor" of a settings area. We can use the design token "#icnSettings" for that icon in every element, component, and screen across the application and then have the ability to swap out that icon, application wide from a single source of truth in the library. In the library we define each metaphor independently.

In the previous example of "Settings" let's say we used a gear icon, that same gear icon could be used to represent another metaphor for example "Motor". By having the two metaphors represented in the Icon Library as separate objects we can change out the "Motor" metaphor for a different visual without effecting the "Settings" icon throughout the app. This also gives us a way of swapping out an entire icon family (ie link a new Icon Library file) for another when you want to change the look and feel of the application.

### Properties

**Name**: \[textField] The human readable way we refer to this "Icon" in the metaphor library

**Family**: \[selectList(Assets.Icons)] The icon family that this icon is in. The list of available icon families is pulled from the Assets > Icons folder. Those icon families that have been uploaded into the system.

**Resource**: \[searchGallary(selectedFamily)] Every icon will have a source file that it references to provide the look of icon.

**Metaphor**: \[textField] Every icon acts as a metaphor for something. Some icons can carry multiple metaphors (i.e. "back" and "previous" for the left-arrow.svg) This allows us to reuse these metaphors as a design token which is referenced throughout our components while all carrying the same look.
