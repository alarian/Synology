# Synology #

[Trello Board](https://trello.com/b/2R0m3FiP)

[![Stories in Ready](https://badge.waffle.io/DotNetDevs/Synology.png?label=ready&title=Ready)](http://waffle.io/DotNetDevs/Synology)

[![Stories in Progress](https://badge.waffle.io/DotNetDevs/Synology.svg?label=in%20progress&title=In%20Progress)](http://waffle.io/DotNetDevs/Synology)

[Kanban Board](https://zube.io/boards/46553751/kanban)

Project on AppVeyor: [![Build status](https://ci.appveyor.com/api/projects/status/extxot8qp13pf4jy?svg=true)](https://ci.appveyor.com/project/matteobruni/synology-c1jb9)

Branch `master` Status: [![Build status](https://ci.appveyor.com/api/projects/status/extxot8qp13pf4jy/branch/master?svg=true)](https://ci.appveyor.com/project/matteobruni/synology-c1jb9/branch/master)

Branch `dev` Status: [![Build status](https://ci.appveyor.com/api/projects/status/extxot8qp13pf4jy/branch/dev?svg=true)](https://ci.appveyor.com/project/matteobruni/synology-c1jb9/branch/dev)

Synology [![NuGet version](https://badge.fury.io/nu/Synology.svg)](https://badge.fury.io/nu/Synology)

Synology.Api [![NuGet version](https://badge.fury.io/nu/Synology.Api.svg)](https://badge.fury.io/nu/Synology.Api)

Synology.DownloadStation [![NuGet version](https://badge.fury.io/nu/Synology.DownloadStation.svg)](https://badge.fury.io/nu/Synology.DownloadStation)

Synology.DownloadStation2 [![NuGet version](https://badge.fury.io/nu/Synology.DownloadStation2.svg)](https://badge.fury.io/nu/Synology.DownloadStation2)

Synology.FileStation [![NuGet version](https://badge.fury.io/nu/Synology.FileStation.svg)](https://badge.fury.io/nu/Synology.FileStation)

Synology.SurveillanceStation [![NuGet version](https://badge.fury.io/nu/Synology.SurveillanceStation.svg)](https://badge.fury.io/nu/Synology.SurveillanceStation)

This is an implementation of Synology Built-In APIs for .NET projects.
You can use it for access your Synology information, upload/download files from disk, use the built-in torrent client and all other services available.

## Pull request will be accepted only if targeting `dev` branch. ##

API Progress:

<table>
	<tr>
		<th>API</th>
		<th>Status</th>
	</tr>
	<tr>
		<th colspan="2">SYNO.API</th>
	</tr>
	<tr>
		<td>Auth</td>
		<td>
			<table>
				<tr>
					<td>login</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>logout</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>Info</td>
		<td>
			<table>
				<tr>
					<td>query</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<th colspan="2">SYNO.DownloadStation</th>
	</tr>
	<tr>
		<td>Info</td>
		<td>
			<table>
				<tr>
					<td>getinfo</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>getconfig</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>setserverconfig</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>Schedule</td>
		<td>
			<table>
				<tr>
					<td>getconfig</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>setserverconfig</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>Task</td>
		<td>
			<table>
				<tr>
					<td>list</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>getinfo</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>create</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>delete</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>pause</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>resume</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>edit</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<th colspan="2">SYNO.DownloadStation2</th>
	</tr>
	<tr>
		<td>Task</td>
		<td>
			<table>
				<tr>
					<td>create</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<th colspan="2">SYNO.FileStation</th>
	</tr>
	<tr>
		<td>CheckPermission</td>
		<td>
			<table>
				<tr>
					<td>write</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>CopyMove</td>
		<td>
			<table>
				<tr>
					<td>start</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>status</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>stop</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>DirSize</td>
		<td>
			<table>
				<tr>
					<td>start</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>status</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>stop</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>Favorite</td>
		<td>
			<table>
				<tr>
					<td>list</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>add</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>delete</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>clear_broken</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>edit</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>FileShare</td>
		<td>
			<table>
				<tr>
					<td>list_share</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>list</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>getinfo</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>Info</td>
		<td>
			<table>
				<tr>
					<td>getinfo</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>List</td>
		<td>
			<table>
				<tr>
					<td>list_share</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>list</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>getinfo</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>MD5</td>
		<td>
			<table>
				<tr>
					<td>start</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>status</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>stop</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>Rename</td>
		<td>
			<table>
				<tr>
					<td>rename</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>Search</td>
		<td>
			<table>
				<tr>
					<td>start</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>list</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>stop</td>
					<td><strong>OK</strong></td>
				</tr>
				<tr>
					<td>clear</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>Thumb</td>
		<td>
			<table>
				<tr>
					<td>get</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>Upload</td>
		<td>
			<table>
				<tr>
					<td>upload</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<td>VirtualFolder</td>
		<td>
			<table>
				<tr>
					<td>list</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
	<tr>
		<th colspan="2">SYNO.SurveillanceStation</th>
	</tr>
	<tr>
		<td>Info</td>
		<td>
			<table>
				<tr>
					<td>getinfo</td>
					<td><strong>OK</strong></td>
				</tr>
			</table>
		</td>
	</tr>
</table>

The following code is my test project, you can use it as a guide for now. I will write the documentation, I promise.

```csharp
public static void Main(string[] args)
{
	using (var syno = new SynologyConnection(LoginData.Url, true))
	{
		DoConnection(syno);
	}
}
public static void DownloadStationTests(SynologyConnection syno)
{
	Console.WriteLine("DS Info");
	var dsResInfo = syno.DownloadStation().Info().GetInfo();
	Console.WriteLine(JsonConvert.SerializeObject(dsResInfo));

	Console.WriteLine("DS Config");
	var dsResConfig = syno.DownloadStation().Info().Config();
	Console.WriteLine(JsonConvert.SerializeObject(dsResConfig));

	Console.WriteLine("DS Schedule Config");
	var dsResSchedule = syno.DownloadStation().Schedule().Config();
	Console.WriteLine(JsonConvert.SerializeObject(dsResSchedule));

	Console.WriteLine("DS Task List");
	var dsResTasks = syno.DownloadStation().Task().List(new TaskListParameters {
		Additional = TaskDetailsType.Detail | TaskDetailsType.Transfer | TaskDetailsType.File | TaskDetailsType.Tracker | TaskDetailsType.Peer	
	});
	Console.WriteLine(JsonConvert.SerializeObject(dsResTasks));
}

public static void FileStationTests(SynologyConnection syno)
{
	Console.WriteLine("FS Info");
	var fsResInfo = syno.FileStation().Info().GetInfo();
	Console.WriteLine(JsonConvert.SerializeObject(fsResInfo));

	Console.WriteLine("FS List Share");
	var fsResShares = syno.FileStation().FileShare().ListShare(FileShareDetailsType.RealPath | FileShareDetailsType.Size | FileShareDetailsType.Owner | FileShareDetailsType.Time | FileShareDetailsType.Perm | FileShareDetailsType.VolumeStatus | FileShareDetailsType.MountPointType);
	Console.WriteLine(JsonConvert.SerializeObject(fsResShares));

	Console.WriteLine("FS List");
	var fsResList = syno.FileStation().FileShare().List("/downloads", null, FileType.All, null, FileDetailsType.RealPath | FileDetailsType.Size | FileDetailsType.Owner | FileDetailsType.Time | FileDetailsType.Perm | FileDetailsType.Type | FileDetailsType.MountPointType);
	Console.WriteLine(JsonConvert.SerializeObject(fsResList));

	Console.WriteLine("FS Info");
	var fsResFileInfo = syno.FileStation().FileShare().Info("/downloads/.apdisk", FileDetailsType.RealPath | FileDetailsType.Size | FileDetailsType.Owner | FileDetailsType.Time | FileDetailsType.Perm | FileDetailsType.Type | FileDetailsType.MountPointType);
	Console.WriteLine(JsonConvert.SerializeObject(fsResFileInfo));

	Console.WriteLine("FS VF List");
	var fsVfResList = syno.FileStation().VirtualFolder().List(VirtualFolderDetailsType.RealPath | VirtualFolderDetailsType.Owner | VirtualFolderDetailsType.Time | VirtualFolderDetailsType.Perm | VirtualFolderDetailsType.MountPointType | VirtualFolderDetailsType.VolumeStatus);
	Console.WriteLine(JsonConvert.SerializeObject(fsVfResList));
}

public static void GetOtp(SynologyConnection syno, ref ResultData<AuthResult> resLogin)
{
	do
	{
		Console.Write("Otp Code: ");

		var otp = Console.ReadLine();

		if (string.IsNullOrWhiteSpace(otp))
		{
			resLogin.Error = new ResultError { Code = 404 };
			continue;
		}

		resLogin = syno.Api().Auth().Login(new LoginParameters {
			Username = LoginData.Username,
			Password = LoginData.Password,
			OtpCode = otp
		});

		Console.WriteLine(JsonConvert.SerializeObject(resLogin));
	}
	while (resLogin.Error != null && resLogin.Error.Code == 404);
}

public static void DoConnection(SynologyConnection syno)
{
	Console.WriteLine("Info");
	var resInfo = syno.Api().Info().GetInfo();

	Console.WriteLine(JsonConvert.SerializeObject(resInfo));

	Console.WriteLine("Auth Login");
	var resLogin = syno.Api().Auth().Login(new LoginParameters {
		Username = LoginData.Username,
		Password = LoginData.Password
	});

	Console.WriteLine(JsonConvert.SerializeObject(resLogin));

	if (resLogin.Error == null || (resLogin.Error != null && resLogin.Error.Code == 403))
	{
		if (resLogin.Error != null && resLogin.Error.Code == 403)
		{
			GetOtp(syno, ref resLogin);
		}

		if (resLogin.Error == null)
		{
			DownloadStationTests(syno);

			FileStationTests(syno);

			Console.WriteLine("Auth Logout");
			var resLogout = syno.Api().Auth().Logout();
			Console.WriteLine(JsonConvert.SerializeObject(resLogout));
		}
	}

	Console.ReadLine();
}
```
