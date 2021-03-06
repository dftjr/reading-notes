# VERSION CONTROL

&nbsp;

## What is it?

A system that allows you to see various versions of a file, or files, by recording the changes. A coder can do the following things:

- Revert a project or previous version
- Track modifications
- Compare changes

&nbsp;

## Types of VCS

<sup>*(Click for definition)*</sup>

<details>
<summary>Local VCS</summary>
<p> 
A single database on a hard drive that stores file changes

- Local database

</p>
</details>

<details>
<summary>Centralized Version Control (CVCS)</summary>
<p>
A single server that stores all file changes and versions

- Streamlines collaboration
- Eliminates need for local databases
- More administrative control

</p>
</details>

<details>
<summary>Distributed Version Control (DVCS)</summary>
<p>
Multiple mirrored repositories

- Assists in various ways of collaborating
- Addresses vulnerability of a server as a single point of failure
- Can replace lost information through data backups

</p>
</details>

&nbsp;

## Git

- **Snapshot:** DVCS that stores data in a file system
  - Saved changes to projects, called commit, create a store a reference to it
  - Only stores a reference if files has not been changed  

&nbsp;

- **Local Operations:** Relies mostly on local operations
  - Heavily relies on local operations
  - Process expediency from history residing on the local disk
  - Eliminates need for fetching information from servers
  - Can work on projects offline  

&nbsp;

- **Tracking Changes:** All changes to files and directories are tracked by Git
  - File corruption and data loss will be detected  

&nbsp;

- **Data Loss:** Set up to minimze irreversible damage to files
  - Extremely difficult for a committed snapshot to be lost  

&nbsp;

- **States:** Files remain in three states
  - ***Commited***: Data secured in a local database
  - ***Modified***: Files are changed, but not comiited to the database
  - ***Staged***: Flags a file's change version being committed in the next snapshot  

&nbsp;

### Getting started

Installation instructions and updates can be found at the link below:

[Setting up Git](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
