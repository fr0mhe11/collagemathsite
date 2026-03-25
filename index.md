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
이 기능은 나중에 커스텀 에디터를 만들 때 요긴하게 쓰입니다.[^2]
```javascript
function calculateDivergence(vectorField) {
  console.log("발산 계산 완료");
  return true;
}
```

## 333333
ㄴㅁㅇㄴㅁㅇㄴㅇㅁㄴㅇㄴㅇㄴㅇㄴㅇㄴㅁㅇㄴ[^3]
## ㄴㅇㄴㅁㅇㄴ
ㄴㅇㄴㅇㄴㅇㄴㅇㄴㅇㄴ
## ㄴㅁㅇ

$$\begin{align*}
&\mathbb{N}  = \{ 1,2,3, \dots\}   \\
&\mathbb{Z} = \{ -3,-2,-1 , 0 ,1,2,3, \dots \} \\ 
& \mathbb{Q} = \left\{   \frac{n}{m} ~|~ n,m \in \mathbb{Z} , m \neq 0   \right \} \\
\frac{\frac{\frac{\int}{\int_{\int}}}{\int \sum^{\int}_{ssss}}}{\int}
\\ \frac{\int}{\int}
\\ \int 
\\ \int
\\ \int
\end{align*}$$

## ㅇㄴㅇㄴㅇㄴㅇ
ㄴㅇㄴㅇㄴㅇㅁㄴㅇ
ㄴㅇㄴㅇㄴㅇㄴㅇㄴㅇ

$$
\sum=\sum=f(x + h) = f(x) + f'(x)h + f''(x) \frac{h^{2}}{2!} + \dots
= f(x + h) = f(x) + f'(x)h + f''(x) \frac{h^{2}}{2!} + \dots
f(x + h) = f(x) + f'(x)h + f''(x) \frac{h^{2}}{2!} + \dots
= f(x + h) = f(x) + f'(x)h + f''(x) \frac{h^{2}}{2!} + \dots
$$


[^1]: 이 정리는 가우스의 정리(Gauss's Theorem)라고도 불리며, 전자기학에서 가우스 법칙을 적분형에서 미분형으로 변환할 때 필수적으로 사용됩니다.

[^2]: 긴 그거 $$\sum=
\sum=\sum=
f(x + h) = f(x) + f'(x)h + f''(x) \frac{h^{2}}{2!} + \dots
= f(x + h) = f(x) + f'(x)h + f''(x) \frac{h^{2}}{2!} + \dots$$
[^3]: short $\sum^{a}_{b}$
