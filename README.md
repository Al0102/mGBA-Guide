# Overview of the mGBA Guide

This guide takes you through the process of getting started
with the [**mGBA**](https://mgba.io/) emulator. The goal for this is to
take you through the basics of setting up games with mGBA
and configuring common settings.

[**mGBA**](https://mgba.io/) is a popular desktop emulator for the [**Game Boy Advance (GBA)**](https://en.wikipedia.org/wiki/Game_Boy_Advance) system. It offers a relatively simple setup, as well as many options for configuring it to suit more specific needs.

In this guide, you will find information about:

- Installing mGBA and loading game ROMs.
- Setting up keyboards and gamepads.
- Configuring audio and display options.
- Patching ROM hacks.

# How we collaborated

We worked together over two weeks through a mix of Discord,
Google Docs, and in-person meetings. We organized this through
constant communication across these channels, ensuring that each of
us knew what we had and what was still needed.

To develop the guide, we used Git for version control and Github
to share the code. We separated our roles based on the main pages
([see above](#overview-of-the-mgba-guide)) to reduce conflicts,
then edited them together to improve cohesion and consistency.

# How we created our guide

This guide was built on our experience with using mGBA and other
emulators over the years. We also referenced
[this guide](https://fantasyanime.com/emuhelp/mgba) to further
round out our knowledge. We tried to write the guide by reflecting
on our first experiences with mGBA in order to lower the barrier
of entry to those new to emulation or even gaming in general.

## MkDocs

We chose MkDocs to generate our static site because of the
ease of writing that Markdown offers, a relatively simple setup,
the versatility of the components/extensions provided.
[Material for MkDocs](https://github.com/squidfunk/mkdocs-material) also
provided for thorough customization of the site themes.

This allowed us to focus on writing better content, rather than
building the site.

## Markdown

Although we had learned Markdown in the past, neither of us
have written any extensive documentation. We learned common
practices and how to style documents from our COMM 2116
Business Communications 2 course, as well as by referencing
[the Material for MkDocs guide](https://squidfunk.github.io/mkdocs-material/getting-started/)
and other existing documentation.

## GitHub Pages

We used GithHub Pages to host the static site, as MkDocs offers
a command-line utility to automatically build the site and deploy
it. Furthermore, we were already using GitHub to collaborate,
so we could reduce the need for using another site.

## Developing a style guide

Given that the guide is not especially long, we decided to write
a small style guide for the site. It vaguely follows Microsoft's
[writing style guide](https://learn.microsoft.com/en-us/style-guide/welcome/),
but is largely just based on personal preferences.

### Annotations and typography

Considering that our guide focuses mostly on
interacting with graphical interfaces and navigating settings,
we decided on the following conventions to maximize
readability and understanding of the processes.

- **Bolded** words represent actions or important ideas.
- *Italicized* words represent elements on the screen or relevant concepts.
- `Blocks` represent file names or text you might input.  
- <kbd>Keyboard</kbd> + <kbd>annotations</kbd> represent a key or combination of keys to input on your keyboard.
- The following example represents a series of actions/elements to follow to complete a goal (left-to-right):

    > File > Option > Sub-option > Feature

In addition to these, we took advantage of MkDocs admonitions to provide
relevant information that is separate from the tasks themselves. These
are also useful for bringing attention to important details, as they stand out
from the regular text.

![MkDocs Admonitions](/docs/assets/general/admonition.png "Admonitions")

# Conclusion

This guide was written out of a love for video games.
We are hoping to make it easier for people to get into emulation,
and provide tips on enhancing the experience.

Writing this also provided us with the opportunity to practice developing
clear and complete documentation, which will be useful in future
projects.

We appreciate you taking the time to read this and hope that we
improved your experience with setting up mGBA.

This guide was built using: [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
