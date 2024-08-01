# cpp_console_app_template

Basic C++ project configuration to start a console simple application.

You can start by clicking 'Use this template' at the upper right corner of Github.

Then, you need to get the basic dependencies, you need to initialize and update the submodules by executing at the rrot of the repository:
```
git submodule update --init --recursive
```
once you are done, you can generate the build files with cmake presets.
```
cmake --presets ninja-release
```
And then, jujst go to `../build_cmake/ninja-release/` and execute `ninja` and you will get your binary file.
You can also get a Visual Studio solution file for your convenience, check [CMakePresets.json](CMakePresets.json) file.

yes, you should have [cmake](https://cmake.org/), [ninja](https://ninja-build.org/) and a compiler such as [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) availables in your development environment.

EOF
