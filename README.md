# SpaceKees Atom Configuration

## Prerequisites

- You have [Atom](https://atom.io/) installed :rocket:
- You have [apm](https://github.com/atom/apm) installed  
  Run *Atom > Install Shell Commands* from the menu option
- You have the [Menlo](https://github.com/hbin/top-programming-fonts/blob/master/Menlo-Regular.ttf) font (installed by default on OS X).

## Instructions

Note: This will wipe out any existing Atom configurations that you have.

```bash
mv ~/.atom ~/.atom-old
git clone git@github.com:SpaceK33z/dotatom.git ~/.atom
```

Install the Atom packages by running:

```
apm install --packages-file ~/.atom/package-list.txt
```

If you add or update an Atom package, update the `package-list.txt` file:

```
apm list --installed --bare > ~/.atom/package-list.txt
```

Readme inspired by [FundingCircle dotatom](https://github.com/FundingCircle/dotatom).
