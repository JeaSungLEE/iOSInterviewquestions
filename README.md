# Jercy's Interview Questions for iOS Developers

> 이전 질문 리스트는 [여기](https://github.com/JeaSungLEE/iOSInterviewquestions/blob/master/oldREADME.md)에서 확인할 수 있습니다.

iOS 면접 준비와 학습을 돕기 위해 구성된 자료 저장소입니다. 이 저장소는 질문의 깊은 '왜'를 이해하는 데 중점을 두고, 단순한 지식 암기를 넘어선 질문들로 구성되어 있습니다.

답변을 단순히 외우는 것이 아니라, 그 이유를 이해하고 설명할 수 있도록 저장소는 질문에 중점을 두고 있습니다. 저장소는 직접적인 답변을 제공하지 않아, 여러분이 자체적으로 답변을 준비하면서 관련 지식을 탐구하고 확장할 수 있도록 유도합니다.

우선, 기초 지식의 확립이 중요하므로, 면접 질문 학습에 앞서 다음과 같은 권장 학습 자료들을 확인하시길 바랍니다:

1. [CS50](https://www.edwith.org/cs50) - 필수적인 컴퓨터 과학 기초 지식을 배울 수 있는 강좌입니다. (챕터5까지)
2. [모두를 위한 컴퓨터 과학](https://www.boostcourse.org/cs112/joinLectures/41307) - 자료구조와 알고리즘등 필수적인 개념을 알려주는 강좌입니다.
3. [Swift 한국어](https://bbiguduk.gitbook.io/swift/) - Swift 언어에 대한 종합적인 이해를 돕는 자료입니다.
4. [ProGit](https://git-scm.com/book/ko/v2) - Git의 기본 사용법과 원리를 학습할 수 있는 자료입니다.
5. [leetCode](https://leetcode.com/) - 알고리즘은 프로그래밍에 있어서 빠질수 없는 영역입니다. 꾸준히 많은 문제를 푸시는것이 좋습니다.

아래는 Apple의 가이드 문서와 튜토리얼입니다. 지속적으로 업데이트 되고 있으니 한번씩 구경 해보세요.

1. [Apple All Videos](https://developer.apple.com/videos/all-videos/) - Apple 개발자 컨퍼런스 비디오로, 최신 iOS 개발 트렌드와 기술을 배울 수 있습니다.
2. [iOS App Dev Tutorials](https://developer.apple.com/tutorials/app-dev-training/) - Apple에서 제공하는 iOS 앱 개발 튜토리얼입니다.
3. [SwiftUI Tutorials](https://developer.apple.com/tutorials/swiftui) - SwiftUI에 대한 Apple의 튜토리얼입니다.
4. [Apple Developer Documentation](https://developer.apple.com/documentation/) - Apple의 공식 개발 문서입니다.

Apple 공식 개발 문서중 읽어 보면 좋은 문서들은 다음과 같습니다:

- [Xcode](https://developer.apple.com/documentation/xcode/)
- [Autolayout](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/AutolayoutPG/index.html)
- [Human Interface Guidelines (HIG)](https://developer.apple.com/design/human-interface-guidelines/)
- [Swift Package Manager (SPM)](https://developer.apple.com/documentation/xcode/swift-packages)
- [Local & Push Notification](https://developer.apple.com/library/archive/documentation/NetworkingInternet/Conceptual/RemoteNotificationsPG/index.html)
- [View, Window Guide](https://developer.apple.com/library/archive/documentation/WindowsViews/Conceptual/ViewPG_iPhoneOS/Introduction/Introduction.html)
- [ViewController Guide](https://developer.apple.com/library/archive/featuredarticles/ViewControllerPGforiPhoneOS/)
- [Code Signing Guide](https://developer.apple.com/library/archive/documentation/Security/Conceptual/CodeSigningGuide/Introduction/Introduction.html)
- [Info Plist Guide](https://developer.apple.com/library/archive/documentation/General/Reference/InfoPlistKeyReference/Introduction/Introduction.html)

이러한 자료들은 iOS 개발의 기초를 다지고, 면접 준비에 필요한 깊은 이해와 지식을 제공할 것입니다.

# 레벨별 예상 질문 리스트

> 아래 레벨은 총 6개로 구성되어있으며, 레벨은 임의로 개인적인 기준으로 나누었습니다.

> 레벨 0: 학생<br>
> 레벨 1: 0 ~ 1년차<br>
> 레벨 2: 1 ~ 3년차<br>
> 레벨 3: 3 ~ 5년차<br>
> 레벨 4: 5 ~ 7년차<br>
> 레벨 5: 7년차 이상

## 레벨 0

> 아래 내용이 어려우시다면 2020년이후 개정 된 [정보처리기사](https://namu.wiki/w/%EC%A0%95%EB%B3%B4%EC%B2%98%EB%A6%AC%EA%B8%B0%EC%82%AC/%EC%8B%9C%ED%97%98/2020%EB%85%84%20%EA%B0%9C%EC%A0%95)를 공부하시는것을 추천합니다.

1. 컴퓨터 구조와 관련하여 CPU, RAM, 저장장치의 역할과 상호 작용에 대해 설명해주세요.

- 캐시 메모리의 개념과 종류, 역할에 대해 설명해주세요.
- CPU 아키텍처의 종류(예: ARM, x86)와 특징에 대해 설명해주세요.
- iOS 기기에서 사용되는 AP(Application Processor)의 특징과 역할에 대해 설명해주세요.

2. 운영체제의 역할과 iOS에서의 운영체제 구조에 대해 설명해주세요.

- 프로세스와 스레드의 차이점, iOS에서의 프로세스와 스레드 관리 방법에 대해 설명해주세요.
- 메모리 관리 기법 중 iOS에서 사용되는 방식과 그 특징에 대해 설명해주세요.
- iOS의 샌드박스(Sandbox) 개념과 역할, 앱 간 데이터 공유 방법에 대해 설명해주세요.

3. iOS에서의 메모리 구조와 관리 방식에 대해 자세히 설명해주세요.

- iOS 앱의 메모리 구조(힙, 스택, 코드 영역 등)와 각 영역의 특징에 대해 설명해주세요.
- 힙 영역에서 객체가 어떻게 할당되고 관리되는지 설명해주세요.
- 스택 영역에서 함수 호출과 로컬 변수의 메모리 할당 및 해제 과정을 설명해주세요.

4. 네트워크 프로토콜 스택과 iOS에서의 네트워크 통신 방식에 대해 설명해주세요.

- HTTP와 HTTPS의 차이점, iOS에서의 보안 통신 방법에 대해 설명해주세요.
- TCP와 UDP의 차이점에 대해서 설명해 주세요.
- 소켓 통신에 대해 설명해주세요.
- REST API와 iOS에서의 네트워크 요청 및 응답 처리 방법에 대해 설명해주세요.
- REST API에서 Method들의 차이점을 설명해주세요.
- HTTP 상태 코드에 대해서 설명해주세요.

5. iOS에서 메모리 사이즈와 관련된 개념과 고려 사항에 대해 설명해주세요.

- iOS 디바이스의 메모리 제약과 앱 메모리 제한에 대해 설명해주세요.
- 메모리 워드(word) 크기와 데이터 정렬(alignment)이 메모리 액세스 성능에 미치는 영향에 대해 설명해주세요.
- 포인터 크기(32비트, 64비트)에 따른 메모리 사용량 차이와 고려 사항에 대해 설명해주세요.
- iOS 앱에서 대용량 데이터를 다룰 때 메모리 사이즈를 고려한 최적화 방안에 대해 설명해주세요.

6. 알고리즘의 시간 복잡도와 공간 복잡도의 개념, 빅오 표기법에 대해 설명해주세요.

- 자주 사용되는 정렬 알고리즘(예: 퀵 정렬, 병합 정렬)의 동작 원리와 시간 복잡도를 설명해주세요.
- 이진 탐색의 원리와 시간 복잡도에 대해 설명해주세요.
- 다이나믹 프로그래밍(Dynamic Programming)의 개념을 설명해주세요.

7. 자료구조의 종류와 iOS 개발에서 자주 사용되는 자료구조에 대해 설명해주세요.

- 배열, 연결 리스트, 스택, 큐의 특징과 iOS에서의 구현 방법을 설명해주세요.
- 해시 테이블의 개념, 충돌 해결 방법을 설명해주세요.
- 트리 자료구조의 종류(예: 이진 트리, 이진 탐색 트리, AVL 트리)을 설명해주세요.

8. 동시성 프로그래밍의 개념과 iOS에서의 동시성 처리 방식에 대해 설명해주세요.

- 병렬 처리와 동시 처리의 차이, iOS에서의 멀티코어 활용 방안에 대해 설명해주세요.

9. 암호화와 보안의 기본 개념, iOS 앱 보안을 위한 방안에 대해 설명해주세요.

- 대칭키 암호화와 비대칭키 암호화의 차이에 대해 설명해주세요.
- 해시 함수의 개념과 활용 사례에 대해 설명해주세요.

10. 가상 메모리(Virtual Memory)의 개념과 동작 원리에 대해 설명해주세요.

- 가상 메모리의 필요성과 장점에 대해 설명해주세요.
- 페이징(Paging) 기법의 개념과 동작 원리, 페이지 테이블의 역할에 대해 설명해주세요.
- 세그먼테이션(Segmentation) 기법의 개념과 페이징과의 차이점에 대해 설명해주세요.

11. iOS 앱의 메모리 사용량 최적화를 위한 방안과 고려 사항에 대해 설명해주세요.

- 메모리 캐싱 기법(예: NSCache, 이미지 캐싱)의 개념과 iOS에서의 구현 방법을 설명해주세요.
- 대용량 데이터(예: 이미지, 비디오) 처리 시 메모리 최적화 방안(예: lazy loading, 썸네일 활용)에 대해 설명해주세요.

12. 데이터베이스의 종류와 iOS에서 주로 사용되는 데이터베이스에 대해 설명해주세요.

- iOS에서 사용되는 SQLite, Core Data, Realm 등의 특징과 사용 사례를 설명해주세요.
- 관계형 데이터베이스의 ACID 특성과 트랜잭션의 개념에 대해 설명해주세요.
- iOS에서 데이터베이스 스키마 버전 관리와 마이그레이션을 처리하는 방법을 설명해주세요.

13. iOS에서 자동 참조 카운팅(ARC)과 가비지 컬렉션(Garbage Collection)의 차이점에 대해 설명해주세요.

- 가비지 컬렉션의 동작 원리와 장단점에 대해 설명해주세요.
- iOS에서 가비지 컬렉션을 사용하지 않는 이유와 ARC를 선택한 배경에 대해 설명해주세요.

## 레벨 1

1. Swift에서 옵셔널이란 무엇이며, 언제 사용해야 하나요?

- 옵셔널 바인딩과 강제 언래핑의 차이점은 무엇인가요?
- 옵셔널 체이닝의 동작 원리를 설명해주세요.
- 암시적 언래핑 옵셔널을 사용하는 경우는 언제인가요?
- nil 병합 연산자(??)의 사용 예시를 들어주세요.

2. iOS 앱의 생명주기(App Life Cycle)에 대해 설명해주세요.

- 앱의 각 상태(Not Running, Inactive, Active, Background, Suspended)에서 할 수 있는 작업은 무엇인가요?
- 앱 상태 변화에 따라 호출되는 AppDelegate 메서드들을 나열해주세요.
- 백그라운드에서 작업을 완료하기 위한 방법들은 무엇이 있나요?

3. Storyboard와 XIB의 차이점은 무엇인가요?

- Storyboard에서 세그(Segue)를 사용하는 이유는 무엇인가요?
- Storyboard 참조(Storyboard Reference)의 장점은 무엇인가요?

4. 뷰를 구현할때 Storyboard와 Code로 구현하는 각각의 장단점은 무엇인가요?

- 선호하는 방식이 있다면 무엇이고 왜 더 선호하나요?

5. Auto Layout을 사용하는 이유와 장점은 무엇인가요?

- 제약 조건(Constraints)의 우선순위(Priority)는 어떤 역할을 하나요?
- 스택 뷰(Stack View)의 속성들을 설명해주세요.
- 인터페이스 빌더에서 제약 조건 충돌을 해결하는 방법은 무엇인가요?

6. Swift에서 클로저(Closure)란 무엇이며, 어떻게 사용하나요?

- 클로저의 캡처 리스트(Capture List)는 어떤 역할을 하나요?
- @escaping 클로저와 non-escaping 클로저의 차이점은 무엇인가요?
- 트레일링 클로저(Trailing Closure) 문법은 언제 사용하면 좋나요?

7. iOS에서 델리게이트 패턴(Delegate Pattern)은 어떤 목적으로 사용되나요?

- 델리게이트 패턴과 콜백 함수의 차이점은 무엇인가요?
- 델리게이트 패턴과 옵저버 패턴의 차이점은 무엇이고 각각 어떨때 사용하면 좋나요?
- 델리게이트 메서드에서 반환값을 사용하는 경우는 언제인가요?

8. Swift의 기본 데이터 타입에는 어떤 것들이 있나요?

- 값 타입(Value Type)과 참조 타입(Reference Type)의 차이점을 설명해주세요.
- 구조체(Struct)와 클래스(Class)는 어떤 차이가 있나요?
- 열거형(Enum)의 원시값(Raw Value)과 연관값(Associated Value)은 무엇인가요?

9. Xcode에서 디버깅 시 자주 사용하는 기능들은 무엇이 있나요?

- 중단점(Breakpoint)의 종류와 사용 방법을 설명해주세요.
- LLDB 콘솔에서 자주 사용하는 명령어는 무엇인가요?
- 조건부 중단점(Conditional Breakpoint)은 어떤 경우에 사용하면 좋나요?

10. iOS 앱에서 데이터를 저장하는 방법에는 어떤 것들이 있나요?

- UserDefaults의 사용 예시와 주의 사항을 설명해주세요.
- Keychain은 어떤 데이터를 저장하는 데 적합한가요?
- Core Data와 SQLite의 차이점은 무엇인가요?

11. Swift에서 프로토콜(Protocol)이란 무엇이며, 어떻게 사용하나요?

- 프로토콜의 요구 사항에는 어떤 것들이 있나요?
- 프로토콜 확장(Protocol Extension)을 사용하는 이유는 무엇인가요?
- 프로토콜 지향 프로그래밍(Protocol-Oriented Programming)의 장점은 무엇인가요?

12. Swift의 접근 제어자(Access Control)에 대해 설명해주세요.

- open과 public의 차이점은 무엇인가요?
- 접근 제어자를 사용하는 이유는 무엇인가요?
- 상속과 관련된 접근 제어자는 무엇이 있나요?

13. iOS 앱에서 네트워크 통신을 하는 방법에는 어떤 것들이 있나요?

- URLSession의 주요 구성 요소를 설명해주세요.
- 네트워크 요청 시 에러 처리는 어떻게 하나요?
- Alamofire와 같은 서드파티 라이브러리를 사용하는 이유는 무엇인가요?

14. Swift의 옵셔널과 관련된 함수에는 어떤 것들이 있나요?

- map()과 flatMap()의 차이점을 설명해주세요.
- compactMap()은 어떤 경우에 사용하나요?
- 옵셔널 체이닝을 사용할 때 주의할 점은 무엇인가요?

15. Git에서 브랜치(Branch)를 사용하는 이유와 장점은 무엇인가요?

- 브랜치를 병합(Merge)하는 방법에는 어떤 것들이 있나요?
- 브랜치 전략(Git-Flow, GitHub-Flow 등)에 대해 설명해주세요.
- 브랜치 충돌(Conflict) 해결 방법을 설명해주세요.

16. iOS 앱에서 코어 데이터(Core Data)를 사용하는 이유는 무엇인가요?

- 코어 데이터의 주요 구성 요소(Entity, Attribute, Relationship 등)를 설명해주세요.
- 코어 데이터에서 데이터를 가져오는 방법(Fetch Request)에 대해 설명해주세요.
- 코어 데이터 마이그레이션(Migration)은 언제 필요한가요?

17. Swift의 high-order functions에 대해 설명해주세요.

- map()과 compactMap()의 차이점은 무엇인가요?
- filter()와 reduce()는 어떤 경우에 사용하나요?
- flatMap()을 사용하는 경우를 예시로 들어주세요.

18. Xcode에서 유용한 단축키와 생산성을 높이는 팁에 대해 설명해주세요.

19. iOS 개발을 위한 라이브러리 관리 도구(CocoaPods, Carthage, Swift Package Manager)의 차이점과 사용법을 설명해주세요.

- 각 도구의 장단점은 무엇인가요?

20. iOS 앱에서 URL Scheme을 사용하여 다른 앱과 통신하는 방법과 주의 사항을 설명해주세요.

21. Xcode의 인스트루먼트(Instruments)를 활용하여 앱의 성능을 분석하고 최적화하는 방법은 무엇인가요?

- Xcode의 디버깅 도구(Breakpoints, Logging 등)를 활용하여 효과적으로 디버깅하는 방법을 소개해주세요.
- 타임 프로파일러(Time Profiler)를 사용하여 앱의 병목 현상을 찾는 방법을 설명해주세요.
- 얼로케이션 프로파일러(Allocations Profiler)를 사용하여 메모리 사용량을 분석하는 방법은 무엇인가요?
- 레이아웃 디버깅(Layout Debugging)을 통해 오토레이아웃 문제를 해결하는 방법을 설명해주세요.

22. Swift에서 Any와 AnyObject의 차이점은 무엇인가요?

23. iOS 앱에서 NotificationCenter를 사용하는 목적과 사용 방법을 설명해주세요.

## 레벨 2

1. Swift의 동시성(Concurrency) 프로그래밍에 대해 설명해주세요.

- Grand Central Dispatch(GCD)의 주요 개념과 사용 방법을 설명해주세요.
- OperationQueue와 DispatchQueue의 차이점은 무엇인가요?
- 동시성 프로그래밍에서 발생할 수 있는 문제(Race Condition, Deadlock 등)와 해결 방법은 무엇인가요?

2. 객체지향 프로그래밍(OOP)의 주요 개념에 대해 설명해주세요.

- 캡슐화(Encapsulation)와 정보 은닉(Information Hiding)의 차이점은 무엇인가요?
- 상속(Inheritance)의 장단점은 무엇인가요?
- 다형성(Polymorphism)을 활용하는 예시를 들어주세요.

3. 프로토콜 지향 프로그래밍(POP)이란 무엇이며, 어떤 장점이 있나요?

- 프로토콜 확장(Protocol Extension)을 사용하는 이유는 무엇인가요?
- 프로토콜 컴포지션(Protocol Composition)은 어떤 경우에 사용하나요?
- 프로토콜과 제네릭(Generic)을 함께 사용하면 어떤 이점이 있나요?

4. iOS 앱의 메모리 관리는 어떻게 이루어지나요?

- ARC(Automatic Reference Counting)의 동작 원리를 설명해주세요.
- 강한 참조(Strong Reference)와 약한 참조(Weak Reference)의 차이점은 무엇인가요?
- 순환 참조(Retain Cycle)가 발생하는 경우와 해결 방법을 설명해주세요.
- 강한 참조, 약한 참조, 미소유 참조의 차이점을 설명해주세요.

5. 싱글톤 패턴(Singleton Pattern)이란 무엇이며, 어떤 경우에 사용하나요?

- 싱글톤 패턴의 장단점은 무엇인가요?
- 싱글톤 객체의 초기화 방법과 접근 방법을 설명해주세요.
- 싱글톤 패턴을 구현할 때 주의할 점은 무엇인가요?

6. Swift의 문자열(String) 다루기와 관련된 주요 기능은 무엇이 있나요?

- 서브스트링(Substring)과 문자열의 차이점은 무엇인가요?
- 문자열 보간법(String Interpolation)을 사용하는 방법과 주의 사항을 설명해주세요.
- 정규식(Regular Expression)을 사용하여 문자열을 다루는 방법을 설명해주세요.

7. Codable 프로토콜은 무엇이며, 어떻게 사용하나요?

- Encodable과 Decodable 프로토콜의 역할은 무엇인가요?
- JSON 데이터를 커스텀 객체로 디코딩하는 방법을 설명해주세요.
- Codable 프로토콜을 채택한 타입에서 인코딩/디코딩 키를 커스터마이징하는 방법은 무엇인가요?

8. iOS 앱에서 의존성 주입(Dependency Injection)은 어떤 목적으로 사용되나요?

- 의존성 주입의 세 가지 유형(Initializer Injection, Property Injection, Method Injection)을 설명해주세요.
- 의존성 주입 컨테이너(Dependency Injection Container)란 무엇인가요?
- 의존성 주입을 사용함으로써 얻을 수 있는 이점은 무엇인가요?

9. 델리게이션 패턴(Delegation Pattern)과 클로저의 차이점은 무엇인가요?

- 델리게이션 패턴에서 메모리 누수가 발생할 수 있는 경우와 해결 방법을 설명해주세요.
- 클로저의 캡처 리스트(Capture List)는 어떤 역할을 하나요?
- 델리게이션 패턴과 클로저를 함께 사용하는 경우의 장단점은 무엇인가요?

10. UIKit에서 테이블 뷰(UITableView)와 컬렉션 뷰(UICollectionView)의 차이점은 무엇인가요?

- 테이블 뷰와 컬렉션 뷰에서 셀을 재사용하는 이유와 방법을 설명해주세요.
- 테이블 뷰와 컬렉션 뷰의 데이터 소스(Data Source)와 델리게이트(Delegate)의 역할은 무엇인가요?
- 컬렉션 뷰에서 사용할 수 있는 레이아웃(Layout)의 종류와 특징을 설명해주세요.

11. iOS 앱 아키텍처 패턴 중 MVC, MVVM, VIP, MVI의 차이점은 무엇인가요?

- MVC의 장점은 무엇인가요?
- 각 아키텍처 패턴의 구성 요소와 책임을 설명해주세요.
- MVVM 패턴에서 Binding은 어떤 역할을 하나요?
- VIP 패턴에서 Presenter의 역할은 무엇인가요?
- MVI 패턴에서 Intent의 역할은 무엇인가요?

12. Swift에서 옵셔널(Optional)을 사용할 때 주의할 점은 무엇인가요?

- 강제 언래핑(Force Unwrapping)을 사용하면 안 되는 이유는 무엇인가요?
- 옵셔널 바인딩(Optional Binding)과 옵셔널 체이닝(Optional Chaining)의 차이점을 설명해주세요.
- 암시적 언래핑 옵셔널(Implicitly Unwrapped Optional)은 어떤 경우에 사용하나요?

13. iOS 앱에서 코어 애니메이션(Core Animation)을 사용하는 방법은 무엇인가요?

- CALayer의 주요 속성과 메서드를 설명해주세요.
- 애니메이션 그룹(Animation Group)은 어떤 경우에 사용하나요?
- 키 프레임 애니메이션(Keyframe Animation)과 스프링 애니메이션(Spring Animation)의 차이점은 무엇인가요?

14. Swift에서 프로토콜 지향 프로그래밍(Protocol-Oriented Programming)을 활용하는 방법은 무엇인가요?

- 프로토콜 확장(Protocol Extension)을 통해 기본 구현을 제공하는 방법을 설명해주세요.
- 프로토콜 상속(Protocol Inheritance)은 어떤 경우에 사용하나요?
- 프로토콜 지향 프로그래밍(Protocol-Oriented Programming)에서 제네릭(Generic)을 함께 사용하면 어떤 이점이 있나요?

15. iOS 앱에서 네트워크 요청 시 응답 캐싱(Response Caching)을 하는 방법은 무엇인가요?

- URLCache는 어떤 역할을 하나요?
- 응답 캐싱의 장단점은 무엇인가요?
- 응답 캐싱을 커스터마이징하는 방법을 설명해주세요.

16. Combine 프레임워크란 무엇이며, 어떤 기능을 제공하나요?

- Publisher와 Subscriber의 역할은 무엇인가요?
- Operator의 종류와 사용 방법을 설명해주세요.
- Combine과 RxSwift의 차이점은 무엇인가요?

17. Swift의 제네릭(Generic)에 대해 설명해주세요.

- 제네릭을 사용하는 이유는 무엇인가요?
- 제네릭 타입 파라미터(Generic Type Parameter)와 제네릭 타입 제약(Generic Type Constraint)은 무엇인가요?
- 제네릭을 사용할 때 주의할 점은 무엇인가요?

18. iOS 앱에서 로컬 푸시 알림(Local Push Notification)을 구현하는 방법은 무엇인가요?

- 로컬 푸시 알림과 원격 푸시 알림(Remote Push Notification)의 차이점은 무엇인가요?
- 푸시 알림의 콘텐츠(Content)와 트리거(Trigger)는 어떤 역할을 하나요?
- 사용자가 푸시 알림을 탭했을 때 앱의 동작을 처리하는 방법을 설명해주세요.

19. iOS 앱에서 SwiftUI와 UIKit을 함께 사용하는 방법은 무엇인가요?

- SwiftUI 뷰에서 UIKit 뷰 컨트롤러를 사용하는 방법을 설명해주세요.
- UIKit 뷰 컨트롤러에서 SwiftUI 뷰를 호스팅하는 방법은 무엇인가요?
- SwiftUI와 UIKit을 함께 사용할 때 주의할 점은 무엇인가요?

19. Swift에서 키 경로(Key Path)란 무엇이며, 어떻게 사용하나요?

- 키 경로 표현식(Key Path Expression)의 문법과 사용 예시를 설명해주세요.
- 런타임에 키 경로를 사용하여 속성에 접근하는 방법은 무엇인가요?
- 키 경로와 KVO(Key-Value Observing)의 관계를 설명해주세요.

20. iOS 앱에서 Deep Link와 Universal Link의 차이점은 무엇인가요?

- Deep Link를 구현하는 방법과 주의 사항을 설명해주세요.
- Universal Link의 동작 원리와 설정 방법은 무엇인가요?
- Deep Link와 Universal Link를 함께 사용하는 경우의 장점은 무엇인가요?

21. Swift의 Result 타입과 에러 처리 방식에 대해 설명해주세요.

- Result 타입을 사용하는 이유와 장점은 무엇인가요?
- 에러 처리 시 do-catch 문과 Result 타입을 함께 사용하는 방법을 설명해주세요.

22. iOS 앱에서 Thread Sanitizer를 사용하여 동시성 문제를 탐지하고 해결하는 방법을 설명해주세요.

23. Swift의 Sequence와 Collection 프로토콜에 대해 설명해주세요.

- Sequence와 Collection 프로토콜의 차이점과 요구 사항을 설명해주세요.
- 사용자 정의 Sequence와 Collection을 구현하는 방법과 사용 예시를 들어주세요.

24. UIKit의 AdaptiveLayout과 Size Classes에 대해 설명해주세요.

- AdaptiveLayout의 개념과 사용 목적을 설명해주세요.
- Size Classes를 활용하여 다양한 기기에 적응적인 UI를 구현하는 방법을 예시와 함께 설명해주세요.

25. Swift의 커스텀 연산자(Custom Operator)에 대해 설명해주세요.

- 커스텀 연산자를 정의하는 방법과 주의 사항은 무엇인가요?
- 커스텀 연산자를 활용한 코드 가독성 향상 방안을 제시해주세요.

26. Swift의 생성자(Initializer)와 관련된 고급 개념에 대해 설명해주세요.

- 지정 생성자(Designated Initializer)와 편의 생성자(Convenience Initializer)의 차이점은 무엇인가요?
- 필수 생성자(Required Initializer)와 실패 가능한 생성자(Failable Initializer)는 어떤 경우에 사용하나요?

27. Combine 프레임워크에서 Scheduler의 역할과 종류에 대해 설명해주세요.

- Scheduler를 사용하여 작업을 특정 큐(DispatchQueue)에서 실행하는 방법을 설명해주세요.
- 백그라운드에서 작업을 수행하고 메인 큐에서 UI를 업데이트하는 패턴을 Combine으로 구현하는 방법을 설명해주세요.

28. UIKit의 `UIView`는 클래스 기반으로 구현되어 있지만, SwiftUI에서 `View` 프로토콜을 준수하는 타입은 보통 구조체를 사용합니다. 그 이유는 무엇일까요?

- `View` 프로토콜을 준수하는 구조체의 주요 특징은 무엇이며, 이는 어떻게 SwiftUI의 성능 및 사용성에 영향을 미치나요?
- SwiftUI의 `View`가 구조체임에도 불구하고, 상태(state)를 어떻게 관리하고 업데이트하나요?
- SwiftUI의 구조체 기반 `View` 생성과 업데이트 사이클은 어떻게 UIKit의 클래스 기반 `UIView`와 다른가요?

## 레벨 3

1. iOS 앱에서 Core Data를 사용한 데이터 마이그레이션(Migration)에 대해 설명해주세요.

- 경량 마이그레이션(Lightweight Migration)과 무거운 마이그레이션(Heavyweight Migration)의 차이점은 무엇인가요?
- 매핑 모델(Mapping Model)을 사용하여 데이터를 마이그레이션하는 방법을 설명해주세요.
- 데이터 마이그레이션 중 발생할 수 있는 문제와 해결 방법은 무엇인가요?

2. iOS 앱의 낮은 메모리 상황 대응 방안과 관련 API에 대해 설명해주세요.

- 낮은 메모리 경고(Low Memory Warning)의 개념과 iOS에서의 동작 방식에 대해 설명해주세요.
- didReceiveMemoryWarning() 메서드의 역할과 구현 방법에 대해 설명해주세요.
- 낮은 메모리 상황에서 앱의 안정성을 유지하기 위한 리소스 관리 전략에 대해 설명해주세요.

3. Swift의 메타타입(Metatype)과 미러(Mirror)에 대해 설명해주세요.

- 메타타입을 사용하여 타입 정보에 접근하는 방법은 무엇인가요?
- 미러를 사용하여 객체의 속성을 동적으로 탐색하는 방법을 설명해주세요.
- 메타타입과 미러를 활용한 실제 사용 사례를 들어주세요.

4. iOS 앱에서 바이너리 프레임워크(Binary Framework)를 생성하고 사용하는 방법은 무엇인가요?

- 바이너리 프레임워크와 소스 코드 프레임워크의 차이점은 무엇인가요?
- 바이너리 프레임워크를 생성할 때 고려해야 할 사항은 무엇인가요?
- 바이너리 프레임워크를 배포하고 버전 관리하는 방법을 설명해주세요.

5. Combine 프레임워크에서 에러 처리는 어떻게 하나요?

- 에러 이벤트를 처리하기 위한 Operator에는 어떤 것들이 있나요?
- 에러 이벤트 발생 시 Subscription을 자동으로 취소하는 방법은 무엇인가요?
- Combine과 Result 타입을 함께 사용하여 에러 처리를 하는 방법을 설명해주세요.

6. Swift의 동적 멤버 조회(Dynamic Member Lookup)에 대해 설명해주세요.

- @dynamicMemberLookup 속성의 역할과 사용 방법은 무엇인가요?
- 서브스크립트(Subscript)를 사용하여 동적 멤버 조회를 구현하는 방법을 설명해주세요.
- 동적 멤버 조회를 활용한 실제 사용 사례를 들어주세요.

7. Swift의 Property Wrapper에 대해 설명해주세요.

- Property Wrapper를 사용하는 이유와 장점은 무엇인가요?
- @State, @Binding, @ObservedObject 등의 Property Wrapper의 차이점과 사용 방법을 설명해주세요.
- Custom Property Wrapper를 만드는 방법과 사용 예시를 들어주세요.

8. iOS 앱에서 Siri Shortcuts을 구현하는 방법은 무엇인가요?

- Siri Shortcuts의 동작 원리와 사용 사례를 설명해주세요.
- NSUserActivity와 Intents Framework를 사용하여 Siri Shortcuts을 구현하는 방법을 설명해주세요.
- Siri Shortcuts을 사용자 정의하고 파라미터를 전달하는 방법은 무엇인가요?

9. Swift의 unsafe 포인터(Unsafe Pointer)에 대해 설명해주세요.

- UnsafePointer, UnsafeMutablePointer, UnsafeRawPointer의 차이점과 사용 방법은 무엇인가요?
- unsafe 포인터를 사용할 때 주의해야 할 점은 무엇인가요?
- unsafe 포인터를 사용하여 C 언어 라이브러리와 상호작용하는 방법을 설명해주세요.

10. Swift의 reflection에 대해 설명해주세요.

- Mirror 타입을 사용하여 객체의 속성을 동적으로 탐색하는 방법은 무엇인가요?
- 런타임에 타입 정보를 검사하고 메서드를 호출하는 방법을 설명해주세요.
- reflection을 사용할 때 주의해야 할 점과 성능 고려 사항은 무엇인가요?

11. iOS 앱에서 Keychain을 사용하여 민감한 데이터를 안전하게 저장하는 방법은 무엇인가요?

- Keychain Services API를 사용하여 데이터를 저장하고 읽어오는 과정을 설명해주세요.
- Keychain Access Groups를 사용하여 앱 간에 데이터를 공유하는 방법은 무엇인가요?
- Keychain의 접근 제어(Access Control) 옵션과 사용 방법을 설명해주세요.

12. Swift의 async/await를 사용한 비동기 프로그래밍에 대해 설명해주세요.

- async/await 문법의 동작 원리와 사용 방법은 무엇인가요?
- Task와 TaskGroup을 사용하여 비동기 작업을 관리하는 방법을 설명해주세요.
- 비동기 시퀀스(AsyncSequence)와 비동기 스트림(AsyncStream)의 차이점과 사용 예시를 들어주세요.

13. iOS 앱에서 WidgetKit을 사용하여 홈 화면 위젯을 구현하는 방법은 무엇인가요?

- 위젯의 생명주기(Life Cycle)와 업데이트 방식을 설명해주세요.
- SwiftUI를 사용하여 위젯의 UI를 구성하는 방법과 주의 사항은 무엇인가요?
- 위젯과 앱 간의 데이터 공유 및 통신 방법을 설명해주세요.

14. MVVM-C(Coordinator) 아키텍처 패턴에 대해 설명해주세요.

- Coordinator의 역할과 구현 방법을 설명해주세요.
- MVVM-C 패턴의 장단점과 적용 사례를 소개해주세요.

15. Swift의 @dynamicCallable과 @dynamicMemberLookup에 대해 설명해주세요.

- @dynamicCallable을 사용하여 사용자 정의 호출 가능 타입을 만드는 방법과 사용 예시를 들어주세요.
- @dynamicMemberLookup을 활용하여 동적으로 속성에 접근하는 방법과 실제 사용 사례를 소개해주세요.

16. Swift의 ABI(Application Binary Interface) 안정성에 대해 설명해주세요.

- ABI 안정성의 개념과 중요성을 설명해주세요.
- ABI 안정성이 프레임워크 개발과 배포에 미치는 영향을 설명해주세요.

17. iOS 앱에서 Combine 프레임워크를 활용한 반응형 프로그래밍 패턴에 대해 설명해주세요.

- MVVM 아키텍처에서 Combine을 활용한 데이터 바인딩 방법을 예시와 함께 설명해주세요.
- Combine과 SwiftUI를 함께 사용하여 선언적이고 반응형 UI를 구축하는 방법을 소개해주세요.

18. Swift의 런타임 동작과 성능 최적화 기법에 대해 설명해주세요.

- Swift 런타임의 구조와 동작 방식을 설명해주세요.
- 동적 디스패치, 인라이닝, 스택 프로모션 등 Swift 성능 최적화 기법과 컴파일러 최적화 옵션을 소개해주세요.

19. iOS 앱의 접근성(Accessibility)을 향상시키기 위한 방법과 고려 사항에 대해 설명해주세요.

- VoiceOver, Switch Control 등 접근성 기술의 동작 원리와 지원 방법을 설명해주세요.
- Dynamic Type, Bold Text 등 시각적 접근성 향상을 위한 기술과 구현 방법을 소개해주세요.
- 접근성 테스트 및 심사 기준, 모범 사례 등을 예시와 함께 설명해주세요.

20. iOS 앱에서 Objective-C 브리징(Bridging)을 하는 방법과 주의 사항을 설명해주세요.

## 레벨 4

1. Swift의 메모리 안전성(Memory Safety)에 대해 설명해주세요.

- 소유권(Ownership)과 빌림(Borrowing)의 개념과 차이점은 무엇인가요?
- 메모리 안전성을 보장하기 위한 Swift의 메커니즘(대여 검사, 소유권 검사 등)을 설명해주세요.
- 메모리 안전성 규칙을 위반하는 경우와 해결 방법을 예시와 함께 설명해주세요.

2. iOS 앱에서 Core Bluetooth를 사용하여 BLE(Bluetooth Low Energy) 통신을 구현하는 방법은 무엇인가요?

- Central과 Peripheral의 역할과 상호작용 과정을 설명해주세요.
- CBCentralManager와 CBPeripheralManager의 주요 메서드와 델리게이트 메서드를 설명해주세요.
- BLE 통신에서 사용되는 서비스(Service)와 특성(Characteristic)의 개념과 구현 방법을 설명해주세요.

3. Swift의 Copy-on-Write 메커니즘에 대해 설명해주세요.

- Copy-on-Write의 동작 원리와 장점은 무엇인가요?
- Copy-on-Write를 사용하는 Swift의 타입에는 어떤 것들이 있나요?
- Copy-on-Write를 고려하여 성능 최적화를 하는 방법을 예시와 함께 설명해주세요.

4. iOS 앱에서 Core NFC를 사용하여 NFC 태그와 상호작용하는 방법은 무엇인가요?

- NFCNDEFReaderSession과 NFCTagReaderSession의 차이점과 사용 방법을 설명해주세요.
- NFC 태그 읽기 및 쓰기 과정과 필요한 권한 설정 방법을 설명해주세요.
- Core NFC를 사용할 때 주의해야 할 점과 제한 사항은 무엇인가요?
- Core NFC를 사용할 때 고려해야 할 보안 사항과 모범 사례를 설명해주세요.

5. Swift의 actor와 structured concurrency에 대해 설명해주세요.

- actor의 개념과 동시성 문제 해결 방법을 설명해주세요.
- async let과 TaskGroup을 사용한 구조적 동시성 프로그래밍 방법을 예시와 함께 설명해주세요.
- actor와 structured concurrency를 활용한 효과적인 비동기 프로그래밍 패턴을 소개해주세요.

6. iOS 앱에서 Vision 프레임워크를 사용하여 이미지 분석 및 처리를 수행하는 방법은 무엇인가요?

- 얼굴 감지 및 인식, 바코드 인식, 텍스트 인식 등의 기능 구현 방법을 설명해주세요.
- Vision 요청(VNRequest)의 종류와 사용 방법, 결과 처리 과정을 설명해주세요.
- Vision 프레임워크와 Core ML, ARKit 등 다른 프레임워크와의 연동 방법을 소개해주세요.

7. Swift의 property wrappers에 대해 설명해주세요.

- property wrappers의 동작 원리와 사용 목적, 구현 방법을 설명해주세요.

8. iOS 앱의 보안을 강화하기 위한 방법과 모범 사례에 대해 설명해주세요.

- 안전한 데이터 저장 및 전송을 위한 암호화 기술(AES, RSA 등)과 구현 방법을 설명해주세요.
- 앱 바이너리 보호, 탈옥 감지, 동적 라이브러리 감지 등의 보안 대책을 소개해주세요.
- 코드 난독화, 런타임 무결성 검사 등 추가적인 보안 강화 방안을 제안해주세요.

9. Swift의 custom string interpolation에 대해 설명해주세요.

- custom string interpolation을 사용하여 문자열 보간법을 확장하는 방법을 예시와 함께 설명해주세요.

10. Swift의 Distributed Actor에 대해 설명해주세요.

- Distributed Actor의 개념과 사용 목적을 설명해주세요.
- 분산 시스템에서 Distributed Actor를 활용한 통신 및 상태 동기화 방법을 예시와 함께 설명해주세요.

11. Swift의 DSL(Domain-Specific Language) 설계 및 구현 방법에 대해 설명해주세요.

- DSL의 개념과 장점, Swift에서의 구현 방식을 설명해주세요.
- result builder를 활용한 DSL 설계 사례를 소개해주세요.

12. Swift의 유연한 문법 기능(e.g., 오퍼레이터 오버로딩, 첨자 표기법)을 활용한 코드 설계 방법에 대해 설명해주세요.

- 오퍼레이터 오버로딩을 사용하여 사용자 정의 타입에 대한 연산을 직관적으로 표현하는 방법을 예시와 함께 설명해주세요.
- 첨자 표기법을 사용하여 사용자 정의 컬렉션 타입을 구현하는 방법과 주의 사항을 설명해주세요.

13. Swift의 리플렉션(Reflection)과 런타임 프로그래밍에 대해 자세히 설명해주세요.

- 리플렉션을 사용하여 런타임에 타입 정보를 검사하고 메서드를 호출하는 방법을 예시와 함께 설명해주세요.
- 리플렉션을 활용한 의존성 주입(Dependency Injection) 프레임워크 구현 방법을 설명해주세요.

14. iOS 앱에서 Core ML을 사용하여 머신러닝 모델을 통합하는 방법은 무엇인가요?

- Core ML 모델을 생성하고 앱에 추가하는 과정을 설명해주세요.
- Vision 프레임워크와 Core ML을 함께 사용하여 이미지 인식을 수행하는 방법은 무엇인가요?
- Core ML 모델의 성능을 최적화하는 방법과 주의 사항을 설명해주세요.
- Core ML 이외에 사용할 수 있는 머신러닝 프레임워크와 장단점을 비교해주세요.
- 머신러닝 모델의 경량화 및 최적화 기법을 소개하고, 모바일 환경에 적합한 모델 설계 방안을 제시해주세요.

## 레벨 5

1. 효과적인 iOS 개발 팀 구성과 운영을 위한 전략과 모범 사례에 대해 설명해주세요.

- 개발 팀의 역할 분담 및 협업 방식, 커뮤니케이션 채널 등을 설명해주세요.
- 코드 리뷰, 페어 프로그래밍 등 코드 품질 및 지식 공유를 위한 방안을 제시해주세요.
- 기술 부채 관리, 성능 모니터링 등 프로젝트 운영과 관련된 모범 사례를 소개해주세요.

2. iOS 앱의 성능 최적화를 위한 전략과 도구에 대해 설명해주세요.

- Instruments를 사용한 성능 분석 및 병목 현상 탐지 방법을 소개해주세요.
- 메모리 관리, 이미지 최적화, 네트워크 요청 최적화 등의 성능 개선 방안을 제시해주세요.
- 앱 시작 시간 단축, 프레임 속도 향상 등 사용자 경험 개선을 위한 최적화 기법을 설명해주세요.

3. 지속 가능한 iOS 앱 개발을 위한 아키텍처 설계와 모듈화 전략에 대해 설명해주세요.

- Clean Architecture, VIPER 등의 아키텍처 패턴과 적용 방법을 소개해주세요.
- 기능 모듈화, 라이브러리 모듈화 등을 통한 코드 재사용성과 유지보수성 향상 방안을 제시해주세요.
- 의존성 주입, 인터페이스 분리 등의 설계 원칙을 적용한 모듈 간 느슨한 결합 방법을 설명해주세요.

4. 효과적인 iOS 개발자 성장과 학습을 위한 전략과 리소스에 대해 설명해주세요.

- WWDC, 컨퍼런스, 커뮤니티 등을 활용한 최신 기술 트렌드 파악 및 학습 방법을 소개해주세요.
- 오픈소스 프로젝트 기여, 기술 블로그 작성 등을 통한 개발자 브랜딩 및 네트워킹 전략을 제시해주세요.
- 개인 프로젝트, 사이드 프로젝트 등을 통한 실무 역량 강화 및 포트폴리오 구성 방안을 설명해주세요.

5. iOS 앱의 사용자 경험 향상을 위한 UX/UI 디자인 전략과 협업 방안에 대해 설명해주세요.

- 사용자 중심 디자인, 접근성, 일관성 등 UX 디자인 원칙과 적용 방법을 소개해주세요.
- 디자인 시스템, UI 키트 등을 활용한 디자인-개발 협업 및 커뮤니케이션 효율화 방안을 제시해주세요.
- 사용자 피드백 수집, A/B 테스트 등을 통한 데이터 기반 UX 최적화 프로세스를 설명해주세요.

6. 크로스 플랫폼 개발과 iOS 네이티브 개발의 장단점 및 선택 기준에 대해 설명해주세요.

- Flutter, React Native 등 크로스 플랫폼 프레임워크의 특징과 생태계를 소개해주세요.
- 크로스 플랫폼 개발과 네이티브 개발의 성능, 사용자 경험, 개발 효율성 측면에서의 차이점을 비교해주세요.
- 프로젝트 요구사항, 팀 역량, 유지보수 계획 등을 고려한 개발 방식 선택 기준을 제시해주세요.

7. iOS 앱의 수익화 및 비즈니스 모델 전략에 대해 설명해주세요.

- 유료 앱, 인앱 구매, 광고, 구독 등 다양한 수익화 방식의 장단점과 적용 사례를 소개해주세요.
- 사용자 세그먼테이션, 가격 정책, 프로모션 등 수익 극대화를 위한 전략을 제시해주세요.
- 앱 스토어 최적화(ASO), 사용자 유치 및 유지 전략 등 마케팅 관점에서의 고려 사항을 설명해주세요.

8. iOS 개발자로서 지속 가능한 커리어를 위한 목표 설정과 성장 전략에 대해 설명해주세요.

- 기술 리더십, 프로젝트 관리, 아키텍처 설계 등 시니어 개발자로서의 역량 개발 방향을 제시해주세요.
- 커뮤니티 활동, 컨퍼런스 발표, 멘토링 등을 통한 지식 공유와 영향력 확대 방안을 소개해주세요.
- 개발 문화 혁신, 팀 빌딩, 프로세스 개선 등 조직 내 리더십 발휘 방안을 설명해주세요.

9. 앱 개발 프로세스 전반의 자동화 및 효율화를 위한 도구와 방법론에 대해 설명해주세요.

- CI/CD 파이프라인 구축, 자동 빌드 및 배포 등을 위한 도구와 프로세스를 소개해주세요.
- 코드 품질 관리, 정적 분석, 테스트 자동화 등을 위한 도구와 적용 방안을 제시해주세요.
- 애자일 방법론, 스크럼, 칸반 등의 프로젝트 관리 프레임워크와 적용 사례를 설명해주세요.

10. iOS 개발자로서 윤리적이고 사회적 책임감 있는 개발 문화 조성을 위한 방안에 대해 설명해주세요.

- 접근성, 포용성, 다양성 등을 고려한 포용적인 앱 설계와 개발 방향을 제시해주세요.
- 사용자 프라이버시 보호, 데이터 보안, 윤리적 데이터 활용 등의 모범 사례를 소개해주세요.
- 기술의 사회적 영향력을 인지하고 긍정적인 변화를 이끌어낼 수 있는 개발자의 역할과 책임에 대해 설명해주세요.

11. 지속 가능한 오픈소스 생태계 기여 및 관리 방안에 대해 설명해주세요.

- 오픈소스 프로젝트 선택, 기여 방법, 이슈 관리 등 효과적인 오픈소스 참여 전략을 제시해주세요.
- 오픈소스 프로젝트 관리, 라이선스 준수, 커뮤니티 운영 등 오픈소스 메인테이너로서의 역할과 모범 사례를 소개해주세요.

12. iOS 개발자로서 글로벌 시장 진출 및 현지화 전략에 대해 설명해주세요.

- 앱 현지화, 언어 지원, 문화적 고려 사항 등 글로벌 사용자를 위한 개발 전략을 제시해주세요.
- 글로벌 앱 스토어 최적화(ASO), 현지 마케팅, 파트너십 등 해외 시장 진출을 위한 전략과 성공 사례를 소개해주세요.

13. iOS 앱 개발에서 보안과 프라이버시 강화를 위한 모범 사례와 전략에 대해 설명해주세요.

- 안전한 데이터 저장, 네트워크 통신 암호화, 사용자 인증 및 권한 관리 등의 보안 모범 사례를 소개해주세요.
- GDPR, CCPA 등 개인정보 보호 규정 준수를 위한 개발 전략과 고려 사항을 설명해주세요.

14. iOS 개발자로서 지속 가능한 기술 생태계 발전을 위한 커뮤니티 활동과 지식 공유 방안에 대해 설명해주세요.

- 기술 블로그 작성, 컨퍼런스 발표, 스터디 그룹 운영 등 개발자 커뮤니티 활동의 중요성과 참여 방법을 제시해주세요.
- 멘토링, 교육 콘텐츠 제작, 오픈소스 프로젝트 공유 등 지식 공유와 후배 양성을 위한 개발자의 역할과 노력에 대해 설명해주세요.

15. iOS 앱의 지속적인 개선과 유지보수를 위한 데이터 기반 의사결정 방법에 대해 설명해주세요.

- A/B 테스트, 사용자 행동 분석 등 데이터 기반 의사결정을 위한 도구와 방법론을 소개해주세요.
- 앱 애널리틱스 데이터를 활용하여 사용자 경험을 개선하고 새로운 기능을 기획하는 프로세스를 설명해주세요.
