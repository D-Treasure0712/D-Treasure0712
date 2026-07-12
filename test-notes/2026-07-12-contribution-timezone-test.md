# Contribution graph timezone test

This file exists to test whether a commit with a backdated author/committer
timestamp (2026-07-12T12:00:00+09:00) shows up on the contribution graph as
July 12, while the "opened a pull request" event itself (which GitHub stamps
with the real creation time) shows up as July 13.
