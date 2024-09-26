# merge_example
An in-class example of how to handle merge conflicts

Workflow:
C0 (main): Create add.py, which adds x to 3
C1 (hotfix): Change add.py to add x and y
C2 (iss53): Change add.py to add a list of numbers
C3 (main): Change ad.py to add x to 4
C4 (main): Merge hotfix into main. Will cause merge conflicts (parents are C1 and C3)
C5 (main): Merge iss53 into main. Will cause merge conflicts (parents are C4 and C2)
