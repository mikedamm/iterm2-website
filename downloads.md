---
layout: default
title: Downloads - iTerm2 - Mac OS Terminal Replacement
active-state: downloads
---

<section>
	<h6 class="question">Stable Releases</h6>
	<a class="download" href="/downloads/stable/iTerm2_v1_0_0.zip">iTerm2 1.0.0 - current stable version</a>
	<p class="answer">
		This is iTerm2 version 1.0.0, the first full releases of iTerm2. 
	</p>
</section>
<section>
	<h6 class="question">Test Releases</h6>
	<a class="download" href="/downloads/beta/iTerm2-1_0_0_20140112.zip">iTerm2 1.0.0.20140112 beta (OS 10.6+, Intel-only)</a>
	<p class="answer">
		This is the recommended beta build for most users. It contains a bunch of bug fixes, including a fix for a crashing bug.  
	</p>
	<a href="#" data-dropdown="drop">&#x25BC; Changelog</a><br><br>
	<div id="drop" data-dropdown-content class="f-dropdown dl-dropdown content">
		<p class="answer">
			<ul>
				<li>Fix a rare crash in ProcessCache</li>
				<li>Convert text to NFC form more aggressively, which should lead to latin characters with accents rendering more consistently with certain fonts like Inconsolata, which lacks some combining marks.</li>
				<li>Update window titles immediately during live resize (bug 2812).</li>
				<li>Don't underline null characters, and fix a bug where underlined characters weren't always drawn correctly in the presence of non-ASCII characters.</li>
				<li>Fix tab order for controls in preferences.</li>
				<li>Update help text for v2.</li>
			</ul>
		</p>
	</div>
</section>
<section>
	<h6 class="question">Nightly Builds</h6>
	<a class="download" href="/nightly/latest"> Latest nightly build</a>
	<p class="answer">
		A nightly build is begun at midnight PST every day and uploaded upon successful completion. If no changes were made, no new build is created. The change log may be seen on Github.
	</p>
</section>