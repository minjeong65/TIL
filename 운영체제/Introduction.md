# Introduction

### 운영체제 분류

**동시 작업 가능 여부**

* 단일 작업 : 한번에 한 작업만 가능(MS-Dos)
* 다중 작업 : 동시에 두 개 이상의 작업 가능(UNIX, MS Windows)

</br>

**사용자수**

* 단일 사용자 : MS-Dos, MS Windows

* 다중 사용자 : UNIX

 </br>

**처리 방식**

* 실시간
  * Hard realtime system : 미사일 제어, 반도체 장비 등 시간에 매우 예민한 작업
  * Soft realtime system : 큰 문제를 초래하지는 않지만 deadline은 있는 작업
* 시분할(Time Sharing System)
  * 사용자와 interactive하게 작업함
  * 각 사용자들에게 컴퓨터 자원을 시간적으로 분할하여 사용할 수 있게 해줌
* 일괄처리(batch processing)
  * 초기의 컴퓨터 시스템 방식
  * 일정량 또는 일정 기간 동안 데이터를 모아서 한꺼번에 처리하는 방식

</br>

</br>

### 용어정리

**Multi tasking**

하나의 프로그램이 끝나기 전에 다른 프로그램을 실행시킬 수 있는 것(여러 작업을 동시에 수행)

**Multi programming**

메모리에 여러 프로그램이 올라가는 것(멀티태스킹의 메모리 측면 강조)

**Time sharing**

CPU의 시간을 분할해서 나누어 쓰는 것(멀티태스킹의 CPU 측면을 강조)

**(cf) Multi processor** 

하나의 컴퓨터에 여러 CPU가 붙어 있는 것

</br>

</br>

### 운영체제 종류

**유닉스**

- 대부분 C언어로 작성(유닉스를 만들기 위해 C언어를 만듦)
- 높은 이식성(portability) : 다른 컴퓨터에 쉽게 적용 가능
- 커널의 크기가 매우 작음 : 핵심적인 것만 커널에 넣음
- 복잡한 시스템에 맞게 확장이 용이
- 소스코드 공개 
- 프로그램 개발에 용이
- 다양한 버전 ex) Linux

​    </br>

**DOS(Disk Operating System)**

- 단일 사용자용 운영체제
- 메모리 관리 능력의 한계 – 주기억장치 : 640KB

​    </br>

**MS Windows**

- 다중 작업용 GUI 기반 운영체제
- Plug and Play, 네트워크 환경 강화
- DOS용 응용 프로그램과 호환성 제공
