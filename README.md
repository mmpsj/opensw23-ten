# opensw23-ten
Text-To-Speech project
## Team Introduction
  김영준 : 201911162 리더  
  박상준 : 201911173 코더  
  신민석 : 202011316 github expert  
  김수형 : 202211276 발표자  
## Topic Introduction
### References
## Topic Introduction
https://github.com/fatchord/WaveRNN  
저희가 선택한 오픈소스는 TTS입니다.  
TTS(Text to Speech)는 '음성합성'으로 일정한 음성 단위로 분할한 후 입력받은 텍스트를 따라 필요한 음성단위들을 이어 붙여 말소리를 인위적으로 만들어 내는 기술입니다.  
python quick_start.py -u --input_text "샘플 텍스트" 커맨드를 사용해 사용자가 입력한 샘플 텍스트를 음성으로 바꿔줍니다.  
자신만의 모델을 트레이닝 시킬 수 있습니다.  
샘플데이터를 사용한 Result는 아래와 같습니다.  
## Results
https://opensw23-ten.github.io/sample/
## Analysis/Visualization

## Installation  
요구 사항 :  
Python 버전 3.6 이상, 3.8 이하  
Pytorch 1(1.0.0) 이상 with CUDA (<https://pytorch.org/get-started/previous-versions/> 참고)  
pip를 이용하여 나머지 모듈 설치 : pip install -r requirements.txt  

### Quick Start  
python quick_start.py -u --input_text "input"을 실행합니다. 이때 "input"에는 원하는 문자열을 넣을 수 있습니다.  


input 1 : Hello my name is konkuk.  
input 2 : We are opensource software team ten.  
input 3 : Are you Konkuk university student?  
input 4 : You look nice today!  
input 5 : hello, we are majoring computer science.  
input 6 : 안녕하세요! 저희 팀 이름은 TEN입니다!  

## Presentation
