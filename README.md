# TimestampIt! verification keys

An official backup repository of verification keys for TimestampIt! (https://timestampit.com).

## Purpose

This repository serves as a permanent backup of verification keys for TimestampIt!.

These verification keys are used to verify Trusted Timestamps created by TimestampIt!. For more information about Trusted Timestamp verification, refer to [TimestampIt! documentation](https://beta.timestampit.com/docs/quickstart), and the [Example client repo](https://github.com/timestampit/example_clients/).

TimestampIt! provides all verification keys on it's website. However, should the website not be functioning, this repo has the verification keys as well.

## Details

All keys in this repo are committed and signed by only one GitHub user: `timestampit-official` with email `github-production@timestampit.com`.

The public key for this user is in the `authorized_keys` file within this repo.

### Before using any key in this repo

Like any git repo, you can force this repo to match the remote repo by running:
```
git fetch origin
git reset --hard origin/main
git clean -dfx
```

You can verify all commits in this repo by running `./verify_commits`.

Performing this action is a good way to ensure you have the correct and official keys **before** verifying any Trusted Timestamps.
