# 비트코인, 공개 블록체인 프로그래밍

해당 내용은 [《Mastering Bitcoin》](https://www.oreilly.com/library/view/mastering-bitcoin-2nd/9781491954379/)에 의해 작성

[github site : Organize by english](https://github.com/bitcoinbook/bitcoinbook)



**저작권(Copyright)**

Mastering Bitcoin by Andreas M. Antonopoulos(O'Reilly)'. &copy;2017 Andreas M. Antonopoulos, 978-1-491-95438-6





### 용어 설명



##### 주소(address)

비트코인의 주소 형태는 1(number one)로 시작하는 여러 개의 문자와 숫자의 조합으로 이루어져 있다. 상대방에게 (나의 비트코인 주소로) 비트코인을 보내 달라고 요청 가능



##### 비트고인 개선 제안(bip)

BIP(Bitcoin Improvement Proposals), 비트코인 커뮤니티 회원들이 비트코인을 개선하기 위해 내놓은 일련의 제안.



##### 비트코인(bitcoin)

화폐 단위(currency unit, coin), 해당 네트어크 및 SW의 이름.



##### 블록(block)

거래의 집합, Timestamp와 함께 이전 블록의 지문(fingerprint)이 표시되어 있다. 블록 헤더를 요약해서 작업증명(proof-of-work)을 만들고 이를 통해 거래가 유효화된다. 유효화된 블록은 네트워크의 동의(consensus)를 얻은 후 메인 블록체인에 추가된다.



##### 블록체인(blochain)

유효화된 블록의 집합(list)으로, 이전에 생성된 블록체인과 연결되어 최초 블록(genesis block)까지 이어진다.