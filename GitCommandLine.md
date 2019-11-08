# Git Kata
Learn Git Command Line with FizzBuzz!
There are two sets of instructions. One for the Command Line, which is useful to know. Another for Visual Studio 2019. Either participant can use either instruction set. 
These can be alternated between as well. It's not one or the other.

### Objective
Experience Git while pair programming. There should be no merge issues. That's a future lesson.

### Basic Usage
This lession is focused on the basic push/pull mechanism of git. 
We have to use a small amount of git's branchin functionality, but not extensively.

#### The work
We will do "remote" Pair Programming, sitting right next to each other.
We will use Test-Ping-Pong. Instead of passing the keyboard and mouse back and forth, we will pass the source code back and forth.
Both participants need their computer. No need for shared monitors.
We will continue to sit next to each other for communication and conversation purposes without the need for headset/mic setups.

There's already a solution `GitPractice.sln` that can be opened once the project is pulled down.

## Command Line
* Person-A
    * Clone this repository.
        * `git clone https://github.com/Fyzxs/GitKata.git`
    * Navigate into the created directory
        * `cd GitKata`
    * Create a branch
        * `git branch [UniqueNameNoSpaces]`
    * Switch to the new branch
        * `git checkout [UniqueNameNoSpaces]`
    * Open solution
    * Write a failing test
    * at the Command Line
        * `git status`
            * This shows all modified files
        * `git add .`
            * This stages all files that have changed (shown in `git status`)
        * `git commit -m "First Failing test"`
            * This commits the staged files.
        * `git status`
            * See that there are no more changed files.
        * `git push -u oigin`
            * This will push the changes, the 'commit', to the server and create the branch.
* Person-B
    * Clone this repository.
        * `git clone https://github.com/Fyzxs/GitKata.git`
    * Checkout the branch created
        * `git checkout [UniqueNameNoSpaces]`
    * Open the Solution
    * Make the test pass
    * Commit the change
        * `git add .`
        * `git commit -m "First Test Passes"`
    * Write a failing test
    * Commit the change
        * `git add .`
        * `git commit -m "Second Failing Test"`
    * Push the change
        * `git push`

# From here it is the same for each participant

* Person-BOTH
    * Pull down the changes
        * `git pull`
            * This pulls down the changes made for a branch you already have
    * Make the test pass
    * Commit the change
        * `git add .`
        * `git commit -m "[NUMBER OF] Test Passes"`
    * Write a failing test
    * Commit the change
        * `git add .`
        * `git commit -m "[NEXT NUMBER OF] Failing Test"`
    * Push the change
        * `git push`
