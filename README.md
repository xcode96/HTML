Wxmp

A Chrome extension that optimizes posting articles in WeChat Official Accounts.
When copying and pasting, the font-family CSS styles are carried over, which get filtered out by WeChat and result in broken formatting.
This extension removes the font-family style from all HTML nodes before submission, so that the pasted styles remain consistent.

Currently, it removes font-family styles from the following tags:

code, pre, h1, h2, h3, h4, h5, h6, p, div, span

Features Implemented

 Remove font-family

 Code highlight area has background color

 Code highlight area has horizontal scrollbars (forces no line wrapping)

 Adds iOS elastic scrolling

 Add title-setting tool

 Add text highlighting tool

 Add strikethrough tool, e.g. <del>strikethrough</del>

Direct Installation

Download the extension file Wxmp.crx

In Chrome, go to chrome://extensions/

Drag the Wxmp.crx file into the Extensions page

Developer Mode Installation

Download and unzip the package

In Chrome, go to chrome://extensions/

Click Load unpacked extension...

Select the plugin’s directory

Usage

Open the WeChat Official Accounts platform, create a new article, and paste your content into the editor

Click the WeChat icon in the top-right corner

In the pop-up modal, click the Delete button

If successful, a message will appear after the button: Change successful!!
