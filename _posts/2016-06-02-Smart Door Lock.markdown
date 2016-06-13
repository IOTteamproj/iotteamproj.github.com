---
layout: post
title:  "Smart Door Lock"
date:   2016-06-02 15:22:09 +0900

---


# Term Project



## 1. 문제정의



### 1.1	필요성 및 문제분석



늘어나는 1인 가구와 이에 비례하여 늘어나는 강력 범죄에 따라, 방범에 대한 관심 또한 높아지고 있다. 디지털 도어락은 이제 가정의 필수품이 되어가고 있으며 특히, 신규 건설되는 아파트는 디지털 도어락이 기본으로 설치되는 추세이다. 하지만 기존 디지털 도어락은 몇 가지 문제점이 있다.

	> 1) 낡은 버튼이나 지문 자국을 통해 비밀번호를 유추하거나, 최근에는 몰래카메라를 이용하여 비밀번호를 알아내어 범죄를 일으키는 사건이 잦아지는 등 외부 침입에 취약해진다.

	> 2) 손에 짐이 많거나, 주변에 사람이 있을 경우 주의하여 비밀번호를 치려면 번거로워진다는 문제점이 있다. 이러한 문제점을 해결하기 위해 기존 NFC를 이용하여 스마트폰을 이용하여 문의 잠금을 해제하는 제품이 나와있으나, 이는 사용자가 도어락에 직접 스마트폰을 가져다 대야 하는 방식이다.

	> 3) 집이 부재중일 시 지인을 초대하면, 비밀번호를 직접 알려주는 방식을 택했을 때 비밀번호를 매번 교체해주어야만 하는 번거로움이 생긴다. 이러한 불편함은 요즘 여행자들 사이에서 성행하고 있는 Airbnb에서도 또한 나타난다.




### 1.2 목적 및 요구사항 도출



	> 1) 기존의 버튼 방식이 아닌 새로운 방식으로 도어락의 잠금 해제가 가능해야 한다.

	> 2) 잠금 해제를 위해 이루어졌던 기존의 일련의 방법과 절차들을 단순화해야한다.

	> 3) 방범용으로써의 역할을 하고 보안성를 높이기 위해 동영상과 사진 촬영이 가능해야한다.

	> 4) 다른 사람에게 도어락을 개폐할 수 있는 권한을 부여할 수 있어야 한다.

	> 5) 이 외에도 Application을 이용한 관리가 수월해야한다.




## 2. 해결방안 및 유사 사례



### 2-1. 핵심 아이디어



	> 1) Bluetooth와 Wifi 기능을 탑재하여 원거리에서도 도어락의 개폐가 가능하다.

	> 2) 도어락에 카메라를 추가하여 방문객이 방문하였을 경우나, 신원이 확인되지 않은 사람이 문 앞에 서성거릴 때 사진과 동영상을 촬영하여 실시간으로 관리자의 Application에 전송한다.

	> 3) 신원이 확인된 방문객일 경우, 방문객의 출입이 허용 가능해진다.

	> 4) 본인의 집에 방문자가 찾아오기로 한 경우 관리자가 방문객에게 초대장을 보내 그 방문자가 도어락을 작동시킬 수 있는 Bluetooth권한을 1회 부여한다.

	> 5) 권한을 부여받지 않은 Bluetooth를 이용하여 임의로 도어락 개폐를 시도할 시 도어락의 기능이 정지되며 관리자의 Application을 통해서만 정지된 기능을 다시 활성화 가능하다.

	> 6) 관리자가 오랜기간동안 집을 비울 경우를 대비해, Application을 통해 수동으로 도어락 전원을 끌 수 있는 기능이 있다.

	> 7) Application을 통해 도어락의 배터리 상태를 확인할 수 있고, 배터리가 방전될 경우 외부 전원을 통해 일시적으로 도어락 사용 가능해진다.




### 2-2. 유사사례



