# IBM 양자 챌린지 연습문제

[IBM Quantum Challenge](http://ibm.co/quantumchallenge)의 원본입니다.

## 이 저장소에는 무엇이 있습니까?

이 저장소에는 [IBM Quantum Challenge] (http://ibm.co/quantumchallenge)의 연습문제 사본과 챌린지가 진행될 때 채울 유용한 힌트 및 실제 FAQ가 있습니다.

## 문제를 풀다가 막혔습니다. 어떻게 할까요?

문제 해결 방법에 대한 조언은 [`hints.md`] (https://github.com/qiskit-community/may4_challenge_exercises/blob/master/hints.md) 파일을 참고하세요.

## 연습 문제의 답을을 검증 할 때 오류가 발생합니다. 어떻게 해야 합니까?

연습을 검증 할 때 문제가 발생하면 다음을 시도하세요. ** 이 단계는 연습을 초기 상태로 복원하고 진행률을 삭제하므로 진행하기 전에 해답을 백업하십시오. **

1. 새 Qiskit notebook을 엽니다.
2. 새 code cell을 열고 다음을 붙여넣습니다.:

```
%pip install -I git+https://github.com/qiskit-community/may4_challenge.git@0.4.30
!git clone https://github.com/qiskit-community/may4_challenge_exercises.git ~/may4_challenge_exercises
!mkdir -p ~/may4-challenge
!cp -r ~/may4_challenge_exercises/* ~/may4-challenge
```

3. `Shift`+`Enter`로 cell을 실행합니다..
4. 연습문제 창을 다시 엽니다.

## 어디서 관련 대화를 할 수 있나요?

[Qiskit Slack] (http://qisk.it/slack)에는 챌린지 전용 채널 (`# ibm-quantum-challenge`)이 있습니다. 대화에 참여해주세요!
