# React Native 할 일 목록 프로젝트

### 개요
이 프로젝트는 React Native를 사용하여 할 일 목록 애플리케이션을 구현합니다. 일일 작업 관리를 위한 사용자 친화적인 인터페이스를 제공하며, 일정을 관리하고 추적할 수 있는 캘린더 뷰가 포함되어 있습니다. 앱은 @react-navigation/native로 내비게이션, react-native-calendars로 캘린더 기능, react-native-paper로 UI 요소 등 React Native 컴포넌트와 라이브러리를 활용합니다.

### 기능
1. 작업 관리: 작업 생성, 업데이트 및 삭제 기능.
2. 캘린더 뷰: 일일, 주간 또는 월간 기준으로 작업을 보고 관리할 수 있음.
3. 커스텀 작업 컨텍스트: 작업의 글로벌 상태 관리를 위한 커스텀 React 컨텍스트 사용.
4. 상호 작용 UI: 상호 작용하는 구성 요소를 위해 TouchableOpacity 사용.
5. 내비게이션: 다른 화면으로 쉽게 이동할 수 있는 하단 탭 내비게이션.

### 사용 방법
● 작업 추가: '+' 아이콘 또는 입력 필드를 탭하여 새 작업을 추가합니다.

● 작업 보기: '할 일 목록' 탭에서 작업을 탐색합니다.

● 작업 관리: 작업을 스와이프하여 삭제하거나 탭하여 완료로 표시합니다.

● 작업 일정: '달력' 탭을 사용하여 특정 날짜의 작업을 보고 관리합니다.

● 작업 업데이트: 각 작업 옆의 편집 아이콘을 탭하여 작업 세부 정보를 편집합니다.

### 화면
● 홈 화면: 작업 목록을 표시하고 추가, 편집 또는 삭제 옵션을 제공합니다.

● 캘린더 화면: 작업 일정 및 개요를 보기 위한 캘린더 뷰를 보여줍니다.

### 컴포넌트
● Task: 개별 작업을 나타내는 컴포넌트로 편집, 삭제 또는 완료로 표시하는 옵션 제공.

● Date: 날짜를 선택하고 표시하는 캘린더 날짜 컴포넌트.

● IconButton: 편집, 삭제 등의 다양한 작업을 위한 재사용 가능한 버튼 컴포넌트.

● Input: 새 작업을 추가하기 위한 텍스트 입력 컴포넌트.

● Schedule: 캘린더 뷰에서 작업을 표시하는 컴포넌트.

● Title: 화면 제목을 렌더링하는 간단한 컴포넌트.

### 사용된 기술
● React Native

● Expo

● React Navigation

● Moment.js

● React Native Calendars

● React Native Paper
