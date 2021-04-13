# ShouldIDispose
A list of [IDisposable](https://docs.microsoft.com/en-us/dotnet/api/system.idisposable?view=net-5.0) types, and if you should `Dispose()` them.
Please feel free to contribute pull requests or issues.

* `System.IO.MemoryStream` [No](https://stackoverflow.com/a/4274769)
* `System.Windows.Forms` [Yes for `ShowDialog()`, No for `Show()`](https://stackoverflow.com/a/8315201/1521988)
