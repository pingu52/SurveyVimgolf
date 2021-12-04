# Vim
![vim-shortkey-keyboard (1)](https://user-images.githubusercontent.com/81621996/144721284-31e2d36c-759d-47e7-a050-d19fbf8fbbc7.jpg)
<br><br>
<br><br>
<br><br>


## 1번 풀이과정
![vimgolf 1번](https://user-images.githubusercontent.com/81621996/144721849-b0d74511-b1b1-4211-8291-54756371b0c3.gif)
+ 타이핑 순서 : `` GWi"<End>"<Esc>ZZ ``
+ ### 점수 : 9
+ G 제일 마지막 줄로 이동 > W 다음단어로 이동 > i 커서 앞에 삽입(입력) > " 타이핑 > End키로 줄 끝 이동 > " 타이핑 > ZZ로 저장 후 나가기
<br><br>
<br><br>
<br><br>

[shift + g] 
## 2번 풀이과정
![vimgolf 2번](https://user-images.githubusercontent.com/81621996/144721873-ebd717c0-f2e4-4cd1-810c-7fccd953fc88.gif)
+ 타이핑 순서 : `` :%s/sublime\|emacs/vim/g<CR>ZZ ``
+ ### 점수 : 27
+ %s 문법과 파이프라인 사용으로 sublime과 emacs 단어의 vim 치환 후 저장 후 나가기 
<br><br>
<br><br>
<br><br>

## 3번 풀이과정
![vimgolf 3번](https://user-images.githubusercontent.com/81621996/144721882-27294eb6-ed4d-49d1-bc73-15158cda1df5.gif)
+ 타이핑 순서 : `` 3jO// V<C-X><C-N> TODO<Esc>jo// D<C-X><C-N> T<C-X><C-N><Esc>ZZ ``
+ ### 점수 : 30
+ 커서에서 3줄 밑으로 간 후 커서에서 윗 줄 삽입(입력) ``// V`` 타이핑 후 비주얼라인 진입 후 V로 시작하는 단어 Version 가져오고 ``TODO`` 타이핑을 한 후 입력모드 나가기 한 줄 밑으로 내려간 후 한 줄 밑 삽입(입력) ``// D``타이핑 후 D로 시작하는 단어 가져오고 한 칸 타이핑 후 방금 쓴 T로 시작하는 TODO 가져온 후 입력모드 나가고 저장 후 나가기 
<br><br>
<br><br>
<br><br>

## 4번 풀이과정 
![vimgolf 4번](https://user-images.githubusercontent.com/81621996/144721891-5b76d594-b265-4177-b9c4-aa8d8d135047.gif)
+ 타이핑 순서 : `` :%s/y1/abs(y1)/g<CR>12wrgkrrkrb:3s/1/2/g<CR>:4s/1/3/g<CR>:5s/1/4/g<CR>ZZ ``
+ ### 점수 : 60
+ %s 문법으로 이 페이지 모든 라인 y1을 abs(y1)으로 치환하고 제일 끝 줄 커서를 12번째 단어로 이동 후 r + [치환 할 글자 하나]사용하여 한 줄씩 올라가며 치환 해주고 한번 더 s문법 사용하여 각자 줄의 1을 변경해야할 숫자로 변경 후 저장 후 나가기
+ 최소 스코어가 34점 저 숫자를 일제히 1,2,3,4로 치환하면 더 줄일 수 있을 것 같은데 거기까지 생각이 닿지 않음..
<br><br>
<br><br>
<br><br>

## 5번 풀이과정
![vimgolf 5번](https://user-images.githubusercontent.com/81621996/144721896-0925688e-5a51-448c-b192-28e208ef8ff4.gif)
+ 타이핑 순서 : `` /"<CR>ast<C-N><C-N>,na<C-N>,ag<C-N>,sc<C-N><Esc>ZZ ``
+ ### 점수 : 23
+ "를 찾아가서 커서 앞 입력후 st타이핑하고 student_id를 찾기위해 N 사용 ,타이핑 후 같은 방법으로 타이핑 쭉 한 후 입력모드 나가고 저장후 나가기 
