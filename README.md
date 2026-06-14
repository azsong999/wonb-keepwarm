# wonb-keepwarm

원비(wonb.kr) 운영 함수의 콜드스타트를 줄이기 위한 **keep-warm 핑 전용** 저장소입니다.

- 5분마다 `https://wonb.kr/api/health` 를 한 번 호출해 Vercel Fluid Compute 인스턴스를 깨어 있게 유지합니다.
- 애플리케이션 코드는 전혀 담지 않습니다. (public repo 의 GitHub Actions 무제한 무료를 활용)

워크플로: [.github/workflows/ping.yml](.github/workflows/ping.yml)
