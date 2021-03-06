---
title:  "가상환경 활성화가 되지 않을 때"
excerpt: "conda activate 안먹힐 때"

categories:
  - Anaconda
tags:
  - [anaconda, virtualenv, Ph.D., ME]

toc: true
toc_sticky: true
 
date: 2021-06-16
last_modified_at: 2021-06-15
---

---

### <span style="color:#084B8A">아나콘다 가상환경이 활성활 되지 않을 때</span>

아래와 같이 우분투(리눅스)에서, 아나콘다의 가상환경이 활성화 되지 않는 경우가 종종 있다.  
``` $ conda activate base```

![failed](/assets/images/2021-06-10-source-activate/error.png)

리눅스 환경에서는 ```conda activate```가 아닌, ```source activate```로 가상환경을 활성화한다. 아래의 코드를 이용하여 가상환경을 활성화할 수 있다.  

```$ source activate base ```

![succeded](/assets/images/2021-06-10-source-activate/source_activate.png)

코드의 ```conda```를 ```source```로 바꿔, 가상환경이 활성화 된 것을 확인할 수 있다.

---