Initial analysis of the source repo gave the impression that it was going to be a spaghetti-mess nightmare, but further digging revealed method to the madness.

For example, using React seemed to be overkill for this sort of project, but it seems to be quite commonly used in other Obsidian plugins. This leaves begs the question of what the alternatives would be? The Obsidian documentation has a guide for using Svelte, but with the level of complexity inherit to this scale of project, a robust framework like React is necessary. Furthermore, one could argue that using a framework such as React is worth the time investment required to build it into the project.

The other main misconception was that having the plugin controls be embedded entirely in a codeblock in the note seemed to be a questionable decision. The reasoning was not obvious at first, but through further contemplation and reading, it seemed an elegant solution for the *original author's* workflow. Although it can be clunky to use, it isn't without merit. Not having to use the sidebar or a separate tab does make it more convenient to edit the details in a visual manner.

Despite these solid benefits, that does not mean that it is the only option worth using. The argument to build out a single-page dashboard and perhaps even expand the sidebar still stand. It does extend beyond the scope of the original project, but that does not mean scope cannot be modified. In fact, great projects tend to start small and grow over time.