![](http://www.samsungsds-nss.com/ko/solution/country/ddl/img/SHS-h511_001.jpg)

이 제품은 삼성SDS 삼성 스마트 도어록 ‘SHS-H511‘라는 제품으로 현재 가장 인기있는 도어락 모델 중 하나이다. 기존 비밀번호만을 입력하는 도어락에 비해 삼성 스마트 도어락은 비밀번호를 입력하는 것 뿐만 아니라 핸드폰의 NFC 기능을 사용하여 손쉽게 문을 열 수 있다. 등록된 NFC 기능을 활성화하여 도어락 근처에 핸드폰을 가져다 대면 문이 열리도록 동작하는 방식으로 편의성에 조금 더 초점을 둔 제품이라고 할 수 있다.

	> 1) 삼성SDS 삼성 스마트 도어락 ‘SHS-H511'

	> 2) 기존 비밀번호만을 입력하는 도어락의 기능에 핸드폰의 NFC 기능을 추가

	> 3) 등록된 NFC 기능을 활성화 하여 도어락 근처에 핸드폰을 가져다 대면 도어락이 동작

### 2-3. 기존 제품과의 차별성 및 장점



	> 1) 기존의 도어락은 비밀번호를 입력하거나, 카드키를 가져다 대거나, NFC가 활성화된 휴대폰을 도어락에 가져다 대는 등 사용자가 잠금을 해제하기 위해 상응하는 행동을 해야만 문이 열렸다. 이러한 원래의 잠금 방법과는 달리, Smart Door Lock은 도어락 가까이에 접근하기만 하면 문이 자동으로 열림으로써 사용자는 단순히 문에 다가가는 것 만으로 잠금을 해제할 수 있다.

![](https://lh3.googleusercontent.com/-AMFr2D8wkHg/V1h4OalYtVI/AAAAAAABPIo/eYgv6-mZYNQA5gH6gwDBMU1KiWWCQx3UwCL0B/w475-h577-no/%25EA%25B7%25B8%25EB%25A6%25BC1.jpg)

	> 2) 기존 제품과는 달리 Bluetooth와Wifi 기능을 탑재하여 원거리에서도 도어락의 개폐가 가능하며, 초대장 기능을 탑재하여 방문자가 찾아오기로 한 경우 방문자에게 1회용 잠금 해제 권한 일임이 가능케 한다거나, 방문객의 사진과 동영상을 Application으로 실시간으로 확인할 수 있게 하는 등의 기능이 추가되어 더욱 편리하고 안전한 이용을 할 수 있도록 한다.

![](https://lh6.googleusercontent.com/-P16ObHS8vZU/V1h4OqIZkCI/AAAAAAABPIo/rWjKIBYIwDYWtIqGLDT1So-xFOH1aHLAACL0B/w559-h577-no/%25EA%25B7%25B8%25EB%25A6%25BC2.jpg)





## 3. 시스템 설계



### 3-1. 시스템 구조



![](https://lh3.googleusercontent.com/-6IghTG_ewgk/V1QJeQCv80I/AAAAAAAAAA0/RnNwYVdpsiAlPFQ1_eBkuW8yIYeSJwVEwCL0B/w953-h491-no/%25EA%25B5%25AC%25EC%25A1%25B0.png)

도어락과 사용자의 어플리케이션을 Wifi와 Bluetooth를 이용하여 상호작용한다. Bluetooth를 통해서 도어락에 사용자 인식 기능을 활용하고 Wifi를 통해서 도어락에 내장된 카메라가 보내주는 사진과 영상을 사용자의 어플리케이션으로 전송해준다.





### 3-2. 시스템 기능



1) 사용자가 도어락에 접근 시 도어락의 자동 개폐

	> Bluetooth를 기반으로 하여 도어락에 접근이 허용된 사용자가 도어락 근처에 접근할 경우 자동으로 도어락이 열린다.

2) 도어락에 카메라를 장착하여 보안 기능 강화

	> 도어락에 내장된 카메라가 항시 작동하여 카메라에 인식되는 사람이 있을 경우 그 장면을 촬영하고 촬영된 사진과 동영상을 Wifi를 통해 사용자의 어플리케이션으로 전송한다.

