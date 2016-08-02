# PaperCut Real-Time Activity

Ever wanted to display real-time activity of your PaperCut print infrastructure on a wide-screen TV in your IT office?
Good, because you're in the right place.
This script essentially polls the same API that the real-time activity box on /admin... except it's in an easier to see, read and display format. It also gives you the flexibility to see *only* warning messages or *only* information messages. You can also very easily change the colours of the messages, sizes, etc.

### Prerequisities

- None

### How to Use

* Simply download the dashboard.htm file and put it in your PaperCut install /server/custom/web directory.
You can also do this in a few seconds by opening PowerShell as administrator and running the following (assuming the install directory is correct - in my case it's an MF install on the C drive):

```powershell
Invoke-WebRequest https://raw.githubusercontent.com/emtunc/PaperCut/master/dashboard.htm -OutFile "C:\Program Files\PaperCut MF\server\custom\web\dashboard.htm"
```

* Change the *var url* in the script

* You'll have to log-in to the admin interface before loading up dashboard.htm as it requires authentication and there currently isn't an easy and secure way to pass-through the authentication in the dashboard.htm page

<https://your-papercut-server/admin>

* Now you can load up the dashboard!

<https://your-papercut-server/custom/dashboard.htm>

### Screenshots


## Credits

- Jonathan Bennetts @ PaperCut support for creating this awesome script

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
