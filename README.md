# InfiniteLayoutSubviewsBug

**This bug existed in iOS 11 at least thru iOS 11.2, but it has been fixed in iOS 12.**

Run the project (in iOS 11). Scroll the table _up_ and release. Watch the console. We get an infinite series of calls to `viewDidLayoutSubviews`.

If you uncomment the line that turns off large titles in the navigation bar, the problem goes away.

Original bug described in question on [Stack Overflow](https://stackoverflow.com/questions/47912392/viewdidlayoutsubviews-stuck-in-infinite-loop-for-blank-method) — this is just a minimal demonstration.
