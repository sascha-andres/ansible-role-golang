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
|1.19.0|- support for 1.19|
|1.18.5|-support for 1.18.5|
||-support for 1.17.13|
|1.18.4|- support for 1.18.4|
||- support for 1.17.12|
|1.18.3|- support for 1.18.3|
||- support for 1.17.11|
|1.18.2|- support for 1.18.2|
||- support for 1.17.10|
|1.8.1-2|-support for darwin|
|1.18.1|- support for 1.18.1|
||- support for 1.17.9|
||due to an issue (https://github.com/golang/go/issues/52317) darwin port is currently unavailable|
|1.18.0|- support for 1.18|
|1.17.8|- support for 1.17.8|
||- support for 1.16.15|
|1.17.7|- support for 1.17.7|
||- support for 1.16.14|
|1.17.6|-support for go 1.17.5 and 1.17.6|
||- support for go 1.16.12 and 1.16.13|
|1.17.4|- support for go 1.17.1 to 1.17.4|
||- support for go 1.16.9 to 1.16.11|
||- support for linux arm64 and windows arm64 for 1.17.4|
||- support for linux arm64 and darwin arm64 for 1.16.11|
|1.17.0|- support for go 1.17|
||- support for darwin-arm64|
|1.16.7|support for 1.16.5|
||support for 1.16.6|
||support for 1.16.7|
||support for 1.15.13|
||support for 1.15.14|
||support for 1.15.15|
|1.16.4|support for 1.16.4|
||support for 1.15.12|
|1.16.3|support for 1.16.1|
||support for 1.16.2|
||support for 1.16.3|
||support for 1.15.9|
||support for 1.15.10|
||support for 1.15.11|
|1.16.0-1|fix download and use 1.16 as key for 1.16|
|1.16.0|support for 1.16 via 1.16.0|
||support for 1.15.8|
||support for 1.14.15|
|1.15.7|support for 1.15.7|
||support for 1.14.14|
|1.15.6|support for 1.15.6|
||support for 1.14.13|
|1.15.5|support for 1.15.4|
||support fot 1.15.5|
||support for 1.14.11|
||support for 1.14.12|
|1.15.3|support for 1.15.3 and 1.14.10|
|1.15.2|support for 1.15.2 and 1.14.9|
|1.15.1|support for 1.15.1 and 1.14.8|
|1.15.0|support for 1.13.15|
||support for 1.13.14|
||support for 1.13.13|
||support for 1.14.5|
||support for 1.14.6|
||support for 1.14.7|
||support for 1.15.0|
|1.14.4|support for 1.14.3 and 1.13.12|
|1.14.3|support for 1.14.3 and 1.13.11|
|1.14.2|support for 1.14.2 and 1.13.10|
||support for 1.13.9 and 1.13.10|
|1.14-1|fix for dictionary|
|1.14|add support for 1.14|
|1.13.8|add support for 1.13.8 and 1.12.17|
|1.13.7|add support for 1.13.7 and 1.12.16|
|1.13.6|add support for 1.13.6 and 1.12.15|
|1.13.5|add support for 1.13.5 and 1.12.14|
|1.13.4|add support for 1.13.4 and 1.12.13|
|1.13.3|add support for 1.13.3 and 1.12.12|
||change version to highest supported go version|
|0.2.11|remove unused template|
|0.2.10|add 1.13.1|
||add 1.12.10|
|0.2.9|add 1.13|
|0.2.8|add 1.12.9 and 1.11.13|
|0.2.7|add 1.12.7|
|0.2.6|add 1.12.6 and 1.11.11|
|0.2.5|add go 1.12.5|
|0.2.4|fix dict key for 1.12.4|
|0.2.3|add go version 1.12.4|
|0.2.1|fix typos|
|0.2.0|limit to go version 1.11 and 1.12|
||update to current patch releases|
|0.1.1|fix: create go_parent_dir if it does not exist|
|0.1.0|initial release|
