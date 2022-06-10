- 👋 Hi, I’m @rijawan81
- 👀 I’m looking to solve below assignment ...
- Please, clone MariaDB server from github. check out the release
10.5.15. Build a debug binary. Create an mtr test case that should
create a table with two columns, id and height and fill it with one
million rows. Integer ids in the range from 0 to 999999, heighs should
be distributed naturally, like heighs of humans. After filling the
table the test should perform two select queries. Both are to find the
average height of all people whose ids start from "1234". One select
you can do any way you want, the shortest, the simplest, the fastest,
whatever, up to you. The second select should return the same result,
but also test for a bug in the optimizer related to long NOT IN()
lists. So it should have WHERE id NOT IN (all values except those that
start from 1234). Note, not a subquery, but literally, a list of
numbers (1234,12340,12341, etc)

As a result, please, send the output of mtr script.

Hints: 1. "MTR" is the "mysql-test-run" test runner tool, it's part of
the source tree. 2. Google is your friend, there's enough information
online on every step from the above assignment. 3. The test file will
have lots of rows and numbers, you can use anything you want to
generate it, pure SQL, python, Javascript, Google, whatever.
...
- 🌱 I’m currently learning ...AI with maching learning 
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
rijawan81/rijawan81 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
