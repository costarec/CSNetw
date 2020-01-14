This is a modification of the source code distribution package provided by author Sean Burns in his book, 
"Hands-On Network Programming with C# and .NET Core" published 2019 by Packt> Publishing.

This distribution has been cleaned up and reorganized so that it can be easily opened in Visual Studio
as a single .SLN solution file, with all .csproj files loading correctly in the solution explorer window.

I did this only to faciliate using the software as examples in my courses:
TINFO-200 Programming II for ITS at the University of Washington Tacoma

I didn't change any of the author's original C# source code. My intention was simply to provide students with an
easy quick way to load all the programs into the IDE so they would be more likely to engage in experimenting
and learning from the sample programs without having to focus on path, build, and configuration inconsistencies.

You should be able to download the repos as a zip, unzip it on your drive, double click the top level
.SLN file to open in Visual Studio and do a Build->Batch Build of the entire solution. 
There are currently 2 warnings, using VS2019 Enterprise Preview (latest updates) with .NET Core 3.1

Alternatively, you could open the Tools->Command Line->Developer PowerShell and issue the cmd:

msbuild -t:rebuild -p:configuration=debug  (or release)

--chuck costarella, 2020-01-10
