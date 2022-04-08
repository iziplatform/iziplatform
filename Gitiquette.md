# Gitiquette - Draft

## Always work on a branch (never commit on master)
  If the origin of the PR would be a ticket, create a branch with its number. (INCxxx, SRQxxx, CHxxx)


## In order to keep our Git organisation maintainable, readable and usable by all engineers we use a strict structure on repository naming.
<pre>
   team-location-project-repository-name
   |                |         | 
   |                |         |->¸ A short description of your repository, optionally separated by hyphens (-).
   |                |
   |                |->¸ The current project this  applies to.
   |
   |->¸ The Git team that own your repository.
</pre>
**migration-pt-automation-**
   
## Repository Name
  The name of your repository, short but descriptive.

  Good examples:<br/>
    recycling-app-frontend<br/>
    poverty-awareness-functions<br/>



## Commit messages are recommended to following the following similar to PRs:
   [FEAT]     : Introducing a new features.<br/>
   [FIX]      : This is essentially a patch to fixes, hotfixes, etc. <br/>
   [DOC]      : Any changes to the documentation. Examples: Cli-help, readme, tutorial, documentation, CHANGELOG, etc.<br/>
   [STYLE]    : Feature and updates related to styling.<br/>
   [REFACTOR] : Refactoring a specific section of the codebase.<br/>
   [TEST]     : Everything related to testing.<br/>
   [CHORE]    : Regular code maintenance.<br/>



## How to write good commit messages
Capitalized, short (50 chars or less) summary

More detailed explanatory text, if necessary.  Wrap it to about 72
characters or so.  In some contexts, the first line is treated as the
subject of an email and the rest of the text as the body.  The blank
line separating the summary from the body is critical (unless you omit
the body entirely); tools like rebase can get confused if you run the
two together.

Write your commit message in the imperative: "Fix bug" and not "Fixed bug"
or "Fixes bug."  This convention matches up with commit messages generated
by commands like git merge and git revert.

Further paragraphs come after blank lines.

- Bullet points are okay, too

- Typically a hyphen or asterisk is used for the bullet, followed by a
  single space, with blank lines in between, but conventions vary here

- Use a hanging indent

If you use an issue tracker, add a reference(s) to them at the bottom,
like so:

Resolves: #123

## Useful Links:
https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/
https://chris.beams.io/posts/git-commit/
