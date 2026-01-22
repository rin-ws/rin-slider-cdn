# RINslider

현대적인 웹사이트를 위해 설계된 가벼운 Vanilla JavaScript 슬라이더: 빠르고, 접근 가능하며, 의존성이 없습니다.

이 저장소는 RINslider의 **CDN용 빌드 파일**을 제공합니다.

👉 **전체 문서 및 예제:**  
[https://rinslider.com](https://rinslider.com)

---

## ✨ 주요 기능

- 🚀 순수 Vanilla JavaScript – 의존성 없음
- 📱 반응형 및 터치 지원
- 🖱️ 마우스 드래그 & 💨 관성 스크롤
- ♾️ 무한 루프
- ⏯️ 자동 재생 + 진행 바
- 🎯 도트, 화살표, 썸네일 내비게이션
- ♿ 접근성 지원 (ARIA, 키보드, 모션 감소)
- 🎭 `prefers-reduced-motion` 대응
- 🎢 중첩 슬라이더 지원
- 🌍 RTL(오른쪽-왼쪽) 완벽 지원
- 🎬 선택적 패럴랙스 효과
- 🖼️ 지연 로딩, 캡션, 슬라이드 간 간격 지원

---

## 📦 CDN 설치 (권장)

### CSS
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/DEINUSER/rin-slider-cdn@v1.0.0/rin-slider.css">
```
### JavaScript
```
<script src="https://cdn.jsdelivr.net/gh/DEINUSER/rin-slider-cdn@v1.0.0/rin-slider.min.js"></script>
```
## 🚀 빠른 시작
```
<div id="mySlider" data-slider>
  <div class="slide">슬라이드 1</div>
  <div class="slide">슬라이드 2</div>
  <div class="slide">슬라이드 3</div>
</div>

<script>
  new Slider('#mySlider', {
    infinite: true,
    autoplay: true,
    dots: true,
    arrows: true
  });
</script>
```
## 📚 문서
전체 문서에는 다음 내용이 포함됩니다:

- 설정 옵션 전체 레퍼런스

- 공개 API 메서드

- 접근성 세부 정보

- RTL, 중첩 슬라이더, 패럴랙스, 지연 로딩 지원

- 다양한 프레임워크 (React, Vue, WordPress 등)에서 사용 예제

👉 RINslider 문서
https://rinslider.com

## 🔖 버전 관리
RINslider는 **시맨틱 버전 관리(Semantic Versioning)**를 따릅니다:

- PATCH – 버그 수정

- MINOR – 하위 호환 기능 추가

- MAJOR – 하위 호환 깨지는 변경

## ❤️ 후원
RINslider는 자원봉사 오픈소스 프로젝트입니다.
유용하다고 생각하면 다음을 통해 지원할 수 있습니다:

- Patreon: https://www.patreon.com/rinslider

- Ko-fi: https://ko-fi.com/rinws

모든 기능은 무료로 제공됩니다. 후원은 선택 사항입니다.

## 📄 라이선스
MIT
