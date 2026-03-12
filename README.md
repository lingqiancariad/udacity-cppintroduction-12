### For general README from the project -> https://github.com/cpp-io2d/P0267_RefImpl.git

### To enable building of this project:
1. e2a030050b77e33ba5d67b3ada5790e97a3f4973 checkout the adaption on CMakeList
2. use following config for settings.json for VSCode
   ```
   {
      "cmake.configureArgs": [
        "-DCMAKE_TOOLCHAIN_FILE=C:/Users/S4RHZME/Projects/vcpkg/vcpkg/scripts/buildsystems/vcpkg.cmake",
        "-DIO2D_BACKEND=CAIRO_WIN32",
        "-DIO2D_DEFAULT=CAIRO_WIN32",
        "-DIO2D_WITHOUT_SAMPLES=ON",
        "-DICONV_LIB=C:/Users/S4RHZME/Projects/vcpkg/vcpkg/packages/libiconv_x64-windows/lib/iconv.lib",
        "-DCHARSET_LIB=C:/Users/S4RHZME/Projects/vcpkg/vcpkg/packages/libiconv_x64-windows/lib/charset.lib",
        "-DCMAKE_INSTALL_PREFIX=C:/Users/S4RHZME/Projects/io2d_built"
        ]
    }
    ```
   <img width="174" height="67" alt="image" src="https://github.com/user-attachments/assets/ae35b5a3-6c95-4142-84d4-0ef5b4d4d487" />
