Horo
===

Horo (from [Horology](https://en.wikipedia.org/wiki/Horology)) is a cross-platform
scheduled task orchestration and monitoring solution.

Configuration is pulled from a "configuration as code" source such as a Git repository and
used to provision tasks which can then be triggered on workers running on any platforms with
a "complication" available.

There will also be support for a number of pluggable alerting outputs.

Examples of tasks this system could be used for:
 - Daily reporting on print counters over SNMP
 - 5 minute checks for service status
