스톰 더 하우스 2 GitHub Pages 수정본 업로드 방법

1. GitHub 저장소의 기존 파일을 전부 삭제합니다.
2. 이 ZIP을 압축 해제합니다.
3. 압축 해제된 내용물 전체를 저장소 루트에 업로드합니다.
   - index.html
   - styles.css
   - favicon.png
   - game.swf
   - assets/game.swf
   - ruffle/ 폴더 전체
   - .nojekyll
4. GitHub Pages 배포 후 Ctrl + F5로 강력 새로고침합니다.

이번 버전은 기본적으로 index.html 내부의 내장 SWF 데이터를 실행하므로 assets/game.swf 경로 문제에 의존하지 않습니다.
그래도 오류가 나면 화면 하단의 실행 상태에서 진단 복사를 눌러 내용을 전달해주세요.
