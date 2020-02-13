Use a clear and descriptive title for the issue to identify the problem.
Describe the exact steps which reproduce the problem in as many details as possible. For example, start by explaining how you started Atom, e.g. which command exactly you used in the terminal, or how you started Atom otherwise. When listing steps, don't just say what you did, but explain how you did it. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut or an Atom command, and if so which one?
Provide specific examples to demonstrate the steps. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use Markdown code blocks.
Describe the behavior you observed after following the steps and point out what exactly is the problem with that behavior.
Explain which behavior you expected to see instead and why.
Include screenshots and animated GIFs which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, record the GIF with the Keybinding Resolver shown. You can use this tool to record GIFs on macOS and Windows, and this tool or this tool on Linux.
If you're reporting that Atom crashed, include a crash report with a stack trace from the operating system. On macOS, the crash report will be available in Console.app under "Diagnostic and usage information" > "User diagnostic reports". Include the crash report in the issue in a code block, a file attachment, or put it in a gist and provide link to that gist.
If the problem is related to performance or memory, include a CPU profile capture with your report.
If Chrome's developer tools pane is shown without you triggering it, that normally means that you have a syntax error in one of your themes or in your styles.less. Try running in Safe Mode and using a different theme or comment out the contents of your styles.less to see if that fixes the problem.
If the problem wasn't triggered by a specific action, describe what you were doing before the problem happened and share more information using the guidelines below.

Consider starting the commit message with an applicable emoji:
🎨 :art: when improving the format/structure of the code
🐎 :racehorse: when improving performance
🚱 :non-potable_water: when plugging memory leaks
📝 :memo: when writing docs
🐧 :penguin: when fixing something on Linux
🍎 :apple: when fixing something on macOS
🏁 :checkered_flag: when fixing something on Windows
🐛 :bug: when fixing a bug
🔥 :fire: when removing code or files
💚 :green_heart: when fixing the CI build
✅ :white_check_mark: when adding tests
🔒 :lock: when dealing with security
⬆️ :arrow_up: when upgrading dependencies
⬇️ :arrow_down: when downgrading dependencies
👕 :shirt: when removing linter warnings
