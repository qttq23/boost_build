- download zip file

- check if file with specified version exists & unzip

- cd to boost root folder

- build b2:   
bootstrap.bat

- build libraries:  
b2 variant=release link=shared address-model=64 toolset=msvc --with-filesystem --with-iostreams install --prefix=%cd%/../boost_1_79_0_win32_x64_release

