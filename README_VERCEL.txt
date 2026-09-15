제일유리 Vercel 배포용 V2
======================

현재 포함된 것
- index.html
- favicon.svg
- assets/ (WebP 이미지)
- vercel.json (Vercel용 보안/캐시 헤더)
- robots.txt
- SEO_AFTER_DOMAIN.txt

다음 배포
1. 이 폴더 전체를 Vercel에 다시 업로드/배포합니다.
2. 현재 임시 *.vercel.app 주소로 기능을 다시 확인합니다.
3. 최종 도메인을 구매/연결합니다.
4. 도메인이 확정되면 SEO_AFTER_DOMAIN.txt 내용을 실제 도메인으로 반영합니다.

주의
- canonical / og:url / sitemap.xml은 아직 최종 도메인이 없어서 의도적으로 미적용 상태입니다.
