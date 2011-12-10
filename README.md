If you have a script named git-something in your $PATH, and you call git something, 
Git will actually automatically call the script for you. It makes easy integration with your git command.

# git playback
Replay a number of commits until back to HEAD. Basically doing a checkout every given seconds.
Handy if you have a editor that refresh automatically as you can actually see the changes in your code replayed.

#### Usage
git playback <number of commmits> [<interval in seconds>]