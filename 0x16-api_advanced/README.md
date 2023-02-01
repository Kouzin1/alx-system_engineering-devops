# API advanced

I continued to practice querying API's in this advanced project, this time
working with the the Reddit API.

## Tests :heavy_check_mark:

## Function Protypes :floppy_disk:

Prototypes for functions written in this project:

| File			| Protypes				|
|-----------------------| --------------------------------------|
| `0-subs.py`		| `def number_of_subscribers(subreddit)`|
| `1-top_ten.py`	| `def top_ten(subreddit)`		|
| `2-recurse.py`	| `def recursive(subreddit, hot_list=[]`|


## Tasks :page_with_curl:

* **0. How many subs?**
  * [0-subs.py](./0-subs.py): Python function that returns the total number of
  subscribers for a given subreddit.
  * Returns `0` if an invalid subreddit is given.

* **1. Top Ten**
  * [1-top_ten.py](./1-top_ten.py): Python function that prints the top ten
  hottest post for a given subreddit.
  * Prints `None` if an invalid subreddit is given.

* **2. Recurse it!**
  * [2-recursive.py](./2-recursive.py): Python function that recursively returns a
  list of titles for all hot articles on a given subreddit.
  * Returns `None` if no results are found on the given subreddit.
