# Alfred-workflow-list-file-metadata
# Introduction

This rather simple workflow acts as a `Universal Action` on a single selected file to provide access to that file's metadata via the Shell. You can choose whether to copy to the clipboard merely the `Universal Type Identifiers` ("UTI") for the file or all of the metadata.

See <https://developer.apple.com/documentation/uniformtypeidentifiers> for an Apple introduction to UTI. 

In Alfred you may need to know:
- UTI for a file or files when, for example, in the `Basic Setup` of a `File Filter`; or
- additional metadata information to complete the `Fields` tab of a `File Filter`.

# Usage

Select a file in Finder (or in Alfred's search results), use your `Universal Action` hotkey and run `List file metadata in Terminal` on the file. You will be given the choice of seeing only the UTI (the default) or all metadata. The result is copied to the clipboard.
