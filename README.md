### Running sync via Github commit

The sync process will fetch the Github sources and prepare them for serving to PrusaSlicer.

#### To invoke sync:
A commit with message containing __PUBLISH__ word at separate line (i.e. one line with only this word). The capitals letters are required.

The commit needs to be pushed to this branch (__sync__). 

#### Examples of commit messages that will invoke the sync:
```
Here are some notes
PUBLISH
```
or just
```
PUBLISH
```
> [!WARNING]
> __Examples of commit messages that will NOT invoke the sync:__
>
> ```
> Publish (the PUBLISH has to be in an all-letters-capital form)
>```
> ```
> Some text here PUBLISH (The PUBLISH command has to be the only word on the line).
> ```


..
