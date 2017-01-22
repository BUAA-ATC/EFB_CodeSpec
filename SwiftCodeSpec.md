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
