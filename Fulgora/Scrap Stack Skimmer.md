# Scrap Stack Skimmer

** [Scrap Stack Skimmer](https://factoriobin.com/post/09sq53)

*** Description
Remove the combinator and replace it with a single green wire into a roboport to read your logistics network. 
[Selector] - Sets quality level
[Selector] - Set to stack level to get stack quanity
[Arithmetic] - Gets the total number of stacks in the logistics network.
[Decider] - Outputs any stacks greater than 90
[Arithmetic] - Takes any stacks above 90 and breaks them back out to an individaul item count.

If you run a green wire from the final arithmetic to a requester chest, you'll get dynamic requests for anything that you need to pull from the logistics network due to too many. This can then be sent to a bit bucket.
