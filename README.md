Commands to complete this assignment are as follows.

task 5:

1. mkdir task5
2. git init
3. touch master.txt
4. git add master.txt
5. git commit -m 'Inital commit to master'
6. git remote add origin https://[secret-key-token]@github.com/98aj/Git-Assignment-task5.git
7. git push -u origin master
8. git branch develop
9. git branch feature/myFeature
10. git branch release
11. git branch hotfix
12. git switch feature/myFeature
13. touch feature1.txt feature2.txt
14. echo 'Hello this is First feature' > feature1.txt
15. echo 'Hello this is Second feature' > feature2.txt
16. git add .
17. git commit -m 'Creating 2 feature for my git project'
18. git push -u origin feature/myFeature
19. git switch develop
20. git merge feature/myFeature
(Adding an new feature)
21. git switch feature/myFeature
22. echo 'This is new feature created' > feature3.txt
23. git add feature3.txt
24. git commit -m 'New feature was created'
25. git push -u origin feature/myFeature
26. git switch develop
27. git merge feature/myFeature
28. git push -u origin develop
(After testing on develop we encounter that feature3 was failing in some scinerio so we release only feature1 and feature2)
29. git switch release
30. git log develop (to get commit id)
31. git cherry-pick 09b99cb (to take only feature1 and feature2 code to release branch)
32. git push -u origin release
(merging release branch to master)
33. git switch master
34. git merge release
35. git push -u origin master
(Now performing hotfix)
36. git switch hotfix
37. git pull origin master
38. echo 'Urgent fixs' > urgent.txt
39. git add urgent.txt
40. git commit -m 'Urgent fix form hotfix branch'
41. git push -u origin hotfix
42. git switch master
43. git merge hotfix
44. git push -u origin master
(Merging hotfix in develop and release so have latest changes form master)
45. git switch develop
46. git merge hotfix
48. git push -u origin develop
49. git switch release
50. git merge hotfix
51. git push -u origin release
