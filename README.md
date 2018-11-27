# nrm_note
Instructions of nrm

### Function
> Change registry

### Install
```
npm install nrm -g
```

### Usage
- List usage information
    ```
    nrm -h
    ```
- List all the registries
    ```
    nvm ls
    ```
    - Show current registry name
        ```
        nrm current
        ```
- Add one custom registry
    ```
    nrm add <registry> <url>
    nrm add testnpm http://registry.npm.360.org
    ```
- Change registry to registry
    ```
    nrm use <registry>
    ```
- Show response time for specific or all registries
    ```
    nrm test npm
    ```
- Delete one custom registry
    ```
    nrm del <registry>
    ```
