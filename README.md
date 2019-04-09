# GoLang role for ansible

This golang roles installs Go into the user's home directory

variables that can be used to customize installation:

    go_ver        - version of go to install (use always the latest patch release)
    go_platform   - os and architecture
    go_parent_dir - directory to store go versions

The role does no set any environment variables. With the adoption of go modules need to set GOPATH should be reduced in the future.

The go_parent_dir variable may change from being relative to absolute in the future.

## History

|Version|Description|
|---|---|
|0.2.0|limit to go verison 1.11 and 1.12|
||update to current patch releases|
|0.1.1|fix: create go_parent_dir if it does not exist|
|0.1.0|initial release|
