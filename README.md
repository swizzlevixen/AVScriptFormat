# AV Script Format Markdown CSS v02

by Mark Boszko

- mark@omnigroup.com
- @bobtiki on social sites

## Contents

- AVScriptMarkdown.css - The stylesheet
- AVScriptFormatTemplate.markdown - A sample script document
- README.markdown - This file
- AVScriptFormat.bbpackage - The CSS and template in a package for BBEdit.

## Background

A/V Script Format is a very basic idea at its core. It's a table view -- two columns, side-by-side, with rows representing Video and Audio that are locked together. It's used a lot in documentary TV production (my background), and is well suited to making ads and promo videos for apps. This way you can make sure that the action you are doing and the voice explaining this action are linked together.

## Installation

This should work with any app that previews Markdown with a CSS stylesheet. For a few specific apps:

### BBEdit

You should be able to double-click the "AVScriptFormat.bbpackage" Package file, and it will install. Otherwise, put the CSS file in:

~/Library/Application Support/BBEdit/Preview CSS

### Marked

In Marked > Preferences > Style, click the + button and select the CSS file to import it.

More directions on their site:

[http://marked2app.com/help/Custom_Styles.html]()

### Ulysses

Drag the CSS file into the style preferences table or use the “Add Styles…” button.

More directions on their site:

[http://www.ulyssesapp.com/styles/]()

## Use

The CSS is designed so that an unordered list is shown as video notes on the left, and paragraph items are shown as audio items, on the right. In markdown, this is as simple as:

    - This is Video
    - Another Video action
    
    This is the audio that goes with those two.
    
    - Here's another video action
    
    And here is the audio that goes with that video.
    
    This second paragraph still goes with that video.

## Support

This stylesheet is **officially unsupported.** However, if you want to chat, hit me up on twitter or email, and I'll see what I can do.
