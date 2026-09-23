# 거지 탈출 RPG

Streamlit 기반 9:16 클릭형 RPG 게임

## 실행

```bash
pip install -r requirements.txt
streamlit run main.py
```

## v15 업데이트

- 농사와 아파트 스테이지에서도 상점 버튼이 항상 오른쪽 아래에 표시되도록 수정
- 상점에 가위바위보 추가
- 1판: 900만원 베팅, 승리 시 1억 8천만원 지급
- 패배 시 베팅금 손실
- 무승부 시 종료하거나 900만원을 추가해 총 1,800만원 베팅으로 2판 진행
- 2판 승리 시 3억 6천만원 지급
- 2판 패배 시 추가 베팅금까지 포함해 총 1,800만원 손실
- 가위바위보 화면은 바위/보/가위 선택 방식


## 배경 파일 오류 방지
`main.py`에 5개 스테이지 배경을 기본 내장해 Streamlit Cloud에 `main.py`만 업로드해도 FileNotFoundError 없이 실행됩니다. `assets/stage1.jpg`~`stage5.jpg`가 있으면 해당 파일을 우선 사용합니다.
