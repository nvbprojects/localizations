<p><strong><span class="wysiwyg-font-size-large">Help us Translate Postbox 5! It's Easy!</span></strong></p>
<p>We've open-sourced our translations, so that anyone can help with untranslated texts, and suggest changes to existing translations too.</p>
<p>Languages currently being translated include: German, French, Spanish (Spain), English (British), Italian, Dutch, Portuguese (Brazilian), Russian, and Swedish.</p>
<p><strong><span class="wysiwyg-font-size-large">Postbox 5 Translation Build</span></strong></p>
<p>Please download and install this special Mac translation build, which contains all of the languages specified above:</p>
<p><a href="http://postbox-downloads.s3.amazonaws.com/mac/postbox-5.0b1-mac64-translate.dmg" target="_blank">Postbox 5 Mac OS X Translation Build</a></p>
<p>Note: we currently do not have a Windows beta available yet.</p>
<p><strong><span class="wysiwyg-font-size-large">Getting Started</span></strong></p>
<ol>
<li>Create a <a href="https://github.com" target="_blank">GitHub</a> account (if you do not already have one).</li>
<li>Download and install the <a href="https://desktop.github.com" target="_blank">Mac</a> or <a href="https://desktop.github.com" target="_blank">Windows</a> GitHub apps, and then under <em>Settings</em>, log into your GitHub account.</li>
<li>Visit our <a href="https://github.com/postbox/localizations" target="_blank">Postbox Localizations</a> project on GitHub, click on the <em>Fork</em> button in the upper right, then fork the repository to your account.</li>
<li>On the <a href="https://github.com/postbox/localizations" target="_blank">Postbox Localizations</a> page, click on the <em>Clone or Download</em> button, then select <em>Open in Desktop</em>.<br /><br /><img src="http://postbox-images.s3.amazonaws.com/github/git-1.png" alt="" width="525" height="341" /><br /><br /></li>
<li>Specify a directory to store the localization files.</li>
</ol>
<p> <strong><span class="wysiwyg-font-size-large">How to Translate</span></strong></p>
<ol>
<li>Go to the GitHub desktop application, and from the <em>Repository</em> menu select <em>Pull</em>.</li>
<li>Find an editor that can search through a lot of files at once. We like using <a href="https://atom.io" target="_blank">Atom</a> (it's free!).</li>
<li>Download and install the Postbox application, install a sample email account, then go to the File menu > Languages > select your language. Then restart Postbox.</li>
<li>Look through Postbox's:
<ul>
<li>main interface - all of it's windows, folder names, button names, etc.</li>
<li>every menu and sub-menu</li>
<li>every Preference panel and sub panel</li>
<li>look through the localization files themselves to find untranslated texts</li>
</ul>
<li>Once you see an untranslated string, search your language directory for the files that contain that string. (Please be sure that you are localizing within the correct directory, as we have several languages!) <br /><br />Typically you would work out of and search through the mail directory for your language. For example, if you are Italian, you would work out of this directory:<br /><em><br />localizations directory &gt; it &gt; mail<br /><br /></em></li>
<li>Change the string(s) and save your work in Atom.</li>
</ol>
<p><strong><span class="wysiwyg-font-size-large">What and What NOT To Translate</span></strong></p>
<p>A word for the German translators: please use the formal addressing of the user, meaning the use of "Sie" instead of "du".</p>
<p>There are some things that should not be translated including:</p>
<ul>
<li><strong>Non-Mail Strings</strong> - Don't worry about translating or suggesting changes to files outside of the mail directory as those are all inherited from the mozilla translations.</li>
<li><strong>%S, %1$S, %2$S </strong>- anything that looks like this with a % in it means it's a place holder for a string to get substituted in dynamically (such as "You have %1$S unread messages") and needs to remain in the translated string.</li>
<li><strong>Branding Strings</strong> - for instance Postbox should not be translated</li>
<li><strong>Command Keys</strong> - entities and properties that end in .key and .commandKey. These are supposed to be the same throughout all translations.</li>
<li><strong>Interface Sizes</strong> - entries like 36em or width: 45em; height: 32em. These define the size of dialogs and are there for you to adjust the dialogs if needed by your localization. Translating them will only make them stop working.</li>
<li><strong>true / false </strong>- several entities have values like true or false - these are actually used to effect the behavior and are not strings to translate.</li>
<li><strong>Product URLs </strong>- urls to Postbox product pages such as release notes, the start page, etc.</li>
<li><strong>Numbers</strong> - if the string is just a number like 900 or 900ch or 900em do not translate it.</li>
</ul>
<p> <strong><span class="wysiwyg-font-size-large">How to Submit Changes</span></strong></p>
<ol>
<li>Within the GitHub application, click on the <em>Changes</em> or <em>Uncommitted Changes</em> tab at the top the application window. Here you will see all of the changes that you have made.</li>
<li>In the lower left, provide a summary and description of the changes you've made, then click on the <em>Commit</em> button.</li>
<li>Finally, click on the <em>Pull Request</em> button at the top, enter a title and/or description, then click the <em>Send Pull Request</em> button.</li>
</ol>
<p><span class="wysiwyg-font-size-large"><strong>FAQ</strong></span></p>
<p><strong>Why is my language not listed?</strong></p>
<p>We are just getting our localization process going and have picked the current set of languages to start with as we test out our system. Over time we'll be adding more locales as we all get more comfortable with the system.</p>
<p><strong>How can I help translate the website?</strong></p>
<p>Right now we are focused on getting the product translations up and running before tackling the website.</p>
