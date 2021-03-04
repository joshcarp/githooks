# githooks
- A collection of githooks to make local dev easier

## Installation
```bash
git clone https://github.com/joshcarp/githooks
git config core.hooksPath $(pwd)/githooks
```

## githooks
 - see [actions/](actions/) for list of scripts

## enable/disable certain githooks
 - in the `pre-commit` and `pre-push` files you can add/remove executions:

```diff
$SCRIPTPATH/actions/no-deletemes
+$SCRIPTPATH/actions/your-new-githook
```