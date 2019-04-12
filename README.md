# mc-exercise

## Conflict Resolution

After Bob and Carol's first merge, everyone should have updated to the latest master branch 
so as to not fall behind on the commits.

Because Bob did not update to the latest commit, he was behind and Git does not know whether
the change he submitted was an intentional change if it conflicts with the previous code.
Because Ted and Alice did update, they did not have problems on the pull requests.

The solution to fix this is to allow Ted and Alice's pull request to be merge dfirst to master 
because they did not have merge conflicts. This would update the master branch and Bob's conflict
can be resolved in one step. Otherwise, if Bob's branch was resolved and merged before Ted and Alice,
Ted and Alice's branch would now have merge conflicts.

But Bob should have just pulled the latest branch when it was updated.
