# Swift_CodeSpec
Swift code specification for project

# 使用// MARK: - 进行分组，一般规则如下
```
import SomeExternalFramework

class FooViewController : UIViewController, FoobarDelegate {

    let foo: Foo

    private let fooStringConstant = "FooConstant"
    private let floatConstant = 1234.5

    // MARK: Lifecycle

    // Custom initializers go here

    // MARK: View Lifecycle

    override func viewDidLoad() {
        super.viewDidLoad()
        // …
    }

    // MARK: Layout

    private func makeViewConstraints() {
        // …
    }

    // MARK: User Interaction

    func foobarButtonTapped() {
        // …
    }

    // MARK: FoobarDelegate

    func foobar(foobar: Foobar didSomethingWithFoo foo: Foo) {
        // …
    }

    // MARK: Additional Helpers

    private func displayNameForFoo(foo: Foo) {
        // …
    }

}
```
# 参考
* [The Swift API Design Guidelines](https://swift.org/documentation/api-design-guidelines/)
* [The Swift Programming Language](https://developer.apple.com/library/prerelease/ios/documentation/swift/conceptual/swift_programming_language/index.html)
* [Using Swift with Cocoa and Objective-C](https://developer.apple.com/library/prerelease/ios/documentation/Swift/Conceptual/BuildingCocoaApps/index.html)
* [Swift Standard Library Reference](https://developer.apple.com/reference/swift)
* [Official raywenderlich.com Swift Style Guide](https://github.com/raywenderlich/swift-style-guide)
* [ios-good-practices](https://github.com/futurice/ios-good-practices#stores)