3) 초대장 기능

	> 본인의 집에 방문자가 찾아오기로 한 경우 관리자가 방문객에게 초대장을 보내 그 방문자가 도어락을 작동시킬 수 있는 Bluetooth권한을 1회 부여한다.

4) 도어락의 자동, 수동 Shutdown 기능

	> 권한을 부여받지 않은 Bluetooth를 이용하여 임의로 도어락 개폐를 시도할 시 도어락의 기능이 정지되며 관리자의 Application을 통해서만 정지된 기능을 다시 활성화 가능하다. 또한, 관리자가 오랜기간동안 집을 비울 경우를 대비하여 Application을 통해 수동으로 도어락 전원을 끌 수 있는 기능이 있다.





### 3-3. 기능에 대한 모듈



1) 사용자 추가 모듈

![](https://lh3.googleusercontent.com/2tp0GNbkY-YKcTTP7KzLXiKmOhmLUmxW_wts0qOAbcQzxrN80rviZrsy0pKTITAxFB6QDA=s165)



2) 사용자 제거 모듈

![](https://lh3.googleusercontent.com/odDMqOH5ZnDMPrmaXk9mjhKWvuNivdHlL7zeBMR_mXxtz3PmLSB68tcc0c1EmKHdyaHn1sM=s170)


3) 사용자 인식 모듈

![](https://lh3.googleusercontent.com/C5LZyCz8pU0MgsOXPu3vdQIGBDVuMm_n05HsD3gFJFItIFGWOtrn9q8bpc7-DM0-aNiC4Q=s170)


4) 보안영상 저장 모듈

![](https://lh3.googleusercontent.com/KhMjHKXN_KccQr8HrhCV5QWSbxc9ZRfW_2SGgL1GWUJZvmpUglxvHlRggAsr53qsJSgc1Jc=s170)


5) 보안영상 관리 모듈

![](https://lh3.googleusercontent.com/Ya50KNaaZ_VvgQeDjEKeQ4qCpTR5MikY7j485ImpR1LR7ywvs6nTlBLO_9UsMZJJSchmxQ=s156)


6) 초대 모듈

![](https://lh3.googleusercontent.com/a1swsRN1xyAGHIa_ILhqCCzH1AwHgQZt_68Zg59OvZHVuXc49Nag2Td53gJmVWuk1izLZQ=s170)


7) 도어락 잠금 모듈

![](https://lh3.googleusercontent.com/x7bSv_N-WYYO0C311nsj541Kxxvw0HGgse27O0q1qa-nDzKh5bgpOHnHdGTFeexgEu_yRg=s170)





### 3-4. 구성요소 간 동작흐름


1) 도어락 개폐 기능

![](https://lh4.googleusercontent.com/-qlgnPDx52I0/V1u6n-PXMEI/AAAAAAAAACI/I1xu4wja4FElrv8DmIrPwf7G35329bnfgCL0B/w622-h235-no/%25EA%25B7%25B8%25EB%25A6%25BC1.png)



2) 카메라 보안 기능

![](https://lh3.googleusercontent.com/-n2QLAn2Ssu0/V1vCiSwJbTI/AAAAAAAAADg/pwsh290Bance4acFPV3FmmMQ7Drmn9rogCL0B/w621-h277-no/%25EA%25B7%25B8%25EB%25A6%25BC2.png)



3) 초대장 기능

![](https://lh4.googleusercontent.com/-wM3Yz2yfOpw/V1vE_yFDotI/AAAAAAAAAFM/y3R2vPeSGgQyDH59kJjaPFmN181E38jxQCL0B/w621-h201-no/%25EA%25B7%25B8%25EB%25A6%25BC3.png)



4) 도어락 shutdown 기능

![](https://lh5.googleusercontent.com/-jHzHjDao1as/V1u7RuYZSVI/AAAAAAAAACw/svWtqyRSZrEeg6AW7cmQor2e3f9bfdnPgCL0B/w622-h292-no/%25EA%25B7%25B8%25EB%25A6%25BC4.png)


