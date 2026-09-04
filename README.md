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

4월 중순부터 다섯 달 동안 AI 코딩 도구로 6.6B 토큰을 태웠다. API 정가로 환산한 비용은 $9,664이고 실제 결제액과는 다르다. 전체 토큰의 94.6%를 캐시에서 읽었다.

툴별로는 Codex $6,990, Claude Code $2,673 순이다. Gemini는 써본 수준이다. 모델로 좁히면 gpt-5.5 하나가 $4,637으로 절반 가까이 가져간다. Claude 쪽은 claude-fable-5가 $1,132까지 올라왔다.

7월이 $3,817로 월 최고였고 8월은 $1,967로 꺾였다. 하루 최고 기록은 5월 중순의 $516이다. 최근 30일만 떼어 보면 Claude Code $1,054, Codex $901로 순서가 뒤집힌다.

#### 비용 인사이트

전체 토큰의 94.6%가 캐시 읽기였다는 점은 긴 컨텍스트를 반복해 실어 나르는 작업 패턴을 짐작하게 하지만 그 자체로 비용이 잘 통제됐다는 뜻은 아니다. [엔터프라이즈 AI 에이전트 비용 통제](https://datanexus-kr.github.io/curations/2026-09/2026-09-04-enterprise-ai-agent-llm-cost-control/)는 비용을 반복되는 기본 입력, 누적 컨텍스트, 호출 수로 나눠 따로 재라고 설명한다. 이 집계에는 호출 수와 세션 정보가 없으니 다음 기록에서는 세션당 턴 수와 캐시 기록 토큰을 함께 남겨 캐시 비중이 어느 변수에서 나오는지 확인해야겠다.

모델 단위로 보면 gpt-5.5 하나가 $4,637의 환산 비용을 차지했는데 무거운 작업을 몰아준 결과인지 단순 조회까지 같은 모델로 처리한 결과인지는 이 집계만으로 갈라낼 수 없다. [우버의 소프트웨어 팩토리 운영 전략](https://datanexus-kr.github.io/curations/2026-09/2026-09-02-efficient-software-factory-uber-scale/)은 실제 작업 기반 벤치마크로 워크로드에 맞는 모델을 고르고 서브에이전트 기본값을 따로 지정하는 방식을 소개한다. 작업 유형 태그를 붙여 기록하면 어떤 성격의 요청이 상위 모델에 몰렸는지 구분해 볼 수 있다.

최근 30일은 Claude Code $1,054, Codex $901로 앞선 다섯 달의 순서가 뒤집혔지만 어느 도구가 더 경제적이라 말하기는 어렵다. [Claude Code 토큰 사용량 측정 가이드](https://datanexus-kr.github.io/curations/2026-09/2026-09-04-claude-code-token-optimization-guide/)는 연결한 MCP 도구 정의가 매 프롬프트에 실려 기본 컨텍스트를 키운다고 짚는다. 도구를 바꾼 시점, 활성화한 MCP 목록, 세션 길이를 함께 적어두면 이 역전이 작업 이동 때문인지 설정 차이 때문인지 다음 비교에서 가려낼 수 있다.
<!-- usage-note:end -->

