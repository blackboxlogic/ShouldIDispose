# ShouldIDispose
A list of IDispable Types, and if you're suppose to dispose them.
Please feel free to make pull requests.

* `System.IO.MemoryStream` [No](https://stackoverflow.com/a/4274769)
* `System.Windows.Forms` [Yes for `ShowDialog()`, No for `Show()`](https://stackoverflow.com/a/8315201/1521988)
