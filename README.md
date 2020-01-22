# Install-Keras


(base) C:\Windows\system32>conda install -c conda-forge keras

Collecting package metadata (current_repodata.json): done
Solving environment: done


==> WARNING: A newer version of conda exists. <==
  current version: 4.7.12
  latest version: 4.8.1

Please update conda by running

    $ conda update -n base -c defaults conda



## Package Plan ##

  environment location: C:\ProgramData\Anaconda3

  added / updated specs:
    - keras


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    _tflow_select-2.3.0        |              mkl           3 KB
    absl-py-0.9.0              |           py37_0         162 KB  conda-forge
    astor-0.7.1                |             py_0          22 KB  conda-forge
    conda-4.8.0                |           py37_1         3.0 MB  conda-forge
    gast-0.2.2                 |             py_0          10 KB  conda-forge
    google-pasta-0.1.8         |             py_0          42 KB  conda-forge
    grpcio-1.23.0              |   py37h3db2c7e_0         1.0 MB  conda-forge
    keras-2.3.1                |   py37h21ff451_0         591 KB  conda-forge
    keras-applications-1.0.8   |             py_1          30 KB  conda-forge
    keras-preprocessing-1.1.0  |             py_0          33 KB  conda-forge
    libgpuarray-0.7.6          |    hfa6e2cd_1003         314 KB  conda-forge
    libmklml-2019.0.5          |                0        17.4 MB
    libprotobuf-3.11.2         |       h1a1b453_0         2.2 MB  conda-forge
    mako-1.1.0                 |             py_0          57 KB  conda-forge
    markdown-3.1.1             |             py_0          60 KB  conda-forge
    opt_einsum-3.1.0           |             py_0          48 KB  conda-forge
    protobuf-3.11.2            |   py37he025d50_0         582 KB  conda-forge
    pygpu-0.7.6                |py37hc8d92b1_1000         600 KB  conda-forge
    tensorboard-2.0.0          |     pyhb38c66f_1         3.3 MB
    tensorflow-2.0.0           |mkl_py37he1bbcac_0           4 KB
    tensorflow-base-2.0.0      |mkl_py37hd1d5974_0        30.9 MB
    tensorflow-estimator-2.0.0 |     pyh2649769_0         250 KB
    termcolor-1.1.0            |             py_2           6 KB  conda-forge
    theano-1.0.4               |py37h6538335_1001         3.7 MB  conda-forge
    vs2015_win-64-14.0.25420   |      h55c1224_11           7 KB
    ------------------------------------------------------------
                                           Total:        64.4 MB

The following NEW packages will be INSTALLED:

  _tflow_select      pkgs/main/win-64::_tflow_select-2.3.0-mkl
  absl-py            conda-forge/win-64::absl-py-0.9.0-py37_0
  astor              conda-forge/noarch::astor-0.7.1-py_0
  gast               conda-forge/noarch::gast-0.2.2-py_0
  google-pasta       conda-forge/noarch::google-pasta-0.1.8-py_0
  grpcio             conda-forge/win-64::grpcio-1.23.0-py37h3db2c7e_0
  keras              conda-forge/win-64::keras-2.3.1-py37h21ff451_0
  keras-applications conda-forge/noarch::keras-applications-1.0.8-py_1
  keras-preprocessi~ conda-forge/noarch::keras-preprocessing-1.1.0-py_0
  libgpuarray        conda-forge/win-64::libgpuarray-0.7.6-hfa6e2cd_1003
  libmklml           pkgs/main/win-64::libmklml-2019.0.5-0
  libprotobuf        conda-forge/win-64::libprotobuf-3.11.2-h1a1b453_0
  mako               conda-forge/noarch::mako-1.1.0-py_0
  markdown           conda-forge/noarch::markdown-3.1.1-py_0
  opt_einsum         conda-forge/noarch::opt_einsum-3.1.0-py_0
  protobuf           conda-forge/win-64::protobuf-3.11.2-py37he025d50_0
  pygpu              conda-forge/win-64::pygpu-0.7.6-py37hc8d92b1_1000
  tensorboard        pkgs/main/noarch::tensorboard-2.0.0-pyhb38c66f_1
  tensorflow         pkgs/main/win-64::tensorflow-2.0.0-mkl_py37he1bbcac_0
  tensorflow-base    pkgs/main/win-64::tensorflow-base-2.0.0-mkl_py37hd1d5974_0
  tensorflow-estima~ pkgs/main/noarch::tensorflow-estimator-2.0.0-pyh2649769_0
  termcolor          conda-forge/noarch::termcolor-1.1.0-py_2
  theano             conda-forge/win-64::theano-1.0.4-py37h6538335_1001
  vs2015_win-64      pkgs/main/win-64::vs2015_win-64-14.0.25420-h55c1224_11

