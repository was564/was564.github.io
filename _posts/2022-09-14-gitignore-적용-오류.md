.gitignore가 적용이 안될 때는 캐시가 문제인 경우가 대부분이였다. (아닐수도)

``` git
git rm -r --cached .
git add .
```

위 명령어를 치면 캐시가 지워지므로 다시 적용되는 것을 볼 수 있었다.

출처 : https://jojoldu.tistory.com/307