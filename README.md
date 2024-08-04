This is my note of my testing of xLua. I'm using "Unity 2022.3.27" and URP.

Installation
From the release page, download the source code zip file. The latest build today is "Tag:v2.1.16_with_ohos".

Put all the files and the folders in "Assets" folder into your Unity project (some meta files, XLua, Plugin folder).

In "Examples" folder, there's "ExampleGenConfig.cs" and it causes error.
Assets\XLua\Examples\ExampleGenConfig.cs(112,36): error CS0246: The type or namespace name 'MemberInfo' could not be found (are you missing a using directive or an assembly reference?)
You can delete the file to use xLua.