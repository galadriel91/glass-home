제일유리 배포용 V1
==================

구성
- index.html
- favicon.svg
- assets/
  - glass-building-v1.webp
  - glass-interior-v1.webp
  - screen-window-v1.webp
- _headers

이번 배포용 정리에서 한 작업
1. HTML 안에 Base64로 들어 있던 이미지들을 실제 WebP 파일로 분리
2. 중복 이미지는 같은 파일을 재사용하도록 정리
3. 히어로 이미지를 preload하도록 설정
4. 브라우저 theme-color 추가
5. Netlify용 기본 보안/캐시 헤더(_headers) 추가
6. 최종 도메인이 아직 없으므로 canonical / Open Graph URL / sitemap / robots는 아직 추가하지 않음

Netlify 테스트 배포 방법
1. 이 ZIP 파일을 압축 해제합니다.
2. Netlify에 로그인합니다.
3. Add new project 또는 Deploy manually / Drag and drop 영역으로 이동합니다.
4. 압축을 푼 'jeilglass_deploy_v1' 폴더 전체를 드래그합니다.
5. 배포가 끝나면 *.netlify.app 임시 주소가 생성됩니다.
6. 생성된 주소를 휴대폰에서 열어 전화, 네이버 지도, FAQ, 고정 헤더를 확인합니다.

주의
- index.html만 따로 올리지 말고 폴더 전체를 올려야 이미지와 favicon이 정상 표시됩니다.
- 실제 도메인은 테스트 배포 확인 후 연결하는 것을 권장합니다.
