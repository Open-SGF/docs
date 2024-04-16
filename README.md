# Open SGF Hub

A centralized space for all of Open SGF operations. Including documentation, guides and details of projects and contributors.

## Contributing

It's recommended that you clone this repo and use either [VS Code](https://code.visualstudio.com/) or [Obsidian](https://obsidian.md/) to make edits.
Both of these tools should help automatically apply the formatting rules we apply for all pull requests (formatting rules are applied via [Prettier](https://prettier.io/))

### Obsidian Setup

- Open the cloned repository as a vault
- Go to Settings -> Community Plugins -> Turn on community plugins
- Click the Browse button
- Manually install the following plugins
	- [File Hider](obsidian://show-plugin?id=OA-file-hider)
	- [Format with Prettier](obsidian://show-plugin?id=format-with-prettier)

### Formatting the entire project

- `npm install` (Recommended to use npm 10.x and node 20.x)
- `npm run lint:fix`
