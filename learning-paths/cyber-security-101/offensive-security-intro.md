# TryHackMe - Offensive Security Intro
**Difficulty:** Easy

## 🧠 Key Takeaways / Summary
*A paragraph or two summarizing what you learned in your own words. This is the most important part for reinforcing knowledge.*
> This room provided a hands-on introduction to the Linux command line. I solidified my understanding of the hierarchical file system and practiced moving between directories. The concept of absolute vs. relative paths became much clearer through the exercises.

## 🔧 New Tools / Commands Encountered
*List tools and commands you used for the first time, with a brief description of their general purpose.*
- `ls` - Lists directory contents.
- `cat` - Concatenates and displays file content.
- `find` - Searches for files in a directory hierarchy.

## 💡 Interesting Concepts & Notes
*Detailed notes on concepts that were new, challenging, or important. Use code blocks for general examples only.*
### The Linux Filesystem Hierarchy
- Learned that `/` is the root directory.
- `/home` contains user directories.
- `/etc` often stores configuration files.

### File Permissions
- Permissions are split into three groups: User, Group, and Others.
- They are represented by `r` (read), `w` (write), and `x` (execute).
- Example of how to *interpret* permissions: `-rw-r--r--` means the file is readable/writable by the owner, but only readable by everyone else.

## 🚧 Challenges Faced
*Be honest about what was difficult. This shows your learning process.*
- I initially kept confusing `..` (parent directory) with `.` (current directory) when using `cd`.
- Understanding the difference between `>` (overwrite) and `>>` (append) shell operators took a couple of tries.

## 🔗 Connect the Dots


