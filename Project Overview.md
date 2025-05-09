## Initiation

- [ ] Project Brief
	- Taking over the abandoned RPG Manager obsidian plugin development, fix bugs, make improvements
### Goals
- [ ] Scope/Deliverables
	- Keep it simple. Do small, completable projects. Dream big later, get something done now.
	- Accessible/extensible code base. Easy for us to work on, and accessible to contributors
- [ ] Success Criteria
	- The plugin can be used to track worldbuilding and state of an RPG at the most generic level
	- A user can, within the plugin, add their on features to player characters/classes/races that reflect their system
	- The codebase is welcoming (not daunting)
	- The plugin is easy to use and is robust against common points of failure (like making a new file, closing/opening Obsidian)
- [ ] Quality
	1. Make it work
		- make it actually usable, no bugs/awful annoying occurrences
		- make it work for GMs
	2. Make it good
		- Add option for Races
		- Easy to add own features/templates
	3. Make it purr
		- make the interfaces have useful buttons and evaluated/linked formulas
### Resources
- [x] Team
	- Jack
	- William
- [x] Budget
	- Nil
- [ ] Time
	- #TODO Decide time constraints
### Motive/Benefit
- [ ] Value
	- Solve problems with the plugin
	- Make a better feature set
### Stakeholders
- [ ] List stakeholders
	- RPG Manager Users
		- Jack
		- William
## Planning

- [ ] Schedule
	- [x] Start date
		- [[2025-05-09]]
	- [ ] Milestones
		- [ ] Phase 0: Make your own plugin to understand Obsidian Plugins
		- [ ] Phase 1: Replicate existing system
		- [ ] Phase 2: Add features
	- [ ] End date
		- #TODO
	- [ ] Timeline
		- [ ] Make a network of each subtask showing dependencies. Each node has a start/end date. Nodes are connected to their dependencies. Some tasks or groups of tasks may therefore happen in parallel.
		- [ ] "Critical Path" - The single path through the timeline of dependencies that will take the longest. If tasks can be done in parallel, this path is the most important to stay on target because delays on it will necessarily slow down the project.
		- [ ] Add buffers for subtasks based on difficulty, complexity, or a reliance on people I can't control
		- Try to replicate rendering without cursed implementation
			- "replicate" doesn't have to be exact as long as its better
			- doesn't have to be data-driven yet
			- Both Jack and William separately implement a proof of concept
				- Done by [[2025-05-31|end of May]] and meet back up to share results
		- Usable UI
			- Evaluate what the UI should look like
				- one integrated view (no sidebar)
				- not textbox-based (no save button, and other obsidian tools will work on text)
				- Consider connected formulas
- [ ] Risk Management Plan
	- [ ] List every single reason your project is likely to fail, roughly in order of likelihood
		- Motivation
			- #TODO Jack, I'm seeking feedback on the following thrown together:
			- Check in with each other and consider at least the following ideas
				- Trading tasks
				- Taking a break from development
				- Managing motivation by
					- sharing progress with each other
					- sharing progress with an interested community on reddit or a discord group for obsidian or TTRPGs or something
		- Technical limitations
			- It seems unlikely we'll face technical limitations, since we're given ✨javascript✨, but
			- if we realize we've backed ourselves into a corner, discuss how far deep we've dug ourselves and how much work we'd lose by going a different direction
				- Keep in mind that one priority of this project is to have a sensible, accessible code base. Allowing dug holes to become graves should be avoided.
		- Deprioritization
			- Decide whether to commit to the project or change priorities
			- If this project is being paused rather than killed, schedule when to reevaluate and either revive, abandon, or again rain check the project
	- [ ] For every threat, write an action plan for what you can do starting right away to make sure those threats don't happen

## Execution

- Make it as fun as possible. Whatever parts of the project aren't enjoyable, can you find a way to not do them?
- Accountability/tracking for completion
	- When will you track updates to this project and reflect on where you are in this plan?
	- How will you celebrate milestones?
- Consistency is more important than intensity

## Closing

- [ ] Write up closing report
	- Address success criteria
	- Compare outputs to goals
	- Evaluate any changes to anticipated value
- [ ] Write up lessons learned
	- Specific technological lessons learned
	- Any unanticipated threats that affected the project