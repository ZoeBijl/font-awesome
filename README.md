# Font Awesome
Assistive Technologies (AT) test for Font Awesome and icon fonts in general. We decided to do these tests after [Dylan raised an issue with Font Awesome](https://github.com/FortAwesome/Font-Awesome/issues/6133).

* All base test results are in `tests/index.html`
* A non-ARIA test bed can be found in `tests/plain-bed.html`

## Progress
At the time of writing—14 days in—the progress has been amazing! Great contributions from the community. Let's keep it up.

### Any help welcome
From code, to test results, to how to actually do decent testing. Anything is welcome.

### Roadmap
There is a [basic roadmap](https://github.com/MichielBijl/font-awesome/milestones) available. All new issues will be assigned to a fitting milestone within the roadmap.

## How to go about this testing buisiness

### How to add a test

1. Copy the contents of test-template.html to tests/index.html
2. Write test
3. Do test
4. Make a pull-request with a short description
4. Be awesome!

### How to add results to a test

1. Either copy the example table row from test-template.html or;
2. copy a table row from tests/index.html
4. Make a pull-request with a short description
4. Profit?

### How to properly test

Depending on the icon coding technique, some or all of these scenarios will be worth testing.

In a screen reader:

1. Linear reading, e.g. screen reader "arrow navigation"
2. Read the icon and its text equivalent in the context of a link. Techniques vary by screen reader: e.g. tab key, rotor, or list of links
3. Read character-at-a-time, e.g. RightArrow
4. Read with a Braille display
5. Repeat the above tests with different verbosity settings, especially with settings related to punctuation.

Other configurations for accessibility:

1. Browser zoom: full page
2. Browser zoom: text-only
3. Windows high contrast mode
4. Text customizations (details TBD)

## Resources

* [E-mail thread at WAI IG](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/stroke-linecap)
* [Icon Fonts + Unicode and Accessibility](http://sites.psu.edu/gotunicode/2013/06/26/icon_fonts_unicode_and_accessi/)
* [ARIA for Screen Readers Not Able to Read Symbols](http://sites.psu.edu/gotunicode/2014/11/18/aria-for-screen-readers-not-able-to-read-symbols/)
* [Death to Icon Fonts](https://www.youtube.com/watch?v=9xXBYcWgCHA) & [Slides](https://speakerdeck.com/ninjanails/death-to-icon-fonts)
* [Seriously, Don’t Use Icon Fonts](http://blog.cloudfour.com/seriously-dont-use-icon-fonts/)
* [Bootstrap: How to use](http://getbootstrap.com/components/#glyphicons-how-to-use)
* [Not allowing pages to choose their own fonts breaks with icon fonts](https://bugzilla.mozilla.org/show_bug.cgi?id=789788)
* [Icon Usability](http://www.nngroup.com/articles/icon-usability/)
* [Icon Classification: Resemblance, Reference, and Arbitrary Icons](http://www.nngroup.com/articles/classifying-icons/)
* [Accessibility support for CSS generated content](http://tink.uk/accessibility-support-for-css-generated-content/)
* [Lessons Learned: Accessibility Theory vs. Implementation Reality](http://files.paciellogroup.com/training/CSUN2014/lessonslearned/) (Use case 3)

## Contributors

* Mallory ([@StommePoes](https://twitter.com/StommePoes))
* Michiel Bijl ([@MichielBijl](https://twitter.com/MichielBijl))
* Mitchell Evan ([@mitchellrevan](https://twitter.com/mitchellrevan))
* Chaals McCathieNevile ([@Chaals](https://twitter.com/chaals))
