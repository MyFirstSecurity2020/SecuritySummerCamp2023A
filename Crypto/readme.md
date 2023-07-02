# Crypto 密碼學

## 袁律恆/Crypto 密碼學
### 課程說明
- 本課程將包括針對以下主題的攻擊技巧分析
  - 對稱密碼
  - 偽隨機數
  - 雜湊
  - 非對稱密碼

### 先備知識
- 編碼與解碼 & 古典密碼學
  - 若不熟悉可以參照 [MyFirstSecurity資安入門的第一堂課](https://github.com/MyFirstSecurity2020/20230301) 自行學習
- Python & Pwntools
  - 若不熟悉可以參照 [Python程式與資安應用入門](https://github.com/MyFirstSecurity2020/SF2023A3)

### 課程主題
- 對稱密碼
  - AES Block Cipher Mode 介紹
    - AES ECB Mode
    - AES CBC Mode
  - 攻擊技巧分析
    - AES ECB Mode : Cut & Paste
    - AES CBC Mode : Padding Oracle Attack
- 偽隨機數
  - LCG
  - MT19937
- 雜湊
  - Length Extension Attack
- 非對稱密碼
  - RSA 介紹
  - RSA 攻擊技巧分析
    - Fermat Factorization
    - Pollard's p - 1 Algorithm
    - Broadcast Attack
    - Common Modulus Attack
    - Wiener's Attack & Coppersmith's Attack 簡介

### 課程相關工具
- [Pwntools](http://docs.pwntools.com/en/stable/)
- [PyCryptodome](https://pycryptodome.readthedocs.io/en/latest/)
- [gmpy2](https://gmpy2.readthedocs.io/en/latest/)
- [SageMath](https://doc.sagemath.org/html/en/)

---

## 周佑康/Crypto 密碼學
### 課程說明(請講師自行修改)
- 本課程將針對現代密碼學進行破密分析
- 對於古典密碼學不熟悉的同學
  - 可以參加 SecurityFoscusOnline2023課程
  - 可以參照自行學習 [MyFirstSecurity資安入門的第一堂課|古典密碼學之破密分析](https://github.com/MyFirstSecurity2020/20230301)

###  課程主題(請講師自行修改)
- 密碼基本觀念
- 現代密碼學之`非對稱式密碼Asymmetric encryption(公開金鑰 Public-key cryptography)`
  - 非對稱式密碼(公開金鑰)
  - RSA 非對稱式密碼(公開金鑰)
  - RSA 非對稱式密碼攻擊技法(有太多攻擊模式,底下針對比較好學部分)
    - 延伸閱讀 [Twenty Years of Attacks on the RSA Cryptosystem](https://crypto.stanford.edu/~dabo/pubs/papers/RSA-survey.pdf) 
    - SMALL N ATTACK(n太小 == >容易被質因數分解)
    - Twin Primes attack
    - Common Modulus Attacks
    - Wiener's Attack
    - Coppersmith's attack
    - ..........
- 現代密碼學之`對稱式密碼Symmetric encryption`(如果太深可以不講此部分)
  - Block Ciphers VS  Stream Ciphers
  - Padding:ECB(Electronic codebook)Mode|CBC(Cipher-block chaining)Mode|.... 
  - 對稱式密碼攻擊技法
    - Padding Oracle attack(CBC 位元反轉攻擊)| bit-flipping attack 
    - Cut and paste attack
- 現代密碼學之HASH
  - HASH攻擊技法
  - Collision attack
  - 長度擴充攻擊 | Length Extension Attack (LEA)
  - 使用Hashpump

### 破密分析常用工具(Tools)(請講師自行修改)
- Pwntools - Python’s Wonderful Networking Tool
- cytro - A CTF cryptography solving tool
- yafu - A factorization tool
- libnum - Number theory
- [sympy - A library for symbolic mathematics.](https://www.sympy.org/en/index.html)
- gmpy2 - Multiple-precision arithmetic & number theory
- Factordb - A large database of factor
- SageMath / CoCalc - Computer algebra system
- pyCrypto / cryptography - Crypto algorithms
