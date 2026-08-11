# 외부 AI 작업 규칙

외부 AI/Reviewer에게 작업을 넘길 때:
1. explicit context만 제공한다.
2. relevant_files와 allowed_write_scope를 명시한다.
3. required_tests를 실제 실행하게 한다.
4. 실행하지 않은 행동을 PASS로 주장하지 못하게 한다.
5. receipt/result artifact를 요구한다.
6. Manager가 반환물을 다시 검증한다.
7. same-provider self-review를 independent review로 세지 않는다.
