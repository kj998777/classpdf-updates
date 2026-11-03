# classpdf-updates

수업 PDF(ClassPDF) 자동 업데이트 파일만 두는 곳입니다.

- `latest.json`: 최신 버전 번호·알림 글·앱 코드 파일 이름·확인값(sha256)·앱 뼈대(Electron·koffi) 버전
- `app-<버전>.asar.gz`: 바뀐 앱 코드 (맥 M칩·인텔·윈도우 공통)

앱이 켜진 뒤 20초, 그리고 6시간마다 `latest.json` 을 확인합니다. 학생 자료나 판서는 여기에 올라오지 않습니다.
