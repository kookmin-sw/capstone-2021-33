# Parallel blockchain validation with Utreexo Compact State Nodes (Utreexo Compact State Node를 사용하여 블록체인 병열검증)

![photo_2021-04-04 23 40 00](https://user-images.githubusercontent.com/37185887/113512332-19325600-959f-11eb-8c60-b0b48417158a.jpeg)

**팀페이지 주소** -> https://kookmin-sw.github.io/capstone-2021-33

**팀 repository들** -> https://github.com/mit-dci/utreexo, https://github.com/mit-dci/utcd

## 프로젝트 소개

비트코인 블록체인을 병열로 검증하는 노드를 구성하는 프로젝트이다. 블록체인의 병렬처리에 bottleneck이 되는 overhead는 
[Utreexo](https://dci.mit.edu/utreexo)라는 Data Structure로 해결할 수 있다. 이로하여 블록체인 검증을 빨리하여 우리는 블록체인의 제일 큰 문제중 하나인 확장성 문제에 좋은 영향을 끼친다.

## Abstract

We create a Bitcoin node in where the Bitcoin blockchain is validated in parallel. The overhead to parallelization is removed with Utreexo compact state nodes. This allows for a better utilization of the CPU as the need for disk access is eliminated with Utreexo Compact State Nodes. With this, we are able to verify the Bitcoin blockchain faster, allowing for on-chain scalability in Bitcoin.

### 중간 보고서

Github repo에 upload되어 있음.

### 팀 소개

#### Tadge Dryja

~~~
Bio: MIT Media Lab 소속 research scientist.
     블록체인 확장성 프로토콜인 Lightning Network 논문의 공동 저자이고
     Discreet Log Contracts라는 스마트 컨트랙트 논문의 저자이다.
     또 Tadge Dryja의 Hashimoto 알고리즘은 변형되어 Ethereum의
     채굴 알고리즘에 활용되고 있다.
Role: Maintainer
Profile: https://dci.mit.edu/thaddeus-dryja-tadge, https://github.com/adiabat
~~~

#### Niklas Goegge

~~~
Bio: Utreexo repository의 contributor이다. Mozilla의 Firefox팀에
     있고 현재는 Utreexo의 C++ 버전을 구현하고 있다.
Role: Contributor
Profile: https://github.com/dergoegge
~~~

#### 김유상/Calvin Kim

~~~
Bio: Utreexo 프로젝트의 contributor이고 비트코인 거래소, Bitmex의
     Research division에서 grant를 받아 프로젝트를 진행 및 연구결과를 기여하고 있다.
Role: Contributor
Profile: https://blog.bitmex.com/calvin-kim/, https://github.com/kcalvinalvin
~~~

### 사용법

https://github.com/mit-dci/utcd 에 있는 README를 참조.
