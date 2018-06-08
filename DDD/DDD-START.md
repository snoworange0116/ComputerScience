# 간단 정리

## 도메인 모델 패턴
* 배송지 관련 기능 여부를 판단하는 기능은 Order에 있든, OrderState에 있든 중요한 점은 주문과 관련된 중요 업무 규칙을 주문 도메인 모델인 Order나 OrderState에서 구현한다는 점입니다.
* **핵심 규칙을 구현한 코드는 도메인 모델에만 위치하기 때문에 규칙이 바뀌거나 규칙을 확장해야 할 때 다른 코드에 영향을 덜 주고 변경 내역을 모델에 반영할 수 있게 된다.**