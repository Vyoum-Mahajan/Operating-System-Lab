# Experiment 6: User Information and Text Processing in Linux

This experiment demonstrates Linux commands for displaying user information and performing basic text processing.

## Programs

1. **Display Current User Information**
   - Displays the current username using `whoami`.
   - Displays user and group IDs using `id`.
   - Displays current login sessions using `who`.
   - Displays the current date and time using `date`.

2. **Display User Login History**
   - Shows the five most recent login records using `last -n 5`.
   - Displays the current username.

3. **Count Lines, Words and Characters**
   - Creates `sample.txt`.
   - Displays its contents.
   - Counts lines using `wc -l`, words using `wc -w`, and characters using `wc -m`.

4. **Extract a Specific Line**
   - Displays the first, second, and third lines of `sample.txt` using `sed`.

5. **Search for a Word in a File**
   - Searches for `Linux` using `grep -n`.
   - Prints a success or not-found message.

6. **Replace Text Using `sed`**
   - Displays the original text.
   - Prints text with `Linux` replaced by `Ubuntu`.
   - The command displays modified output without changing the source file.

7. **Display Unique Lines**
   - Creates `duplicate.txt` with repeated fruit names.
   - Displays the original lines and then sorted unique lines using `sort -u`.

8. **Sort Text File Contents**
   - Creates `fruits.txt`.
   - Displays the original contents and the sorted output using `sort`.

## Requirements

- Linux or a Bash-compatible environment
- Standard utilities: `whoami`, `id`, `who`, `date`, `last`, `cat`, `wc`, `sed`, `grep`, and `sort`

## Running

Run a script with:

```bash
bash script_name.sh
```

Or make it executable:

```bash
chmod +x script_name.sh
./script_name.sh
```

## Notes

- Scripts that create `sample.txt`, `duplicate.txt`, or `fruits.txt` may overwrite files with those names in the current directory.
- Programs 4–6 expect `sample.txt` to exist and contain the intended sample text. Run Program 3 first if needed.
- `sort -u` both sorts the lines and removes duplicates.

## Result

User information commands, login history, line extraction, searching, counting, sorting, and text replacement using Linux commands were studied.
