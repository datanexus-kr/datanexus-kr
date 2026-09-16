## Hi there 👋

<!--
**datanexus-kr/datanexus-kr** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<img width="100%" src="https://raw.githubusercontent.com/datanexus-kr/datanexus-kr/main/cards/ai-usage-full.svg" alt="AI usage" />

<!-- usage-note:start -->
### 사용량 노트 <sub>2026-09-16 기준</sub>

4월 중순부터 다섯 달 동안 AI 코딩 도구로 9.2B 토큰을 태웠다. API 정가로 환산한 비용은 $13,784로 실제 결제액과는 다르다. 전체 토큰의 94.6%를 캐시에서 읽었다.

툴별로는 Codex $9,692, Claude Code $4,091 순이고 Gemini는 써본 수준이다. 모델로 좁히면 gpt-5.5 하나가 $4,860으로 가장 많이 가져간다. Claude 쪽은 claude-opus-5가 $1,371까지 올라왔다.

9월이 $4,050로 월 최고였고 8월은 $2,163로 꺾였다. 하루 최고 기록은 9월초의 $1,064이다. 최근 30일만 떼어 보면 Codex $3,167, Claude Code $1,582로 순서가 그대로다.

#### 비용 인사이트

1. 환산 비용을 작업 종류별로 나눠 기록해볼 만하다. [우버 사례](https://datanexus-kr.github.io/curations/2026-09/2026-09-02-efficient-software-factory-uber-scale/)는 세션과 주고받은 횟수, 토큰으로 쪼개 따로 잰다. 지금 집계로는 어디서 늘었는지 알기 어렵다.

2. 캐시 94.6%가 왜 이렇게 높은지 확인해볼 만하다. [토큰 최적화 가이드](https://datanexus-kr.github.io/curations/2026-09/2026-09-04-claude-code-token-optimization-guide/)는 전에 보낸 내용을 다시 쓴 토큰이 5분 안에 요청하면 싸진다고 짚는다. 짧게 몰아서 작업한 습관이 영향을 줬는지 볼 필요가 있다.

3. 모델 하나에 비용이 쏠린 구조는 나눠볼 여지가 있다. [멀티 모델 설정](https://datanexus-kr.github.io/curations/2026-08/2026-08-08-codex-multi-model-agent-cost-optimization/)은 설계를 메인 모델에 맡기고 조사와 구현은 가벼운 모델에 넘기는 분담을 제안한다.
<!-- usage-note:end -->

