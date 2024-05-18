# Compose_Migration
[Android] Compose Migration
```
기존 xml 프로젝트를 Compose UI로 Migration 기술 학습

기간 : 2024.06.10 ~ (예정)
```
## Jetpack Compose 마이그레이션 한 이유
- XML을 사용하지 않고 Kotlin Code만으로 UI 개발이 가능하다
- 복잡한 RecyclerView 및 Adapter를 더 이상 사용하지 않아도 된다   

## Jetpack Compose 마이그레이션 전략
작은 컴포넌트부터 시작하기   
- TopAppBar, Image, Button 등 작은 컴포넌트를 우선으로 먼저 Compose로 변환 시킨다
## XML과 Compose 공존하기
- XML에서 ComposeView를 사용하여 Compose로 작성된 컴포넌트를 사용하여 기존 XML 뷰 시스템과 같이 사용할 수 있도록 한다
- 작은 것부터 시작해서 점차적으로 Compose로 변환 시키기
- View -> ViewGroup -> RootView로 점차적으로 Compose로 변환 시켜 전체적으로 Compose로 사용할 수 있게 한다.
