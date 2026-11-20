# Reference for the setup agent

The checkout and the setup ZIP contain the same optional fictional demo.
From the folder containing PLAYBOOK.md:

```sh
./practice-demo
```

On Intel or AMD 64-bit Linux with bubblewrap, the command starts a fresh practice inbox,
runs the actual local checker, reads back its output and exercises restart
and replay. It owns the processes it starts and stops them before handing
back a report. The only messages accepted by this command are bundled fixtures.

If the command says it needs the local checker, explain the roughly 9 GB
download. The runner checks disk space. Use `./practice-demo estimate` if a
brief connection sample would help the owner decide when to start. Then run
`./practice-demo --download` when authorized. It installs in this folder without
system or mailbox changes. Linux prerequisites include bubblewrap, flock,
curl and tar with zstd support. If the platform is incompatible or necessary
permission is unavailable, choose a suitable local alternative or show the
earlier example clearly as an earlier run.

- Open the `Results.html` path printed by a passing run and give the owner a
  link. Retell the short before/after and held example in chat using that run.
- Use `./practice-demo status` to get live run state and the last completed page.
  Link the owner to `Practice status.html` if a run is waiting or blocked.
  A failed attempt leaves any earlier page intact. The owner status page
  identifies it as an earlier result. Keep technical details in the attempt
  folder printed by the command.
- Run the same command again for a fresh demonstration. There is no practice
  inbox to keep running after a completed test and no real mail was connected.

The [earlier example](demo-results.html) is readable without any installation.
A separate 100-message trial missed several expected outcomes. A practice run
does not verify Claude access, real mail delivery, or supported setup on a Mac.

In the full checkout, `flow/REFERENCE-OPERATIONS.md` covers the separate
development and historical verification commands. The receiving agent can
reuse, adapt, or replace the reference.
