# MrCleansTodo

This is version 3 of my personal todolist syntax.

Version 1 was made for TextMate. Version 2 was made for Sublime Text 2. Version 1 and 2 were not under source control.

Questions: Open an issue or email me at `michael+mr-cleans-todo@informatikk.org`

## Example usage

Two simple days are shown here, without the syntax highlighting. TODO: Add screenshot instead.

```
saturday 17.12.18 ~ Trondheim trip
Awesome hotel breakfast.
[x] Elv Technology
    [x] talk to the person about the thing at 9:30
    [x] fix the bug in the user module
    [ ] finish planning of new wiki module
    [ ] team retrospective at 15
Dinner at Solsiden with the team, at 17:30.
[ ] Shopping
    [ ] pick up the IKEA-package at the post office
    [ ] buy a new mouse mat
- - Remember to send a birthday message to Jørund
Pizza and beer at Øyvind's place at 20:45.
[ ] Go through email
[ ] Pack suitcase for tomorrows trip

sunday 17.12.19
[ ] Flight to Oslo at 9
Got Starbucks on the way.
Netflix all day long. Didn't even unpack.
```

Legend:

```
[ ] A task or context
    [ ] A subtask
    ::: Lunch, or some other informational context
    [ ] Another subtask
    [ ] A meeting at 9:00
        ::: I prefer times to be at the end of the line, like above
        [ ] Agenda point
        [ ] Agenda point
    [ ] An unplanned meeting in room ??? at ???
        ::: The question marks on the line above are highlighted because
            I use the triple question mark for all undetermined things,
            which are usually times, dates or room numbers.
        [ ] Agenda point
        [ ] Agenda point
    - - A deletable, usually a very short task or a small reminder
    !!! An important note or reminder, also deletable, but highlighted
    >>> A thing that must be moved to a future day
    [ ] One last subtask
[ ] Get a birthday gift for Jon Andreas
    +++ 1 year (copy the task to the future date, then delete this triple-plus)
    [ ] Buy the gift
    [ ] Wrap and deliver the gift
```

## Gamification

Days that I've done a lot are tagged with "Supereffektiv" (super efficient), "Ninjaeffektiv" (ninja efficient), or "Godlike" (Unreal Tournament reference). The names are silly, but that doesn't matter. These tags, applied at the end of each day, help me aim to accomplish a lot in a day by celebrating the small checks. Checking boxes always feels good.

- "~ Supereffektiv" (super efficient) is used for days where I check 20 or more boxes, this usually happens 3-4 times a week.
- "~ Ninjaeffektiv" (ninja efficient) is used for days where I check 30 or more boxes, this usually happens once a week.
- "~ Godlike" is used for days where I check 40 or more boxes, this usually happens 4-5 times a year.

I usually consider a task worthy of a checkbox if it takes 15-20 minutes. At any time, when I look back on my last week, it feels great to see that several days are marked with these celebratory tags.

Note that the goal is *not* to reach 30 or 40 checked boxes each day. The goal is to cross off 20 checkboxes, because that's a sustainable pace. Checking 30 or more boxes in a day *feels* really good then and there, but inevitably means you'll do less tomorrow because you'll be tired. Don't burn out. Keep a sustainable pace.
