# WoW Guild Professions Tracker

## Installation

Use this link to install the bot onto your server: <a href="https://discord.com/oauth2/authorize?client_id=1377491013677092970">https://discord.com/oauth2/authorize?client_id=1377491013677092970</a>.  You'll need admin privileges on the server you want to use.

## Usage
Create a channel and type <code>!recipes</code> to initialize the main screen for the bot.  (Your original message will be removed by the bot.)
                
<img width="500" src="main.png" />

Click any of the buttons and the bot send a message to you (and you only!) and allow you to mark your recipes for the Discord server.

<img width="500" src="book.png" />

### Roles and Retrictions
By default, invoking the App via <code>!recipes</code> is only available to admins.  Any user can interact with the App by pressing a profession button to mark whether or not they have profession recipes.

You can define a role for interacting with the App via the <code>!setrole "role name"</code> command.  Now, in order for any of your users to use the App, they will need to have this role set.  Anyone with the role will be able to invoke <code>!recipes</code> and mark recipes as owned.

To remove this restriction and restore default behavior, use <code>!resetrole</code>.  You will have to unset and set to assign a different role to the App.

### Welcome Message Customization
The <code>!recipes</code> command's message can be customized through two additional commands, <code>!settitle</code> and <code>!setmessage</code>.  The following uses will configure the recipes' message to read like the above screenshot:

<code>!settitle Welcome to the Guild Professions Tracker!</code>

<code>!setmessages Click a recipe button to open the guild ownership book. You can also enter any recipes you own.</code>

## Frequently Asked Questions

#### Do I need to set my recipes for each server that I'm on?
Yes.  Because a server usually signifies a guild, your recipe data is stored per server.  This allows the same Discord account to have recipes for multiple factions and WoW servers!

#### How are new recipes added to the app?
If you want new recipes added, leave a response on this Google Form: <a href="https://docs.google.com/forms/d/e/1FAIpQLSfH2Jm-jeN89_lrcyDUp2zZL9S_YSyaEstQzcEgTQl-yv_nZw/viewform?usp=dialog"></a>.  Note: the bot also has a button with a link to the same form.

#### What's the quickest way to view who owns a specific recipe?
You can search through each profession's recipes list.  The App will only show you a set number at a time due to Discord restrictions.  However, the App also lets you perform a text search via a modal.  The modal can be triggered through a search button which should be located at the bottom of every message the App sends.

#### I've got another question or issue, how do I contact you?
There's a support Discord for any additional questions and concerns.  Join here: <a href="https://discord.gg/MCauqfP9Qg">https://discord.gg/MCauqfP9Qg</a>

## Privacy Policy
<a href="https://wow-gpt.github.io/docs/privacy.html">https://wow-gpt.github.io/docs/privacy.html</a>

## Terms of Service
<a href="https://wow-gpt.github.io/docs/tos.html">https://wow-gpt.github.io/docs/tos.html</a>

