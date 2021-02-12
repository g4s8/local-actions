Run GitHub actions workflows on localhost

## Install

TBD

## Prerequirements and limitation

You have to be familiar with GitHub actions, this documentation is not supposed to explain it.

Local actions tool requires Docker daemon to be installed and run. The user has to be a member of `docker` group.

## Usage

Run `actions` CLI from repository root (`.github/workflows` directory should be accessible from `$PWD`).

### Trigger workflow

To trigger a workflow use `trigger` command: `actions trigger <event> [options]`.

E.g. to trigger `push` event use: `actions trigger push`, to trigger it on specified branch use `actions trigger push branch=master`.
