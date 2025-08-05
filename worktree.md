Add a new worktree: `git worktree add <path-to-new-worktree> <branch>`<br/>
Creates new folder in the path-to-new-worktree and from the branch specified. (cant create new worktree of the branch youre currently in. `git worktree add ../newTree main` doesnt work if it's already in the main branch ) then cd to the new directory, do work.
List all worktrees: `git worktree list`<br/>
Remove a worktree: `git worktree remove <path-to-worktree>`<br/>
Prune worktrees: `git worktree prune`<br/> (Removes references to worktrees that are no longer valid.)
