# winPortPush
win PortPush is a small PowerShell utility used for pivoting into internal networks upon compromising a Windows public-facing host.

There are a couple of pre-requisites for this tool to work in its current state:

    Must have a means of getting the script onto the compromised host (i.e, this isn't a "remote" utility).
    Must have Administrator privileges on the compromised host you will be pivoting from.
    Must be an IPv4 environment. Currently, IPv6 addressing or hostnames will not work.
    Must have PowerShell installed on the host.
