# taskwarrior-tag_expire-hook

This taskwarrior hook-script is intended to
- get my feet wet, learning how hook-scripts work, starting with a basic one
- to offer users an easy alternative to assigning an until:date value, that is immediately after the due:date, for those tasks that are un-completable beyond the due:date. 
By assigning a (user configurable) +expire tag, a task will be automatically and silently (?) deleted. This is desirable for high-frequncy, or daily tasks, like taking your vitamins. You don't need an overdue reminder to take yesterdays vitamins. If you took them yesterday, and marked the task completed, or you didn't, and today it was automatically deleted, you still have a decent record of hits and misses. 

Possible advantages over using the until:date attribute 
- speed of entry, as opposed to until:date(due:date+1) to set
- tags are visible in most reports, unlike until:attribute
