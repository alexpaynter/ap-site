+++
title = 'State window tint laws'
date = 2024-08-16T18:17:34-07:00
draft = false
+++

I got the windows of my car tinted recently. Why would an office professional approaching middle age do such a thing? It could be that I read about the low UV protection offered by car side windows, due to the tempered glass that's used, and I believe the skin damage incurred while driving adds up to a pernicious risk for skin cancer over time. It could also be that I was so blown away by Bow Wow and Lucas Black's performances in *Fast and the Furious: Tokyo Drift* that I've decided tinted windows are the life for me.

If you too decide to get tinted windows, you will have an important decision to make: how dark? Within a class of tint materials (ceramic, dyed, etc.) a lower visible light transmission (VLT) rating means darker windows and more light blocked. This includes visible, infrared and UV radiation, so darker seems preferable if you like a chilly car and undamaged skin. As long as you're not considering limo tint, the main downside of low VLT treatment is that if you go too dark, you may be in violation of your jurisdiction's laws. Generally laws specify the minimum allowed VLT for different parts of the car. US residents will be brought to a familiar place: this choice comes down to navigating our quasi-feudal, inexplicable system of state laws, and of course all states are a bit different.

I was stunned that the internet didn't have some data visualizations to show these state laws at a glance.  The overlap between the car modification and data science communities may be weaker than anticipated.  I made one to help my decision:

![Window tint square choropleth](/posts/window_tints_square_choro.png)

The data are pulled from [here](https://www.raynofilm.com/blog/automotive-window-tint-laws-by-state). We simplified the display by taking the maximum of the rear and side numbers, since all but 6 states have the same laws for those regions of the car.

I had some hypotheses about window tints that I can think more clearly about now. First, I figured that states with lots of sun or high temperatures would be more likely to allow low VLT tints. There's a bit of this, the heaviest restrictions in the north on front windows, but the west coast doesn't align with that at all.

I also expected that state politics would come into play. Maybe states with a libertarian vibe would allow you to do whatever with your car. On the other hand maybe more conservative states would have greater law enforcement support. It would be more convenient for policing if we just made the entire car out of clear glass, so I expected red states to have more restrictive (higher) VLT requirements for the front.  I don't see much of an effect there.

My dissertation on potential/imagined causes of state window tinting laws in US will have to wait.
 
