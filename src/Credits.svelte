<script>
	import discord from './img/discord-logo.svg'
	import github from './img/github-logo.png'

	const changelogLastUpdated = window.__SNOWSTAMP_CHANGELOG_LAST_UPDATED__
</script>

<div class="credits">
	<p class="disclaimer">
		© 2024 Jason Yu. All rights reserved. This tool is open-source. View the
		source code on <a href="https://github.com/your-repo" target="_blank"
			>GitHub</a
		>.
	</p>
</div>

<style>
	.credits {
		color: #777;
		text-align: center;
		font-size: 1em;
		margin: auto auto 10px;
	}
	:global(body.dark-mode) .credits {
		color: #bec2cc;
	}

	code {
		font-family: 'Fira Code', monospace;
		font-size: 0.9em;
		padding: 0.2em 0.3em;
		background: #f4f4f4;
	}

	:global(body.dark-mode) code {
		color: #bcc5d7;
		background: #2f343a;
	}

	span {
		display: inline-block;
	}

	a.github img {
		position: relative;
		margin-right: 2px;
		top: 5px;
		margin-top: -5px;
	}

	:global(body.dark-mode) a.github img {
		filter: invert();
	}

	.disclaimer {
		font-size: 0.9em;
		color: #88939f;
	}
</style>
