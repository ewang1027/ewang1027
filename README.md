<!-- hi, source reader. the rendered version is prettier, but you already knew that. -->

### hey, i'm ethan

I like the parts of the stack people apologize for — schedulers, storage
engines, consensus, whatever the profiler says is actually slow.

```text
$ systemctl status ethan
● ethan.service — Ethan Wang
     Loaded: loaded (~/.config/curiosity.service; enabled)
     Active: active (running); Restart=always
       Docs: man:ethan(1)
             https://github.com/ewang1027
   Main PID: 1 (stubborn)
      Tasks: 3 (limit: optimistic)
     Memory: failure modes, mostly
     CGroup: /hoops.slice — reserved for basketball

$ journalctl -u ethan -n 3
signal-forge[7]: harvested 194 real complaints, shipped 2 grounded ideas, killed 1
signal-forge[7]: (the killed one deserved it)
ethan[1]: status: measuring before guessing
```

**on the workbench**

- **[signal-forge](https://github.com/ewang1027/signal-forge)** — scrapes real
  complaints off HN, GitHub and Lobste.rs, clusters them into pain themes, and
  emails me project ideas grounded in evidence instead of vibes. Its gates are
  allowed to reject everything: "nothing" is an acceptable outcome.

**how i work**

- evidence density beats novelty scores
- boring infrastructure, interesting problems
- the free tier is a design constraint, not a budget

<!--
$ systemctl stop ethan
Job for ethan.service canceled.
-->
