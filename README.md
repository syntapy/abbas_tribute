Intro
=====

My first CSS project for freecodecamp

View on [Github Pages](https://syntapy.github.io/fcc_tribute/)

Implemented based in [figma design](https://www.figma.com/file/V2DberliY6Y7uoZTu7vYsV/Abbas-Effendi-Tribute?node-id=0%3A1&t=DEqw7dAmPYHP0N2k-1) I made

Tested in Firefox 108 devtools

Todo
====

Main thing left is to support all screen sizes. It looks unprofessional to have part of an element cut off at the bottom of the page

I can fix this in pure CSS through animations, where top elements dissappear and lower elements appear as you scroll down

I could also fit the elements into the page on a case by case basis with respect to screen dimensions
But this requires the height and width of the quote element, which needs a simple line of javascript incorporated

Animation Approach
------------------

For all sizes
- [ ] screenshot tests
- [ ] h1 should be title, h2s in main portion
- [ ] make sure remote fonts are enabled
 - [ ] double check sizes are good for both fonts enabled/fonts disabled
   - media query?
- [ ] img should have more padding / margin in portrait/mobile mode
- [ ] img should fill right side in landscape mobile mode
- [ ] max width of quote in large landscape screens
- [ ] subtitle should not go beyond picture
- [ ] decrease space between quote and attribution
- [ ] header should fill screen when scrolled to top
  - [ ] quote should not be cut-off in smaller portrait modes
- [ ] add tiny turqoise outline to picture

Animation types
- [ ] type 1
  - pg load
    - img fades in and moves up a little
  - scroll down
    - img fades out while quote fades in
    - quote fades out while text body fades in except top bar
      - top bar fades in fast at/near top
    - small scroll resistance between fades
    - Maybe?? -> fast fade out at small top horizontal sliver 
- [ ] type 2
  - pg load
    - img / quote fade in together
  - scroll down
    - img / quote fade out together
    - text body fades in except top bar
      - top bar fades in fast at/near top
    - small scroll resistance between fades
    - Maybe?? -> fast fade out at small top horizontal sliver 
- [ ] type 3
  - Everything fades in on pg load
  - No fade in on switch to landscape
  - Nothing fades on scroll down

Browsers
- [ ] Firefox
- [ ] Firefox esr
- [ ] Chromium
- [ ] Webkit

Common Screen Sizes
- 360 x 640
- 360 x 720
- 360 x 760
- 360 x 780
- 375 x 667
- 375 x 812
- 414 x 736
- 414 x 896
- 768 x 1024
- 1366 x 768
- 1440 x 900
- 1536 x 864
- 1920 x 1080
