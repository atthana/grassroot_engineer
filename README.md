# grassroot-engineer web
A Sample page that created from Flutter2 to show grassroot's story and interesting things.



---

Path is in `/Private_Q/Website/Learnings/grassroot_engineer`

## Flutter version is: 
```
Flutter 2.2.3 • channel stable • https://github.com/flutter/flutter.git
Framework • revision f4abaa0735 (5 months ago) • 2021-07-01 12:46:11 -0700
Engine • revision 241c87ad80
Tools • Dart 2.13.4
```
## Creating flutter for web:

1. Open Android studio `File > New > New Flutter Project...`
2. Type command `flutter create .`
3. Create repo in github (type only repo name > Create repository)
```
git init
git add .
git commit -m "Initial project"
git branch -M main
git remote add origin https://github.com/atthana/grassroot_engineer.git
git push -u origin main
```
4. Test by command.
```
flutter2 run -d chrome
flutter2 build web
```
5. After run `flutter2 build web` will get files in path `grassroot_web/build/web`.
-  Copy all of files to root (this is important step na)
<br><br>
6. Setup github to support `github pages`
- Settings > Pages > Branch:main > (root) > Save
- It will show published site at `https://atthana.github.io/grassroot_engineer/`
<br><br>
7. The last important thing is go to file `index.html` that just was created from command `flutter2 build web` then add more text in line14 from `<base href="/">` to below:<br><br>
```<base href="/grassroot_engineer/">```
<br><br>
8. Go to [here](https://atthana.github.io/grassroot_engineer/) should be shown the website as expected.

<br><br>

#### References of setup Flutter web with Github pages.
https://www.youtube.com/watch?v=YfNC0QiYNB8&t=175s

---
Wrote by GRASSROOT ENGINEER | T-rex :t-rex: | Sunflower :sunflower: | Tomato :tomato:

