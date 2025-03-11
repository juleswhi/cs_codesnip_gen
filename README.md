# C# Code Snippet Generator

Code Snippet Generator for SSD/DT Coursework ( Uses Freeze )

# Usage

You may need to enable scripts to run on your system. To fix this, open an `Administrator` powershell.

```
Start Menu -> Powershell -> Click "Run As Administrator"
```

Once open, copy the following execution policy into powershell and hit enter.

```sh
Set-ExecutionPolicy unrestricted
```

> [!IMPORTANT]
> Change to `restricted` to revert the execution policy changes

The easiest way to do the next step is to copy and paste this folder contents into the *ROOT* directory of your project. Once it is in the root directory, you can choose either PNG or SVG images. 

> [!NOTE]
> Png -> Slower ( By a lot )
> Svg -> Sucks

Open a new powershell in the root directory of your project, and execute the following line.

```sh
.\PNG_GEN.ps1
```

or 

```sh
.\SVG_GEN.ps1
```

This will create an `images/` directory in your project, where all the images will be. PNG _will_ take a while to generate them all.
