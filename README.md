# udemy-courses
Courses followed and completed on udemy.com

## Repository structure

```
udemy-courses/
├── csharp/          # C# courses (one sub-folder per course)
└── rust/            # Rust courses (one sub-folder per course)
```

Each course lives in its own sub-folder under the relevant language directory and contains its own README with course details, progress notes, and setup prerequisites.

## Active courses

| Language | Course | Folder |
|----------|--------|--------|
| Rust | [Hands-On Data Structures and Algorithms in Rust](https://www.udemy.com/course/hands-on-data-structures-and-algorithms-in-rust/) | `rust/hands-on-data-structures-and-algorithms/` |

## Quick-start

### Rust
```bash
cd rust/hands-on-data-structures-and-algorithms
cargo test --workspace        # run all tests
cargo build --workspace       # build all crates
cargo test -p linked-lists    # run tests for a single topic
```

### C#
```bash
cd csharp/<course-slug>
dotnet build
dotnet test
```
