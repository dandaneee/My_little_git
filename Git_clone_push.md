1. new repository 생성

2. 주소 복사

   ![tempsnip](C:/Users/Robot/Documents/md_images/tempsnip.jpg)

3. 폴더 선택 - git bash

4. $ git clone  ' 복사한 clone주소 '

5. 폴더 내부 repository명 파일 생성

6. push 파일 repository파일로 이동

7. $ cd assign_java/

8. $ git status 확인 - Untracked files:

9. $ git add ' 파일명 '

10. $ git status 확인 - Changes to be committed:

11. commit - $ git commit -m 'first init'

12. $ git push origin master

!! error

remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead. remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information. fatal: unable to access 'https://github.com/dandaneee/assign_java.git/': The requested URL returned error: 403

—>https://firstquarter.tistory.com/entry/Git-토큰-인증-로그인-remote-Support-for-password-authentication-was-removed-on-August-13-2021-Please-use-a-personal-access-token-instead

블로그 참고해서 해결완료