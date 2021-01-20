# Reading Level Approximation

Given a sample input from a test, "reading_level.c" uses the [Coleman-Liau index](https://readabilityformulas.com/coleman-liau-readability-formula.php "The Coleman-Liau index") to output the reading level according to the index.

## Usage

The input must be text of any length up to a 10,000 character limit. It should be without newlines, or else the sample will terminate at the newline.

```c

Input: It was almost December, and Jonas was beginning to be frightened. No. Wrong word, Jonas thought. Frightened meant that deep, sickening feeling of something terrible about to happen. Frightened was the way he had felt a year ago when an >unidentified aircraft had overflown the community twice. He had seen it both times.

Output: Grade 10

```

## Sample Run

![Sample output](sample_run.png?raw=true "Sample Output")
