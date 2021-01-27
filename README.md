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

### Step6

### Build and Test
```bash
$ mkdir Step6_build
$ cd Step6_build
$ cmake ../Step6 -DUSE_MYMATH=ON
$ cmake --build .
```

```bash
$ ctest -N
$ ctest -VV
```

### Step7

### Build and Test
```bash
$ mkdir Step7_build && cd Step7_build
$ cmake ../Step7 -DUSE_MYMATH=ON
$ cmake --build .
```

```bash
$ ctest -N
$ ctest -VV
```

### Step8

### Build and Test
```bash
$ mkdir Step8_build && cd Step8_build
$ cmake ../Step8 -DUSE_MYMATH=ON
$ ctest [-VV] -D Experimental
```

```bash
$ ctest -N
$ ctest -VV
```

### Step9

### Build and Test
```bash
$ mkdir Step9_build && cd Step9_build
$ cmake ../Step9 -DUSE_MYMATH=OFF
$ cmake --build .
```

```bash
$ ctest -N
$ ctest -VV
```