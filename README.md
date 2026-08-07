# Jjaptoon Komikku / Mihon Store Index

이 폴더를 GitHub의 새 Public 저장소 루트에 그대로 업로드하세요.

필수 구조:

jjaptoon-store-index/
├─ index.min.json
├─ index.json
├─ apk/
│  └─ tachiyomi-ko.jjaptoon-v1.6.1.apk
└─ icon/
   └─ eu.kanade.tachiyomi.extension.ko.jjaptoon.png

## Komikku에 입력할 URL

GitHub 사용자명이 USERNAME, 저장소 이름이 REPOSITORY라면:

https://raw.githubusercontent.com/USERNAME/REPOSITORY/refs/heads/main/index.min.json

예:
https://raw.githubusercontent.com/example/jjaptoon-extension/refs/heads/main/index.min.json

중요:
- GitHub 저장소는 Public으로 만드세요.
- ZIP 파일 자체를 GitHub에 올리는 것이 아니라, ZIP을 풀어서 위 파일/폴더들이 저장소 루트에 보이도록 업로드하세요.
- APK는 apk/ 폴더 안에 있어야 합니다.
- index.min.json은 저장소 루트에 있어야 합니다.

현재 메타데이터:
- Package: eu.kanade.tachiyomi.extension.ko.jjaptoon
- Version: 1.6.1
- Version code: 1
- Source: 짭툰
- Source ID: 6220307967993008309
- Base URL: https://www.jjaptoon005.com
