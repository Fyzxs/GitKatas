## Through Visual Studio
*Git Practice with Visual Studio 2019*

* Person-A
    * Clone the repository
    
      |||
      |-|-|
      |Open Vusial Studio 2019||
      |Click "Clone or checkout code" | ![CloneCode](images/CloneCode.PNG)|
      |Put this Repository Path "https://github.com/Fyzxs/GitKata" into the "Repository location" field | ![RepositoryLocation](images/RepositoryLocation.PNG)|
      |Customize "Local path" as desired.| ![LocalPath](images/LocalPath.PNG)|
      |Click "Clone" | ![ClickClone](images/ClickClone.PNG)|
    * Open The Solution
    
      |||
      |-|-|
      |Once the Clone is complete, Click on "Switch Views"|![SwitchViews](images/SwitchViews.PNG)|
      |Click on "GitPractice.sln"|![SwitchViewsSln](images/SwitchViewsSln.PNG)|
    * Create a Branch
    
      |||
      |-|-|
      |Click on "master" at the bottom right of the Visual Studio window||
      |Click on "New Branch"         |![IdeMaster](images/IdeMaster.PNG)|
      |Enter a [UniqueNameNoSpaces]  |![IdeNewBranch](images/IdeNewBranch.PNG)|
      |Have "Checkout Branch" checked|![BranchName](images/BranchName.PNG)|
      |Click "Create Branch"         |![CheckoutBranchChecked](images/CheckoutBranchCheck.PNG)|
    * Write a failing test
    * Commit the change
    
      |||
      |-|-|
      Go to Team Explorer Tab                     |![TeamExplorerTab](images/TeamExplorerTab.PNG)
      Go to the "Changes" view                    |![GotoChanges](images/GoToChanges.PNG)
      Enter a Commit Message "First Failing Test" |![CommitMessage](images/CommitMessage.PNG)
      Click "Commit All"                          |![CommitAll](images/CommitAll.PNG)
    * Push changes to server
    
      |||
      |-|-|
      Go to the "Sync" view |![GotoSync](images/GotoSync.PNG)
      Click either "Push"   |![Push](images/Push.PNG)
* Person-B
    * Clone the repository
    
      |||
      |-|-|
      |Open Vusial Studio 2019||
      |Click "Clone or checkout code"                                                                 |![CloneCode](images/CloneCode.PNG)|
      |Put this Repository Path "https://github.com/Fyzxs/GitKata" into the "Repository location" field|![RepositoryLocation](images/RepositoryLocation.PNG)|
      |Customize "Local path" as desired.                                                             |![LocalPath](images/LocalPath.PNG)|
      |Click "Clone"                                                                                  |![ClickClone](images/ClickClone.PNG)|
    * Open The Solution
    
      |||
      |-|-|
      |Once the Clone is complete, Click on "Switch Views"|![SwitchViews](images/SwitchViews.PNG)|
      |Click on "GitPractice.sln"|![SwitchViewsSln](images/SwitchViewsSln.PNG)|
    * Switch to the Branch
    
      |||
      |-|-|
      Click on "master" at the bottom right of the Visual Studio window|![IdeMaster](images/IdeMaster.PNG)
      Click "Manage Branches"                                          |![IdeManageBranches](images/IdeManageBranches.PNG)
      Expand "remotes/origin"                                          |![RemotesOrigin](images/RemotesOrigin.PNG)
      Double Click on the created branch [UniqueNameNoSpaces]          |![PairBranch](images/PairBranch.PNG)
    * Make the test pass
    * Commit the change
    
      |||
      |-|-|
      Go to Team Explorer Tab                     |![TeamExplorerTab](images/TeamExplorerTab.PNG)
      Go to the "Changes" view                    |![GotoChanges](images/GotoChanges.PNG)
      Enter a Commit Message "First Failing Test" |![CommitMessage](images/CommitMessage.PNG)
      Click "Commit All"                          |![CommitAll](images/CommitAll.PNG)
    * Push changes to server
    
      |||
      |-|-|
      Go to the "Sync" view|![GotoSync](images/GotoSync.PNG)
      Click either "Push"  |![Push](images/Push.PNG)


# From here it is the same for each participant

* Person-BOTH
    * Pull down the changes
    
      |||
      |-|-|
      Go to the "Sync" view |![GotoSync](images/GotoSync.PNG)
      Click either "Pull"   |![GetChanges](images/GetChanges.PNG)
    * Make the test pass
    * Commit the change
    
      |||
      |-|-|
      Go to Team Explorer Tab                     |![TeamExplorerTab](images/TeamExplorerTab.PNG)
      Go to the "Changes" view                    |![GotoChanges](images/GotoChanges.PNG)
      Enter a Commit Message "First Failing Test" |![CommitMessage](images/CommitMessage.PNG)
      Click "Commit All"                          |![CommitAll](images/CommitAll.PNG)
    * Write a failing test
    * Commit the change
    
      |||
      |-|-|
      Go to Team Explorer Tab                     |![TeamExplorerTab](images/TeamExplorerTab.PNG)
      Go to the "Changes" view                    |![GotoChanges](images/GotoChanges.PNG)
      Enter a Commit Message "First Failing Test" |![CommitMessage](images/CommitMessage.PNG)
      Click "Commit All"                          |![CommitAll](images/CommitAll.PNG)
    * Push changes to server
    
      |||
      |-|-|
      Go to the "Sync" view |![GotoSync](images/GotoSync.PNG)
      Click either "Push"   |![Push](images/Push.PNG)