The following packages will be UPDATED:

  conda                      pkgs/main::conda-4.7.12-py37_0 --> conda-forge::conda-4.8.0-py37_1


Proceed ([y]/n)? y


Downloading and Extracting Packages
libmklml-2019.0.5    | 17.4 MB   | ############################################################################ | 100%
vs2015_win-64-14.0.2 | 7 KB      | ############################################################################ | 100%
keras-2.3.1          | 591 KB    | ############################################################################ | 100%
protobuf-3.11.2      | 582 KB    | ############################################################################ | 100%
tensorflow-2.0.0     | 4 KB      | ############################################################################ | 100%
tensorboard-2.0.0    | 3.3 MB    | ############################################################################ | 100%
termcolor-1.1.0      | 6 KB      | ############################################################################ | 100%
markdown-3.1.1       | 60 KB     | ############################################################################ | 100%
tensorflow-estimator | 250 KB    | ############################################################################ | 100%
absl-py-0.9.0        | 162 KB    | ############################################################################ | 100%
google-pasta-0.1.8   | 42 KB     | ############################################################################ | 100%
libgpuarray-0.7.6    | 314 KB    | ############################################################################ | 100%
gast-0.2.2           | 10 KB     | ############################################################################ | 100%
opt_einsum-3.1.0     | 48 KB     | ############################################################################ | 100%
pygpu-0.7.6          | 600 KB    | ############################################################################ | 100%
theano-1.0.4         | 3.7 MB    | ############################################################################ | 100%
tensorflow-base-2.0. | 30.9 MB   | ############################################################################ | 100%
grpcio-1.23.0        | 1.0 MB    | ############################################################################ | 100%
keras-applications-1 | 30 KB     | ############################################################################ | 100%
astor-0.7.1          | 22 KB     | ############################################################################ | 100%
keras-preprocessing- | 33 KB     | ############################################################################ | 100%
_tflow_select-2.3.0  | 3 KB      | ############################################################################ | 100%
mako-1.1.0           | 57 KB     | ############################################################################ | 100%
libprotobuf-3.11.2   | 2.2 MB    | ############################################################################ | 100%
conda-4.8.0          | 3.0 MB    | ############################################################################ | 100%
Preparing transaction: done
Verifying transaction: done
Executing transaction: done

C:\Windows\system32>set "KERAS_BACKEND="

C:\Windows\system32>python C:\ProgramData\Anaconda3\etc\keras\load_config.py  1>temp.txt

C:\Windows\system32>set /p KERAS_BACKEND= 0<temp.txt

C:\Windows\system32>del temp.txt

C:\Windows\system32>python -c "import keras"  1>nul 2>&1

C:\Windows\system32>if errorlevel 1 (
ver  1>nul
 set "KERAS_BACKEND=theano"
 python -c "import keras"  1>nul 2>&1
)

C:\Windows\system32>SET DISTUTILS_USE_SDK=1

C:\Windows\system32>SET MSSdk=1

C:\Windows\system32>SET platform=

C:\Windows\system32>IF /I [AMD64] == [amd64] set "platform=true"

C:\Windows\system32>IF /I [] == [amd64] set "platform=true"

