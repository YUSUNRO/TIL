# 반복문

## 증감
```java
// A부터 B까지 증가
for(int i=A; i<=B; i++)

// A부터 B까지 C씩 증가
for(int i=A; i<=B; i+=C)

// A부터 B까지 감소
for(int i=A; i>=B; i--)
```
```java
// 1, 2, 3, 4, 5
for(int i=1; i<=5; i++)

// 5, 10, 15, 20
for(int i=5; i<=20; i+=5)

// 4, 7, 10, 13, 16, 19
for(int i=4; i<=19; i+=3)

// 10, 8, 6, 4
for(int i=10; i>=4; i-=2)

// 3, 1, -1
for(int i=3; i>=-1; i-=2)
```
## 합산
```java
// 1~N 의 합
int sum = 0;
for(int i=1; i<=N; i++) {
  sum += i;
}
```

## count 변수 사용 안하고, 단순 반복 실행
```java
// N번 반복
for(int i=0; i<N; i++) {
  System.out.print("*");
}
```

## 이중 for문
```java
/*
*
**
***
****
*****
*/
for(int i=1; i<=5; i++) { // i: 1~5 (증감 용도의 for문)
  for(int j=0; j<i; j++) { // i번 반복실행 (j 변수 사용안했고, 단순반복 용도로 사용된 for문)
    System.out.print("*");
  }
  System.out.println();
}
```
