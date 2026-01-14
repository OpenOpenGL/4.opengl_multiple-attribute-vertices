To run it first create build folder using

```
mkdir build
```

then 
```
cd build
cmake ..
make
./MyOpenGLProject
```
This is how your file structure should look

```
.
├── CMakeLists.txt
├── README.md
├── build
├── include
│   ├── KHR
│   │   └── khrplatform.h
│   └── glad
│       └── glad.h
└── src
    ├── glad.c
    └── main.cpp
```
