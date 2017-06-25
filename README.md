Results in error:

```
/Library/Frameworks/Mono.framework/Versions/5.0.1/lib/mono/msbuild/15.0/bin/Sdks/Microsoft.NET.Sdk/build/Microsoft.NET.Sdk.DefaultItems.targets(5,5): Error: Duplicate 'Compile' items were included. The .NET SDK includes 'Compile' items from your project directory by default. You can either remove these items from your project file, or set the 'EnableDefaultCompileItems' property to 'false' if you want to explicitly include them in your project file. For more information, see https://aka.ms/sdkimplicititems. The duplicate items were: 'App.xaml.cs'; 'Views/AboutPage.xaml.cs'; 'Views/ItemDetailPage.xaml.cs'; 'Views/ItemsPage.xaml.cs'; 'Views/LoginPage.xaml.cs'; 'Views/NewItemPage.xaml.cs' (App2.Shared)
```

Doing the same steps in Visual Studio on Windows does not result in this error.
