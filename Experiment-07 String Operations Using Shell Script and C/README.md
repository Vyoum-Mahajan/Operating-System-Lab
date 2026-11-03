# Experiment 7: String Operations Using Shell Script and C

This experiment demonstrates how to extract a substring, find string length, and observe program execution time using Bash and C.

## Programs

### 1. Bash: Extract Substring and Find Length

The shell script:
- Accepts a string from the user.
- Accepts a starting position and substring length.
- Extracts the requested portion using `cut -c`.
- Displays the string length using Bash's `${#str}`.

### 2. C: Extract Substring and Find Length

The C program:
- Reads a string.
- Accepts a starting position (0-based) and substring length.
- Prints the selected characters.
- Displays the string length using `strlen()`.

### 3. Compare Running Time

The experiment uses the `time` command to observe runtime:

```bash
time bash substring.sh

gcc substring.c -o substring
time ./substring
```

## Requirements

- Linux, WSL, or another Bash-compatible environment
- GCC compiler for the C program

## Running the Bash Program

```bash
bash substring.sh
```

Or:

```bash
chmod +x substring.sh
./substring.sh
```

## Compiling and Running the C Program

```bash
gcc substring.c -o substring
./substring
```

## Important Notes

- Bash's `cut -c` positions begin at **1**. The C program uses a **0-based** starting position.
- The C program uses `scanf("%99s", str)`, so it reads a single word and does not accept spaces within the input string.
- Enter non-negative start positions and lengths that fit the input string.
- Run the timing commands more than once for a more useful observation. Results can vary with system load and timing overhead.

## Learning Outcomes

- Extract substrings using Bash and C.
- Determine string length.
- Use `cut`, `strlen()`, and Bash string-length expansion.
- Use `time` to observe command execution duration.

## Result

Substring extraction, string-length calculation, and basic runtime observation using Bash and C were studied.
