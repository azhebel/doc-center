# Local History

IntelliJ IDEA uses *Local History* to constantly track all changes made to projects.
Unlike version control systems that show differences between specific commits,
*Local History* automatically maintains revisions for all meaningful events.
This produces a detailed timeline of changes in project structure and source code,
with the ability to roll back to any point if necessary.

## Viewing Local History

To view *Local History*, open the **VCS** menu and choose **Local History** > **Show History**.

When viewing *Local History* for a directory, revisions show only names of files that changed in the directory.
Revisions for a specific file contain changes to the contents of the file.

**NOTE:** *Local History* is not available for binary files.

## Reverting Changes

*Local History* contains a list of revisions and shows differences between them.
To revert to a specific revision, select it from the list and click **Revert** in the toolbar.
This adds a new revision to *Local History*.

---

See also:

- [Viewing Local History for Source Code Elements](local-history-source.md)
- [Adding Labels to Local History](local-history-labels.md)
- [Sharing Local History](local-history-share.md)
- [Viewing Recent Changes](recent-changes.md)

