---
layout: default
title: "벡터 미적분학: 발산 정리 (Divergence Theorem)"
---

이 글은 GitHub Pages의 마크다운 변환 테스트를 위한 문서입니다.

## 1. 발산 정리의 개념
발산 정리는 벡터장의 유량(Flux)과 그 발산(Divergence) 사이의 관계를 나타내는 아주 중요한 정리입니다. 닫힌 곡면을 통과하는 총 유량은 그 곡면이 둘러싼 부피 안에서 발생하는 벡터장의 발산의 총합과 같습니다.[^1]

$$\iint_{\partial V} \mathbf{F} \cdot d\mathbf{S} = \iiint_{V} (\nabla \cdot \mathbf{F}) \, dV$$

### 1.1 직관적 의미
* **좌변:** 표면 $\partial V$를 뚫고 나가는 벡터장 $\mathbf{F}$의 알짜 유량
* **우변:** 공간 $V$ 내부의 각 점에서 퍼져나가는 '발산'의 정도를 다 더한 것

## 2. 코드 블록 테스트
이 기능은 나중에 커스텀 에디터를 만들 때 요긴하게 쓰입니다.
```javascript
function calculateDivergence(vectorField) {
  console.log("발산 계산 완료");
  return true;
}
