Intro
=====

My first CSS project for freecodecamp: A tribute to Abbas Effendi (also known as Abdul-Baha), Who led the Baha'i community and taught that we are happier when we appreciate diversity and act with compassion

View on [Github Pages](https://syntapy.github.io/fcc_tribute/)

Tested in Firefox 88 - 95, Chromium 96

Todo
====

Main thing left is to support all screen sizes. It looks unprofessional to have part of an element cut off at the bottom of the page

I can fix this in pure CSS through animations, where top elements dissappear and lower elements appear as you scroll down

I could also fit the elements into the page on a case by case basis with respect to screen dimensions
But this requires the height and width of the quote element, which needs a simple line of javascript incorporated

Animation Approach
------------------

For all sizes
- [ ] desired text size...
  - with remote font
  - no remote font
- [ ] no cutoff when scrolled to top
  - image fills top view
    - [ ] mobile animation #1
  - quote is cutoff halfway
    - [ ] mobile animation #1
  - img + quote fills top view
    - [ ] mobile animation #2
  - mobile landscape mode
    - has no cutoff
    - [ ] mobile animation #3
  - desktop view (landscape)
    - [ ] multi-column body
      - [ ] header in top left

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

Test Screen Sizes
- [x] 320 x 480
  - [x] Portrait
  - [x] Landscape
- [ ] 360 x 640
  - [ ] Portrait
  - [ ] Landscape
- [ ] 360 x 720
  - [ ] Portrait
  - [ ] Landscape
- [ ] 360 x 760
  - [ ] Portrait
  - [ ] Landscape
- [ ] 360 x 780
  - [ ] Portrait
  - [ ] Landscape
- [ ] 375 x 667
  - [ ] Portrait
  - [ ] Landscape
- [ ] 375 x 812
  - [ ] Portrait
  - [ ] Landscape
- [ ] 414 x 736
  - [ ] Portrait
  - [ ] Landscape
- [ ] 414 x 896
  - [ ] Portrait
  - [ ] Landscape
- [ ] 768 x 1024
- [ ] 1366 x 768
- [ ] 1440 x 900
- [ ] 1536 x 864

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
