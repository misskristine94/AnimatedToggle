# AnimatedToggle
Animated dark/light mode toggle for your #PowerApps
![image](https://github.com/misskristine94/AnimatedToggle/assets/86930618/6c7acf2a-f171-4b21-a502-7ee625b4313f)


Animated light/dark mode toggle for your Power Apps so you don't have to use a boring dropdown 😜 

A simple component built using HTML & SVG with added 3 types of animation to add a little sparkle 🦄

The component has a couple of very simple properties:

◻ LinearGradientColour1 and 2 – the gradient colours (HEX or RGB). If you want a unified colour, please put the same value in both fields

◼ Label – this is a toggle to show/hide the label

◻ LabelTrueText and LabelFalseText - the text for the label (e.g. Dark/Light)

◼ FontSize – font size of the label

◻ Animation – just type in 1, 2 or 3. 1 is a breathe in animation, 2 is a bounce in, and 3 is a rotate animation.

◼ LabelColour – color of the label. You can put in a variable here too.

To make sure the background changes colour, you'll need to use the output property of the component (AnimatedToggle.Toggled). Example - If(AnimatedToggle.Toggled = true, RGBA(0,0,0,1), RGBA(255,255,255,1))

If you have any enhancement ideas, or experience any issues at all - please reach out to me either by raising an issue or getting in touch on my social media: LinkedIn - https://www.linkedin.com/in/kristine-kolodziejski-07b6a7212/ Twitter - @kristinekk94

And please don't forget - this is a sample code for you to reuse, not a library!

Happy Power Apping 😊
