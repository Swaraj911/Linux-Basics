# Linux Basics – DevOps Assignment

- **Name:** Swaraj Sutradhar
- **Module:** Linux Basics
- **Github Repository:** [Your Repository URL](https://github.com/<your-username>/<repo-name>)

---

## Task 1: Creating and Renaming Files/Directories:

Firstly I created a directory named `test_dir` using `mkdir` command .

![Create test_dir](screenshots/task1_1.png)

Then I created a file inside the `test_dir` names as `example.txt` using `touch` command .

![Create example.txt](screenshots/task1_2.png)

After creating the file, I renamed the file name from `example.txt` to `renamed_example.txt` using `mv` command.

![Rename example.txt](screenshots/task1_3.png)

---

## Task 2: Viewing File Contents:

I displayed the contents of `/etc/passwd` using `cat` command.

![Display /etc/passwd](screenshots/task2_1.png)

![Display /etc/passwd continued](screenshots/task2_2.png)

I displayed the first 5 lines of `/etc/passwd` using `head` command.

![Head /etc/passwd](screenshots/task2_3.png)

Lastly, I displayed the last 5 lines of `/etc/passwd` using `tail` command.

![Tail /etc/passwd](screenshots/task2_4.png)

---

## Task 3: Searching for Patterns:

I used `grep` command to find all the lines containing the word “root” in `/etc/passwd`.

![Grep root](screenshots/task3_1.png)

---

## Task 4: Zipping and Unzipping:

I compressed the `test_dir` to a file named `test_dir.zip` using `zip` command.

![Zip test_dir](screenshots/task4_1.png)

![Zip file in GUI](screenshots/task4_2.png)

After compressing, I unzipped the `test_dir.zip` file with a new name `unzipped_dir` using `unzip` command.

![Unzip command](screenshots/task4_3.png)

![Unzipped directory GUI](screenshots/task4_4.png)

---

## Task 5: Downloading Files:

I used `wget` command to download to a file from a URL.

![Wget download](screenshots/task5_1.png)

![Downloaded file GUI](screenshots/task5_2.png)

---

## Task 6: Changing Permissions:

I created a file named `secure.txt` using `touch` command and then changed the permission for read only for everyone using `chmod` command.

![Chmod secure.txt](screenshots/task6_1.png)

---

## Task 7: Working with Environment Variables:

I used `export` command to set a new environment variable named as `MY_VAR` and also a added a value- “Hello, Linux!”.

![Export MY_VAR](screenshots/task7_1.png)
