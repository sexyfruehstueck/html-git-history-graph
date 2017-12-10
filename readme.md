# A HTML Canvas Git History Graph 
## Versionnumber 1.0.0 (2017-12-10)
(***Documentation last update 2017-12-10 21:45***)  

HTML Canvas Git History Graph, to create fast and nice history graphs.  
![Screenshot of a small git history graph](https://raw.githubusercontent.com/sexyfruehstueck/html-git-history-graph/master/readme/screenhot.png)

## Features
* create Graph
  * initialize Repo
  * create feature branch
  * create hotfix branch
  * create release branch
  * tagging

## Roadmap / Future Features
* code cleanup

## Known Bugs
* none

## Usage

## SourceControl Link & Information
git@github.com:sexyfruehstueck/html-git-history-graph.git

## Documentation

### Main Git - Draw Commands Functions
* _initRepo      -->  Initialize Repository 
* _startFeature  -->  Starts a new feature branch
* _endFeature    -->  Ends a feature branch
* _startHotfix   -->  Starts a new hotfix branch
* _endHotfix     -->  Ends a hotfix branch
* _startRelease  -->  Starts a new release branch
* _endRelease    -->  Ends a release branch
* _setNewTag     -->  creates a tag and sets a develop and master point
* _newCommit     -->  creates a new commit on the current branch
* _goToTimeSlot  -->  moves currentposition to passed timeslot


### File / Folder Structure

    +-- readme.md (this document)
    +-- git-history.html ( Graph creating HTML / Application)
    +-- LICENSE