C:\Windows\system32>if defined platform (set "VSREGKEY=HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\VisualStudio\14.0" )  ELSE (set "VSREGKEY=HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\VisualStudio\14.0" )

C:\Windows\system32>for /F "skip=2 tokens=2,*" %A in ('reg query "HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\VisualStudio\14.0" /v InstallDir') do SET "VSINSTALLDIR=%B"
ERROR: The system was unable to find the specified registry key or value.

C:\Windows\system32>if "" == "" (set "VSINSTALLDIR=C:\Program Files (x86)\Microsoft Visual Studio 14.0\Common7\Tools\" )

C:\Windows\system32>if "C:\Program Files (x86)\Microsoft Visual Studio 14.0\Common7\Tools\" == "" (
ECHO "WARNING: Did not find VS in registry or in VS140COMNTOOLS env var - your compiler may not work"
 GOTO End
)

C:\Windows\system32>echo "Found VS2014 at C:\Program Files (x86)\Microsoft Visual Studio 14.0\Common7\Tools\"
"Found VS2014 at C:\Program Files (x86)\Microsoft Visual Studio 14.0\Common7\Tools\"

C:\Windows\system32>SET "VS_VERSION=14.0"

C:\Windows\system32>SET "VS_MAJOR=14"

C:\Windows\system32>SET "VS_YEAR=2015"

C:\Windows\system32>set "MSYS2_ARG_CONV_EXCL=/AI;/AL;/OUT;/out"

C:\Windows\system32>set "MSYS2_ENV_CONV_EXCL=CL"

C:\Windows\system32>set "PY_VCRUNTIME_REDIST=\vcruntime140.dll"

C:\Windows\system32>set "CFLAGS= -MD -GL"

C:\Windows\system32>set "CXXFLAGS= -MD -GL"

C:\Windows\system32>set "LDFLAGS_SHARED= -LTCG ucrt.lib"

C:\Windows\system32>set "CXX=cl.exe"

C:\Windows\system32>set "CC=cl.exe"

C:\Windows\system32>IF /I [] == [win-64] (set "folder=x64" )  else (set "folder=x86" )

C:\Windows\system32>for /F "tokens=*" %I in ('dir "C:\Program Files (x86)\Windows Kits\*1*" /B /O:N') do for %A in (%~I) do if "%A" == "8.1" set win=%A

C:\Windows\system32>for %A in (10) do if "%A" == "8.1" set win=%A

C:\Windows\system32>if "10" == "8.1" set win=10

C:\Windows\system32>for %A in (8.1) do if "%A" == "8.1" set win=%A

C:\Windows\system32>if "8.1" == "8.1" set win=8.1

C:\Windows\system32>for /F "tokens=*" %I in ('dir "C:\Program Files (x86)\Windows Kits\*1*" /B /O:N') do for %A in (%~I) do if "%A" == "10" set win=%A

C:\Windows\system32>for %A in (10) do if "%A" == "10" set win=%A

C:\Windows\system32>if "10" == "10" set win=10

C:\Windows\system32>for %A in (8.1) do if "%A" == "10" set win=%A

C:\Windows\system32>if "8.1" == "10" set win=8.1

C:\Windows\system32>setlocal enabledelayedexpansion

C:\Windows\system32>if "10" == "10" (
for /F "tokens=*" %I in ('dir "C:\Program Files (x86)\Windows Kits\10\bin\10*" /B /O:N') do for %A in (%~I) do set last=%A
 set "sdk_bin_path=C:\Program Files (x86)\Windows Kits\10\bin\!last!\x86"
)  else (set "sdk_bin_path=C:\Program Files (x86)\Windows Kits\8.1\bin\x86" )

C:\Windows\system32>for %A in (10.0.14393.0) do set last=%A

C:\Windows\system32>set last=10.0.14393.0

C:\Windows\system32>for %A in (10.0.15063.0) do set last=%A

C:\Windows\system32>set last=10.0.15063.0

C:\Windows\system32>for %A in (10.0.16299.0) do set last=%A

