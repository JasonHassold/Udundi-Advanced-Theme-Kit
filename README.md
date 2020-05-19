# Udundi-Advanced-Theme-Kit

### Setup

```
sudo ln -s {{ full current directory }}/atk /usr/bin/atk
```

### Usage:

```atk {command} {options}```

### Commands:

   * **Setup:** ```atk setup {store ex. advanced-theme-kit-tester.myshopify.com} {password}```

      * downloads live theme and sets up github repository with the live theme as the master branch

   * **Get:** ```atk get {github repo URL} {store ex. advanced-theme-kit-tester.myshopify.com} {password}```

      * gets an existing repository

   * **Sync:** ```atk sync```

      * syncs any new remote branches

   * **List Branches:** ```atk branch```
   * **Create Branch:** ```atk branch {branch name}```
   * **Delete Branch:** ```atk branch {branch name} delete```

   * **Switch Branch:** ```atk switch {branch name}```

   * **Watch:** ```atk watch```

   * **Merge:** ```atk merge {branch to merge into} {branch being merged}```
