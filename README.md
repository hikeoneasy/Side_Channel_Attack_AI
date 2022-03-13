# Side_Channel_Attack_AI


SEED Crypto side channel attack by ML

SEED에 대한 파형은 다음을 통해 얻었습니다.

SEED의 구조를 이용하여 SCA를 진행하였습니다.

# 머신러닝을 이용한 SCA를 위해 다음과 같이 설계하였습니다. 


**KEY_LEFT** 와 **KEY_RIGHT**를 각각 공격하기 위해 먼저, **KEY_RIGHT**를 공격합니다.


이때, 비선형 함수인 S-BOX의 입력값과 파형을 학습시킵니다. **(Profiling 과정)**

이를 통해 key right를 얻게 되면 S-box의 출력값을 이용해 **KEY_LEFT**또한 유사한 과정을 통해 공격해 줍니다. 


**자세한 내용은 pdf에 담아두었습니다.**
