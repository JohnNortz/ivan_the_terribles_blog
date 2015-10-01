# My New Blog!

# Updated performance for the blog:

  changed the posts controller to eager load all comments and replies when loading the posts index, should drastically cut requests and increase speed.

  comments partial no longer renders reply partial, instead simply writes the reply body in its own partial

  added mini-profiler gem to monitor performance durring testing

  added file perflog to show what changes I made during development and tehir resulting performance result
