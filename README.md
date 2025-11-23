# ssc-github-sharedresources

A collection of scripts and code snippets which can be sourced by numerous other repos and runners, to keep from code drift.

Example:
`./shell/SendEmail.ah` contains a function that can send an email via SMTP2Go. If we ever change providers or the provider changes requirements, we hopefully only ever have to rewrite that shell code once.
