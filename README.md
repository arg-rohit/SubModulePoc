# SubModulePoc

This project demonstrates the use of Git submodules, specifically incorporating a shared Utilities module.

## Submodules

### Utilities
A submodule containing utility classes for Redis operations. Located in the `Utilities` directory.

## Managing Submodules

### Clone the Repository with Submodules
To clone this repository along with its submodules, use:
```bash
git clone --recurse-submodules <repository-url>
```

### Initialize Submodules (if cloned without --recurse-submodules)
```bash
git submodule init    --> initializes the submodules defined in the repository.
git submodule update    --> to fetches the latest commits from the submodule repository.
```

### Add Repository as Submodule at root or at particular path
```bash
git submodule add <submodule_url>            --> URL of the Git repository to add as submodule
git submodule add <submodule_url> <path>     --> path where the submodule to be added within repository
```

### Update Submodules
To update all submodules to their latest commits:
```bash
git submodule update --remote
