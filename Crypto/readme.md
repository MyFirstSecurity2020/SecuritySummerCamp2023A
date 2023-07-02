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
### 課程說明
- 本課程將針對現代密碼學進行破密分析
- 對於古典密碼學不熟悉的同學
  - 可以參照自行學習 [MyFirstSecurity資安入門的第一堂課|古典密碼學之破密分析](https://github.com/MyFirstSecurity2020/20230301)

### 課程主題
- 1.現代密碼學
    - 柯克霍夫原則
    - 基本觀念
    - 串流加密 & 區塊加密
    - ECB & CBC & CTR & Padding
    - 金鑰
      
- 2.漏洞利用&工具使用
    - 對稱式加密
        - 分組密碼     
            - AES
                - byte-at-a-time
                - CBC-Padding-Oracle
                - CBC-IV-Detection
        - 串流密碼
            - LCG
            - LFSR
    - 非對稱式加密
        - RSA
            - 因式分解
            - 低加密指數小明文
            - 共模
            - 廣播
            - 低解密指數   
    - 雜湊
        - 彩虹表
        - 生日攻擊
        - 長度擴充攻擊
- 3.實務分析
    - 真實案例解析
    - 漏洞利用實務    


### 課程相關工具
- [Python 3.11](https://www.python.org/downloads/release/python-3111/)
- [Pwntools](http://docs.pwntools.com/en/stable/)
- [PyCryptodome](https://pycryptodome.readthedocs.io/en/latest/)
- [gmpy2](https://gmpy2.readthedocs.io/en/latest/)
- [SageMath](https://doc.sagemath.org/html/en/)

