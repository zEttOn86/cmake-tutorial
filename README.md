### Step1

#### Build and Test
```bash
$ mkdir Step1_build
$ cd Step1_build
$ cmake ../Step1
$ cmake --build .
```

```bash
./Tutorial 10
./Tutorial
```

### Step2

### Build and Test
```bash
$ mkdir Step1_build
$ cd Step1_build
$ cmake ../Step2 -DUSE_MYMATH=[OFF or ON]
$ cmake --build .
```

```bash
./Tutorial 4
```

### Step4

### Build and Test
```bash
$ mkdir Step4_build
$ cd Step4_build
$ cmake ../Step4 -DUSE_MYMATH=OFF
$ cmake --build .
```

```bash
$ ctest -N
$ ctest -VV
```
