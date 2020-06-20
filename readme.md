### diffdir

#### Installation

```bash
pip install diffdir
```

#### Usage

```bash
diffdir dir_a dir_b
```

#### Interface

Suppose

```bash
$ tree dir_a
dir_a
├── common.txt
└── foo
    └── end
```

```bash
$ tree dir_b
dir_b
├── bar
│   └── end
└── common.txt
```

Then

```python
Only in dir_a:	/foo
Only in dir_b:	/bar
(0)  Diff dir_a	dir_b		/common.txt
(q)Quit;(d)Diff all;(dX)Diff line X
```

