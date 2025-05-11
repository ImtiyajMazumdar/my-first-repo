user@imtiyaj MINGW64 ~
$ cd /d/my-first-repo/my-first-repo

user@imtiyaj MINGW64 /d/my-first-repo/my-first-repo (main)
$ user@imtiyaj MINGW64 /d/my-first-repo/my-first-repo (main)
bash: syntax error near unexpected token `('

user@imtiyaj MINGW64 /d/my-first-repo/my-first-repo (main)
$ ls
LICENSE          former-vc.html                   regional-center-dhaka.html
auth.html        images/                          regional-center-rajshahi.html
chancellor.html  index.html                       school-of-education.html
faq.html         regional-center-chattogram.html

user@imtiyaj MINGW64 /d/my-first-repo/my-first-repo (main)
$ ls -a
./         chancellor.html  regional-center-chattogram.html
../        faq.html         regional-center-dhaka.html
.git/      former-vc.html   regional-center-rajshahi.html
LICENSE    images/          school-of-education.html
auth.html  index.html

user@imtiyaj MINGW64 /d/my-first-repo/my-first-repo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        auth.html
        chancellor.html
        faq.html
        former-vc.html
        images/
        index.html
        regional-center-chattogram.html
        regional-center-dhaka.html
        regional-center-rajshahi.html
        school-of-education.html

nothing added to commit but untracked files present (use "git add" to track)

user@imtiyaj MINGW64 /d/my-first-repo/my-first-repo (main)
$ git add .
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

user@imtiyaj MINGW64 /d/my-first-repo/my-first-repo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   auth.html
        new file:   chancellor.html
        new file:   faq.html
        new file:   former-vc.html
        new file:   images/1830000182327303.jpeg
        new file:   images/1830086712325681.jpg
        new file:   images/1830277502635591.jpeg
        new file:   images/1830526882780829.jpg
        new file:   images/1830527586262099.jpeg
        new file:   images/1830634688796273.jpeg
        new file:   images/1831164705658034.jpg
        new file:   images/1831165009731008.jpg
        new file:   images/1831275439444441.jpg
        new file:   images/1831523313027465.jpg
        new file:   images/26_march_banner_2025.jpg
        new file:   images/INNOVATION.jpg
        new file:   images/Prof_Dr_M_Aminul_Islam.jpg
        new file:   images/Prof_Dr_M_Ershadul_Bari.jpg
        new file:   images/Prof_Dr_M_Farid_Ahmed.jpg
        new file:   images/Prof_Muhammad_Qaisuddinn.jpg
        new file:   images/R.I.M_Aminur_Rashid.jpg
        new file:   images/Shamsher_Ali.jpg
        new file:   images/apa.jpg
        new file:   images/banner_1432.jpg
        new file:   images/bou_google_map.jpg
        new file:   images/bou_logo.jpg
        new file:   images/bouchanecellor.jpg
        new file:   images/chattogram-banner.jpg
        new file:   images/complain.jpg
        new file:   images/ctg.jpg
        new file:   images/dhaka-banner.jpg
        new file:   images/fbanner20242.jpg
        new file:   images/fbanner20243.jpg
        new file:   images/fbanner20244.jpg
        new file:   images/icons8-email-48.png
        new file:   images/icons8-facebook-48.png
        new file:   images/icons8-insta-48.png
        new file:   images/icons8-linkedin-50.png
        new file:   images/icons8-radio-station-48.png
        new file:   images/icons8-twitter-50.png
        new file:   images/icons8-webex-48.png
        new file:   images/icons8-youtube-24.png
        new file:   images/infocom.jpg
        new file:   images/nis.jpg
        new file:   images/nsda_bou_mou_banner.jpg
        new file:   images/pvc_Sayeed _Ferdous.jpg
        new file:   images/pvc_bou.jpg
        new file:   images/rajshahi-banner.jpg
        new file:   images/treasurer_bou.jpg
        new file:   images/vc_bou.jpg
        new file:   images/web_banner1.jpg
        new file:   images/web_banner3.jpg
        new file:   index.html
        new file:   regional-center-chattogram.html
        new file:   regional-center-dhaka.html
        new file:   regional-center-rajshahi.html
        new file:   school-of-education.html


user@imtiyaj MINGW64 /d/my-first-repo/my-first-repo (main)
$ git commit -m "Add BOU website files"
[main 244af1c] Add BOU website files
 57 files changed, 5206 insertions(+)
 create mode 100644 auth.html
 create mode 100644 chancellor.html
 create mode 100644 faq.html
 create mode 100644 former-vc.html
 create mode 100644 images/1830000182327303.jpeg
 create mode 100644 images/1830086712325681.jpg
 create mode 100644 images/1830277502635591.jpeg
 create mode 100644 images/1830526882780829.jpg
 create mode 100644 images/1830527586262099.jpeg
 create mode 100644 images/1830634688796273.jpeg
 create mode 100644 images/1831164705658034.jpg
 create mode 100644 images/1831165009731008.jpg
 create mode 100644 images/1831275439444441.jpg
 create mode 100644 images/1831523313027465.jpg
 create mode 100644 images/26_march_banner_2025.jpg
 create mode 100644 images/INNOVATION.jpg
 create mode 100644 images/Prof_Dr_M_Aminul_Islam.jpg
 create mode 100644 images/Prof_Dr_M_Ershadul_Bari.jpg
 create mode 100644 images/Prof_Dr_M_Farid_Ahmed.jpg
 create mode 100644 images/Prof_Muhammad_Qaisuddinn.jpg
 create mode 100644 images/R.I.M_Aminur_Rashid.jpg
 create mode 100644 images/Shamsher_Ali.jpg
 create mode 100644 images/apa.jpg
 create mode 100644 images/banner_1432.jpg
 create mode 100644 images/bou_google_map.jpg
 create mode 100644 images/bou_logo.jpg
 create mode 100644 images/bouchanecellor.jpg
 create mode 100644 images/chattogram-banner.jpg
 create mode 100644 images/complain.jpg
 create mode 100644 images/ctg.jpg
 create mode 100644 images/dhaka-banner.jpg
 create mode 100644 images/fbanner20242.jpg
 create mode 100644 images/fbanner20243.jpg
 create mode 100644 images/fbanner20244.jpg
 create mode 100644 images/icons8-email-48.png
 create mode 100644 images/icons8-facebook-48.png
 create mode 100644 images/icons8-insta-48.png
 create mode 100644 images/icons8-linkedin-50.png
 create mode 100644 images/icons8-radio-station-48.png
 create mode 100644 images/icons8-twitter-50.png
 create mode 100644 images/icons8-webex-48.png
 create mode 100644 images/icons8-youtube-24.png
 create mode 100644 images/infocom.jpg
 create mode 100644 images/nis.jpg
 create mode 100644 images/nsda_bou_mou_banner.jpg
 create mode 100644 images/pvc_Sayeed _Ferdous.jpg
 create mode 100644 images/pvc_bou.jpg
 create mode 100644 images/rajshahi-banner.jpg
 create mode 100644 images/treasurer_bou.jpg
 create mode 100644 images/vc_bou.jpg
 create mode 100644 images/web_banner1.jpg
 create mode 100644 images/web_banner3.jpg
 create mode 100644 index.html
 create mode 100644 regional-center-chattogram.html
 create mode 100644 regional-center-dhaka.html
 create mode 100644 regional-center-rajshahi.html
 create mode 100644 school-of-education.html

user@imtiyaj MINGW64 /d/my-first-repo/my-first-repo (main)
$

user@imtiyaj MINGW64 /d/my-first-repo/my-first-repo (main)
$ git push origin main
Enumerating objects: 61, done.
Counting objects: 100% (61/61), done.
Delta compression using up to 8 threads
Compressing objects: 100% (60/60), done.
Writing objects: 100% (60/60), 5.33 MiB | 462.00 KiB/s, done.
Total 60 (delta 9), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (9/9), done.
To https://github.com/ImtiyajMazumdar/my-first-repo.git
   bac727f..244af1c  main -> main

user@imtiyaj MINGW64 /d/my-first-repo/my-first-repo (main)
$
