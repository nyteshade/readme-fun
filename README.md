# readme-fun
Playing with README.md and markdown tricks

## Copy code block to clipboard

<span style="cursor: pointer;" onclick="navigator.clipboard.writeText(document.querySelector('#brew').innerHTML.trim())">📋</span><code id="brew" style="padding:0.25em 0.1em 0.25em 0">
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
</code>
