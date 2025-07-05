# File Manipulation Commands:-

| Command |          Syntax         | Description                          | Forensic Usage                 |
|---------|-------------------------|--------------------------------------|--------------------------------|
| ls      | ls -la /path            | List directory contents with details | List hidden files, timestamps  |
| cp      | cp file1 file2          | Copy files                           | Duplicate evidence files safely|
| mv      | mv file1 new location   | Move/rename files                    | Organize seized files          |
| rm      | rm filename             | Delete files                         | Detect if files were deleted   |
| touch   | touch filename          | Create empty file/update timestamp   | Observe timestamp tampering    |
| cat     | cat filename            | Display file content                 | Inspect logs quickly           |
| less    | less filename           | View file paginated                  | Review large evidence files    |
| grep    | grep "keyword" file     | Search text patterns                 | Find suspicious entries        |
| find    | find /path -name"*.log" | Locate files by name                 | Discover logs                  |
| diff    | diff file1 file2        | Compare files                        | Detect unauthorized changes    |