C:\Windows\system32>set last=10.0.16299.0

C:\Windows\system32>for %A in (10.0.17763.0) do set last=%A

C:\Windows\system32>set last=10.0.17763.0

C:\Windows\system32>for %A in (10.0.18362.0) do set last=%A

C:\Windows\system32>set last=10.0.18362.0

C:\Windows\system32>endlocal   & set "PATH=C:\ProgramData\Anaconda3;C:\ProgramData\Anaconda3\Library\mingw-w64\bin;C:\ProgramData\Anaconda3\Library\usr\bin;C:\ProgramData\Anaconda3\Library\bin;C:\ProgramData\Anaconda3\Scripts;C:\ProgramData\Anaconda3\bin;C:\ProgramData\Anaconda3\condabin;C:\ProgramData\Anaconda3;C:\ProgramData\Anaconda3\Library\mingw-w64\bin;C:\ProgramData\Anaconda3\Library\usr\bin;C:\ProgramData\Anaconda3\Library\bin;C:\ProgramData\Anaconda3\Scripts;C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.2\bin;C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.2\libnvvp;C:\Program Files\Microsoft MPI\Bin;C:\Windows\system32;C:\Windows;C:\Windows\System32\Wbem;C:\Windows\System32\WindowsPowerShell\v1.0;C:\Windows\System32\OpenSSH;C:\Program Files (x86)\NVIDIA Corporation\PhysX\Common;C:\Program Files\dotnet;C:\Program Files\Microsoft SQL Server\130\Tools\Binn;C:\Program Files (x86)\Microsoft SQL Server\140\Tools\Binn;C:\Program Files\Microsoft SQL Server\140\Tools\Binn;C:\Program Files (x86)\Microsoft SQL Server\140\DTS\Binn;C:\Program Files\Microsoft SQL Server\140\DTS\Binn;C:\Program Files\Microsoft SQL Server\Client SDK\ODBC\130\Tools\Binn;C:\Program Files (x86)\Microsoft SQL Server\150\DTS\Binn;C:\Program Files (x86)\Microsoft SQL Server\110\DTS\Binn;C:\Program Files (x86)\Microsoft SQL Server\120\DTS\Binn;C:\Program Files (x86)\Microsoft SQL Server\130\DTS\Binn;C:\Program Files (x86)\QuickTime\QTSystem;C:\Program Files\Microsoft SQL Server\Client SDK\ODBC\170\Tools\Binn;C:\Program Files (x86)\Intel\Intel(R) Management Engine Components\DAL;C:\Program Files\Intel\Intel(R) Management Engine Components\DAL;C:\Program Files (x86)\Microsoft SQL Server\150\Tools\Binn;C:\Program Files\Microsoft SQL Server\150\Tools\Binn;C:\Program Files\Microsoft SQL Server\150\DTS\Binn;C:\Program Files\Calibre2;C:\Program Files\MiKTeX 2.9\miktex\bin\x64;C:\Program Files (x86)\Wolfram Research\WolframScript;C:\Program Files\NVIDIA Corporation\Nsight Compute 2019.5.0;C:\Program Files (x86)\Python\Python38-32\Scripts;C:\Program Files (x86)\Python\Python38-32;C:\Users\prasa\AppData\Local\Microsoft\WindowsApps;C:\Program Files\Java\jdk-13\bin;C:\Users\prasa\.dotnet\tools;C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.2\extras\CUPTI\libx64;C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.2\include;C:\Program Files (x86)\Windows Kits\10\bin\10.0.18362.0\x86"

C:\Windows\system32>IF NOT "" == "" (
set "INCLUDE=;"
 set "LIB=;"
 set "CMAKE_PREFIX_PATH=;"
)

C:\Windows\system32>SET "CMAKE_GENERATOR=Visual Studio 14 2015 Win64"

C:\Windows\system32>CALL "C:\Program Files (x86)\Microsoft Visual Studio 14.0\Common7\Tools\..\..\VC\vcvarsall.bat" amd64
