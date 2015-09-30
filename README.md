# honeyqa-DB-Architecture

##ERD 다이어그램(도메인 모델링)

1. 현재 데이터 타입은 정의되어 있지 않지만, 상당 부분 json 타입으로 정의 될 예정입니다.
2. tag, event_path 등 레코드가 다수인 필드의 경우 array로 저장한다고 생각하고 봐주시면 됩니다.
3. 필터 부분은 레디스로 처리할 예정이며 현재 설계중에 있습니다. 마무리 되는대로 올릴게요.
4. 통계 역시 레디스로 처리 가능한 부분이라고 생각하여 현재 erd에서는 제외하였습니다 ㅎㅎ

![erd](https://lh3.googleusercontent.com/O-dH6YRbpLPntANGe7OeD63Rt6EzpIWKZDsbQBB8wz1UqppDs2sbLFYhvuUEgPeSOYNX0xVd718juMo=w2434-h1036-rw)

##Server Architecture

![sa](https://lh4.googleusercontent.com/6Lve0nURfQnAofUdgneGTFHI7Lv_Ep6wzCLBkyejIogzEaY9k2SeRwqA409ET7z3UcWAgSMhD59SCis=w2434-h1036-rw)
