# InfiniteLayoutSubviewsBug

Run the project. Scroll the table _up_ and release. Watch the console. We get an infinite series of calls to `viewDidLayoutSubviews`.

If you uncomment the line that turns off large titles in the navigation bar, the problem goes away.

Original bug described in question on [Stack Overflow](https://stackoverflow.com/questions/47912392/viewdidlayoutsubviews-stuck-in-infinite-loop-for-blank-method) — this is just a minimal demonstration.
