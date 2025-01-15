Made error while trying to rebase,
the commits were supposed to be arranged like this:
A-B-C-D-E-F-G-H-I
But I ended up with:
A-B-C-D-H-I-E-G
Solution: add commit F and cherry pick everything.
Let's see if it works :)
