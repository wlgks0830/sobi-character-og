# sobi-character-og

앱인토스 미니앱 **소비 캐릭터 테스트**(`sobi-character`)의 공유 카드 이미지예요.

친구에게 결과를 공유하면 카드 미리보기에 이 이미지가 붙어요.
16종 캐릭터별로 한 장씩, 1200×630 PNG 입니다.

사용 주소:

```
https://raw.githubusercontent.com/wlgks0830/sobi-character-og/main/{코드}.png
```

`{코드}`는 `PVSA` 처럼 4글자예요. 앱 코드에서는 `src/config.ts` 의
`OG_IMAGE_BASE_URL` 에 위 주소의 `{코드}.png` 앞부분까지만 넣어 둡니다.

`app-icon.png`(600×600)는 앱 아이콘 후보라 공유 카드에는 쓰지 않아요.

파일 이름을 바꾸면 공유 카드가 깨지니 그대로 두세요.
