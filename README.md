# InfiniteLayoutSubviewsBug

Run the project. Scroll the table _up_ and release. Watch the console. We get an infinite series of calls to `viewDidLayoutSubviews`.

If you uncomment the line that turns of large titles in the navigation bar, the problem goes away.
