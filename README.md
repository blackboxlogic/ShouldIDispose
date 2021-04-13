# ShouldIDispose
A list of [IDisposable](https://docs.microsoft.com/en-us/dotnet/api/system.idisposable?view=net-5.0) c# .Net types, and if you should `Dispose()` them.

* `System.Data.DataSet` [No](https://stackoverflow.com/a/913286)
* `System.Data.DataTable` [No](https://stackoverflow.com/a/913286)
* `System.IO.MemoryStream` [No](https://stackoverflow.com/a/4274769)
* `System.IO.StringWriter` [No](https://stackoverflow.com/a/2477076)
* `System.Threading.Mutex` [Yes](https://stackoverflow.com/a/7107218)
* `System.Windows.Form` [Yes for `ShowDialog()`, No for `Show()`](https://stackoverflow.com/a/8315201/1521988)

Pull requests or issues are welcome.
