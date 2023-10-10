# create-electric-app

## 0.1.7

### Patch Changes

- 0d879a8: Improved starter such that several (independent) Electric projects can run concurrently.
  The starter now has 2 modes: fast mode and interactive mode.
  In fast mode, you can provide the app name and optional ports for Electric and the webserver as arguments.
  In interactive mode, the script will prompt for an app name and ports (suggesting defaults).
  Port clashes are now detected and reported to the user.
  The user can change the ports the app uses by invoking 'yarn ports:configure'.
  Also fixes the bug where all Electric applications would forward requests to the esbuild server that is running on port 8000 instead of their own esbuild server.

## 0.1.6

### Patch Changes

- a42ee2c: Pull latest Electric and TS dependencies in starter and freeze them.

## 0.1.5

### Patch Changes

- bec4399: Remove NodeJS --no-warnings flag

## 0.1.3

### Patch Changes

- a05c04d: Add missing `typescript` devDependency to fix package build.

## 0.1.2

### Patch Changes

- 7cc6e27: Use correct version of `electric-sql` on the starter template

## 0.1.1

### Patch Changes

- 1c20e29: Improve starter template output and introduced new db:connect command.
- d9344b9: Use a tab scoped dbName so the starter example syncs across tabs.
- 345cfc6: Added auth.insecureAuthToken function and updated examples to use it.
- 29c7cc3: Starter template for bootstrapping Electric applications.
- 158431b: Include template in packaged files

## 0.1.1-next.2

### Patch Changes

- d9344b9: Use a tab scoped dbName so the starter example syncs across tabs.
- 345cfc6: Added auth.insecureAuthToken function and updated examples to use it.

## 0.1.1-next.1

### Patch Changes

- 1c20e29: Improve starter template output and introduced new db:connect command.
- 158431b: Include template in packaged files

## 0.1.1-next.0

### Patch Changes

- 29c7cc3: Starter template for bootstrapping Electric applications.
