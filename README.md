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

툴별로는 Codex $9,683, Claude Code $4,100 순이고 Gemini는 써본 수준이다. 모델로 좁히면 gpt-5.5 하나가 $4,857으로 가장 많이 가져간다. Claude 쪽은 claude-opus-5가 $1,369까지 올라왔다.

9월이 $4,050로 월 최고였고 8월은 $2,163로 꺾였다. 하루 최고 기록은 9월초의 $1,064이다. 최근 30일만 떼어 보면 Codex $3,158, Claude Code $1,591로 순서가 그대로다.

#### 비용 인사이트

1. 비용이 어디서 생기는지 쪼개 볼 만하다. [우버 사례](https://datanexus-kr.github.io/curations/2026-09/2026-09-02-efficient-software-factory-uber-scale/)는 세션 수와 대화를 주고받은 횟수, 토큰을 따로 재서 원인을 찾는다. 내 기록에는 토큰과 환산 비용만 있어 같은 분해는 어렵다.

2. 캐시가 94.6%라고 그만큼 싸지는 건 아니다. 캐시 읽기는 전에 보낸 내용을 다시 쓴 토큰이다. [토큰 측정 가이드](https://datanexus-kr.github.io/curations/2026-09/2026-09-04-claude-code-token-optimization-guide/)는 5분 안에 다시 요청할 때 싸진다고 짚는다.

3. 켜둔 도구가 입력을 늘렸는지 볼 만하다. 도구 설명은 호출할 때마다 모델에 함께 보내는 정보에 다시 실린다. [에이전트 비용 글](https://datanexus-kr.github.io/curations/2026-09/2026-09-04-enterprise-ai-agent-llm-cost-control/)이 짚는 대목이다.
<!-- usage-note:end -->

