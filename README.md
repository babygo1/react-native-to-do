# react-native-to-do

리액트 네이티브 to-do-app을 위한 codebase project입니다.

해당 과제는 인터넷에서 starter로써 가장 많은 예시가 있기 때문에, React-Native에 대한 이해를 돕기 위한 Task라고 보시면 되겠습니다. 

아래 몇 가지 유의사항을 확인하시면서 진행하시면 되겠습니다.

https://reactnative.dev/ 

를 참고하여 실제 개발환경을 세팅해 보시고 (다른 source라도 괜찮습니다.) 만약 문제가 있으실 경우 저에게 연락해 주시면 최대한 알려드리겠습니다.

https://javascript.plainenglish.io/building-a-todo-app-with-react-native-aaa33b779d5b

에서 실제 작동하는 코드를 확인하실 수 있지만, 참고용으로만 사용하시고 실제로 고민하시면서 작성하시는 것을 추천 드립니다.

1. ios에서 작업 시 ios 환경, 그 외에서 작업 시 android 환경으로 작업
2. React Hooks 구조로 작업, 라이프사이클 및 메소드에 대해 고민해보면 좋겠습니다.(UseEffect, UseRef, UseMemo) 등
3. Dynamic한 데이터를 다룰 때, 기존의 Array.prototype.map 메소드를 사용하셨을 것이지만, React-Native docs에서 권장하는 대로 FlatList로 작성해 보시면 좋겠습니다.
   두가지 코드의 차이점에 대해서도 한번 알아보시는게 좋을 것 같습니다.


Fundamental Goals

사용하시는 개발 기기에 맞는 React-Native 개발 환경 세팅

1. TextInput을 사용해 실제로 To-Do의 리스트를 입력할 수 있는 입력창 및 추가 버튼
2. 입력창을 지울 수 있게 하는 버튼 추가
3. 해당 item을 탭할 경우 완료하였다는 뜻으로 취소선을 그을 수 있는 기능

Advanced Goals

해보시고 싶은 모든 것을 진행해보시면 좋겠습니다.

1. recoil을 이용한 to-do 리스트 구현해보기
2. 1.의 list가 앱 종료 후 다시 실행할 때에도 유지되는 방안을 고민해보기
3. 기기별 가로 세로 비를 고려해 더 나은 design props을 넣는 방안을 고민해보기
4. etc...


