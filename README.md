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
git submodule init
git submodule update
```

### Update Submodules
To update all submodules to their latest commits:
```bash
git submodule update --remote
