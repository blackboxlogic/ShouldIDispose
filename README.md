# ShouldIDispose
A list of [IDisposable](https://docs.microsoft.com/en-us/dotnet/api/system.idisposable?view=net-5.0) c# .Net types, and if you need to `Dispose()` them.

* `System.Data.DataSet` [No](https://stackoverflow.com/a/913286)
* `System.Data.DataTable` [No](https://stackoverflow.com/a/913286)
* `System.Data.SqlClient.SqlCommand` [Yes](https://stackoverflow.com/a/1808056)
* `System.Data.SqlClient.SqlConnection` [Yes](https://stackoverflow.com/a/1808056)
* `System.Data.SqlClient.SqlDataReader` [Yes](https://stackoverflow.com/a/744069)
* `System.Data.SqlClient.SqlTransaction` [Yes](https://stackoverflow.com/a/9525729)
* `System.Drawing.Font` [It's complicated, safest not to](https://github.com/dotnet/runtime/issues/36233)
* `System.IO.MemoryStream` [No](https://stackoverflow.com/a/4274769)
* `System.IO.StringWriter` [No](https://stackoverflow.com/a/2477076)
* `System.Net.Http.HttpClient` [Better to re-use one instance, but when you're _done_ with it: Yes](https://stackoverflow.com/a/15708633)
* `System.Net.Mail.MailMessage` [Yes, if it might have attachments](https://stackoverflow.com/a/8477820/1521988)
* `System.Threading.CancellationTokenSource` [Yes](https://stackoverflow.com/a/9332634/1521988)
* `System.Threading.Mutex` [Yes](https://stackoverflow.com/a/7107218)
* `System.Windows.Form` [Yes for `ShowDialog()`, No for `Show()`](https://stackoverflow.com/a/8315201/1521988)

Pull requests or issues are welcome.
