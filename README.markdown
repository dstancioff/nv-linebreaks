# nvAlt with Markdown without double-space line endings
This fork of [nvAlt][nvalt] replaces newlines with <br/>, similar to GitHub flavored Markdown, instead of the two space end of line requirement of traditional markdown.

In this build, this:
    One
    Two
    Three
 
 Will preview as this:
     <p>One<br />
     Two<br />
     Three</p>
     
Without the need to suffix each line with two spaces.