# Jercy's Interview Questions for iOS Developers

iOS 면접 준비와 학습을 돕기 위해 구성된 자료 저장소입니다. 이 저장소는 질문의 깊은 '왜'를 이해하는 데 중점을 두고, 단순한 지식 암기를 넘어선 질문들로 구성되어 있습니다.

답변을 단순히 외우는 것이 아니라, 그 이유를 이해하고 설명할 수 있도록 저장소는 질문에 중점을 두고 있습니다. 저장소는 직접적인 답변을 제공하지 않아, 여러분이 자체적으로 답변을 준비하면서 관련 지식을 탐구하고 확장할 수 있도록 유도합니다.

우선, 기초 지식의 확립이 중요하므로, 면접 질문 학습에 앞서 다음과 같은 권장 학습 자료들을 확인하시길 바랍니다:

1. [CS50](https://www.edwith.org/cs50) - 필수적인 컴퓨터 과학 기초 지식을 배울 수 있는 강좌입니다. (챕터5까지)
2. [모두를 위한 컴퓨터 과학](https://www.boostcourse.org/cs112/joinLectures/41307)_- 자료구조와 알고리즘등 필수적인 개념을 알려주는 강좌입니다.
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

# NEW
새로운 질문 리스트는 [여기](https://github.com/JeaSungLEE/iOSInterviewquestions/blob/master/newREADME.md)에서 확인할 수 있습니다.

## iOS
- Bounds 와 Frame 의 차이점을 설명하시오.
- 실제 디바이스가 없을 경우 개발 환경에서 할 수 있는 것과 없는 것을 설명하시오.
- 앱의 콘텐츠나 데이터 자체를 저장/보관하는 특별한 객체를 무엇이라고 하는가?
- 앱 화면의 콘텐츠를 표시하는 로직과 관리를 담당하는 객체를 무엇이라고 하는가?
- App thinning에 대해서 설명하시오.
###
- 앱이 시작할 때 main.c 에 있는 UIApplicationMain 함수에 의해서 생성되는 객체는 무엇인가?
- @Main에 대해서 설명하시오.
- 앱이 foreground에 있을 때와 background에 있을 때 어떤 제약사항이 있나요?
- 상태 변화에 따라 다른 동작을 처리하기 위한 앱델리게이트 메서드들을 설명하시오.
- 앱이 In-Active 상태가 되는 시나리오를 설명하시오.
- scene delegate에 대해 설명하시오.
- UIApplication 객체의 컨트롤러 역할은 어디에 구현해야 하는가?
- App의 Not running, Inactive, Active, Background, Suspended에 대해 설명하시오.
###
- iOS 앱을 만들고, User Interface를 구성하는 데 필수적인 프레임워크 이름은 무엇인가?
- Foundation Kit은 무엇이고 포함되어 있는 클래스들은 어떤 것이 있는지 설명하시오.
- Delegate란 무엇인지 설명하고, retain 되는지 안되는지 그 이유를 함께 설명하시오.
- NotificationCenter 동작 방식과 활용 방안에 대해 설명하시오.
- UIKit 클래스들을 다룰 때 꼭 처리해야하는 애플리케이션 쓰레드 이름은 무엇인가?
- App Bundle의 구조와 역할에 대해 설명하시오.
- 모든 View Controller 객체의 상위 클래스는 무엇이고 그 역할은 무엇인가?
- 자신만의 Custom View를 만들려면 어떻게 해야하는지 설명하시오.
- View 객체에 대해 설명하시오.
- UIView 에서 Layer 객체는 무엇이고 어떤 역할을 담당하는지 설명하시오.
- iOS에서 뷰(View)와 레이어(Layer)의 개념과 차이점에 대해 설명해보세요.
- UIWindow 객체의 역할은 무엇인가?
- UINavigationController 의 역할이 무엇인지 설명하시오.
- TableView를 동작 방식과 화면에 Cell을 출력하기 위해 최소한 구현해야 하는 DataSource 메서드를 설명하시오.
- 하나의 View Controller 코드에서 여러 TableView Controller 역할을 해야 할 경우 어떻게 구분해서 구현해야 하는지 설명하시오.
- setNeedsLayout와 setNeedsDisplay의 차이에 대해 설명하시오.
- stackView의 장점과 단점에 대해서 설명하시오.
###
- NSCache와 딕셔너리로 캐시를 구성했을때의 차이를 설명하시오.
- URLSession에 대해서 설명하시오.
- prepareForReuse에 대해서 설명하시오.
- 다크모드를 지원하는 방법에 대해 설명하시오.
- ViewController의 생명주기를 설명하시오.
- TableView와 CollectionView의 차이점을 설명하시오.
- Dynamic Library와 Static Library의 차이점에 대해 설명해보세요.

## Autolayout
- 오토레이아웃을 코드로 작성하는 방법은 무엇인가? (3가지)
- hugging, resistance에 대해서 설명하시오.
- Intrinsic Size에 대해서 설명하시오.
- 스토리보드를 이용했을때의 장단점을 설명하시오.
- Safearea에 대해서 설명하시오.
- Left Constraint 와 Leading Constraint 의 차이점을 설명하시오.
- Auto Layout과 Frame-based Layout의 차이점은 무엇인가요?
- 성능 향상을 위해 어떤 디버깅 도구를 사용할 수 있나요? 각각의 디버깅 도구는 어떤 상황에서 사용하는 것이 좋나요?

## Swift
- struct와 class와 enum의 차이를 설명하시오.
- class의 성능을 향상 시킬수 있는 방법들을 나열해보시오.
- Copy On Write는 어떤 방식으로 동작하는지 설명하시오.
- Convenience init에 대해 설명하시오.
- AnyObject에 대해 설명하시오.
- Optional 이란 무엇인지 설명하시오.
- Struct 가 무엇이고 어떻게 사용하는지 설명하시오.
- Subscripts에 대해 설명하시오.
- String은 왜 subscript로 접근이 안되는지 설명하시오.
- instance 메서드와 class 메서드의 차이점을 설명하시오.
- class 메서드와 static 메서드의 차이점을 설명하시오.
- Delegate 패턴을 활용하는 경우를 예를 들어 설명하시오.
- Singleton 패턴을 활용하는 경우를 예를 들어 설명하시오.
- KVO 동작 방식에 대해 설명하시오.
- Delegates와 Notification 방식의 차이점에 대해 설명하시오.
- 멀티 쓰레드로 동작하는 앱을 작성하고 싶을 때 고려할 수 있는 방식들을 설명하시오.
- MVC 구조에 대해 블록 그림을 그리고, 각 역할과 흐름을 설명하시오.
- 프로토콜이란 무엇인지 설명하시오.
- Protocol Oriented Programming과 Object Oriented Programming의 차이점을 설명하시오.
- Hashable이 무엇이고, Equatable을 왜 상속해야 하는지 설명하시오.
- mutating 키워드에 대해 설명하시오.
- 탈출 클로저에 대하여 설명하시오.
- Extension에 대해 설명하시오.
- Extension 내부에서 함수를 override할 수 있는지 설명하시오.
- 접근 제어자의 종류엔 어떤게 있는지 설명하시오.
- defer란 무엇인지 설명하시오.
- defer가 호출되는 순서는 어떻게 되고, defer가 호출되지 않는 경우를 설명하시오.
- property wrapper에 대해서 설명하시오.
- Generic에 대해 설명하시오.
- some 키워드에 대해 설명하시오.
- Result타입에 대해 설명하시오.
- Codable에 대하여 설명하시오.
- Closure에 대하여 설명하시오.
- Closure와 함수와의 관계에 대해 설명하시오.
- Optional Chaining과 nil-coalescing operator(??)의 차이점과 사용 시 주의사항은 무엇인가요?
- Swift에서 Async/Await 기능이 도입되기 전에, 비동기(Asynchronous) 작업을 처리하는 방법에는 어떤 것들이 있나요?
- 타입 변환(Type Casting)과 다형성(Polymorphism)에 대해 설명해보세요.
- Swift에서 타입 안전성(type safety)은 어떤 방식으로 보장되나요?

## ARC
- ARC란 무엇인지 설명하시오.
- Retain Count 방식에 대해 설명하시오.
- Strong 과 Weak 참조 방식에 대해 설명하시오.
- 순환 참조에 대하여 설명하시오.
- 강한 순환 참조 (Strong Reference Cycle) 는 어떤 경우에 발생하는지 설명하시오.

## Functional Programming
- 순수함수란 무엇인지 설명하시오.
- 함수형 프로그래밍이 무엇인지 설명하시오.
- 고차 함수가 무엇인지 설명하시오.
- Swift Standard Library의 map, filter, reduce, compactMap, flatMap에 대하여 설명하시오.
- Either type이란?

## Architecture
- MVVM, MVI, Ribs, VIP 등 자신이 알고있는 아키텍쳐를 설명하시오.
- 의존성 주입에 대하여 설명하시오.

## SwiftUI
- @State가 어떻게 동작하는지 설명하시오.

## Combine
- PassthroughSubject에 대해서 설명하시오
- @Published에 대해서 설명하시오
- AnyCancellable에 대해서 설명하시오
- sink에 대해서 설명하시오
- throttle과 debounce의 차이점을 설명하시오.
- Data를 Binding 하는 방법에 대해서 설명하시오.

## Concurrency
### GCD, NSOperation
- NSOperationQueue 와 GCD Queue 의 차이점을 설명하시오.
- GCD API 동작 방식과 필요성에 대해 설명하시오.
- Global DispatchQueue 의 Qos 에는 어떤 종류가 있는지, 각각 어떤 의미인지 설명하시오.

### Swift Concurrency
- @MainActor는 언제 이용하는가?
- task동작 방식과 gcd, nsoperation과의 차이점을 설명하시오.


# Optional
아래부터는 추가로 공부를 하면 좋을 내용들입니다.

Objective-c나 rx는 회사, 팀마다 사용하는곳이 차이가있고 신입이나 주니어기준으로 필수라고 여겨지지않기에 옵셔널에 추가하였습니다.

## Rx
- Reactive Programming이 무엇인지 설명하시오.
- RxSwift를 왜 사용하는지 설명하시오.
- RxSwift의 단점을 설명하시오.
- RxSwift에서 Hot Observable과 Cold Observable의 차이를 설명하시오.
- Subject의 종류와 차이점에 대해 설명하시오.
- Subject와 Driver의 차이를 설명하시오.
- Single, Completable, Maybe의 차이점에 대해 설명하고, 언제 적용하면 좋을지 설명하시오.

## MRC
- ARC 대신 Manual Reference Count 방식으로 구현할 때 꼭 사용해야 하는 메서드들을 쓰고 역할을 설명하시오.
- retain 과 assign 의 차이점을 설명하시오.
- 특정 객체를 autorelease 하기 위해 필요한 사항과 과정을 설명하시오.
- Autorelease Pool을 사용해야 하는 상황을 두 가지 이상 예로 들어 설명하시오. 
- 다음 코드를 실행하면 어떤 일이 발생할까 추측해서 설명하시오.
Ball *ball = [[[[Ball alloc] init] autorelease] autorelease];

## Advanced
- method swizzling이 무엇이고, 어떨 때 사용하는지 설명하시오.
- NSCoder 클래스는 어떤 상황에서 어떻게 써야 하는지 설명하시오.
- Responder Chain 구조에 대해 설명하고, First Responder 역할에 대해 설명하시오.
- NSObject부터 UIButton 까지 상속 과정의 계층과 역할을 설명하시오.
- shallow copy와 deep copy의 차이점을 설명하시오.
- Push Notification 방식에 대해 설명하시오.
- Foundation 과 Core Foundation 프레임워크의 차이점을 설명하시오.
- NSURLConnection 에서 사용하는 Delegate 메서드들에 대해 설명하시오.
- Synchronous 방식과 Asynchronous 방식으로 URL Connection을 처리할 경우의 장단점을 비교하시오.
- Plist 파일 구조와 Plist 파일에 저장된 데이터를 다루기 적합한 클래스를 설명하시오.
- Core Data와 Sqlite 같은 데이터 베이스의 차이점을 설명하시오.
- JSON 데이터를 처리하는 방식과 파서, 객체 변환 방식에 대해 설명하시오.
- 웹 서버와 HTTP 연결을 사용해서 데이터를 주거나 받으려면 사용해야 하는 클래스와 동작을 설명하시오.
- Protocol에서는 왜 var만 되는지 설명하시요.
- DispatchQueue.main.sync를 사용하는 상황을 설명하시오.
- Run Loops에 대해 설명하시오.

## Objective-C
- Swift의 클로저와 Objective-C의 블록은 어떤 차이가 있는가?
- Mutable 객체과 Immutable 객체는 어떤것이 있는지 예를 들고, 차이점을 설명하시오.
- dynamic과 property 의미와 차이를 설명하시오.
- @property로 선언한 NSString* title 의 getter/setter 메서드를 구현해보시오.
- @property에서 atomic과 nonatomic 차이점을 설명하고, 어떤것이 안전한지, 어느것이 기본인지 설명하시오.
- @property로 선언한다는 것의 의미를 설명하고, .h에 넣을 경우와 .m에 넣을 경우 차이점을 설명하시오.
- -performSelector:withObject:afterDelay: 메시지를 보내면 인자값의 객체는 retain되는가? 그 이유를 함께 설명하시오.
- Objective-C 에서 캡슐화된 데이터를 접근하기 위한 방법들을 설명하시오.
- Fast Enumeration 이란 무엇인지 설명하시오. 
- unnamed category 방식에 대해 설명하시오.
- Category 확장과 Subclass 확장의 차이점을 설명하시오.
- Category 방식에 대해 설명하시오.
- Objective-C 에서 Protocol 이란 무엇인지 설명하시오.
- Objective-C++ 방식이 무엇인지 설명하고, 어떤 경우 사용해야 하는지 설명하시오.
