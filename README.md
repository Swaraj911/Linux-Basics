# Linux Basics – DevOps Assignment

- **Name:** Swaraj Sutradhar
- **Module:** Linux Basics

---

## Task 1: Creating and Renaming Files/Directories:

Firstly I created a directory named `test_dir` using `mkdir` command .

<img width="1285" height="812" alt="Screenshot 2026-10-10 123003" src="https://github.com/user-attachments/assets/dadfafa9-1271-495a-bc69-11208024b2e8" />

Then I created a file inside the `test_dir` names as `example.txt` using `touch` command .

<img width="1285" height="806" alt="Screenshot 2026-10-10 123413" src="https://github.com/user-attachments/assets/9ef6c861-dea5-4b67-92bc-970ae9288860" />
After creating the file, I renamed the file name from `example.txt` to `renamed_example.txt` using `mv` command.

<img width="1282" height="807" alt="Screenshot 2026-10-10 123528" src="https://github.com/user-attachments/assets/540f4157-f13e-4e29-b82d-3914f40a0c42" />
---

## Task 2: Viewing File Contents:

I displayed the contents of `/etc/passwd` using `cat` command.

<img width="1283" height="807" alt="Screenshot 2026-10-10 125347" src="https://github.com/user-attachments/assets/0fa89f0f-677f-41ea-b889-f3e75f772c9d" />
<img width="1283" height="808" alt="Screenshot 2026-10-10 125406" src="https://github.com/user-attachments/assets/852b72f4-762c-4a1f-8a85-6dd4dff345dc" />
I displayed the first 5 lines of `/etc/passwd` using `head` command.

<img width="1285" height="807" alt="Screenshot 2026-10-10 125538" src="https://github.com/user-attachments/assets/4712c6bb-cb27-4203-b91f-a41b98ab3fc1" />
Lastly, I displayed the last 5 lines of `/etc/passwd` using `tail` command.

<img width="1278" height="811" alt="Screenshot 2026-10-10 125646" src="https://github.com/user-attachments/assets/a5722135-809e-47b1-9f40-15102b6bca5e" />
---

## Task 3: Searching for Patterns:

I used `grep` command to find all the lines containing the word “root” in `/etc/passwd`.

<img width="1283" height="805" alt="Screenshot 2026-10-10 125933" src="https://github.com/user-attachments/assets/d27fa09a-eadc-4610-8100-d638b28a8e2b" />
---

## Task 4: Zipping and Unzipping:

I compressed the `test_dir` to a file named `test_dir.zip` using `zip` command.

<img width="1282" height="805" alt="Screenshot 2026-10-10 130708" src="https://github.com/user-attachments/assets/d0b72756-f421-49c2-a235-d131863adf2b" />
<img width="1283" height="805" alt="Screenshot 2026-10-10 130749" src="https://github.com/user-attachments/assets/801fa9c9-73e9-450e-99ad-9fd1265a6d7e" />
After compressing, I unzipped the `test_dir.zip` file with a new name `unzipped_dir` using `unzip` command.

<img width="1282" height="807" alt="Screenshot 2026-10-10 131336" src="https://github.com/user-attachments/assets/6880625b-955a-4636-9c83-e332bcc2bae3" />
<img width="1282" height="805" alt="Screenshot 2026-10-10 151503" src="https://github.com/user-attachments/assets/9f42fda8-3079-4632-81d2-04f7352a4bf6" />
---

## Task 5: Downloading Files:

I used `wget` command to download to a file from a URL.

<img width="1286" height="811" alt="Screenshot 2026-10-10 153450" src="https://github.com/user-attachments/assets/23f2ede1-6a78-47bd-8b2e-4a66295f1731" />
<img width="1287" height="805" alt="Screenshot 2026-10-10 170106" src="https://github.com/user-attachments/assets/671ff4b3-6ac4-4b00-be00-c117b7ad1cbf" />
---

## Task 6: Changing Permissions:

I created a file named `secure.txt` using `touch` command and then changed the permission for read only for everyone using `chmod` command.

<img width="1282" height="805" alt="Screenshot 2026-10-10 155245" src="https://github.com/user-attachments/assets/9000c5ab-40de-473f-9d90-8d1daac48cbb" />
---

## Task 7: Working with Environment Variables:

I used `export` command to set a new environment variable named as `MY_VAR` and also a added a value- “Hello, Linux!”.

<img width="1286" height="811" alt="Screenshot 2026-10-10 155739" src="https://github.com/user-attachments/assets/27c13baa-2cb6-4f92-aaa6-8100cb5bca17" />
