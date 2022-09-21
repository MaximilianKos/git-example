# Git exercise

---

## `git commit`

#### Question 1
What are the benefits of commits?

#### Answer
Commits help you organize your thoughts as you work on your project. They help you confirm you are only committing intentional changes, not unintentional ones. You can access all previously committed versions.

#### Question 2
Is there another way to verify a commit was created?

#### Answer
You can use `git status` and `git log`.

#### Question 3
How to check if a file is tracked and if not, then track it?

#### Answer
You can use `git ls-files --error-unmatch <file name>` to check if a file is tracked. If not the code will exit with 1.

---

## `git diff`

#### Question 1 
In which situation should you use `git diff`?

#### Answer
You should use `git diff` if you're comparing changes. It takes two input data sets and outputs the changes between them.

#### Question 2
How do you create a patch with `git diff`?

#### Answer
First, you have to generate a diff patch with `git diff > some-changes.patch`. Then copy this patch to your local machine, and apply it to your local working copy with: `git apply /path/to/some-changes.patch`.