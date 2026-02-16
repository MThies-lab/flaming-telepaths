#  Purpose
The purpose of this text document is to test the automatic notification integration between github and slack and to eliminate menial yet persistent tasks that we should be able to skip.
# The Problem
We currently make PRs and the manually and individually notify a social channel that we have PRs tha need to be reviewed. While this is short step, it is inefficient as it requires manual data entry, it is a manual operation over two platforms, and requires a albeit a small amount of context switching, but one that adds up, especially across a whole team. 
# Proposed Solution
Use github's webhook and slack integration to automatically update a specific channel, a PR-only channel when new PRs are created. This will abide by individual's notificatiopn settings, and will individually notify anyone who is tagged/selected as a reviewer on the PR. 
# ROI
We eleminiate a step from our workflow, ensure notification accuracy, and present a valuable proof of concept for workflow refiniement. 
