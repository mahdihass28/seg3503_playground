# seg3503_playground

| Field    | Value         |
|----------|---------------|
| Course   | SEG 3503      |
| Date     | Summer 2026   |
| Student  | Mahdi Roueh   |
| Email    | mrouehs11@gmail.com |

---

## Lab 1

Both projects live in `Lab1/`. Run all commands from inside each project folder using **Git Bash** (Windows) or a standard terminal (Mac/Linux).

### Java — newmath_java

**Requirements:** Java 21+

```bash
cd Lab1/newmath_java

# Run the interactive division program
bin/run

# Run JUnit tests
bin/test
```

**Run output:**
```
Newmath (type 'exit' to exit program)
Numerator: 5
Demoninator: 5
5 / 5 = 1
Numerator: exit
```

**Test output:**
```
Thanks for using JUnit! Support its development at https://junit.org/sponsoring

├─ JUnit Jupiter ✔
│  └─ NewmathTest ✔
│     ├─ div_ok() ✔
│     └─ div_by_zero() ✔
└─ JUnit Vintage ✔

Test run finished after 40 ms
[         3 containers found      ]
[         0 containers skipped    ]
[         3 containers started    ]
[         0 containers aborted    ]
[         3 containers successful ]
[         0 containers failed     ]
[         2 tests found           ]
[         0 tests skipped         ]
[         2 tests started         ]
[         0 tests aborted         ]
[         2 tests successful      ]
[         0 tests failed          ]
```

---

### Elixir — newmath_ex

**Requirements:** Elixir 1.14+ with Erlang/OTP 25+

```bash
cd Lab1/newmath_ex

# Run interactive IEx session
bin/run
# Then in IEx:
#   iex(1)> NewmathEx.div(5, 2)
#   {:ok, 2.5}
#   iex(2)> NewmathEx.div(5, 0)
#   {:error, "Cannot divide by zero"}

# Run ExUnit tests
bin/test
```

**Test output:**
```
...
Finished in 0.01 seconds (0.00s async, 0.01s sync)
1 doctest, 2 tests, 0 failures
```

---

## Screenshots

### Java version
<!-- Add screenshot of: java --version -->

### Java run
<!-- Add screenshot of bin/run output -->

### Java test
<!-- Add screenshot of bin/test output -->

### Elixir version
<!-- Add screenshot of: elixir --version -->

### Elixir run
<!-- Add screenshot of bin/run with NewmathEx.div calls -->

### Elixir test
<!-- Add screenshot of bin/test output -->
