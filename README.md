# manageiq_build

Goals:
- Move build logic out of build machines (cron jobs, installed dependencies, etc.)
- Only run VMs when they're needed (for appliance image builds)
- Break up with logic in manageiq-appliance_build that isn't appliance related (rpm build, container build, etc.)
