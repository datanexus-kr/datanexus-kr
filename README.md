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
### 사용량 노트 <sub>2026-09-15 기준</sub>

4월 중순부터 다섯 달 동안 AI 코딩 도구로 8.7B 토큰을 태웠다. API 정가로 환산한 비용은 $12,555로 실제 결제액과는 다르다. 전체 토큰의 94.6%를 캐시에서 읽었다.

툴별로는 Codex $9,027, Claude Code $3,527 순이고 Gemini는 써본 수준이다. 모델로 좁히면 gpt-5.5 하나가 $4,794으로 가장 많이 가져간다. Claude 쪽은 claude-opus-5가 $1,357까지 올라왔다.

7월이 $3,817로 월 최고였고 8월은 $1,967로 꺾였다. 하루 최고 기록은 9월초의 $1,049이다. 최근 30일만 떼어 보면 Codex $2,605, Claude Code $1,083로 순서가 그대로다.

#### 비용 인사이트

1. 작업별로 모델을 나눠 쓸 수 있다. [우버 사례](https://datanexus-kr.github.io/curations/2026-09/2026-09-02-efficient-software-factory-uber-scale/)는 실제 작업으로 성능과 비용을 비교해 가벼운 작업에 가벼운 모델을 기본값으로 둔다. 내 기록에도 작업 종류를 남기면 같은 비교를 해볼 수 있다.

2. 같은 내용을 얼마나 다시 보내는지 볼 필요가 있다. [에이전트 비용 글](https://datanexus-kr.github.io/curations/2026-09/2026-09-04-enterprise-ai-agent-llm-cost-control/)은 매 호출마다 들어가는 기본 입력과 쌓인 대화를 따로 재보라고 짚는다. 캐시 읽기 94.6%는 전체 비율이지 호출별 절감률은 아니다.

3. 연결해둔 도구도 입력을 늘린다. [Claude Code 가이드](https://datanexus-kr.github.io/curations/2026-09/2026-09-04-claude-code-token-optimization-guide/)는 도구 설명이 매 프롬프트에 같이 실린다고 알려준다. 안 쓰는 연결이 켜져 있는지 점검해볼 만하다.
<!-- usage-note:end -->

