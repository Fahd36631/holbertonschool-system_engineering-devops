# Web Infrastructure Design

This directory contains answers for the **Web Infrastructure Design** project in the Holberton System Engineering / DevOps track.

## Task 0: Simple Web Stack

File: `0-simple_web_stack`

This task describes a one-server infrastructure hosting `www.foobar.com` with:

- One server (`8.8.8.8`)
- One web server (`Nginx`)
- One application server
- One application code base
- One database (`MySQL`)

It also explains:

- The role of each component
- DNS records used for `www.foobar.com`
- How a user request flows through the stack
- Infrastructure limitations (SPOF, downtime risk, and scaling limits)

## Task 1: Distributed Web Infrastructure

File: `1-distributed_web_infrastructure`

This task describes a three-server distributed infrastructure hosting `www.foobar.com` with:

- One load balancer (`HAproxy`)
- Two application servers (each with `Nginx`, application server, and application files)
- One `MySQL` Primary-Replica setup

It also explains:

- Why each additional element is added
- The `round-robin` distribution algorithm
- `Active-Active` vs `Active-Passive`
- How Primary-Replica replication works
- Remaining limitations (SPOF, no firewall/HTTPS, no monitoring)

## Note

Replace the placeholder screenshot links in:

- `0-simple_web_stack`
- `1-distributed_web_infrastructure`

with your real diagram URLs (for example, Imgur links) before submission.
