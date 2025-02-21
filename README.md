
<div align="center">
	<img src="img/icon.png" width="128" height="128">
	<br>
	<img src="docs/images/logo-text-trans.png" width="391" height="66">
	<br>
	A <b>Text to Speech Voice Reader</b> extension for your browser!
</div>

<div align="center">
	<a href="https://chrome.google.com/webstore/detail/read-aloud-a-text-to-spee/hdhinadidafjejdhmfkjgnolgimiaplp">Chrome Web Store</a> | <a href="https://addons.mozilla.org/en-US/firefox/addon/read-aloud/">Firefox Addon</a> | <a href="https://blog.readaloud.app/">Blog</a> | <a href="https://readaloud.app/">Website</a> 
</div>

<br>

<div align="center">
    <br> github stats:
    <img src="https://badgen.net/github/stars/ken107/read-aloud" >
    <img src="https://badgen.net/github/open-issues/ken107/read-aloud" >
    <img src="https://badgen.net/github/open-prs/ken107/read-aloud" >
    <img src="https://badgen.net/github/tag/ken107/read-aloud" >
    <img src="https://badgen.net/github/license/ken107/read-aloud/" >
    <br> chrome web store stats:
    <img src="https://badgen.net/chrome-web-store/users/hdhinadidafjejdhmfkjgnolgimiaplp" >
    <img src="https://badgen.net/chrome-web-store/rating/hdhinadidafjejdhmfkjgnolgimiaplp" >
    <img src="https://badgen.net/chrome-web-store/rating-count/hdhinadidafjejdhmfkjgnolgimiaplp" >
    <img src="https://badgen.net/chrome-web-store/v/hdhinadidafjejdhmfkjgnolgimiaplp" >
    <br> firefox addon stats:
    <img src="https://badgen.net/amo/users/read-aloud" >
    <img src="https://badgen.net/amo/rating/read-aloud" >
    <img src="https://badgen.net/amo/reviews/read-aloud" >
    <img src="https://badgen.net/amo/v/read-aloud" >
</div>

<br>

<div align="center">
	<sub>A little browser extension built with ❤︎ by <a href="https://github.com/ken107">Hai Phan</a> and <a href="https://github.com/ken107/read-aloud/graphs/contributors">contributors</a> </sub>
</div>

<hr />

## Reviews
>First impressions are super. Natural flowing voice and very helpful for multitasking and also giving my eyes a rest. 

*Giuseppe*

> Thank you so much for this extension. I absolutely swear by it whenever I need to read any large chunk of text. The combination of hearing it in a clear voice (...)  Its fantastic, thank you so much.

*Abi*

> LOVE this extension. I remember better when i hear a story vs reading

*David*

> This is a phenomenal extension. Better than anything else I tryed so far. Simple, easy, customizable (...) I would recommend this whole heartedly to anyone who has dyslexia like me, or any other reasons for not beeing able to read comfortably at all times.

*Merlin*

---

## UPDATE

Using this for reading a lot of code? I decided to fork the repository, and 
add an option to avoid reading certain characters (`<` and `>` at the moment).

This is only the case for selected text, but if I keep using the plugin I'll 
add some options to make this usable for anyone, and probably extend it to 
use the same exclusions on the whole page read.

Watch this space.

NB: The file that's been modified is:

- `js/content/html-doc.js`

Specifically the `ignoreTags` variable has had the `pre` tag added to it, and 
the `getSelectedText` function has had the regex for removing `<` and `>` 
characters added to it.

---


## Overview
Read Aloud is a Chrome and Firefox extension that uses text-to-speech technology to convert webpage text to audio.&nbsp; It works on a variety of websites, including news sites, blogs, fan fiction, publications, textbooks, school and class websites, online universities and course materials.

Read Aloud is aimed at users who prefer to listen to content instead of reading, people with dyslexia or other learning disabilities, children learning to read, or simply to provide users with alternative way to consume web content.

Read Aloud allows you to select from a variety of text-to-speech voices, including those provided natively by the browser, as well as by text-to-speech cloud service providers such as Google Wavenet, Amazon Polly, IBM Watson, and Microsoft.&nbsp; Some of the cloud-based voices may require additional in-app purchase to enable.

## Basic Usage

### Extension Button
<img src="docs/images/demo-extension-button.gif">

### Right Click Menu
<img src="docs/images/demo-right-click.gif">


## Advanced Usage

### Shortcuts

```yaml
ALT/Option + P           : Play/Pause
ALT/Option + O           : Stop
ALT/Option + Comma       : Rewind
ALT/Option + Period      : Forward
```

### Customization

You can change the voice, reading speed, pitch, or enable text highlighting:

1. Click the Read Aloud icon on the [Extensions menu](https://i.imgur.com/KTqFZ3Q.png).
2. Stop any text that may be playing.
3. Click on the Gear icon in the Read Aloud context menu. (It may take a second or two for settings to appear)


### Using Premium Voices
[Using Premium Voices (Google Wavenet & Amazon Polly)](docs/usage/premium-voices.md)


## Installation

### Chrome and Chromium-based browsers
You can get the latest available Read Aloud Extension version from the [Chrome Web Store](https://chrome.google.com/webstore/detail/read-aloud-a-text-to-spee/hdhinadidafjejdhmfkjgnolgimiaplp).

### Firefox
You can get the latest version of Read Aloud Extension from the [Mozilla Add-ons website](https://addons.mozilla.org/en-US/firefox/addon/read-aloud/).

#### Firefox install from source

1. Create a build directory with `mkdir build`
2. Run `npm run-script package`
3. Extract the resulting zip file. You should see a `manifest.json` which will be used later.
4. In Firefox, first make sure there isn't an existing read-aloud add-on already installed
5. type `about:debugging` in the Address bar and enter.
6. Click on "This Firefox" then click "Load Unpackaged Extension"
7. Select the `manifest.json` file produced earlier.

## Contribute

- Star this GitHub repo :star:
- Post about it on your social media (Twitter / Blogs / Facebook / Instagram etc).
- Leave a positive review on the [Chrome Web Store](https://chrome.google.com/webstore/detail/read-aloud-a-text-to-spee/hdhinadidafjejdhmfkjgnolgimiaplp) or [Firefox Addon](https://addons.mozilla.org/en-US/firefox/addon/read-aloud/) pages.
- Create pull requests, submit bugs, suggest new features or documentation updates 🛠 
	- To do so, go to [this page](https://github.com/ken107/read-aloud/issues) and click the *New issue* button.


## Credits

### Images

 - [Streamline Labs](https://lab.streamlineicons.com/)
 - [Freepik](https://www.freepik.com/free-vector/colorful-memphis-design-background-vector_3893585.htm)
