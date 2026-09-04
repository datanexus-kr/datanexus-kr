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
### 사용량 노트 <sub>2026-09-05 기준</sub>

4월 중순부터 다섯 달 동안 AI 코딩 도구로 6.6B 토큰을 태웠다. API 정가로 환산한 비용은 $9,664이고 실제 결제액과는 다르다. 전체 토큰의 94.6%는 캐시에서 읽었다.

툴별로는 Codex $6,990, Claude Code $2,673 순이다. Gemini는 써본 수준이다. 모델로 좁히면 gpt-5.5 하나가 $4,637으로 절반 가까이 가져간다. Claude 쪽은 claude-fable-5가 $1,132까지 올라왔다.

7월이 $3,817로 월 최고였고 8월은 $1,967로 꺾였다. 하루 최고 기록은 5월 중순의 $516. 최근 30일만 떼어 보면 Claude Code $1,054, Codex $901로 순서가 뒤집힌다.

#### 비용 인사이트

다섯 달 누적에서 전체 토큰의 94.6%가 캐시 읽기로 잡혔다. 토큰 기준 비중이라 요청별 적중이나 절감률과는 다르고, [Claude Code 토큰 사용량 측정 가이드](https://datanexus-kr.github.io/curations/2026-09/2026-09-04-claude-code-token-optimization-guide/)가 짚듯 매 프롬프트에 실리는 도구 정의 같은 기본 입력은 이 비중 뒤에 가려지기 쉽다. 다음 기록에서는 연결해 둔 MCP 도구 수와 세션당 컨텍스트 점유를 함께 남겨, 비중이 높은데도 토큰 총량이 큰 구간을 분리해 볼 만하다.

모델 단위로 보면 gpt-5.5 하나가 환산 비용의 절반 가까이를 가져갔고 claude-fable-5는 $1,132 선에 머물렀다. 집계에 작업 난도나 호출 수가 없어 이 격차를 모델 성격 탓으로 돌리기는 어렵다. [우버의 AI 코딩 비용 안정화 전략](https://datanexus-kr.github.io/curations/2026-09/2026-09-02-efficient-software-factory-uber-scale/)처럼 세션과 턴, 요청 수로 나눠 봐야 어디서 돈이 붙는지 드러나니, 모델별로 어떤 유형의 작업을 맡겼는지 태그를 붙여 기록하는 방식을 확인할 필요가 있다.

최근 30일 구간에서는 Claude Code가 Codex보다 앞서며 누적 순서가 뒤집혔는데 도구의 경제성보다 그 기간에 무엇을 맡겼는지가 먼저 설명돼야 한다. [엔터프라이즈 AI 에이전트 비용 통제](https://datanexus-kr.github.io/curations/2026-09/2026-09-04-enterprise-ai-agent-llm-cost-control/)는 반복 입력과 누적 컨텍스트, 호출 수를 각각 따로 재라고 말한다. 전환 시점과 작업 종류를 같은 축에 올려 두면 7월 $3,817 같은 피크가 어느 변수에서 왔는지 가려낼 여지가 생긴다.
<!-- usage-note:end -->

