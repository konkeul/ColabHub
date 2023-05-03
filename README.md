#hello
# Code Peer Review Templete
---
- 코더 : 김영원
- 리뷰어 : 박기용


# PRT(PeerReviewTemplate)
---
각 항목을 스스로 확인하고 체크하고 확인하여 작성한 코드에 적용하세요.
- [v] 1.코드가 정상적으로 동작하나요?
- [v] 2.문제를 제대로 이해했나요?
- [v] 3.함수가 작동하는 방식을 잘 설명했나요?
- [ ] 4.발생 가능한 에러를 찾아서 디버깅을 했나요?
- [ ] 5.코드를 더 개선시켰나요?

# 예시
1. 코드의 작동 방식을 주석으로 기록합니다.
2. 코드의 작동 방식에 대한 개선 방법을 주석으로 기록합니다.
3. 참고한 링크 및 ChatGPT 프롬프트 명령어가 있다면 주석으로 남겨주세요.
---
# 단어 입력후 변수에 할당
word = input("?:")
# backword 에 word에 입력된 문자열 데이터를 인덱싱을 사용해서 역순으로 정렬
backword = word[::-1]

# word , backword 출력
print(f"출력값 : {word}")
print(f"뒤집힌 단어는 : {backword}")

# word 와 backword를 비교하여 회문여부를 출력
if word == backword :
  print("입력된 단어는 회문입니다.")
else :
  print("입력된 단어는 회문이 아닙니다.")

# 참고 링크 
X
