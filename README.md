# Joycon droid tas

# Joycon droid Tas
# 1.Tas 버튼
```
+1-시간 키 L스틱X;L스틱Y R스틱X;R스틱Y

ex : +1-5 x 0;0 0;0
ex : +1-5 n -15000;-15000 0;0
ex : +1-5 n -0;0 15000;-15000 
```
### 모든 스틱의 X , Y 는 -30000 ~ 30000까지가 범위다
### 대각선은 -15000 ~ 15000까지다.
| 스위치 키 | 그키의 텍스트 |
|--------|---|
| A | a |
| B | b |
| X | x |
| Y | y |
| L | l |
| R | r |
| ZL | zl |
| ZR | zr |
| 아무것도 안 누르는거 | n |

| 스틱 가르키는 방향 | X | Y |
|------------------|---|---|
| ⬆ | 0 | 30000 |
| ↗ | 15000 | 15000 |
| ➡ | 30000 | 0 |
| ↘ | 15000 | -15000|
| ⬇ | 0 | -30000|
| ↙ | -15000 | -15000 |
| ⬅ | -30000| 0 |
| ↖ | -15000 | 15000 |
### &nbsp;
#  2.반복

### ______번을 반복하고 싶다면
```
_____x {
 # 내용
}
```
### 이렇게 쓴다.
### &nbsp;
# 3. 주석
### TAS스크립트를 작성하다 보면 이 코드가 뭐하는 코드인지 까먹을 때가 있다.
### 그럴때를 대비해 주석을 쓴다.
```
코드코드코드코드
# ~~~~~~~~~~~~~~~~
코드코드코드코드
```
### #뒤에 오는 내용은 사용하지않는(?) 코드가 된다.
